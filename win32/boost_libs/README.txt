How to build:
1. Get a full boost distribution with a version matching the headers included here, unpack
2. Include the path to mingw from code::blocks in the standard PATH variable, start a command prompt
3. verify that 2 went correctly by typing "gcc --version"
4. navigate to root of boost source
5. type "bootstrap.bat gcc"
6. edit project-config.jam, replace msvc with gcc
7. run ".\b2.exe --with-thread --with-system"
8. Library files are in stage\lib