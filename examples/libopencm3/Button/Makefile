CFILES = main.c
PROJECT = button
BUILD_DIR = build

DEVICE=STM32L072KZTx
LIB_TARGET = stm32/l0

# Path to the libopencm3 source
OPENCM3_DIR = ../lib/libopencm3

include $(OPENCM3_DIR)/mk/genlink-config.mk
include ../lib/rules.mk
include $(OPENCM3_DIR)/mk/genlink-rules.mk