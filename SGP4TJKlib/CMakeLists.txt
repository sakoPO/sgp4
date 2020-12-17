set(SRCSTJK    
    SGP4TJK.cpp
    )

set(INCSTJK    
    SGP4TJK.h      
    )
    
add_library(sgp4tjk STATIC ${SRCSTJK} ${INCSTJK})
target_include_directories(sgp4tjk PUBLIC ${CMAKE_CURRENT_SOURCE_DIR})
