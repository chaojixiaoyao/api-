抖音下拉接口
===

### 必要参数
- `username`
- `password`

##添加任务（批量或单个）

#### URL

- `https://www.waimaojingling.com/api/dyxl/addTask?username=&password=&data=`
  
##### 请求方式
- GET 

##### 请求示例
- `https://www.waimaojingling.com/api/dyxl/addTask?username=&password=&data=[{"root": "填写你的主词",
    "dropdown": "填写你的下拉词",
    "times": 填写优化次数},{"root": "主词",
    "dropdown": "下拉词",
    "times": 1}]`


##### 返回示例 

``` 
{"code":1, "msg": "成功"}
```


##查询所有优化任务

##### URL
- `http://www.waimaojingling.com/api/dyxl/gettasklist?username=&password=&page=1`
  
##### 请求方式
- GET


##### 参数说明 

|参数名|类型|说明|
|:-----  |:-----|-----                           |
|page |int   |页码  |


##查询指定的优化任务

##### URL
- `http://www.waimaojingling.com/api/dyxl/gettask?username=&password=&ids=`
  
##### 请求方式
- GET


##### 参数说明 

|参数名|类型|说明|
|:-----  |:-----|-----                           |
|ids |list   |查询参数的id  |


##设置优化次数

##### URL
- `http://www.waimaojingling.com/api/dyxl/edittimes?username=&password=&ids=&times=`
  
##### 请求方式
- GET


##### 参数说明 

|参数名|类型|说明|
|:-----  |:-----|-----                           |
|ids |list   |设置优化次数的id  |
|times |int   |优化次数  |

##停止任务

##### URL
- `http://www.waimaojingling.com/api/dyxl/stoptask?username=&password=&ids=`
  
##### 请求方式
- GET


##### 参数说明 

|参数名|类型|说明|
|:-----  |:-----|-----                           |
|ids |list   |任务的id  |

##开启任务

##### URL
- `http://www.waimaojingling.com/api/dyxl/starttask?username=&password=&ids=`
  
##### 请求方式
- GET


##### 参数说明 

|参数名|类型|说明|
|:-----  |:-----|-----                           |
|ids |list   |任务的id  |

##删除任务

##### URL
- `http://www.waimaojingling.com/api/dyxl/deltask?username=&password=&ids=`
  
##### 请求方式
- GET


##### 参数说明 

|参数名|类型|说明|
|:-----  |:-----|-----                           |
|ids |list   |任务的id  |
