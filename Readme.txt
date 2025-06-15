0. install dependencies in ubuntu 20

    sudo apt install libxft2 libxft2:i386 lib32ncurses6
    sudo apt install libxext6
    sudo apt install libxext6:i386

1. lic gen

    python2 mgclicgen.py <hostid>

license.dat is generated


2. install questa sim

    ./questa_sim-2021.2_1.aol

3. copy file into install dir, then execute

   ./pubkey_verify -y

4. config env variable

    export PATH="/path/to/questasim/linux_x86_64":$PATH
    export PATH="/path/to/questasim/RUVM_2021.2":$PATH
    export LM_LICENSE_FILE="/path/to/license.dat":$LM_LICENSE_FILE
=================
www.downloadly.ir