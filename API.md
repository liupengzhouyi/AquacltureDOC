# Aquacltureserver APIs


**简介**:Aquacltureserver APIs


**HOST**:127.0.0.1:8080


**联系人**:


**Version**:1.0


**接口路径**:undefined


[TOC]






# 员工管理


## 添加员工


**接口地址**:`/staff/addOne`


**请求方式**:`POST`


**请求数据类型**:`application/json`


**响应数据类型**:`application/json;charset=UTF-8`


**接口描述**:


**请求示例**:


```javascript
{
	"entryDate": "",
	"id": 0,
	"idCardNumber": "",
	"isSeparation": 0,
	"name": "",
	"phoneNumber": "",
	"positionId": 0,
	"separationDate": "",
	"wage": 0
}
```


**请求参数**:


| 参数名称                   | 参数说明 | in   | 是否必须 | 数据类型          | schema |
| -------------------------- | -------- | ---- | -------- | ----------------- | ------ |
| staff                      | staff    | body | true     | Staff             | Staff  |
| &emsp;&emsp;entryDate      |          |      | false    | string(date-time) |        |
| &emsp;&emsp;id             |          |      | false    | integer(int32)    |        |
| &emsp;&emsp;idCardNumber   |          |      | false    | string            |        |
| &emsp;&emsp;isSeparation   |          |      | false    | integer(int32)    |        |
| &emsp;&emsp;name           |          |      | false    | string            |        |
| &emsp;&emsp;phoneNumber    |          |      | false    | string            |        |
| &emsp;&emsp;positionId     |          |      | false    | integer(int32)    |        |
| &emsp;&emsp;separationDate |          |      | false    | string(date-time) |        |
| &emsp;&emsp;wage           |          |      | false    | number(double)    |        |


**响应状态**:


| 状态码 | 说明         | schema |
| ------ | ------------ | ------ |
| 200    | OK           | Staff  |
| 201    | Created      |        |
| 401    | Unauthorized |        |
| 403    | Forbidden    |        |
| 404    | Not Found    |        |


**响应参数**:


| 参数名称       | 参数说明 | 类型              | schema            |
| -------------- | -------- | ----------------- | ----------------- |
| entryDate      |          | string(date-time) | string(date-time) |
| id             |          | integer(int32)    | integer(int32)    |
| idCardNumber   |          | string            |                   |
| isSeparation   |          | integer(int32)    | integer(int32)    |
| name           |          | string            |                   |
| phoneNumber    |          | string            |                   |
| positionId     |          | integer(int32)    | integer(int32)    |
| separationDate |          | string(date-time) | string(date-time) |
| wage           |          | number(double)    | number(double)    |


**响应示例**:
```javascript
{
	"entryDate": "",
	"id": 0,
	"idCardNumber": "",
	"isSeparation": 0,
	"name": "",
	"phoneNumber": "",
	"positionId": 0,
	"separationDate": "",
	"wage": 0
}
```


## 通过ID删除员工信息


**接口地址**:`/staff/deleteOne`


**请求方式**:`POST`


**请求数据类型**:`application/json`


**响应数据类型**:`application/json;charset=UTF-8`


**接口描述**:


**请求示例**:


```javascript
{
	"entryDate": "",
	"id": 0,
	"idCardNumber": "",
	"isSeparation": 0,
	"name": "",
	"phoneNumber": "",
	"positionId": 0,
	"separationDate": "",
	"wage": 0
}
```


**请求参数**:


| 参数名称                   | 参数说明 | in   | 是否必须 | 数据类型          | schema |
| -------------------------- | -------- | ---- | -------- | ----------------- | ------ |
| staff                      | staff    | body | true     | Staff             | Staff  |
| &emsp;&emsp;entryDate      |          |      | false    | string(date-time) |        |
| &emsp;&emsp;id             |          |      | false    | integer(int32)    |        |
| &emsp;&emsp;idCardNumber   |          |      | false    | string            |        |
| &emsp;&emsp;isSeparation   |          |      | false    | integer(int32)    |        |
| &emsp;&emsp;name           |          |      | false    | string            |        |
| &emsp;&emsp;phoneNumber    |          |      | false    | string            |        |
| &emsp;&emsp;positionId     |          |      | false    | integer(int32)    |        |
| &emsp;&emsp;separationDate |          |      | false    | string(date-time) |        |
| &emsp;&emsp;wage           |          |      | false    | number(double)    |        |


**响应状态**:


| 状态码 | 说明         | schema |
| ------ | ------------ | ------ |
| 200    | OK           |        |
| 201    | Created      |        |
| 401    | Unauthorized |        |
| 403    | Forbidden    |        |
| 404    | Not Found    |        |


**响应参数**:


暂无


**响应示例**:
```javascript

```


## 办理员工离职


**接口地址**:`/staff/employeeResignation`


**请求方式**:`POST`


**请求数据类型**:`application/json`


**响应数据类型**:`application/json;charset=UTF-8`


**接口描述**:


**请求示例**:


```javascript
{
	"entryDate": "",
	"id": 0,
	"idCardNumber": "",
	"isSeparation": 0,
	"name": "",
	"phoneNumber": "",
	"positionId": 0,
	"separationDate": "",
	"wage": 0
}
```


**请求参数**:


