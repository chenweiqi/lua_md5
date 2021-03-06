# MD5 - Cryptographic Library for Lua

MD5 offers basic cryptographic facilities for Lua 5.3: a hash (digest)
function, a pair crypt/decrypt based on MD5 and CFB, and a pair crypt/decrypt based
on DES with 56-bit keys.

It is based on keplerproject's md5 module, and changed to support Lua 5.3
http://keplerproject.github.io/md5/

## Buiding on Linux/OSX/BSD

To install on Linux/OSX/BSD, please edit the config file and then call

```
make
make install
```

The last step may require root privileges.

To test, please call

```
make test
```

## Buiding on Windows

Please find md5.sln at /vc6, and execute with the Visual Studio. The min version of VS is vc2010, you can use vc2013, vc2015 and so on. 

Now both x86 and x64 are supported.


## License

MD5 is free software and uses the same license as Lua (MIT). 

The DES 56 C library was implemented by Stuart Levy and uses a MIT license too (check the source).
