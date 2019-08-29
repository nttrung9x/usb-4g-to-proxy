## How to build youself 4g proxies

Allproxy provides a easy to make your 4g proxy, it suporrts most of platform, and easy to use.

[![DEMO](https://img.youtube.com/vi/eQ9m05CQR8U/0.jpg)](https://www.youtube.com/watch?v=eQ9m05CQR8U)

## Android
1. Download and Install allproxy app from google play.
2. Click connect button, you will get a proxy address, your phone network is published with this address.

## Windows/Macos/Raspeberry/Other Linux
1. Change the server address in conf_client.yaml or just use my free servers
2. Open allproxyC

## Install PC client as server
1. You need to assign [execute] permission for allproxyC in linux env
```bash
chmod +x allproxyC
```
2. Install it as daemon service 
```bash
allproxyC -i
```
3. Check its status
```bash
allproxyC -q
```

## Help
You can get all valid parameters by:
```bash
allproxyC -h
```
Valid Options:

  -h    this help

  -i    install as deamon service

  -q    query the service status

  -s signal
        send signal to IgerslikeProxy: stop, restart, start

  -server string
        The server address

  -u    uninstall deamon service

  -userId string
        The user id
        
  -w string
        The working directory,default is the current directory

## Free Server
+ conn2.trs.ai  (China)
+ conn4.trs.ai   (US)
+ conn3.trs.ai   (My test env, so not stable)
