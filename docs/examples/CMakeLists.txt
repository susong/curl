
link_libraries(libcurl ${CURL_LIBS})

add_executable(examples_debug debug.c)
add_executable(examples_simple simple.c)
add_executable(examples_simplepost simplepost.c)

