This is a fork of the [yaml-cpp](https://code.google.com/p/yaml-cpp/)
project with modest edits for bundling in an existing CMake project.

Usage
-----
I wanted to be able to bundle `yaml-cpp` like so:

1. Clone it as a subdirectory.
2. In CMakeLists.txt, add the subdirectory. Then, I should be able to:

        include_directories(${yaml-cpp_INCLUDE_DIRS})
        ...
        target_link_libraries(my_app yaml-cpp)
3. Use `yaml-cpp` at your will. See the project site for [detailed documentation](https://code.google.com/p/yaml-cpp/w/list).

License
-----
[MIT License](http://www.opensource.org/licenses/mit-license.php).
