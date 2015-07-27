# Galaxy FDS C++ SDK User Guide

## Build
- The following third-party libraries are required to being installed to build properly:
* Poco, only need its Foundation/Net/JSON/NETSSL_OpenSSL module. Refer http://pocoproject.org for installation.
* OpenSSL.
- After the dependencies are installed properly, run the following command to build:
```
$ cd ${SDK_SRC_DIR}
$ mkdir cmake_build
$ cd cmake_build
$ cmake ..
$ make
```

## Usage
Please refer to the sample/test code to get start.
