mDaemon֊ի տեղադրման ձեռնարկը
===============================
Բացեք տերմինալը root֊ի թույլտվությաբ
```
sudo -i
```
Բացեք /usr/local/src/ պանակը cd հրամանով
```
cd /usr/local/src/
```
Պատճենեք գիթ պահոցից
```
git clone https://github.com/mrananyan/mdaemon.git
```
Բացեք /usr/local/src/mdaemon պանակը պանակը cd հրամանով
```
cd mdaemon/
```
Կոմպիլացրեք GCC֊ի օգնությամբ։
```
gcc mdaemon.c -o mdaemon
```
Պատճենեք կոմպիլացված mdaemon ֆայլը /usr/sbin/ պանակի մեջ
```
cp mdaemon /usr/sbin/mdaemon
```
Վայելեք ^_^
```
mdaemon --help
```
