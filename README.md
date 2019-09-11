To use C++ libraries, there are several optional nowadays.

1. nan
2. napi
3. node-addon-api

And you can get all the related code here ([Node.js Addon Examples](https://github.com/nodejs/node-addon-examples)).

However, it's more convenient to use CMake system for a larger C++ project.  Then 'cmake-js' become handy.  [cmake.js with nan](https://github.com/cmake-js/cmake-js/wiki/TUTORIAL-01-Creating-a-native-module-by-using-CMake.js-and-NAN)

In this repositories, I provide some simple example to combine nan and cmake-js together.  Hope this will help you to integrate Node.js with C++.

