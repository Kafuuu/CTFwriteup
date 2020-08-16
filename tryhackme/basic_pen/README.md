# TryHackMe - Basic Pentesting

# Available port : SSH ....

# Question

1 & 2 via nmap

3 via gobuster
5 via enum4linux
6 via hydra ( 'armando')
7 - SSH
9 - ssh as john and find kay's rsa private keys. 
hash the key by python /usr/share/john/ssh2john.py kay_id  > id_rsa.txt
Then, using JohntheRipper with rockyou dictionary 
passphrase with 'beeswax'
cat pass.bak, then we get 
heresareallystrongpasswordthatfollowsthepasswordpolicy

