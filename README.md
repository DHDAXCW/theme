# theme
### 自用主题，从其他拉来的，[删除主题强制默认。](https://github.com/DHDAXCW/theme/commit/0269f614a00c6b795f1dacb8a01e3262858cd597)

下载主题到源码里 ```git clone https://github.com/DHDAXCW/theme package/theme```

选择主题：

```bash
LuCI ---> Themes ---> luci-theme-atmaterial_new
LuCI ---> Themes ---> luci-theme-edge
LuCI ---> Themes ---> luci-theme-ifit
LuCI ---> Themes ---> luci-theme-infinityfreedom
LuCI ---> Themes ---> luci-theme-material
LuCI ---> Themes ---> luci-theme-mcat
LuCI ---> Themes ---> luci-theme-neobird
LuCI ---> Themes ---> luci-theme-netgear
LuCI ---> Themes ---> luci-theme-rosy
LuCI ---> Themes ---> luci-theme-tomato
```

云编译主题配置:

```bash
CONFIG_PACKAGE_luci-theme-atmaterial_new=y
CONFIG_PACKAGE_luci-theme-edge=y
CONFIG_PACKAGE_luci-theme-ifit=y
CONFIG_PACKAGE_luci-theme-infinityfreedom=y
CONFIG_PACKAGE_luci-theme-material=y
CONFIG_PACKAGE_luci-theme-mcat=y
CONFIG_PACKAGE_luci-theme-neobird=y
CONFIG_PACKAGE_luci-theme-netgear=y
CONFIG_PACKAGE_luci-theme-rosy=y
CONFIG_PACKAGE_luci-theme-tomato=y
```

默认主题：

请在选好主题保存之后执行代码来编译系统默认主题：

```bash
sed -i 's/luci-theme-bootstrap/主题名/' feeds/luci/collections/luci/Makefile
```

把你需要修改的主题名加到下面链接，比如默认主题infinityfreedom

```bash
sed -i 's/luci-theme-bootstrap/infinityfreedom/' feeds/luci/collections/luci/Makefile
```
