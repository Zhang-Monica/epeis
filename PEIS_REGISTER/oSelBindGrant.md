## 1、接口描述  
服务接口：(oSelBindGrant)授权关系查询  
接口描述：xxxxx  
请求说明：POST https://epeis.com/Service/V1/oSelBindGrant  
  
## 2、服务接口请求参数  
#### 2.1、公共请求参数  
公共请求参数说明，参数对象名：SYS_HEAD，参数对象类型：object  
  
| 参数 | 必选 | 类型 | 描述 |  
| :----------------- | :----: | :-------- | :---------------- |  
| CHANNEL_DID | 是 | String | 16字符渠道号 |  
| DYNAMIC_KEY | 是 | String | 动态请求密钥 |  
| REGISTER_DID      |  是  | String   | 16位注册ID，必须实名 |  
  
#### 2.2、请求参数  
本服务接口请求参数说明，参数对象名：INOUT_BINDGRANT，参数对象类型：Array，请求参数描述：xxxxx  
  

| 参数              | 必选 | 类型     | 描述             |  
| :----------------- | :----: | :-------- | :---------------- |  
| ATTESTATION_TYPE |  是  | String   | xxxxx |  
| BINDCONNECT_TYPE |  是  | String   | xxxxx |  
| REGISTER_INFO |  是  | String   | xxxxx |  
本服务接口请求参数说明，参数对象名：SYS_PAGE，参数对象类型：object，请求参数描述：xxxxx  
  

| 参数              | 必选 | 类型     | 描述             |  
| :----------------- | :----: | :-------- | :---------------- |  
| PAGE_NO |  是  | Number   | xxxxx |  
| PAGE_ROWS |  否  | Number   | xxxxx |  
| NEXT_YESNO |  是  | String   | xxxxx |  
| TOTAL |  否  | Number   | xxxxx |  
#### 2.3、请求参数报文示例  
~~~  
{
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
	}
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
本服务接口响应参数说明，参数对象名：INOUT_BINDGRANT，参数对象类型：Array，响应参数描述：xxxxx  
  

| 参数              | 必选 | 类型     | 描述             |  
| :----------------- | :----: | :-------- | :---------------- |  
| REGISTER_DID |  是  | String   | xxxxx |  
| REGISTER_NAME |  是  | String   | xxxxx |  
| ACCOUNT_DID |  是  | String   | xxxxx |  
| ACCOUNT_TYPE |  是  | String   | xxxxx |  
| ACCOUNT_NAME |  是  | String   | xxxxx |  
| BUSINESS_DESC |  是  | String   | xxxxx |  
| ATTESTATION_TYPE |  是  | String   | xxxxx |  
| BINDCONNECT_TYPE |  是  | String   | xxxxx |  
  
本服务接口响应参数说明，参数对象名：SYS_PAGE，参数对象类型：object，响应参数描述：xxxxx  
  

| 参数              | 必选 | 类型     | 描述             |  
| :----------------- | :----: | :-------- | :---------------- |  
| PAGE_NO |  否  | Number   | xxxxx |  
| PAGE_ROWS |  否  | Number   | xxxxx |  
| NEXT_YESNO |  否  | String   | xxxxx |  
| TOTAL |  否  | Number   | xxxxx |  
  
#### 3.3、响应参数报文示例  
~~~  
{
	"CODE":	0,
	"MESSAGE":	"",
	"DATA":	{
		"INOUT_BINDGRANT":	[{
				"REGISTER_DID":	"",
				"REGISTER_NAME":	"",
				"ACCOUNT_DID":	"",
				"ACCOUNT_TYPE":	"",
				"ACCOUNT_NAME":	"",
				"BUSINESS_DESC":	"",
				"ATTESTATION_TYPE":	"",
				"BINDCONNECT_TYPE":	""
			}],
		"SYS_PAGE":	{
			"PAGE_NO":	0,
			"PAGE_ROWS":	0,
			"NEXT_YESNO":	"",
			"TOTAL":	0
		}
	}
}  
~~~  
## 4、服务接口说明  
xxxxxxx  
