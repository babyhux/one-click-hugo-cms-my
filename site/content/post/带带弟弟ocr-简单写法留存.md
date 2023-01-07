---
title: 带带弟弟ocr 简单写法留存
date: 2023-01-07T03:19:38.354Z
description: "带带弟弟ocr "
---
github 地址 ：https://github.com/sml2h3/ddddocr

<!--StartFragment-->

# 当前版本为1.4.7

<!--EndFragment-->

然后 pip install ddddocr

好像很多功能啊

简单的 

<!--StartFragment-->

```
import ddddocr

ocr = ddddocr.DdddOcr(det=False, ocr=False, import_onnx_path="myproject_0.984375_139_13000_2022-02-26-15-34-13.onnx", charsets_path="charsets.json")

with open('888e28774f815b01e871d474e5c84ff2.jpg', 'rb') as f:
    image_bytes = f.read()

res = ocr.classification(image_bytes)
print(res)
```

<!--EndFragment-->