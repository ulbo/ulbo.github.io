Notizen für Horizon EDA
=======================

## Compilieren unter Solus Linux

Tools installieren:

    $ sudo eopkg install git
    $ sudo eopkg install -c system.devel
    $ sudo eopkg install libgtkmm-3-devel cairomm-devel librsvg-devel util-linux-devel yaml-cpp-devel sqlite3-devel libboost-devel zeromq-devel cppzmq-devel glm binutils-gold libgit2-devel curl-devel opencascade-ce-devel libzip-devel podofo-devel


Source herunterladen und Build starten:

    $ mkdir -p ~/tmp
    $ cd ~/tmp
    $ git clone https://github.com/carrotIndustries/horizon.git
    $ cd horizon
    $ make -j4


Starten:

    $ ~/tmp/horizon/build/horizon-eda
