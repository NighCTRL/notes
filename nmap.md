network auditing command
# commands
nmap [IP to scan]
  -> simple scan 
    - return open ports
nmap 192.168.1.1-7 --exclude 192.168.1.3
  -> scan a range of ip and exclude 1.3
nmap -sV 192.168.1.1
  -> service and version of individual ports
nmap -T5 192.168.1.1/24
  -> scan the whole subnet
  -> T5= use the timing template 5 (the fastest)
