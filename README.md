tool used - uncomplicated firewall(UFW)

1. opened the cmd and executed the command -sudo ufw status verbose to check the ufw status

2. checked the current firewalls by using the command -sudo ufw status numbered

3. blocked the inbound traffic by using -sudo ufw deny 23

4. tried to connect to port 23 using telnet -telnet localhost 23

5. now removed the block rule for port 23 -sudo ufw delete deny 23

6. conclusion

The firewall was configured using UFW on Linux. Rules were added to block traffic on port 23 (Telnet) and allow SSH traffic on port 22. After testing, the block rule was removed.
Firewalls filter traffic by checking rules set by the user or system. If a rule matches, it either allows or denies the traffic, helping to secure the system from unauthorized access or vulnerabilities.



