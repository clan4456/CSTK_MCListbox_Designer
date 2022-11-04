# CLAN Studio Toolkits - MCListbox Designer

仓库地址：[CSTK_MCListbox_Designer](https://github.com/clan4456/CSTK_MCListbox_Designer)

下载地址：[clan_studio_lib_cstk_mclistbox_designer-1.0.0.1.vip](https://github.com/clan4456/CSTK_MCListbox_Designer/releases/download/v1.0.0.1/clan_studio_lib_cstk_mclistbox_designer-1.0.0.1.vip)

SHA-256：c26127e5c49b315be15eef26d568a90ccde33c6c51e5d995a247a5c3e71c3f58

## 1. 简介

![2022-11-03-16-44-45.gif](http://pic2.clan4456.com/clan-picgo-core/images/2022/11/03/2022-11-03-16-44-45-83c7ec26123d3efa442a05bb832a6665.gif)

本工具主要用于在开发过程中提供统一的设置界面，对MultiColumnListbox控件进行便捷快速精准的界面调整，可快速调整表头字体样式、列宽、行首字体样式、列顺序等各种设置。避免频繁右击多列列表框属性、选择字体设置字体属性等操作。

## 2. 前置库

无

## 3. 安装MCListbox Designer

下载Release中的`clan_studio_lib_cstk_mclistbox_designer-1.0.0.1.vip`，并双击通过VIPM进行安装。（需安装VIPM 2014或以上版本）

## 4. 使用MCListbox Designer

### 4.1 工具菜单打开

安装 ***MCListbox Designer*** 后，可通过LabVIEW的“工具”-->“CLAN Studio Toolkits”-->“CSTK_MCListbox Designer”打开。

### 4.2 QuickDrop快捷键打开

安装 ***MCListbox Designer*** 后，可通过快捷键调出QuickDrop面板，并使用默认快捷键Ctrl+M快速打开。默认快捷键也可根据需要修改成其他快捷键。

### 4.3 选择打开

通过以上两种方式打开本工具，均需先选择待调整属性的MCListbox控件，再打开 MCListbox Designer 面板。没有选择或选择了非MCListbox控件，以上打开操作均不响应。

### 4.4 功能简介

![](http://pic2.clan4456.com/clan-picgo-core/images/2022/11/04/Snipaste_2022-11-04_10-53-26-decac51333e9341adf3d73fee10d271a.png!small)

MCListbox Designer 面板从上到下主要分4个部分：

#### 4.4.1 控件信息栏

![Snipaste_2022-11-04_11-15-33.png](http://pic2.clan4456.com/clan-picgo-core/images/2022/11/04/Snipaste_2022-11-04_11-15-33-63d2886ce265aed781d062960c35a57b.png!small)

该信息栏主要用于显示当前捕捉到的控件信息

#### 4.4.2 表头统一设置栏

![Snipaste_2022-11-04_11-23-51.png](http://pic2.clan4456.com/clan-picgo-core/images/2022/11/04/Snipaste_2022-11-04_11-23-51-10e2ba8b5bbe4d69ea0f13f00e717317.png!small)

该设置栏主要用于对所有表头进行统一设置操作，可统一设置列宽、字体粗体、字体斜体、字体对齐方向。统一设置时需保持列名框为空。

填入列名后，可用于新增插入列。

#### 4.4.3 表头设置栏

![Snipaste_2022-11-04_11-29-06.png](http://pic2.clan4456.com/clan-picgo-core/images/2022/11/04/Snipaste_2022-11-04_11-29-06-b4eeae4f1cc44b23919da47de7422c5d.png!small)

该设置栏主要用于分别对每一列进行表头设置、列顺序调整、新增/删除列等操作。左侧为列选择框，选择了列后，即可对该列进行删除、顺序调整等操作。右侧最下方为刷新按钮，当在非本界面上调整了MCListbox属性后，使用该按钮即可更新本工具界面的属性状态。

#### 4.4.4 其他属性设置栏

![Snipaste_2022-11-04_11-35-54.png](http://pic2.clan4456.com/clan-picgo-core/images/2022/11/04/Snipaste_2022-11-04_11-35-54-6a69a6e022283fbfc50831e073a2947d.png!small)

该设置栏主要用于设置MCListbox的其他属性，如总宽度总高度、行数列数、行首属性等。

## 5. 已知bug

暂未发现

## 6. 开源许可

本工具遵循BSD开源协议，可任意分发或二次开发使用。但需保留UI界面上的CLAN Studio标志即可。

## 7. 关于捐赠

作者开发不易，如对本工具使用效果满意，同时经济允许的情况下，可向作者相赠一杯咖啡，感谢！本工具为免费开源，仅接受微信公众号（请使用微信扫描下方二维码关注 `CLAN Studio` 公众号）文章打赏，其他途径均非作者本意，请注意分辨，谢谢！

![公众号二维码_500px.png](http://pic2.clan4456.com/clan-picgo-core/images/2022/11/04/%E5%85%AC%E4%BC%97%E5%8F%B7%E4%BA%8C%E7%BB%B4%E7%A0%81_500px-515fa711dc785a71dd8819fa999ebd07.png)