| 参数名称                   | 参数说明 | in   | 是否必须 | 数据类型          | schema |
| -------------------------- | -------- | ---- | -------- | ----------------- | ------ |
| staff                      | staff    | body | true     | Staff             | Staff  |
| &emsp;&emsp;entryDate      |          |      | false    | string(date-time) |        |
| &emsp;&emsp;id             |          |      | false    | integer(int32)    |        |
| &emsp;&emsp;idCardNumber   |          |      | false    | string            |        |
| &emsp;&emsp;isSeparation   |          |      | false    | integer(int32)    |        |
| &emsp;&emsp;name           |          |      | false    | string            |        |
| &emsp;&emsp;phoneNumber    |          |      | false    | string            |        |
| &emsp;&emsp;positionId     |          |      | false    | integer(int32)    |        |
| &emsp;&emsp;separationDate |          |      | false    | string(date-time) |        |
| &emsp;&emsp;wage           |          |      | false    | number(double)    |        |


**响应状态**:


| 状态码 | 说明         | schema |
| ------ | ------------ | ------ |
| 200    | OK           | Staff  |
| 201    | Created      |        |
| 401    | Unauthorized |        |
| 403    | Forbidden    |        |
| 404    | Not Found    |        |


**响应参数**:


| 参数名称       | 参数说明 | 类型              | schema            |
| -------------- | -------- | ----------------- | ----------------- |
| entryDate      |          | string(date-time) | string(date-time) |
| id             |          | integer(int32)    | integer(int32)    |
| idCardNumber   |          | string            |                   |
| isSeparation   |          | integer(int32)    | integer(int32)    |
| name           |          | string            |                   |
| phoneNumber    |          | string            |                   |
| positionId     |          | integer(int32)    | integer(int32)    |
| separationDate |          | string(date-time) | string(date-time) |
| wage           |          | number(double)    | number(double)    |


**响应示例**:
```javascript
{
	"entryDate": "",
	"id": 0,
	"idCardNumber": "",
	"isSeparation": 0,
	"name": "",
	"phoneNumber": "",
	"positionId": 0,
	"separationDate": "",
	"wage": 0
}
```


## 查询全部员工


**接口地址**:`/staff/queryAll`


**请求方式**:`POST`


**请求数据类型**:`application/json`


**响应数据类型**:`application/json;charset=UTF-8`


**接口描述**:


**请求参数**:


暂无


**响应状态**:


| 状态码 | 说明         | schema |
| ------ | ------------ | ------ |
| 200    | OK           | Staff  |
| 201    | Created      |        |
| 401    | Unauthorized |        |
| 403    | Forbidden    |        |
| 404    | Not Found    |        |


**响应参数**:


| 参数名称       | 参数说明 | 类型              | schema            |
| -------------- | -------- | ----------------- | ----------------- |
| entryDate      |          | string(date-time) | string(date-time) |
| id             |          | integer(int32)    | integer(int32)    |
| idCardNumber   |          | string            |                   |
| isSeparation   |          | integer(int32)    | integer(int32)    |
| name           |          | string            |                   |
| phoneNumber    |          | string            |                   |
| positionId     |          | integer(int32)    | integer(int32)    |
| separationDate |          | string(date-time) | string(date-time) |
| wage           |          | number(double)    | number(double)    |


**响应示例**:
```javascript
[
	{
		"entryDate": "",
		"id": 0,
		"idCardNumber": "",
		"isSeparation": 0,
		"name": "",
		"phoneNumber": "",
		"positionId": 0,
		"separationDate": "",
		"wage": 0
	}
]
```


## 关键字IDCard查询员工


**接口地址**:`/staff/queryByIDCard`


**请求方式**:`POST`


**请求数据类型**:`application/json`


**响应数据类型**:`application/json;charset=UTF-8`


**接口描述**:


**请求示例**:


```javascript
{
	"entryDate": "",
	"id": 0,
	"idCardNumber": "",
	"isSeparation": 0,
	"name": "",
	"phoneNumber": "",
	"positionId": 0,
	"separationDate": "",
	"wage": 0
}
```


**请求参数**:


| 参数名称                   | 参数说明 | in   | 是否必须 | 数据类型          | schema |
| -------------------------- | -------- | ---- | -------- | ----------------- | ------ |
| staff                      | staff    | body | true     | Staff             | Staff  |
| &emsp;&emsp;entryDate      |          |      | false    | string(date-time) |        |
| &emsp;&emsp;id             |          |      | false    | integer(int32)    |        |
| &emsp;&emsp;idCardNumber   |          |      | false    | string            |        |
| &emsp;&emsp;isSeparation   |          |      | false    | integer(int32)    |        |
| &emsp;&emsp;name           |          |      | false    | string            |        |
| &emsp;&emsp;phoneNumber    |          |      | false    | string            |        |
| &emsp;&emsp;positionId     |          |      | false    | integer(int32)    |        |
| &emsp;&emsp;separationDate |          |      | false    | string(date-time) |        |
| &emsp;&emsp;wage           |          |      | false    | number(double)    |        |


**响应状态**:


| 状态码 | 说明         | schema |
| ------ | ------------ | ------ |
| 200    | OK           | Staff  |
| 201    | Created      |        |
| 401    | Unauthorized |        |
| 403    | Forbidden    |        |
| 404    | Not Found    |        |


