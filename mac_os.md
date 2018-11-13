### Install Homebrew 
``` $ /usr/bin/ruby -e "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/master/install)"```
Homebrew is an package manager for mac, for additional software using the cli  
Eg ``` brew cask install firefox```

### Add Shortcuts 

For example to check my internet connection is okay. Try to ping google dns
```
$ vi ~/.bash_profile
  #Aliases
#Custom commands
alias check-net="ping -c 5 www.google.com"

$ source ~/.bash_profile

$ check-net
PING www.google.com (172.217.6.132): 56 data bytes
64 bytes from 172.217.6.132: icmp_seq=0 ttl=46 time=43.752 ms
64 bytes from 172.217.6.132: icmp_seq=1 ttl=46 time=43.859 ms
64 bytes from 172.217.6.132: icmp_seq=2 ttl=46 time=43.923 ms
64 bytes from 172.217.6.132: icmp_seq=3 ttl=46 time=43.797 ms
64 bytes from 172.217.6.132: icmp_seq=4 ttl=46 time=43.870 ms

--- www.google.com ping statistics ---
5 packets transmitted, 5 packets received, 0.0% packet loss
round-trip min/avg/max/stddev = 43.752/43.840/43.923/0.060 ms
```
### Install vagrant 
``` 
$ brew cask install virtualbox
$ brew cask install vagrant 
```
If you want you can install vagrant manager - I dont have this installed 
``` 
$brew cask install vagrant-manager
```
