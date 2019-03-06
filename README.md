# blog_photos


* 如果出现 from PIL import Image 这里报错.说明没有 PIL 这个库. 执行 `python3 -m pip install Pillow`.

### 使用
1.在此库中加入图片,图片路径在 photos 里面 图片命名方式 yyyy-MM-dd_des.jpg/jpeg/gif/png.
2.执行 python3 tool.py 生成data.json（执行完命令，tool.py已将远端代码更新）
3.切换到博客 source/photos 目录下 替换 data.json 文件，并提交更新到 github 上面.
4.输入网址查看照片.
