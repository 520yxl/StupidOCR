# StupidOCR 
_________________
```
应用于爬虫，注册，登录等场景的验证码识别
快速 便捷 通用的方法提供用户调用，堪称作者开发神器
```
## Docker
_________________
```
docker run -d --name stupidocr --restart=always -p 6688:6688 yangxiao6/stupidocr:main 
```
_________________
## 项目说明：

>Python开发， 用于验证码识别，<strong>秉承着会HttpPost协议即可调用的原则！</strong>
> 
>支持部署 <strong>本地</strong> 和 <strong>服务器</strong> .
> 
> 内嵌开发者文档：http://127.0.0.1:6688/docs
> 
>成品长期维护，提供源代码，免费使用等特点

## 更新内容：
* 修复开发者文档部分BUG


* 请求异步执行，实现并发


* 通用型验证码识别


* 算数验证码识别


* 独立滑块验证码识别【返回坐标】


* 缺口滑块验证码识别【返回坐标】


* 文字点选验证码识别【返回坐标】

 
## 常见问题和解决方法:
> 
>>1:服务器部怎么部署？
> 
>打开6688端口，修改127.0.0.1为服务器ip地址即可
>
>>2.软件运行缺少DLL？
> 
> 补齐所缺DLL(项目用Python3.9环境 + Pyinstaller编译，部分win7服务器不能运行，提供源码自行编译)
>
>>3.服务器运行秒退？
> 
> 参考文章：https://blog.csdn.net/Vickie_Liang/article/details/106538355
_________________




## 关于作者
**[81NewArk【我叫牛二】](https://github.com/81NewArk/StupidOCR)**

|     | 地址  |
|  ----  | ----  |
| B站  | https://space.bilibili.com/37887820 |
| 乐乎  | http://niuer-pepsi.lofter.com |
