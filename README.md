Bash script to interact with c99.nl API specific services for web pen testers recon assessment.

Created this script to support my recon process to get c99 API specific operations results and use them as stdin for other similar tools. 


### Usage

- Set your c99.nl API key in

```
C99_API="VALUE"
```

- Save and run.

```
./c99.sh 

./scriptname.sh [option] [target.com]

1 - Subdomain Finder [ ./run.sh 1 target.com ] 
2 - Firewall Technology (WAF) Detector [ ./run.sh 2 target.com ]
3 - Multiple Port Scanner [ ./run.sh 3 hosts.txt
4 - Single Port Scanner [ ./run.sh 4 hosts.txt PORT_Number ]
5 - Nmap Scanner [ ./run.sh 5 hosts.txt
6 - Host to IP [ ./run.sh 6 target.com ]
7 - IP 2 Domains [ ./run.sh 7 IP/1.1.1.1 ]
8 - Whois Checker [ ./run.sh 8 target.com ]
9 - Get Website Headers [ ./run.sh 10 target.com ]

```



