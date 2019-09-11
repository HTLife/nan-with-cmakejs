


To use Boost, we need to modify the following parts.

1. Add `FIND_PACKAGE( Boost 1.65 COMPONENTS program_options REQUIRED )` and `${Boost_LIBRARIES}` into CMakeLists.txt
2. Add the following code into hello.cc
```cpp
#include <iostream>
#include <boost/format.hpp>

...
std::cout << boost::format("%s\n") % "Hello, World";
```




# How to use
```bash
npm install
cmake-js build
node hello.js
```

## output
```
Hello, World
world
```