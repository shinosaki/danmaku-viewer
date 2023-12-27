# danmaku-viewer
NicoNico Live  viewer with [weizhenye/Danmaku](https://github.com/weizhenye/Danmaku)  

ニコ生の録画ファイルをコメント付きで再生するプレイヤーです。ブラウザで動作します。  
コメントの表示には [weizhenye/Danmaku](https://github.com/weizhenye/Danmaku) を使用しています。

![動作例](https://github.com/shinosaki/danmaku-viewer/assets/88357168/fc19be65-5e17-4d82-8c68-b20f3cd96a27)

## Usage / 使い方
Drag and drop the video/comment files to the top of the page.  

ページ上部の枠に、動画ファイルとコメントファイルをドラッグ＆ドロップします。もしくは、枠内をクリックして動画ファイルとコメントファイルを選択します。  

コメントファイルはこのようなJSON形式のファイルです。
```json
[
  {"thread":{"resultcode":0,"thread":"M.HS-SsES_iNE2we_ZUyzzCQ","revision":1,"server_time":1703500279,"last_res":null,"ticket":"c2fb418"}},
  {"chat":{"thread":"M.HS-SsES_iNE2we_ZUyzzCQ","no":1,"vpos":2160,"date":1703500281,"date_usec":609415,"name":"ワニノコ","user_id":"116054870","premium":1,"content":"ｐ"}},
  {"chat":{"thread":"M.HS-SsES_iNE2we_ZUyzzCQ","no":2,"vpos":2211,"date":1703500282,"date_usec":119524,"name":"たかぽりにあす","user_id":"30678345","premium":1,"content":"焦らないで焦らないで焦らないで焦らないで焦らないで焦らないで焦らないで焦らないで焦らないで"}},
  {"chat":{"thread":"M.HS-SsES_iNE2we_ZUyzzCQ","no":3,"vpos":2273,"date":1703500282,"date_usec":733925,"mail":"184","user_id":"Xw55LR1yc-yZGzk5Nhal5y9aGYY","anonymity":1,"content":"なんでや"}},
  {"chat":{"thread":"M.HS-SsES_iNE2we_ZUyzzCQ","no":4,"vpos":2593,"date":1703500285,"date_usec":934872,"mail":"184","user_id":"e7RKrVd_FrneHlck05i7z_ES1x0","premium":3,"anonymity":1,"content":"/info 10 「料理」が好きな3人、「コスプレ」が好きな3人が来場しました"}},
  {"chat":{"thread":"M.HS-SsES_iNE2we_ZUyzzCQ","no":5,"vpos":2833,"date":1703500288,"date_usec":337545,"mail":"184","user_id":"xaLsoaOrtveZzfOYpCqf8AEsdt0","premium":1,"anonymity":1,"content":"真顔でたすかる"}}
]
```

## LICENSE
[MIT](./LICENSE)
