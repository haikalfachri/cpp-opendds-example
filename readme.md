## TEMP README

1. Tiap buka terminal wsl wajib setenv dulu
source '/mnt/c/OpenDDS-3.26.1/setenv.sh'

2. Generate .idl pake $path/to/opendds_idl /path/to/.idl file di folder src
```
cd src
```
```
'/mnt/c/OpenDDS-3.26.1/bin/opendds_idl' '/mnt/c/Users/haika/OneDrive/Documents/MSIB5/cpp-opendds/src/HelloWorld.idl'
```
ntar muncul 3 file nama ujungnya ada xxxTypeSupport.idl, .cpp, .h

3. Cmake quick start 
```
cmake .
```
4. Cmake build
```
cmake --build .
```
ntar muncul banyak file di folder opendds_generated sama muncul file publisher dan subscriber tanpa ekstensi