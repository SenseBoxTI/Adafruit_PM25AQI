cmake_minimum_required(VERSION 3.5)

idf_component_register(SRCS "Adafruit_PM25AQI.cpp"
                       INCLUDE_DIRS "."
                       REQUIRES arduino adafruit_busio)

project(adafruit_pm25aqi)
