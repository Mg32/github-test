# GitHub CI/CD Test

## How to Build

### Windows

Install Visual Studio 2019 and vcpkg, and then run the following commands.

```powershell
"C:\Program Files (x86)\Microsoft Visual Studio\2019\Community\VC\Auxiliary\Build\vcvars64.bat"  # x64 Native Tools Command Prompt for VS 2019
cmake --preset=default
cmake --build build
```
