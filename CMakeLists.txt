add_executable(assert src/main.c)

target_link_libraries(assert
    libsel4
    libsel4printf
    libsel4startstop
)

add_dependencies(assert sel4_kernel)
