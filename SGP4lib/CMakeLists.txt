set(SRCS
    SGP4.cpp    
    )

set(INCS
    SGP4.h          
    )

add_library(sgp4 STATIC ${SRCS} ${INCS})
target_include_directories(sgp4 PUBLIC ${CMAKE_CURRENT_SOURCE_DIR})
