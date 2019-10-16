## 1、接口描述  
服务接口：(pSelChaService)渠道服务查询  
接口描述：xxxxx  
请求说明：POST https://epeis.com/Service/V1/pSelChaService  
  
## 2、服务接口请求参数  
#### 2.1、公共请求参数  
公共请求参数说明，参数对象名：SYS_HEAD，参数对象类型：object  
  
| 参数 | 必选 | 类型 | 描述 |  
| :----------------- | :----: | :-------- | :---------------- |  
| CHANNEL_DID | 是 | String | 16字符渠道号 |  
| DYNAMIC_KEY | 是 | String | 动态请求密钥 |  
| REGISTER_DID      |  是  | String   | 16位注册ID，必须实名 |  
| ACCOUNT_DID       |  是  | String   | 16位账户ID，必须激活 |  
  
#### 2.2、请求参数  
本服务接口请求参数说明，参数对象名：SYS_CHANNEL，参数对象类型：Array，请求参数描述：xxxxx  
  

| 参数              | 必选 | 类型     | 描述             |  
| :----------------- | :----: | :-------- | :---------------- |  
| CHANNEL_DID |  是  | String   | xxxxx |  
#### 2.3、请求参数报文示例  
~~~  
{
	"SYS_HEAD":	{
		"CHANNEL_DID":	"",
		"DYNAMIC_KEY":	"",
		"REGISTER_DID":	"",
		"ACCOUNT_DID":	""
	},
	"SYS_CHANNEL":	[{
			"CHANNEL_DID":	""
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
本服务接口响应参数说明，参数对象名：SYS_CHA_SERVICE，参数对象类型：Array，响应参数描述：xxxxx  
  

| 参数              | 必选 | 类型     | 描述             |  
| :----------------- | :----: | :-------- | :---------------- |  
| CHANNEL_DID |  是  | String   | xxxxx |  
| SERVICE_NAME_INFO |  是  | String   | xxxxx |  
| SERVICE_TYPE |  是  | String   | xxxxx |  
| REG_ATTESTATION_TYPE |  是  | String   | xxxxx |  
| ACC_ATTESTATION_TYPE |  是  | String   | xxxxx |  
| REG_ACC_CONNECT_TYPE |  是  | String   | xxxxx |  
  
#### 3.3、响应参数报文示例  
~~~  
{
	"CODE":	0,
	"MESSAGE":	"",
	"DATA":	{
		"SYS_CHA_SERVICE":	[{
				"CHANNEL_DID":	"",
				"SERVICE_NAME_INFO":	"",
				"SERVICE_TYPE":	"",
				"REG_ATTESTATION_TYPE":	"",
				"ACC_ATTESTATION_TYPE":	"",
				"REG_ACC_CONNECT_TYPE":	""
			}]
	}
}  
~~~  
## 4、服务接口说明  
xxxxxxx  
