# BEAST

To install, compile and run BEAST on School of Computer Science machines follow the following steps:

git clone git@github.com:uol-school-of-computing/BEAST.git
cd BEAST
mkdir build
cd build
cmake ..
make -j 16
cd bin
./beast ../projects/libdemos.so
