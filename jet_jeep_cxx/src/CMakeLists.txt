add_executable(bin_main main.cpp)

add_library(hello STATIC hello.cpp)

target_link_libraries(bin_main hello)