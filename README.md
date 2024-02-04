# SSTI
Server Side Template Injection - XSS Finder

This tool will grap all target subdomains from shodan that are using AsgularJS Technology and in output it will provide us with XSS payload related to AngularJS version of that subdomain.

## Prerequisites

```
1. npm i -g wappalyzer
2. pip install -U setuptools
3. pip install shodan
4. shodan init YOUR_API_KEY
```

```
git clone https://github.com/Himangshu30/SSTI && cd SSTI && chmod +x *.sh
```

## Usage
Linux

```
./SSTI-XSS-Finder.sh <Shodan-Dork>  like  org:target | hostname:target.com | net:127.0.0.1
```



## Reference
* https://github.com/swisskyrepo/PayloadsAllTheThings/blob/master/XSS%20Injection/XSS%20in%20Angular.md


