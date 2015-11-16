include_directories(${CMAKE_CURRENT_SOURCE_DIR}/include)

add_library(mathLib SHARED src/my_math.cpp)
target_include_directories(mathLib PUBLIC ${CMAKE_CURRENT_SOURCE_DIR}/include)

install(TARGETS mathLib DESTINATION lib)
install(FILES include/my_math.h DESTINATION include)

