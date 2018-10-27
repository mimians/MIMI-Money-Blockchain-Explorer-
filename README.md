# MIMI Money Blockchain Explorer
Block explorer for MIMI Money CryptoNote based cryptocurrency.

#### Installation

1) It takes data from daemon MIMIMoneyd. It should be accessible from the Internet. Run MIMIMoneyd with open port as follows:
```bash
./MIMIMoneyd --enable-cors="*" --enable_blockexplorer --rpc-bind-ip=0.0.0.0 --rpc-bind-port=39700
```
2) Just upload to your website and change 'api' variable in config.js to point to your daemon.


### Development
Devs:
Copyright (c) 2018 MIMI Money Developers

### Note

A lot of this code is from the great Karbovanets/Karbowanec-Blockchain-Explorer
