# 方向ガイド

iPhone Safariで使う方向案内の試作アプリです。

## GitHub Pagesで使う手順

1. GitHubで新しいリポジトリを作る
2. このフォルダの `index.html` と `README.md` をアップロードする
3. リポジトリの Settings > Pages を開く
4. Source を `Deploy from a branch`、Branch を `main`、Folder を `/root` にする
5. 表示された `https://...github.io/.../` のURLをiPhone Safariで開く

## 注意

iPhone Safariの方位センサーは、基本的にHTTPSページでないと動きません。
`http://192.168...` で開いた場合、画面表示はできますが方位が取れないことがあります。
