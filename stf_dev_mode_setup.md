
# Setup Development Mode.

## Use this guide if you want to setup an stf instance/service system wide in development mode.

### Disclaimer:
 - The following guide was used on a machine running Ubuntu server 16.04
 - You can provide feedback in order to increase the utility of the script.
 - After the installation the host machine will reboot.

##Install Steps
 1. **Locate the file at this repo:** src/utils/install_stf_dev.sh
 2. Copy it into your target server
 3. Enable the executable flag
 
 ```
 chmod +x install_stf_dev.sh
 ```
 4. Run it with admin privileges to install the dependencies
 
 ```
 sudo ./install_stf_dev.sh
 ```

##Run steps
1. **Locate the file at this repo:** src/utils/launch_stf.sh 
2. Copy it into your target server
3. Enable the executable flag

```
chmod +x launch_stf.sh
```
4. Run it

```
./launch_stf.sh
```


The service will be raised over the shell session on foreground mode.


