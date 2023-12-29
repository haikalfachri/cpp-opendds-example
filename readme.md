## OpenDDS Example Using C++ and CMake

> **_Note:_** This readme is for Windows with WSL terminal and using OpenDDS with CMake method.

1. Set environment every time open a new WSL terminal
    ```
    source 'path/to/opendds/setenv.sh'
    ```
    Example:
    ```
    source '/mnt/c/OpenDDS-3.26.1/setenv.sh'
    ```

2. Move to src directory
    ```
    cd src
    ```

3. Generate .idl file using `$path/to/opendds_idl/path/to/.idl`
    
    ```
    $DDS_ROOT/bin/opendds_idl ./HelloWorld.idl
    ```
    After the process is complete, 3 files will appear with the extension `<idl_filename>TypeSupport.idl, .cpp, .h`

4. Cmake quick start 
    ```
    cmake .
    ```
5. Cmake build
    ```
    cmake --build .
    ```
    After processing is complete, many files will appear in the `opendds_generated` folder and also publisher and subscriber files to execute.