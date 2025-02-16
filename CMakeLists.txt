add_library(tinygps-espidf STATIC
    TinyGPSPlus/src/TinyGPS++.cpp
)

target_include_directories(tinygps-espidf PUBLIC
    TinyGPSPlus/src
    include
)
