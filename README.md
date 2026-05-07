# いろ・啼鳥 第一号 Book Viewer

PDFを本のように読むための静的サイトです。

## 起動方法

このフォルダでターミナルを開いて、以下を実行してください。

```bash
python3 -m http.server 8000
```

ブラウザで開きます。

```text
http://localhost:8000
```

## 公開方法

GitHub Pagesなどに、このフォルダの中身をそのままアップロードしてください。

- `index.html`
- `pdf/issue01.pdf`

## 注意

`index.html`をダブルクリックして `file://` で開くと、ブラウザの制限でPDFが読めないことがあります。必ずローカルサーバー、またはWebサーバー上で開いてください。