**响应参数**:


| 参数名称       | 参数说明 | 类型              | schema            |
| -------------- | -------- | ----------------- | ----------------- |
| entryDate      |          | string(date-time) | string(date-time) |
| id             |          | integer(int32)    | integer(int32)    |
| idCardNumber   |          | string            |                   |
| isSeparation   |          | integer(int32)    | integer(int32)    |
| name           |          | string            |                   |
| phoneNumber    |          | string            |                   |
| positionId     |          | integer(int32)    | integer(int32)    |
| separationDate |          | string(date-time) | string(date-time) |
| wage           |          | number(double)    | number(double)    |


**响应示例**:
```javascript
[
	{
		"entryDate": "",
		"id": 0,
		"idCardNumber": "",
		"isSeparation": 0,
		"name": "",
		"phoneNumber": "",
		"positionId": 0,
		"separationDate": "",
		"wage": 0
	}
]
```


## 关键字Name查询员工


**接口地址**:`/staff/queryByName`


**请求方式**:`POST`


**请求数据类型**:`application/json`


**响应数据类型**:`application/json;charset=UTF-8`


**接口描述**:


**请求示例**:


```javascript
{
	"entryDate": "",
	"id": 0,
	"idCardNumber": "",
	"isSeparation": 0,
	"name": "",
	"phoneNumber": "",
	"positionId": 0,
	"separationDate": "",
	"wage": 0
}
```


**请求参数**:


| 参数名称                   | 参数说明 | in   | 是否必须 | 数据类型          | schema |
| -------------------------- | -------- | ---- | -------- | ----------------- | ------ |
| staff                      | staff    | body | true     | Staff             | Staff  |
| &emsp;&emsp;entryDate      |          |      | false    | string(date-time) |        |
| &emsp;&emsp;id             |          |      | false    | integer(int32)    |        |
| &emsp;&emsp;idCardNumber   |          |      | false    | string            |        |
| &emsp;&emsp;isSeparation   |          |      | false    | integer(int32)    |        |
| &emsp;&emsp;name           |          |      | false    | string            |        |
| &emsp;&emsp;phoneNumber    |          |      | false    | string            |        |
| &emsp;&emsp;positionId     |          |      | false    | integer(int32)    |        |
| &emsp;&emsp;separationDate |          |      | false    | string(date-time) |        |
| &emsp;&emsp;wage           |          |      | false    | number(double)    |        |


**响应状态**:


| 状态码 | 说明         | schema |
| ------ | ------------ | ------ |
| 200    | OK           | Staff  |
| 201    | Created      |        |
| 401    | Unauthorized |        |
| 403    | Forbidden    |        |
| 404    | Not Found    |        |


**响应参数**:


| 参数名称       | 参数说明 | 类型              | schema            |
| -------------- | -------- | ----------------- | ----------------- |
| entryDate      |          | string(date-time) | string(date-time) |
| id             |          | integer(int32)    | integer(int32)    |
| idCardNumber   |          | string            |                   |
| isSeparation   |          | integer(int32)    | integer(int32)    |
| name           |          | string            |                   |
| phoneNumber    |          | string            |                   |
| positionId     |          | integer(int32)    | integer(int32)    |
| separationDate |          | string(date-time) | string(date-time) |
| wage           |          | number(double)    | number(double)    |


**响应示例**:
```javascript
[
	{
		"entryDate": "",
		"id": 0,
		"idCardNumber": "",
		"isSeparation": 0,
		"name": "",
		"phoneNumber": "",
		"positionId": 0,
		"separationDate": "",
		"wage": 0
	}
]
```


## 关键字PhoneNUmber查询员工


**接口地址**:`/staff/queryByPhoneNumber`


**请求方式**:`POST`


**请求数据类型**:`application/json`


**响应数据类型**:`application/json;charset=UTF-8`


**接口描述**:


**请求示例**:


```javascript
{
	"entryDate": "",
	"id": 0,
	"idCardNumber": "",
	"isSeparation": 0,
	"name": "",
	"phoneNumber": "",
	"positionId": 0,
	"separationDate": "",
	"wage": 0
}
```


**请求参数**:


| 参数名称                   | 参数说明 | in   | 是否必须 | 数据类型          | schema |
| -------------------------- | -------- | ---- | -------- | ----------------- | ------ |
| staff                      | staff    | body | true     | Staff             | Staff  |
| &emsp;&emsp;entryDate      |          |      | false    | string(date-time) |        |
| &emsp;&emsp;id             |          |      | false    | integer(int32)    |        |
| &emsp;&emsp;idCardNumber   |          |      | false    | string            |        |
| &emsp;&emsp;isSeparation   |          |      | false    | integer(int32)    |        |
| &emsp;&emsp;name           |          |      | false    | string            |        |
| &emsp;&emsp;phoneNumber    |          |      | false    | string            |        |
| &emsp;&emsp;positionId     |          |      | false    | integer(int32)    |        |
| &emsp;&emsp;separationDate |          |      | false    | string(date-time) |        |
| &emsp;&emsp;wage           |          |      | false    | number(double)    |        |


**响应状态**:


| 状态码 | 说明         | schema |
| ------ | ------------ | ------ |
| 200    | OK           | Staff  |
| 201    | Created      |        |
| 401    | Unauthorized |        |
| 403    | Forbidden    |        |
| 404    | Not Found    |        |


**响应参数**:


| 参数名称       | 参数说明 | 类型              | schema            |
| -------------- | -------- | ----------------- | ----------------- |
| entryDate      |          | string(date-time) | string(date-time) |
| id             |          | integer(int32)    | integer(int32)    |
| idCardNumber   |          | string            |                   |
| isSeparation   |          | integer(int32)    | integer(int32)    |
| name           |          | string            |                   |
| phoneNumber    |          | string            |                   |
| positionId     |          | integer(int32)    | integer(int32)    |
| separationDate |          | string(date-time) | string(date-time) |
| wage           |          | number(double)    | number(double)    |


**响应示例**:
```javascript
[
	{
		"entryDate": "",
		"id": 0,
		"idCardNumber": "",
		"isSeparation": 0,
		"name": "",
		"phoneNumber": "",
		"positionId": 0,
		"separationDate": "",
		"wage": 0
	}
]
```


## 查询在职员工


**接口地址**:`/staff/queryOnJob`


**请求方式**:`POST`


**请求数据类型**:`application/json`


**响应数据类型**:`application/json;charset=UTF-8`


**接口描述**:


**请求示例**:


```javascript
{
	"entryDate": "",
	"id": 0,
	"idCardNumber": "",
	"isSeparation": 0,
	"name": "",
	"phoneNumber": "",
	"positionId": 0,
	"separationDate": "",
	"wage": 0
}
```


**请求参数**:


| 参数名称                   | 参数说明 | in   | 是否必须 | 数据类型          | schema |
| -------------------------- | -------- | ---- | -------- | ----------------- | ------ |
| staff                      | staff    | body | true     | Staff             | Staff  |
| &emsp;&emsp;entryDate      |          |      | false    | string(date-time) |        |
| &emsp;&emsp;id             |          |      | false    | integer(int32)    |        |
| &emsp;&emsp;idCardNumber   |          |      | false    | string            |        |
| &emsp;&emsp;isSeparation   |          |      | false    | integer(int32)    |        |
| &emsp;&emsp;name           |          |      | false    | string            |        |
| &emsp;&emsp;phoneNumber    |          |      | false    | string            |        |
| &emsp;&emsp;positionId     |          |      | false    | integer(int32)    |        |
| &emsp;&emsp;separationDate |          |      | false    | string(date-time) |        |
| &emsp;&emsp;wage           |          |      | false    | number(double)    |        |


**响应状态**:


| 状态码 | 说明         | schema |
| ------ | ------------ | ------ |
| 200    | OK           | Staff  |
| 201    | Created      |        |
| 401    | Unauthorized |        |
| 403    | Forbidden    |        |
| 404    | Not Found    |        |


**响应参数**:


| 参数名称       | 参数说明 | 类型              | schema            |
| -------------- | -------- | ----------------- | ----------------- |
| entryDate      |          | string(date-time) | string(date-time) |
| id             |          | integer(int32)    | integer(int32)    |
| idCardNumber   |          | string            |                   |
| isSeparation   |          | integer(int32)    | integer(int32)    |
| name           |          | string            |                   |
| phoneNumber    |          | string            |                   |
| positionId     |          | integer(int32)    | integer(int32)    |
| separationDate |          | string(date-time) | string(date-time) |
| wage           |          | number(double)    | number(double)    |


**响应示例**:
```javascript
[
	{
		"entryDate": "",
		"id": 0,
		"idCardNumber": "",
		"isSeparation": 0,
		"name": "",
		"phoneNumber": "",
		"positionId": 0,
		"separationDate": "",
		"wage": 0
	}
]
```


## 查询离职员工


**接口地址**:`/staff/queryResignedEmployees`


**请求方式**:`POST`


**请求数据类型**:`application/json`


**响应数据类型**:`application/json;charset=UTF-8`


**接口描述**:


**请求示例**:


```javascript
{
	"entryDate": "",
	"id": 0,
	"idCardNumber": "",
	"isSeparation": 0,
	"name": "",
	"phoneNumber": "",
	"positionId": 0,
	"separationDate": "",
	"wage": 0
}
```


**请求参数**:


| 参数名称                   | 参数说明 | in   | 是否必须 | 数据类型          | schema |
| -------------------------- | -------- | ---- | -------- | ----------------- | ------ |
| staff                      | staff    | body | true     | Staff             | Staff  |
| &emsp;&emsp;entryDate      |          |      | false    | string(date-time) |        |
| &emsp;&emsp;id             |          |      | false    | integer(int32)    |        |
| &emsp;&emsp;idCardNumber   |          |      | false    | string            |        |
| &emsp;&emsp;isSeparation   |          |      | false    | integer(int32)    |        |
| &emsp;&emsp;name           |          |      | false    | string            |        |
| &emsp;&emsp;phoneNumber    |          |      | false    | string            |        |
| &emsp;&emsp;positionId     |          |      | false    | integer(int32)    |        |
| &emsp;&emsp;separationDate |          |      | false    | string(date-time) |        |
| &emsp;&emsp;wage           |          |      | false    | number(double)    |        |


**响应状态**:


