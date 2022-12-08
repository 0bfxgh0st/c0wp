# c0wp
c0wp is a simple script to discover ipv4/ipv6 hosts in the network based on ping command.  

## Install

```
sudo cp -r c0wp /usr/bin/ && sudo chmod +x /usr/bin/c0wp
```

```
 ______________________
< M0x0 /proc/net/arp ! >                                                                                                                                                                           
 ----------------------                                                                                                                                                                            
        \   ^__^                                                                                                                                                                                   
         \  (**)\_______                                                                                                                                                                           
            (__)\       )\/\                                                                                                                                                                       
             U  ||----w |                                                                                                                                                                          
                ||     ||                                                                                                                                                                          
                                                                                                                                                                                                   
+ host discover
+ ping command based                                                                                                                                                                               

Usage:

c0wp 10.0.2.1                    single host ipv4 scan
c0wp fe80::a00:27ff:fe7b:8cd7    single host ipv6 scan
c0wp 10.0.2.1-40                 custom range ipv4 scan (from 10.0.2.1 to 10.0.2.40)

Last positional argument option:

--fast      to faster scan

Fast scan example:

c0wp 10.0.2.1-200 --fast
```
