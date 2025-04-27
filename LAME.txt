#Beginner Lab - 27/04/2025 

1. How many of the nmap top 1000 TCP ports are open on the remote host?
  nmap 10.10.10.3
  ^ basic command - searching ports on the Target IP. Identified [4]

2. What version of VSFTPd is running on Lame?
   ftp 10.10.10.3
   There are different ways to detect VSFTPd versions - something like <VSFTPd -version> doesn't always work.
   I connected directly to the ftp using the above command. This shows the VSFTPd version in the banner.
   
