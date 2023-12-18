以下のコードをコピーしてブックマークのバーにドラッグ&ドロップしてください。
<br>
<br>
```
javascript:(function(){ var currentUrl = window.location.href; var videoId = currentUrl.split('v=')[1]; if(videoId){ var ampersandPosition = videoId.indexOf('&'); if(ampersandPosition !== -1) { videoId = videoId.substring(0, ampersandPosition); } window.prompt("Youtube%E5%8B%95%E7%94%BB%E3%81%AEID:", videoId); } else { alert("Youtube%E5%8B%95%E7%94%BB%E3%81%AEURL%E3%81%A7%E3%81%AF%E3%81%82%E3%82%8A%E3%81%BE%E3%81%9B%E3%82%93%E3%80%82"); } })();
```
<br>
<br>
Youtubeの動画が表示されたページでこのブックマークレットをワンクリックします。
<br>
動画の「ID」番号が出力されます。
<br>
![YouTube-ID-extractor](https://github.com/feeloursoul/YouTube-ID-popup/assets/152250183/42cf5637-28d0-4475-a0e2-590ea8310efd)
<br>
<br>
以上になります。


