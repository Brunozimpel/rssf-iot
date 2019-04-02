TARGET = srf06-cc26xx
BOARD = launchpad/cc1350

CONTIKI_PROJECT = hello-world

all: $(CONTIKI_PROJECT)

CONTIKI = ../../contiki
CFLAGS += -g
include $(CONTIKI)/Makefile.include
CC_PREFIX = /home/brunozimp/ti/ccsv8/tools/compiler/gcc-arm-none-eabi-7-2017-q4-major/bin/
#CC_PREFIX = /home/ruanmolgero/ti/ccsv8/tools/compiler/gcc-arm-none-eabi-7-2017-q4-major/bin/
CC      = $(CC_PREFIX)arm-none-eabi-gcc
CPP     = $(CC_PREFIX)arm-none-eabi-cpp
LD      = $(CC_PREFIX)arm-none-eabi-gcc
AR      = $(CC_PREFIX)arm-none-eabi-ar
OBJCOPY = $(CC_PREFIX)arm-none-eabi-objcopy
OBJDUMP = $(CC_PREFIX)arm-none-eabi-objdump
NM      = $(CC_PREFIX)arm-none-eabi-nm
SIZE    = $(CC_PREFIX)arm-none-eabi-size