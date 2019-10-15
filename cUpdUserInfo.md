## 1. 接口描述  
服务接口：(cUpdUserInfo)修改用户信息  
接口描述：xxxxx  
请求说明：POST https://epeis.com/Service/1.0.0/cUpdUserInfo  
  
## 2. 输入参数  
公共请求参数说明，参数对象名：SYS_HEAD，参数对象类型：object  
| 参数              | 必选 | 类型     | 描述             |  
| :----------------- | :----: | :-------- | :---------------- |  
| CHANNEL_DID       |  是  | String   | 16字符渠道号 |  
| DYNAMIC_KEY       |  是  | String   | 动态请求密钥 |  
| REGISTER_DID      |  是  | String   | 16位注册ID，必须实名 |  
| ACCOUNT_DID       |  是  | String   | 16位账户ID，必须激活 |  
本服务接口请求参数说明，参数对象名：USER_ACCOUNT，参数对象类型：Array，请求参数描述：xxxxx  
| 参数              | 必选 | 类型     | 描述             |  
| :----------------- | :----: | :-------- | :---------------- |  
| USER_ACCOUNT_AID |  是  | String   | xxxxx |  
| USER_PLACE_NAME |  是  | String   | xxxxx |  
| ADMIN_CODE_INFO |  是  | String   | xxxxx |  
| ADDRESS |  是  | String   | xxxxx |  
| MAP_NAME |  否  | String   | xxxxx |  
| X |  否  | Number   | xxxxx |  
| Y |  否  | Number   | xxxxx |  
本服务接口响应参数说明：无响应参数  
