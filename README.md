# OverTheWire
```
https://overthewire.org/wargames/
```
### USE THIS ONLY IF YOUR REALLY STUCK AND TIRED OF FINDING THE PASSWORD AND HAVE NO OTHER WAY.

# Bandit
## Level 0:
CMD: 
```bash
ssh bandit0@bandit.labs.overthewire.org -p 2220
```
Password: 
```bash
bandit0
```
Solution:
```bash
ls
cat readme
```
**Password: ZjLjTmM6FvvyRnrb2rfNWOZOTa6ip5If**

## Level 1:
CMD:
```bash
ssh bandit1@bandit.labs.overthewire.org -p 2220
```
Password: 
```bash
ZjLjTmM6FvvyRnrb2rfNWOZOTa6ip5If
```
Solution:
```bash
cat ./-
```
**Password: 263JGJPfgU6LtdEvgfWU1XP5yac29mFx**

## Level 2:
CMD:
```bash
ssh bandit2@bandit.labs.overthewire.org -p 2220
```
Password: 
```bash
263JGJPfgU6LtdEvgfWU1XP5yac29mFx
```
Solution:
```bash
cat "spaces in this filename"
```
**Password: MNk8KNH3Usiio41PRUEoDFPqfxLPlSmx**

## Level 3:
CMD:
```bash
ssh bandit3@bandit.labs.overthewire.org -p 2220
```
Password: 
```bash
MNk8KNH3Usiio41PRUEoDFPqfxLPlSmx
```
Solution:
```bash
cd inhere
ls -la
cat ./...Hiding-From-You
```
**Password: 2WmrDFRmJIq3IPxneAaMGhap0pFhF3NJ**

## Level 4:
CMD:
```bash
ssh bandit4@bandit.labs.overthewire.org -p 2220
```
Password: 
```bash
2WmrDFRmJIq3IPxneAaMGhap0pFhF3NJ
```
Solution:
```bash
ls
cd inhere
 ls -la
 file ./-file*
 cat ./-file07
```
**Password: 4oQYVPkxZOOEOO5pTW81FB8j8lxXGUQw**

## Level 5:
CMD:
```bash
ssh bandit5@bandit.labs.overthewire.org -p 2220
```
Password: 
```bash
4oQYVPkxZOOEOO5pTW81FB8j8lxXGUQw
```
Solution:
```bash
ls
cd inhere
ls -la
find . -type f -size 1033c ! -executable
cat ./maybehere07/.file2
```
**Password: HWasnPhtq9AVKe0dmk45nxy20cvUa6EG**

## Level 6:
CMD:
```bash
ssh bandit6@bandit.labs.overthewire.org -p 2220
```
Password: 
```bash
HWasnPhtq9AVKe0dmk45nxy20cvUa6EG
```
Solution:
```bash
find / -type f -user bandit7 -group bandit6 -size 33c 2>/dev/null
cat /var/lib/dpkg/info/bandit7.password
```
**Password: morbNTDkSW6jIlUc0ymOdMaLnOlFVAaj**

## Level 7:
CMD:
```bash
ssh bandit7@bandit.labs.overthewire.org -p 2220
```
Password: 
```bash
morbNTDkSW6jIlUc0ymOdMaLnOlFVAaj
```
Solution:
```bash
cat data.txt | grep "millionth"
```
**Password: dfwvzFQi4mU0wfNbFOe9RoWskMLg7eEc**

## Level 8:
CMD:
```bash
ssh bandit8@bandit.labs.overthewire.org -p 2220
```
Password: 
```bash
dfwvzFQi4mU0wfNbFOe9RoWskMLg7eEc
```
Solution:
```bash
sort data.txt | uniq -u
```
**Password: 4CKMh1JI91bUIZZPXDqGanal4xvAg0JM**

## Level 9:
CMD:
```bash
ssh bandit9@bandit.labs.overthewire.org -p 2220
```
Password: 
```bash
4CKMh1JI91bUIZZPXDqGanal4xvAg0JM
```
Solution:
```bash
strings data.txt | grep "=.*"
```
**Password: FGUW5ilLVJrxX9kMYMmlN4MgbpfMiqey**

