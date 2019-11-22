# UniBitX-Blockchain-Explorer
Block explorer for UniBitX CryptoNote based cryptocurrency.

#### Installation

1) It takes data from daemon unibitxd. It should be accessible from the Internet. Run unibitxd with open port as follows:
```bash
./unibitxd --enable-cors="*" --enable-blockexplorer --rpc-bind-ip=0.0.0.0 --rpc-bind-port=11898
```
2) Just upload to your website and change 'api' variable in config.js to point to your daemon.


### Note

A lot of this code is from the great Karbovanets/Karbowanec Blockchain Explorer and Turtlecoin Blockchain Explorer
