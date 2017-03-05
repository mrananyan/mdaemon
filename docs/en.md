mDaemon install and usage guide
===============================
Open terminal as root
```
sudo -i
```
Go to /usr/local/src/
```
cd /usr/local/src/
```
Clone it
```
git clone https://github.com/mrananyan/mdaemon.git
```
Go to /usr/local/src/mdaemon
```
cd mdaemon/
```
Compile it by GCC
```
gcc mdaemon.c -o mdaemon
```
Copy to /usr/sbin/
```
cp mdaemon /usr/sbin/mdaemon
```
Enjoy ^_^
```
mdaemon --help
```
