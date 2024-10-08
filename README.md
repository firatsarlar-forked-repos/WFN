# WFN (Windows Firewall Notifier)

![](https://img.shields.io/badge/.NET-7.0-blue)
![](https://img.shields.io/badge/UI-WPF-green)
![](https://img.shields.io/badge/Status-Active-green) 

[![Release](https://github.com/wokhan/WFN/actions/workflows/release.yml/badge.svg)](https://github.com/wokhan/WFN/actions/workflows/release.yml)
[![Nightlies](https://github.com/wokhan/WFN/actions/workflows/nightly.yml/badge.svg)](https://github.com/wokhan/WFN/actions/workflows/nightly.yml)

## 🗃️ Project Description
WFN started as a hobby around 2010 and is an "extension" to the embedded Windows firewall, offering real time connections monitoring, connections map, bandwidth usage monitoring...

Its main feature being the Notifier alert itself, which tells you about outgoing connections attempts and allows you to allow or block them, either permanently or temporarily. 

It has been made open source a few years ago.  

Please read the documentation about the features and limitation of WFN. 

Especially note that WFN is **not** a firewall itself!  

## 🗄️ Releases

All versions are available in the [releases](https://github.com/wokhansoft/WFN/releases) page. 

**Nightly**

This version is automatically built on each PR merge, meaning that you'll get the most recent build. With the most recent features... and bugs 😁

**2018.05 - v2.5 beta**

Version 2.5 should be used (and should have been since its release, while a beta) as it fixes a lot of issues, has been modernized (both the code and the UI), is faster, more reliable... 
I'm keeping v2.0 in this list though as it was the mainly used version for years. 

**2018.03.03 - v2.0 beta 3**  

The latest release for version 2.0, kept here if you encounter issues with 2.5.

**Keep in mind, beta versions are work in progress! Read the full description page before downloading!**  

## 🧰 Requirements  
WFN requires Windows 7 or later (with Microsoft .NET 4.5.2 or higher for version 2.0, version 2.5 comes as a standalone version which embeds the proper framework, i.e. .NET 6.0+). 

Windows Server 2008 or later are not officially supported, but WFN should work fine on them.  

## 🖼️ Features / Screenshots

**Screenshots are from v2.0 and are outdated. This page will be updated soon. **

**Connections listing**  
![](http://wokhan.online.fr/progs/wfn/connections.PNG)

**Real time connections mapping with routes**  
![](http://wokhan.online.fr/progs/wfn/map.PNG)

**Bandwidth monitoring**  
![](http://wokhan.online.fr/progs/wfn/bandwidth.PNG)

**Adapters informations**  
![](http://wokhan.online.fr/progs/wfn/adapters.PNG)

**Windows Firewall status management**  
![](http://wokhan.online.fr/progs/wfn/firewallstatus.PNG)

**Notification popup for unknown outgoing connections (optional)**  
![](http://wokhan.online.fr/progs/wfn/notifier.PNG)

## 🔎 Additional information
- You can refer to the [roadmap](ROADMAP.md) to have a glance at what's coming next.
- If you want to contribute, please refer to our [contributing guide](CONTRIBUTING.md).
- You can also use the Sponsor button in GitHub if you want to support the project with a donation. 

## 🙏 Thanks
Thanks to everyone who contributed and donated, and of course to people who will!
