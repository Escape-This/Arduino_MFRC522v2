file(GLOB_RECURSE srcs "src" *.cpp *.c)

idf_component_register(
    SRCS ${srcs}
    INCLUDE_DIRS "src"
    REQUIRES arduino-esp32
)