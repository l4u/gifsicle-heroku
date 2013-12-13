Built with
```
vulcan build -v -p /tmp/gifsicle -c "make clean; mkdir /tmp/gifsicle && autoreconf -i && ./configure --disable-gifview --prefix=/tmp/gifsicle && make && make install"
```
