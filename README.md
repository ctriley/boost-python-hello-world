# boost-python-hello-world
Boost Python Hello World for Cmake 3.12+


### Installation
```sh
brew install python3 cmake boost boost-python3
mkdir build
cd build && cmake .. && make 
```

### Usage
```
cd build
python3
```
In the python shell
```
> import greet_ext
> greet_ext.greet()
```

### Notes
Has been tested on Intel and Apple Silicon Macs on macOS 12.1, as well as Ubuntu 20.04LTS.
