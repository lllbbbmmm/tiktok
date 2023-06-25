
##Tiktok视频功能摘要
 
-包含TikTok &&高清视频，没有水印 
 
-包含TikTok &&抖音音乐和用户、帖子、搜索、提要、评论、追随者和趋势。 
 
-包含搜索tiktok关键字… 
 
-Api地址https://rapidapi.com/llbbmm/api/tiktok-download-video1/
 
 使用方法 
-首先，如果您还没有快速平台账户，请先注册该账户， 
-然后单击打开 TikTok API https://rapidapi.com/llbbmm/api/tiktok-download-video1/pricing 订阅基本的免费程序，然后您可以使用它到您的工作 
-如果您有任何问题，请通过电子邮件850784744@qq.com联系我

## Tiktok Video Feature Summary

the tiktok && douyin api in rapid 
- Contains TikTok && HD videos without watermark 
- Contains TikTok && douyin music and user, post, search, feeds, comments, followers, and trends.
- Contains Search tiktok keywords ...

- [The Api Address](https://rapidapi.com/llbbmm/api/tiktok-download-video1/).

### Usage method

- Firstly, if you do not already have a Rapid platform account, register the account first, 
- Then click to open the [ TikTok API](https://rapidapi.com/llbbmm/api/tiktok-download-video1/pricing) and subscribe to the basic free program and then you can use it to your work
- If you have any questions, please contact me via email by 850784744@qq.com


```angular2
// php
<?php

$curl = curl_init();

curl_setopt_array($curl, [
	CURLOPT_URL => "https://tiktok-video-feature-summary.p.rapidapi.com/?url=https%3A%2F%2Fwww.tiktok.com%2F%40user954840753%2Fvideo%2F7229174351906573569&hd=1",
	CURLOPT_RETURNTRANSFER => true,
	CURLOPT_ENCODING => "",
	CURLOPT_MAXREDIRS => 10,
	CURLOPT_TIMEOUT => 30,
	CURLOPT_HTTP_VERSION => CURL_HTTP_VERSION_1_1,
	CURLOPT_CUSTOMREQUEST => "GET",
	CURLOPT_HTTPHEADER => [
		"X-RapidAPI-Host: tiktok-video-feature-summary.p.rapidapi.com",
		"X-RapidAPI-Key: your api key"
	],
]);

$response = curl_exec($curl);
$err = curl_error($curl);

curl_close($curl);

if ($err) {
	echo "cURL Error #:" . $err;
} else {
	echo $response;
}

```

```angular2
// python 
import http.client

conn = http.client.HTTPSConnection("tiktok-video-feature-summary.p.rapidapi.com")

headers = {
    'X-RapidAPI-Key': "your api key",
    'X-RapidAPI-Host': "tiktok-video-feature-summary.p.rapidapi.com"
}

conn.request("GET", "/?url=https%3A%2F%2Fwww.tiktok.com%2F%40user954840753%2Fvideo%2F7229174351906573569&hd=1", headers=headers)

res = conn.getresponse()
data = res.read()

print(data.decode("utf-8"))
```

```angular2
// respones
{
  "code": 0,
  "msg": "success",
  "processed_time": 0.3789,
  "data": {
    "aweme_id": "v10025g50000ch9iurbc77u4pv6q62b0",
    "id": "7229174351906573569",
    "region": "TW",
    "title": "#",
    "cover": "https://p16-sign-sg.tiktokcdn.com/obj/tos-alisg-p-0037/ab1fe4defdb84f2f881a720372b3c3d7_1683173419?x-expires=1685678400&x-signature=aYnweo3x2AKBsoohOwTqGBXcWAI%3D&s=AWEME_DETAIL&se=false&sh=&sc=dynamic_cover&l=202306010448047E6EEACCAF37736F5C8A",
    "origin_cover": "https://p16-sign-sg.tiktokcdn.com/tos-alisg-p-0037/53fcbd72d5404391905cd4916e8848a7_1683173421~tplv-tiktokx-360p.jpeg?x-expires=1685678400&x-signature=R65%2BKm%2B6uEnONLhB%2FyMEIpm14ho%3D&s=AWEME_DETAIL&se=false&sh=&sc=feed_cover&l=202306010448047E6EEACCAF37736F5C8A",
    "duration": 453,
    "play": "https://v16m-default.akamaized.net/db3ab878acafc7ceafe06048cf448450/6478792a/video/tos/alisg/tos-alisg-pve-0037/o0B8VkyBzjehCKfViCEQMhAQ2MgtW2ET85UIFz/?a=0&ch=0&cr=0&dr=0&lr=all&cd=0%7C0%7C0%7C0&cv=1&br=792&bt=396&cs=0&ds=6&ft=iJOG.y7oZzv0PD1S4NlXg9w0t-MrBEeC~&mime_type=video_mp4&qs=0&rc=Nmg5ZDxmOTw6ZTo1ZjU2NUBpMzV0eTc6ZnVsazMzODgzNEBhMzUzMTJeX18xXi1jMjY2YSNfMzNtcjRfcjZgLS1kLy1zcw%3D%3D&l=202306010448047E6EEACCAF37736F5C8A&btag=e00080000",
    "wmplay": "https://v16m-default.akamaized.net/c20ec8accc1cea98c2cef269d95eeaa6/6478792a/video/tos/alisg/tos-alisg-pve-0037/oQtRDnHUg9JVAQtMk4Iy5KeeCGBmQybYBEgsnD/?a=0&ch=0&cr=0&dr=0&lr=all&cd=0%7C0%7C0%7C0&cv=1&br=1012&bt=506&cs=0&ds=3&ft=iJOG.y7oZzv0PD1S4NlXg9w0t-MrBEeC~&mime_type=video_mp4&qs=0&rc=ZmU7O2k8NWk8OjhnOGQ8ZUBpMzV0eTc6ZnVsazMzODgzNEAvMV4wLjZhX2AxYmI0YF82YSNfMzNtcjRfcjZgLS1kLy1zcw%3D%3D&l=202306010448047E6EEACCAF37736F5C8A&btag=e00080000",
    "hdplay": "https://v16m-default.akamaized.net/e3d1730a293e7a9b58753cd37f6ffa74/6478792a/video/tos/alisg/tos-alisg-pv-0037/1953920f702d4ed0ba3353fc59ff55db/?a=0&ch=0&cr=0&dr=0&lr=all&cd=0%7C0%7C0%7C1&cv=1&br=12812&bt=6406&cs=0&ds=4&ft=iJOG.y7oZzv0PD1S4NlXg9w0t-MrBEeC~&mime_type=video_mp4&qs=13&rc=MzV0eTc6ZnVsazMzODgzNEBpMzV0eTc6ZnVsazMzODgzNEBfMzNtcjRfcjZgLS1kLy1zYSNfMzNtcjRfcjZgLS1kLy1zcw%3D%3D&l=20230601044804688D16D11F81306B663D&btag=e00040000",
    "size": 23018190,
    "wm_size": 29391844,
    "hd_size": 371978009,
    "music": "https://sf16-ies-music-sg.tiktokcdn.com/obj/tiktok-obj/7232255942115871490.mp3",
    "music_info": {
      "id": "7229174817214417666",
      "title": "original sound - user954840753",
      "play": "https://sf16-ies-music-sg.tiktokcdn.com/obj/tiktok-obj/7232255942115871490.mp3",
      "cover": "https://p16-sign-sg.tiktokcdn.com/aweme/1080x1080/tos-alisg-avt-0068/c6ad2a5bece82ac7f812d925359ffc6a.jpeg?x-expires=1685678400&x-signature=n%2Fk8m%2F52kHS5JOvDwV3x7pLvqkg%3D",
      "author": "直哉史魚",
      "original": true,
      "duration": 453,
      "album": ""
    },
    "play_count": 173636,
    "digg_count": 1652,
    "comment_count": 248,
    "share_count": 67,
    "download_count": 134,
    "create_time": 1683891000,
    "author": {
      "id": "6810725789928260614",
      "unique_id": "user954840753",
      "nickname": "直哉史魚",
      "avatar": "https://p16-sign-sg.tiktokcdn.com/tos-alisg-avt-0068/c6ad2a5bece82ac7f812d925359ffc6a~c5_300x300.jpeg?x-expires=1685678400&x-signature=JqDr7YIKxfbx7rKu03ewIWRDe9w%3D"
    }
  }
}
```  
