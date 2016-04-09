# apidoc
#所有到达服务端请求按照如下格式响应:
1、正常业务逻辑 
{ 
  "code":200,
  "msg":"",
  "biz":"success",
  "data":{
  }
}
2、业务逻辑错误
{
  "code":500,
  "msg":"请求ID查找错误",
  "biz":"NO ID IN DATABASE",
  "data":null
}