## Level 10:
CMD:
```bash
ssh bandit10@bandit.labs.overthewire.org -p 2220
```
Password: 
```bash
FGUW5ilLVJrxX9kMYMmlN4MgbpfMiqey
```
Solution:
```bash
base64 -d data.txt
```
**Password: dtR173fZKb0RRsDFSGsg2RWnpNVj3qRr**

## Level 11:
CMD:
```bash
ssh bandit11@bandit.labs.overthewire.org -p 2220
```
Password: 
```bash
dtR173fZKb0RRsDFSGsg2RWnpNVj3qRr
```
Solution:
```bash
cat data.txt | tr 'A-Za-z' 'N-ZA-Mn-za-m'
```
**Password: 7x16WNeHIi5YkIhWsfFIqoognUTyj9Q4**

## Level 12:
CMD:
```bash
ssh bandit12@bandit.labs.overthewire.org -p 2220
```
Password: 
```bash
7x16WNeHIi5YkIhWsfFIqoognUTyj9Q4
```
Solution:
```bash
mkdir /tmp/tmp1000099
cd /tmp/tmp1000099
cp ~/data.txt .
mv data.txt hexdump_data
xxd -r hexdump_data compressed_data
mv compressed_data compressed_data.gz
gzip -d compressed_data.gz
mv compressed_data compressed_data.bz2
bzip2 -d compressed_data.bz2
mv compressed_data compressed_data.gz
gzip -d compressed_data.gz
mv compressed_data compressed_data.tar
tar -xf compressed_data.tar
tar -xf data5.bin
bzip2 -d data6.bin
tar -xf data6.bin.out
mv data8.bin data8.gz
gzip -d data8.gz
cat data8
```
**Password: FO5dwFsc0cbaIiH0h8J2eUks2vdTDwAn**

## Level 13:
CMD:
```bash
ssh bandit13@bandit.labs.overthewire.org -p 2220
```
Password: 
```bash
FO5dwFsc0cbaIiH0h8J2eUks2vdTDwAn
```
Solution:
```bash
ssh -i sshkey.private -p 2220 bandit14@localhost
cat /etc/bandit_pass/bandit14
```
**Password: MU4VWeTyJk8ROof1qqmcBPaLh7lDCPvS**

## Level 14:
CMD:
```bash
ssh bandit14@bandit.labs.overthewire.org -p 2220
```
Password: 
```bash
MU4VWeTyJk8ROof1qqmcBPaLh7lDCPvS
```
Solution:
```bash
echo "MU4VWeTyJk8ROof1qqmcBPaLh7lDCPvS" | nc localhost 30000
```
**Password: 8xCjnmgoKbGLhHFAZlGE5Tmu4M2tKJQo**

## Level 15:
CMD:
```bash
ssh bandit15@bandit.labs.overthewire.org -p 2220
```
Password: 
```bash
8xCjnmgoKbGLhHFAZlGE5Tmu4M2tKJQo
```
Solution:
```bash
openssl s_client -connect localhost:30001
```
```bash
8xCjnmgoKbGLhHFAZlGE5Tmu4M2tKJQo
```
**Password: kSkvUpMQ7lBYyCM4GBPvCvT1BfWRy0Dx**

