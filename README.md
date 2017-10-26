Time spent: **?** hours spent in total 
### Challenges / User Stories
The following **required** Milestones are completed:
1. [ ]  Milestone 0 - Networking Toolbox
    - [ ]  `ifconfig` Challenges
      - [ ]  Primary Network Interface: 
      - [ ]  IP Address: 
       - 
      - [ ]  MAC Address: 
    - [X]  `ping` Challenges
      -  [x]  `codepath.com` IP Address: `198.58.125.217`
      -  [X]  `google.com` IP Address: `172.217.2.238`
       -  Because `google.com` is such a massive service it has different servers that users are able to connect to hence the different IP addresses that user can connect to.
    - [X]  `nslookup` Challenges
      - [X]  `nslookup` `codepath.com`: `Server:     172.16.0.18
Address:    172.16.0.18#53`
       -  `nslookup` only uses DNS, while ping will first look in `hosts` file
    - [X]  `traceroute` Challenges
      - [X]  traceroutes for `codepath.com`: 64 hops max, 52 byte packets
      - [X]  traceroutes for `google.com`: 64 hops max, 52 byte packets
       -  Both pass thorugh MSU colleges IP addresses to get to "outside world"
    - [ ]  `telnet` Challenges
      -   `telnet` sends data in plaintext and can be easily read using wireshark
      - [X]  `telnet` `codepath.com`
        -  `telnet codepath.com` returns the following: 
        ```
Trying 198.58.125.217...
telnet: connect to address 198.58.125.217: Connection refused
telnet: Unable to connect to remote host
        ```


    - [ ]  `curl` Challenges
      -
      -
      -
      -
      -
    - [ ]  `ssh` and `scp` Challenges
      -
      -
    
    
1. [ ]  Required: Milestone 1 - Security-Flavored Net Tools
    - [ ]  Challenge 1
    - [ ]  Challenge 2
1. [ ]  Required: Milestone 2 - Grabbing Packets with `tcpdump`
    - [ ]  Challenge 1
    - [ ]  Challenge 2
1. [ ]  Required: Milestone 3 - Hello, Wireshark
    - [ ]  Challenge
1. [ ]  Required: Milestone 4 - Traffic Analysis - Mike's Computer is Acting Weird
1. [ ]  Required: Milestone 5 - Traffic Analysis - Mystery Meat Malware
1. [ ]  Required: Milestone 6 - Wi-Fi Hacking - Crack a Handshake
    - [ ]  Challenge
1. [ ]  Required: Milestone 7 - Wi-Fi Hacking - Grab a Handshake

The following **Bonus** Milestones are completed:
1. [ ] Bonus: Milestone 8 - Wi-Fi Hacking - Sniff Thy Neighbor's Packets
