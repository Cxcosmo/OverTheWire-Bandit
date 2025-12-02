# OverTheWire-Bandit  

<p> Link - https-//overthewire.org/wargames/bandit </p>  

---  
> ssh bandit{level}@bandit.labs.overthewire.org -p 2220  
---  
### level 0  

<p>ssh bandit0@bandit.labs.overthewire.org -p 2220</p>  
<p>Password - bandit0</p>  

---  
### level 0 -> 1  

<p>Solve - cat readme</p>  
<p>Flag - ZjLjTmM6FvvyRnrb2rfNWOZOTa6ip5If</p>  

---  
### level 1 -> 2  

<p>Solve - cat ./-</p>  
<p>Flag - 263JGJPfgU6LtdEvgfWU1XP5yac29mFx</p>  

---  
### level 2 -> 3  

<p>Solve - cat ./'--spaces in this filename--'</p>  
<p>Flag - MNk8KNH3Usiio41PRUEoDFPqfxLPlSmx</p>  

---  
### level 3 -> 4  

<p>Solve - $ls -a -> $cd inhere -> $ls -a -> $cat ...Hiding-From-You</p>  
<p>Flag - 2WmrDFRmJIq3IPxneAaMGhap0pFhF3NJ</p>  

---  
### level 4 -> 5  

<p>Solve - $cd inhere -> Brute-Force cat all file format cat ./-file0_</p>  
<p>Flag - 4oQYVPkxZOOEOO5pTW81FB8j8lxXGUQw</p>  

---  
### level 5 -> 6  

<p>Solve - $cd inhere -> $find . -type f -size 1033c ! -perm /111 -> $cat ./maybehere07/.file2</p>  
<p>Flag - HWasnPhtq9AVKe0dmk45nxy20cvUa6EG</p>  

---  
### level 6 -> 7  

<p>Solve - find / -type f -user bandit7 -group bandit6 -size 33c</p>  
<p>Flag - morbNTDkSW6jIlUc0ymOdMaLnOlFVAaj</p>  

---  
### level 7 -> 8  

<p>Solve - grep "millionth" data.txt</p>  
<p>Flag - dfwvzFQi4mU0wfNbFOe9RoWskMLg7eEc</p>  

---  
### level 8 -> 9  

<p>Solve - cat data.txt | sort | uniq -u</p>  
<p>Flag - 4CKMh1JI91bUIZZPXDqGanal4xvAg0JM</p>  

---  
### level 9 -> 10  

<p>Solve - strings data.txt | grep "="</p>  
<p>Flag - FGUW5ilLVJrxX9kMYMmlN4MgbpfMiqey</p>  

---  
### level 10 -> 11  

<p>Solve - cat data.txt -> Decode base64</p>  
<p>Flag - dtR173fZKb0RRsDFSGsg2RWnpNVj3qRr</p>  

---  
### level 11 -> 12  

<p>Solve - cat data.txt | tr "A-Za-z" "N-ZA-Mn-za-m"</p>  
<p>Flag - 7x16WNeHIi5YkIhWsfFIqoognUTyj9Q4</p>  

---  
### level 12 -> 13  

<p>Solve</p>
<p>1. mktemp -d (create tmp)</p>  
<p>2. cp data.txt /tmp/tmp.{tmp path that u create}</p>  
<p>3. cd /tmp/tmp.{tmp path that u create}</p>  
<p>4. xxd -r data.txt > data (reverse hexdump and keep it to file name data)</p>  
<p>5. file data (show log of compressed file)</p>  
<p>6. mv data data.{type of file that log told U}</p>  
<p>7. Decompression file</p>  
<p>8. do again & again</p>  
<p>9. If it told U POSIX tar - $tar -xf {file name}</p>  
<p>10. do 5 - 8 again</p>  
<p>11. last time it told U that ASCII text</p>  
<p>12. cat Your file</p>  

#### -- Decompression file --
##### gzip
```
gzip -d {file name}
```
##### bzip2
```
bzip2 -d {file name}
```

<p>Flag - FO5dwFsc0cbaIiH0h8J2eUks2vdTDwAn</p>  

---  
### level 13 -> 14  

<p>Solve - </p>  
<p>Flag - </p>  

---  
### level 14 -> 15  

<p>Solve - </p>  
<p>Flag - </p>  

---  
### level 15 -> 16  

<p>Solve - </p>  
<p>Flag - </p>  

---  
### level 16 -> 17  

<p>Solve - </p>  
<p>Flag - </p>  

---  
### level 17 -> 18  

<p>Solve - </p>  
<p>Flag - </p>  

---  
### level 18 -> 19  

<p>Solve - </p>  
<p>Flag - </p>  

---  
### level 19 -> 20  

<p>Solve - </p>  
<p>Flag - </p>  

---  
### level 20 -> 21  

<p>Solve - </p>  
<p>Flag - </p>  

---  
### level 21 -> 22  

<p>Solve - </p>  
<p>Flag - </p>  

---  
### level 23 -> 24  

<p>Solve - </p>  
<p>Flag - </p>  

---  
### level 24 -> 25  

<p>Solve - </p>  
<p>Flag - </p>  

---  
### level 25 -> 26  

<p>Solve - </p>  
<p>Flag - </p>  

---  
### level 26 -> 27  

<p>Solve - </p>  
<p>Flag - </p>  

---  
### level 27 -> 28  

<p>Solve - </p>  
<p>Flag - </p>  

---  
### level 28 -> 29  

<p>Solve - </p>  
<p>Flag - </p>  

---  
### level 29 -> 30  

<p>Solve - </p>  
<p>Flag - </p>  

---  
### level 30 -> 31  

<p>Solve - </p>  
<p>Flag - </p>  

---  
### level 31 -> 32  

<p>Solve - </p>  
<p>Flag - </p>  

---  
### level 32 -> 33  

<p>Solve - </p>  
<p>Flag - </p>  

---  
### level 33 -> 34  

<p>Solve - </p>  
<p>Flag - </p>  

