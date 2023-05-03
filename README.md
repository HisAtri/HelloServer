# HelloServer

## 简介

基于Python的图片生成器，可以分析请求头获得IP、操作系统、浏览器信息并生成图片。

## 启动

修改config.ini

```ini
port=8000 # 端口
timezone=Asia/Shanghai # 时区
font=font/font.ttf # 字体路径
image=image/sample.jpg # 背景图路径（JPEG），要使用PNG等其他格式在源码中修改
```

如果没有config.ini，启动时会自动生成以上配置，修改后重启即可。

启动主程序

访问配置项中设置的端口（port），默认8000

## 自定义

### 替换字体

修改config.ini中的font

### 替换背景图

修改config.ini中的image（必须是jpeg格式）

### 替换文本内容

自己修改源代码编译（

修改字体时注意和图片尺寸匹配