| 状态码 | 说明         | schema |
| ------ | ------------ | ------ |
| 200    | OK           | Staff  |
| 201    | Created      |        |
| 401    | Unauthorized |        |
| 403    | Forbidden    |        |
| 404    | Not Found    |        |


**响应参数**:


| 参数名称       | 参数说明 | 类型              | schema            |
| -------------- | -------- | ----------------- | ----------------- |
| entryDate      |          | string(date-time) | string(date-time) |
| id             |          | integer(int32)    | integer(int32)    |
| idCardNumber   |          | string            |                   |
| isSeparation   |          | integer(int32)    | integer(int32)    |
| name           |          | string            |                   |
| phoneNumber    |          | string            |                   |
| positionId     |          | integer(int32)    | integer(int32)    |
| separationDate |          | string(date-time) | string(date-time) |
| wage           |          | number(double)    | number(double)    |


**响应示例**:
```javascript
[
	{
		"entryDate": "",
		"id": 0,
		"idCardNumber": "",
		"isSeparation": 0,
		"name": "",
		"phoneNumber": "",
		"positionId": 0,
		"separationDate": "",
		"wage": 0
	}
]
```


## 通过ID查询单一员工


**接口地址**:`/staff/selectOne`


**请求方式**:`POST`


**请求数据类型**:`application/json`


**响应数据类型**:`application/json;charset=UTF-8`


**接口描述**:


**请求示例**:


```javascript
{
	"entryDate": "",
	"id": 0,
	"idCardNumber": "",
	"isSeparation": 0,
	"name": "",
	"phoneNumber": "",
	"positionId": 0,
	"separationDate": "",
	"wage": 0
}
```


**请求参数**:


| 参数名称                   | 参数说明 | in   | 是否必须 | 数据类型          | schema |
| -------------------------- | -------- | ---- | -------- | ----------------- | ------ |
| staff                      | staff    | body | true     | Staff             | Staff  |
| &emsp;&emsp;entryDate      |          |      | false    | string(date-time) |        |
| &emsp;&emsp;id             |          |      | false    | integer(int32)    |        |
| &emsp;&emsp;idCardNumber   |          |      | false    | string            |        |
| &emsp;&emsp;isSeparation   |          |      | false    | integer(int32)    |        |
| &emsp;&emsp;name           |          |      | false    | string            |        |
| &emsp;&emsp;phoneNumber    |          |      | false    | string            |        |
| &emsp;&emsp;positionId     |          |      | false    | integer(int32)    |        |
| &emsp;&emsp;separationDate |          |      | false    | string(date-time) |        |
| &emsp;&emsp;wage           |          |      | false    | number(double)    |        |


**响应状态**:


| 状态码 | 说明         | schema |
| ------ | ------------ | ------ |
| 200    | OK           | Staff  |
| 201    | Created      |        |
| 401    | Unauthorized |        |
| 403    | Forbidden    |        |
| 404    | Not Found    |        |


**响应参数**:


| 参数名称       | 参数说明 | 类型              | schema            |
| -------------- | -------- | ----------------- | ----------------- |
| entryDate      |          | string(date-time) | string(date-time) |
| id             |          | integer(int32)    | integer(int32)    |
| idCardNumber   |          | string            |                   |
| isSeparation   |          | integer(int32)    | integer(int32)    |
| name           |          | string            |                   |
| phoneNumber    |          | string            |                   |
| positionId     |          | integer(int32)    | integer(int32)    |
| separationDate |          | string(date-time) | string(date-time) |
| wage           |          | number(double)    | number(double)    |


**响应示例**:
```javascript
{
	"entryDate": "",
	"id": 0,
	"idCardNumber": "",
	"isSeparation": 0,
	"name": "",
	"phoneNumber": "",
	"positionId": 0,
	"separationDate": "",
	"wage": 0
}
```


## 员工更新信息


**接口地址**:`/staff/updateOne`


**请求方式**:`POST`


**请求数据类型**:`application/json`


**响应数据类型**:`application/json;charset=UTF-8`


**接口描述**:


**请求示例**:


```javascript
{
	"entryDate": "",
	"id": 0,
	"idCardNumber": "",
	"isSeparation": 0,
	"name": "",
	"phoneNumber": "",
	"positionId": 0,
	"separationDate": "",
	"wage": 0
}
```


**请求参数**:


| 参数名称                   | 参数说明 | in   | 是否必须 | 数据类型          | schema |
| -------------------------- | -------- | ---- | -------- | ----------------- | ------ |
| staff                      | staff    | body | true     | Staff             | Staff  |
| &emsp;&emsp;entryDate      |          |      | false    | string(date-time) |        |
| &emsp;&emsp;id             |          |      | false    | integer(int32)    |        |
| &emsp;&emsp;idCardNumber   |          |      | false    | string            |        |
| &emsp;&emsp;isSeparation   |          |      | false    | integer(int32)    |        |
| &emsp;&emsp;name           |          |      | false    | string            |        |
| &emsp;&emsp;phoneNumber    |          |      | false    | string            |        |
| &emsp;&emsp;positionId     |          |      | false    | integer(int32)    |        |
| &emsp;&emsp;separationDate |          |      | false    | string(date-time) |        |
| &emsp;&emsp;wage           |          |      | false    | number(double)    |        |


