# hello-world
cmake gcov example

This is small example which depicts usage of gcov in c++ project with cmake.

mkdir build
cd build
cmake ..
make
./sample

It generates .gcno and .gcda files in build/CMakeFiles/sample.dir/.
Use lcov command to scan these files and get coverage data.
