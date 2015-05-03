ogre-sample
===========

Ogre3D project template is ~~ready to be used~~ (make fork and pull requests to make it usable)
in experimental projects to learn Ogre3D, featuring:

* Oriented to Ogre3D 1.9, 1.10 (for Ogre3D 2.1 look [here](https://github.com/rafis/ogre2-sample))
* OIS Mouse and Keyboard
* Basic camera controller (striped from OgreBites)
* No GUI/HUD/SDK Tray

Installation on Windows
-----------------------

Change project name in CMakeLists.txt and use `cmake-gui`.

Installation on Linux/OS X
--------------------------

For example you want to create `ogre-myapp1`, rough steps are following:

    git clone https://github.com/rafis/ogre-sample.git
    cp -ar ogre-sample ogre-myapp1
    cd ogre-myapp1
    sed -i 's/ogre-sample/ogre-myapp1/g' CMakeLists.txt
    cd ..
    mkdir ogre-myapp1-bin
    cd ogre-myapp1-bin
    cmake ../ogre-myapp1 -DCMAKE_BUILD_TYPE="Debug"
    make
    cd ogre-myapp1/bin
    ./ogre-myapp1

Other templates
---------------

* [http://www.ogre3d.org/tikiwiki/Building+Your+Projects+With+CMake](http://www.ogre3d.org/tikiwiki/Building+Your+Projects+With+CMake)
* [https://github.com/scrawl/ogre-framework](https://github.com/scrawl/ogre-framework)
