cmake_minimum_required(VERSION 3.2.0)

project(code_practice)

add_compile_options(-std=c++11)

set(CMAKE_RUNTIME_OUTPUT_DIRECTORY ${PROJECT_SOURCE_DIR}/binary)
add_subdirectory(ADT_Stack)
add_subdirectory(ADT_Queue)
add_subdirectory(Sorting)
add_subdirectory(Permutation_Combination)
add_subdirectory(String)
add_subdirectory(CompleteBinaryTree)
add_subdirectory(LinkedList)
add_subdirectory(ChainingHashTable_Mod)
add_subdirectory(Movie)
add_subdirectory(Fibonacci)
add_subdirectory(Subset)
add_subdirectory(ShortestPath)
