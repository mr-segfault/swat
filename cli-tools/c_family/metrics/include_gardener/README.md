Build dependecies

    cmake

Runtime Dependencies:

    boost

Test Dependencies:

    Python 3.x
    PyUnit
    PyGraphviz
    PyGraphml
    XMLRunner

Note: pip requires GraphViz development files to install PyGraphViz and PyGraphML. To install these libraries using apt-get, run sudo apt-get libgraphviz-dev

git clone https://github.com/feddischson/include_gardener.git;
cd include_gardener;
mkdir build;
cd build;
cmake ..;
make;
make doc;
make install;



