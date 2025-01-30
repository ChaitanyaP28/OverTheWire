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
```bash
cat data.txt | tr 'A-Za-z' 'N-ZA-Mn-za-m'
```
**Password: 7x16WNeHIi5YkIhWsfFIqoognUTyj9Q4**