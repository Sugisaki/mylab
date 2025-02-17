# mylab

## プライバシーポリシー
./android には静的ページ、プライバシーポリシー。
roundrun は日本語ページと英語ページがあるので注意。
### シンフリーサーバーにプライバシーポリシーをデプロイ
静的ページはこのスクリプトでコピーする。
upload_privacy_to_shin-server.sh


## React チュートリアルページ
React ビルドの生成物は react-project/dist
### Vercelに Reactデプロイ
React はワークフロー使わずにデプロイ。
Vercel ではワークフローで Reactと静的ページを混ぜる処理できないので、
静的ページは別途。


## GitHubワークフローで GitHub Pagesにデプロイ
.github/workflows/deploy.yml
Reactページと静的ページ、両方デプロイしたいので、
./deployment ディレクトリに両方をコピーしてアップロードする。

