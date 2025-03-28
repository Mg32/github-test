# GitHub CI/CD Test

## How to Build

### Windows

Install Visual Studio 2019 and vcpkg, and then run the following commands.

```powershell
cmake --preset=default -G "Visual Studio 16 2019" -A x64 -T ClangCL -DCMAKE_BUILD_TYPE=Release -DVCPKG_TARGET_TRIPLET=x64-windows-static-md
cmake --build build --config Release
```