**响应状态**:


| 状态码 | 说明         | schema |
| ------ | ------------ | ------ |
| 200    | OK           | Staff  |
| 201    | Created      |        |
| 401    | Unauthorized |        |
| 403    | Forbidden    |        |
| 404    | Not Found    |        |


**响应参数**:


| 参数名称       | 参数说明 | 类型              | schema            |
| -------------- | -------- | ----------------- | ----------------- |
| entryDate      |          | string(date-time) | string(date-time) |
| id             |          | integer(int32)    | integer(int32)    |
| idCardNumber   |          | string            |                   |
| isSeparation   |          | integer(int32)    | integer(int32)    |
| name           |          | string            |                   |
| phoneNumber    |          | string            |                   |
| positionId     |          | integer(int32)    | integer(int32)    |
| separationDate |          | string(date-time) | string(date-time) |
| wage           |          | number(double)    | number(double)    |


**响应示例**:
```javascript
{
	"entryDate": "",
	"id": 0,
	"idCardNumber": "",
	"isSeparation": 0,
	"name": "",
	"phoneNumber": "",
	"positionId": 0,
	"separationDate": "",
	"wage": 0
}
```

# 职位管理


## 添加职位


**接口地址**:`/position/addPositionl`


**请求方式**:`POST`


**请求数据类型**:`application/json`


**响应数据类型**:`application/json;charset=UTF-8`


**接口描述**:


**请求示例**:


```javascript
{
	"descriptionPosition": "",
	"position": "",
	"positionid": 0
}
```


**请求参数**:


| 参数名称                        | 参数说明 | in   | 是否必须 | 数据类型       | schema   |
| ------------------------------- | -------- | ---- | -------- | -------------- | -------- |
| position                        | position | body | true     | Position       | Position |
| &emsp;&emsp;descriptionPosition |          |      | false    | string         |          |
| &emsp;&emsp;position            |          |      | false    | string         |          |
| &emsp;&emsp;positionid          |          |      | false    | integer(int32) |          |


**响应状态**:


| 状态码 | 说明         | schema   |
| ------ | ------------ | -------- |
| 200    | OK           | Position |
| 201    | Created      |          |
| 401    | Unauthorized |          |
| 403    | Forbidden    |          |
| 404    | Not Found    |          |


**响应参数**:


| 参数名称            | 参数说明 | 类型           | schema         |
| ------------------- | -------- | -------------- | -------------- |
| descriptionPosition |          | string         |                |
| position            |          | string         |                |
| positionid          |          | integer(int32) | integer(int32) |


**响应示例**:
```javascript
{
	"descriptionPosition": "",
	"position": "",
	"positionid": 0
}
```


## 删除职位


**接口地址**:`/position/deletePositionl`


**请求方式**:`POST`


**请求数据类型**:`application/json`


**响应数据类型**:`application/json;charset=UTF-8`


**接口描述**:


**请求示例**:


```javascript
{
	"descriptionPosition": "",
	"position": "",
	"positionid": 0
}
```


**请求参数**:


| 参数名称                        | 参数说明 | in   | 是否必须 | 数据类型       | schema   |
| ------------------------------- | -------- | ---- | -------- | -------------- | -------- |
| position                        | position | body | true     | Position       | Position |
| &emsp;&emsp;descriptionPosition |          |      | false    | string         |          |
| &emsp;&emsp;position            |          |      | false    | string         |          |
| &emsp;&emsp;positionid          |          |      | false    | integer(int32) |          |


**响应状态**:


| 状态码 | 说明         | schema |
| ------ | ------------ | ------ |
| 200    | OK           |        |
| 201    | Created      |        |
| 401    | Unauthorized |        |
| 403    | Forbidden    |        |
| 404    | Not Found    |        |


**响应参数**:


暂无


**响应示例**:
```javascript

```


## 查询所有职位


**接口地址**:`/position/selectAll`


**请求方式**:`POST`


**请求数据类型**:`application/json`


**响应数据类型**:`application/json;charset=UTF-8`


**接口描述**:


**请求参数**:


暂无


**响应状态**:


| 状态码 | 说明         | schema   |
| ------ | ------------ | -------- |
| 200    | OK           | Position |
| 201    | Created      |          |
| 401    | Unauthorized |          |
| 403    | Forbidden    |          |
| 404    | Not Found    |          |


**响应参数**:


| 参数名称            | 参数说明 | 类型           | schema         |
| ------------------- | -------- | -------------- | -------------- |
| descriptionPosition |          | string         |                |
| position            |          | string         |                |
| positionid          |          | integer(int32) | integer(int32) |


**响应示例**:
```javascript
[
	{
		"descriptionPosition": "",
		"position": "",
		"positionid": 0
	}
]
```


## 职位查询


**接口地址**:`/position/selectOne`


**请求方式**:`POST`


**请求数据类型**:`application/json`


**响应数据类型**:`application/json;charset=UTF-8`


**接口描述**:


**请求示例**:


```javascript
{
	"descriptionPosition": "",
	"position": "",
	"positionid": 0
}
```


**请求参数**:


