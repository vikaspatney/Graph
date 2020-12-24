add_library(Graph graph.cpp)
add_executable (graph graph.cpp)

target_include_directories (Graph PUBLIC ${CMAKE_CURRENT_SOURCE_DIR})
