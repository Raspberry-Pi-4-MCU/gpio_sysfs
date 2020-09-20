## sysfs for linux, using shared library 

- build:
```
make
```

- test:
```
make test
```

- install (install to /usr/lib and /usr/include):
```
sudo make install
```

- clear:
```
make clean
```

- uninstall:
```
sudo make uninstall
```

- using shared library(after install):
```
gcc your_c_source_code -lsysfstest -o your_ELF_name
```

- bash call(after install)
```
sudo sysfstest
```
