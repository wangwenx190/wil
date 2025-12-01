add_library(WIL INTERFACE)
add_library(WIL::WIL ALIAS WIL)
set_target_properties(WIL PROPERTIES VERSION "1.0.260126.7")
target_include_directories(WIL INTERFACE
    "${CMAKE_CURRENT_SOURCE_DIR}/include"
    "${CMAKE_CURRENT_SOURCE_DIR}/include/wil"
)
