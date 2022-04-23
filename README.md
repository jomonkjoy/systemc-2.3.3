# systemc-2.3.3
https://www.accellera.org/downloads/standards/systemc

# setting environment variables

```
if [[ ! -d "$SYSTEMC_INCLUDE" ]]; then 
  export SYSTEMC_INCLUDE="/usr/local/systemc-2.3.2/include/"
  echo 'export SYSTEMC_INCLUDE="/usr/local/systemc-2.3.2/include/"' >> ~/.bashrc
  export SYSTEMC_LIBDIR="/usr/local/systemc-2.3.2/lib-linux64/"
  echo 'export SYSTEMC_LIBDIR="/usr/local/systemc-2.3.2/lib-linux64/"' >> ~/.bashrc
fi
```

