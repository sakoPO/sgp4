cmake_minimum_required (VERSION 2.6)

set(CMAKE_CXX_FLAGS_DEBUG  "-g")
set(CMAKE_BUILD_TYPE "Debug")
project (sgp4_comparison_test)




add_subdirectory(SGP4lib)
add_subdirectory(SGP4TJKlib)

add_subdirectory(tests/testSGP4TJK)
add_subdirectory(tests/testSGP4)






