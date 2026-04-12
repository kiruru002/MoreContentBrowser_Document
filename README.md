
# MoreContentBrowser_Document

## Table of Content

- [MoreContentBrowser\_Document](#morecontentbrowser_document)
	- [Table of Content](#table-of-content)
	- [Overview](#overview)
	- [Plugin settings](#plugin-settings)
	- [How to Install](#how-to-install)
	- [How to Build](#how-to-build)
		- [If a solution file (.sln) is not generated](#if-a-solution-file-sln-is-not-generated)

## Overview

This is a plugin that increases the number of Content Browser panels in UE5.  

![a.png](images/a.png)  

## Plugin settings

The settings can be found under:
"Editor Preferences" → "Plugins"

![b.png](images/b.png)  

| Name | Effect | Default value |
|-|-|-|
| Additional Content Browser Num | The number of ContentBrowsers added by this plugin | 4 |

## How to Install

This plugin is available for Unreal Engine 5.7 and later.  

To install it, place the plugin in the "Plugins" folder inside your project directory.  
If the "Plugins" folder does not exist, create it manually.  

![c.png](images/c.png)  

## How to Build

Since this is a code plugin, you'll need to build it after installation.  

For more details, see: [ue5study.com](https://ue5study.com/how/unrealengine-packaging-visualstudio-settings/)  

Download Visual Studio here: [microsoft.com](https://visualstudio.microsoft.com/vs/community/)

### If a solution file (.sln) is not generated

If you see an error like this:

> This project does not have any source code. You need to add C++ source files to the project from the Editor before you can generate project files.  
> For projects without source code, you must first add source code.  

You can fix it by adding an empty C++ class to the project.  

Steps:

- Select "New C++ Class" in the Editor
- Tools → New C++ Class...
- Choose "None" → Next → Create Class
- Click OK → Yes
