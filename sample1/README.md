## help

[windows从零搭建googletest测试工程](https://blog.csdn.net/qq_42769920/article/details/121198844)

## CMake Info
```powershell
[variant] Loaded new set of variants
[kit] Successfully loaded 5 kits from C:\Users\inTree\AppData\Local\CMakeTools\cmake-tools-kits.json
[proc] Executing command: D:\DevelopEnv\msys2\mingw64\bin\gcc.exe -v
[proc] The command: ninja --version failed with error: Error: spawn ninja ENOENT
[proc] The command: ninja-build --version failed with error: Error: spawn ninja-build ENOENT
[main] Configuring folder: sample1 
[proc] Executing command: D:\DevelopEnv\CMake\bin\cmake.EXE --no-warn-unused-cli -DCMAKE_EXPORT_COMPILE_COMMANDS:BOOL=TRUE -DCMAKE_BUILD_TYPE:STRING=Debug -DCMAKE_C_COMPILER:FILEPATH=D:\DevelopEnv\msys2\mingw64\bin\gcc.exe -DCMAKE_CXX_COMPILER:FILEPATH=D:\DevelopEnv\msys2\mingw64\bin\g++.exe -Se:/CSA/Google-Test/Project/sample1 -Be:/CSA/Google-Test/Project/sample1/build -G "Unix Makefiles"
[cmake] Not searching for unused variables given on the command line.
[cmake] CMake Warning (dev) in CMakeLists.txt:
[cmake]   No project() command is present.  The top-level CMakeLists.txt file must
[cmake]   contain a literal, direct call to the project() command.  Add a line of
[cmake]   code such as
[cmake] 
[cmake]     project(ProjectName)
[cmake] 
[cmake]   near the top of the file, but after cmake_minimum_required().
[cmake] 
[cmake]   CMake is pretending there is a "project(Project)" command on the first
[cmake]   line.
[cmake] This warning is for project developers.  Use -Wno-dev to suppress it.
[cmake] 
[cmake] -- The C compiler identification is GNU 12.1.0
[cmake] -- The CXX compiler identification is GNU 12.1.0
[cmake] -- Detecting C compiler ABI info
[cmake] -- Detecting C compiler ABI info - done
[cmake] -- Check for working C compiler: D:/DevelopEnv/msys2/mingw64/bin/gcc.exe - skipped
[cmake] -- Detecting C compile features
[cmake] -- Detecting C compile features - done
[cmake] -- Detecting CXX compiler ABI info
[cmake] -- Detecting CXX compiler ABI info - done
[cmake] -- Check for working CXX compiler: D:/DevelopEnv/msys2/mingw64/bin/g++.exe - skipped
[cmake] -- Detecting CXX compile features
[cmake] -- Detecting CXX compile features - done
[cmake] -- Configuring done
[cmake] -- Generating done
[cmake] -- Build files have been written to: E:/CSA/Google-Test/Project/sample1/build
```


