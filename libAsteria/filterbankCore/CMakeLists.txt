﻿cmake_minimum_required (VERSION 3.8)
set (CMAKE_CXX_STANDARD 11)

project ("filterbankCore")

include_directories("./include")

add_library(filterbankCore "./src/filterbankCore.cpp" "./src/filterbankFile.cpp" "./src/filterbankStdio.cpp")