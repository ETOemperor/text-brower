# text-brower

## Version:0.1

> 一个能用终端看网站的程序

> 使用
* 使用<code>url {url}</code>查看网页
* 使用<code>exit</code>退出程序

> 获取网页：使用requests的get函数获取。可以自动添加"https://"

> 解析html(等待更新：
* 使用python html标准库处理
* 通过re获取html标签中的内容，(text版本会自动忽略css与大部分的js(正式版本1.0不一定支持))
* 文字标签比较好处理(字体会被忽略）
* img与video标签中的内容会下载到缓存目录中转换为文字后播放(正式版本1.0不一定支持)

