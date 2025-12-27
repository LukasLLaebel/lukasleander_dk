# My portfolio Website

## setup
### Get
- DNS server:
  Simply.com
- github repo:
  lukasleander_dk

### Create Repository
```bash
$ mkdir website
$ cd website/
$ git init -b main
$ touch index.html
$ touch README.md
$ git add .
$ git commit -m "init commit"
$ git remote add origin git@github.com:LukasLLaebel/lukasleander_dk.git
$ git push -u origin main
``` 

```
```
### Edit pages
Go To: 
lukasleander_dk -> Settings -> Pages
Change "Source" to "Github Action"
Use "static HTML"
commit.

### DNS add 4 A records:
- Hostname: lukasleander value: 185.199.108.153 (Github)
- Hostname: lukasleander value: 185.199.109.153 (Github)
- Hostname: lukasleander value: 185.199.110.153 (Github)
- Hostname: lukasleander value: 185.199.111.153 (Github)
### DNS add an CNAME record:
- Hostname: www.lukasleander.dk value: lukasllaebelcan.github.io 

### Insert into Github
Go To:
lukasleander_dk -> Settings -> Pages
Change "Custom domain" to lukasleander.dk
save.
