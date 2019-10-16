## 1. 接口描述  
服务接口：(oGetDynamicCode)获取动态验证码  
接口描述：xxxxx  
请求说明：POST https://epeis.com/Service/1.0.0/oGetDynamicCode  
  
## 2. 输入公共参数  
公共请求参数说明，参数对象名：SYS_HEAD，参数对象类型：object  
  
| 参数              | 必选 | 类型     | 描述             |  
| :----------------- | :----: | :-------- | :---------------- |  
| CHANNEL_DID       |  是  | String   | 16字符渠道号 |  
| DYNAMIC_KEY       |  是  | String   | 动态请求密钥 |  
  
## 3. 服务接口输入参数  
本服务接口请求参数说明，参数对象名：INOUT_VERIFYCODE，参数对象类型：Array，请求参数描述：xxxxx  
  

| 参数              | 必选 | 类型     | 描述             |  
| :----------------- | :----: | :-------- | :---------------- |  
| OBJECT_INFO |  否  | String   | xxxxx |  
| OBJECT_TYPE |  否  | String   | xxxxx |  
| REGISTER_INFO |  否  | String   | xxxxx |  
| REGISTER_TYPE |  是  | String   | xxxxx |  
| INPUT_YESNO |  是  | String   | xxxxx |  
  
### 服务接口报文示例：  
~~~  
{
	"SYS_HEAD":	{
		"CHANNEL_DID":	"",
		"DYNAMIC_KEY":	""
	},
	"INOUT_VERIFYCODE":	[{
			"OBJECT_INFO":	"",
			"OBJECT_TYPE":	"",
			"REGISTER_INFO":	"",
			"REGISTER_TYPE":	"",
			"INPUT_YESNO":	""
		}]
}  
~~~  
## 4. 服务接口响应参数  
本服务接口响应参数说明：无响应参数  
## 5. 服务接口说明  
xxxxxxx  
