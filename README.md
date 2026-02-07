# examplehealth-dns-webserver-troubleshooting
New ticket

Through investigation check was completed on bbc.co.uk 

DNS Resoulation check was done by using; dig bbc.co.uk 
command came back the correct IP and is working as expected 

Networking check completed by using ping -c 4, command showed everything was working as expected. 

Webserver was checked using, curl -I, command fetched the service. 

After a check on the log/services, using systemltc status, the service was not found. 

Findings were explain and the use of commands and the likely issue with the services. 
