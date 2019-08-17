# travis_qmake_gcc_cpp14_boost_xml

Minimal project that uses qmake, GCC, C++14, Boost and XML and is tested by Travis CI

Branch|[![Travis CI logo](TravisCI.png)](https://travis-ci.org)
---|---
master|[![Build Status](https://travis-ci.org/richelbilderbeek/travis_qmake_gcc_cpp14_boost_xml.svg?branch=master)](https://travis-ci.org/richelbilderbeek/travis_qmake_gcc_cpp14_boost_xml)

This GitHub is part of:

 * [the Travis C++ Tutorial](https://github.com/richelbilderbeek/travis_cpp_tutorial)

The goal of this project is to have a clean Travis CI build, with specs:
 * Build system: `qmake`
 * C++ compiler: `gcc`
 * C++ version: `C++14`
 * Libraries: `STL`, `Boost` and XML
 * Code coverage: none
 * Source: one single file, `main.cpp`

Used example code from [this Boost example code](https://www.boost.org/doc/libs/1_70_0/libs/property_tree/examples/debug_settings.cpp).

More complex builds:
 * [![Build Status](https://travis-ci.org/richelbilderbeek/travis_qmake_gcc_cpp17_boost_xml.svg?branch=master)](https://travis-ci.org/richelbilderbeek/travis_qmake_gcc_cpp17_boost_xml) Use Boost and XML: [travis_qmake_gcc_cpp17_boost_xml](https://www.github.com/richelbilderbeek/travis_qmake_gcc_cpp17_boost_xml)

Simpler builds:
 * [![Build Status](https://travis-ci.org/richelbilderbeek/travis_qmake_gcc_cpp14_boost.svg?branch=master)](https://travis-ci.org/richelbilderbeek/travis_qmake_gcc_cpp14_boost) Add `Boost.Graph`: [travis_qmake_gcc_cpp14_boost](https://www.github.com/richelbilderbeek/travis_qmake_gcc_cpp14_boost)