## Level 16:
CMD:
```bash
ssh bandit16@bandit.labs.overthewire.org -p 2220
```
Password: 
```bash
kSkvUpMQ7lBYyCM4GBPvCvT1BfWRy0Dx
```
Solution:
```bash
echo "kSkvUpMQ7lBYyCM4GBPvCvT1BfWRy0Dx" | openssl s_client -quiet -connect localhost:31790
```
**Password:**
```
-----BEGIN RSA PRIVATE KEY-----
MIIEogIBAAKCAQEAvmOkuifmMg6HL2YPIOjon6iWfbp7c3jx34YkYWqUH57SUdyJ
imZzeyGC0gtZPGujUSxiJSWI/oTqexh+cAMTSMlOJf7+BrJObArnxd9Y7YT2bRPQ
Ja6Lzb558YW3FZl87ORiO+rW4LCDCNd2lUvLE/GL2GWyuKN0K5iCd5TbtJzEkQTu
DSt2mcNn4rhAL+JFr56o4T6z8WWAW18BR6yGrMq7Q/kALHYW3OekePQAzL0VUYbW
JGTi65CxbCnzc/w4+mqQyvmzpWtMAzJTzAzQxNbkR2MBGySxDLrjg0LWN6sK7wNX
x0YVztz/zbIkPjfkU1jHS+9EbVNj+D1XFOJuaQIDAQABAoIBABagpxpM1aoLWfvD
KHcj10nqcoBc4oE11aFYQwik7xfW+24pRNuDE6SFthOar69jp5RlLwD1NhPx3iBl
J9nOM8OJ0VToum43UOS8YxF8WwhXriYGnc1sskbwpXOUDc9uX4+UESzH22P29ovd
d8WErY0gPxun8pbJLmxkAtWNhpMvfe0050vk9TL5wqbu9AlbssgTcCXkMQnPw9nC
YNN6DDP2lbcBrvgT9YCNL6C+ZKufD52yOQ9qOkwFTEQpjtF4uNtJom+asvlpmS8A
vLY9r60wYSvmZhNqBUrj7lyCtXMIu1kkd4w7F77k+DjHoAXyxcUp1DGL51sOmama
+TOWWgECgYEA8JtPxP0GRJ+IQkX262jM3dEIkza8ky5moIwUqYdsx0NxHgRRhORT
8c8hAuRBb2G82so8vUHk/fur85OEfc9TncnCY2crpoqsghifKLxrLgtT+qDpfZnx
SatLdt8GfQ85yA7hnWWJ2MxF3NaeSDm75Lsm+tBbAiyc9P2jGRNtMSkCgYEAypHd
HCctNi/FwjulhttFx/rHYKhLidZDFYeiE/v45bN4yFm8x7R/b0iE7KaszX+Exdvt
SghaTdcG0Knyw1bpJVyusavPzpaJMjdJ6tcFhVAbAjm7enCIvGCSx+X3l5SiWg0A
R57hJglezIiVjv3aGwHwvlZvtszK6zV6oXFAu0ECgYAbjo46T4hyP5tJi93V5HDi
Ttiek7xRVxUl+iU7rWkGAXFpMLFteQEsRr7PJ/lemmEY5eTDAFMLy9FL2m9oQWCg
R8VdwSk8r9FGLS+9aKcV5PI/WEKlwgXinB3OhYimtiG2Cg5JCqIZFHxD6MjEGOiu
L8ktHMPvodBwNsSBULpG0QKBgBAplTfC1HOnWiMGOU3KPwYWt0O6CdTkmJOmL8Ni
blh9elyZ9FsGxsgtRBXRsqXuz7wtsQAgLHxbdLq/ZJQ7YfzOKU4ZxEnabvXnvWkU
YOdjHdSOoKvDQNWu6ucyLRAWFuISeXw9a/9p7ftpxm0TSgyvmfLF2MIAEwyzRqaM
77pBAoGAMmjmIJdjp+Ez8duyn3ieo36yrttF5NSsJLAbxFpdlc1gvtGCWW+9Cq0b
dxviW8+TFVEBl1O4f7HVm6EpTscdDxU+bCXWkfjuRb7Dy9GOtt9JPsX8MBTakzh3
vBgsyi/sN3RqRBcGU40fOoZyfAMT8s1m/uYv52O6IgeuZ/ujbjY=
-----END RSA PRIVATE KEY-----
```

## Level 17:
CMD:
```bash
ssh -i Key.txt bandit17@bandit.labs.overthewire.org -p 2220
```
Password: 

Save Password in Key.txt

