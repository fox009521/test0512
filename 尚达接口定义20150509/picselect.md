# 图片查询接口
|相关信息|内容|
|--|--|
|访问类型|POST|
|访问地址|/common/picselect|

###请求参数

|参数名称|是否必填|类型|说明|示例数据|
|--|--|--|--|--|--|
|gid|否|字符串|图片GID||
|type|否|字符串|图片类型（thumb-缩略图/original-原图/HD-高清图）||

###请求示例
<pre>
<code>
{

    {
        "gid":"图片gid，
        "type":"图片类型（thumb-缩略图/original-原图/HD-高清图）"
    }

}
</code>
</pre>

###返回结果示例

<pre>
<code>
    {
       "code": 1,
       "message": "新增成功",
       "result_data":
       {
            "url":"图片地址"
       }
    }



</code>
</pre>
