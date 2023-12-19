#OSCP 
## This page provides an overview of tools and their commonly used switches

### Gobuster

Gobuster is used to enumerate hidden webpages in a website by using a wordlist to brute force possible existing directories.

```
gobuster -u http://fakebank.com -w wordlist.txt dir
```

'-u <website>' denotes the target website
'-w <wordlist.txt>' denotes the wordlist for gobuster to iterate through
