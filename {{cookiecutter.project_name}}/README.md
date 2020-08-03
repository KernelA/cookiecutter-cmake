# {{cookiecutter.project_name}}

## Description


## Requirements

1. CMake {{cookiecutter.cmake_min_ver}} or higher.
2. Compiler with support C++{{cookiecutter.cpp_standard}}.

## How to run

Create new directory `build`.

```
mkdir build
cmake -S . -B .\build
```

Run CMake:
```
cmake --build .\build --config Release -j 4 --target <input_target>
```
