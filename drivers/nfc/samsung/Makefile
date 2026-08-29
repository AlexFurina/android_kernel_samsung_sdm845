#
# Makefile for nfc devices
#

obj-$(CONFIG_SEC_NFC)		+= sec_nfc.o
obj-$(CONFIG_NFC_PN547)		+= pn547.o
obj-$(CONFIG_ESE_P3_LSI)		+= ese_p3.o
obj-y				+= nfc_logger/

ccflags-$(CONFIG_NFC_DEBUG) := -DDEBUG