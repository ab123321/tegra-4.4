ifeq ($(CONFIG_ARCH_TEGRA),y)
obj-y					+= fuse-tegra.o
obj-y					+= fuse-tegra30.o
obj-y					+= tegra-apbmisc.o
obj-y					+= tegra-platform.o
tegra_fuse-objs				:= tegra-chipid.o
obj-y					+= tegra_fuse.o
endif
obj-y					+= fuse-burn.o
obj-$(CONFIG_ARCH_TEGRA_2x_SOC)		+= fuse-tegra20.o
obj-$(CONFIG_ARCH_TEGRA_2x_SOC)		+= speedo-tegra20.o
obj-$(CONFIG_ARCH_TEGRA_3x_SOC)		+= speedo-tegra30.o
obj-$(CONFIG_ARCH_TEGRA_114_SOC)	+= speedo-tegra114.o
obj-$(CONFIG_ARCH_TEGRA_124_SOC)	+= speedo-tegra124.o
obj-$(CONFIG_ARCH_TEGRA_132_SOC)	+= speedo-tegra124.o
obj-$(CONFIG_ARCH_TEGRA_210_SOC)	+= speedo-tegra210.o
