<h3 align="center">
  
  <p align="center"><img src="https://img.shields.io/badge/WLCM%20TO -SHAON MEDIA DOWNLOADER-green?colorA=%23ff0000&colorB=%23017e40&style=flat-square">  
  
</h3>

[![Typing SVG](https://readme-typing-svg.herokuapp.com?font=Neuton&size=25&color=30FF40&background=000000&center=true&vCenter=true&width=360&height=60&lines=Hello+World%2C+I'm+Mr-SHAON+Here+🤙;𝙸𝚃'𝚜+𝙽𝙾𝚃+𝙰+𝙹𝚄𝚂𝚃+𝙽𝙰𝙼𝙴+𝙱𝚁𝙾+🥱;𝙸𝚃'𝚜+𝙰+𝙱𝚁𝙰𝙽𝙳+🔥;Respect+MR.SHAON+🥀;Thanks+My+All+Friend+🤙+🥰)](https://git.io/typing-svg)



## Instalation :
```bash
> npm i shaon-videos-downloader
```
## Last Update 
```print
• pintarest (fix)
• capcut (fix)
• ytdown (fix)
```

## Example (fb & insta)
```js
const { ndown } = require("shaon-videos-downloader")
let URL = await ndown("https://www.facebook.com/100000959749712/posts/pfbid0288xi44nvodK9d7r3wf4LHeM3dtEsVghQXmz5t59axwz7KdLStYyg4qfvTVrAL27Ll/?app=fbl")
console.log(URL)
```
## Output Example
```
{
    "author": "SHAON AHMED",
    "cp": "✅Successfully downloaded the video!🎀",
    "videos": [
        {
            "url": "https://video.fsgn24-1.fna.fbcdn.net/o1/v/t2/f2/m69/AQOVfz7sZ2FUWE3vf3y1XmeXAPxY8OvwOU21fVN2kPEtrpOwGLVi8qKwOMyzya44Lkf0tgWjcsaJOW5-HQJZeNMD.mp4?strext=1&_nc_cat=102&_nc_oc=AdltGwW8ja8YUIpm4aSDqrP9YQIU0lAgkZnE9eJSurwF_-ZsBuMAb4nNXnXfipuOE0U&_nc_sid=5e9851&_nc_ht=video.fsgn24-1.fna.fbcdn.net&_nc_ohc=2RcwEzz0CN4Q7kNvwGz_xoI&efg=eyJ2ZW5jb2RlX3RhZyI6Inhwdl9wcm9ncmVzc2l2ZS5GQUNFQk9PSy4uQzMuNzIwLmRhc2hfaDI2NC1iYXNpYy1nZW4yXzcyMHAiLCJ4cHZfYXNzZXRfaWQiOjExNDczNDI5MTcxNDA3NzMsInZpX3VzZWNhc2VfaWQiOjEwMTIwLCJkdXJhdGlvbl9zIjo5LCJ1cmxnZW5fc291cmNlIjoid3d3In0%3D&ccb=17-1&vs=c2d6c0a4cab8ed5&_nc_vs=HBksFQIYOnBhc3N0aHJvdWdoX2V2ZXJzdG9yZS9HRlNBVUIwZ0k4TkF3UlFDQUxfVE1wc19IazlHYm1kakFBQUYVAALIAQAVAhg6cGFzc3Rocm91Z2hfZXZlcnN0b3JlL0dLbkFVUjJyYWVGMVBOc0ZBUE9BdGF5aHUzWklickZxQUFBRhUCAsgBACgAGAAbAogHdXNlX29pbAExEnByb2dyZXNzaXZlX3JlY2lwZQExFQAAJsqEmPCS4IkEFQIoAkMzLBdAIzMzMzMzMxgZZGFzaF9oMjY0LWJhc2ljLWdlbjJfNzIwcBEAdQIA&_nc_zt=28&oh=00_AfF55wdhHxieGPXqeqMuoUO3MfY-SlK60-Rdec03s7WmMQ&oe=680FA110"
        },
        {
            "url": "https://video.fsgn24-2.fna.fbcdn.net/o1/v/t2/f2/m69/AQO0YKxhs-7i5GjCzlHCJKkYR-r3bFJAWWJ9r9e2TD2bxMftSD0f4q6BhYP2ya5mbpr2g9FDDY10EcPcjb26YNem.mp4?strext=1&_nc_cat=111&_nc_oc=AdmkJI-3l0dVnXiEMCzFQrxI7D9sgL5xV_6wEp0vh1tGEYCVEruwNuqo-7-kW2ByMn8&_nc_sid=8bf8fe&_nc_ht=video.fsgn24-2.fna.fbcdn.net&_nc_ohc=BPs0WrwWtDQQ7kNvwGS8axx&efg=eyJ2ZW5jb2RlX3RhZyI6Inhwdl9wcm9ncmVzc2l2ZS5GQUNFQk9PSy4uQzMuMzYwLnN2ZV9zZCIsInhwdl9hc3NldF9pZCI6MTE0NzM0MjkxNzE0MDc3MywidmlfdXNlY2FzZV9pZCI6MTAxMjAsImR1cmF0aW9uX3MiOjksInVybGdlbl9zb3VyY2UiOiJ3d3cifQ%3D%3D&ccb=17-1&_nc_zt=28&oh=00_AfHFawNKflh8p3QWFFLI75J4AH00wRgJBXZ1TpLAGfkbtQ&oe=680FAB83"
        }
    ]
}
```
## Instagram Usage 
```js
const {instagram} = require("shaon-videos-downloader");

const link = "https://www.instagram.com/p/DAxzjkAyWOm/?igsh=MTZ5eThrMXpteTFpOA==" //past video link

  instagram(link).then(data => {

    console.log(data)

});
```
## Example (TikTok)
```js
const { tikdown } = require("shaon-videos-downloader")
let URL = await tikdown("https://vt.tiktok.com/ZSNvs6h6o/")
console.log(URL)
```
## Output Example (tikTok)
```
{
    "code": 0,
    "msg": "success",
    "processed_time": 0.246,
    "data": {
        "id": "7495372137511783687",
        "region": "BD",
        "title": "আপাতত আমি হেরে গেছি.!😅❤️‍🩹 #bd #tiktok #foryou @TikTok @For You ",
        "cover": "https://p16-sign-sg.tiktokcdn.com/tos-alisg-p-0037/o0jEJFD8AcffA9CSnQ3eA4oJPAIIQAA0Dd0LEA~tplv-tiktokx-cropcenter:300:400.jpeg?dr=14579&refresh_token=09338d09&x-expires=1745560800&x-signature=%2FYbug58OdHYj9%2F9VUnkhW4QkKOo%3D&t=4d5b0474&ps=13740610&shp=d05b14bd&shcp=34ff8df6&idc=maliva&s=AWEME_DETAIL",
        "ai_dynamic_cover": "https://p16-sign-sg.tiktokcdn.com/tos-alisg-p-0037/o0jEJFD8AcffA9CSnQ3eA4oJPAIIQAA0Dd0LEA~tplv-tiktokx-origin.image?dr=14575&refresh_token=2e26e7d9&x-expires=1745560800&x-signature=iNo%2B5dxOU5pxu6maEbj5H5nsQe4%3D&t=4d5b0474&ps=13740610&shp=d05b14bd&shcp=34ff8df6&idc=maliva&s=AWEME_DETAIL",
        "origin_cover": "https://p16-sign-sg.tiktokcdn.com/tos-alisg-p-0037/ooADBUXEdfQIfC9W5ADcjIWVoC6jEeFAImOIDN~tplv-tiktokx-360p.jpeg?dr=14555&refresh_token=9a2cc989&x-expires=1745560800&x-signature=BbH37LyBbO1sAVyNjI8mHEyqSAg%3D&t=4d5b0474&ps=13740610&shp=d05b14bd&shcp=34ff8df6&idc=maliva&s=AWEME_DETAIL&ftpl=1",
        "duration": 12,
        "play": "https://v16m-default.tiktokcdn.com/3dc98a4e180c5db869823955dd83b813/680a2d3f/video/tos/alisg/tos-alisg-pve-0037c001/oweQUw8dJAozWjeuAQLGC0oGteauGpcIDICgJI/?a=0&bti=OUBzOTg7QGo6OjZAL3AjLTAzYCMxNDNg&ch=0&cr=0&dr=0&er=0&lr=all&net=0&cd=0%7C0%7C0%7C0&cv=1&br=896&bt=448&cs=0&ds=6&ft=EeF4ntZWD03Q12NvEyvQWIxRSfYFpq_45SY&mime_type=video_mp4&qs=4&rc=Ozg6ZDg4OjU8NDY5ZGc3OEBpanF0bXY5cjhoMzMzODczNEA0LS0zX2AyNWExXl4tYTUvYSMuMzZzMmRrYy9hLS1kMTFzcw%3D%3D&vvpl=1&l=20250424142315365B72209DEC60017057&btag=e000b0000",
        "wmplay": "https://v16m-default.tiktokcdn.com/dfbde37bf484083e3b98bcc562983789/680a2d3f/video/tos/alisg/tos-alisg-pve-0037c001/oUaQCgGGQDCIDQzReIAAIgMLdcJtzGu8f0ejo3/?a=0&bti=OUBzOTg7QGo6OjZAL3AjLTAzYCMxNDNg&ch=0&cr=0&dr=0&er=0&lr=all&net=0&cd=0%7C0%7C0%7C0&cv=1&br=2070&bt=1035&cs=0&ds=3&ft=EeF4ntZWD03Q12NvEyvQWIxRSfYFpq_45SY&mime_type=video_mp4&qs=0&rc=ZjM8NmdnPDs3OTVkNzRnM0BpanF0bXY5cjhoMzMzODczNEAxLjUvYDIvNV8xYi5hYjNfYSMuMzZzMmRrYy9hLS1kMTFzcw%3D%3D&vvpl=1&l=20250424142315365B72209DEC60017057&btag=e000b0000",
        "size": 725828,
        "wm_size": 1674153,
        "music": "https://sf16-ies-music-va.tiktokcdn.com/obj/tos-useast2a-ve-2774/oUOCrw5eZEHMLDFBQZoez5MGAIeag2dp8bRHYh",
        "music_info": {
            "id": "7359564085166884881",
            "title": "Vaseegara - Slow Reverb",
            "play": "https://sf16-ies-music-va.tiktokcdn.com/obj/tos-useast2a-ve-2774/oUOCrw5eZEHMLDFBQZoez5MGAIeag2dp8bRHYh",
            "cover": "https://p16-va-default.akamaized.net/img/tos-useast2a-v-2774/ogAi7JMiABzUaAZEAAwUzEBzPcirW2PNAviQY~c5_720x720.jpeg",
            "author": "Future Frequencies & Bombay Jayashri",
            "original": false,
            "duration": 60,
            "album": "Vaseegara - Slow Reverb"
        },
        "play_count": 184033,
        "digg_count": 18551,
        "comment_count": 466,
        "share_count": 2994,
        "download_count": 1130,
        "collect_count": 1998,
        "create_time": 1745152324,
        "anchors": null,
        "anchors_extras": "",
        "is_ad": false,
        "commerce_info": {
            "adv_promotable": false,
            "auction_ad_invited": false,
            "branded_content_type": 0,
            "organic_log_extra": "{\"req_id\":\"20250424142315365B72209DEC60017057\"}",
            "with_comment_filter_words": false
        },
        "commercial_video_info": "",
        "item_comment_settings": 0,
        "mentioned_users": "107955,6642309458071568390",
        "author": {
            "id": "7168718594821784581",
            "unique_id": "v.apon",
            "nickname": "A~🎀",
            "avatar": "https://p16-sign-sg.tiktokcdn.com/tos-alisg-avt-0068/e64bdee681f516dced32269aa93107c3~tplv-tiktokx-cropcenter:300:300.jpeg?dr=14577&refresh_token=041a1fe7&x-expires=1745560800&x-signature=EQDf1HnR05v7UxX42WQ8cqYLZK8%3D&t=4d5b0474&ps=13740610&shp=45126217&shcp=d05b14bd&idc=maliva"
        }
    }
}
```
## Example (YouTube)
```js
const { ytdown } = require("shaon-videos-downloader")
let URL = await ytdown("https://youtu.be/aRSuyrZFu_Q?si=bsfzgeeGmRpsHqnF")
console.log(URL)
```
## Example (Twitter)
```js
const { twitterdown } = require("shaon-videos-downloader")
let URL = await twitterdown("https://twitter.com/TeamAbhiSha/status/1743351410761019794?t=vms8wxcU0mQuhVxwGCHjFw&s=19")
console.log(URL)
```
## Output Example (Twitter)
```
{
    "developer": "MOHAMMAD SHAON",
    "devfb": "https://www.facebook.com/profile.php?id=100000959749712",
    "devwp": "wa.me/+8801615298449",
    "status": true,
    "data": {
        "HD": "https://video.twimg.com/ext_tw_video/1743351351898181632/pu/vid/avc1/810x720/gKWI2KEyLdRMQBFa.mp4?tag=12",
        "SD": "https://video.twimg.com/ext_tw_video/1743351351898181632/pu/vid/avc1/404x360/dtDrE8AqyxXhoRhO.mp4?tag=12"
    }
}
```

## Example Fbdown2
```js
const { fbdown2 } = require("shaon-videos-downloader");
const request = require('request')

const key = "Nayan" //dont change key

const link = "url" //past video link

fbdown2(link, key).then(data => {
  console.log(data)
});
```
## Output Example (fbdown2)
```
{
    "developer": "MOHAMMAD SHAON",
    "devfb": "https://www.facebook.com/profile.php?id=100000959749712",
    "devwp": "wa.me/+8801615298449",
    "status": true,
    "media": {
               title: video title,
                hd: Hd video link,
                sd: normal video link
              }
}
```

## Usage GDLink 
```js
const {GDLink} = require("shaon-videos-downloader");

const url = 'url' // Public Google Drive Url

GDLink(url).then(data => {
  console.log(data)

});
```
## Usage Pintarest 
```js
const {pintarest} = require("shaon-videos-downloader");

const url = 'url' // pintarest post url

  pintarest(url).then(data => {
  console.log(data)
    });
```
## Usage CapCut 
```js
const { capcut } = require("shaon-videos-downloader");

const url = "link" // capcut link

capcut(url).then(data => {
  console.log(data)
});
```
## Usage Likee 
```js
const { likee} = require("shaon-videos-downloader");

 const url = "link" // past url
likee(url).then(data => { 
  console.log(data) 
});
```
## Usage Threads
```js
const { threads } = require("shaon-videos-downloader");

 const url = "link" // past url
threads(url).then(data => { 
  console.log(data) 
});
```
## Usage All Media Down
```bash
support url: facebook, tiktok, twitter, instagram, youtube, pinterest, gdrive, capcut, likee, threads
note: Let me know if any of the platforms you use are missing
```
```js
const {alldown} = require("shaon-videos-downloader");
const url = 'url' // past url

  alldown(url).then(data => {
  console.log(data)
    });
```
## Output Example (alldown)
```
{
    "author": "SHAON AHMED",
    "cp": "✅Successfully downloaded the video!🎀",
    "videos": [
        {
            "url": "https://video.fsgn24-1.fna.fbcdn.net/o1/v/t2/f2/m69/AQOVfz7sZ2FUWE3vf3y1XmeXAPxY8OvwOU21fVN2kPEtrpOwGLVi8qKwOMyzya44Lkf0tgWjcsaJOW5-HQJZeNMD.mp4?strext=1&_nc_cat=102&_nc_oc=AdltGwW8ja8YUIpm4aSDqrP9YQIU0lAgkZnE9eJSurwF_-ZsBuMAb4nNXnXfipuOE0U&_nc_sid=5e9851&_nc_ht=video.fsgn24-1.fna.fbcdn.net&_nc_ohc=2RcwEzz0CN4Q7kNvwGz_xoI&efg=eyJ2ZW5jb2RlX3RhZyI6Inhwdl9wcm9ncmVzc2l2ZS5GQUNFQk9PSy4uQzMuNzIwLmRhc2hfaDI2NC1iYXNpYy1nZW4yXzcyMHAiLCJ4cHZfYXNzZXRfaWQiOjExNDczNDI5MTcxNDA3NzMsInZpX3VzZWNhc2VfaWQiOjEwMTIwLCJkdXJhdGlvbl9zIjo5LCJ1cmxnZW5fc291cmNlIjoid3d3In0%3D&ccb=17-1&vs=c2d6c0a4cab8ed5&_nc_vs=HBksFQIYOnBhc3N0aHJvdWdoX2V2ZXJzdG9yZS9HRlNBVUIwZ0k4TkF3UlFDQUxfVE1wc19IazlHYm1kakFBQUYVAALIAQAVAhg6cGFzc3Rocm91Z2hfZXZlcnN0b3JlL0dLbkFVUjJyYWVGMVBOc0ZBUE9BdGF5aHUzWklickZxQUFBRhUCAsgBACgAGAAbAogHdXNlX29pbAExEnByb2dyZXNzaXZlX3JlY2lwZQExFQAAJsqEmPCS4IkEFQIoAkMzLBdAIzMzMzMzMxgZZGFzaF9oMjY0LWJhc2ljLWdlbjJfNzIwcBEAdQIA&_nc_zt=28&oh=00_AfF55wdhHxieGPXqeqMuoUO3MfY-SlK60-Rdec03s7WmMQ&oe=680FA110"
        },
        {
            "url": "https://video.fsgn24-2.fna.fbcdn.net/o1/v/t2/f2/m69/AQO0YKxhs-7i5GjCzlHCJKkYR-r3bFJAWWJ9r9e2TD2bxMftSD0f4q6BhYP2ya5mbpr2g9FDDY10EcPcjb26YNem.mp4?strext=1&_nc_cat=111&_nc_oc=AdmkJI-3l0dVnXiEMCzFQrxI7D9sgL5xV_6wEp0vh1tGEYCVEruwNuqo-7-kW2ByMn8&_nc_sid=8bf8fe&_nc_ht=video.fsgn24-2.fna.fbcdn.net&_nc_ohc=BPs0WrwWtDQQ7kNvwGS8axx&efg=eyJ2ZW5jb2RlX3RhZyI6Inhwdl9wcm9ncmVzc2l2ZS5GQUNFQk9PSy4uQzMuMzYwLnN2ZV9zZCIsInhwdl9hc3NldF9pZCI6MTE0NzM0MjkxNzE0MDc3MywidmlfdXNlY2FzZV9pZCI6MTAxMjAsImR1cmF0aW9uX3MiOjksInVybGdlbl9zb3VyY2UiOiJ3d3cifQ%3D%3D&ccb=17-1&_nc_zt=28&oh=00_AfHFawNKflh8p3QWFFLI75J4AH00wRgJBXZ1TpLAGfkbtQ&oe=680FAB83"
        }
    ]
}
```

[![WhatsApp](https://img.shields.io/badge/WhatsApp-green?style=for-the-badge&logo=whatsapp)](https://wa.me/+8801814587247)
[![Facebook](https://img.shields.io/badge/Facebook-green?style=for-the-badge&logo=facebook)](https://www.facebook.com/Hey.Its.Me.Shaon.Ahmed)
[![Messenger](https://img.shields.io/badge/Chat-Messenger-blue?style=for-the-badge&logo=messenger)](https://m.me/Hey.Its.Me.Shaon.Ahmed)
[![Github](https://img.shields.io/badge/Github-MrDarkYTgreen?style=for-the-badge&logo=github)](https://github.com/shaonproject)

