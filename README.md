# nethues-linux-openvpn-easy

> This repo contain demo files to quickly connect to vpn without entering multiple password on linux OS

it assume that all files inside this repo exists inside same folder = Desktop

#### Below steps are require only once

1. move all file inside Desktop Folder except `README.md`
2. replace file `username__ssl_vpn_config.ovpn` with orginal file provided by Nethes's Admin, update `vpn-connect.py` with correct `ovpn` file name
3. udpate vpn-pass.txt with correct credentials
4. add executable permission to vpn-connect.py
    ```
    cd Desktop
    sudo chmod +x vpn-connect.py
    ```
    
All done, Now you can connect to vpn by just execulte `vpn-connect.py` on cli, enter only system login password if it ask for it
```
cd Desktop
./vpn-connect.py
```
   
