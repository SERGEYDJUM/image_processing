add_library(sharedlib SHARED SharedLib.cc SharedLib.h)
target_include_directories(sharedlib PUBLIC ${CMAKE_CURRENT_SOURCE_DIR})
target_link_libraries(sharedlib PUBLIC opencv_core)