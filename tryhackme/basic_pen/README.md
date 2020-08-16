# TryHackMe - Basic Pentesting

# Available port : SSH, etc

# Question ------

# Question 1 & 2 
via nmap

# Question 3 
via gobuster

# Question5  
via enum4linux

# Question 6 
via hydra ( 'armando')

# Question 7 - SSH

# Question 9 
ssh as john and find kay's rsa private keys. 

hash the key by python /usr/share/john/ssh2john.py kay_id  > id_rsa.txt

Then, using JohntheRipper with rockyou dictionary 

passphrase with 'beeswax'

cat pass.bak, then we get 
heresareallystrongpasswordthatfollowsthepasswordpolicy

