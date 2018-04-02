$ sudo apt-get update

$ sudo apt-get install gcc g++ python python-dev mercurial bzr gdb valgrind gsl-bin libgsl0-dev libgsl0ldbl flex bison 
tcpdump sqlite sqlite3 libsqlite3-dev libxml2 libxml2-dev libgtk2.0-0 libgtk2.0-dev uncrustify doxygen graphviz imagemagick
python-pygraphviz python-kiwi python-pygoocanvas libgoocanvas-dev python-pygccxml --fix-missing

cd  
mkdir ns3
cd ns3
wget http://www.nsnam.org/release/ns-allinone-3.26.tar.bz2
tar xjf ns-allinone-3.26.tar.bz2
cd ns-allinone-3.26/
ls

./build.py --enable-examples --enable-tests

If the build is successful then it will give output
 "Build finished successfully".

 
cd ns-3.26
 ./test.py

 ./waf --run first
