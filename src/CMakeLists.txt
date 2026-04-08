

add_executable(
    exampleproject
    main.cpp
)

target_include_directories(
    exampleproject
    PRIVATE
    ${CMAKE_CURRENT_SOURCE_DIR}
)

install(
    TARGETS exampleproject
    RUNTIME DESTINATION ${CMAKE_INSTALL_BINDIR}
)