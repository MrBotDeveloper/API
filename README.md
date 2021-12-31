# <center>Mr. Developer API</center>
**Note that the API can stop working at the moment you started Abusing it.**

``Please don't abuse the API.``
### Show some :heart: and :star: the repo to support the project

[![GitHub stars](https://img.shields.io/github/stars/MrBotDeveloper/API.svg?style=social&label=Star)](https://github.com/MrBotDeveloper/API) ![GitHub followers](https://img.shields.io/github/followers/MrBotDeveloper.svg?style=social&label=Follow)

[![Telegram Channel](https://img.shields.io/badge/Telegram-Channel-orange)](https://t.me/NACBots)
[![Hits](https://hits.seeyoufarm.com/api/count/incr/badge.svg?url=https://github.com/MrBotDeveloper/API)](https://github.com/MrBotDeveloper/API)

---
#### **If you make something useful using the API feel free to add your amazing work in `Made using these APIs` section and send a pull request.**
---
## <center>:closed_lock_with_key: **API Features**</center>
---
### **1) YouTube Search** :mag:
Searches for youtube video's.
##### Usage:  

```sh
https://api.mrdeveloper.ga/youtube?query={your-query-here}
```

**:octocat: Required Args**

`query`: `str` Query to be searched

**:electron: Optional Supported Args**

`limit`: `integer` No. of results to get **(Defaults to 50)** :neutral_face: **(Maximum 100)**
##### **Example:** https://api.mrdeveloper.ga/youtube?query=TrollDCompany&limit=50
#####
<details><summary>Example Output</summary>

<!--START_RESPONSE-->
```json
{
    "success": true,
    "query": "TrollDCompany",
    "limit": 50,
    "results": [
        {
            "type": "video",
            "id": "LXBrMIdoigI",
            "title": "Troll Co. Who We Are",
            "publishedTime": "6 months ago",
            "duration": "0:31",
            "viewCount": {
                "text": "5,637 views",
                "short": "5.6K views"
            },
            "thumbnails": [
                {
                    "url": "https://i.ytimg.com/vi/LXBrMIdoigI/hq720.jpg?sqp=-oaymwEcCOgCEMoBSFXyq4qpAw4IARUAAIhCGAFwAcABBg==&rs=AOn4CLCy2HVwqTV0hwvZGyxag1nEnEe35A",
                    "width": 360,
                    "height": 202
                },
                {
                    "url": "https://i.ytimg.com/vi/LXBrMIdoigI/hq720.jpg?sqp=-oaymwEcCNAFEJQDSFXyq4qpAw4IARUAAIhCGAFwAcABBg==&rs=AOn4CLBGFQTBcSLn0DdpDUAPaNCAXHa3Mg",
                    "width": 720,
                    "height": 404
                }
            ],
            "richThumbnail": {
                "url": "https://i.ytimg.com/an_webp/LXBrMIdoigI/mqdefault_6s.webp?du=3000&sqp=CKDmyYwG&rs=AOn4CLB0ofjcLrkZw8sbCs3emIuk360Q8g",
                "width": 320,
                "height": 180
            },
            "descriptionSnippet": [
                {
                    "text": "Dirty Hands Clean Money."
                }
            ],
            "channel": {
                "name": "Troll Co. Clothing",
                "id": "UCgjYGDATjbJcxII33rX6xVA",
                "thumbnails": [
                    {
                        "url": "https://yt3.ggpht.com/ytc/AKedOLSvk42Ml4MJw3mNkOJnL1YZmzcotMrRkAii--r6=s68-c-k-c0x00ffffff-no-rj",
                        "width": 68,
                        "height": 68
                    }
                ],
                "link": "https://www.youtube.com/channel/UCgjYGDATjbJcxII33rX6xVA"
            },
            "accessibility": {
                "title": "Troll Co. Who We Are by Troll Co. Clothing 6 months ago 31 seconds 5,637 views",
                "duration": "31 seconds"
            },
            "link": "https://www.youtube.com/watch?v=LXBrMIdoigI",
            "shelfTitle": null
        },
        {
            "type": "video",
            "id": "yxcteej2B-A",
            "title": "Working Clothing (Troll Co Hat Barricade TC0315 & DHCM Meshback TC0178)",
            "publishedTime": "3 months ago",
            "duration": "3:17",
            "viewCount": {
                "text": "272 views",
                "short": "272 views"
            },
            "thumbnails": [
                {
                    "url": "https://i.ytimg.com/vi/yxcteej2B-A/hq720.jpg?sqp=-oaymwEcCOgCEMoBSFXyq4qpAw4IARUAAIhCGAFwAcABBg==&rs=AOn4CLB3yOJji7fWI4oc17snDtyUsytogQ",
"width": 360,
                    "height": 202
                },
                {
                    "url": "https://i.ytimg.com/vi/yxcteej2B-A/hq720.jpg?sqp=-oaymwEcCNAFEJQDSFXyq4qpAw4IARUAAIhCGAFwAcABBg==&rs=AOn4CLDq7fRf4i-8SRMjM1IddvaofPPhsw",
                    "width": 720,
                    "height": 404
                }
            ],
            "richThumbnail": {
                "url": "https://i.ytimg.com/an_webp/yxcteej2B-A/mqdefault_6s.webp?du=3000&sqp=CPDcyYwG&rs=AOn4CLAeBf1U3Hs5CGnuNK92-zn_M3B-kQ",
                "width": 320,
                "height": 180
            },
            "descriptionSnippet": [
                {
                    "text": "Mail Box: One Tool A Week Guy P.O. Box 692056 San Antonio, TX, 78269 5000 Subscribers Giveaway Veto Pro Pac Tech Pac\u00a0..."
                }
            ],
            "channel": {
                "name": "One Tool A Week Guy !",
                "id": "UC5IxEy1kMWu4s_ZkuU52lEQ",
                "thumbnails": [
                    {
                        "url": "https://yt3.ggpht.com/ytc/AKedOLSogjFue1TqX8q0dAOAMJHK34nSrt1s0F5yn-2lQA=s68-c-k-c0x00ffffff-no-rj",
                        "width": 68,
                        "height": 68
                    }
                ],
                "link": "https://www.youtube.com/channel/UC5IxEy1kMWu4s_ZkuU52lEQ"
            },
            "accessibility": {
                "title": "Working Clothing (Troll Co Hat Barricade TC0315 & DHCM Meshback TC0178) by One Tool A Week Guy ! 3 months ago 3 minutes, 17 seconds 272 views",
                "duration": "3 minutes, 17 seconds"
            },
            "link": "https://www.youtube.com/watch?v=yxcteej2B-A",
            "shelfTitle": null
        },
        {
            "type": "video",
            "id": "zbxs7vrpHzk",
            "title": "troll co. unboxing + updates",
            "publishedTime": "2 years ago",
            "duration": "11:16",
            "viewCount": {
                "text": "4,082 views",
                "short": "4K views"
            },
            "thumbnails": [
                {
                    "url": "https://i.ytimg.com/vi/zbxs7vrpHzk/hq720.jpg?sqp=-oaymwEcCOgCEMoBSFXyq4qpAw4IARUAAIhCGAFwAcABBg==&rs=AOn4CLBSUTlHNIR8GcQ5ozUMOGNwRYmcwQ",
                    "width": 360,
                    "height": 202
                },
                {
                    "url": "https://i.ytimg.com/vi/zbxs7vrpHzk/hq720.jpg?sqp=-oaymwEcCNAFEJQDSFXyq4qpAw4IARUAAIhCGAFwAcABBg==&rs=AOn4CLAG192otwHntYgITSgMF1bxfNkg6Q",
                    "width": 720,
                    "height": 404
                }
            ],
            "richThumbnail": null,
            "descriptionSnippet": [
                {
                    "text": "Hey maniacs madman here with a bit of an unboxing video plus some updates on what Ive been up to the last couple of weeks!"
                }
            ],
            "channel": {
                "name": "Kryptic Art",
                "id": "UCm6uRX4MvR6_rnNShKwgAgQ",
                "thumbnails": [
                    {
                        "url": "https://yt3.ggpht.com/ytc/AKedOLSS76SD2av73Rm5Ma7N3lAq9usBDyRrnyCqgyBN5A=s68-c-k-c0x00ffffff-no-rj",
                        "width": 68,
                        "height": 68
                    }
                ],
                "link": "https://www.youtube.com/channel/UCm6uRX4MvR6_rnNShKwgAgQ"
            },
            "accessibility": {
                "title": "troll co. unboxing + updates by Kryptic Art 2 years ago 11 minutes, 16 seconds 4,082 views",
                "duration": "11 minutes, 16 seconds"
            },
            "link": "https://www.youtube.com/watch?v=zbxs7vrpHzk",
            "shelfTitle": null
        },
        {
            "type": "video",
            "id": "-LJtb0a-0DQ",
            "title": "Troll Company",
            "publishedTime": "10 months ago",
            "duration": "0:17",
            "viewCount": {
    "text": "3 views",
                "short": "3 views"
            },
            "thumbnails": [
                {
                    "url": "https://i.ytimg.com/vi/-LJtb0a-0DQ/hqdefault.jpg?sqp=-oaymwEcCOADEI4CSFXyq4qpAw4IARUAAIhCGAFwAcABBg==&rs=AOn4CLDUjESoWMl9XfdD1uwHg_pB7SOzlw",
                    "width": 480,
                    "height": 270
                }
            ],
            "richThumbnail": {
                "url": "https://i.ytimg.com/an_webp/-LJtb0a-0DQ/mqdefault_6s.webp?du=3000&sqp=CNyEyowG&rs=AOn4CLCOFHvQvHLTG-zHTgNAwP5MlDr6tQ",
                "width": 320,
                "height": 180
            },
            "descriptionSnippet": [
                {
                    "text": "https://store.playstation.com/#!/tid=CUSA15147_00."
                }
            ],
            "channel": {
                "name": "Nowlind TV",
                "id": "UCtkWZnpxD5Z7r1JuFjFO3Tg",
                "thumbnails": [
                    {
                        "url": "https://yt3.ggpht.com/ytc/AKedOLROwuaD3QpPAxXrabMWgdSuluedG2tKRbN2E4uz=s68-c-k-c0x00ffffff-no-rj",
                        "width": 68,
                        "height": 68
                    }
                ],
                "link": "https://www.youtube.com/channel/UCtkWZnpxD5Z7r1JuFjFO3Tg"
            },
            "accessibility": {
                "title": "Troll Company by Nowlind TV 10 months ago 17 seconds 3 views",
                "duration": "17 seconds"
            },
            "link": "https://www.youtube.com/watch?v=-LJtb0a-0DQ",
            "shelfTitle": null
        },
        {
            "type": "video",
            "id": "LObarHyVlyQ",
            "title": "Troll Company",
            "publishedTime": "8 years ago",
            "duration": "2:51",
            "viewCount": {
                "text": "99 views",
                "short": "99 views"
            },
            "thumbnails": [
                {
                    "url": "https://i.ytimg.com/vi/LObarHyVlyQ/hq720.jpg?sqp=-oaymwEcCOgCEMoBSFXyq4qpAw4IARUAAIhCGAFwAcABBg==&rs=AOn4CLChP6jItrk76oIWKfw4axMejdQZug",
                    "width": 360,
                    "height": 202
                },
                {
                    "url": "https://i.ytimg.com/vi/LObarHyVlyQ/hq720.jpg?sqp=-oaymwEcCNAFEJQDSFXyq4qpAw4IARUAAIhCGAFwAcABBg==&rs=AOn4CLDnwZH5M6uOA5aOVzTsc2VIBEXuCA",
                    "width": 720,
                    "height": 404
                }
            ],
            "richThumbnail": null,
            "descriptionSnippet": [
                {
                    "text": "Pz.Kpfw. I Ausf. C : the art of "
                },
                {
                    "text": "trolling",
                    "bold": true
                },
                {
                    "text": "."
                }
            ],
            "channel": {
                "name": "Mamadou7891",
                "id": "UCaBY83NCXdKG0c-FubCTAHw",
                "thumbnails": [
                    {
                        "url": "https://yt3.ggpht.com/ytc/AKedOLSJYrzrw6NWOylN5tQAup4VHVu42cHMYZC_9bHB=s68-c-k-c0x00ffffff-no-rj",
                        "width": 68,
                        "height": 68
                    }
                ],
                "link": "https://www.youtube.com/channel/UCaBY83NCXdKG0c-FubCTAHw"
            },
            "accessibility": {
                "title": "Troll Company by Mamadou7891 8 years ago 2 minutes, 51 seconds 99 views",
                "duration": "2 minutes, 51 seconds"
            },
            "link": "https://www.youtube.com/watch?v=LObarHyVlyQ",
            "shelfTitle": null
        },
        {
            "type": "video",
            "id": "USu5Skl2Wv8",
            "title": "\u0d28\u0d32\u0d4d\u0d32 interesting \u0d06\u0d2f \u0d15\u0d41\u0d31\u0d1a\u0d4d\u0d1a\u0d41 \u0d38\u0d3f\u0d28\u0d3f\u0d2e\u0d15\u0d7e | D Company Movies",
            "publishedTime": "3 months ago",
            "duration":"7:08",
            "viewCount": {
                "text": "9,194 views",
                "short": "9.1K views"
            },
            "thumbnails": [
                {
                    "url": "https://i.ytimg.com/vi/USu5Skl2Wv8/hq720.jpg?sqp=-oaymwEcCOgCEMoBSFXyq4qpAw4IARUAAIhCGAFwAcABBg==&rs=AOn4CLCH9uUT0WFsYWZXv0gYx446y8SzeQ",
                    "width": 360,
                    "height": 202
                },
                {
                    "url": "https://i.ytimg.com/vi/USu5Skl2Wv8/hq720.jpg?sqp=-oaymwEcCNAFEJQDSFXyq4qpAw4IARUAAIhCGAFwAcABBg==&rs=AOn4CLB49rzQj2cB5pmHPpbkxcdLZhocpw",
                    "width": 720,
                    "height": 404
                }
            ],
            "richThumbnail": {
                "url": "https://i.ytimg.com/an_webp/USu5Skl2Wv8/mqdefault_6s.webp?du=3000&sqp=CPHbyYwG&rs=AOn4CLC8GVGnQaE93qMukq4kr_pqk70Sig",
                "width": 320,
                "height": 180
            },
            "descriptionSnippet": [
                {
                    "text": "DCompanyMovies #TrollDCompanyMovieSuggestions Follow us on our different platform's "
                },
                {
                    "text": "Troll",
                    "bold": true
                },
                {
                    "text": " D\u00a0..."
                }
            ],
            "channel": {
                "name": "D Company Movies",
                "id": "UCZnj5Nnn7DNwT9Bn-JIknlg",
                "thumbnails": [
                    {
                        "url": "https://yt3.ggpht.com/ytc/AKedOLRaGOhaZ-NjO9Awii4R6VlPzF0hbZTH0dixXFVh3A=s68-c-k-c0x00ffffff-no-rj",
                        "width": 68,
                        "height": 68
                    }
                ],
                "link": "https://www.youtube.com/channel/UCZnj5Nnn7DNwT9Bn-JIknlg"
            },
            "accessibility": {
                "title": "\u0d28\u0d32\u0d4d\u0d32 interesting \u0d06\u0d2f \u0d15\u0d41\u0d31\u0d1a\u0d4d\u0d1a\u0d41 \u0d38\u0d3f\u0d28\u0d3f\u0d2e\u0d15\u0d7e | D Company Movies by D Company Movies 3 months ago 7 minutes, 8 seconds 9,194 views",
                "duration": "7 minutes, 8 seconds"
            },
            "link": "https://www.youtube.com/watch?v=USu5Skl2Wv8",
            "shelfTitle": null
        },
        {
            "type": "video",
            "id": "2ix8JEqCJ1s",
            "title": "Inside the bizarre world of internet trolls and propagandists | Andrew Marantz",
            "publishedTime": "2 years ago",
            "duration": "14:37",
            "viewCount": {
                "text": "176,223 views",
                "short": "176K views"
            },
            "thumbnails": [
                {
                    "url": "https://i.ytimg.com/vi/2ix8JEqCJ1s/hq720.jpg?sqp=-oaymwEcCOgCEMoBSFXyq4qpAw4IARUAAIhCGAFwAcABBg==&rs=AOn4CLA9V9oBwSU8SYLrkxJd7jx0FBgFNQ",
                    "width": 360,
                    "height": 202
                },
                {
                    "url": "https://i.ytimg.com/vi/2ix8JEqCJ1s/hq720.jpg?sqp=-oaymwEcCNAFEJQDSFXyq4qpAw4IARUAAIhCGAFwAcABBg==&rs=AOn4CLDFpmw3kcT83RgH902pSp2SJpuDuw",
                    "width": 720,
                    "height": 404
                }
            ],
            "richThumbnail": {
                "url": "https://i.ytimg.com/an_webp/2ix8JEqCJ1s/mqdefault_6s.webp?du=3000&sqp=CNnZyYwG&rs=AOn4CLCTdLz4HKW-zeeW4v1Q76ORlzwsTg",
                "width": 320,
                "height": 180
            },
            "descriptionSnippet": [
                {
                    "text": "Journalist Andrew Marantz spent three years embedded in the world of internet "
                },
                {
                    "text": "trolls",
                    "bold": true
                },
                {
                    "text": " and social media propagandists, seeking out\u00a0..."
                }
            ],
            "channel": {
                "name":"TED",
                "id": "UCAuUUnT6oDeKwE6v1NGQxug",
                "thumbnails": [
                    {
                        "url": "https://yt3.ggpht.com/ytc/AKedOLRTHraf4M_OaDZFwfqK8F9TTjxe3DHwFZMkZGqmAw=s68-c-k-c0x00ffffff-no-rj",
                        "width": 68,
                        "height": 68
                    }
                ],
                "link": "https://www.youtube.com/channel/UCAuUUnT6oDeKwE6v1NGQxug"
            },
            "accessibility": {
                "title": "Inside the bizarre world of internet trolls and propagandists | Andrew Marantz by TED 2 years ago 14 minutes, 37 seconds 176,223 views",
                "duration": "14 minutes, 37 seconds"
            },
            "link": "https://www.youtube.com/watch?v=2ix8JEqCJ1s",
            "shelfTitle": null
        },
        {
            "type": "video",
            "id": "NZf98ni0i5E",
            "title": "Troll's Company",
            "publishedTime": "9 years ago",
            "duration": "1:04",
            "viewCount": {
                "text": "25 views",
                "short": "25 views"
            },
            "thumbnails": [
                {
                    "url": "https://i.ytimg.com/vi/NZf98ni0i5E/hqdefault.jpg?sqp=-oaymwEcCOADEI4CSFXyq4qpAw4IARUAAIhCGAFwAcABBg==&rs=AOn4CLCM1YbfO3q-BfXB7V07VcfFESnlFw",
                    "width": 480,
                    "height": 270
                }
            ],
            "richThumbnail": null,
            "descriptionSnippet": [
                {
                    "text": "Come and knock on our doooor...."
                }
            ],
            "channel": {
                "name": "grandpahipster",
                "id": "UC00Bg-sYziH0oILG0zfIZhw",
                "thumbnails": [
                    {
                        "url": "https://yt3.ggpht.com/ytc/AKedOLSXc72jmGk8ZghzakSFRqy6v4OTRElsLVIM3w=s68-c-k-c0x00ffffff-no-rj",
                        "width": 68,
                        "height": 68
                    }
                ],
                "link": "https://www.youtube.com/channel/UC00Bg-sYziH0oILG0zfIZhw"
            },
            "accessibility": {
                "title": "Troll's Company by grandpahipster 9 years ago 1 minute, 4 seconds 25 views",
                "duration": "1 minute, 4 seconds"
            },
            "link": "https://www.youtube.com/watch?v=NZf98ni0i5E",
            "shelfTitle": null
        },
        {
            "type": "video",
            "id": "E_lb3D7Ay-M",
            "title": "Drew Curtis: How I beat a patent troll",
            "publishedTime": "9 years ago",
            "duration": "6:41",
            "viewCount": {
                "text": "140,263 views",
                "short": "140K views"
            },
            "thumbnails": [
                {
                    "url": "https://i.ytimg.com/vi/E_lb3D7Ay-M/hq720.jpg?sqp=-oaymwEcCOgCEMoBSFXyq4qpAw4IARUAAIhCGAFwAcABBg==&rs=AOn4CLCEpTkM6koH0g5yATXaJ1z7AGzC5g",
                    "width": 360,
                    "height": 202
                },
                {
                    "url": "https://i.ytimg.com/vi/E_lb3D7Ay-M/hq720.jpg?sqp=-oaymwEcCNAFEJQDSFXyq4qpAw4IARUAAIhCGAFwAcABBg==&rs=AOn4CLCK63FR2w4QtlRIRXAc6YC17lEB3w",
                    "width": 720,
                    "height": 404
                }
            ],
            "richThumbnail": {
                "url": "https://i.ytimg.com/an_webp/E_lb3D7Ay-M/mqdefault_6s.webp?du=3000&sqp=CIHlyYwG&rs=AOn4CLChb9C6-BJ2rH8nFSB_0zUjJ5lYgA",
                "width": 320,
                "height": 180
            },
            "descriptionSnippet": [
                {
                    "text": "TEDTalks is a daily video podcast of the best talks and performances from the TED Conference, where the world's leading\u00a0..."
                }
            ],
            "channel": {
                "name": "TED",
                "id": "UCAuUUnT6oDeKwE6v1NGQxug",
                "thumbnails":[
                    {
                        "url": "https://yt3.ggpht.com/ytc/AKedOLRTHraf4M_OaDZFwfqK8F9TTjxe3DHwFZMkZGqmAw=s68-c-k-c0x00ffffff-no-rj",
                        "width": 68,
                        "height": 68
                    }
                ],
                "link": "https://www.youtube.com/channel/UCAuUUnT6oDeKwE6v1NGQxug"
            },
            "accessibility": {
                "title": "Drew Curtis: How I beat a patent troll by TED 9 years ago 6 minutes, 41 seconds 140,263 views",
                "duration": "6 minutes, 41 seconds"
            },
            "link": "https://www.youtube.com/watch?v=E_lb3D7Ay-M",
            "shelfTitle": null
        },
        {
            "type": "video",
            "id": "us4Eti0UmDI",
            "title": "The world's greatest internet troll explains his craft",
            "publishedTime": "5 years ago",
            "duration": "8:07",
            "viewCount": {
                "text": "4,103,598 views",
                "short": "4.1M views"
            },
            "thumbnails": [
                {
                    "url": "https://i.ytimg.com/vi/us4Eti0UmDI/hq720.jpg?sqp=-oaymwEcCOgCEMoBSFXyq4qpAw4IARUAAIhCGAFwAcABBg==&rs=AOn4CLDmEe-ALPbLpbSY6IxST6DFmt2h5w",
                    "width": 360,
                    "height": 202
                },
                {
                    "url": "https://i.ytimg.com/vi/us4Eti0UmDI/hq720.jpg?sqp=-oaymwEcCNAFEJQDSFXyq4qpAw4IARUAAIhCGAFwAcABBg==&rs=AOn4CLAD-9MFMGpPULYqz6Eh3R4JGNFwng",
                    "width": 720,
                    "height": 404
                }
            ],
            "richThumbnail": {
                "url": "https://i.ytimg.com/an_webp/us4Eti0UmDI/mqdefault_6s.webp?du=3000&sqp=CIKHyowG&rs=AOn4CLBL0KgLjT3pCMTgSqDf3TCpE_OpQA",
                "width": 320,
                "height": 180
            },
            "descriptionSnippet": [
                {
                    "text": "Ken M. is probably the world's greatest internet "
                },
                {
                    "text": "troll",
                    "bold": true
                },
                {
                    "text": ". Is it "
                },
                {
                    "text": "trolling",
                    "bold": true
                },
                {
                    "text": " to pick the world's greatest "
                },
                {
                    "text": "troll",
                    "bold": true
                },
                {
                    "text": "? You be the judge. But this is how\u00a0..."
                }
            ],
            "channel": {
                "name": "Vox",
                "id": "UCLXo7UDZvByw2ixzpQCufnA",
                "thumbnails": [
                    {
                        "url": "https://yt3.ggpht.com/ytc/AKedOLTm7P51YEeoapoU-FYmc8v7YfBeHZpbX8CfPCmxAg=s68-c-k-c0x00ffffff-no-rj",
                        "width": 68,
                        "height": 68
                    }
                ],
                "link": "https://www.youtube.com/channel/UCLXo7UDZvByw2ixzpQCufnA"
            },
            "accessibility": {
                "title": "The world's greatest internet troll explains his craft by Vox 5 years ago 8 minutes, 7 seconds 4,103,598 views",
                "duration": "8 minutes, 7 seconds"
            },
            "link": "https://www.youtube.com/watch?v=us4Eti0UmDI",
            "shelfTitle": null
        },
        {
            "type": "video",
            "id": "Y7W4fRdluzY",
            "title": "# pirate troll company",
            "publishedTime": "3 hours ago",
            "duration": "0:15",
            "viewCount": {
                "text": "No views",
                "short": "No views"
            },
            "thumbnails": [
                {
                    "url": "https://i.ytimg.com/vi/Y7W4fRdluzY/hq720.jpg?sqp=-oaymwEcCOgCEMoBSFXyq4qpAw4IARUAAIhCGAFwAcABBg==&rs=AOn4CLAFt4snDhAXlEkUI_5Sf2FcbP_lZQ",
                    "width": 360,
                    "height": 202
                },
                {
                    "url": "https://i.ytimg.com/vi/Y7W4fRdluzY/hq720.jpg?sqp=-oaymwEcCNAFEJQDSFXyq4qpAw4IARUAAIhCGAFwAcABBg==&rs=AOn4CLALdow8PlpilR_F1dOUuYNcoxx7-g",
                    "width": 720,
                    "height": 404
                }
            ],
            "richThumbnail": {
                "url": "https://i.ytimg.com/an_webp/Y7W4fRdluzY/mqdefault_6s.webp?du=3000&sqp=CMz3yYwG&rs=AOn4CLDQ4ILFfwC4k9kZOzJNa0AEz2TckA",
                "width": 320,
                "height": 180
            },
            "descriptionSnippet": null,
            "channel": {
                "name": "pirate troll company",
                "id": "UCElk7SluyEiHlHfqgDnFOWQ",
                "thumbnails": [
                    {
                        "url": "https://yt3.ggpht.com/BVrxgK1rFdu9PDcw9MlBafVWjZA0vhpCKdhQxjk-PD3hb2euE671l5fm2JmbY4heJU3qA7D47A=s68-c-k-c0x00ffffff-no-rj",
                        "width": 68,
                        "height": 68
                    }
                ],
                "link": "https://www.youtube.com/channel/UCElk7SluyEiHlHfqgDnFOWQ"
            },
            "accessibility": {
                "title": "# pirate troll company by pirate troll company 3 hours ago 15 seconds No views",
                "duration": "15 seconds"
            },
            "link": "https://www.youtube.com/watch?v=Y7W4fRdluzY",
            "shelfTitle": null
        },
        {
            "type": "video",
            "id": "GWnn8D9ZlJM",
            "title": "\ud83c\udf55KOMPANY SLICE\ud83c\udf55 (Coutinho Man City football cartoon Liverpool 3-2 Man City 2014)",
            "publishedTime": "7 years ago",
            "duration": "2:51",
            "viewCount": {
                "text": "3,215,116 views",
                "short": "3.2M views"
            },
            "thumbnails": [
                {
                    "url": "https://i.ytimg.com/vi/GWnn8D9ZlJM/hq720.jpg?sqp=-oaymwEcCOgCEMoBSFXyq4qpAw4IARUAAIhCGAFwAcABBg==&rs=AOn4CLBCpd9juScykDYSvVaOze4YbCvfXA",
                    "width": 360,
                    "height": 202
                },
                {
                    "url": "https://i.ytimg.com/vi/GWnn8D9ZlJM/hq720.jpg?sqp=-oaymwEcCNAFEJQDSFXyq4qpAw4IARUAAIhCGAFwAcABBg==&rs=AOn4CLB37sgVXkFwK4KXWE4rqKSfYgykrg",
                    "width": 720,
                    "height": 404
                }
            ],
            "richThumbnail": {
                "url": "https://i.ytimg.com/an_webp/GWnn8D9ZlJM/mqdefault_6s.webp?du=3000&sqp=CO7RyYwG&rs=AOn4CLDLZ9JDwv_6w6Nt0dYLtluzzQsBhA",
                "width": 320,
                "height": 180
            },
            "descriptionSnippet": [
                {
                    "text": "Please note: these shit cartoons are not made for kids in any way. They contain swearing, cartoon violence and non-children\u00a0..."
                }
            ],
            "channel": {
                "name": "442oons",
                "id": "UC4SUUloEcrgjsxbmy_rQQXA",
                "thumbnails": [
                    {
                        "url": "https://yt3.ggpht.com/mZG7H7YFvazBbPT55mRNXBvpEhHdw9XZISMeVaafmHk4m-I7VDbfOsbA3idv8svioM-t-ddV4w=s68-c-k-c0x00ffffff-no-rj",
                        "width": 68,
                        "height": 68
                    }
                ],
                "link": "https://www.youtube.com/channel/UC4SUUloEcrgjsxbmy_rQQXA"
            },
            "accessibility": {
                "title": "\ud83c\udf55KOMPANY SLICE\ud83c\udf55 (Coutinho Man City football cartoon Liverpool 3-2 Man City 2014) by 442oons 7 years ago 2 minutes, 51 seconds 3,215,116 views",
                "duration": "2 minutes, 51 seconds"
            },
            "link": "https://www.youtube.com/watch?v=GWnn8D9ZlJM",
            "shelfTitle": null
        },
        {
            "type": "video",
      "id": "8wMV3aM_Hu0",
            "title": "Ca\u00eddas en p\u00fablico (TROLL Company)",
            "publishedTime": "7 years ago",
            "duration": "3:18",
            "viewCount": {
                "text": "238 views",
                "short": "238 views"
            },
            "thumbnails": [
                {
                    "url": "https://i.ytimg.com/vi/8wMV3aM_Hu0/hq720.jpg?sqp=-oaymwEcCOgCEMoBSFXyq4qpAw4IARUAAIhCGAFwAcABBg==&rs=AOn4CLD8bMmbpMiJSvuBMPweyVasXoNAVw",
                    "width": 360,
                    "height": 202
                },
                {
                    "url": "https://i.ytimg.com/vi/8wMV3aM_Hu0/hq720.jpg?sqp=-oaymwEcCNAFEJQDSFXyq4qpAw4IARUAAIhCGAFwAcABBg==&rs=AOn4CLCswTsa8cmQe5KSFytoTtBOm_YxLw",
                    "width": 720,
                    "height": 404
                }
            ],
            "richThumbnail": null,
            "descriptionSnippet": null,
            "channel": {
                "name": "Troll Company",
                "id": "UCUr81IWSPcZshW5PzG4CMpQ",
                "thumbnails": [
                    {
                        "url": "https://yt3.ggpht.com/ytc/AKedOLSaPavID161ymtnlBF0rKhSq7NOe5k_RC1fg2fi=s68-c-k-c0x00ffffff-no-rj",
                        "width": 68,
                        "height": 68
                    }
                ],
                "link": "https://www.youtube.com/channel/UCUr81IWSPcZshW5PzG4CMpQ"
            },
            "accessibility": {
                "title": "Ca\u00eddas en p\u00fablico (TROLL Company) by Troll Company 7 years ago 3 minutes, 18 seconds 238 views",
                "duration": "3 minutes, 18 seconds"
            },
            "link": "https://www.youtube.com/watch?v=8wMV3aM_Hu0",
            "shelfTitle": null
        },
        {
            "type": "video",
            "id": "JQClnZrN9HE",
            "title": "HAPPY DIWALI / TROLL COMPANY| /\ud83d\ude18\ud83d\ude18",
            "publishedTime": "10 days ago",
            "duration": "2:39",
            "viewCount": {
                "text": "32 views",
                "short": "32 views"
            },
            "thumbnails": [
                {
                    "url": "https://i.ytimg.com/vi/JQClnZrN9HE/hq720.jpg?sqp=-oaymwEcCOgCEMoBSFXyq4qpAw4IARUAAIhCGAFwAcABBg==&rs=AOn4CLB2XmCVofE21L0eYsz05XSJdG5Zlw",
                    "width": 360,
                    "height": 202
                },
                {
                    "url": "https://i.ytimg.com/vi/JQClnZrN9HE/hq720.jpg?sqp=-oaymwEcCNAFEJQDSFXyq4qpAw4IARUAAIhCGAFwAcABBg==&rs=AOn4CLCu71SHRjdF21Zxa8tctqwZQRFUCQ",
                    "width": 720,
                    "height": 404
                }
            ],
            "richThumbnail": {
                "url": "https://i.ytimg.com/an_webp/JQClnZrN9HE/mqdefault_6s.webp?du=3000&sqp=CJWByowG&rs=AOn4CLBB_LYKIYYbZk6GLZTToZwTcHilkw",
                "width": 320,
                "height": 180
            },
            "descriptionSnippet": [
                {
                    "text": "https://youtu.be/VlyzUsUfvqo."
                }
            ],
            "channel": {
                "name": "TROLL COMPANY",
                "id": "UCr0PinX_OBak-Ytv4J1lVqA",
                "thumbnails": [
                    {
                        "url": "https://yt3.ggpht.com/2ONSjZTt3aOxxS2OW6op_VllZF2yQhVnw1t5x4lUL2JZ0hbPBGMmktw0qSdZvzA-IGoHTcTMfw=s68-c-k-c0x00ffffff-no-rj",
                        "width": 68,
                        "height": 68
                    }
                ],
                "link": "https://www.youtube.com/channel/UCr0PinX_OBak-Ytv4J1lVqA"
            },
            "accessibility": {
                "title": "HAPPY DIWALI / TROLL COMPANY| /\ud83d\ude18\ud83d\ude18 by TROLL COMPANY 10 days ago 2 minutes, 39 seconds 32 views",
                "duration": "2 minutes, 39 seconds"
            },
            "link": "https://www.youtube.com/watch?v=JQClnZrN9HE",
            "shelfTitle": null
  },
        {
            "type": "video",
            "id": "8Ws38L6Y4Ak",
            "title": "The Light Troll Company",
            "publishedTime": "9 years ago",
            "duration": "12:47",
            "viewCount": {
                "text": "733 views",
                "short": "733 views"
            },
            "thumbnails": [
                {
                    "url": "https://i.ytimg.com/vi/8Ws38L6Y4Ak/hq720.jpg?sqp=-oaymwEcCOgCEMoBSFXyq4qpAw4IARUAAIhCGAFwAcABBg==&rs=AOn4CLChZ5fRsn_hjjZ86MF-DTh5mB865A",
                    "width": 360,
                    "height": 202
                },
                {
                    "url": "https://i.ytimg.com/vi/8Ws38L6Y4Ak/hq720.jpg?sqp=-oaymwEcCNAFEJQDSFXyq4qpAw4IARUAAIhCGAFwAcABBg==&rs=AOn4CLAx_mgNpv4DMl7gCtpYANGDD2Vvnw",
                    "width": 720,
                    "height": 404
                }
            ],
            "richThumbnail": null,
            "descriptionSnippet": [
                {
                    "text": "6 Lights tank 2 Platoons 3 Battles Infinite Win Music: Tomboyish Girl in Love (Hisoutensoku remix) - ZUN."
                }
            ],
            "channel": {
                "name": "Elepole Eolis",
                "id": "UCQMR3NoQ4bdWK02r-9PVccw",
                "thumbnails": [
                    {
                        "url": "https://yt3.ggpht.com/ytc/AKedOLSLuWvExKkyGK58hNYfJdP3A1-4-dbkYsonFmhc9Q=s68-c-k-c0x00ffffff-no-rj",
                        "width": 68,
                        "height": 68
                    }
                ],
                "link": "https://www.youtube.com/channel/UCQMR3NoQ4bdWK02r-9PVccw"
            },
            "accessibility": {
                "title": "The Light Troll Company by Elepole Eolis 9 years ago 12 minutes, 47 seconds 733 views",
                "duration": "12 minutes, 47 seconds"
            },
            "link": "https://www.youtube.com/watch?v=8Ws38L6Y4Ak",
            "shelfTitle": null
        },
        {
            "type": "video",
            "id": "2q5zzh5TYDo",
            "title": "Copyright Troll Arrest Hearing Reveals Company in Shambles (Malibu Media v. Mullins)",
            "publishedTime": "3 weeks ago",
            "duration": "18:42",
            "viewCount": {
                "text": "25,901 views",
                "short": "25K views"
            },
            "thumbnails": [
                {
                    "url": "https://i.ytimg.com/vi/2q5zzh5TYDo/hq720.jpg?sqp=-oaymwEcCOgCEMoBSFXyq4qpAw4IARUAAIhCGAFwAcABBg==&rs=AOn4CLAOYZS4FN39gXabywmlVMYQW49UvQ",
                    "width": 360,
                    "height": 202
                },
                {
                    "url": "https://i.ytimg.com/vi/2q5zzh5TYDo/hq720.jpg?sqp=-oaymwEcCNAFEJQDSFXyq4qpAw4IARUAAIhCGAFwAcABBg==&rs=AOn4CLDA3OjKBhLQFIfuxcTEfoUohOnpVQ",
                    "width": 720,
                    "height": 404
                }
            ],
            "richThumbnail": {
                "url": "https://i.ytimg.com/an_webp/2q5zzh5TYDo/mqdefault_6s.webp?du=3000&sqp=COiByowG&rs=AOn4CLAWHAcB0jioNBIQrer_zFOA20mdVA",
                "width": 320,
                "height": 180
            },
            "descriptionSnippet": [
                {
                    "text": "I attended the Malibu Media v. Mullins hearing where X-Art proprietor Colette Pelissier faced an arrest Order for failure to turn over\u00a0..."
                }
            ],
            "channel": {
                "name": "Lawful Masses with Leonard French",
                "id": "UChBJtu4BhT8b8t9Qe9R-EZg",
                "thumbnails": [
                    {
                        "url": "https://yt3.ggpht.com/ytc/AKedOLSBGOdW3BfHeHvY36pnQR5IgW0bQBnaJl7Q52uzRg=s68-c-k-c0x00ffffff-no-rj",
                        "width": 68,
                        "height": 68
                    }
                ],
                "link": "https://www.youtube.com/channel/UChBJtu4BhT8b8t9Qe9R-EZg"
          },
            "accessibility": {
                "title": "Copyright Troll Arrest Hearing Reveals Company in Shambles (Malibu Media v. Mullins) by Lawful Masses with Leonard French 3 weeks ago 18 minutes 25,901 views",
                "duration": "18 minutes, 42 seconds"
            },
            "link": "https://www.youtube.com/watch?v=2q5zzh5TYDo",
            "shelfTitle": null
        },
        {
            "type": "video",
            "id": "0-b_gIyjXgc",
            "title": "Troll company guys",
            "publishedTime": "8 years ago",
            "duration": "0:28",
            "viewCount": {
                "text": "5 views",
                "short": "5 views"
            },
            "thumbnails": [
                {
                    "url": "https://i.ytimg.com/vi/0-b_gIyjXgc/hqdefault.jpg?sqp=-oaymwEcCOADEI4CSFXyq4qpAw4IARUAAIhCGAFwAcABBg==&rs=AOn4CLBZlJaPJIw8DaqVkx4pxCKFagayLg",
                    "width": 480,
                    "height": 270
                }
            ],
            "richThumbnail": null,
            "descriptionSnippet": [
                {
                    "text": "this is a random video for the start and congrats for our new gaming "
                },
                {
                    "text": "troll company",
                    "bold": true
                },
                {
                    "text": "."
                }
            ],
            "channel": {
                "name": "Drew Capitosti",
                "id": "UC2LKLygboV_z8olTuSJUHcg",
                "thumbnails": [
                    {
                        "url": "https://yt3.ggpht.com/ytc/AKedOLRo58hMUN_3VQkJIGb9MtY5eL_1TsDA6JZ7xK3O=s68-c-k-c0x00ffffff-no-rj",
                        "width": 68,
                        "height": 68
                    }
                ],
                "link": "https://www.youtube.com/channel/UC2LKLygboV_z8olTuSJUHcg"
            },
            "accessibility": {
                "title": "Troll company guys by Drew Capitosti 8 years ago 28 seconds 5 views",
                "duration": "28 seconds"
            },
            "link": "https://www.youtube.com/watch?v=0-b_gIyjXgc",
            "shelfTitle": null
        },
        {
            "type": "video",
            "id": "RX_sT8prmlg",
            "title": "Bienvenue sur La Troll Company !",
            "publishedTime": "7 years ago",
            "duration": "1:01",
            "viewCount": {
                "text": "90 views",
                "short": "90 views"
            },
            "thumbnails": [
                {
                    "url": "https://i.ytimg.com/vi/RX_sT8prmlg/hq720.jpg?sqp=-oaymwEcCOgCEMoBSFXyq4qpAw4IARUAAIhCGAFwAcABBg==&rs=AOn4CLARAQZU23tGNmxXkZ2njistSB6D-Q",
                    "width": 360,
                    "height": 202
                },
                {
                    "url": "https://i.ytimg.com/vi/RX_sT8prmlg/hq720.jpg?sqp=-oaymwEcCNAFEJQDSFXyq4qpAw4IARUAAIhCGAFwAcABBg==&rs=AOn4CLA1g8eDC0jdKMzfm-Af5ZLh8KEWQw",
                    "width": 720,
                    "height": 404
                }
            ],
            "richThumbnail": null,
            "descriptionSnippet": [
                {
                    "text": "Notre Facebook : https://www.facebook.com/pages/La-"
                },
                {
                    "text": "Troll",
                    "bold": true
                },
                {
                    "text": "-"
                },
                {
                    "text": "Company",
                    "bold": true
                },
                {
                    "text": "/203429399843916 Notre Twitter\u00a0..."
                }
            ],
            "channel": {
                "name": "La Troll Company \u00a9 LTC",
                "id": "UCQBP53LWBThM5Yq5JZ0_x9Q",
                "thumbnails": [
                    {
                        "url": "https://yt3.ggpht.com/ytc/AKedOLSs7k9y83kW71VGUZTjB822nIu-2baysO686N1z=s68-c-k-c0x00ffffff-no-rj",
                        "width": 68,
                        "height": 68
                    }
                ],
                "link": "https://www.youtube.com/channel/UCQBP53LWBThM5Yq5JZ0_x9Q"
            },
            "accessibility": {
                "title": "Bienvenue sur La Troll Company ! by La Troll Company \u00a9 LTC 7 years ago 1 minute, 1 second 90 views",
                "duration": "1 minute, 1 second"
            },
            "link": "https://www.youtube.com/watch?v=RX_sT8prmlg",
            "shelfTitle": null
        },
        {
            "type": "video",
            "id": "cbOB0_duN1s",
            "title": "Samsung TROLL Apple AGAIN! (All 9 New Ads)",
            "publishedTime": "3 years ago",
            "duration": "5:03",
            "viewCount": {
                "text": "1,230,150 views",
                "short": "1.2M views"
            },
            "thumbnails": [
                {
                    "url": "https://i.ytimg.com/vi/cbOB0_duN1s/hq720.jpg?sqp=-oaymwEcCOgCEMoBSFXyq4qpAw4IARUAAIhCGAFwAcABBg==&rs=AOn4CLB3B5-soLdTPUbBpmaUFfi2FvcWrw",
                    "width": 360,
                    "height": 202
                },
                {
                    "url": "https://i.ytimg.com/vi/cbOB0_duN1s/hq720.jpg?sqp=-oaymwEcCNAFEJQDSFXyq4qpAw4IARUAAIhCGAFwAcABBg==&rs=AOn4CLDYQ-OvsajmVNrteVxbd326n6cuog",
                    "width": 720,
                    "height": 404
                }
            ],
            "richThumbnail": {
                "url": "https://i.ytimg.com/an_webp/cbOB0_duN1s/mqdefault_6s.webp?du=3000&sqp=CNnmyYwG&rs=AOn4CLAfG4E0jWnVe1_6daiXomjcSVkesg",
                "width": 320,
                "height": 180
            },
            "descriptionSnippet": [
                {
                    "text": "Hello YouTube, Samsung has released new ads AGAIN targeting Apple. These ads were posted on Samsung US channel."
                }
            ],
            "channel": {
                "name": "Mobile Tech Point",
                "id": "UCSY2_WP6dt87_dtdnv7hcsQ",
                "thumbnails": [
                    {
                        "url": "https://yt3.ggpht.com/ytc/AKedOLQXnu5ttMx7MCv2yhqhAgOQfrG8B5UUusb1jgHdww=s68-c-k-c0x00ffffff-no-rj",
                        "width": 68,
                        "height": 68
                    }
                ],
                "link": "https://www.youtube.com/channel/UCSY2_WP6dt87_dtdnv7hcsQ"
            },
            "accessibility": {
                "title": "Samsung TROLL Apple AGAIN! (All 9 New Ads) by Mobile Tech Point 3 years ago 5 minutes, 3 seconds 1,230,150 views",
                "duration": "5 minutes, 3 seconds"
            },
            "link": "https://www.youtube.com/watch?v=cbOB0_duN1s",
            "shelfTitle": null
        },
        {
            "type": "video",
            "id": "xPxj67OqmvM",
            "title": "My Gibson Rant Video|Why Gibson is becoming a Troll company|",
            "publishedTime": "8 months ago",
            "duration": "8:17",
            "viewCount": {
                "text": "754 views",
                "short": "754 views"
            },
            "thumbnails": [
                {
                    "url": "https://i.ytimg.com/vi/xPxj67OqmvM/hq720.jpg?sqp=-oaymwEcCOgCEMoBSFXyq4qpAw4IARUAAIhCGAFwAcABBg==&rs=AOn4CLC-lT9wDgvXl99GZIqx2NBNvZDu-w",
                    "width": 360,
                    "height": 202
                },
                {
                    "url": "https://i.ytimg.com/vi/xPxj67OqmvM/hq720.jpg?sqp=-oaymwEcCNAFEJQDSFXyq4qpAw4IARUAAIhCGAFwAcABBg==&rs=AOn4CLC9xqVPJNvzLbU9C1UwHyvXkY1Xfg",
                    "width": 720,
                    "height": 404
                }
            ],
            "richThumbnail": {
                "url": "https://i.ytimg.com/an_webp/xPxj67OqmvM/mqdefault_6s.webp?du=3000&sqp=CNX-yYwG&rs=AOn4CLBf7MOMyYckmjdaWEY1iU-2qig3Ew",
                "width": 320,
                "height": 180
            },
            "descriptionSnippet": [
                {
                    "text": "I am so sick of Gibson announcing announcements, teasing things that they don't have ready and guitars that won't come out for\u00a0..."
                }
            ],
            "channel": {
                "name": "Three Chord Dave",
                "id": "UCm1D3veNJRjVfT5RXTLWPwA",
                "thumbnails": [
                    {
                        "url": "https://yt3.ggpht.com/ytc/AKedOLTtdGz7K4R-wrTCsg52QeBcaIv1fw8-ZI55Eg5W7w=s68-c-k-c0x00ffffff-no-rj",
                        "width": 68,
                        "height": 68
                    }
                ],
                "link": "https://www.youtube.com/channel/UCm1D3veNJRjVfT5RXTLWPwA"
            },
            "accessibility": {
                "title": "My Gibson Rant Video|Why Gibson is becoming a Troll company| by Three Chord Dave 8 months ago 8 minutes, 17 seconds 754 views",
                "duration": "8 minutes, 17 seconds"
            },
            "link": "https://www.youtube.com/watch?v=xPxj67OqmvM",
            "shelfTitle": null
        }
    ]
}
```
<!--END_RESPONSE-->

</details>

---
### **2) Google Search** :mag:
Searches Google.
##### Usage:  

```sh
https://api.mrdeveloper.ga/google?query={your-query-here}
```

**:octocat: Required Args**

`query`: `str` Query to be searched

**:electron: Optional Supported Args**

`limit`: `integer` No. of results to get **(Defaults to 50)** :neutral_face: **(Maximum 100)**
##### **Example:** https://api.mrdeveloper.ga/google?query=India&limit=50
#####
<details><summary>Example Output</summary>

<!--START_RESPONSE-->
```json
{
    "success": true,
    "query": "India",
    "limit": 50,
    "results": [
        {
            "title": "India - Wikipedia",
            "description": "India, officially the Republic of India (Hindi: Bh\u0101rat Ga\u1e47ar\u0101jya), is a country in South Asia. It is the seventh-largest country by area, the second-most\u00a0...",
            "link": "https://en.wikipedia.org/wiki/India"
        },
        {
            "title": "India | History, Map, Population, Economy, & Facts | Britannica",
            "description": "6 days ago \u2014 India, country that occupies the greater part of South Asia. It is a constitutional republic that represents a highly diverse population\u00a0...",
            "link": "https://www.britannica.com/place/India"
        },
        {
            "title": "India - United States Department of State",
            "description": "The United States and India have shared interests in promoting global security, stability, and economic prosperity through trade, investment, and connectivity.",
            "link": "https://www.state.gov/countries-areas/india/"
        },
        {
            "title": "National Portal of India",
            "description": "22 hours ago \u2014 National Portal of India provides a single-window access to information and services that are electronically delivered from all Government Departments,\u00a0...",
            "link": "https://www.india.gov.in/"
        },
        {
            "title": "Incredible India | English",
            "description": "India has a myriad of landscapes, great heritage and culture, varied flora and fauna. The country is the most preferred tourist destinations for tourists\u00a0...",
            "link": "https://www.incredibleindia.org/"
        },
        {
            "title": "India - Statistics, Rankings, News | U.S. News Best Countries",
            "description": "Located in South Asia, India sits on a peninsula that extends between the Bay of Bengal and the Arabian Sea. The country, the birthplace of Hinduism and\u00a0...",
            "link": "https://www.usnews.com/news/best-countries/india"
        },
        {
            "title": "MoHFW | Home",
            "description": "COVID-19 INDIA as on : 15 November 2021, 08:00 IST (GMT+5:30) ... Procedure (SOP) for COVID-19 Management- International Cruise Ships at major Indian Ports\u00a0...",
            "link": "https://mohfw.gov.in/"
        },
        {
            "title": "India : Development news, research, data | World Bank",
            "description": "With a population of more than 1.2 billion, India is the world's largest democracy. Over the past decade, the country's integration into the global economy\u00a0...",
            "link": "https://www.worldbank.org/en/country/india"
        },
        {
            "title": "India - BBC News",
            "description": "India and China are being criticised for forcing a key part of the Glasgow climate deal to be ... Coal supplies power to around 70% of India's electric grid\u00a0...",
            "link": "https://www.bbc.com/news/world/asia/india"
        },
        {
            "title": "India | World | The Guardian",
            "description": "5 hours ago \u2014 India \u00b7 The politics sketch Boris Johnson confirms that Cop26 went well \u2013 and was definitely in Glasgow. John Crace. Published: 3:17 PM.",
            "link": "https://www.theguardian.com/world/india"
        },
        {
            "title": "India.com: Top Headlines from the USA and Top national stories",
            "description": "3 hours ago \u2014 India.com provides the latest US news, top stories, photos and videos from around the nation (USA).",
            "link": "https://www.india.com/"
        },
        {
            "title": "India | Country Page | World | Human Rights Watch",
            "description": "In August 2019, the government revoked the constitutional autonomy of India's only Muslim-majority Jammu and Kashmir state and split it into two federally\u00a0...",
            "link": "https://www.hrw.org/asia/india"
        },
        {
            "title": "India | Today's latest from Al Jazeera",
            "description": "6 hours ago \u2014 India opens to fully vaccinated foreign tourists. This is the first time since March 2020 that India has allowed foreign tourists on commercial flights to enter\u00a0...",
            "link": "https://www.aljazeera.com/where/india/"
        },
        {
            "title": "India COVID - Coronavirus Cases - Worldometer",
            "description": "4 hours ago \u2014 India Coronavirus update with statistics and graphs: total and new cases, deaths per day, mortality and recovery rates, current active cases, recoveries,\u00a0...",
            "link": "https://www.worldometers.info/coronavirus/country/india/"
        },
        {
            "title": "India - The New York Times",
            "description": "16 hours ago \u2014 India is the second most populous country in the world, its largest democracy and home to vast diversity in geography, climate, culture, language and\u00a0...",
            "link": "https://www.nytimes.com/topic/destination/india"
        },
        {
            "title": "Randy Arozarena and Jonathan India Win Rookie of the Year",
            "description": "2 hours ago \u2014 Tampa Bay's Randy Arozarena and Cincinnati's Jonathan India stood out in a deep rookie class for both leagues.",
            "link": "https://www.nytimes.com/2021/11/15/sports/baseball/arozarena-india-rookie-of-the-year.html"
        },
        {
            "title": "India - latest news, breaking stories and comment - The ...",
            "description": "17 hours ago \u2014 Indian police constable suspended for receiving kiss from woman \u00b7 News \u00b7 India opens to vaccinated foreign tourists after 18 months.",
            "link": "https://www.independent.co.uk/topic/india"
        },
        {
            "title": "India news - Covid-19 coverage, breaking news, video ... - CNN",
            "description": "View the latest India news, videos, headlines and opinion on CNN.com.",
            "link": "https://www.cnn.com/india"
        },
        {
            "title": "Welcome to Air India",
            "description": "22 hours ago \u2014 Air India, the National Carrier of India, offers connections to over 70 international and 100 domestic destinations for your travel plan.",
            "link": "https://www.airindia.in/"
        },
        {
            "title": "India allows quarantine-free travel for tourists from 99 countries",
            "description": "21 hours ago \u2014 After shutting its borders to international visitors for 20 months due to the pandemic, India will now allow fully vaccinated foreign\u00a0...",
            "link": "https://www.cnbc.com/2021/11/15/india-allows-quarantine-free-travel-for-tourists-from-99-countries.html"
        },
        {
            "title": "India Country Profile - National Geographic Kids",
            "description": "India is part of the continent of Asia. Most of India forms a peninsula, which means it is surrounded by water on three sides. The world's highest mountain\u00a0...",
            "link": "https://kids.nationalgeographic.com/geography/countries/article/india"
        },
        {
            "title": "India: Introduction >> globalEDGE",
            "description": "India is located in Southern Asia bordering the Arabian Sea and the Bay of Bengal. Neighboring countries include Bangladesh, Bhutan, Burma, China, Nepal,\u00a0...",
            "link": "https://globaledge.msu.edu/countries/india"
        },
        {
            "title": "Home | Ministry Of Tourism | Government of India",
            "description": "22 hours ago \u2014 Awards are also given to the meritorious students of the institutes of Hotel Management and Indian Institute of Tourism & Travel Management. National Tourism\u00a0...",
            "link": "https://tourism.gov.in/"
        },
        {
            "title": "Election Commission of India",
            "description": "Official website of the Election Commission of India.",
            "link": "https://eci.gov.in/"
        },
        {
            "title": "India | The Commonwealth",
            "description": "India mainly sits on a vast peninsula in Southern Asia, surrounded by the Arabian Sea and the Bay of Bengal. In the north, it borders countries including\u00a0...",
            "link": "https://thecommonwealth.org/our-member-countries/india"
        },
        {
            "title": "Reserve Bank of India",
            "description": "3 hours ago \u2014 Conversion/Switch of Government of India (GoI)'s Securities ... Reserve Bank of India Commits to Support Greening India's Financial System- NGFS.",
            "link": "https://www.rbi.org.in/"
        },
        {
            "title": "India travel advice - GOV.UK",
            "description": "5 days ago \u2014 Latest travel advice for India including how coronavirus (COVID-19) is affecting travel and entry requirements at this time as well as\u00a0...",
            "link": "https://www.gov.uk/foreign-travel-advice/india"
        },
        {
            "title": "Times of India: News - Latest News, Breaking News ...",
            "description": "Top News in India: Read Latest News on Sports, Business, Entertainment, Blogs and Opinions from leading columnists. Times of India brings the Breaking News\u00a0...",
            "link": "https://timesofindia.indiatimes.com/"
        },
        {
            "title": "Government of India, Department of Post",
            "description": "India Post, Ministry of Communication & Technology.",
            "link": "https://www.indiapost.gov.in/"
        },
        {
            "title": "Home - Unique Identification Authority of India | Government of ...",
            "description": "UIDAI is mandated to issue an easily verifiable 12 digit random number as Unique Identity - Aadhaar to all Residents of India.",
            "link": "https://uidai.gov.in/"
        },
        {
            "title": "India Visa Online",
            "description": "Authorized Portal for Visa Application to India ... form of a national passport with a valid visa from an Indian Mission/Post or eVisa (Limited Categories)\u00a0...",
            "link": "https://indianvisaonline.gov.in/"
        },
        {
            "title": "India - AP News",
            "description": "20 hours ago \u2014 Police: India rebels kill 5 troops, 2 others in border state. By WASBIR HUSSAINNovember 13, 2021. GAUHATI, India (AP) \u2014 At least five Indian soldiers and\u00a0...",
            "link": "https://apnews.com/hub/india"
        },
        {
            "title": "Census of India Website : Office of the Registrar General ...",
            "description": "Office of the Registrar General & Census Commissioner, India (ORGI), Provisional Population Totals Paper 2 of India & States/UTs.",
            "link": "https://censusindia.gov.in/"
        },
        {
            "title": "India Today",
            "description": "3 hours ago \u2014 Check out the latest news from India and around the world. Latest India news on Bollywood, Politics, Business, Cricket, Technology and Travel.",
            "link": "https://www.indiatoday.in/"
        },
        {
            "title": "Union Bank of India",
            "description": "Union Bank of India is one of the largest government-owned banks of India, we present you range of Netbanking, Corporate, NRI Banking Services and etc at\u00a0...",
            "link": "https://www.unionbankofindia.co.in/"
        },
        {
            "title": "US-India Business Council: USIBC",
            "description": "The U.S.-India Business Council. We make business between the United States and India easier, more efficient, and more profitable. We are focused on growth for\u00a0...",
            "link": "https://www.usibc.com/"
        },
        {
            "title": "Ministry of External Affairs, Government of India",
            "description": "22 hours ago \u2014 This is the official portal of External Affairs Ministry, Government of India. You can find information related Statements, Interviews, Press Releases,\u00a0...",
            "link": "https://www.mea.gov.in/"
        },
        {
            "title": "AIIMS - All India Institute Of Medical Science",
            "description": "Prof. Randeep Guleria, Director \u00b7 Medical No.1, All India Institute of Medical Sciences, New Delhi \u00b7 The world's smallest and cheapest ventilator can help\u00a0...",
            "link": "https://aiims.edu/"
        },
        {
            "title": "India - Wikitravel",
            "description": "India is the largest country in the South Asia Region, located primarily in the center of the subcontinent. The country shares land borders with Pakistan to\u00a0...",
            "link": "https://wikitravel.org/en/India"
        },
        {
            "title": "Make In India",
            "description": "11 hours ago \u2014 ... Explore: Scheme on 'Enhancement of Competitiveness in Indian Capital Goods Sector' 12-11-2021; Explore: Indian Army inks MoU with Bhaskaracharya\u00a0...",
            "link": "https://www.makeinindia.com/"
        },
        {
            "title": "Netflix India - YouTube",
            "description": "Netflix is the world's leading streaming entertainment service with 204 million paid memberships in over 190 countries enjoying TV series, documentaries and\u00a0...",
            "link": "https://www.youtube.com/channel/UCZSNzBgFub_WWil6TOTYwAg?feature=emb_ch_name_ex"
        },
        {
            "title": "SBI - Loans, Accounts, Cards, Investment, Deposits, Net ...",
            "description": "State Bank of India, a financial powerhouse, provides banking services like saving account, fixed deposits, personal loans, education loan, SME loans,\u00a0...",
            "link": "https://sbi.co.in/web/personal-banking"
        },
        {
            "title": "India - Statistics & Facts | Statista",
            "description": "Oct 20, 2021 \u2014 Discover all relevant statistics and facts on India, like total population or GDP, now on statista.com!",
            "link": "https://www.statista.com/topics/754/india/"
        },
        {
            "title": "Central Bank of India",
            "description": "Apply Online: Online Savings Account opening \u00b7 Online Locker Application \u00b7 Online Loan. Fund Transfers: UPI \u00b7 IMPS \u00b7 NEFT \u00b7 RTGS.",
            "link": "http://www.centralbankofindia.co.in/"
        },
        {
            "title": "Public Health Foundation of India (PHFI)",
            "description": "Launched by Public Health Foundation of India (PHFI), Indian Institute of Public Health Gandhinagar (IIPHG) aims to strengthen the overall health system in the\u00a0...",
            "link": "https://phfi.org/"
        },
        {
            "title": "The Board of Control for Cricket in India",
            "description": "15 hours ago \u2014 Indian Cricket Today. Live Matches \u00b7 Article. India's squad for Tests\u00a0...",
            "link": "https://www.bcci.tv/"
        },
        {
            "title": "Travel advice and advisories for India - Travel.gc.ca",
            "description": "Nov 1, 2021 \u2014 Flights from India. Direct flights from India to Canada have resumed. Passengers eligible to enter Canada and travelling on those flights must:.",
            "link": "https://travel.gc.ca/destinations/india"
        },
        {
            "title": "India's top court orders 'work from home' over pollution in capital",
            "description": "14 hours ago \u2014 NEW DELHI, Nov 15 (Reuters) - India's Supreme Court told authorities on Monday to shut offices in the capital and nearby cities,\u00a0...",
            "link": "https://www.reuters.com/world/india/indias-top-court-orders-work-home-over-pollution-capital-2021-11-15/"
        },
        {
            "title": "Latest India News | Today's Top Stories | Reuters",
            "description": "17 hours ago \u2014 India \u00b7 Africa \u00b7 Americas \u00b7 Asia Pacific \u00b7 China \u00b7 Europe \u00b7 India \u00b7 Middle East \u00b7 United Kingdom.",
            "link": "https://www.reuters.com/world/india"
        },
        {
            "title": "CARE India - Top Indian NGO | Charity Foundations in India ...",
            "description": "CARE India is one of the top trusted NGO in India, working for women empowerment, Health & child education in rural areas. Care India- charity foundations\u00a0...",
            "link": "https://www.careindia.org/"
        }
    ]
}
```
<!--END_RESPONSE-->

</details>

---
#### **3) Google PlayStore Search** :mag:
Searches Apps and Games Details in Google Play Store
###### Usage:
```sh
https://api.mrdeveloper.ga/playstore?query={your-query-here}
```

**:octocat: Required Args**

`query`: `str` Query to be searched

##### **Example:** https://api.mrdeveloper.ga/playstore?query=Telegram
#####
<details><summary>Example Output</summary>

<!--START_RESPONSE-->
```json
{
    "success": true,
    "query": "Telegram",
    "results": [
        {
            "title": "Telegram",
            "description": "Pure instant messaging \u2014 simple, fast, secure, and synced across all your devices. One of the world's top 10 most downloaded apps with over 500 million active users.\r\n\r\nFAST: Telegram is the fastest messaging app on the market, connecting people via a unique, distributed network of data centers around the globe.\r\n\r\nSYNCED: You can access your messages from all your phones, tablets and computers at once. Telegram apps are standalone, so you don\u2019t need to keep your phone connected. Start typing on one device and finish the message from another. Never lose your data again.\r\n\r\nUNLIMITED: You can send media and files, without any limits on their type and size. Your entire chat history will require no disk space on your device, and will be securely stored in the Telegram cloud for as long as you need it. \r\n\r\nSECURE: We made it our mission to provide the best security combined with ease of use. Everything on Telegram, including chats, groups, media, etc. is encrypted using a combination of 256-bit symmetric AES encryption, 2048-bit RSA encryption, and Diffie\u2013Hellman secure key exchange. \r\n\r\n100% FREE & OPEN: Telegram has a fully documented and free API for developers, open source apps and verifiable builds to prove the app you download is built from the exact same source code that is published. \r\n\r\nPOWERFUL: You can create group chats with up to 200,000 members, share large videos, documents of any type (.DOCX, .MP3, .ZIP, etc.) up to 2 GB each, and even set up bots for specific tasks. Telegram is the perfect tool for hosting online communities and coordinating teamwork.\r\n\r\nRELIABLE: Built to deliver your messages using as little data as possible, Telegram is the most reliable messaging system ever made. It works even on the weakest mobile connections. \r\n\r\nFUN: Telegram has powerful photo and video editing tools, animated stickers and emoji, fully customizable themes to change the appearance of your app, and an open sticker/GIF platform to cater to all your expressive needs.\r\n\r\nSIMPLE: While providing an unprecedented array of features, we take great care to keep the interface clean. Telegram is so simple you already know how to use it.\r\n\r\nPRIVATE: We take your privacy seriously and will never give any third parties access to your data. You can delete any message you ever sent or received for both sides, at any time and without a trace. Telegram will never use your data to show you ads.\r\n\r\nFor those interested in maximum privacy, Telegram offers Secret Chats. Secret Chat messages can be programmed to self-destruct automatically from both participating devices. This way you can send all types of disappearing content \u2014 messages, photos, videos, and even files. Secret Chats use End-to-End Encryption to ensure that a message can only be read by its intended recipient.\r\n\r\nWe keep expanding the boundaries of what you can do with a messaging app. Don\u2019t wait years for older messengers to catch up with Telegram \u2014 join the revolution today.",
            "descriptionHTML": "Pure instant messaging \u2014 simple, fast, secure, and synced across all your devices. One of the world&#39;s top 10 most downloaded apps with over 500 million active users.<br><br>FAST: Telegram is the fastest messaging app on the market, connecting people via a unique, distributed network of data centers around the globe.<br><br>SYNCED: You can access your messages from all your phones, tablets and computers at once. Telegram apps are standalone, so you don\u2019t need to keep your phone connected. Start typing on one device and finish the message from another. Never lose your data again.<br><br>UNLIMITED: You can send media and files, without any limits on their type and size. Your entire chat history will require no disk space on your device, and will be securely stored in the Telegram cloud for as long as you need it. <br><br>SECURE: We made itour mission to provide the best security combined with ease of use. Everything on Telegram, including chats, groups, media, etc. is encrypted using a combination of 256-bit symmetric AES encryption, 2048-bit RSA encryption, and Diffie\u2013Hellman secure key exchange. <br><br>100% FREE &amp; OPEN: Telegram has a fully documented and free API for developers, open source apps and verifiable builds to prove the app you download is built from the exact same source code that is published. <br><br>POWERFUL: You can create group chats with up to 200,000 members, share large videos, documents of any type (.DOCX, .MP3, .ZIP, etc.) up to 2 GB each, and even set up bots for specific tasks. Telegram is the perfect tool for hosting online communities and coordinating teamwork.<br><br>RELIABLE: Built to deliver your messages using as little data as possible, Telegram is the most reliable messaging system ever made. It works even on the weakest mobile connections. <br><br>FUN: Telegram has powerful photo and video editing tools, animated stickers and emoji, fully customizable themes to change the appearance of your app, and an open sticker/GIF platform to cater to all your expressive needs.<br><br>SIMPLE: While providing an unprecedented array of features, we take great care to keep the interface clean. Telegram is so simple you already know how to use it.<br><br>PRIVATE: We take your privacy seriously and will never give any third parties access to your data. You can delete any message you ever sent or received for both sides, at any time and without a trace. Telegram will never use your data to show you ads.<br><br>For those interested in maximum privacy, Telegram offers Secret Chats. Secret Chat messages can be programmed to self-destruct automatically from both participating devices. This way you can send all types of disappearing content \u2014 messages, photos, videos, and even files. Secret Chats use End-to-End Encryption to ensure that a message can only be read by its intended recipient.<br><br>We keep expanding the boundaries of what you can do with a messaging app. Don\u2019t wait years for older messengers to catch up with Telegram \u2014 join the revolution today.",
            "summary": "Telegram is a messaging app with a focus on speed and security.",
            "summaryHTML": "Telegram is a messaging app with a focus on speed and security.",
            "installs": "1,000,000,000+",
            "minInstalls": 1000000000,
            "score": 4.4175158,
            "ratings": 9082912,
            "reviews": 102326,
            "histogram": [
                782248,
                193540,
                374951,
                831097,
                6901076
            ],
            "price": 0,
            "free": true,
            "currency": "USD",
            "sale": false,
            "saleTime": null,
            "originalPrice": null,
            "saleText": null,
            "offersIAP": false,
            "inAppProductPrice": null,
            "size": "Varies with device",
            "androidVersion": "Varies",
            "androidVersionText": "Varies with device",
            "developer": "Telegram FZ-LLC",
            "developerId": "Telegram+FZ-LLC",
            "developerEmail": "support@telegram.org",
            "developerWebsite": "https://telegram.org",
            "developerAddress": null,
            "privacyPolicy": "https://telegram.org/privacy",
            "developerInternalID": "7766252821327259628",
            "genre": "Communication",
            "genreId": "COMMUNICATION",
            "icon": "https://play-lh.googleusercontent.com/ZU9cSsyIJZo6Oy7HTHiEPwZg0m2Crep-d5ZrfajqtsH-qgUXSqKpNA2FpPDTn-7qA5Q",
            "headerImage": "https://play-lh.googleusercontent.com/pgiel6OzR01do2sPxONlteJ5_GAwD6W-JpiF98hdns3XinShKZkziUd1B8sG-8qa",
            "screenshots": [
                "https://play-lh.googleusercontent.com/wlwY1vowGxTrvQMRDHJD21iYBG7S_E09QbKPY-L6dqEc4UxCi0fDQiNuCBonFYED1yU",
                "https://play-lh.googleusercontent.com/xdjWKko-a2DFtICA6tfP0vXSBIDTFl_iprhVQb9HnS-rGjyR1wZckqM721qHsF-2z0U",
                "https://play-lh.googleusercontent.com/NaeXtT-aGP9_R8LROs3XyWVc6eU7sxYuuywNwg3c99AjRtj6cCoPaJynhP0t8uynF6hm",
                "https://play-lh.googleusercontent.com/J5JG9T92CSZopWKloI00_DsmyQprRvEwItBwPkESjcAlIKy5v4ae3T4pmbH1sWFf3RTQ",
                "https://play-lh.googleusercontent.com/9HoCw2kOVFD504YpjDyk1Aa5WtcbDsxS_wesF-yT-5iHEvRgHZXT22g2clFXGGwoCTOt",
                "https://play-lh.googleusercontent.com/bDGf2oHe1y_uaFE6XCh2kYicn3-1yiLMTI5hae9s5zMaNPzOpj04An1URWQyw5m5JhA",
                "https://play-lh.googleusercontent.com/v0zodHEHUcMgUZSK490M9L5c3Grk5pkDHL-TTdfQK3098Wg0W2bxbK1-cmgN9aKEuQ",
                "https://play-lh.googleusercontent.com/-4x3oxK3bMWXTpwPrlai_HYHcHnH_sa8KvYj5KvYPwjSZV7rsg4kpIafYhfnRvBsUtc"
            ],
            "video": null,
            "videoImage": null,
            "contentRating": "Mature 17+",
            "contentRatingDescription": null,
            "adSupported": null,
            "containsAds": false,
            "released": "Sep 6, 2013",
            "updated": 1636792427,
            "version": "8.2.7",
            "recentChanges": null,
            "recentChangesHTML": null,
            "comments": [
                "Lately I've been having issues where I try to call someone and it is stuck on waiting... followed by \"failed to connect.\" I've tried everything: clear cache and data, restart my phone, reinstall... nothing!!! Really sad. This was my favorite messaging app.",
                "Unable to Verify my Phone or Ipad. I was excited about trying this app, but I have been unable to even access it. I downloaded the app. Then I installed the app. Then the app asks for a code that will be sent to me via text or phone, but the code never arrives. So, I am unable to move forward with using the app. I sent several messages to support, but I haven't received a response.",
                "It's totally great, I think it's the best app in this section But I decreased one star because of two things: First, please do the same unblocking thing that you did in russia, for iran Second, it would be great to have the delivered thing that is in for example whatsapp, it's really a handy thing and I'd be glad to see it here two, to see that the Telegram has the advantage in almost every single thing ;)",
                "Best way to communicate with friends, get news, and follow people without restrictions. Telegram is also a good replacement for Twitter and Facebook as group and channels give you social interaction features. Way better and secure than Messenger and Whatsapp, both of those owned by screwy Facebook.",
                "Only bad thing about this app is that videos take too long to download/play. With 150mbps, it takes about 2 minutes per 100mb in size. But I can download files from the internet, 1gb per minute.",
                "I use Nokia 7.2. Telegram keeps on asking me to go through the verification process every time I open it and times me out due to too many attempts. I have reinstalled at latest 3 times and the issue persists.",
                "Great app, will add 5th star when issues with last update are fixed. Can no longer find or share my media from app. Everything has become buggy and slow. First time having any issues. But the issues are persisting. Please fix.",
                "Telegram support for wear OS is no longer! The whole reason I bought a smart watch was so I could initiate conversations with people from my watch! Bring telegram back to wear os! Telegram was the only good platform on wear OS to talk to people over seas!",
                "Would love to give the app 5 stars, BUUUUUT... Experiencing the same problem a lot of people seem to be experiencing... Can't download media to phone... And now I don't even get the \"photo downloaded to gallery\" prompt... Please kindly patch this issue, devs... Your app is great, but something like this is going to tank your ratings.",
                "Great messaging app over all, highly recommended. Not5 stars though because sometimes there are connection issues when in calls: delays, calls wouldn't get through when answered, gets stuck at reconnecting,... even though both callers have good reception. also, call quality drops drastically when it's a video call. please fix asap.",
                "Android 11; It does not matter if the \"save to gallery\" is on or off in \"chat settings\", Because this option does not work.\ud83e\udd14 Why is there this option?\ud83d\ude10",
                "Fun & easy to use messaging app with lots of features to be able to personalize with fun free animated stickers, gifs, etc. Meeting new people with similar interests is fun exciting!",
                "Used to love this app, but ever since yesterday I haven't been able to save pictures to my gallery. And yes, I have the \"Save to Gallery\" set to on and it still doesn't work for me. Until this gets fixed, I'm lowering my ranking to two stars.",
                "After using this app for years I'm deleting it. I'm so beyond frustrated with this craptastical system that locks a user out of their account if they log in/out too many times. If there isn't any suspicious activity I should be allowed to log in and out of my account as many times as I would like without any sort of penalty. Then, there appears to be no rhyme or reason for how long someone's locked out of their account.",
                "Updated again: there's been yet another update to telegram and my app is still sending me multiple notifications of the same message. Your app is still broken. You don't have anywhere in the app or on your website to report bugs. And you don't answer emails regarding bugs. FIX YOUR DAMN APP!!!",
                "Telegram is the best app for chat but since the last update (the app messaged me and said i should update for bug fixes and improvements) all of my media (all of my pic, music and ...) are deleted in the app but they are in my mobile file and it have a lots of bugs Before the update i didn't have any bugs\ud83e\udd72 And it's so slow since the last update I had a lots of important thing in the app and i trust the app and put it in I hape they fix it soon",
                "I like the ease of messages, the personal background options, stickers, etc, but the group search is abysmal and the army of spam bots, prostitutes, and drug dealers is horrific.",
                "I think this is a bug, when I save pictures or videos it makes difference telegram albums in my gallery, it use to put them in one telegram album.",
                "The app is great i use it every day, i love all the customizable options too. The only issue i have with the app right now is that pictures will not save to my device im sure this is just a bug from the new update though and will be e fixed soon",
                "Can no longer save photos to my gallery which is quite frustrating and I'll most likely stop using the app and use Whatsapp if this isn't fixed soon.",
                "Love the app. Such creativity and function. Double underscore on either side of your text for italics. Double asterix for bold. Etc. Very flexible.",
                "Best app ever\ud83d\udc4c\ud83c\udfaf The feature that I want to see is something like chatting sticker. So the Idea is you write a short message then you choose a sticker, the sticker will be sent and the text is written inside the sticker with animation.",
                "Very good app, but my current problem is that Pictures No longer save to the \"Telegram\" Album and instead to the \"Pictures\" Album! Either fix this or give me a way to change it. It's annoying!",
                "Edit: this new update is trash, the save to gallery option doesn't work anymore, what's up with that? I can't save photos that anyone sends me which I count on, so please fix",
                "Can you please give us an option to completely disable the account auto self-destruct? I'll give 5 stars if you do. Otherwise, pretty reliable and takes good pics and videos. Love the trim option for videos, too.",
                "This update saves download files in android>data>org.telegra....>cache. Android devices can't have the access to data folder and users gotta use a third party app to see the files. But this savind path makes my files being simply deleted by clearing cache. I lost tons of datas because of this stupid update",
                "The latest update moved the downloads into a folder that is hidden from the gallery. All this has done is make users miserable and the app a pain to use. One star until the reverse this idiotic mistake.",
                "The last update removed all my downloaded media and cleared the cache and I redownloaded my media again but as soon as I close the app it happens again and It cleares my cache automatically And also when I hit save to Gallery or Save to music nothing happens And I can't find the Telegram folder on my phone anymore I'm on Android Device btw",
                "Not able to save media to gallery. It will say saved but no where to be found. Please fix asap as I use this app to store marketing graphics and videos and I'm unable to get and use them.",
                "Most recent update doesn't let you save pictures at all. Save to gallery option for pictures doesn't work.",
                "I am a huge fan of the mission and reason telegram exists. I think they have an amazing app with so many great features, some even rivaling other chat apps. Chat on!",
                "Seems almost dangerous. The support team doesn't respond to anything, and I regularly get spam messages, deletion of my files, invites to dangerous groups, and people messaging me who are only miles away in real life (despite me blocking this from happening using settings).",
                "For last 5 days, downloaded videos are not visible in the telegram folder. So, i reinstalled the telegram app, now telegram folders are not generated niether I can find any downloaded videos.",
                "Great app overall it has many awesome features. I only gave it 4 stars because it would be better if it had the option for daily stories included.",
                "Great for the most part! Except with the newest update, I can't save pictures to my device from others or groups :( and my own pictures aren't saving to my device either if I take them using TG like they used to.",
                "Probably the best messaging app I've ever used. After migrating from WhatsApp, things are better on Telegram. Like the chat stickers, which is used as emojis. I use this messaging app on all of my devices (Phone and PC). l would definitely recommend this to my friends.",
                "See this app is coolest than the rest out there but the problem is that downloaded images and vids aren't saved in gallery.pls do something about it...",
                "You seriously removed the downloading data and media to the Telegram folder?! That was the entire purpose of this application!!!! For SHARING MEDIA!!!! Without it, this app is worthless. This app is terrible for media sharing now without the downloads being accessible to the users!",
                "Great app. 6 yr user. I have met many good friends all over the world Calls are good no complaints.",
                "I'm having issues since the last update. It's no longer letting me save pictures to my gallery. I really hope this is fixed soon."
            ],
            "editorsChoice": false,
            "similarApps": [
                "org.thunderdog.challegram",
                "com.discord",
                "com.instagram.android",
                "us.zoom.videomeetings",
                "com.whatsapp"
            ],
            "moreByDeveloper": [
                "org.thunderdog.challegram",
                "org.telegram.wastickers.bestof",
                "org.telegram.wastickers.halloween"
            ],
            "appId": "org.telegram.messenger",
            "url": "https://play.google.com/store/apps/details?id=org.telegram.messenger&hl=en&gl=us"
        }
    ]
}
```
<!--END_RESPONSE-->

</details>

---
#### **4) Python PIP Details Search** :mag:  
Searches the details about the python module
##### Usage:
```sh
https://api.mrdeveloper.ga/pypip?query={python-module-name-here}
```

**:octocat: Required Args**

`query`: `str` Python Module name
##### **Example:** https://api.mrdeveloper.ga/pypip?query=html5lib
#####
<details><summary>Example Output</summary>

<!--START_RESPONSE-->
```json
{
    "sucess": true,
    "query": "html5lib",
    "results": [
        {
            "name": "html5lib",
            "version": "1.1",
            "license": "MIT License",
            "description": "HTML parser based on the WHATWG HTML specification",
            "size": "0.112173 MB",
            "uploadTime": "2020-06-22T23:32:36",
            "author": "",
            "authorEmail": "",
            "keywords": "",
            "requirements": [
                "six (>=1.9)",
                "webencodings",
                "genshi ; extra == 'all'",
                "chardet (>=2.2) ; extra == 'all'",
                "lxml ; (platform_python_implementation == 'CPython') and extra == 'all'",
                "chardet (>=2.2) ; extra == 'chardet'",
                "genshi ; extra == 'genshi'",
                "lxml ; (platform_python_implementation == 'CPython') and extra == 'lxml'"
            ],
            "minPyVersion": ">=2.7, !=3.0.*, !=3.1.*, !=3.2.*, !=3.3.*, !=3.4.*",
            "homepage": "https://github.com/html5lib/html5lib-python",
            "bugTrackURL": null,
            "docsURL": null,
            "pypiURL": "https://pypi.org/project/html5lib/",
            "releaseURL": "https://pypi.org/project/html5lib/1.1/",
            "projectURLS": {
                "Homepage": "https://github.com/html5lib/html5lib-python"
            }
        }
    ]
}
```
<!--END_RESPONSE-->

</details>

---

### **5) Web Screenshot** :camera:
Captures Screenshot of a Website from URL
##### Usage:  

```sh
https://api.mrdeveloper.ga/webss?url={your-link-here}
```

**:octocat: Required Args**

`url`: `str` URL whose screenshot is to be taken

**:electron: Optional Supported Args**

`full`: `boolean` Captures full page Screenshot **(No infinite Scrolling)** :neutral_face: **(Defaults to False)**

`format`: `png / pdf` Provides the Screenshot in the selected format **(Defaults to png)**

`Cookie Banners, Ads and Tracking Scripts are disabled by default while taking Screenshots`
##### **Example:** https://api.mrdeveloper.ga/webss?url=https://github.com/MrBotDeveloper/API&full=True&format=png
#####
<details><summary>Example Output</summary>

![WEBSS](https://api.mrdeveloper.ga/webss?url=https://github.com/MrBotDeveloper/API&full=True&format=png)

</details>

---

### **6) Unshort Link** :link:
Unshorts the Given link
##### Usage:  

```sh
https://api.mrdeveloper.ga/unshort?url={your-url-here}
```

**:octocat: Required Args**

`url`: `str` URL to be unshorten

##### **Example:** https://api.mrdeveloper.ga/unshort?url=https://bit.ly/3kRdcYm
#####
<details><summary>Example Output</summary>

<!--START_RESPONSE-->
```json
{
    "success":true,
    "short_url":"https://bit.ly/3kRdcYm",
    "expanded_url":"https://github.com/MrBotDeveloper/API"
}
```
<!--END_RESPONSE-->

</details>

---

### **7) Short Link** :link:
Shorts a Long URL
##### Manually Usage:

```sh
https://api.mrdeveloper.ga/short
```

##### **Example:** https://api.mrdeveloper.ga/short
#####
<details><summary>Example Output</summary>

[![Short URL](https://api.mrdeveloper.ga/webss?url=https://api.mrdeveloper.ga/short&full=True)](https://api.mrdeveloper.ga/short)

</details>

---
##### Usage using code [POST Method]:
To get API please [see this 👀](https://github.com/MrBotDeveloper/API/blob/main/Get-API_KEY.md)
```python
import json
import requests

headers = {
    "User-Agent": "Mozilla/5.0 (Windows NT 10.0; Win64; x64) AppleWebKit/537.36 (KHTML, like Gecko) Chrome/88.0.4324.104 Safari/537.36",
    "content-type": "application/json",
}

data = {
    "url": {your-url-here},
    "api_key": {your-api-key}
}

short_url = requests.post("https://api.mrdeveloper.ga/short", data=json.dumps(data), headers=headers)

print(short_url.json())
```

**:octocat: Required Args**

`url`: `str` URL to be shortened

`api_key`: `str` API Key to get [check this 👀](https://github.com/MrBotDeveloper/API/blob/main/Get-API_KEY.md)
##### **Example:**

```python
import json
import requests

headers = {
    "User-Agent": "Mozilla/5.0 (Windows NT 10.0; Win64; x64) AppleWebKit/537.36 (KHTML, like Gecko) Chrome/88.0.4324.104 Safari/537.36",
    "content-type": "application/json",
}

data = {
    "url": "https://github.com/MrBotDeveloper/API",
    "api_key": "MrDeveloper" #Please Use Your API Key 😕
}

short_url = requests.post("https://api.mrdeveloper.ga/short", data=json.dumps(data), headers=headers)

print(short_url.json())
```
#####
<details><summary>Example Output</summary>

```json
{
    "success": true,
    "api_key": "MrDeveloper",
    "long_url": "https://github.com/MrBotDeveloper/API",
    "short_url": "https://ishort.gq/s8xGf8Q"
}
```

</details>

---
### **8) IMDb** :movie_camera:

#### Search Movie :mag:

##### Usage:
```sh
https://api.mrdeveloper.ga/imdb?query={your-query-here}
```

**:octocat: Required Args**

`query`: `str` Query to be searched
##### **Example:** https://api.mrdeveloper.ga/imdb?query=Eternals
#####
<details><summary>Example Output</summary>

<!--START_RESPONSE-->
```json
{
    "success": true,
    "count": 50,
    "query": "Eternals",
    "results": [
        {
            "imdb_id": "tt9032400",
            "name": "Eternals (2021)",
            "poster": "https://m.media-amazon.com/images/M/MV5BMTExZmVjY2ItYTAzYi00MDdlLWFlOWItNTJhMDRjMzQ5ZGY0XkEyXkFqcGdeQXVyODIyOTEyMzY@.jpg",
            "plot": "The saga of the Eternals, a race of immortal beings who lived on Earth and shaped its history and civilizations....",
            "runtime": "156 min",
            "genre": "Action, Adventure, Fantasy",
            "rating": "6.9",
            "votes": "88,578",
            "directors": "Chlo\u00e9 Zhao",
            "stars": "Gemma Chan, Richard Madden, Angelina Jolie, Salma Hayek",
            "gross": null
        },
        {
            "imdb_id": "tt0338013",
            "name": "Eternal Sunshine of the Spotless Mind (2004)",
            "poster": "https://m.media-amazon.com/images/M/MV5BMTY4NzcwODg3Nl5BMl5BanBnXkFtZTcwNTEwOTMyMw@@.jpg",
            "plot": "When their relationship turns sour, a couple undergoes a medical procedure to have each other erased from their memories....",
            "runtime": "108 min",
            "genre": "Drama, Romance, Sci-Fi",
            "rating": "8.3",
            "votes": "954,715",
            "directors": "Michel Gondry",
            "stars": "Jim Carrey, Kate Winslet, Tom Wilkinson, Gerry Robert Byrne",
            "gross": "$34.40M"
        },
        {
            "imdb_id": "tt4118878",
            "name": "Eternals (2014\u2013 )",
            "poster": "https://m.media-amazon.com/images/M/MV5BNGE3ODRjMDYtMThkOC00MDBiLWJkNGQtMTg0MDcyNDI3ODVmXkEyXkFqcGdeQXVyNjExODE1MDc@.jpg",
            "plot": "Medical student Mark Curry's world is turned upside down when he meets Ike Harris, a man who believes that he is part of a centuries-old race of super-powered beings put here on Earth by ...",
            "runtime": null,
            "genre": "Animation, Adventure, Fantasy",
            "rating": "6.4",
            "votes": "139",
            "directors": null,
            "stars": "Lisa Ann Beley, Trevor Devall, Heather Doerksen, Kirby Morrow",
            "gross": null
        },
        {
            "imdb_id": "tt12063450",
            "name": "To Your Eternity (2021\u2013 )",
            "poster": "https://m.media-amazon.com/images/M/MV5BMWI4MjNjNjgtNWE0MC00NThmLTg0YzEtMDZlODA5NTJhYzY3XkEyXkFqcGdeQXVyMzgxODM4NjM@.jpg",
            "plot": "A lonely boy wandering the Arctic regions of North America meets a wolf, and the two become fast friends, depending on each other to survive the harsh environment. But the boy has a history, and the wolf is more than meets the eye as well....",
            "runtime": "25 min",
            "genre": "Animation, Adventure, Drama",
            "rating": "8.8",
            "votes": "4,765",
            "directors": null,
            "stars": "Jacob Hopkins, Reiji Kawashima, Kenjir\u00f4 Tsuda, Rikako Aikawa",
            "gross": null
        },
        {
            "imdb_id": "tt11228748",
            "name": "The King: Eternal Monarch (2020)",
            "poster": "https://m.media-amazon.com/images/M/MV5BMDk2MDAyNmYtY2VlNS00N2EzLWE4ZDEtMmI0N2ViYzk4ODU4XkEyXkFqcGdeQXVyNjc3MjQzNTI@.jpg",
            "plot": "A modern-day Korean emperor passes through a mysterious portal and into a parallel world, where he encounters a feisty police detective....",
            "runtime": "70 min",
            "genre": "Fantasy, Mystery, Romance",
            "rating": "8.2",
            "votes": "9,131",
            "directors": null,
            "stars": "Lee Min-Ho, Kim Go-eun, Woo Do-Hwan, Kim Kyung-Nam",
            "gross": null
        },
        {
            "imdb_id": "tt6938828",
            "name": "At Eternity's Gate (2018)",
            "poster": "https://m.media-amazon.com/images/M/MV5BOTRmZGJiZjUtMGJjYi00MzZhLTkzYjUtODE1Yjk5ZDRiODhlXkEyXkFqcGdeQXVyODAzODU1NDQ@.jpg",
            "plot": "A look at the life of painter Vincent van Gogh during thetime he lived in Arles and Auvers-sur-Oise, France....",
            "runtime": "111 min",
            "genre": "Biography, Drama",
            "rating": "6.9",
            "votes": "32,346",
            "directors": "Julian Schnabel",
            "stars": "Willem Dafoe, Rupert Friend, Oscar Isaac, Mads Mikkelsen",
            "gross": "$2.29M"
        },
        {
            "imdb_id": "tt0045793",
            "name": "From Here to Eternity (1953)",
            "poster": "https://m.media-amazon.com/images/M/MV5BM2U3YzkxNGMtYWE0YS00ODk0LTk1ZGEtNjk3ZTE0MTk4MzJjXkEyXkFqcGdeQXVyNDk0MDg4NDk@.jpg",
            "plot": "At a U.S. Army base in 1941 Hawaii, a private is cruelly punished for not boxing on his unit's team, while his commanding officer's wife and top aide begin a tentative affair....",
            "runtime": "118 min",
            "genre": "Drama, Romance, War",
            "rating": "7.6",
            "votes": "45,504",
            "directors": "Fred Zinnemann",
            "stars": "Burt Lancaster, Montgomery Clift, Deborah Kerr, Donna Reed",
            "gross": "$30.50M"
        },
        {
            "imdb_id": "tt6849036",
            "name": "The Eternals (2017)",
            "poster": "https://m.media-amazon.com/images/M/MV5BZjU4OWQ5ZGEtY2Q2Mi00MDZlLWFkYjEtZGZhYTExNDBmYmEyXkEyXkFqcGdeQXVyNzI4MDMyMTU@.jpg",
            "plot": "We call those who suffer from the melancholy of eternity, eternals. Convinced that death cannot triumph over their lives, they believe that they are doomed to wander in anticipation of the ...",
            "runtime": "75 min",
            "genre": "Documentary, War",
            "rating": "6.3",
            "votes": "82",
            "directors": "Pierre-Yves Vandeweerd",
            "stars": null,
            "gross": null
        },
        {
            "imdb_id": "tt0382019",
            "name": "Eternal (2004)",
            "poster": "https://m.media-amazon.com/images/M/MV5BMzgxNDI0NzQ3NF5BMl5BanBnXkFtZTcwNDI2MDEzMQ@@.jpg",
            "plot": "Detective Raymond Pope is a detective of questionable morals, searching for his missing wife. His investigation leads him to the wealthy estate of the enigmatic Elizabeth Kane and her young maid Irina....",
            "runtime": "107 min",
            "genre": "Horror, Mystery, Thriller",
            "rating": "4.8",
            "votes": "1,385",
            "directors": "Wilhelm Liebenberg, Federico Sanchez",
            "stars": "Caroline N\u00e9ron, Sarah Manninen, Victoria Sanchez, Conrad Pla",
            "gross": "$0.03M"
        },
        {
            "imdb_id": "tt11454718",
            "name": "The Yin-Yang Master: Dream of Eternity (2020)",
            "poster": "https://m.media-amazon.com/images/M/MV5BYzlmNmNhYWQtYzc4NS00ZmI5LWE2ZjUtNzcxZjdmMjNlMzliXkEyXkFqcGdeQXVyNTI2MzI4NTU@.jpg",
            "plot": "Qing Ming, the Yin-Yang Master, took his master's last wish and went to the Captial Tiandu City to attend the heaven ceremony....",
            "runtime": "132 min",
            "genre": "Action, Drama, Fantasy",
            "rating": "6.5",
            "votes": "4,377",
            "directors": "Jingming Guo",
            "stars": "Mark Chao, Allen Deng, Ziwen Wang, Jessie Li",
            "gross": null
        },
        {
            "imdb_id": "tt10477558",
            "name": "Violet Evergarden: Eternity and the Auto Memories Doll (2019)",
            "poster": "https://m.media-amazon.com/images/M/MV5BZjljM2M1ZTgtZGM4My00OGRkLTliMjAtYzJiZDBkMzQ5ZDkzXkEyXkFqcGdeQXVyMTMxODk2OTU@.jpg",
            "plot": "Violet Evergarden, a former soldier returned from war, comes to teach at a women's academy and changes a young girl's life....",
            "runtime": "90 min",
            "genre": "Animation, Drama, Family",
            "rating": "7.5",
            "votes": "3,774",
            "directors": "Haruka Fujita, Taichi Ishidate",
            "stars": "Yui Ishikawa, Bob Buchholz, Kira Buckland, Reba Buhr",
            "gross": null
        },
     {
            "imdb_id": "tt0156794",
            "name": "Eternity and a Day (1998)",
            "poster": "https://m.media-amazon.com/images/M/MV5BZjUyZjRlMTMtYTA1MS00ZjQwLThlMzgtNzlmZmU4Mjc3YTE1XkEyXkFqcGdeQXVyNjMwMjk0MTQ@.jpg",
            "plot": "Famous writer Alexander is very ill and has little time left to live. He meets a little boy on the street, who is an illegal immigrant from Albania, and goes on a journey with him to take the boy home....",
            "runtime": "137 min",
            "genre": "Drama",
            "rating": "7.9",
            "votes": "11,862",
            "directors": "Theodoros Angelopoulos",
            "stars": "Bruno Ganz, Isabelle Renauld, Fabrizio Bentivoglio, Ahilleas Skevis",
            "gross": "$0.11M"
        },
        {
            "imdb_id": "tt0885520",
            "name": "Eternal Summer (2006)",
            "poster": "https://m.media-amazon.com/images/M/MV5BMTcxNjgxMTk3Nl5BMl5BanBnXkFtZTcwNDM3NTM1MQ@@.jpg",
            "plot": "Two best friends Shane and Jonathan learn more about themselves in an ever evolving sexuality....",
            "runtime": "95 min",
            "genre": "Drama, Romance",
            "rating": "7.1",
            "votes": "2,347",
            "directors": "Leste Chen",
            "stars": "Hsiao-chuan Chang, Ray Chang, Kate Yeung",
            "gross": null
        },
        {
            "imdb_id": "tt8550890",
            "name": "Doom Eternal (2020 Video Game)",
            "poster": "https://m.media-amazon.com/images/M/MV5BZWQ1NjIwYTItMzVjZC00YTgwLTliYTktZjM2ZjI0NGJmZjNmXkEyXkFqcGdeQXVyNzU3Nzk4MDQ@.jpg",
            "plot": "In this sequel to Doom (2016), Hell has taken Earth, so it's up to the Doom Slayer, the ultimate demon-killing machine created by a mystical force, to rip and tear the forces of Hell apart. However, Hell is not alone in this fight....",
            "runtime": null,
            "genre": "Action, Adventure, Fantasy",
            "rating": "8.7",
            "votes": "2,191",
            "directors": "Hugo Martin",
            "stars": "Darin De Paul, Kevin Schon, Jason Spisak, Keith Silverstein",
            "gross": null
        },
        {
            "imdb_id": "tt0158011",
            "name": "The Eternal (1998)",
            "poster": "https://m.media-amazon.com/images/M/MV5BMjA4MDQxOTcwMl5BMl5BanBnXkFtZTcwNTQ4MzMyMQ@@.jpg",
            "plot": "An alcoholic American couple travel to Ireland with their son so he can meet his grandmother but they walk in on their crazed uncle who is in the midst of reviving a centuries-old Druid witch....",
            "runtime": "95 min",
            "genre": "Horror",
            "rating": "4.4",
            "votes": "1,490",
            "directors": "Michael Almereyda",
            "stars": "Rachel O'Rourke, Lois Smith, Alison Elliott, Jared Harris",
            "gross": null
        },
        {
            "imdb_id": "tt5362940",
            "name": "Eternal Beauty (2019)",
            "poster": "https://m.media-amazon.com/images/M/MV5BZWE3ZmZhOTctOTU5Ny00MTM0LWFkZjctYjc0OWI1ZjM3MzQ5XkEyXkFqcGdeQXVyMTkxNjUyNQ@@.jpg",
            "plot": "After Jane falls into a state of despair over her schizophrenia, she encounters new sources of love and life with surprising results....",
            "runtime": "95 min",
            "genre": "Comedy, Drama, Romance",
            "rating": "6.3",
            "votes": "1,625",
            "directors": "Craig Roberts",
            "stars": "Sally Hawkins, Morfydd Clark, Robert Pugh, Natalie O'Neill",
            "gross": null
        },
        {
            "imdb_id": "tt10635042",
            "name": "Sailor Moon Eternal (2021)",
            "poster": "https://m.media-amazon.com/images/M/MV5BZTY1Mzg0YjctOTlmYi00MjhhLTllZmItYTA2Y2Y3ZTdkNmY5XkEyXkFqcGdeQXVyODMyNTM0MjM@.jpg",
            "plot": "When a dark power enshrouds the Earth after a total solar eclipse, the scattered Sailor Guardians must reunite to bring light back into the world....",
            "runtime": "160 min",
            "genre": "Animation, Action, Adventure",
            "rating": "7.1",
            "votes": "1,070",
            "directors": "Chiaki Kon",
            "stars": "Kotono Mitsuishi, Stephanie Sheh, Kate Higgins, Cristina Valenzuela",
            "gross": null
        },
        {
            "imdb_id": "tt13874422",
            "name": "The Eternal Daughter (2022)",
            "poster": "https://m.media-amazon.com/images/S/sash/NapCxx-VwSOJtCZ.png.jpg",
            "plot": "In this ghost story from acclaimed filmmaker Joanna Hogg, a middle-aged daughter and her elderly mother must confront long-buried secrets when they return to their former family home, a ...",
            "runtime": null,
            "genre": "Drama",
            "rating": null,
            "votes": null,
            "directors": "Joanna Hogg",
            "stars": "Tilda Swinton, Joseph Mydell, Carly-Sophia Davies, August Joshi",
            "gross": null
        },
        {
            "imdb_id": "tt0078616",
            "name": "From Here to Eternity (1979)",
            "poster": "https://m.media-amazon.com/images/M/MV5BMTk1ODQ5NjQwMl5BMl5BanBnXkFtZTcwNjcxMjUyMQ@@.jpg",
            "plot": "In Hawaii in 1941, a private is cruelly punished for not boxing on his unit's team, while his captain's wife and second-in-command are falling in love....",
            "runtime": "360 min",
            "genre": "Drama",
            "rating": "7.2",
            "votes": "457",
            "directors": null,
            "stars": "Natalie Wood, William Devane, Steve Railsback, Roy Thinnes",
            "gross": null
        },
        {
            "imdb_id": "tt4058600",
            "name": "Marvel Knights: Eternals (2014 Video)",
            "poster": "https://m.media-amazon.com/images/M/MV5BMzA1ZTAxYjQtYzQzNy00N2QzLThjZTMtMWU1NGM3YWFhYmU2XkEyXkFqcGdeQXVyMjMxMDM2NjY@.jpg",
            "plot": null,
            "runtime": null,
            "genre": "Animation",
            "rating": "6.4",
            "votes": "69",
            "directors": null,
            "stars": null,
            "gross": null
        },
        {
            "imdb_id": "tt7034108",
            "name": "Pillars of Eternity II: Deadfire (2018 Video Game)",
            "poster": "https://m.media-amazon.com/images/M/MV5BNTQyNDAzYjEtY2NjNS00MjM3LWEyNjgtNzI3ZWJjMWM0NGM3XkEyXkFqcGdeQXVyMjM5NzU3OTM@.jpg",
            "plot": "Eothas has returned and now inhabits the stone titan that sat buried under your keep, Caed Nua. Ripping his way out of the ground, he destroyed your stronghold and left you at the brink of death. To save your soul, you must track him down....",
            "runtime": null,
            "genre": "Adventure, Fantasy",
            "rating": "8.0",
            "votes": "154",
            "directors": "Josh Sawyer",
            "stars": "Ashley Johnson, Laura Bailey, Liam O'Brien, Marisha Ray",
            "gross": null
        },
        {
            "imdb_id": "tt7514476",
            "name": "The Eternal Love (2017\u2013 )",
            "poster": "https://m.media-amazon.com/images/M/MV5BYWI1MTZjNDMtZmU3Yy00MjdhLWFiOWYtNjA1MTdlNjQ3NzM0XkEyXkFqcGdeQXVyNzE3MzYwOTk@.jpg",
            "plot": "When two sides of the same woman fall in love with two different princes, can either find true love?...",
            "runtime": null,
            "genre": "Adventure, Comedy, Fantasy",
            "rating": "7.6",
            "votes": "329",
            "directors": null,
            "stars": "Zhaolin Xing, Liang Jie, Ruichang Wang, Yi Ning Sun",
            "gross": null
        },
        {
            "imdb_id": "tt0053115",
            "name": "The Human Condition II: Road to Eternity (II) (1959)",
            "poster": "https://m.media-amazon.com/images/M/MV5BMTdlNTc0MWEtODY5ZS00MmJlLWI0MmUtNjI2NzJmYzk5NjMzXkEyXkFqcGdeQXVyNjI2OTgxNzY@.jpg",
            "plot": "As a conscript in war-time Japan's military, a pacifist struggles to maintain his determination to keep his ideals....",
            "runtime": "181 min",
            "genre": "Drama, History, War",
            "rating": "8.5",
            "votes": "5,983",
            "directors": "Masaki Kobayashi",
            "stars": "Tatsuya Nakadai, Michiyo Aratama, Kokinji Katsura, Jun Tatara",
            "gross": null
        },
        {
            "imdb_id": "tt0048975",
            "name": "Back from Eternity (1956)",
            "poster": "https://m.media-amazon.com/images/M/MV5BY2FlYTY2OGEtZGM2OS00ZTA1LThkMmItMjQ1MDUzODk3ZDE4XkEyXkFqcGdeQXVyNDcxNDkxMjA@.jpg",
            "plot": "When a commercial plane force-lands in a South American jungle, the passengers and pilots must patch-up the engines and escape the cannibal-infested area....",
            "runtime": "97 min",
            "genre": "Adventure, Drama",
            "rating": "6.5",
            "votes": "1,398",
            "directors": "John Farrow",
            "stars": "Robert Ryan, Anita Ekberg, Rod Steiger, Phyllis Kirk",
            "gross": null
        },
        {
            "imdb_id": "tt4270452",
            "name": "Seven Stages to Achieve Eternal Bliss (2018)",
            "poster": "https://m.media-amazon.com/images/M/MV5BODRhMmYwYTctZmJmZi00YjcyLWJmZDUtNmQ1OTU0NGEyNjUxXkEyXkFqcGdeQXVyMTkxNjUyNQ@@.jpg",
            "plot": "A small-town couple finds the perfect apartment in the big city, except there's one catch: the apartment is home to the ritualistic suicides of a deranged cult....",
            "runtime": "98 min",
            "genre": "Comedy, Horror, Thriller",
            "rating": "5.6",
            "votes": "795",
            "directors": "Vivieno Caldinelli",
            "stars": "Taika Waititi, Rhea Seehorn, Kate Micucci, Matt Jones",
            "gross": null
        },
        {
            "imdb_id": "tt1740482",
            "name": "Eternity (2010)",
            "poster": "https://m.media-amazon.com/images/M/MV5BMmY3MWFiOGQtMDQ3YS00NTYzLWI1MGYtMjVhZjU3NTJmYmE1XkEyXkFqcGdeQXVyNTY0MDI2NjY@.jpg",
            "plot": "A young man strikes up an adulterous affair with his uncle's wife....",
            "runtime": "190 min",
            "genre": "Musical",
            "rating": "6.7",
            "votes": "258",
            "directors": "M.L. Pundhevanop Dhewakul",
            "stars": "Ananda Everingham, Laila Boonyasak, Teerapong Liaorakwong, Sakrat Ruekthamrong",
            "gross": null
        },
        {
            "imdb_id": "tt2404217",
            "name": "The Fighter Pilot (2013)",
            "poster": "https://m.media-amazon.com/images/M/MV5BNzQ5ZDlhODMtZDczYi00ZjMzLTllYjUtZGE4YjE2YmE5MmNhXkEyXkFqcGdeQXVyNTEwMzkyODI@.jpg",
            "plot": "A young woman and her brother explore the history of their grandfather, who died in the WW2. They start contacting the men who flew with him, asking them about who he was....",
            "runtime": "144 min",
            "genre": "Action, Drama, Mystery",
            "rating": "7.2",
            "votes": "2,466",
            "directors": "Takashi Yamazaki",
            "stars": "Jun'ichi Okada, Haruma Miura, Mao Inoue, Gaku Hamada",
            "gross": null
        },
        {
            "imdb_id": "tt8655738",
            "name": "Eternal Code (2019)",
            "poster": "https://m.media-amazon.com/images/M/MV5BMmQxOWEzZGQtOWNhNi00ZTRjLTllOWQtOTA1OWIyODk4NmRmXkEyXkFqcGdeQXVyNDg3NzEyMzY@.jpg",
            "plot": "Eternal life technology (transferring mind to new body) is developed by 2 companies. Resistance to the merger of the 2 companies is met with kidnapping and murder....",
            "runtime": "105 min",
            "genre": "Action, Crime, Thriller",
            "rating": "4.6",
            "votes": "4,778",
            "directors": "Harley Wallen",
            "stars": "Richard Tyson, Scout Taylor-Compton, Billy Wirth, Yan Birch",
            "gross": null
        },
        {
            "imdb_id": "tt13373182",
            "name": "Unicorn: Warriors Eternal (2022\u2013 )",
            "poster": "https://m.media-amazon.com/images/M/MV5BYzFhZDNmMmItYTcyZi00OTRlLWIwYzAtOWYxZmMzZTVkMmMzXkEyXkFqcGdeQXVyMTE0NzY5OTk5.jpg",
            "plot": "The series follows a team of ancient heroes protecting the world from an ominous force. Throughout history, unicorns have symbolized the virtuous, appearing to ensure that goodness reigns. ...",
            "runtime": null,
            "genre": "Animation, Action, Adventure",
            "rating": null,
            "votes": null,
            "directors": null,
            "stars": "Ron Bottitta",
            "gross": null
        },
        {
            "imdb_id": "tt0053901",
            "name": "Hell to Eternity (1960)",
            "poster": "https://m.media-amazon.com/images/M/MV5BOTJhOTliN2ItM2I5My00ZjAxLWI4NmQtMjk1ODEzYTE4ZWY2XkEyXkFqcGdeQXVyMTk2MzI2Ng@@.jpg",
            "plot": "When his adoptive Japanese-American family is sent to Manzanar after Pearl Harbor, a young Chicano enlists in the marines to become a hero in the Battle of Saipan....",
            "runtime": "131 min",
            "genre": "Biography, Drama, War",
            "rating": "7.0",
            "votes": "1,213",
            "directors": "Phil Karlson",
            "stars": "Jeffrey Hunter, David Janssen, Vic Damone, Patricia Owens",
            "gross": null
        },
        {
            "imdb_id": "tt3564574",
            "name": "Eternity (2016)",
            "poster": "https://m.media-amazon.com/images/M/MV5BNmQ4NWZmYzctMTRmMS00YWFkLThkZjUtNmZmOGNkNjQ5OTNmXkEyXkFqcGdeQXVyNDcyMjQ4MzU@.jpg",
            "plot": "The story of the women and relationships that define a family across a century....",
            "runtime": "115 min",
            "genre": "Drama",
            "rating": "5.6",
            "votes": "1,238",
            "directors": "Anh Hung Tran",
            "stars": "Audrey Tautou, B\u00e9r\u00e9nice Bejo, M\u00e9lanie Laurent, J\u00e9r\u00e9mie Renier",
            "gross": null
        },
        {
            "imdb_id": "tt4173170",
            "name": "The Eternal Road (2017)",
            "poster": "https://m.media-amazon.com/images/M/MV5BODA1NDI0ZGYtYjUxNC00MzI3LWJiNWItYzEyZDUyN2Q3MmU0XkEyXkFqcGdeQXVyNzI1NzMxNzM@.jpg",
            "plot": "One night of 1930, nationalist thugs violently abduct Ketola from his home in Finland. Beaten and forced to walk the Eternal Road towards a foreign Soviet Russia, his only dream is to return to his family cost it what it may....",
            "runtime": "103 min",
            "genre": "Drama, History",
            "rating": "7.1",
            "votes": "2,175",
            "directors": "Antti-Jussi Annila",
            "stars": "Tommi Korpela, Sidse Babett Knudsen, Hannu-Pekka Bj\u00f6rkman, Irina Bj\u00f6rklund",
            "gross": null
        },
        {
            "imdb_id": "tt6605812",
            "name": "Eternal Winter (2018)",
            "poster": "https://m.media-amazon.com/images/M/MV5BZTViZTRkODMtYzJkYy00MTdlLWEwMjctYzIxNzkzZDE3NzU4XkEyXkFqcGdeQXVyNDMyNTgyOA@@.jpg",
            "plot": "The true story of an unlikely romance in a Soviet labor camp....",
            "runtime": "110 min",
            "genre": "Drama, History, Romance",
            "rating": "7.4",
            "votes": "1,547",
            "directors": "Attila Sz\u00e1sz",
            "stars": "Marina Gera, S\u00e1ndor Cs\u00e1nyi, Laura D\u00f6br\u00f6si, Di\u00e1na Magdolna Kiss",
            "gross": null
        },
        {
            "imdb_id": "tt0052771",
            "name": "Edge of Eternity (1959)",
            "poster": "https://m.media-amazon.com/images/M/MV5BNDU5MDQ3YTAtZGZjMy00MWNmLThmMzctNzQzYjRmOTljMTJhXkEyXkFqcGdeQXVyNzQxMzQ5NTI@.jpg",
            "plot": "In the 1950s, Arizona Deputy Sheriff Les Martin is pressured by his community to solve a string of mysterious murders around a mining ghost town in the Grand Canyon....",
            "runtime": "80 min",
            "genre": "Crime, Drama, Mystery",
            "rating": "6.4",
            "votes": "820",
            "directors": "Don Siegel",
            "stars": "Cornel Wilde, Victoria Shaw, Mickey Shaughnessy, Edgar Buchanan",
            "gross": null
        },
        {
            "imdb_id": "tt5707754",
            "name": "The Eternal Feminine (2017)",
            "poster": "https://m.media-amazon.com/images/M/MV5BZmI4MGM1MDQtZGQ5Yi00MmNmLWE4MzUtYTM0YThjODRjOWI0XkEyXkFqcGdeQXVyNTMyNTA3Mzc@.jpg",
            "plot": "Rosario Castellanos is an introverted university student who doesn't seem to belong to her time. In the early 1950s in Mexico City, she is fighting to have voice heard in a society run by ...",
            "runtime": "85 min",
            "genre": "Drama",
            "rating": "7.0",
            "votes": "702",
            "directors": "Natalia Berist\u00e1in",
            "stars": "Karina Gidi, Daniel Gim\u00e9nez Cacho, Tessa Ia, Pedro De Tavira",
            "gross": null
        },
        {
            "imdb_id": "tt5516404",
            "name": "Hope Springs Eternal (2018)",
            "poster": "https://m.media-amazon.com/images/M/MV5BNzE3YWMzNTMtYzA5YS00MWE0LWI0M2EtNDdlY2Q0YzY3Y2NmXkEyXkFqcGdeQXVyMzU3NjY4Mzc@.jpg",
            "plot": "When 18 year old Hope Gracin suddenly finds herself in remission from end-stage cancer, she must learn to live without an expiration date....",
            "runtime": "78 min",
            "genre": "Comedy, Drama",
            "rating": "4.8",
            "votes": "520",
            "directors": "Jack C. Newell",
            "stars": "Mia Rose Frampton, Stony Blyden, Juliette Angelo, Beth Lacke",
            "gross": null
        },
        {
            "imdb_id": "tt15528116",
            "name": "The Timekeepers of Eternity (2021)",
            "poster": "https://m.media-amazon.com/images/M/MV5BYTRjNjBiOTQtYjQzYS00MTJkLWI5MDItMTkzMWIwNmE0NGRmXkEyXkFqcGdeQXVyNjU3MDQxNQ@@.jpg",
            "plot": "A classic Stephen King miniseries is re-envisioned in this radical collage animation experiment by Greek director, Aristotelis Maragkos: A group of passengers aboard a routine flight to ...",
            "runtime": "64 min",
            "genre": "Animation",
            "rating": "6.9",
            "votes": "14",
            "directors": "Aristotelis Maragkos",
            "stars": null,
            "gross": null
        },
        {
            "imdb_id": "tt8260948",
            "name": "Eternity (2017)",
            "poster": "https://m.media-amazon.com/images/M/MV5BYzUzYzJiYTEtZDUwYy00YmM3LWE3MWEtOTg5MzAyNjRhN2E3XkEyXkFqcGdeQXVyNzkyOTY0Njg@.jpg",
            "plot": "A couple of elderlies try to survive in Los Andes of Peru while they wait for their son....",
            "runtime": "86 min",
            "genre": "Drama",
            "rating": "7.7",
            "votes": "518",
            "directors": "\u00d3scar Catacora",
            "stars": "Vicente Catacora, Rosa Nina",
            "gross": null
        },
        {
            "imdb_id": "tt4359948",
            "name": "Life Is an Eternal Swing (2015)",
            "poster": "https://m.media-amazon.com/images/M/MV5BMTUxNjEwNzAzNl5BMl5BanBnXkFtZTgwNjMzMzAxNDE@.jpg",
            "plot": null,
            "runtime": "88 min",
            "genre": "Documentary",
            "rating": "9.7",
            "votes": "7",
            "directors": "Andr\u00e9 Chandelle",
            "stars": null,
            "gross": null
        },
        {
            "imdb_id": "tt2461406",
            "name": "Pillars of Eternity (2015 Video Game)",
            "poster": "https://m.media-amazon.com/images/M/MV5BN2Q3MWE0YzYtYjM3NS00ZDU0LTgyNDMtODcwNWZiOGZmOTYyXkEyXkFqcGdeQXVyNTAyODkwOQ@@.jpg",
            "plot": "Imbued with the power to interact with souls and memories of others, you set out to investigate the origin of your new found power and why infants of the world of Eora are born without a soul....",
            "runtime": null,
            "genre": "Adventure, Fantasy",
            "rating": "7.9",
            "votes": "400",
            "directors": "Chris Avellone, Tim Cain, Josh Sawyer",
"stars": "Orion Acaba, Valerie Arem, Edward Bosco, Brandon Cole",
            "gross": null
        },
        {
            "imdb_id": "tt14884402",
            "name": "Ping Mo Ce: The Red Sword of Eternal Love (2021)",
            "poster": "https://m.media-amazon.com/images/M/MV5BNTlhNTk2YWItZDNlNi00ZWI4LWIzODgtMGZiYzNlYTAyMzU4XkEyXkFqcGdeQXVyMzAzMzkzNTU@.jpg",
            "plot": "Yue Qingyin investigates her sisters death....",
            "runtime": "81 min",
            "genre": "Fantasy",
            "rating": "4.8",
            "votes": "14",
            "directors": "Yanbo Han",
            "stars": "Yanbo Han, Chen Xixu",
            "gross": null
        },
        {
            "imdb_id": "tt6138484",
            "name": "Star Wars: The Old Republic - Knights of the Eternal Throne (2016 Video Game)",
            "poster": "https://m.media-amazon.com/images/M/MV5BMjQyZmNiMTktMDYzZS00YjQ4LWFiMzMtZDE4MzQ3OTZmMzM2XkEyXkFqcGdeQXVyMzM2MzI5MzU@.jpg",
            "plot": "After the Alliance Commander overthrows Arcann, she is faced with a new threat; Vaylin. Faced with new challenges, opportunities, and unlikely allies; the Commander must dethrone Vaylin....",
            "runtime": null,
            "genre": "Action, Sci-Fi",
            "rating": "8.1",
            "votes": "251",
            "directors": "Charles Boyd",
            "stars": "Tom Spackman, Grey Griffin, Bertie Carvel, Jo Wyatt",
            "gross": null
        },
        {
            "imdb_id": "tt15783444",
            "name": "Marvel Studios' Eternals Red Carpet LIVE! (2021 TV Special)",
            "poster": "https://m.media-amazon.com/images/S/sash/NapCxx-VwSOJtCZ.png.jpg",
            "plot": null,
            "runtime": "122 min",
            "genre": "Reality-TV",
            "rating": null,
            "votes": null,
            "directors": "Bill Chapman",
            "stars": "Victoria Alonso, Mitchell Bell, Patrick Burleigh, Gemma Chan",
            "gross": null
        },
        {
            "imdb_id": "tt13621794",
            "name": "Eternal Return: Black Survival (2020 Video Game)",
            "poster": "https://m.media-amazon.com/images/M/MV5BYjhlNWYyMTMtOWM2Yy00MGIwLWEyZWEtMDg1MDZiMjFkNGJhXkEyXkFqcGdeQXVyMTIwODcyMzky.jpg",
            "plot": null,
            "runtime": null,
            "genre": "Action",
            "rating": null,
            "votes": null,
            "directors": null,
            "stars": "Felecia Angelle, Jacob Barrens, Caitlyn Elizabeth, Joe Goffeney",
            "gross": null
        },
        {
            "imdb_id": "tt10422832",
            "name": "Ephemeral Eternity (2018)",
            "poster": "https://m.media-amazon.com/images/M/MV5BYzZmN2JiZjktNjZiOS00ZTc2LWI3M2UtYzA3NDQxOTExNzZjXkEyXkFqcGdeQXVyMjM5ODE2MzI@.jpg",
            "plot": "In a seemingly random (yet fateful) arrangement, an Asian man had some unique encounters with his house tenants: a German foreign student and a Swiss/Taiwanese traveler while his wife was ...",
            "runtime": "77 min",
            "genre": "Romance",
            "rating": "3.5",
            "votes": "9",
            "directors": "Teli Share",
            "stars": "Cham, Sarah Navratil, James Speed, Olivia Stiefel",
            "gross": null
        },
        {
            "imdb_id": "tt7542312",
            "name": "Eternal Warrior",
            "poster": "https://m.media-amazon.com/images/S/sash/NapCxx-VwSOJtCZ.png.jpg",
            "plot": "The Eternal Warrior has protected the Earth for more than 10,000 years from The Immortal Enemy - a monstrous, civilization killer....",
            "runtime": null,
            "genre": "Action, Adventure, Fantasy",
            "rating": null,
            "votes": null,
            "directors": null,
            "stars": "Dave Bautista",
            "gross": null
        },
        {
            "imdb_id": "tt3914324",
            "name": "Eternal Summer (I) (2015)",
            "poster": "https://m.media-amazon.com/images/M/MV5BMTgwOTYwNzU3OV5BMl5BanBnXkFtZTgwNzYyNjc5NTE@.jpg",
            "plot": "When Isak meets Em during a night in Stockholm everything change. Suddenly nothing else matter. Isak wants Em. Em wants more....",
            "runtime": "106 min",
            "genre": "Comedy, Drama, Romance",
            "rating": "6.3",
            "votes": "633",
            "directors": "Andreas \u00d6hman",
            "stars": "Madeleine Martin, Filip Berg, Torkel Petersson, Fanny Ketter",
            "gross": null
        },
        {
            "imdb_id": "tt0113928",
            "name": "The Eternal Evil of Asia (1995)",
            "poster": "https://m.media-amazon.com/images/M/MV5BMTkwMjUxODY3OV5BMl5BanBnXkFtZTcwODEzMTMyMQ@@.jpg",
            "plot": "A group of friends went on a hedonistic trip to Thailand. Accidentally, they rape and kill a sorcerer's sister. Now, upon arriving back home to Hong Kong, they find themselves cursed by the sorcerer....",
            "runtime": "89 min",
            "genre": "Comedy, Fantasy, Horror",
            "rating": "6.1",
            "votes": "486",
            "directors": "Man Kei Chin",
            "stars": "Ellen Chan, Lily Chung, Ben Ngai-Cheung Ng, Kwok-Pong Chan",
            "gross": null
        },
        {
            "imdb_id": "tt1194612",
            "name": "Into Eternity: A Film for the Future (2010)",
            "poster": "https://m.media-amazon.com/images/M/MV5BMjI4NzUxMjA2NF5BMl5BanBnXkFtZTcwNjczNjI0NA@@.jpg",
            "plot": "A documentary on the safety of nuclear storage....",
            "runtime": "75 min",
            "genre": "Documentary",
            "rating": "7.4",
            "votes": "2,988",
            "directors": "Michael Madsen",
            "stars": "Carl Reinhold Br\u00e5kenhjelm, Mikael Jensen, Berit Lundqvist, Michael Madsen",
            "gross": "$0.06M"
        },
        {
            "imdb_id": "tt7364994",
            "name": "Highlander Eternity",
            "poster": "https://m.media-amazon.com/images/S/sash/NapCxx-VwSOJtCZ.png.jpg",
            "plot": "Best science now tells us, everyone alive today is descended from the same few-thousand people who survived our near-extinction a few-thousand generations ago - Their story continues....",
            "runtime": null,
            "genre": "Sci-Fi",
            "rating": null,
            "votes": null,
            "directors": null,
            "stars": null,
            "gross": null
        }
    ]
}
```
<!--END_RESPONSE-->

</details>

---
#### Get Movie Details :popcorn:

##### Usage
```sh
https://api.mrdeveloper.ga/imdb?id={IMDb-id-here}
```

**:octocat: Required Args**

`id`: `str` IMDb ID [❓]()
##### **Example:** https://api.mrdeveloper.ga/imdb?id=tt9032400
#####
<details><summary>Example Output</summary>

<!--START_RESPONSE-->
```json
{
    "success": true,
    "query": "tt9032400",
    "results": [
        {
            "id": "tt9032400",
            "type": "Movie",
            "content_rating": "PG-13",
            "title": "Eternals",
            "url": "https://m.imdb.com/title/tt9032400",
            "genre": [
                "Action",
                "Adventure",
                "Fantasy"
            ],
            "keywords": [
                "superhero",
                "marvel comics",
                "marvel cinematic universe",
                "marvel entertainment",
                "gay"
            ],
            "releaseYear": "2021",
            "releaseDate": "05 November 2021",
            "runTime": {
                "inHours": 2.6,
                "inMinutes": 156,
                "inSeconds": 9360
            },
            "budget": "$118,765,255",
            "gross_us": "$71,297,219",
            "gross_worldwide": "$281,365,255",
            "languages": [
                "English",
                "American Sign Language",
                "Spanish"
            ],
            "short_plot": "The saga of the Eternals, a race of immortal beings who lived on Earth and shaped its history and civilizations.",
            "awards": "1 nomination",
            "also_known": "Ch\u1ee7ng T\u1ed9c B\u1ea5t T\u1eed",
            "country": "United States",
            "shooting_locations": [
                "Fuerteventura",
                "Canary Islands",
                "Spain"
            ],
            "full_plot": "Following the events of Avengers: Endgame (2019), an unexpected tragedy forces the Eternals, ancient aliens who have been living on Earth in secret for thousands of years, out of the shadows to reunite against mankind's most ancient enemy, the Deviants.",
            "full_synopsis": "The movie opens up with a text scrolls that explains a short history of celestials and eternals. The movie goes back and forth between past and present showing us all things the eternals participated in history, including helping them advance their technology to the point humans make the bomb that hit Hiroshima and the conquistadors conquest through America. As well as all the times they protected the world from the alien monster called the Deviants up until the 1500s as they thought they had killed the last of them.Thena is the one that sparks them all to split by attacking the group but she doesn't kill anyone. Ajak the leader wants to erase her memories to prevent more attacks but Gilgamesh steps up and says he'll take her and keep everyone safe. Druig ensues into a deep monologue about how he doesn't like standing on the side lines while humans slaughter each other, so he takes some of the nearby fighting humans and leaves. Gilgamesh and Thena go off and live in Australia together. Sprite and Sersi become companions during the time when Ikaris leaves Sersi. Sersi starts dating Dane Whitman and teaching at a primary school. Kingo travels the world and eventually becomes a popular Bollywood actor, even going as far as pretending to be his own descendants within a fake family so he can keep acting. Druig starts a colony in the Amazon. Phastos goes and lives his life by having a family, he has a husband and a son. Makkari has been living in their ship for centuries.After the Deviants start attacking again Sersi, Ikaris, and Sprite go and try to find their leader Ajak who they find dead, attacked by a deviant which now has her powers of healing and later becomes Kro. Ajak has a orb in her chest that allowed her to talk to the Celestial who made them, when Sersi finds the body the orb goes into her allowing her to speak to the celestial that made them. The team then goes and collects Kingo while he's making a film. They use his private jet to travel most of the movie, his valet tagging along to record a \"documentary\". They travel to Australia to collect Gilgamesh and Thena. While there Sersi talks to the Celestial again using the orb. They then find out that the celestial sent the eternals toprotect a seed that was planted inside the earth. The seed grows into a another Celestial so long as the population grows. The Celestial made Deviants to kill predators on planets so that the intelligent population would thrive. But instead they evolved and started hunting down everything. So the Celestial made the Eternals kill the Deviants so the population may grow. Once the seed is done growing the emergence begins destroying the world creating a new Celestial after the complete destruction of said planet. The eternals minds are then erased and they are sent onto a new planet to destroy. Thena's memories weren't completely erased so that's why she's going crazy.After learning this information, they go and try to convince Druig to help put the celestial to sleep. There is a fight scene with the Deviants, as Kro eats Gilgamesh then becomes more humanoid. After some convincing Druig says he can't do it alone, and needs a machine built by Phastos to even think about potentially doing that. So they all go collect Phastos, Phastos is not convinced by the other Eternals that his husband is the one that convinced him to help. They all go back to the main ship in the desert where Makkari is residing, they tell her what's going on. Phastos's big idea is to connect them all in a uni-mind state allowing Druig to control the Celestial. Ikaris finally breaks after people start taking sides, calling for him to help make a decision for the team. It flashes back and shows that he was the one that fed Ajax to Kro and the other deviants allowing them to evolve further. He's also known for a long time their true purpose, but when he found out Ajak didn't want to destroy planets anymore he killed her. Ajak had decided to intervene with the emergence after she watched the avengers bring back everyone from Thanos's snap. The avengers bringing half the population back also sped up the emergence according to Ajak. The group then gets into a fight leading to Ikaris and Sprite leaving together. Kingo leaves too because he agrees with Ikaris but doesn't want to fight his friends. Thena convinces Sersi that what she's doing is right and that they need to save the planet.After Sersi is convinced to continue their mission to save earth, Phastos takes the sphere that allows Sersi to talk to the celestials to create bracelets to connect the eternals. They then fly in their ship to the source of the emergence. Once they arrive they connect to Druig in a attempt to control the celestial. Ikaris starts fighting the group, injuring druig so he's unable to complete his connection to the celestial. They then decide that it's best for sersi to use her powers to connect to the celestial to kill it. While the others in the group distract Ikaris, Kro comes in and starts a fight with Thena. Thena kills Kro and in doing so regains control of her memories. Phastos and Makkari are effective at holding their own against Ikaris, at one point Phastos has Ikaris trapped and unable to use any of his powers using some kind of power dampening device he made in the moment. Sersi attempts to connect the celestial but Sprite comes up and violently stabs her in the back with a knife. Druig then comes out of nowhere and knocks out Sprite with a rock. Sersi connects to the celestial and starts turning it into stone. Ikaris breaks free and tries to stop her, but realizes he can't because he loves her. Sersi then reconnects to the celestial but this time with the help of the other eternals completely changing it into stone. Ikaris starts crying because he can't decide whether or not to continue fighting them or join them, after this is done ikaris flies off straight into the sun. Sersi uses what little power she has left from connecting to the celestial to make sprite a human. It doesn't state whether or not she kept her powers though. Druig, Thena, and Makkari go off in their ship to find more eternals.Dane professes his love for Sersi and is about to reveal a secret about his family history when she, along with Phastos and Kingo, are remotely dragged into space by Arishem, who is displeased with their treason but elects to spare humanity if the Eternals' memories show that humans are worthy of living. He vows to return for judgment before disappearing into a singularity, taking them with him.Mid-credit scene: Thena, Makkari and Druig are visited by the Eternal Eros (brother of Thanos) and his assistant Pip the Troll, who offer to help them.Post-credit scene: Dane Whitman opens an old chest inherited from his ancestors that contains the legendary Ebony Blade when an unseen person (identified off screen as Blade) questions him whether he his ready for it.",
            "poster": "https://m.media-amazon.com/images/M/MV5BMTExZmVjY2ItYTAzYi00MDdlLWFlOWItNTJhMDRjMzQ5ZGY0XkEyXkFqcGdeQXVyODIyOTEyMzY@.jpg",
            "rating": 6.9,
            "total_rated": 86818,
            "cast": [
                "Gemma Chan",
                "Richard Madden",
                "Angelina Jolie"
            ],
            "full_cast": [
                {
                    "actor": "Gemma Chan",
                    "role": "Sersi"
                },
                {
                    "actor": "Richard Madden",
                    "role": "Ikaris"
                },
                {
                    "actor": "Angelina Jolie",
                    "role": "Thena"
                },
                {
                    "actor": "Salma Hayek",
                    "role": "Ajak"
                },
                {
                    "actor": "Kit Harington",
                    "role": "Dane Whitman"
                },
                {
                    "actor": "Kumail Nanjiani",
                    "role": "Kingo"
                },
                {
                    "actor": "Lia McHugh",
                    "role": "Sprite"
                },
                {
                    "actor": "Brian Tyree Henry",
                    "role": "Phastos"
                },
                {
                    "actor": "Lauren Ridloff",
                    "role": "Makkari"
                },
                {
                    "actor": "Barry Keoghan",
                    "role": "Druig"
                },
                {
                    "actor": "Ma Dong-seok",
                    "role": "Gilgamesh (as Don Lee)"
                },
                {
                    "actor": "Harish Patel",
                    "role": "Karun"
                },
                {
                    "actor": "Bill Skarsg\u00e5rd",
                    "role": "Kro"
                },
                {
                    "actor": "Haaz Sleiman",
                    "role": "Ben"
                },
                {
                    "actor": "Esai Daniel Cross",
                    "role": "Jack"
                },
                {
                    "actor": "Harry Styles",
                    "role": "Eros"
                },
                {
                    "actor": "Alan Scott",
                    "role": "Patrick"
                },
                {
                    "actor": "Hannah Dodd",
                    "role": "Sandra"
                },
                {
                    "actor": "Adri\u00e0 Escudero",
                    "role": "Diego (as Adri\u00e1 Escudero)"
                },
                {
                    "actor": "Sebasti\u00e1n Capit\u00e1n Viveros",
                    "role": "Jano"
                },
                {
                    "actor": "Nikkita Chadha",
                    "role": "Bollywood Star"
                },
                {
                    "actor": "Grahame Fox",
                    "role": "Kro On-Set Reader"
                },
                {
                    "actor": "Zain Al Rafeea",
                    "role": "Mesopotamian Young Man"
                },
                {
                    "actor": "Alberto Falcon Rodriguez",
                    "role": "Mesopotamian Father"
                },
                {
                    "actor": "Lucia Efstathiou",
                    "role": "Natural History Museum Student"
                },
                {
                    "actor": "Orson Rosenberg",
                    "role": "Aztec Child"
                },
                {
                    "actor": "Ariadna Vadillo Soto",
                    "role": "Ancient Babylon Farmer"
                },
                {
                    "actor": "Derek Horsham",
                    "role": "Ancient Babylon Smuggler #1"
                },
                {
                    "actor": "Jeff Mirza",
                    "role": "Gupta Hindu Priest"
                },
                {
                    "actor": "Ascension Martinez Rubio",
                    "role": "Mesopotamian Grandmother"
                },
                {
                    "actor": "Ozer Ercan",
                    "role": "Ancient Babylon Smuggler #2"
                },
                {
                    "actor": "Patton Oswalt",
                    "role": "Pip the Troll"
                },
                {
                    "actor": "David Kaye",
                    "role": "Arishem (voice)"
                },
                {
                    "actor": "Mahershala Ali",
                    "role": "Eric Brooks / Blade (voice) (uncredited)"
                },
                {
                    "actor": "Brenda Lorena Garcia",
                    "role": "Babylon Villager (uncredited)"
                },
                {
                    "actor": "Sebastian Senior",
                    "role": "Passerby (uncredited)"
                },
                {
                    "actor": "Chloe Stannage",
                    "role": "Girl (uncredited)"
                }
            ],
            "writers": [
                "Chlo\u00e9 Zhao",
                "Patrick Burleigh",
                "Ryan Firpo"
            ],
            "directors": [
                "Chlo\u00e9 Zhao"
            ],
            "producers": [
                {
                    "actor": "Victoria Alonso",
                    "type": "executive producer"
                },
                {
                    "actor": "Mitchell Bell",
                    "type": "co-producer (as Mitch Bell)"
                },
                {
                    "actor": "Louis D'Esposito",
                    "type": "executive producer"
                },
                {
                    "actor": "Kevin de la Noy",
                    "type": "executive producer"
                },
                {
                    "actor": "Kevin Feige",
                    "type": "producer (produced by) (p.g.a.)"
                },
                {
                    "actor": "Nate Moore",
                    "type": "producer (produced by) (p.g.a.)"
                }
            ],
            "production": [
                "Marvel Studios",
                "TSG Entertainment"
            ]
        }
    ]
}
```
<!--END_RESPONSE-->

</details>

---
### **9) IP Address** :globe_with_meridians:
Get an IP Address details.
##### Usage:  

```sh
https://api.mrdeveloper.ga/ip
```

**:electron: Optional Supported Args**

`query`: `integer` IP address to get details **(Defaults to User IP)** :neutral_face:
##### **Example:** https://api.mrdeveloper.ga/ip?query=34.132.18.9
#####
<details><summary>Example Output</summary>

<!--START_RESPONSE-->
```json
{
    "success": true,
    "query": "34.132.18.9",
    "results": [
        {
            "ip": "34.132.18.9",
            "version": "IPv4",
            "city": "Council Bluffs",
            "region": "Iowa",
            "region_code": "IA",
            "country": "US",
            "country_name": "United States",
            "country_code": "US",
            "country_code_iso3": "USA",
            "country_capital": "Washington",
            "country_tld": ".us",
            "continent_code": "NA",
            "in_eu": false,
            "postal": "51502",
            "latitude": 41.2591,
            "longitude": -95.8517,
            "timezone": "America/Chicago",
            "utc_offset": "-0600",
            "country_calling_code": "+1",
            "currency": "USD",
            "currency_name": "Dollar",
            "languages": "en-US,es-US,haw,fr",
            "country_area": 9629091.0,
            "country_population": 327167434,
            "asn": "AS15169",
            "org": "GOOGLE"
        }
    ]
}
```
<!--END_RESPONSE-->

</details>

---
### **10) Telegram Chat/User Information** :genie_man:
Get telegram Chat/User information
##### Usage:  

```sh
https://api.mrdeveloper.ga/tginfo?username={tg-username-here}
```

**:octocat: Required Args**

`username`: `str` Username of telegram :genie_man: User/Chat whose information is to be received
##### **Example:** https://api.mrdeveloper.ga/tginfo?username=NACBots
#####
<details><summary>Example Output</summary>

<!--START_RESPONSE-->
```json
{
    "success": true,
    "query": "NACBots",
    "results": [
        {
            "type": "Channel",
            "id": -1001481400401,
            "name": "N A C UPDATES",
            "dc": 5,
            "subs": 20446,
            "description": "OUR BOTS 🔻\n\nhttps://t.me/nacbots/10\n\nSUPPORT GROUP 🔻\n\n@n_a_c_bot_developers\n\nTORRENT LEECH/MIRROR GROUP 🔻\n\n@torrcloud\n\nMUSIC GROUP 🔻\n\n@gramaphone_mp3\n\nMOVIES 🔻\n\n@trolldcompany\n\nOFFTOPIC 🔻\n\n@nacofftopic",
            "username": "nacbots",
            "chat_image": "https://cdn5.telesco.pe/file/Ply6dIafQcRP37cHgHwE0C3esTvPMA7FOKcfXYsWGp54dl2IdbWkDQEl6W4_PJqaDMnY9kha-2CKuvSmJYCx11qOP6W7y5e0HMs-w5DsL8W5YGaLVV1qxwpTB19TonJ9IGki3P9VAMS8xzWSGn7tU-xHZzQg_i0v4X_qyU2muoD3rdU4SIZS9zWdYvbz5s6eXv3m0ndQlAJlSJOzedBWSm5N2wwpGYg-vw1AHopTWZQ-Q1WFHRJpG13axFaE8zreUfX7HZxpheQZ5XsGkhbLwNxNVqLZz-0AZ9qB0PZTHYpHtheQn5T-2L_0YEYzEEQh7eUSFI3q220dzyCm1dMv4Q.jpg"
        }
    ]
}
```
<!--END_RESPONSE-->

</details>

---
### **11) Telegram Bot Status** :robot:
Check telegram bot status
##### Usage:  

```sh
https://api.mrdeveloper.ga/tg_bot_status?username={tg-username-here}
```

**:octocat: Required Args**

`username`: `str` Username of telegram bot whose status :rocket: is to be received
##### **Example:** https://api.mrdeveloper.ga/tg_bot_status?username=YTPlaylistRoBot
#####
<details><summary>Example Output</summary>

<!--START_RESPONSE-->
```json
{
    "success": true,
    "query": "YTPlaylistRoBot",
    "results": [
        {
            "status": "Working",
            "time_waited": 5,
            "response_time": 0.6565804481506348
        }
    ]
}
```
<!--END_RESPONSE-->

</details>

---
### **12) Random Word** 📚
Check telegram bot status
##### Usage:  

```sh
https://api.mrdeveloper.ga/random_word
```

##### **Example:** https://api.mrdeveloper.ga/random_word
#####
<details><summary>Example Output</summary>

<!--START_RESPONSE-->
```json
{
    "success": true,
    "results": [
        {
            "word":"spheroplasts",
            "defination":"a bacterium or plant cell bound by its plasma membrane, the cell wall being deficient or lacking and the whole having a spherical form."
        }
    ]
}
```
<!--END_RESPONSE-->

</details>

---
### **Note:** ```The API is hosted on Heroku so it may be slow to respond.```

---

## <center>:star: Made using the API :star:</center>
---

---
### Star the Repo if you find it useful :heart:
### © [Mr. Developer](https://mrdeveloper.ga)
#### All Rights Reserved
---
