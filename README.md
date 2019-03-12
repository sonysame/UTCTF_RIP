# UTCTF_RIP
forensics

USE *John the Ripper* and rockyou.txt as a wordlist


zip2john [zipfile] > hash.txt

./john /home/sonysame/Desktop/hash.txt --wordlist=/home/sonysame/Desktop/rockyou.txt --rules
