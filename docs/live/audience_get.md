## 查询直播间观众

> https://api.live.bilibili.com/xlive/general-interface/v1/rank/queryContributionRank

*请求方式: GET*

需要 WBI 鉴权。

参数：

ruid
主播用户UID

room_id
房间号

page
1

page_size
100

type
online_rank

switch
contribution_rank

platform
web

web_location
444.8

w_rid
略 (WBI)

wts
略 (WBI)

<details>
<summary>查看响应示例：</summary>

```json
{
    "code": 0,
    "message": "0",
    "ttl": 1,
    "data": {
        "count": 5,
        "item": [
            {
                "uid": 3494361276877525,
                "name": "Wormwaker",
                "face": "https://i1.hdslb.com/bfs/face/44766ba473ac5e3234fc5b78c1f59981eab80192.jpg",
                "rank": 1,
                "score": 1,
                "medal_info": {
                    "guard_level": 0,
                    "medal_color_start": 1725515,
                    "medal_color_end": 5414290,
                    "medal_color_border": 1725515,
                    "medal_name": "Intave",
                    "level": 21,
                    "target_id": 3494361276877525,
                    "is_light": 1
                },
                "guard_level": 0,
                "wealth_level": 6,
                "is_mystery": false,
                "uinfo": {
                    "uid": 3494361276877525,
                    "base": {
                        "name": "Wormwaker",
                        "face": "https://i1.hdslb.com/bfs/face/44766ba473ac5e3234fc5b78c1f59981eab80192.jpg",
                        "name_color": 0,
                        "is_mystery": false,
                        "risk_ctrl_info": {
                            "name": "Wormwaker",
                            "face": "https://i1.hdslb.com/bfs/face/44766ba473ac5e3234fc5b78c1f59981eab80192.jpg"
                        },
                        "origin_info": {
                            "name": "Wormwaker",
                            "face": "https://i1.hdslb.com/bfs/face/44766ba473ac5e3234fc5b78c1f59981eab80192.jpg"
                        },
                        "official_info": {
                            "role": 0,
                            "title": "",
                            "desc": "",
                            "type": -1
                        },
                        "name_color_str": ""
                    },
                    "medal": {
                        "name": "Intave",
                        "level": 21,
                        "color_start": 1725515,
                        "color_end": 5414290,
                        "color_border": 1725515,
                        "color": 1725515,
                        "id": 0,
                        "typ": 0,
                        "is_light": 1,
                        "ruid": 3494361276877525,
                        "guard_level": 0,
                        "score": 2768,
                        "guard_icon": "",
                        "honor_icon": "",
                        "v2_medal_color_start": "#3FB4F699",
                        "v2_medal_color_end": "#3FB4F699",
                        "v2_medal_color_border": "#3FB4F699",
                        "v2_medal_color_text": "#FFFFFF",
                        "v2_medal_color_level": "#3FB4F6E6",
                        "user_receive_count": 0
                    },
                    "wealth": {
                        "level": 6,
                        "dm_icon_key": ""
                    },
                    "title": {
                        "old_title_css_id": "",
                        "title_css_id": ""
                    },
                    "guard": {
                        "level": 0,
                        "expired_str": ""
                    },
                    "uhead_frame": null,
                    "guard_leader": null
                },
                "icon_show": false
            },
            {
                "uid": 3546612248873545,
                "name": "琅人TV",
                "face": "https://i1.hdslb.com/bfs/face/3fb7dca6d4b2221e242e4f83e82ca6cda24f23b6.jpg",
                "rank": 2,
                "score": 0,
                "medal_info": null,
                "guard_level": 0,
                "wealth_level": 0,
                "is_mystery": false,
                "uinfo": {
                    "uid": 3546612248873545,
                    "base": {
                        "name": "琅人TV",
                        "face": "https://i1.hdslb.com/bfs/face/3fb7dca6d4b2221e242e4f83e82ca6cda24f23b6.jpg",
                        "name_color": 0,
                        "is_mystery": false,
                        "risk_ctrl_info": {
                            "name": "琅人TV",
                            "face": "https://i1.hdslb.com/bfs/face/3fb7dca6d4b2221e242e4f83e82ca6cda24f23b6.jpg"
                        },
                        "origin_info": {
                            "name": "琅人TV",
                            "face": "https://i1.hdslb.com/bfs/face/3fb7dca6d4b2221e242e4f83e82ca6cda24f23b6.jpg"
                        },
                        "official_info": {
                            "role": 0,
                            "title": "",
                            "desc": "",
                            "type": -1
                        },
                        "name_color_str": ""
                    },
                    "medal": null,
                    "wealth": {
                        "level": 0,
                        "dm_icon_key": ""
                    },
                    "title": {
                        "old_title_css_id": "",
                        "title_css_id": ""
                    },
                    "guard": {
                        "level": 0,
                        "expired_str": ""
                    },
                    "uhead_frame": null,
                    "guard_leader": null
                },
                "icon_show": false
            },
            {
                "uid": 1270641296,
                "name": "涟幽Alex",
                "face": "https://i2.hdslb.com/bfs/face/e5e099e8fd97351e20026dab5e3529701a579e88.jpg",
                "rank": 3,
                "score": 0,
                "medal_info": {
                    "guard_level": 0,
                    "medal_color_start": 12632256,
                    "medal_color_end": 12632256,
                    "medal_color_border": 12632256,
                    "medal_name": "Intave",
                    "level": 21,
                    "target_id": 3494361276877525,
                    "is_light": 0
                },
                "guard_level": 0,
                "wealth_level": 4,
                "is_mystery": false,
                "uinfo": {
                    "uid": 1270641296,
                    "base": {
                        "name": "涟幽Alex",
                        "face": "https://i2.hdslb.com/bfs/face/e5e099e8fd97351e20026dab5e3529701a579e88.jpg",
                        "name_color": 0,
                        "is_mystery": false,
                        "risk_ctrl_info": {
                            "name": "涟幽Alex",
                            "face": "https://i2.hdslb.com/bfs/face/e5e099e8fd97351e20026dab5e3529701a579e88.jpg"
                        },
                        "origin_info": {
                            "name": "涟幽Alex",
                            "face": "https://i2.hdslb.com/bfs/face/e5e099e8fd97351e20026dab5e3529701a579e88.jpg"
                        },
                        "official_info": {
                            "role": 0,
                            "title": "",
                            "desc": "",
                            "type": -1
                        },
                        "name_color_str": ""
                    },
                    "medal": {
                        "name": "Intave",
                        "level": 21,
                        "color_start": 12632256,
                        "color_end": 12632256,
                        "color_border": 12632256,
                        "color": 1725515,
                        "id": 0,
                        "typ": 0,
                        "is_light": 0,
                        "ruid": 3494361276877525,
                        "guard_level": 0,
                        "score": 2140,
                        "guard_icon": "",
                        "honor_icon": "",
                        "v2_medal_color_start": "#919298CC",
                        "v2_medal_color_end": "#919298CC",
                        "v2_medal_color_border": "#919298CC",
                        "v2_medal_color_text": "#FFFFFF",
                        "v2_medal_color_level": "#919298E6",
                        "user_receive_count": 0
                    },
                    "wealth": {
                        "level": 4,
                        "dm_icon_key": ""
                    },
                    "title": {
                        "old_title_css_id": "",
                        "title_css_id": ""
                    },
                    "guard": {
                        "level": 0,
                        "expired_str": ""
                    },
                    "uhead_frame": null,
                    "guard_leader": null
                },
                "icon_show": false
            },
            {
                "uid": 1598523129,
                "name": "ZspecialfE",
                "face": "https://i0.hdslb.com/bfs/face/09e340bb25e713fd549049342805f9abce65e5b7.jpg",
                "rank": 4,
                "score": 0,
                "medal_info": null,
                "guard_level": 0,
                "wealth_level": 0,
                "is_mystery": false,
                "uinfo": {
                    "uid": 1598523129,
                    "base": {
                        "name": "ZspecialfE",
                        "face": "https://i0.hdslb.com/bfs/face/09e340bb25e713fd549049342805f9abce65e5b7.jpg",
                        "name_color": 0,
                        "is_mystery": false,
                        "risk_ctrl_info": {
                            "name": "ZspecialfE",
                            "face": "https://i0.hdslb.com/bfs/face/09e340bb25e713fd549049342805f9abce65e5b7.jpg"
                        },
                        "origin_info": {
                            "name": "ZspecialfE",
                            "face": "https://i0.hdslb.com/bfs/face/09e340bb25e713fd549049342805f9abce65e5b7.jpg"
                        },
                        "official_info": {
                            "role": 0,
                            "title": "",
                            "desc": "",
                            "type": -1
                        },
                        "name_color_str": ""
                    },
                    "medal": null,
                    "wealth": {
                        "level": 0,
                        "dm_icon_key": ""
                    },
                    "title": {
                        "old_title_css_id": "",
                        "title_css_id": ""
                    },
                    "guard": {
                        "level": 0,
                        "expired_str": ""
                    },
                    "uhead_frame": null,
                    "guard_leader": null
                },
                "icon_show": false
            },
            {
                "uid": 3461571525216391,
                "name": "蛋糕11368",
                "face": "https://i1.hdslb.com/bfs/face/3d78313514bde5f4fdb1a563888b3a535c9531ae.jpg",
                "rank": 5,
                "score": 0,
                "medal_info": null,
                "guard_level": 0,
                "wealth_level": 2,
                "is_mystery": false,
                "uinfo": {
                    "uid": 3461571525216391,
                    "base": {
                        "name": "蛋糕11368",
                        "face": "https://i1.hdslb.com/bfs/face/3d78313514bde5f4fdb1a563888b3a535c9531ae.jpg",
                        "name_color": 0,
                        "is_mystery": false,
                        "risk_ctrl_info": {
                            "name": "蛋糕11368",
                            "face": "https://i1.hdslb.com/bfs/face/3d78313514bde5f4fdb1a563888b3a535c9531ae.jpg"
                        },
                        "origin_info": {
                            "name": "蛋糕11368",
                            "face": "https://i1.hdslb.com/bfs/face/3d78313514bde5f4fdb1a563888b3a535c9531ae.jpg"
                        },
                        "official_info": {
                            "role": 0,
                            "title": "",
                            "desc": "",
                            "type": -1
                        },
                        "name_color_str": ""
                    },
                    "medal": null,
                    "wealth": {
                        "level": 2,
                        "dm_icon_key": ""
                    },
                    "title": {
                        "old_title_css_id": "",
                        "title_css_id": ""
                    },
                    "guard": {
                        "level": 0,
                        "expired_str": ""
                    },
                    "uhead_frame": null,
                    "guard_leader": null
                },
                "icon_show": false
            }
        ],
        "own_info": {
            "uid": 3494361276877525,
            "name": "Wormwaker",
            "face": "https://i1.hdslb.com/bfs/face/44766ba473ac5e3234fc5b78c1f59981eab80192.jpg",
            "rank": 1,
            "score": 1,
            "rank_text": "1",
            "need_score": 0,
            "medal_info": {
                "guard_level": 0,
                "medal_color_start": 1725515,
                "medal_color_end": 5414290,
                "medal_color_border": 1725515,
                "medal_name": "Intave",
                "level": 21,
                "target_id": 3494361276877525,
                "is_light": 1
            },
            "guard_level": 0,
            "wealth_level": 6,
            "score_lead": 1,
            "score_behind": 1,
            "is_mystery": false,
            "uinfo": {
                "uid": 3494361276877525,
                "base": {
                    "name": "Wormwaker",
                    "face": "https://i1.hdslb.com/bfs/face/44766ba473ac5e3234fc5b78c1f59981eab80192.jpg",
                    "name_color": 0,
                    "is_mystery": false,
                    "risk_ctrl_info": {
                        "name": "Wormwaker",
                        "face": "https://i1.hdslb.com/bfs/face/44766ba473ac5e3234fc5b78c1f59981eab80192.jpg"
                    },
                    "origin_info": {
                        "name": "Wormwaker",
                        "face": "https://i1.hdslb.com/bfs/face/44766ba473ac5e3234fc5b78c1f59981eab80192.jpg"
                    },
                    "official_info": {
                        "role": 0,
                        "title": "",
                        "desc": "",
                        "type": -1
                    },
                    "name_color_str": ""
                },
                "medal": {
                    "name": "Intave",
                    "level": 21,
                    "color_start": 1725515,
                    "color_end": 5414290,
                    "color_border": 1725515,
                    "color": 1725515,
                    "id": 0,
                    "typ": 0,
                    "is_light": 1,
                    "ruid": 3494361276877525,
                    "guard_level": 0,
                    "score": 2768,
                    "guard_icon": "",
                    "honor_icon": "",
                    "v2_medal_color_start": "#3FB4F699",
                    "v2_medal_color_end": "#3FB4F699",
                    "v2_medal_color_border": "#3FB4F699",
                    "v2_medal_color_text": "#FFFFFF",
                    "v2_medal_color_level": "#3FB4F6E6",
                    "user_receive_count": 0
                },
                "wealth": {
                    "level": 6,
                    "dm_icon_key": ""
                },
                "title": {
                    "old_title_css_id": "",
                    "title_css_id": ""
                },
                "guard": {
                    "level": 0,
                    "expired_str": ""
                },
                "uhead_frame": null,
                "guard_leader": null
            }
        },
        "tips_text": "",
        "count_format": "",
        "desc_format": "",
        "config": {
            "deadline_ts": 0,
            "value_text": "贡献值",
            "icon_jpg": "",
            "icon_jump_url": ""
        },
        "count_text": "5",
        "non_expandable": false,
        "bottom_guide": {
            "title": "",
            "text": "",
            "text_jump_url": "",
            "button_text": "",
            "button_jump_url": "",
            "background_img_url": "",
            "icon": ""
        },
        "list_end_prompt": ""
    }
}
```

</details>
