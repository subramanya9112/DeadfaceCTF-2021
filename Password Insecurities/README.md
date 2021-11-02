It looks like DEADFACE is going after the password of one of De Monne's customers: Haily Poutress. She has since changed her password, but De Monne is looking for ways to improve password requirements. De Monne would like you to crack the password from the database leak to determine if Haily's password was secure enough. Submit the flag as flag{password}.

Use the MySQL database dump from Body Count.

Download MySQL database dump
SHA1: 2b1ceb8102a9dc67254fc82bfdd80c5551da66a4

Password: d34df4c3

```
hashcat -a 0 -m 500 digest.txt /usr/share/wordlists/rockyou.txt 

flag{trustno1}
```