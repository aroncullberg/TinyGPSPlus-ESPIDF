idf_component_register(
        SRCS "TinyGPS++.cpp"
        INCLUDE_DIRS "include"
        REQUIRES driver freertos nav shared
)