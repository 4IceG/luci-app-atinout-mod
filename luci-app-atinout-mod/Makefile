include $(TOPDIR)/rules.mk
	
LUCI_TITLE:=Web UI for atinout
LUCI_DEPENDS:=+atinout +luci-compat
PKG_VERSION:=1.3.2-20220315
PKG_LICENSE:=GPLv3

define Package/luci-app-atinout-mod/postinst
#!/bin/sh
chmod +x /sbin/set_at_port.sh
chmod +x /usr/bin/luci-app-atinout
rm -rf /tmp/luci-indexcache
rm -rf /tmp/luci-modulecache/
/sbin/set_at_port.sh
exit 0
endef
	
include $(TOPDIR)/feeds/luci/luci.mk
	
# call BuildPackage - OpenWrt buildroot signature
