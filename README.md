# WildcoreDMS documentation
Device management system 
Screens - [link](./wca/agent-screens.md)

## Who is this tool for?
- **For installer** - for monitor realtime situation with devices in the field 
- **For operator** - for fast detecting problem when user/subscriber calling
- **For engineer** - for monitoring and notifications about problems (for example - downing BGP session) 
- **For the provider** - to reduce the response time to diagnostics

## Basic features
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
- ZTE (OLT C320)
- D-Link (Some DES/DGS switches)
- Mikrotik (All routers based on RouterOS)

[Full list of supported devices](https://github.com/meklis/switcher-core/blob/master/docs/DEVICES.md)

## Requirements:
* System
  * 2cores+ CPU
  * 4Gb+ memory
  * 50Gb+ SSD
* OS
  * Linux (Ubuntu/Debian)
  * MacOS
  * WSL (linux on windows)
* docker (>=20.10)
* docker-compose (>=2.4)

## Before start
Request agent on web site - https://wildcore.tools or contact over email support@wildcore.tools  .    
In response we send unique key for you agent (key required for installation).

## Installation
Please use `wca-tool` for first installation, docs -  [wca-tool](/wca-tools/README.md)

## Migration table 
* 0.4.x -> 0.5.x - [recomendations](migrates/0.4.x_0.5.x.md)

## Contacts
Group: [@wildcore_dms_channel](https://t.me/wildcore_dms_channel)   
News: [@wildcore_dms_news](https://t.me/wildcore_dms)   
Email: support@wildcore.tools   
