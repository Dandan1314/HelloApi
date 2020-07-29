# TangPoetry 唐诗查询相关API

**API地址 i.needapi.net， 支持HTTP和HTTPS请求**

## 1.查询唐诗信息
### 1.1 功能描述
查询唐诗信息
### 1.2 请求说明
> 请求方式：GET
>
> 请求URL ：[/TangPoetry/getData/:poet/:name/:page/:limit](#) 

### 1.3 请求参数
| 字段  | 字段类型 | 字段说明 |
| ----- | -------- | -------- |
| poet  | String   | 诗人     |
| name  | String   | 诗名     |
| page  | String   | 页码     |
| limit | String   | 每页数量 |
### 1.4 返回结果
```json  
{
    "page": 1,
    "countAll": 1,
    "pageAll": 1,
    "result": [
        {
            "poet": "李白",
            "name": "静夜思",
            "content": "床前明月光，疑是地上霜。举头望明月，低头思故乡。"
        }
    ]
}
```
### 1.5 返回参数
| 字段     | 字段类型 | 字段说明 |
| -------- | -------- | -------- |
| page     | Number   | 当前页   |
| countAll | Number   | 总条数   |
| pageAll  | Number   | 总页数   |
| result   | Array    | 唐诗信息 |

---