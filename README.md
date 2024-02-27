# C++ Inference Engine

## How to compile

To compile the program follow these steps:

In the root directory of the project there is a file named CMakeLists.txt with the following content:

```text
cmake_minimum_required(VERSION 3.0)
project(inference-engine)
add_executable(inference-engine src/main.cpp)
```

Now execute the following commands in the terminal:

```zsh
cd build
```

```zsh
cmake ..
```

```zsh
make
```

```zsh
./inference-engine
```
