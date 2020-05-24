Notizen für Horizon EDA
=======================

## Compilieren unter Solus Linux

Tools installieren:

    $ sudo eopkg install git
    $ sudo eopkg install -c system.devel
    $ sudo eopkg install libgtkmm-3-devel cairomm-devel librsvg-devel util-linux-devel yaml-cpp-devel sqlite3-devel libboost-devel zeromq-devel cppzmq-devel glm binutils-gold libgit2-devel curl-devel opencascade-ce-devel libzip-devel podofo-devel

TODO: Aktualisieren, ist veraltet!


Source herunterladen und Build starten:

    $ mkdir -p ~/tmp
    $ cd ~/tmp
    $ git clone https://github.com/carrotIndustries/horizon.git
    $ cd horizon
    $ make -j4


Pool und Testprojekt herunterladen:
Nicht mehr nötig; das kann Horizon selbst.

    $ cd ~/tmp
    $ git clone https://github.com/carrotIndustries/horizon-pool.git
    $ git clone https://github.com/carrotIndustries/horizon-test-project.git


Starten:

    $ ~/tmp/horizon/build/horizon-eda
