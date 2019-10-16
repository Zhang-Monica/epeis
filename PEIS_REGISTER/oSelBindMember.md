## 1、接口描述  
服务接口：(oSelBindMember)绑定成员查询  
接口描述：xxxxx  
请求说明：POST https://epeis.com/Service/V1/oSelBindMember  
  
## 2、服务接口请求参数  
#### 2.1、公共请求参数  
公共请求参数说明，参数对象名：SYS_HEAD，参数对象类型：object  
  
| 参数 | 必选 | 类型 | 描述 |  
| :----------------- | :----: | :-------- | :---------------- |  
| CHANNEL_DID | 是 | String | 16字符渠道号 |  
| DYNAMIC_KEY | 是 | String | 动态请求密钥 |  
| REGISTER_DID      |  是  | String   | 16位注册ID，必须实名 |  
  
#### 2.2、请求参数  
本服务接口请求参数说明，参数对象名：SYS_REG_CONNECT，参数对象类型：Array，请求参数描述：xxxxx  
  

| 参数              | 必选 | 类型     | 描述             |  
| :----------------- | :----: | :-------- | :---------------- |  
| REGISTER_DID |  是  | String   | xxxxx |  
| ACCOUNT_DID |  是  | String   | xxxxx |  
| ACCOUNT_TYPE |  是  | String   | xxxxx |  
#### 2.3、请求参数报文示例  
~~~  
{
	"SYS_HEAD":	{
		"CHANNEL_DID":	"",
		"DYNAMIC_KEY":	"",
		"REGISTER_DID":	""
	},
	"SYS_REG_CONNECT":	[{
			"REGISTER_DID":	"",
			"ACCOUNT_DID":	"",
			"ACCOUNT_TYPE":	""
		}]
}  
~~~  
  
## 3、服务接口响应参数  
#### 3.1、公共响应参数  
公共响应参数说明，参数对象名：SYS_HEAD，参数对象类型：object  
  
| 参数              | 必选 | 类型     | 描述             |  
| :----------------- | :----: | :-------- | :---------------- |  
| CODE | 是 | Number | 响应代码，0为成功 |  
| MESSAGE | 是 | String | 响应信息 |  
| DATA | 是 | Object | 响应数据 |  
  
#### 3.2、响应参数  
本服务接口响应参数说明，参数对象名：INOUT_BINDMEMBER，参数对象类型：Array，响应参数描述：xxxxx  
  

| 参数              | 必选 | 类型     | 描述             |  
| :----------------- | :----: | :-------- | :---------------- |  
| REGISTER_DID |  是  | String   | xxxxx |  
| REGISTER_INFO |  是  | String   | xxxxx |  
| REGISTER_NAME |  是  | String   | xxxxx |  
| CERTIFICATES_INFO |  是  | String   | xxxxx |  
| CERTIFICATES_TYPE |  是  | String   | xxxxx |  
| ACCOUNT_DID |  是  | String   | xxxxx |  
| ACCOUNT_TYPE |  是  | String   | xxxxx |  
| ACCOUNT_NAME |  是  | String   | xxxxx |  
| MOBILE_PHONE_INFO |  是  | String   | xxxxx |  
| EMAIL_INFO |  是  | String   | xxxxx |  
| ACC_REGI_DID |  是  | String   | xxxxx |  
| ADMIN_CODE_INFO |  是  | String   | xxxxx |  
| ADDRESS |  是  | String   | xxxxx |  
| TAX_TYPE |  是  | String   | xxxxx |  
| TAX_NUMBER_INFO |  是  | String   | xxxxx |  
| TELEPHONE_INFO |  是  | String   | xxxxx |  
| BANK_NAME |  是  | String   | xxxxx |  
| ACC_CERT_INFO |  是  | String   | xxxxx |  
| ACC_CERT_TYPE |  是  | String   | xxxxx |  
| BUSINESS_DESC |  是  | String   | xxxxx |  
| ATTESTATION_TYPE |  是  | String   | xxxxx |  
| OPERATION_DATE |  是  | Number   | xxxxx |  
| OPERATION_TIME |  是  | Number   | xxxxx |  
  
#### 3.3、响应参数报文示例  
~~~  
{
	"CODE":	0,
	"MESSAGE":	"",
	"DATA":	{
		"INOUT_BINDMEMBER":	[{
				"REGISTER_DID":	"",
				"REGISTER_INFO":	"",
				"REGISTER_NAME":	"",
				"CERTIFICATES_INFO":	"",
				"CERTIFICATES_TYPE":	"",
				"ACCOUNT_DID":	"",
				"ACCOUNT_TYPE":	"",
				"ACCOUNT_NAME":	"",
				"MOBILE_PHONE_INFO":	"",
				"EMAIL_INFO":	"",
				"ACC_REGI_DID":	"",
				"ADMIN_CODE_INFO":	"",
				"ADDRESS":	"",
				"TAX_TYPE":	"",
				"TAX_NUMBER_INFO":	"",
				"TELEPHONE_INFO":	"",
				"BANK_NAME":	"",
				"ACC_CERT_INFO":	"",
				"ACC_CERT_TYPE":	"",
				"BUSINESS_DESC":	"",
				"ATTESTATION_TYPE":	"",
				"OPERATION_DATE":	0,
				"OPERATION_TIME":	0
			}]
	}
}  
~~~  
## 4、服务接口说明  
xxxxxxx  
