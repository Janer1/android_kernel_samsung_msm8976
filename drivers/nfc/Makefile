#
# Makefile for nfc devices
#

obj-$(CONFIG_NFC_PN544)		+= pn544/
obj-$(CONFIG_NFC_MICROREAD)	+= microread/
obj-$(CONFIG_NFC_PN533)		+= pn533.o
obj-$(CONFIG_NFC_WILINK)	+= nfcwilink.o
obj-$(CONFIG_NFC_MEI_PHY)	+= mei_phy.o
obj-$(CONFIG_NFC_QNCI)		+= nfc-nci.o
obj-$(CONFIG_NFC_NQ)		+= nq-nci.o
obj-$(CONFIG_SEC_NFC)           += sec_nfc.o
obj-$(CONFIG_ESE_P3)           += ese_p3.o
obj-$(CONFIG_NFC_PN547_ESE_SUPPORT)        += p61.o
obj-$(CONFIG_NFC_PN547)     += pn547.o

ccflags-$(CONFIG_NFC_DEBUG) := -DDEBUG
