|- main.cpp
|- CMakeLists.txt
|- build/


CMakeLists.txt 

```cmake
cmake_minimum_required(VERSION 3.1)
project(hello_world CXX)
add_executable(main_app main.cpp)
```
1. specify the version of cmake
2. define the project name and specify the language you use. in this case c++ is selected.
3. specify execute file name and specify file which consist execute file.

making build dir, clarify the builed file. 

```bash
cd build
```

specify CMakeLists.txt by writting .. where CMakeLists.txt exists
execute configure and generate proccess
```bash
cmake ..
```


build
in the background specifically in Mac os environment, make command log will be shown.
```bash
cmake --build .
```

execute
```bash
./main_app
```

