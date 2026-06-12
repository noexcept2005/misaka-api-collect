# 查询直播间封禁状态

> https://api.live.bilibili.com/room/v1/Room/getBannedInfo
*请求方式: GET*

参数：

roomid
房间号


<details>
<summary>查看响应示例：</summary>
已封禁：
```json
{"code":0,"msg":"ok","message":"ok","data":{"lock_till":1780847819}}
```

未封禁：
```json
{"code":0,"msg":"ok","message":"ok","data":{"lock_till":0}}
```
</details>


# 查询账号直播间诊断

> https://api.live.bilibili.com/xlive/web-ucenter/v1/anchorViolationsRecord/GetAccountDiagnostics
*请求方式: GET*

需要 Cookies

<details>
<summary>查看被封禁响应示例：</summary>
```json
{
    "code": 0,
    "message": "0",
    "ttl": 1,
    "data": {
        "room_ban_status": 1,
        "room_ban_recover_time": 1780847819,
        "live_permission_status": 0,
        "live_permission_recover_time": 0,
        "cover_permission_status": 0,
        "cover_permission_recover_time": 0,
        "traffic_permission_status": 0,
        "traffic_permission_recover_time": 0,
        "head_img": "https://i1.hdslb.com/bfs/face/xxxxxxxxxxxxxxxxxxxxxxxxxxxxxxx.jpg"
    }
}
```

</details>

# 获取直播间违规记录

GET

> https://api.live.bilibili.com/xlive/web-ucenter/v1/anchorViolationsRecord/GetAnchorViolationsRecord

需要 Cookies

参数：

page
1

page_size
6

<details>
<summary>查看响应示例：</summary>
```json
{
    "code": 0,
    "message": "0",
    "ttl": 1,
    "data": {
        "page_size": 6,
        "page": 1,
        "count": 8,
        "violations_record": [
            {
                "id": 14704843,
                "violations_reason": "违反直播规范",
                "penalty_reason": "封禁1.00天",
                "break_time": "2026年6月6日23时57分",
                "violation_timestamp": 1780761420
            },
            {
                "id": 14704771,
                "violations_reason": "检测发现您直播间因涉及违规内容已被切断直播流，后续若核查出更严重违规，平台将依规追加处罚",
                "penalty_reason": "禁止开播60秒",
                "break_time": "2026年6月6日23时53分",
                "violation_timestamp": 1780761180
            },
            {
                "id": 14452510,
                "violations_reason": "直播中禁止展示、宣传、推广游戏私服或游戏外挂",
                "penalty_reason": "警告",
                "break_time": "2026年5月25日20时7分",
                "violation_timestamp": 1779710820
            },
            {
                "id": 13695230,
                "violations_reason": "直播中禁止展示、宣传、推广游戏私服或游戏外挂",
                "penalty_reason": "禁止开播60秒",
                "break_time": "2026年4月18日16时54分",
                "violation_timestamp": 1776502440
            },
            {
                "id": 13695082,
                "violations_reason": "直播中禁止展示、宣传、推广游戏私服或游戏外挂",
                "penalty_reason": "警告",
                "break_time": "2026年4月18日16时47分",
                "violation_timestamp": 1776502020
            },
            {
                "id": 12844185,
                "violations_reason": "请勿在直播间展示该游戏服务器ip",
                "penalty_reason": "禁止开播60秒",
                "break_time": "2026年3月12日17时24分",
                "violation_timestamp": 1773307440
            }
        ]
    }
}
```

</details>
