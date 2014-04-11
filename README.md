libCoolProp
===========

Original from https://github.com/ibell/coolprop (v 4.1.0). I only modified the path of header files and added CMake setting


================================================================================
CoolProp is a thermophysical property database and wrappers for a selection of programming environments

It offers similar functionality to REFPROP, but CoolProp is open-source and free, with flexible licensing terms

It was originally developed by Ian Bell, currently a post-doc at the University of Liege, in Liege, Belgium.

To see whats new, go to http://coolprop.sourceforge.net/changelog.html

================================================================================

If you want to install it, you can use cmake
1. In the libCoolProp dir: mkdir build
2. cmake -DCMAKE_INSTALL_PREFIX=your_path ..
3. make
4. make install
5. Change the setting of LD_LIBRARY_PATH to add you_path/lib
