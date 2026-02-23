# textscan

A small C++17 console tool (Windows) to analyze text files in a directory.
Planned features: count files/lines/words and show top N most frequent words.

## Build (CMake + Ninja + clang++)
```powershell
cmake -S . -B build -G Ninja -DCMAKE_CXX_COMPILER=clang++ -DCMAKE_BUILD_TYPE=Debug
cmake --build build
```

##Run
```powershell
.\build\textscan.exe
```
