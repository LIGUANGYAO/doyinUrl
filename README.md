    
**简要描述：** 

- 解析抖音视频原始无水印链接

**请求URL：** 
- ` https://www.98api.cn/api/dyjx.php `
  
**请求方式：**
- GET 

**参数：** 

|参数名|必选|类型|说明|
|:----    |:---|:----- |-----   |
|url |是  |string |短视频链接   |

**请求示例：** 
- ` https://www.98api.cn/api/dyjx.php?url=http://v.douyin.com/A2a5aT/ `
  
  
 **返回示例**

``` 
  {
	"status": 1,
	"url": "http:\/\/v1-dy.ixigua.com\/5a8e1681065bb396f508e12d5eba6345\/5d3ff952\/video\/m\/22068739047972143a18cc4e0ce42bff46f1162d53d400001a3dc284b8c5\/?rc=ampmZTlmOjhzbjMzZmkzM0ApQHRAb0ZFPDs0NDU0NDU0ODM6PDNAKXUpQGczdSlAZjN2KUBmbGRqZXpoaGRmOzRAb2ZzNWkxaG1mXy0tLi0wc3MtbyNvIy0yNjE2LTItLS0tLjAtLi9pOmIucCM6YS1xIzpgLW8jbWwrYitqdDojLy5e"
}
```

 **返回参数说明** 

|参数名|必选|类型|说明|
|:----    |:---|:----- |-----   |
|url |是  |string |原始链接   |
|status |是  |number |1解析正常；0解析失败   |

 **备注** 

- 同步最新接口请看98api官网
- [www.98api.cn](https://www.98api.cn)

