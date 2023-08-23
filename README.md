AI Art is an AI image generation and editing technology API service, which can intelligently create image content related to input by combining input pictures or text, with stronger Chinese understanding ability, more diversified style selection, and more Oriental aesthetic painting creation ability. Better support the generation of architectural scenery, ancient poetry understanding, ink paper-cutting and other Chinese elements in the Chinese scene, as well as the high-precision image generation and style conversion of various animation and game styles, to provide technical support for high-quality content creation and content operation.
Specifically provide the following API services:
Intelligent Vincennes diagram: Take Vincennes diagram. According to the input text description, intelligent generation of related results, supporting ink painting, oil painting, animation and other styles of image generation.


## How to use

- First, if you don't already have a Quick Platform account, please register it first

- and then click open the TikTok API subscription at https://rapidapi.com/llbbmm/api/drawing1 

- Then you can use any of the above interfaces

If you have any questions, please contact me at nb429429@gmail.com or 850784744@qq.com

```angular
//php
<?php
$curl = curl_init();
curl_setopt_array($curl, [
	CURLOPT_URL => "https://drawing1.p.rapidapi.com/aiDraw?description=Girl%20in%20the%20Rain&Styles=201&RspImgType=url&ResultConfig=768%3A768",
	CURLOPT_RETURNTRANSFER => true,
	CURLOPT_ENCODING => "",
	CURLOPT_MAXREDIRS => 10,
	CURLOPT_TIMEOUT => 30,
	CURLOPT_HTTP_VERSION => CURL_HTTP_VERSION_1_1,
	CURLOPT_CUSTOMREQUEST => "GET",
	CURLOPT_HTTPHEADER => [
		"X-RapidAPI-Host: drawing1.p.rapidapi.com",
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
