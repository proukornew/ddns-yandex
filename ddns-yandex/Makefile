include $(TOPDIR)/rules.mk

PKG_NAME:=ddns-yandex
PKG_VERSION:=0.1.0
PKG_RELEASE:=1

PKG_BUILD_DIR := $(BUILD_DIR)/$(PKG_NAME)

include $(INCLUDE_DIR)/package.mk

define Package/ddns-yandex
	SECTION:=net
	CATEGORY:=Network
        SUBMENU:=IP Addresses and Names
	TITLE:=Dynamic DNS Scripts
	PKGARCH:=all
endef

define Package/ddns-yandex/description
	A highly configurable set of scripts for doing
	dynamic dns updates
endef

define Build/Prepare
endef

define Build/Configure
endef

define Build/Compile
endef

define Package/ddns-yandex/conffiles
/etc/config/ddns
endef

define Package/ddns-yandex/install
	$(INSTALL_DIR) $(1)
	$(CP) ./files/* $(1)/
endef

$(eval $(call BuildPackage,ddns-yandex))
