C is a language that need compiler AND IDE. There are two things needed to be installed: minGW and one of the IDE (VSCode is selected).

MinGW (to prevent "the file has been downloaded incorrectly" error)
1. Go to this website to download MinGW. https://sourceforge.net/projects/mingw-w64/
2. Select win 32 dwarf version.
3. Download and unzip the file.
4. copy the mingw32 directory to C:\
5. find the bin directory in the mingw32 directory
6. copy the address link
7. search for "edit environment variable" in windows
8. find the "path" variable at the bottom, edit, and new
9. add the copied address link
10. confirm
11. open cmd, type gcc --version
12. if there are info shown up, success.

VSCode

