# EzpzLFI by H0j3n

![https://github.com/H0j3n/EazyPeazy/blob/master/My%20Tools/EzpzLFI/img/1.png?raw=true](https://github.com/H0j3n/EazyPeazy/blob/master/My%20Tools/EzpzLFI/img/1.png?raw=true)

```
[Available Type]

[+] param
	- Try all posible paramater that can LFI

[+] log
	- Try all possible files with known parameter of LFI

[+] rce
	- Try all possible parameter that can execute commands
```

### How to use

```python
# Better use /etc/passwd only as sample lfi.txt 
[+] param
	- python3 ezpzLFI-v2.py --wordlist lfi.txt --type log

[+] log
	- python3 ezpzLFI-v2.py --wordlist log.txt --type log

[+] rce
	- python3 ezpzLFI-v2.py --wordlist rce.txt --type rce 
```

### Options Available
```
--cookies
Example : --cookies PHPSESSID=123456789

--technique

--verbose
```

### RCE

![rce](https://github.com/H0j3n/EazyPeazy/blob/master/My%20Tools/EzpzLFI/img/rce.png?raw=true)

### PARAM

### LOG