```
-----BEGIN RSA PRIVATE KEY-----
MIIEogIBAAKCAQEAvmOkuifmMg6HL2YPIOjon6iWfbp7c3jx34YkYWqUH57SUdyJ
imZzeyGC0gtZPGujUSxiJSWI/oTqexh+cAMTSMlOJf7+BrJObArnxd9Y7YT2bRPQ
Ja6Lzb558YW3FZl87ORiO+rW4LCDCNd2lUvLE/GL2GWyuKN0K5iCd5TbtJzEkQTu
DSt2mcNn4rhAL+JFr56o4T6z8WWAW18BR6yGrMq7Q/kALHYW3OekePQAzL0VUYbW
JGTi65CxbCnzc/w4+mqQyvmzpWtMAzJTzAzQxNbkR2MBGySxDLrjg0LWN6sK7wNX
x0YVztz/zbIkPjfkU1jHS+9EbVNj+D1XFOJuaQIDAQABAoIBABagpxpM1aoLWfvD
KHcj10nqcoBc4oE11aFYQwik7xfW+24pRNuDE6SFthOar69jp5RlLwD1NhPx3iBl
J9nOM8OJ0VToum43UOS8YxF8WwhXriYGnc1sskbwpXOUDc9uX4+UESzH22P29ovd
d8WErY0gPxun8pbJLmxkAtWNhpMvfe0050vk9TL5wqbu9AlbssgTcCXkMQnPw9nC
YNN6DDP2lbcBrvgT9YCNL6C+ZKufD52yOQ9qOkwFTEQpjtF4uNtJom+asvlpmS8A
vLY9r60wYSvmZhNqBUrj7lyCtXMIu1kkd4w7F77k+DjHoAXyxcUp1DGL51sOmama
+TOWWgECgYEA8JtPxP0GRJ+IQkX262jM3dEIkza8ky5moIwUqYdsx0NxHgRRhORT
8c8hAuRBb2G82so8vUHk/fur85OEfc9TncnCY2crpoqsghifKLxrLgtT+qDpfZnx
SatLdt8GfQ85yA7hnWWJ2MxF3NaeSDm75Lsm+tBbAiyc9P2jGRNtMSkCgYEAypHd
HCctNi/FwjulhttFx/rHYKhLidZDFYeiE/v45bN4yFm8x7R/b0iE7KaszX+Exdvt
SghaTdcG0Knyw1bpJVyusavPzpaJMjdJ6tcFhVAbAjm7enCIvGCSx+X3l5SiWg0A
R57hJglezIiVjv3aGwHwvlZvtszK6zV6oXFAu0ECgYAbjo46T4hyP5tJi93V5HDi
Ttiek7xRVxUl+iU7rWkGAXFpMLFteQEsRr7PJ/lemmEY5eTDAFMLy9FL2m9oQWCg
R8VdwSk8r9FGLS+9aKcV5PI/WEKlwgXinB3OhYimtiG2Cg5JCqIZFHxD6MjEGOiu
L8ktHMPvodBwNsSBULpG0QKBgBAplTfC1HOnWiMGOU3KPwYWt0O6CdTkmJOmL8Ni
blh9elyZ9FsGxsgtRBXRsqXuz7wtsQAgLHxbdLq/ZJQ7YfzOKU4ZxEnabvXnvWkU
YOdjHdSOoKvDQNWu6ucyLRAWFuISeXw9a/9p7ftpxm0TSgyvmfLF2MIAEwyzRqaM
77pBAoGAMmjmIJdjp+Ez8duyn3ieo36yrttF5NSsJLAbxFpdlc1gvtGCWW+9Cq0b
dxviW8+TFVEBl1O4f7HVm6EpTscdDxU+bCXWkfjuRb7Dy9GOtt9JPsX8MBTakzh3
vBgsyi/sN3RqRBcGU40fOoZyfAMT8s1m/uYv52O6IgeuZ/ujbjY=
-----END RSA PRIVATE KEY-----
```
Solution:
```bash

```
**Password:**
