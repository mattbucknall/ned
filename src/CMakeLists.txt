add_executable(ned main.c ned.c)

set_target_properties(ned PROPERTIES
    RUNTIME_OUTPUT_DIRECTORY ${CMAKE_BINARY_DIR}
)
