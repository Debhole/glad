project(Glad)

set(SOURCE_FILES
    include/glad/glad.h
    include/KHR/khrplatform.h
    src/glad.c)

add_library(glad ${SOURCE_FILES})

target_include_directories(glad PUBLIC include)