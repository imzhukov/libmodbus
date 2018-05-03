set(SOURCE_libmodbus src/modbus.c
src/modbus-serial.c
src/modbus-data.c
src/modbus-rtu.c
src/modbus-tcp.c
src/modbus-ascii.c
)
include_directories(.)
add_library(libmodbus STATIC ${SOURCE_libmodbus})
