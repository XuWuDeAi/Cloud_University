#      foodAPI接口文档  

### 1. 用户登录
**接口地址**：/api/login
**参数校验**： 用户名，密码均不能为空  
**接口描述**： 用户登录  
**Auth-date**：[add by XXX 2018-3-17]  
#####   请求格式：  
```json  

    
    {  
        "id":"", //账号
        "password":""//用户密码  
      
    }//json请求对象  
 
```  


### 1. seller表查询
**接口地址**： /api//sellerDb
**参数校验**： 无
**接口描述**： 返回seller表json字符串 
**Auth-date**：[add by XXX 2018-3-17]  
#####   请求格式：  
```json  

    
    {  
        无  
      
    }//json请求对象  
 
```  

### 1. order_itemDb表查询
**接口地址**： /api//order_itemDb
**参数校验**： 无
**接口描述**： 返回order_itemDbr表json字符串  
**Auth-date**：[add by XXX 2018-3-17]  
#####   请求格式：  
```json  

    
    {  
        无  
      
    }//json请求对象  
 
```  

### 1. orderDb表查询
**接口地址**： /api//orderDb
**参数校验**： 无
**接口描述**： 返回orderDb表json字符串  
**Auth-date**：[add by XXX 2018-3-17]  
#####   请求格式：  
```json  

    
    {  
        无  
      
    }//json请求对象  
 
```  

### 1. seller表更新
**接口地址**： /api//update_sellerDb
**参数校验**： 所有参数不能为空！
**接口描述**： 更新seller表 
**Auth-date**：[add by XXX 2018-3-17]  
#####   请求格式：  
```json  

    
    {  
        
        "sid":, 
        "name":"", 
        "logo":"", 
        "info":"", 
        "rating":"", 
        "name":"" 
    }//json请求对象  
 
```  

### 1. seller表添加
**接口地址**： /api//add_sellerDb
**参数校验**： 除字段名rating其他字段不能为空，id默认自增！
**接口描述**： 添加seller表 
**Auth-date**：[add by XXX 2018-3-17]  
#####   请求格式：  
```json  

    
    {  
    
        
        "name":, 
        "logo":"", 
        "info":"", 
        "info":"", 
        "rating":"", 
        
    }//json请求对象  
 
```  

### 1.orderr表更新字段status
**接口地址**： /api//updateStatus_orderrDb
**参数校验**：oid(主键)不能为空！
**接口描述**： order表更新字段status 
**Auth-date**：[add by XXX 2018-3-17]  
#####   请求格式：  
```json  

    
    {  
    
        
        "oid":, 
       
        "updateValue":""
        
    }//json请求对象  
 
```  