| 参数名称                        | 参数说明 | in   | 是否必须 | 数据类型       | schema   |
| ------------------------------- | -------- | ---- | -------- | -------------- | -------- |
| position                        | position | body | true     | Position       | Position |
| &emsp;&emsp;descriptionPosition |          |      | false    | string         |          |
| &emsp;&emsp;position            |          |      | false    | string         |          |
| &emsp;&emsp;positionid          |          |      | false    | integer(int32) |          |


**响应状态**:


| 状态码 | 说明         | schema   |
| ------ | ------------ | -------- |
| 200    | OK           | Position |
| 201    | Created      |          |
| 401    | Unauthorized |          |
| 403    | Forbidden    |          |
| 404    | Not Found    |          |


**响应参数**:


| 参数名称            | 参数说明 | 类型           | schema         |
| ------------------- | -------- | -------------- | -------------- |
| descriptionPosition |          | string         |                |
| position            |          | string         |                |
| positionid          |          | integer(int32) | integer(int32) |


**响应示例**:
```javascript
{
	"descriptionPosition": "",
	"position": "",
	"positionid": 0
}
```


## 更新职位


**接口地址**:`/position/updatePositionl`


**请求方式**:`POST`


**请求数据类型**:`application/json`


**响应数据类型**:`application/json;charset=UTF-8`


**接口描述**:


**请求示例**:


```javascript
{
	"descriptionPosition": "",
	"position": "",
	"positionid": 0
}
```


**请求参数**:


| 参数名称                        | 参数说明 | in   | 是否必须 | 数据类型       | schema   |
| ------------------------------- | -------- | ---- | -------- | -------------- | -------- |
| position                        | position | body | true     | Position       | Position |
| &emsp;&emsp;descriptionPosition |          |      | false    | string         |          |
| &emsp;&emsp;position            |          |      | false    | string         |          |
| &emsp;&emsp;positionid          |          |      | false    | integer(int32) |          |


**响应状态**:


| 状态码 | 说明         | schema   |
| ------ | ------------ | -------- |
| 200    | OK           | Position |
| 201    | Created      |          |
| 401    | Unauthorized |          |
| 403    | Forbidden    |          |
| 404    | Not Found    |          |


**响应参数**:


| 参数名称            | 参数说明 | 类型           | schema         |
| ------------------- | -------- | -------------- | -------------- |
| descriptionPosition |          | string         |                |
| position            |          | string         |                |
| positionid          |          | integer(int32) | integer(int32) |


**响应示例**:
```javascript
{
	"descriptionPosition": "",
	"position": "",
	"positionid": 0
}
```

# 财务数据管理


## 添加财务数据


**接口地址**:`/finance/addOne`


**请求方式**:`POST`


**请求数据类型**:`application/json`


**响应数据类型**:`application/json;charset=UTF-8`


**接口描述**:


**请求示例**:


```javascript
{
	"id": 0,
	"incomeAndExpenditureType": 0,
	"note": "",
	"number": 0,
	"why": ""
}
```


**请求参数**:


| 参数名称                             | 参数说明 | in   | 是否必须 | 数据类型       | schema  |
| ------------------------------------ | -------- | ---- | -------- | -------------- | ------- |
| finance                              | finance  | body | true     | Finance        | Finance |
| &emsp;&emsp;id                       |          |      | false    | integer(int32) |         |
| &emsp;&emsp;incomeAndExpenditureType |          |      | false    | integer(int32) |         |
| &emsp;&emsp;note                     |          |      | false    | string         |         |
| &emsp;&emsp;number                   |          |      | false    | number(double) |         |
| &emsp;&emsp;why                      |          |      | false    | string         |         |


**响应状态**:


| 状态码 | 说明         | schema  |
| ------ | ------------ | ------- |
| 200    | OK           | Finance |
| 201    | Created      |         |
| 401    | Unauthorized |         |
| 403    | Forbidden    |         |
| 404    | Not Found    |         |


**响应参数**:


| 参数名称                 | 参数说明 | 类型           | schema         |
| ------------------------ | -------- | -------------- | -------------- |
| id                       |          | integer(int32) | integer(int32) |
| incomeAndExpenditureType |          | integer(int32) | integer(int32) |
| note                     |          | string         |                |
| number                   |          | number(double) | number(double) |
| why                      |          | string         |                |


**响应示例**:
```javascript
{
	"id": 0,
	"incomeAndExpenditureType": 0,
	"note": "",
	"number": 0,
	"why": ""
}
```


## 通过ID删除财务数据信息


**接口地址**:`/finance/deleteOne`


**请求方式**:`POST`


**请求数据类型**:`application/json`


**响应数据类型**:`application/json;charset=UTF-8`


**接口描述**:


**请求示例**:


```javascript
{
	"id": 0,
	"incomeAndExpenditureType": 0,
	"note": "",
	"number": 0,
	"why": ""
}
```


**请求参数**:


| 参数名称                             | 参数说明 | in   | 是否必须 | 数据类型       | schema  |
| ------------------------------------ | -------- | ---- | -------- | -------------- | ------- |
| finance                              | finance  | body | true     | Finance        | Finance |
| &emsp;&emsp;id                       |          |      | false    | integer(int32) |         |
| &emsp;&emsp;incomeAndExpenditureType |          |      | false    | integer(int32) |         |
| &emsp;&emsp;note                     |          |      | false    | string         |         |
| &emsp;&emsp;number                   |          |      | false    | number(double) |         |
| &emsp;&emsp;why                      |          |      | false    | string         |         |


