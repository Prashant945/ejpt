# ejpt

website vs web application

# HNPT - host based attacks
IIS port 80/443--> nmap -sV -sC targetip
nmap -sV -p 80 --script=http-enum targetip //detailed view

hydra tool
hydra -L /usr/share/wordlists/metasploit/coomon_users.txt -P /usr/share/wordlists/metasploit/coomon_passwords.txt targetip http-get /webdav/

davtest -url http://targetip/webdav

upload, dowaload, delete cadaver

