include $(TOPDIR)/rules.mk
	
LUCI_TITLE:=Web UI for atinout
LUCI_DEPENDS:=+atinout +luci-compat
PKG_VERSION:=1.3.1-08082021
PKG_LICENSE:=GPLv3

define Package/luci-app-atinout-mod/postinst
#!/bin/sh
rm -rf /tmp/luci-indexcache
rm -rf /tmp/luci-modulecache/
/sbin/set_at_port.sh
exit 0
endef
	
include $(TOPDIR)/feeds/luci/luci.mk
	
# call BuildPackage - OpenWrt buildroot signature
