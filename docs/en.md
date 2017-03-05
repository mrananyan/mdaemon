mDaemon install and usage guide
===============================
0. Open terminal as root
```
sudo -i
```
1. Go to /usr/local/src/
```
cd /usr/local/src/
```
2. Clone it
```
git clone https://github.com/mrananyan/mdaemon.git
```
3. Go to /usr/local/src/mdaemon
```
cd mdaemon/
```
4. Compile it by GCC
```
gcc mdaemon.c -o mdaemon
```
5. Copy to /usr/sbin/
```
cp mdaemon /usr/sbin/mdaemon
```
6. Enjoy *_*
```
mdaemon --help
```
