# ErfanGSIs-build

## 一个自动跑 ErfanGSIs 的脚本。 
### 步骤如下： 
- 首先，fork 这个仓库。 
- 去.github/workflows/build.yml里在env中修改内容
- 去actions里，点击Select Workflow，选择ErfanGSI-build, 点击Run Workflow
- 最后，在 Release 里下载

## 其他注意事项 ##
因GitHub Release无法上传超过2GB的文件，所以此项目把超过2GB的文件进行拆分，如你的项目运行完后发现release里的文件被拆分成了多个（后缀名为zip00，zip01这种），请用Linux系统将其合并

```
cat 文件1 文件2 ...>文件.tar.gz         # 对文件进行合并(eg:cat MIUI.zip00 MIUI.zip01>MIUI.zip.tar.gz)
tar xzvf 文件.tar.gz                   # 解压缩文件
```
小于1mb的Rom一般为无法打包，可使用线下进行制作。

## 附：ErfanGSI支持的ROM ##
> ROM_NAME里填一摸一样的，下的ROM也要一样；Generic是（类）原生的意思，任何系统都可以使用Generic参数
### 安卓9： ### 
> ColorOS
	
> Flyme

> Generic

> MIUI	

> Moto	

> Nubia	

> OneUI	

> OxygenOS	

> Pixel	

> Xperia	

> ZUI	

> ZenUI
### 安卓10： ###
> Generic

> MIUI
	
> OxygenOS (氢OS HydrogenOS 的海外版，两者跑 gsi 都用 OxygenOS 代替)

> Pixel

> Flyme
### 安卓11： ##
> Generic
	
> Pixel
### 安卓12： ##
> Generic
	
> Pixel

## 联系 ##
> 酷安：[mi20210630](https://www.coolapk.com/u/mi20210630)

> 邮箱：shanghaizhouwanli@163.com

> Github: [ShanghaiZhouWanLi](https://github.com/mi20210630)

