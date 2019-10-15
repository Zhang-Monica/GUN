## 1. 接口描述  
服务接口：(sCreSupAccount)商户账户开户  
接口描述：xxxxx  
请求说明：POST https://epeis.com/Service/1.0.0/sCreSupAccount  
  
## 2. 输入公共参数  
公共请求参数说明，参数对象名：SYS_HEAD，参数对象类型：object  
  
| 参数              | 必选 | 类型     | 描述             |  
| :----------------- | :----: | :-------- | :---------------- |  
| CHANNEL_DID       |  是  | String   | 16字符渠道号 |  
| DYNAMIC_KEY       |  是  | String   | 动态请求密钥 |  
| REGISTER_DID      |  是  | String   | 16位注册ID，必须实名 |  
  
## 3. 服务接口输入参数  
本服务接口请求参数说明，参数对象名：SUP_ACCOUNT，参数对象类型：Array，请求参数描述：xxxxx  
  

| 参数              | 必选 | 类型     | 描述             |  
| :----------------- | :----: | :-------- | :---------------- |  
| ACC_CERT_INFO |  是  | String   | xxxxx |  
| ACC_CERT_TYPE |  是  | String   | xxxxx |  
| ACCOUNT_PASSWORD |  是  | String   | xxxxx |  
| SUPPLIER_NAME |  是  | String   | xxxxx |  
| ADMIN_CODE_INFO |  是  | String   | xxxxx |  
| ADDRESS |  是  | String   | xxxxx |  
| SUPPLIER_TYPE |  是  | String   | xxxxx |  
| TAX_NUMBER_INFO |  是  | String   | xxxxx |  
| TELEPHONE_INFO |  是  | String   | xxxxx |  
| BANK_ACCOUNT_INFO |  是  | String   | xxxxx |  
| BANK_NAME |  是  | String   | xxxxx |  
| EMAIL_INFO |  是  | String   | xxxxx |  
| VERIFY_CODE |  是  | String   | xxxxx |  
  
## 4. 服务接口响应参数  
本服务接口响应参数说明，参数对象名：SUP_ACCOUNT，参数对象类型：Array，响应参数描述：xxxxx  
  

| 参数              | 必选 | 类型     | 描述             |  
| :----------------- | :----: | :-------- | :---------------- |  
| SUPPLIER_DID |  是  | String   | xxxxx |  
| ATTESTATION_TYPE |  是  | String   | xxxxx |  
| SUPPLIER_NAME |  是  | String   | xxxxx |  
  
