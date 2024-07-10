
idf_component_register(
    SRCS "rtdb_example.cpp"
    REQUIRES esp_firebase esp_wifi nvs_flash
    INCLUDE_DIRS "." 
)
