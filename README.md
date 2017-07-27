# Atom URL Handler on Linux (Ubuntu based)

Enables Atom to open URL Scheme atm:// and txmt:// like these:

`atm://open/?url=file:///etc/passwd&line=10&column=2`

Note: We would have liked to have used atom:// as a protocol, but that is already taken and used for other purposes by Atom itself.


## Installation

Download [latest release](https://github.com/eclemens/atom-url-handler/archive/master.zip).

Unzip it, then:
``` bash
cd atom-url-handler-master
bash install
```


## Test it

Open a new tab on your browser and type: atm://open/?url=file:///etc/hosts


## Thanks

Algorich for his [work](https://github.com/algorich/sublime-url-handler).
Thierry G. for his [post](http://goo.gl/bO6AZ).
