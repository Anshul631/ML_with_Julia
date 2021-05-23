# **Assignment_1**

---
-**level 0 --> level 1**
 
 ```
 $ ssh -p 2220 bandit0@bandit.labs.overthewire.org
```
password: bandit0

--->*password obtained*: boJ9jbbUNNfktd78OOpsqOltutMc3MY1 

<br/>

-**level 1 --> level 2**

```
$ ssh -p 2220 bandit1@bandit.labs.overthewire.org
```
password: boJ9jbbUNNfktd78OOpsqOltutMc3MY1 

~$ ls
~$ cat readme

--->*password obtained*: CV1DtqXWVFXTvM2F0k09SHz0YwRINYA9

<br/>

-**level 2 --> level 3**

```
$ ssh -p 2220 bandit2@bandit.labs.overthewire.org
```
password: CV1DtqXWVFXTvM2F0k09SHz0YwRINYA9

~$ ls
~$ cat <-

--->*password obtained*: UmHadQclWmgdLOKQ3YNgjWxGoRMb5luK

<br/>
-**level 3 --> level 4**

```
$ssh -p 2220 bandit3@bandit.labs.overthewire.org
```
password: UmHadQclWmgdLOKQ3YNgjWxGoRMb5luK

~$ ls
~$ cat "spaces in this filename"

--->*passsword obtained*: pIwrPrtPN36QITSp3EQaw936yaFoFgAB

<br/>
-**level 4 --> level 5**

```
$ssh -p 2220 bandit4@bandit.labs.overthewire.org
```
password: pIwrPrtPN36QITSp3EQaw936yaFoFgAB

~$ ls
~$ cd inhere/
~/inhere$ ls -a
~/inhere$ cat .hidden

--->*password obtained*: koReBOKuIDDepwhWk7jZC0RTdopnAYKh

<br/>
-**level 5 --> level 6**

```
$ ssh -p 2220 bandit5@bandit.labs.overthewire.org
```
password: koReBOKuIDDepwhWk7jZC0RTdopnAYKh
~$ cd inhere
~/inhere$ find . -type f -size 1033c ! -executable
~/inhere$ cat ./maybehere07/.file2

-->*password obtained*: DXjZPULLxYr17uwoI01bNLQbtFemEgo7

<br/>
-**level 6 --> level 7**

```
$ ssh -p 2220 bandit6@bandit.labs.overthewire.org
```
password: DXjZPULLxYr17uwoI01bNLQbtFemEgo7

~$ find / -type f -user bandit7 -group bandit6 -size 33
~$ cat /var/lib/dpkg/info/bandit7.password

-->*password obtained*: HKBPTKQnIay4Fw76bEy8PVxKEDQRKTzs

<br/>
-**level 7 --> level 8**

```
$ ssh -p 2220 bandit7@bandit.labs.overthewire.org
```
password: HKBPTKQnIay4Fw76bEy8PVxKEDQRKTzs

~$ grep -i "millionth" data.txt

-->*password obtained*:  cvX2JJa4CFALtqS87jk27qwqGhBM9plV
<br/>
-**level 8 --> level 9**

```
$ ssh -p 2220 bandit8@bandit.labs.overthewire.org
```
password:  cvX2JJa4CFALtqS87jk27qwqGhBM9plV

~$ ls
~$ cat data.txt
~$ sort data.txt | uniq -c

-->*password obtained*: UsvVyFSfZZWbi6wgC7dAFyFuR6jQQUhR

<br/>
-*level 9 --> level 10*

```
$ ssh -p 2220 bandit9@bandit.labs.overthewire.org
```
password: UsvVyFSfZZWbi6wgC7dAFyFuR6jQQUhR

~$ strings data.txt | grep "="

-->*password obtained*: truKLdjsbJ5g7yyJ2X2R0o3a5HQJFuLk

<br/>
-*level 10 --> level 11*

```
$ ssh -p 2220 bandit10@bandit.labs.overthewire.org
```

password: truKLdjsbJ5g7yyJ2X2R0o3a5HQJFuLk

~$ ls
~$ cat data.txt
~$ base64 -d data.txt

-->*password obtained*: IFukwKGsFW8MOq3IRFqrxE1hxTNEbUPR

<br/>
*level 11 --> level 12*

```
$ ssh -p 2220 bandit11@bandit.labs.overthewire.org
```
password: IFukwKGsFW8MOq3IRFqrxE1hxTNEbUPR

~$ ls
~$ cat data.txt
  \\Gur cnffjbeq vf 5Gr8L4qetPEsPk8htqjhRK8XSP6x2RHh
~$ echo "Gur cnffjbeq vf 5Gr8L4qetPEsPk8htqjhRK8XSP6x2RHh" | tr 'n-za-mN-ZA-M' 'a-zA-Z'

-->*password obtained*: 5Te8Y4drgCRfCx8ugdwuEX8KFC6k2EUu

<br/>
**level 12 --> level 13**

```
$ ssh -p 2220 bandit12@bandit.labs.ovverthewire.org
```
password: 5Te8Y4drgCRfCx8ugdwuEX8KFC6k2EUu








