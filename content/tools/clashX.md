---
title:  clashX 
date: 2022-07-21
description:  clashX 
---


- clashX 配置访问白名单

```shell
vim ~/.config/clash/proxyIgnoreList.plist
```

```xml
<?xml version="1.0" encoding="UTF-8"?>
<!DOCTYPE plist PUBLIC "-//Apple//DTD PLIST 1.0//EN" "http://www.apple.com/DTDs/PropertyList-1.0.dtd">
<plist version="1.0">
<array>
	<string>192.168.0.0/16</string>
	<string>10.0.0.0/8</string>
	<string>172.16.0.0/12</string>
	<string>127.0.0.1</string>
	<string>localhost</string>
	<string>*.local</string>
	<string>*.crashlytics.com</string>
	<string>*.infoq.cn</string>
    <string>*.geekbang.org</string>
</array>
</plist>
```