#
# Copyright 2023-2025 sirpdboy team <herboy2008@gmail.com>
# This is free software, licensed under the Apache License, Version 2.0 .
#

include $(TOPDIR)/rules.mk
NAME:=advancedplus
PKG_NAME:=luci-app-$(NAME)
LUCI_TITLE:=LuCI support for Kucat theme setting by sirpdboy
LUCI_DEPENDS:=+luci-compat +curl +wget
LUCI_PKGARCH:=all

PKG_VERSION:=1.8.2
PKG_RELEASE:=20250213

define Package/$(PKG_NAME)/conffiles
/etc/config/advancedplus
endef

include $(TOPDIR)/feeds/luci/luci.mk

# call BuildPackage - OpenWrt buildroot signature


