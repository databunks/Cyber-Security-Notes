`Port 0` is a ==reserved port== in TCP/IP networking and is ==not used== in TCP or UDP messages. If anything attempts to bind to `port 0` (such as a `service`), it will bind to the ==next available port== above `port 1024` because `port 0` is treated as a "==wild card==" port.

`port 3389` is the default port for ==Remote Desktop== Services and is an excellent indication that the target is a ==Windows machine==

`port 22 SSH` indicates that the target is likely running linux


#nmap/ports
