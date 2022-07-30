
```T0 - T4``` usually determines the speed or how "sneaky" you want the scan to be (lower the faster)

commands below make nmap run slower
```-p0-```  scans all ports (65,535 where by default it scans 1000)
```-sC```  gives more detailed information
`-sV` gives information on version

The syntax for running an Nmap script is `nmap --script <script name> -p<port> <host>`.
[[002 Handy ports to know about]]

Use ```ipcalc``` to determine network range
![[Pasted image 20220211233155.png]]
#nmap/cheatsheet