# 标准命名

> 制定统一命名风格，减少前后端交互沟通

## 资讯文章类

|中文|英文|类型|
|:------|:----|:----|
|标题|title|string|
|简介|summary|string|
|描述|description|string|
|正文|content|string|
|作者|author|string|
|头像|avatar|string|
|发布日期|publish_at|string|
|发布状态|status|string|
|编辑|editor|string|
|标签|tags|array(string)|
|一级标签|first_tags|array(string)|
|二级标签|second_tags|array(string)|
|三级标签|third_tags|array(string)|
|图片、头图|image|string|
|来源|origin|string|
|来源链接|origin_url|string|

## 报告

|中文|英文|类型|
|:------|:----|:----|
|标题|title|string|
|简介|summary|string|
|状态|status|string|
|图片|images|array(string)|
|PDF链接|pdf_url|array(string)|

## 用户类

|中文|英文|类型|
|:------|:----|:----|
|昵称|nickname|string|
|真实姓名|realname|string|
|年龄|age|number|
|性别|gender|string|
|生日|birthday|string|
|头像|avatar|string|
|邮箱|email|string|
|电话|mobile|string|
|职业|job|string|
|公司|company|string|

## 标签、分类

|中文|英文|类型|
|:------|:----|:----|
|名称|name|string|
|类型|category|string|

## 栏目

|中文|英文|类型|
|:------|:----|:----|
|名称|name|string|
|位置|position|number|
|描述|description|string|

## 数量

|中文|英文|类型|
|:------|:----|:----|
|粉丝数|fans|number|
|收藏数|collects|number|
|喜欢数、点赞数|likes|number|
|笔记数、内容数|contents|number|
|收藏数|collects|number|
|转发数|forwards|number|
|阅读数|reads|number|

## 第三方信息

|中文|英文|类型|
|:------|:----|:----|
|抖音openid|douyin_open_id|string|
|微信openid|wechat_open_id|string|
|微信unionid|wechat_union_id|string|

## 认证

|中文|英文|类型|
|:------|:----|:----|
|Token(参数中)|auth_token|string|
|Token(headers中)|Authorization|string|

## 地区

|中文|英文|类型|
|:------|:----|:----|
|国家|country|string|
|省份|province|string|
|市|city|string|
|区县|district|string|

## 地址

|中文|英文|类型|
|:------|:----|:----|
|联系人|contract_name|string|
|联系电话|contract_mobile|string|
|详细地址|detail|string|
|是否默认|is_default|boolean|

## 订单

|中文|英文|类型|
|:------|:----|:----|
|状态|status|string|
|订单号|code|string|
|金额|amount|number|
|评价|review|string|
|支付平台|platform|string|

## 轮播图

|中文|英文|类型|
|:------|:----|:----|
|标题|title|string|
|图片|image|string|
|类型|category（图片、视频）|string|
|链接|link|string|
|宽度|width|number|
|长度|height|number|
|版权|copyright|string|

## 商品

|中文|英文|类型|
|:------|:----|:----|
|名称|name|string|
|图片|image|string|
|原价|origin_amount|number|
|现价|amount|number|
|库存|stocks|number|
|销量|sales|number|
|状态|status|string|

## 系统消息

|中文|英文|类型|
|:------|:----|:----|
|内容|content|string|
|是否已读|is_read|boolean|
|类型|category|string|

## 记录

|中文|英文|类型|
|:------|:----|:----|
|内容|content|string|