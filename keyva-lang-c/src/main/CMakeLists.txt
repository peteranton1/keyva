cmake_minimum_required(VERSION 3.10)

project(keyva_lang)

add_executable(keyva_lang main.c kvstdlib.c kvstdlib.h kvlang_internals.h debug_print.h)

target_link_libraries(keyva_lang PRIVATE m)
