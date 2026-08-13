# comandoskali1 - Juan Pablo Orjuela
Comandos usados en la segunda clase, desde la terminal usando Kali


PS C:\Users\juanp> wsl -d kali-linux
┏━(Message from Kali developers)
┃
┃ This is a minimal installation of Kali Linux, you likely
┃ want to install supplementary tools. Learn how:
┃ ⇒ https://www.kali.org/docs/troubleshooting/common-minimum-setup/
┃
┗━(Run: “touch ~/.hushlogin” to hide this message)
┌──(juanp㉿Cloud)-[/mnt/c/Users/juanp]
└─$ pwd
/mnt/c/Users/juanp

┌──(juanp㉿Cloud)-[/mnt/c/Users/juanp]
└─$ cd ..

┌──(juanp㉿Cloud)-[/mnt/c/Users]
└─$ cd ..

┌──(juanp㉿Cloud)-[/mnt/c]
└─$ echo
┌──(juanp㉿Cloud)-[/mnt/c]
└─$ echo ola
ola

┌──(juanp㉿Cloud)-[/mnt/c]
└─$ cd downloads
-bash: cd: downloads: No such file or directory

┌──(juanp㉿Cloud)-[/mnt/c]
└─$
┌──(juanp㉿Cloud)-[/mnt/c]
└─$ echo ola
ola

┌──(juanp㉿Cloud)-[/mnt/c]
└─$ echo -n "ola" "tengo sueno"
ola tengo sueno
┌──(juanp㉿Cloud)-[/mnt/c]
└─$ echo HolaMundo
HolaMundo

┌──(juanp㉿Cloud)-[/mnt/c]
└─$ echo HolaMundo
HolaMundo

┌──(juanp㉿Cloud)-[/mnt/c]
└─$ cd /mnt/c/Users/juanp

┌──(juanp㉿Cloud)-[/mnt/c/Users/juanp]
└─$
┌──(juanp㉿Cloud)-[/mnt/c/Users/juanp]
└─$ echo "Holamundo" > mensaje.txt

┌──(juanp㉿Cloud)-[/mnt/c/Users/juanp]
└─$ cat mensaje.txt
Holamundo

┌──(juanp㉿Cloud)-[/mnt/c/Users/juanp]
└─$ mkdir Holamundo

┌──(juanp㉿Cloud)-[/mnt/c/Users/juanp]
└─$ pws
Could not find command-not-found database. Run 'sudo apt update' to populate it.
pws: command not found

┌──(juanp㉿Cloud)-[/mnt/c/Users/juanp]
└─$ pwd
/mnt/c/Users/juanp

┌──(juanp㉿Cloud)-[/mnt/c/Users/juanp]
└─$ touch Holamundo.txt

┌──(juanp㉿Cloud)-[/mnt/c/Users/juanp]
└─$ nano Holamundo.txt

┌──(juanp㉿Cloud)-[/mnt/c/Users/juanp]
└─$ wc -m mensaje.txt
10 mensaje.txt

┌──(juanp㉿Cloud)-[/mnt/c/Users/juanp]
└─$ sed -i 's/Holamundo/Hola mundo/' mensaje.txt

┌──(juanp㉿Cloud)-[/mnt/c/Users/juanp]
└─$ wc -m mensaje.txt
11 mensaje.txt

┌──(juanp㉿Cloud)-[/mnt/c/Users/juanp]
└─$ echo -n "Holamundo" > mensaje.txt

┌──(juanp㉿Cloud)-[/mnt/c/Users/juanp]
└─$ wc -m mensaje.txt
9 mensaje.txt

┌──(juanp㉿Cloud)-[/mnt/c/Users/juanp]
└─$ mkdir respaldo

┌──(juanp㉿Cloud)-[/mnt/c/Users/juanp]
└─$ cp mensaje.txt respaldo/

┌──(juanp㉿Cloud)-[/mnt/c/Users/juanp]
└─$ ls respaldo
mensaje.txt

┌──(juanp㉿Cloud)-[/mnt/c/Users/juanp]
└─$ rm mensaje.txt

┌──(juanp㉿Cloud)-[/mnt/c/Users/juanp]
└─$ ls respaldo
mensaje.txt

┌──(juanp㉿Cloud)-[/mnt/c/Users/juanp]
└─$ ls juanp
ls: cannot access 'juanp': No such file or directory

┌──(juanp㉿Cloud)-[/mnt/c/Users/juanp]
└─$  grep "Holamundo" mensaje.txt
grep: mensaje.txt: No such file or directory

┌──(juanp㉿Cloud)-[/mnt/c/Users/juanp]
└─$ grep "Holamundo" respaldo/mensaje.txt
Holamundo

┌──(juanp㉿Cloud)-[/mnt/c/Users/juanp]
└─$ echo Juan Pablo Orjuela
Juan Pablo Orjuela
