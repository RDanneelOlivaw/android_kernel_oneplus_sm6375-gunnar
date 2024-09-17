# SPDX-License-Identifier: GPL-2.0-only
# Copyright (C) 2018-2020 Oplus. All rights reserved.

obj-y 	+= platform.o
obj-$(CONFIG_OPLUS_FEATURE_FEEDBACK) 	+= feedback/
obj-$(CONFIG_OPLUS_FEATURE_OPROJECT) 	+= oplus_project/
obj-$(CONFIG_OPLUS_FEATURE_PHOENIX)     += oplus_phoenix/
obj-$(CONFIG_OPLUS_FEATURE_RECORD_MDMRST)     += mdmrst/
obj-$(CONFIG_OPLUS_FEATURE_CMDLINE)     += cmdline_parser/

ifdef CONFIG_OPLUS_SYSTEM_KERNEL_QCOM
obj-$(CONFIG_OPLUS_FEATURE_PROJECTINFO)	+=  project_info/
endif

#ifdef OPLUS_FEATURE_ACM
obj-$(CONFIG_OPLUS_FEATURE_ACM)     += acm/
#endif /* OPLUS_FEATURE_ACM */
#ifdef OPLUS_FEATURE_THEIA
obj-$(CONFIG_OPLUS_FEATURE_THEIA)     += theia/
#endif /* OPLUS_FEATURE_THEIA */
#ifdef OPLUS_FEATURE_MDMFEATURE
obj-$(CONFIG_OPLUS_FEATURE_MDMFEATURE)     += mdmfeature/
#endif /*OPLUS_FEATURE_MDMFEATURE*/
#ifdef OPLUS_FEATURE_MM_FEEDBACK
obj-$(CONFIG_OPLUS_FEATURE_MM_FEEDBACK)         += oplus_mm_fb/
#endif /* OPLUS_FEATURE_MM_FEEDBACK */