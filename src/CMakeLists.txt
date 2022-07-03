add_executable(${PROJECT_NAME} main.cpp)

add_library(header header.cpp)

target_link_libraries(${PROJECT_NAME} PRIVATE header)