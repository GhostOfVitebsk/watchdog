# WATCHDOG
## Traffic sniffing program for Linux OS 

Release version: [0.1](https://github.com/GhostOfVitebsk/watchdog)

## Downloading and preparing
```
git clone https://github.com/GhostOfVitebsk/watchdog
cd watchdog
make
sudo make install
```

## Dependency resolution

```
sudo apt install libpcap-dev
```

## Using
```
sudo watchdog
```
You need to use "sudo", because the link layer requires this. All captured data will be written to "sniff.log" in the directory from which the program was called.

## Releases 
* version 0.1:
  
  Simply sniffs IPv4 and IPv6 packets, logs protocol, size, source address and destination address.


### Developed by
* Makar Semyonov: [telegram](https://t.me/makarsemyonov2), [github](https://github.com/GhostOfVitebsk)
