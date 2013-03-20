Embedded JSON database library Lua binding
============================================================

**[EJDB Lua API documentation](http://ejdb.org/luadoc/)**

Installation
-----------------------------------------------------

**Required tools/system libraries:**

* gcc
* **Lua >= 5.1**
* EJDB C library **libtcejdb** ([from sources](https://github.com/Softmotions/ejdb#manual-installation) or as [debian packages](https://github.com/Softmotions/ejdb/wiki/Debian-Ubuntu-installation))

**(A) Using luarocks from github sources**

```
git clone https://github.com/Softmotions/ejdb.git
cd ./ejdb/luaejdb
umask 022
make
sudo luarocks install ./luaejdb-1.0-2.linux-x86_64.rock
```




