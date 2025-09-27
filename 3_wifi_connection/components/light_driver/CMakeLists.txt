
idf_component_register(SRCS "./light_driver.c" "./iot_led.c"
                    INCLUDE_DIRS "." 
                    			 "./include"
                    			 "$ENV{IDF_PATH}/components/esp_driver_ledc/include"
                    			 "$ENV{IDF_PATH}/components/esp_driver_gpio/include"
                    			 "$ENV{IDF_PATH}/components/driver/deprecated"
                    REQUIRES app_storage
)
