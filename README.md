ngui
-------------------
ngui is an HTML 5 based GUI toolkit for the Go language.

How to build on Windows platform (Win7 32/64-bit).
-------------------

1. Make sure you have installed windows-386 version of Go (for example: 1.3.3)
2. Install mingw and add C:\MinGW\bin to PATH. You can install mingw using mingw-get-setup.exe. Select packages to install: "mingw-developer-toolkit", "mingw32-base", "msys-base". CEF2go was tested and works fine with GCC 4.8.1. You can check gcc version with "gcc --version".
3. Download CEF 3 branch 2171 revision 1897 binaries: [cef_binary_3.2171.1897_windows32.7z](http://pan.baidu.com/s/1eQkYTYa)
   Copy Release/* to cef2go/Release
   Copy Resources/* to cef2go/Release
4. install github.com/nvsoft/cef and github.com/nvsoft/wingui
   go get github.com/nvsoft/cef
   go get github.com/nvsoft/wingui
5. Run [build.bat] in the directory
6. Run ngui.exe in the "Release" directory


Author email: 
-------------------
> 529808348@qq.com JianSu  China
> xulei8@qq.com  Beijing China