# getQRImage
生成二维码图片 代码取自https://github.com/sylnsfar/qrcode ，稍作修改，添加仅获取图片内容而不保存功能

```python
import myqr
import os
qr = myqr.run('Hello'*4, content_only = True)
```
