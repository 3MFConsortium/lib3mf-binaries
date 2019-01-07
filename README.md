# lib3mf-binaries

This repository contains regular binary builds of the develop branch of the [https://github.com/3MFConsortium/lib3mf/tree/develop](https://github.com/3MFConsortium/lib3mf) repository in form of a standalone, binary SDK with examples: [lib3mf_sdk.zip](lib3mf_sdk.zip)

This SDK package contains a CMake project-setup for several examples. To use them, follow these steps:
1. Download [lib3mf_sdk.zip](lib3mf_sdk.zip)
2. Extract the archive
3. Navigate to `Examples` and run
	- `GenerateMake.sh` on Linux or MAC
	- `GenerateVS2015.bat` on Windows
4. Build the examples:
	- Navigate to `build` and run <br> `cmake --build .`
5. Run the example-exectuables in the `build`-folder
