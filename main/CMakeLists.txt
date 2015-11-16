add_executable(app main.cpp)
TARGET_LINK_LIBRARIES(app mathLib)

install(TARGETS app DESTINATION bin)
