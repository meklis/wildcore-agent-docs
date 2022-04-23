# First installation *wildcore* over wca-tool
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

## Install wildcore agent
### Install wca-tool
1. Run this command to download the current release of wca tool:
```shell
sudo curl -L "https://releases.wildcore.tools/wca-tool/latest/wca-tool-$(uname -s)-$(uname -m)" -o /usr/local/bin/wca-tool
```
2. Apply executable permissions to the binary: 
```shell
sudo chmod +x /usr/local/bin/wca-tool
```
3. Check wca-tool is installed
```shell 
wca-tool --version
```
Example output:
```shell
wca-tool version 0.0.1 
```

### Install agent 
@TODO 