# 获取个人资料

https://api.bilibili.com/x/member/web/account

*请求方式: GET*

参数：
web_location
333.33


Referer:
https://account.bilibili.com/

User-Agent:
Mozilla/5.0 (Windows NT 10.0; Win64; x64) AppleWebKit/537.36 (KHTML, like Gecko) Chrome/148.0.0.0 Safari/537.36 Edg/148.0.0.0



<details>
<summary>查看响应示例：</summary>

```json
{
    "code": 0,
    "message": "OK",
    "ttl": 1,
    "data": {
        "mid": 3494361276877525,
        "uname": "Wormwaker",
        "userid": "bili_99486075325",
        "sign": "致力于打造独特的 Windows 视觉客户。\n爱发電: wormwaker697\n代表作 JackalClient\n测试文本",
        "birthday": "2005-03-05",
        "sex": "男",
        "nick_free": false,
        "rank": "正式会员",
        "handle": "",
        "user_field_settings": [
            {
                "field": "handle",
                "visible": false,
                "editable": false,
                "rule_message": ""
            }
        ]
    }
}
```
</details>

# 修改个人资料

https://api.bilibili.com/x/member/web/update
*请求方式: POST*

Referer: 
https://account.bilibili.com/

User-Agent:
Mozilla/5.0 (Windows NT 10.0; Win64; x64) AppleWebKit/537.36 (KHTML, like Gecko) Chrome/148.0.0.0 Safari/537.36 Edg/148.0.0.0

参数：

uname
你的用户名。

usersign
你的个性签名。

sex
男

birthday
YYYY-MM-DD格式的生日

csrf
bili_jct, 存在于Cookies中

<details>
<summary>查看响应示例：</summary>

```json
{"code":0,"message":"OK","ttl":1,"data":null}
```
</details>