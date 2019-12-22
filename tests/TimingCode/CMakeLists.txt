cmake_minimum_required(VERSION 3.0)
set(CMAKE_C_STANDARD 99)
project(GreenFFTs LANGUAGES C)


add_executable( ffttiming   fftTiming.c )
add_executable( rffttiming  rfftTiming.c )

target_link_libraries(ffttiming  GreenFFT)
target_link_libraries(rffttiming GreenFFT)
