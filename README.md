# textscan

A small C++17 console tool (Windows) to analyze text files.

## Current
- Builds with CMake + Ninja + clang++
- Basic executable skeleton

## Planned
- Analyze `.txt` files: count files/lines/words
- Top N most frequent words
- JSON/CSV report
- Unit tests

## Requirements
- clang++ (MSYS2 clang64)
- CMake
- Ninja

## Build (CMake + Ninja + clang++)
```powershell
cmake -S . -B build -G Ninja -DCMAKE_CXX_COMPILER=clang++ -DCMAKE_BUILD_TYPE=Debug
cmake --build build
```

## Run
```powershell
.\build\textscan.exe
```
