# cisco-rhcos
ign file for user and pass

1.	Start the coreos and run the "nmtui " tool to setup network. 

2.	Run this command on the shell : 
   
    #$> sudo coreos-installer install /dev/sda –copy-network \
  	–ignition-url  https://raw.githubusercontent.com/amihai4by/cisco-rhcos/main/coreos-latest.ign \
  	--insecure-ignition


   user: cisco
   password : P@ssw0rd



