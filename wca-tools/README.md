# WCA-TOOL - Utility for working with wildcore DMS

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
wca-tool version 0.0.6
```

### Install agent 
1. Run command over sudo or root   
```shell
sudo wca-tool --key=<YOU AGENT UNIQUE KEY> install
```
After installation you can access to DMS over http://<SERVER_IP>:8088 or over cli (type `wca --help` for info)


### Update/Upgrade agent 
```shell
sudo wca-tool update 
```

### Backup/Restoring agent
- For create backup - run command:
```shell
sudo wca-tool backup
```
backup will be created in /opt/wildcore-dms/backups with automatic name (yyyymmddhhii.tar.gz)

- For restoring from backup - run command: 
```shell
sudo wca-tool restore --name <name of archive, without extension (.tar.gz)>
```
