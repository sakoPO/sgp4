set(SRCS
    TestSGP4.cpp)

add_executable(TestSGP4
               ${SRCS})
target_link_libraries(TestSGP4
                      sgp4)
    

