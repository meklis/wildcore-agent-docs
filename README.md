# WildcoreDMS documentation
Device management system     
Screens - [link](./wca/agent-screens.md)

## Who is this tool for?
- **For installer** - for monitor realtime situation with devices in the field 
- **For operator** - for fast detecting problem when user/subscriber calling
- **For engineer** - for monitoring and notifications about problems (for example - downing BGP session) 
- **For the provider** - to reduce the response time to diagnostics

## Basic features
- Working from box. No more searching OIDs, commands and read documentation.   
- Adaptive web interface for desktop, tablet or phone
- User permissions by groups, with allow creating custom groups
- Working with devices over telnet, SNMP or Mikrotik API (for device with RouterOS)
- Working in docker
- Integrated with prometheus
- Caching device information
- RestAPI support
- CLI support

## Supported vendors
- C-Data (Some OLTs)
- ZTE (OLT C320, FW 2.1)
- D-Link (Some DES/DGS switches)
- Mikrotik (All routers based on RouterOS)

[Full list of supported devices](https://github.com/meklis/switcher-core/blob/master/docs/DEVICES.md)      

Also, you can request add more devices, if you need. Please, contact with contact@wildcore.tools or in our telegram channel.  
    
If you want to add some specific devices, you can fork [switcher-core](https://github.com/meklis/switcher-core) library and add devices.
And we will implement them to wildcoreDMS.    


## Requirements:
* Access to internet from static IP (v4)
* System
  * 2cores+ CPU
  * 4Gb+ memory
  * 50Gb+ SSD
* OS
  * Linux (Ubuntu/Debian)
  * MacOS (not tested)
  * WSL2 (linux on windows, not tested)
* docker (>=20.10) - [Install docs](https://docs.docker.com/engine/install/)

## Before start
Request agent on web site - https://wildcore.tools or contact over email support@wildcore.tools  .    
In response we send unique key for you agent (key required for installation).

## Installation
Please use `wca-tool` for first installation, docs -  [wca-tool](/wca-tools/README.md)

## Updates 
Please use `wca-tool` for updates, docs -  [wca-tool](/wca-tools/README.md)

### Migration table (for some upgrades)
* 0.4.x -> 0.5.x - [recomendations](migrates/0.4.x_0.5.x.md)

## Components
* [Events (events)](wca/components/events.md) 
* [Alerts (alerts)](wca/components/alerts.md) 


## Contacts
Group: [@wildcore_dms_channel](https://t.me/wildcore_dms_channel)   
News: [@wildcore_dms_news](https://t.me/wildcore_dms)   
Email: support@wildcore.tools   
