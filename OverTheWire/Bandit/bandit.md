## Over the Wire: Bandit
- Soluções desenvolvidas para esse CTF
- Have Fun!
___
# Level 0
**Para logar no ssh**
~~~
ssh bandit0@bandit.labs.overthewire.org -p 2220
~~~
Daí passamos a senha **bandit0** 
___
# Level 0 --> Level 1
Uma vez logado no level anterior
~~~
bandit0@bandit:~$ ls
readme
bandit0@bandit:~$ cat readme
NH2SXQwcBdpmTEzi3bvBHMM9H66vVXjL
~~~
Para sairmos do level anterior usamos `CRTRL + d`/n 
Usamos essa senha para logarmos no bandit1:
~~~
ssh bandit1@bandit.labs.overthewire.org -p 2220
~~~