**响应状态**:


| 状态码 | 说明         | schema |
| ------ | ------------ | ------ |
| 200    | OK           |        |
| 201    | Created      |        |
| 401    | Unauthorized |        |
| 403    | Forbidden    |        |
| 404    | Not Found    |        |


**响应参数**:


暂无


**响应示例**:
```javascript

```


## 查询全部财务数据


**接口地址**:`/finance/queryAll`


**请求方式**:`POST`


**请求数据类型**:`application/json`


**响应数据类型**:`application/json;charset=UTF-8`


**接口描述**:


**请求参数**:


暂无


**响应状态**:


| 状态码 | 说明         | schema  |
| ------ | ------------ | ------- |
| 200    | OK           | Finance |
| 201    | Created      |         |
| 401    | Unauthorized |         |
| 403    | Forbidden    |         |
| 404    | Not Found    |         |


**响应参数**:


| 参数名称                 | 参数说明 | 类型           | schema         |
| ------------------------ | -------- | -------------- | -------------- |
| id                       |          | integer(int32) | integer(int32) |
| incomeAndExpenditureType |          | integer(int32) | integer(int32) |
| note                     |          | string         |                |
| number                   |          | number(double) | number(double) |
| why                      |          | string         |                |


**响应示例**:
```javascript
[
	{
		"id": 0,
		"incomeAndExpenditureType": 0,
		"note": "",
		"number": 0,
		"why": ""
	}
]
```


## 通过ID查询单一财务数据


**接口地址**:`/finance/selectOne`


**请求方式**:`POST`


**请求数据类型**:`application/json`


**响应数据类型**:`application/json;charset=UTF-8`


**接口描述**:


**请求示例**:


```javascript
{
	"id": 0,
	"incomeAndExpenditureType": 0,
	"note": "",
	"number": 0,
	"why": ""
}
```


**请求参数**:


| 参数名称                             | 参数说明 | in   | 是否必须 | 数据类型       | schema  |
| ------------------------------------ | -------- | ---- | -------- | -------------- | ------- |
| finance                              | finance  | body | true     | Finance        | Finance |
| &emsp;&emsp;id                       |          |      | false    | integer(int32) |         |
| &emsp;&emsp;incomeAndExpenditureType |          |      | false    | integer(int32) |         |
| &emsp;&emsp;note                     |          |      | false    | string         |         |
| &emsp;&emsp;number                   |          |      | false    | number(double) |         |
| &emsp;&emsp;why                      |          |      | false    | string         |         |


**响应状态**:


| 状态码 | 说明         | schema  |
| ------ | ------------ | ------- |
| 200    | OK           | Finance |
| 201    | Created      |         |
| 401    | Unauthorized |         |
| 403    | Forbidden    |         |
| 404    | Not Found    |         |


**响应参数**:


| 参数名称                 | 参数说明 | 类型           | schema         |
| ------------------------ | -------- | -------------- | -------------- |
| id                       |          | integer(int32) | integer(int32) |
| incomeAndExpenditureType |          | integer(int32) | integer(int32) |
| note                     |          | string         |                |
| number                   |          | number(double) | number(double) |
| why                      |          | string         |                |


**响应示例**:
```javascript
{
	"id": 0,
	"incomeAndExpenditureType": 0,
	"note": "",
	"number": 0,
	"why": ""
}
```


## 更新财务数据信息


**接口地址**:`/finance/updateOne`


**请求方式**:`POST`


**请求数据类型**:`application/json`


**响应数据类型**:`application/json;charset=UTF-8`


**接口描述**:


**请求示例**:


```javascript
{
	"id": 0,
	"incomeAndExpenditureType": 0,
	"note": "",
	"number": 0,
	"why": ""
}
```


**请求参数**:


| 参数名称                             | 参数说明 | in   | 是否必须 | 数据类型       | schema  |
| ------------------------------------ | -------- | ---- | -------- | -------------- | ------- |
| finance                              | finance  | body | true     | Finance        | Finance |
| &emsp;&emsp;id                       |          |      | false    | integer(int32) |         |
| &emsp;&emsp;incomeAndExpenditureType |          |      | false    | integer(int32) |         |
| &emsp;&emsp;note                     |          |      | false    | string         |         |
| &emsp;&emsp;number                   |          |      | false    | number(double) |         |
| &emsp;&emsp;why                      |          |      | false    | string         |         |


**响应状态**:


| 状态码 | 说明         | schema  |
| ------ | ------------ | ------- |
| 200    | OK           | Finance |
| 201    | Created      |         |
| 401    | Unauthorized |         |
| 403    | Forbidden    |         |
| 404    | Not Found    |         |


**响应参数**:


| 参数名称                 | 参数说明 | 类型           | schema         |
| ------------------------ | -------- | -------------- | -------------- |
| id                       |          | integer(int32) | integer(int32) |
| incomeAndExpenditureType |          | integer(int32) | integer(int32) |
| note                     |          | string         |                |
| number                   |          | number(double) | number(double) |
| why                      |          | string         |                |


**响应示例**:
```javascript
{
	"id": 0,
	"incomeAndExpenditureType": 0,
	"note": "",
	"number": 0,
	"why": ""
}
```