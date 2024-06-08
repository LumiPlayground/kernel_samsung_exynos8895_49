# SPDX-License-Identifier: GPL-2.0
ifeq ($(CONFIG_SOC_EXYNOS8895),y)
dtb-$(CONFIG_MACH_EXYNOS8895_DREAMLTE_EUR_OPEN) :=  \
    exynos8895/exynos8895-dreamlte_eur_open_10.dtb
dtb-$(CONFIG_MACH_EXYNOS8895_DREAM2LTE_EUR_OPEN) :=  \
    exynos8895/exynos8895-dream2lte_eur_open_10.dtb
dtb-$(CONFIG_MACH_EXYNOS8895_GREATLTE_EUR_OPEN) :=  \
    exynos8895/exynos8895-greatlte_eur_open_06.dtb

# dtb-$(CONFIG_MACH_EXYNOS8895_DREAMLTE_KOR) :=
# dtb-$(CONFIG_MACH_EXYNOS8895_DREAM2LTE_KOR) := 
# dtb-$(CONFIG_MACH_EXYNOS8895_GREATLTE_KOR) := 
else
dtb-y += exynos/exynos9810-crownlte_eur_open_23.dtb
dtb-y += exynos/exynos9810-crownlte_eur_open_17.dtb
dtb-y += exynos/exynos9810-crownlte_eur_open_24.dtb
dtb-y += exynos/exynos9810-crownlte_eur_open_25.dtb
dtb-y += exynos/exynos9810-crownlte_eur_open_26.dtb
dtb-y += exynos/exynos9810-crownlte_eur_open_19.dtb
dtb-y += exynos/exynos9810-crownlte_eur_open_21.dtb
dtb-y += exynos/exynos9810-crownlte_eur_open_18.dtb
endif

targets += dtbs
DTB_LIST  := $(dtb-y) $(dtbo-y)
always    := $(DTB_LIST)

dtbs: $(addprefix $(obj)/, $(DTB_LIST))

clean-files := *.dtb*
