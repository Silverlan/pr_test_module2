cmake_minimum_required(VERSION 3.12)

include("./CMakeShared.txt")

set(PROJ_NAME pr_test)

project(${PROJ_NAME} CXX)

link_generic_module_libraries()
register_pragma_module(${PROJ_NAME})
