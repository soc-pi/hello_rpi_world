# Create a library called "hello_rpi_world"
add_library(hello_rpi_world_lib hello_rpi_world.c)

# Specify include directories for the library
target_include_directories(hello_rpi_world_lib PUBLIC ${CMAKE_CURRENT_SOURCE_DIR}/../../include)
