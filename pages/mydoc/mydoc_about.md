---
title: About the theme's author
keywords: documentation theme, jekyll, technical writers, help authoring tools, hat replacements
last_updated: July 3, 2016
tags: [getting_started]
summary: "I have used this theme for projects that I've worked on as a professional technical writer."
sidebar: mydoc_sidebar
permalink: mydoc_about.html
folder: mydoc
---
# **Initial setup**

**Make sure to update the list of packages**

**For window**

`Select Start > Settings > Update & Security > Windows Update, and then select Check for updates`

**For Linux** 

`Apt update `

**For mac**

`Softwareupdate-I`



**Retrieve content from web servers**

**For windows**

`C:\> Get-WebsitesServer`

**For Linux**

`Apt install y –wget`

**For Mac**

In the Finder on your Mac, `choose Go > Connect to Server.`



**Install prebuilt OpenJDK packages**

**For Windows**

`"openjdk-11.0.1_windows-x64_bin.zip": https://download.java.net/java/GA/jdk11/13/GPL/openjdk-11.0.1_windows-x64_bin.zip `

**For Linux**

`Apt install –y git OpenJDK-11-jdk`



## Installation

**For Windows, Mac, Linux**

Sample App New-life-experience can be cloned with framework 

`git clone http://github.sec.samsung.net/New-life-Experience/healthcare-research-kit.git `

Setup Username and password 

**Install the latest version of android studio**

**For Windows**

`https://developer.android.com/studio`

**For Linux**

`Wget[http://redirector.gvtI.com/edgedl/android/studio/ide-zips/2021.2.1.16/andoid-studio-2021.2.1.16-linux.tar.gz]` 

**For Mac**

`**https://developer.android.com/studio/index.html#downloads**.` and install in ox



### **Building** 

Scratch plain text file from android studio 

`Ctrl + Alt + shift + Insert` 

 **Kit and External** 

This sample application depends on SDK modules so it must have kit and external 

`Dependencies { `

`Implementation {project (“: kit”))` 

​               `{project (“: external”)) `

​              ` }` 

 **Google-Services-Json** 

The sample application uses firebase so this has google-services-json 

`“Client”: [ `

`{“package_name”: “con.samsung.healthcare.kitsample”} `

 

 **Project Id for App** 

This sample App interacts with research platform for health data upload , task sync and result upload so we have to set project id 

`String name=”research_project_id”>1</string> `

 

**Run sample App on real Samsung device** 

Can’t Run Sample App on emulator so run it on real device 

 

{% include links.html %}
