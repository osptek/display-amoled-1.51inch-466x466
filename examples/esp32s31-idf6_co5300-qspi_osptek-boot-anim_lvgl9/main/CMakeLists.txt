idf_component_register(SRCS "main.c"
                    INCLUDE_DIRS "."
                    REQUIRES "esp_lcd_touch_cst820")

spiffs_create_partition_assets(
    efc
    "../assets"
    FLASH_IN_PROJECT
    MMAP_FILE_SUPPORT_FORMAT ".efc"
)