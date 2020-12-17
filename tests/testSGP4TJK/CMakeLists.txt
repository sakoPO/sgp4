set(SRCS
    TestSGP4.cpp)

add_executable(TestSGP4TJK
	       ${SRCS})

target_link_libraries(TestSGP4TJK
                      sgp4tjk)
    

