![popup-id](https://github.com/feeloursoul/YouTube-ID-popup/assets/152250183/e5310ef6-075e-4771-ac7e-60ed4e40f1d1)


<br>
<br>
上の画像のように簡単にYouTubeの動画のIDを取得することが可能です。
<br>
<br>
<br>
<br>
<br>
以下のコードをコピーしてブラウザのブックマークバーにドラッグ&ドロップしてください。
<br>
<br>

```
javascript:(function(){ var currentUrl = window.location.href; var videoId = currentUrl.split('v=')[1]; if(videoId){ var ampersandPosition = videoId.indexOf('&'); if(ampersandPosition !== -1) { videoId = videoId.substring(0, ampersandPosition); } window.prompt("Youtube%E5%8B%95%E7%94%BB%E3%81%AEID:", videoId); } else { alert("Youtube%E5%8B%95%E7%94%BB%E3%81%AEURL%E3%81%A7%E3%81%AF%E3%81%82%E3%82%8A%E3%81%BE%E3%81%9B%E3%82%93%E3%80%82"); } })();
```
<br>
<br>
Youtubeの動画が表示されてるページ上でブックマークレットをクリックします。
<br>
<br>
ブックマークレット名を好きな名前にリネームしてください。
<br>
<br>
今見ている動画の「ID」番号がポップアップ出力されます。



