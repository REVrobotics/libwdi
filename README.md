## Build instructions
1. [Install the Windows 11 WDK](https://docs.microsoft.com/en-us/windows-hardware/drivers/download-the-wdk)
2. Open libwdi.sln in Visual Studio 2019 or later
3. Select `Release` and `x64` from the toolbar dropdowns
4. Select `Build` -> `Build Solution`
5. The binary file we care about is located at `x64/Release/examples/wdi-simple.exe`


## Note for the future
If we want or need to switch to a future WDK version, the `WDK_DIR` definition in `mscv/config.h` file may need to be updated.
