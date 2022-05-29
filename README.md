# WSO2 Carbon Server CVE-2022-29464
Pre-auth RCE bug  CVE-2022-29464.
Write by Chocapikk
lightely modded by trhacknon

## Usage

```bash
python exploit.py -u <wso2_carbon_server> 
```
or:

```bash
python exploit.py -f <file>
```
## Zoomeye Dork
CLI:
```bash

zoomeye search 'title:"WSO2 Management Console"'  -num 10  -filter=ip,port
```
WEB:
```
title:"WSO2 Management Console"
```
## Google dorks
```

inurl:"/carbon/admin/login.jsp"
inurl"/authtenticationdpoit/login.do"
inurl:"/authenticationendpoint/login.do"
inurl:"devportal/apis"
intitle:"API Publisher- Login" 
intitle:"WSO2 Management Console"
```
