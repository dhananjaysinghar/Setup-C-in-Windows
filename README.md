# Setup-C-in-Windows

Steps to setup C & C++
```
1. Install https://www.msys2.org/
	open the app
        command: pacman -Syu
2. open MSYS2 MSYS
      command: pacman -Su

3.  open MSYS2 MinGW 64-bit

4. Run this command  "pacman -Ss gcc" and search for 64 bit collection(C, C++, OpenMP) : mingw-w64-x86_64-gcc

5 run command pacman -S mingw-w64-x86_64-gcc

6. gcc --version

7. g++ --version

8. For debugger: Run this command  "pacman -Ss gdb" and search for 64 bit collection(C, C++, OpenMP) : mingw-w64-x86_64-gdb
 
9. pacman -S mingw-w64-x86_64-gdb

10. gdb --version

11. add path to gcc as env variable: C:\msys64\mingw64\bin

12. Install VS code : https://code.visualstudio.com/download

13. Install extensions: C,C++ (https://marketplace.visualstudio.com/items?itemName=ms-vscode.cpptools)

14. Install extensions: C,C++ extension (https://marketplace.visualstudio.com/items?itemName=ms-vscode.cpptools-extension-pack)

15. Install extensions: Code Runner (https://marketplace.visualstudio.com/items?itemName=formulahendry.code-runner)
```
