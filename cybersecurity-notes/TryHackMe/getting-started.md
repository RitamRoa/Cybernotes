# Getting Started with TryHackMe

## Introduction

This document serves as a reflection on my learning journey through TryHackMe. It captures key insights, experiences, and personal growth as I navigate various challenges and topics in cybersecurity.

## Learning Reflections

### Commands of Windows CLI i Learnt

ONCE YOU HAVE HOST

- ssh -> secure shell used to navigate safely through a unsafe network.
- ipconfig -> gives the ip address, subnet mask, default gateway...subnet mask-> 32 bit seperates ip address to host and netwrok... defaultgateway-> network device acts as a router.
     -> in ipconfig /all -> you will get physical address/ mac address which will be there even if you switch off your wifi or not. ip keeps on changing whereas physical won't. mac is hardware dependant. 
      -> Default Gateway -> Like wifi connected to devices it can have multiple i.e. doors to a room
      -> ping can also be ip address... for eg ping can be -t for indefinite times -n *number* for number of times.
##History: 
-> ipv4 uses 2^32 as in 32 bits... meaning it has 2^32 ipaddresses
-> ipv6 uses 2^128 as in 128 bits... meaning it has 2^128 addresses                                              
- after ssh
  -> ver -> will tell the os version
  -> systeminfo
- tracert -> number of routes to go the host. for windows tracepath also. 
- nslookup -> returns the host ip address.
- netstat -about the connected networks
  -> -a -> established connections and listening ports .
  -> -b -> program associated with the ports.
  -> -o -> shows the process id.
  -> -n -> shows the numerical address and ports.

- dir /a -> shows hidden files shows all files
- dir /s -> displays current directory and sub
- type {file name} -> shows what inside the file.

TASKS:
-> tasklist/FI "imagename eq _ .exe " -> to get _.exe process.
-> taskkill / PID 0000 -> kills process id 0000.

## Conclusion

My journey through TryHackMe has been both challenging and rewarding. The skills and knowledge I am acquiring will serve as a strong foundation for my future endeavors in cybersecurity.
