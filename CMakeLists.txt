project (c11threads)

file(GLOB c11threads_sources ./**.c)
set(c11threads ${c11threads_sources})

add_library(c11threads ${c11threads})
target_link_libraries(c11threads)