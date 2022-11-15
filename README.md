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

由于自己编译，我[删除](https://github.com/DHDAXCW/theme/commit/0269f614a00c6b795f1dacb8a01e3262858cd597)了各个默认主题~

想默认主题，请在选好主题保存之后执行代码来编译系统默认主题：

```bash
sed -i 's/luci-theme-bootstrap/主题名/' feeds/luci/collections/luci/Makefile
```

把你需要修改的主题名加到下面链接，比如默认主题infinityfreedom

```bash
sed -i 's/luci-theme-bootstrap/infinityfreedom/' feeds/luci/collections/luci/Makefile
```

主题展示:

![image](https://user-images.githubusercontent.com/74764072/196173667-260349b0-3d98-4709-ac6a-6faf44291f52.png)
![image](https://user-images.githubusercontent.com/74764072/196173784-b012dc58-6d9b-438d-9046-71e1f0bc7c0a.png)
![image](https://user-images.githubusercontent.com/74764072/196173849-222cb846-bce1-408e-a37b-3f04636ad735.png)
![image](https://user-images.githubusercontent.com/74764072/196173950-eac36bbf-6e59-4eab-8863-a6c5b78770a4.png)
![image](https://user-images.githubusercontent.com/74764072/196174090-a5a5bc49-9c00-46e3-8cd4-ce918a045f2b.png)
![image](https://user-images.githubusercontent.com/74764072/196174153-88f11140-679e-4e34-8e44-3ac7001ecaeb.png)
![image](https://user-images.githubusercontent.com/74764072/196174226-be0947a2-a295-46dd-8327-1122a63ea4d2.png)
![image](https://user-images.githubusercontent.com/74764072/196174294-2b0a78b6-6ff2-4d0d-8290-5dd92efd1b72.png)
![image](https://user-images.githubusercontent.com/74764072/196174375-79596913-0744-4f9b-adb2-2ee2cfa17af1.png)
![image](https://user-images.githubusercontent.com/74764072/196174456-35de83ee-9b88-4e77-80b6-6b799521ef43.png)
![image](https://user-images.githubusercontent.com/74764072/196174573-3501c03e-cd61-47bd-ab16-7f6676403f1e.png)
![image](https://user-images.githubusercontent.com/74764072/196174668-ad6e6be3-279d-4d92-bec6-f88c2771803b.png)
![image](https://user-images.githubusercontent.com/74764072/196174779-8903d0b5-cd85-4329-abe7-1c9b2329fe8a.png)
