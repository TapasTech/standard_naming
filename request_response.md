# 请求和返回规范

## Request

公共params

```json
{
  "page": 1,
  "per": 10
}
```

body

```json
{
  "name": "name"
}
```

## Response

### 单条

body

> code 2xx

```json
{
  "data": {}
}
```

### 多条

body

> code 2xx

```json
{
  "data": [],
  "meta": {
    "current_page": 1,
    "total_pages": 1,
    "next_page": 1,
    "total_count": 1,
    "per": 1
  }
}
```

## 错误返回

body

> code 4xx

```json
{
  "message": "你没权限"
}
