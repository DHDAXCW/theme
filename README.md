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

![1665630469215](https://user-images.githubusercontent.com/74764072/195490667-5b1972c5-acf4-4fdb-9899-9fde4edea414.png)
![16656303839781](https://user-images.githubusercontent.com/74764072/195490670-a8c35f2c-fc58-4635-a649-b25cb6ae1215.png)
![16656303977909](https://user-images.githubusercontent.com/74764072/195490671-23d11043-92e1-476b-82cc-4e78fc3f7c28.png)
![16656304136774](https://user-images.githubusercontent.com/74764072/195490677-9751d300-dc57-4c74-a8f1-7b7851248639.png)
![16656304282313](https://user-images.githubusercontent.com/74764072/195490682-3e88f131-9eec-49b6-883c-3e49d937ad5a.png)
![16656304542812](https://user-images.githubusercontent.com/74764072/195490683-b0bf4b18-68e7-46fc-8c55-dd44af9e2dbc.png)
![16656304842563](https://user-images.githubusercontent.com/74764072/195490686-8079d4e6-c09e-479b-bd93-cc9e8b62101b.png)
![16656305009364](https://user-images.githubusercontent.com/74764072/195490688-9ce9eeb3-4ca0-4dba-b32f-2da4bb8694bc.png)
![16656305206071](https://user-images.githubusercontent.com/74764072/195490690-12133fd8-26b0-4f86-baa6-93ebab72bdd9.png)
![16656305376140](https://user-images.githubusercontent.com/74764072/195490693-11541641-490a-4ffb-9a72-2f1aa528387a.png)
![16656305528706](https://user-images.githubusercontent.com/74764072/195490695-d1ca7ce4-f7fe-4cac-bf2a-7ff0e73bcb74.png)
![16656305683537](https://user-images.githubusercontent.com/74764072/195490697-b5042f74-835d-4839-b7f1-c30a9ddcde0f.png)
![16656305818631](https://user-images.githubusercontent.com/74764072/195490698-b9e8d132-0d06-4ec7-81e8-e3711a0a179c.png)

