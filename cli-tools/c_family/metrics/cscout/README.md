CScout:
    Clone the source code from GitHub:
    git clone https://github.com/dspinellis/cscout/ 
    Enter the CScout directory:
    cd cscout;
    Run make:
    make;
    Run make test (optional, but highly recommended):
    make test;
    Run sudo make install:
    sudo make install; 

git clone https://github.com/dspinellis/cscout/; cd cscount; make; sudo make install

 If you want the installation to use a different directory hierarchy than the default /usr/loca , you can specify this on the command line with the INSTALL_PREFIX variable. For example, you run make install INSTALL_PREFIX=/home/mydir to install CScout under your home directory or sudo make install INSTALL_PREFIX=/usr to install CScout under /usr. 
