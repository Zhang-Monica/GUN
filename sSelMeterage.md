## 1. 接口描述  
服务接口：(sSelMeterage)查询计量点信息  
接口描述：xxxxx  
请求说明：POST https://epeis.com/Service/1.0.0/sSelMeterage  
  
## 2. 输入公共参数  
公共请求参数说明，参数对象名：SYS_HEAD，参数对象类型：object  
  
| 参数              | 必选 | 类型     | 描述             |  
| :----------------- | :----: | :-------- | :---------------- |  
| CHANNEL_DID       |  是  | String   | 16字符渠道号 |  
| DYNAMIC_KEY       |  是  | String   | 动态请求密钥 |  
| REGISTER_DID      |  是  | String   | 16位注册ID，必须实名 |  
  
## 3. 服务接口输入参数  
本服务接口请求参数说明，参数对象名：SETTLE_METERAGE，参数对象类型：Array，请求参数描述：xxxxx  
  

| 参数              | 必选 | 类型     | 描述             |  
| :----------------- | :----: | :-------- | :---------------- |  
| SETTLEMENT_AID |  否  | String   | xxxxx |  
| ADDRESS |  否  | String   | xxxxx |  
  
## 4. 服务接口响应参数  
本服务接口响应参数说明，参数对象名：SETTLE_METERAGE，参数对象类型：Array，响应参数描述：xxxxx  
  

| 参数              | 必选 | 类型     | 描述             |  
| :----------------- | :----: | :-------- | :---------------- |  
| SETTLEMENT_AID |  是  | String   | xxxxx |  
| ADDRESS |  是  | String   | xxxxx |  
| BOOK_AID |  是  | String   | xxxxx |  
| NODE_AID |  是  | String   | xxxxx |  
| NETWORK_TYPE |  是  | String   | xxxxx |  
| METER_YESNO |  是  | String   | xxxxx |  
| DEVICE_DID |  是  | String   | xxxxx |  
| REAL_ESTATE_AID |  是  | String   | xxxxx |  
| NETWORK_CO_DID |  是  | String   | xxxxx |  
| NET_STORES_AID |  是  | String   | xxxxx |  
| RETAIL_CO_DID |  是  | String   | xxxxx |  
| RET_STORES_AID |  是  | String   | xxxxx |  
| ASSESS_YESNO |  是  | String   | xxxxx |  
| PURCHASE_SALE_TYPE |  是  | String   | xxxxx |  
| ENERGY_LOAD |  是  | Number   | xxxxx |  
| ACCOUNT_ITEM_INFO |  是  | String   | xxxxx |  
| AGREE_PRICE_YESNO |  是  | String   | xxxxx |  
| PROTOCOL_DID |  是  | String   | xxxxx |  
| STOP_EMPTY_YESNO |  是  | String   | xxxxx |  
| OUTAGE_VACANCY_DATE |  是  | Number   | xxxxx |  
| RESUPPLY_DATE |  是  | Number   | xxxxx |  
| SETTLEMENT_DATE_TYPE |  是  | String   | xxxxx |  
| MAIN_PACK_DID |  是  | String   | xxxxx |  
| TEMP_PACK_DID |  是  | String   | xxxxx |  
| TMP_MONTHS |  是  | Number   | xxxxx |  
| BASIC_FEES_TYPE |  是  | String   | xxxxx |  
| LOAD_CAPACITY |  是  | Number   | xxxxx |  
| METER_DEMAND_RATE |  是  | Number   | xxxxx |  
| MAX_DEMAND_APPR |  是  | Number   | xxxxx |  
| COMP_DEVIATION_YESNO |  是  | String   | xxxxx |  
| FOR_RATE_VALID_TYPE |  是  | String   | xxxxx |  
| ABUND_WITHER_YESNO |  是  | String   | xxxxx |  
| TIME_FEES_TYPE |  是  | String   | xxxxx |  
| LADDER_TYPE |  是  | String   | xxxxx |  
| LADDER_NAME_TYPE |  是  | String   | xxxxx |  
| FIXED_CHARGE |  是  | Number   | xxxxx |  
| FIXED_FEE |  是  | Number   | xxxxx |  
| DIVI_FIXED_CHARGE |  是  | Number   | xxxxx |  
| MET_DIVID_RATIO |  是  | Number   | xxxxx |  
| FLOOR_NUM |  是  | Number   | xxxxx |  
| FLOOR_HEIGHT |  是  | Number   | xxxxx |  
| CHARGE_AREA_FACTOR |  是  | Number   | xxxxx |  
| ACTUAL_AREA |  是  | Number   | xxxxx |  
| CHARGE_POPULATION |  是  | Number   | xxxxx |  
| CHARGE_HOUSEHOLDS |  是  | Number   | xxxxx |  
  
