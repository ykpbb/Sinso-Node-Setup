# Sinso-Node-Setup

## System Requirements
- CPU >= 4 cores
- Memory >= 8G
- Storage disks >=200G

## SETUP
```
wget https://github.com/sinsoio/mine_publish/archive/refs/tags/v1.1.6.tar.gz
tar -xf v1.1.6.tar.gz
cd mine_publish-1.1.6/ && chmod 755 sinso
```

### Run Sinso
```
./sinso start --full-node=true --swap-endpoint=https://data-seed-pressc-3.sinso.io
```

After successfully starting the node, the program will prompt "Welcome to Sinso"

![image](https://user-images.githubusercontent.com/101433838/177037638-a685a7ec-44ef-46d8-9a83-2c1bd92ea3c7.png)

1. In "Password": Enter the node password (Please memorize the password, it will be needed in subsequent node restarts).
2. In "Privatekey": Please enter the private key corresponding to the node address.

![image](https://user-images.githubusercontent.com/101433838/177037671-137902eb-2301-457a-8e11-c54eb8cb30fe.png)

After the above steps are successfully completed, wait to connect to other nodes, and the following similar prompt appears, indicating that the connection is successful.

![image](https://user-images.githubusercontent.com/101433838/177037684-c9d69e8a-6fef-485d-b08d-3c63a7c7d1fe.png)
