# Video Started

### 

## Javascript Code
```js
window.appEventData = window.appEventData || [];
appEventData.push({
  "event": "Video Started",
    "video": {
        "secondsLength": "<secondsLength>",
        "videoID": "<videoID>",
        "videoName": "<videoName>"
    }
});
```

## Variable Definitions

|Field|Type|Description|Example|Pattern|Min Length|Max Length|Minimum|Maximum|Multiple Of|
| --- | --- | --- | --- | --- | --- | --- | --- | --- | --- |
|secondsLength|integer|The total length of the video in seconds|36, 67, 178, 600||||0|||
|videoID|string|Video ID|YT456789, BC4567890, 876546789|||||||
|videoName|string|Video Name|Twitch_FPS, Age of Empires, Halo|||||||
