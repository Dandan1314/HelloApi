# searchIp IP查询相关API

## 1.获取请求者的IP
### 1.1 功能描述
获取请求者的IP
### 1.2 请求说明
> 请求方式：GET
>
> 请求URL ：[/searchIp/myIp](#) 

### 1.3 请求参数
### 1.4 返回结果
```json  
{
    "int": 2130706433,
    "ip": "127.0.0.1",
    "Country": "本机地址",
    "Area": ""
}
```
### 1.5 返回参数
| 字段    | 字段类型 | 字段说明     |
| ------- | -------- | ------------ |
| int     | Number   | IP的整形数据 |
| ip      | String   | 请求者的IP   |
| Country | String   | 国家信息     |
| Area    | String   | 地区信息     |

---

## 2.查询IP信息
### 2.1 功能描述
查询指定IP信息
### 2.2 请求说明
> 请求方式：GET
>
> 请求URL ：[/searchIp/search/:ip](#) 

### 2.3 请求参数
| 字段 | 字段类型 | 字段说明       |
| ---- | -------- | -------------- |
| ip   | String   | 待查询的IP信息 |
### 2.4 返回结果
```json  
"IPV4": {
    "int": 2130706433,
    "ip": "127.0.0.1",
    "Country": "本机地址",
    "Area": ""
}
"IPV6": {
    "ip": {
        "start": "::",
        "end": "64:ff9a:ffff:ffff::"
    },
    "Country": "IANA保留地址",
    "Area": "IANA保留地址 "
}
```
### 2.5 返回参数
| 字段    | 字段类型 | 字段说明                           |
| ------- | -------- | ---------------------------------- |
| int     | Number   | IP的整形数据                       |
| ip      | String   | 请求者的IP(ipv6时返回开始和结束IP) |
| Country | String   | 国家信息                           |
| Area    | String   | 地区信息                           |

---