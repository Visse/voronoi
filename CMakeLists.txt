
add_library(jc_voronoi STATIC
    src/jc_voronoi.h
    src/jc_voronoi.c
)

target_include_directories(jc_voronoi PUBLIC src/)
