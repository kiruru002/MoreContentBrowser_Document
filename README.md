
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

About the Settings  

The settings can be found under "Editor Preferences" and "Plugins"  

![b.png](images/b.png)  

| Name | Effect | Default value |
|-|-|-|
| Additional Content Browser Num | The number of ContentBrowsers added by this plugin | 4 |

## How to Install

This plugin is available for Unreal Engine 5.7 and later versions.  

To install this plugin, place it in the “Plugins” folder located in your engine folder.  
If you can't find the “Plugins” folder, create one yourself.  

![c.png](images/c.png)  

## How to Build

Since this is a code plugin, you'll need to build it after installation.  

This site also has detailed information. → [ue5study.com](https://ue5study.com/how/unrealengine-packaging-visualstudio-settings/)  

Click here for Visual Studio plans. → [Visual Studio Community](https://visualstudio.microsoft.com/vs/community/)

### If a solution file (.sln) is not generated

If you receive an error like the one below, you can resolve it by adding an empty source code file to the project.  

> This project does not have any source code. You need to add C++ source files to the project from the Editor before you can generate project files.  
> For projects without source code, you must first add source code.  

Select \[New C++ Class\] from the Editor to add an empty C++ class or similar to the project.  
Select Tools → New C++ Class...  
Click None → Next → Create Class  
Click OK → Yes to create the class  
