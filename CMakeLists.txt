cmake_minimum_required(VERSION 3.16)
project(BrainDamaged)

set(CMAKE_CXX_STANDARD 20)

add_executable(BrainDamagedVM bdvm/src/Main.cpp bdvm/include/BrainDamagedVM.hpp bdvm/src/BrainDamagedVM.cpp bdvm/include/Bytecode.hpp bdvm/include/Types.hpp)
add_executable(BrainFuckCompiler bfc/src/Main.cpp bfc/src/BrainFuckCompiler.cpp bfc/include/Types.hpp bfc/include/BrainFuckCompiler.hpp)