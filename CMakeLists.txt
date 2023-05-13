idf_component_register(SRCS "apsta.c"
                    INCLUDE_DIRS "."
                    REQUIRES
                        freertos
                        esp_system
                        esp_wifi
                        esp_event
                        spi_flash
                        nvs_flash
                        lwip
                        wpa_supplicant)