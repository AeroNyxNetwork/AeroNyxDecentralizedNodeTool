# AeroNyxTools
Tools for deploying AeroNyxNode services.

# Deploy
## Download source
```shell 
git clone https://github.com/AeroNyxNetwork/AeroNyxDecentralizedNodeTool.git
cd AeroNyxDecentralizedNodeTool/
```

## Deploy Environment
```shell
python3 main.py -I
```

## Register node
```shell
python3 main.py --set_register --owner=Your client public key --name=node_name
```
- owner--Owner of node (You can copy the pubkey from the AeroNyx client as the owner of the node)
- name--Name of node

## Run service
```sheel
python3 main.py --start
```

# More
```
-h, --help     show this help message and exit
-I, --install  install dependent environment
-U, --update   update all
-p, --private  show private key
-P, --public   show public key
--start        start the service
--stop         stop the service
-v, --version  show program's version number and exit
```
