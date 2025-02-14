# modifyVpc


## 描述
修改私有网络接口

## 请求方式
PATCH

## 请求地址
https://vpc.jdcloud-api.com/v1/regions/{regionId}/vpcs/{vpcId}

|名称|类型|是否必需|默认值|描述|
|---|---|---|---|---|
|**regionId**|String|True| |Region ID|
|**vpcId**|String|True| |Vpc ID|

## 请求参数
|名称|类型|是否必需|默认值|描述|
|---|---|---|---|---|
|**vpcName**|String|False| |私有网络名称,只允许输入中文、数字、大小写字母、英文下划线“_”及中划线“-”，不允许为空且不超过32字符。|
|**description**|String|False| |vpc描述，允许输入UTF-8编码下的全部字符，不超过256字符。|


## 返回参数
|名称|类型|描述|
|---|---|---|
|**requestId**|String|请求ID|


## 返回码
|返回码|描述|
|---|---|
|**200**|OK|
|**400**|Invalid parameter|
|**404**|Not found|
|**409**|Parameter conflict|
|**500**|Internal server error|
|**503**|Service unavailable|

## 请求示例
调用方法、签名算法及公共请求参数请参考[京东云OpenAPI公共说明](https://docs.jdcloud.com/common-declaration/api/introduction)。


PATCH
```
 /v1/regions/cn-north-1/vpcs/vpc-s5e3eqf9pk
      {
          "vpcName": "cheney_test_modify"
      }

```

## 返回示例
```
{
    "requestId": "411e3da7-021f-43f9-a389-7e13ec706cc7"
}
```
