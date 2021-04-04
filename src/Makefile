# SPDX-License-Identifier: GPL-2.0-only
#
#  Makefile for the Linux Controller Area Network SPI drivers.
#


obj-m += mcp251x.o

all:
	make -C /lib/modules/$(shell uname -r)/build M=$(PWD) modules

clean:
	make -C /lib/modules/$(shell uname -r)/build M=$(PWD) clean
