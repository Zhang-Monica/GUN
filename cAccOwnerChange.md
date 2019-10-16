## 1. 接口描述  
服务接口：(cAccOwnerChange)接受所有权人变更  
接口描述：xxxxx  
请求说明：POST https://epeis.com/Service/1.0.0/cAccOwnerChange  
  
## 2. 输入公共参数  
公共请求参数说明，参数对象名：SYS_HEAD，参数对象类型：object  
  
| 参数              | 必选 | 类型     | 描述             |  
| :----------------- | :----: | :-------- | :---------------- |  
| CHANNEL_DID       |  是  | String   | 16字符渠道号 |  
| DYNAMIC_KEY       |  是  | String   | 动态请求密钥 |  
| REGISTER_DID      |  是  | String   | 16位注册ID，必须实名 |  
| ACCOUNT_DID       |  是  | String   | 16位账户ID，必须激活 |  
  
## 3. 服务接口输入参数  
本服务接口请求参数说明，参数对象名：USER_ACCOUNT，参数对象类型：Array，请求参数描述：xxxxx  
  

| 参数              | 必选 | 类型     | 描述             |  
| :----------------- | :----: | :-------- | :---------------- |  
| USER_ACCOUNT_AID |  是  | String   | xxxxx |  
| ATTESTATION_TYPE |  是  | String   | xxxxx |  
  
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
		}],
	"SYS_HEAD":	{
		"CHANNEL_DID":	"",
		"DYNAMIC_KEY":	""
	},
	"SYS_REGISTER":	[{
			"REGISTER_INFO":	"",
			"REGISTER_TYPE":	"",
			"REGISTER_PASSWORD":	""
		}],
	"SYS_HEAD":	{
		"CHANNEL_DID":	"",
		"DYNAMIC_KEY":	""
	},
	"SYS_REGISTER":	[{
			"REGISTER_INFO":	"",
			"REGISTER_TYPE":	"",
			"VERIFY_CODE":	"",
			"REGISTER_PASSWORD":	""
		}],
	"SYS_HEAD":	{
		"CHANNEL_DID":	"",
		"DYNAMIC_KEY":	"",
		"REGISTER_DID":	""
	},
	"SYS_REGISTER":	[{
			"REGISTER_INFO":	"",
			"REGISTER_TYPE":	"",
			"VERIFY_CODE":	""
		}],
	"SYS_HEAD":	{
		"CHANNEL_DID":	"",
		"DYNAMIC_KEY":	"",
		"REGISTER_DID":	""
	},
	"SYS_REGISTER":	[{
			"CERTIFICATES_INFO":	"",
			"CERTIFICATES_TYPE":	"",
			"OPERATION_NAME":	"",
			"EMAIL_INFO":	"",
			"VERIFY_CODE":	""
		}],
	"SYS_HEAD":	{
		"CHANNEL_DID":	"",
		"DYNAMIC_KEY":	""
	},
	"SYS_REGISTER":	[{
			"REGISTER_INFO":	"",
			"REGISTER_TYPE":	"",
			"VERIFY_CODE":	"",
			"REGISTER_PASSWORD":	""
		}],
	"SYS_HEAD":	{
		"CHANNEL_DID":	"",
		"DYNAMIC_KEY":	"",
		"REGISTER_DID":	""
	},
	"SYS_REGISTER":	[{
			"CERTIFICATES_INFO":	"",
			"CERTIFICATES_TYPE":	"",
			"OPERATION_NAME":	"",
			"MOBILE_PHONE_INFO":	"",
			"EMAIL_INFO":	"",
			"VERIFY_CODE":	""
		}],
	"SYS_HEAD":	{
		"CHANNEL_DID":	"",
		"DYNAMIC_KEY":	"",
		"REGISTER_DID":	""
	},
	"SYS_HEAD":	{
		"CHANNEL_DID":	"",
		"DYNAMIC_KEY":	"",
		"REGISTER_DID":	""
	},
	"SYS_REGISTER":	[{
			"REGISTER_INFO":	"",
			"REGISTER_TYPE":	""
		}],
	"SYS_HEAD":	{
		"CHANNEL_DID":	"",
		"DYNAMIC_KEY":	"",
		"REGISTER_DID":	""
	},
	"SYS_HEAD":	{
		"CHANNEL_DID":	"",
		"DYNAMIC_KEY":	"",
		"REGISTER_DID":	""
	},
	"SYS_HEAD":	{
		"CHANNEL_DID":	"",
		"DYNAMIC_KEY":	"",
		"REGISTER_DID":	""
	},
	"SYS_REG_CONNECT":	[{
			"REGISTER_DID":	"",
			"ACCOUNT_DID":	"",
			"ACCOUNT_TYPE":	""
		}],
	"SYS_HEAD":	{
		"CHANNEL_DID":	"",
		"DYNAMIC_KEY":	"",
		"REGISTER_DID":	""
	},
	"SYS_REG_CONNECT":	[{
			"REGISTER_DID":	"",
			"ACCOUNT_DID":	"",
			"ACCOUNT_TYPE":	"",
			"ATTESTATION_TYPE":	""
		}],
	"SYS_HEAD":	{
		"CHANNEL_DID":	"",
		"DYNAMIC_KEY":	"",
		"REGISTER_DID":	""
	},
	"SYS_REGISTER":	[{
			"REGISTER_INFO":	""
		}],
	"SYS_HEAD":	{
		"CHANNEL_DID":	"",
		"DYNAMIC_KEY":	"",
		"REGISTER_DID":	""
	},
	"SYS_REG_CONNECT":	[{
			"REGISTER_DID":	"",
			"ACCOUNT_DID":	"",
			"ACCOUNT_TYPE":	""
		}],
	"SYS_HEAD":	{
		"CHANNEL_DID":	"",
		"DYNAMIC_KEY":	"",
		"REGISTER_DID":	""
	},
	"INOUT_BINDGRANT":	[{
			"ATTESTATION_TYPE":	"",
			"BINDCONNECT_TYPE":	"",
			"REGISTER_INFO":	""
		}],
	"SYS_PAGE":	{
		"PAGE_NO":	0,
		"PAGE_ROWS":	0,
		"NEXT_YESNO":	"",
		"TOTAL":	0
	},
	"SYS_HEAD":	{
		"CHANNEL_DID":	"",
		"DYNAMIC_KEY":	"",
		"REGISTER_DID":	""
	},
	"SYS_REG_CONNECT":	[{
			"REGISTER_DID":	"",
			"ACCOUNT_DID":	"",
			"ACCOUNT_TYPE":	"",
			"BUSINESS_DESC":	""
		}],
	"SYS_HEAD":	{
		"CHANNEL_DID":	"",
		"DYNAMIC_KEY":	"",
		"REGISTER_DID":	""
	},
	"CUS_ACCOUNT":	[{
			"CERTIFICATES_INFO":	"",
			"MOBILE_PHONE_INFO":	"",
			"ACC_CERT_INFO":	"",
			"CUSTOMER_NAME":	"",
			"ATTESTATION_TYPE":	""
		}],
	"SYS_HEAD":	{
		"CHANNEL_DID":	"",
		"DYNAMIC_KEY":	"",
		"REGISTER_DID":	""
	},
	"CUS_ACCOUNT":	[{
			"CERTIFICATES_INFO":	"",
			"MOBILE_PHONE_INFO":	"",
			"ACC_CERT_INFO":	"",
			"CUSTOMER_NAME":	"",
			"ATTESTATION_TYPE":	""
		}],
	"SYS_HEAD":	{
		"CHANNEL_DID":	"",
		"DYNAMIC_KEY":	"",
		"REGISTER_DID":	"",
		"ACCOUNT_DID":	""
	},
	"ACCOUNT_CONNECT":	[{
			"ACCOUNT_DID":	""
		}],
	"SYS_HEAD":	{
		"CHANNEL_DID":	"",
		"DYNAMIC_KEY":	"",
		"REGISTER_DID":	""
	},
	"SUP_ACCOUNT":	[{
			"ACC_CERT_INFO":	"",
			"ACC_CERT_TYPE":	"",
			"ACCOUNT_PASSWORD":	"",
			"SUPPLIER_NAME":	"",
			"ADMIN_CODE_INFO":	"",
			"ADDRESS":	"",
			"SUPPLIER_TYPE":	"",
			"TAX_NUMBER_INFO":	"",
			"TELEPHONE_INFO":	"",
			"BANK_ACCOUNT_INFO":	"",
			"BANK_NAME":	"",
			"EMAIL_INFO":	"",
			"VERIFY_CODE":	""
		}],
	"SYS_HEAD":	{
		"CHANNEL_DID":	"",
		"DYNAMIC_KEY":	"",
		"REGISTER_DID":	""
	},
	"SUP_ACCOUNT":	[{
			"SUPPLIER_DID":	""
		}],
	"SYS_HEAD":	{
		"CHANNEL_DID":	"",
		"DYNAMIC_KEY":	"",
		"REGISTER_DID":	"",
		"ACCOUNT_DID":	""
	},
	"SUP_ACCOUNT":	[{
			"SUPPLIER_NAME":	"",
			"EMAIL_INFO":	"",
			"VERIFY_CODE":	"",
			"TAX_NUMBER_INFO":	"",
			"TELEPHONE_INFO":	"",
			"BANK_ACCOUNT_INFO":	"",
			"BANK_NAME":	"",
			"ADMIN_CODE_INFO":	"",
			"ADDRESS":	""
		}],
	"SYS_HEAD":	{
		"CHANNEL_DID":	"",
		"DYNAMIC_KEY":	"",
		"REGISTER_DID":	"",
		"ACCOUNT_DID":	""
	},
	"SUP_ACCOUNT":	[{
			"ACCOUNT_PASSWORD":	"",
			"VERIFY_CODE":	""
		}],
	"SYS_HEAD":	{
		"CHANNEL_DID":	"",
		"DYNAMIC_KEY":	"",
		"REGISTER_DID":	"",
		"ACCOUNT_DID":	""
	},
	"SUP_ACCOUNT":	[{
			"MOBILE_PHONE_INFO":	"",
			"VERIFY_CODE":	""
		}],
	"SYS_HEAD":	{
		"CHANNEL_DID":	"",
		"DYNAMIC_KEY":	"",
		"REGISTER_DID":	"",
		"ACCOUNT_DID":	""
	},
	"SUP_ACCOUNT":	[{
			"EMAIL_INFO":	"",
			"VERIFY_CODE":	""
		}],
	"SYS_HEAD":	{
		"CHANNEL_DID":	"",
		"DYNAMIC_KEY":	"",
		"REGISTER_DID":	"",
		"ACCOUNT_DID":	""
	},
	"USER_ACCOUNT":	[{
			"USER_ACCOUNT_AID":	"",
			"RESIDENT_YESNO":	"",
			"ATTESTATION_TYPE":	"",
			"RISK_BALANCE":	0,
			"MARGIN_BALANCE":	0,
			"ADVANCE_LIMIT":	0,
			"MAP_NAME":	"",
			"X":	0,
			"Y":	0
		}],
	"SYS_HEAD":	{
		"CHANNEL_DID":	"",
		"DYNAMIC_KEY":	"",
		"REGISTER_DID":	"",
		"ACCOUNT_DID":	""
	},
	"USER_ACCOUNT":	[{
			"CUSTOMER_DID":	"",
			"USER_CUS_DID":	"",
			"USER_NAME":	"",
			"ADMIN_CODE_INFO":	"",
			"ADDRESS":	"",
			"MAP_NAME":	"",
			"X":	0,
			"Y":	0,
			"RESIDENT_YESNO":	"",
			"ATTESTATION_TYPE":	"",
			"RISK_BALANCE":	0,
			"MARGIN_BALANCE":	0,
			"ADVANCE_LIMIT":	0
		}],
	"SYS_HEAD":	{
		"CHANNEL_DID":	"",
		"DYNAMIC_KEY":	"",
		"REGISTER_DID":	"",
		"ACCOUNT_DID":	""
	},
	"SETTLE_ACCOUNT":	[{
			"CUSTOMER_DID":	"",
			"USER_CUS_DID":	"",
			"USER_ACCOUNT_AID":	"",
			"SETTLEMENT_AID":	"",
			"SETTLEMENT_NAME":	"",
			"ATTESTATION_TYPE":	"",
			"ADDRESS":	"",
			"CONTROL_TYPE":	"",
			"INDUSTRY_CODE_INFO":	"",
			"INDUSTRY_TYPE":	"",
			"RESIDENT_YESNO":	"",
			"CITY_YESNO":	"",
			"ARMY_YESNO":	"",
			"TEMPORARY_YESNO":	"",
			"PUBLIC_USE_YESNO":	"",
			"CONNECT_MODE_TYPE":	"",
			"SIGN_CONTRACT_YESNO":	"",
			"CONTRACT_NUM":	"",
			"CON_DEADLINE_DATE":	0,
			"REMARK_INS":	""
		}],
	"SYS_HEAD":	{
		"CHANNEL_DID":	"",
		"DYNAMIC_KEY":	"",
		"REGISTER_DID":	"",
		"ACCOUNT_DID":	""
	},
	"SETTLE_ACCOUNT":	[{
			"CUSTOMER_DID":	"",
			"USER_CUS_DID":	"",
			"USER_ACCOUNT_AID":	"",
			"SETTLEMENT_NAME":	"",
			"ATTESTATION_TYPE":	"",
			"ADDRESS":	"",
			"CONTROL_TYPE":	"",
			"INDUSTRY_CODE_INFO":	"",
			"INDUSTRY_TYPE":	"",
			"RESIDENT_YESNO":	"",
			"CITY_YESNO":	"",
			"ARMY_YESNO":	"",
			"TEMPORARY_YESNO":	"",
			"PUBLIC_USE_YESNO":	"",
			"CONNECT_MODE_TYPE":	"",
			"SIGN_CONTRACT_YESNO":	"",
			"CONTRACT_NUM":	"",
			"CON_DEADLINE_DATE":	0,
			"REMARK_INS":	""
		}],
	"SYS_HEAD":	{
		"CHANNEL_DID":	"",
		"DYNAMIC_KEY":	"",
		"REGISTER_DID":	"",
		"ACCOUNT_DID":	""
	},
	"SETTLE_ACCOUNT":	[{
			"SETTLEMENT_AID":	""
		}],
	"SYS_HEAD":	{
		"CHANNEL_DID":	"",
		"DYNAMIC_KEY":	"",
		"REGISTER_DID":	"",
		"ACCOUNT_DID":	""
	},
	"SETTLE_METERAGE":	[{
			"ADDRESS":	"",
			"BOOK_AID":	"",
			"NODE_AID":	"",
			"NETWORK_TYPE":	"",
			"METER_YESNO":	"",
			"DEVICE_DID":	"",
			"NETWORK_CO_DID":	"",
			"NET_STORES_AID":	"",
			"RETAIL_CO_DID":	"",
			"RET_STORES_AID":	"",
			"ASSESS_YESNO":	"",
			"PURCHASE_SALE_TYPE":	"",
			"ENERGY_LOAD":	0,
			"ACCOUNT_ITEM_INFO":	"",
			"AGREE_PRICE_YESNO":	"",
			"PROTOCOL_DID":	"",
			"STOP_EMPTY_YESNO":	"",
			"OUTAGE_VACANCY_DATE":	0,
			"RESUPPLY_DATE":	0,
			"SETTLEMENT_DATE_TYPE":	"",
			"MAIN_PACK_DID":	"",
			"TEMP_PACK_DID":	"",
			"TMP_MONTHS":	0,
			"BASIC_FEES_TYPE":	"",
			"LOAD_CAPACITY":	0,
			"METER_DEMAND_RATE":	0,
			"MAX_DEMAND_APPR":	0,
			"COMP_DEVIATION_YESNO":	"",
			"FOR_RATE_VALID_TYPE":	"",
			"ABUND_WITHER_YESNO":	"",
			"TIME_FEES_TYPE":	"",
			"LADDER_TYPE":	"",
			"LADDER_NAME_TYPE":	"",
			"FIXED_CHARGE":	0,
			"FIXED_FEE":	0,
			"DIVI_FIXED_CHARGE":	0,
			"MET_DIVID_RATIO":	0,
			"FLOOR_NUM":	0,
			"FLOOR_HEIGHT":	0,
			"CHARGE_AREA_FACTOR":	0,
			"ACTUAL_AREA":	0,
			"CHARGE_POPULATION":	0,
			"CHARGE_HOUSEHOLDS":	0
		}],
	"SYS_HEAD":	{
		"CHANNEL_DID":	"",
		"DYNAMIC_KEY":	"",
		"REGISTER_DID":	""
	},
	"SETTLE_METERAGE":	[{
			"SETTLEMENT_AID":	"",
			"ADDRESS":	""
		}],
	"SYS_HEAD":	{
		"CHANNEL_DID":	"",
		"DYNAMIC_KEY":	"",
		"REGISTER_DID":	"",
		"ACCOUNT_DID":	""
	},
	"SETTLE_METERAGE":	[{
			"SETTLEMENT_AID":	"",
			"ADDRESS":	"",
			"BOOK_AID":	"",
			"NODE_AID":	"",
			"NETWORK_TYPE":	"",
			"METER_YESNO":	"",
			"DEVICE_DID":	"",
			"REAL_ESTATE_AID":	"",
			"NETWORK_CO_DID":	"",
			"NET_STORES_AID":	"",
			"RETAIL_CO_DID":	"",
			"RET_STORES_AID":	"",
			"ASSESS_YESNO":	"",
			"PURCHASE_SALE_TYPE":	"",
			"ENERGY_LOAD":	0,
			"ACCOUNT_ITEM_INFO":	"",
			"AGREE_PRICE_YESNO":	"",
			"PROTOCOL_DID":	"",
			"STOP_EMPTY_YESNO":	"",
			"OUTAGE_VACANCY_DATE":	0,
			"RESUPPLY_DATE":	0,
			"SETTLEMENT_DATE_TYPE":	"",
			"MAIN_PACK_DID":	"",
			"TEMP_PACK_DID":	"",
			"TMP_MONTHS":	0,
			"BASIC_FEES_TYPE":	"",
			"LOAD_CAPACITY":	0,
			"METER_DEMAND_RATE":	0,
			"MAX_DEMAND_APPR":	0,
			"COMP_DEVIATION_YESNO":	"",
			"FOR_RATE_VALID_TYPE":	"",
			"ABUND_WITHER_YESNO":	"",
			"TIME_FEES_TYPE":	"",
			"LADDER_TYPE":	"",
			"LADDER_NAME_TYPE":	"",
			"FIXED_CHARGE":	0,
			"FIXED_FEE":	0,
			"DIVI_FIXED_CHARGE":	0,
			"MET_DIVID_RATIO":	0,
			"FLOOR_NUM":	0,
			"FLOOR_HEIGHT":	0,
			"CHARGE_AREA_FACTOR":	0,
			"ACTUAL_AREA":	0,
			"CHARGE_POPULATION":	0,
			"CHARGE_HOUSEHOLDS":	0
		}],
	"SYS_HEAD":	{
		"CHANNEL_DID":	"",
		"DYNAMIC_KEY":	"",
		"REGISTER_DID":	"",
		"ACCOUNT_DID":	""
	},
	"SETTLE_METERAGE":	[{
			"SETTLEMENT_AID":	""
		}],
	"SYS_HEAD":	{
		"CHANNEL_DID":	"",
		"DYNAMIC_KEY":	"",
		"REGISTER_DID":	"",
		"ACCOUNT_DID":	""
	},
	"USER_ACCOUNT":	[{
			"USER_ACCOUNT_AID":	"",
			"CUSTOMER_DID":	""
		}],
	"SETTLE_ACCOUNT":	[{
			"SETTLEMENT_AID":	""
		}],
	"SYS_HEAD":	{
		"CHANNEL_DID":	"",
		"DYNAMIC_KEY":	"",
		"REGISTER_DID":	""
	},
	"CUS_ACCOUNT":	[{
			"ACC_CERT_INFO":	"",
			"ACC_CERT_TYPE":	"",
			"ACCOUNT_PASSWORD":	"",
			"CUSTOMER_NAME":	"",
			"ADMIN_CODE_INFO":	"",
			"ADDRESS":	"",
			"CUSTOMER_TYPE":	"",
			"TAX_NUMBER_INFO":	"",
			"TELEPHONE_INFO":	"",
			"BANK_ACCOUNT_INFO":	"",
			"BANK_NAME":	"",
			"EMAIL_INFO":	"",
			"VERIFY_CODE":	""
		}],
	"SYS_HEAD":	{
		"CHANNEL_DID":	"",
		"DYNAMIC_KEY":	"",
		"REGISTER_DID":	""
	},
	"CUS_ACCOUNT":	[{
			"CUSTOMER_DID":	""
		}],
	"SYS_HEAD":	{
		"CHANNEL_DID":	"",
		"DYNAMIC_KEY":	"",
		"REGISTER_DID":	"",
		"ACCOUNT_DID":	""
	},
	"CUS_ACCOUNT":	[{
			"CUSTOMER_NAME":	"",
			"EMAIL_INFO":	"",
			"VERIFY_CODE":	"",
			"TAX_NUMBER_INFO":	"",
			"TELEPHONE_INFO":	"",
			"BANK_ACCOUNT_INFO":	"",
			"BANK_NAME":	"",
			"ADMIN_CODE_INFO":	"",
			"ADDRESS":	""
		}],
	"SYS_HEAD":	{
		"CHANNEL_DID":	"",
		"DYNAMIC_KEY":	"",
		"REGISTER_DID":	"",
		"ACCOUNT_DID":	""
	},
	"CUS_ACCOUNT":	[{
			"ACCOUNT_PASSWORD":	"",
			"VERIFY_CODE":	""
		}],
	"SYS_HEAD":	{
		"CHANNEL_DID":	"",
		"DYNAMIC_KEY":	"",
		"REGISTER_DID":	"",
		"ACCOUNT_DID":	""
	},
	"CUS_ACCOUNT":	[{
			"MOBILE_PHONE_INFO":	"",
			"VERIFY_CODE":	""
		}],
	"SYS_HEAD":	{
		"CHANNEL_DID":	"",
		"DYNAMIC_KEY":	"",
		"REGISTER_DID":	"",
		"ACCOUNT_DID":	""
	},
	"CUS_ACCOUNT":	[{
			"EMAIL_INFO":	"",
			"VERIFY_CODE":	""
		}],
	"SYS_HEAD":	{
		"CHANNEL_DID":	"",
		"DYNAMIC_KEY":	"",
		"REGISTER_DID":	"",
		"ACCOUNT_DID":	""
	},
	"USER_ACCOUNT":	[{
			"USER_NAME":	"",
			"ADMIN_CODE_INFO":	"",
			"ADDRESS":	"",
			"MAP_NAME":	"",
			"X":	0,
			"Y":	0
		}],
	"SYS_HEAD":	{
		"CHANNEL_DID":	"",
		"DYNAMIC_KEY":	"",
		"REGISTER_DID":	"",
		"ACCOUNT_DID":	""
	},
	"USER_ACCOUNT":	[{
			"ATTESTATION_TYPE":	""
		}],
	"SYS_HEAD":	{
		"CHANNEL_DID":	"",
		"DYNAMIC_KEY":	"",
		"REGISTER_DID":	"",
		"ACCOUNT_DID":	""
	},
	"USER_ACCOUNT":	[{
			"USER_ACCOUNT_AID":	"",
			"USER_NAME":	"",
			"ADMIN_CODE_INFO":	"",
			"ADDRESS":	"",
			"MAP_NAME":	"",
			"X":	0,
			"Y":	0
		}],
	"SYS_HEAD":	{
		"CHANNEL_DID":	"",
		"DYNAMIC_KEY":	"",
		"REGISTER_DID":	"",
		"ACCOUNT_DID":	""
	},
	"USER_ACCOUNT":	[{
			"USER_ACCOUNT_AID":	""
		}],
	"SYS_HEAD":	{
		"CHANNEL_DID":	"",
		"DYNAMIC_KEY":	"",
		"REGISTER_DID":	"",
		"ACCOUNT_DID":	""
	},
	"CUS_ACCOUNT":	[{
			"ATTESTATION_TYPE":	""
		}],
	"SYS_HEAD":	{
		"CHANNEL_DID":	"",
		"DYNAMIC_KEY":	"",
		"REGISTER_DID":	"",
		"ACCOUNT_DID":	""
	},
	"USER_ACCOUNT":	[{
			"USER_ACCOUNT_AID":	"",
			"USER_CUS_DID":	""
		}],
	"SETTLE_ACCOUNT":	[{
			"SETTLEMENT_AID":	""
		}],
	"SYS_HEAD":	{
		"CHANNEL_DID":	"",
		"DYNAMIC_KEY":	"",
		"REGISTER_DID":	"",
		"ACCOUNT_DID":	""
	},
	"USER_ACCOUNT":	[{
			"USER_ACCOUNT_AID":	"",
			"ATTESTATION_TYPE":	""
		}],
	"SYS_HEAD":	{
		"CHANNEL_DID":	"",
		"DYNAMIC_KEY":	"",
		"REGISTER_DID":	"",
		"ACCOUNT_DID":	""
	},
	"USER_ACCOUNT":	[{
			"USER_ACCOUNT_AID":	""
		}],
	"SYS_HEAD":	{
		"CHANNEL_DID":	"",
		"DYNAMIC_KEY":	"",
		"REGISTER_DID":	"",
		"ACCOUNT_DID":	""
	},
	"USER_ACCOUNT":	[{
			"USER_ACCOUNT_AID":	""
		}],
	"SYS_HEAD":	{
		"CHANNEL_DID":	"",
		"DYNAMIC_KEY":	"",
		"REGISTER_DID":	"",
		"ACCOUNT_DID":	""
	},
	"USER_ACCOUNT":	[{
			"USER_ACCOUNT_AID":	"",
			"ATTESTATION_TYPE":	""
		}],
	"SYS_HEAD":	{
		"CHANNEL_DID":	"",
		"DYNAMIC_KEY":	"",
		"REGISTER_DID":	"",
		"ACCOUNT_DID":	""
	},
	"USER_ACCOUNT":	[{
			"USER_ACCOUNT_AID":	"",
			"CUSTOMER_DID":	""
		}],
	"SETTLE_ACCOUNT":	[{
			"SETTLEMENT_AID":	""
		}],
	"SYS_HEAD":	{
		"CHANNEL_DID":	"",
		"DYNAMIC_KEY":	"",
		"REGISTER_DID":	"",
		"ACCOUNT_DID":	""
	},
	"USER_ACCOUNT":	[{
			"USER_ACCOUNT_AID":	"",
			"ATTESTATION_TYPE":	""
		}]
}  
~~~  
## 4. 服务接口响应参数  
本服务接口响应参数说明：无响应参数  
## 5. 服务接口说明  
xxxxxxx  
