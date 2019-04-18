---
layout: page
title: F&Q
permalink: /faq/
---

There is the place I record some notes

**(1) To get a site's IP**

**Answer:**  terminal windows:

```shell
nslookup xxx
```
mac

```shell
dig xxx
```

**(2) sublime license**

**Answer**  input license :

```shell
----- BEGIN LICENSE -----

Andrew Weber

Single User License

EA7E-855605

813A03DD 5E4AD9E6 6C0EEB94 BC99798F

942194A6 02396E98 E62C9979 4BB979FE

91424C9D A45400BF F6747D88 2FB88078

90F5CC94 1CDC92DC 8457107A F151657B

1D22E383 A997F016 42397640 33F41CFC

E1D0AE85 A0BBD039 0E9C8D55 E1B89D5D

5CDB7036 E56DE1C0 EFCC0840 650CD3A6

B98FC99C 8FAC73EE D2B95564 DF450523

------ END LICENSE ------
```

**(3) To set up other members of the LAN to be accessible in wordpress**

**Answer** Open mysql admin, Then open wordpress's database, change the options of siteurl

**（4）Pip3 Use Better Network in China**

**Answer:** 

All: Open %users/USERNAME/%, create the **pip** folder, and then create **pip.ini** flie in pip folder, and add the below codes

```
[global]
timeout = 6000
index-url = https://pypi.tuna.tsinghua.edu.cn/simple
trusted-host = pypi.tuna.tsinghua.edu.cn
```

One: 

```
pip install ... --index-url="https://pypi.tuna.tsinghua.edu.cn/simple"
```

**(5) Npm Use Taobao sources to speed up download speed** 

```
# use always:
npm config set registry https://registry.npm.taobao.org
```

or use temp：

```
# use Temp
npm --registry https://registry.npm.taobao.org install SOMETHING
```

use 

```
npm config get registry
```

to TEST registry

use 

```
npm info node-gyp
```

to GET package infos

**(6)Windows 10 LTSB**

> It is a good version in win 10, only update safe modules, not install kernel often (Just one year or two year / update)

It can download at itellyou and activate by autokms

**(7)Intall Node-gyp**

```
npm install -g node-gyp
```

then 

```
npm install --global --production windows-build-tools
```

