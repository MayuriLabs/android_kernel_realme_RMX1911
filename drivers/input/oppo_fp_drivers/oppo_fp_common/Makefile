ifeq ($(CONFIG_OPPO_FINGERPRINT_QCOM),y)
PROJECT_NAME = 19631
endif

DEFS = -DCONFIG_OPPO_FINGERPRINT_PROJCT=$(PROJECT_NAME)
ccflags-y += $(DEFS)

DEFS_PLATFORM = -DCONFIG_OPPO_FINGERPRINT_PLATFORM=6125

ccflags-y += $(DEFS_PLATFORM) -Wno-implicit-function-declaration

obj-y     +=  oppo_fp_common.o

