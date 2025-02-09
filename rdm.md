```Bash
rm -rf pycdc;git clone https://github.com/ansyso/pycdc.git
cd pycdc;mkdir build;cd build;cmake ..
make;cp pycdc pycdas $PREFIX/bin/
