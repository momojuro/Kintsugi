# SPDX-License-Identifier: GPL-2.0
dtb-y += exynos/dtbo/exynos7885.dtb

dtb-$(CONFIG_MACH_EXYNOS7885_A30_GLOBAL) := \
	exynos/dtbo/exynos7904-a30_cis_open_00.dtbo \
	exynos/dtbo/exynos7904-a30_cis_open_01.dtbo \
	exynos/dtbo/exynos7904-a30_cis_open_02.dtbo \
	exynos/dtbo/exynos7904-a30_kor_single_00.dtbo \
	exynos/dtbo/exynos7904-a30_kor_single_01.dtbo \
	exynos/dtbo/exynos7904-a30_kor_single_02.dtbo \
	exynos/dtbo/exynos7904-a30_swa_open_00.dtbo \
	exynos/dtbo/exynos7904-a30_swa_open_01.dtbo \
	exynos/dtbo/exynos7904-a30_swa_open_02.dtbo

ifeq ($(CONFIG_MACH_EXYNOS7885_A30_GLOBAL),y)
always         := $(dtb-y) $(dtbo-y)
clean-files    := *.dtb *.dtbo
endif
