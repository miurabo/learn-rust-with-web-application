# 【Webアプリ開発で学ぶ よくわかるRustプログラミング入門】参考実装

書籍[Webアプリ開発で学ぶ よくわかるRustプログラミング入門](https://www.amazon.co.jp/dp/4798067318)の題材であるTodoアプリの参考実装です。

## RUST を選択するメリット
- 速度
- 開発効率？
- 将来性

## todo-api

### dbの起動
```sh
sudo lsof -i:5432
sudo launchctl list | grep xxx
sudo launchctl unload -w /Library/LaunchDaemons/postgresql-16.plist
make db
```
### apiの起動
```sh
cargo install sqlx-cli
cargo install cargo-watc
make dev
```
### frontの起動
```sh
npm i
npm run dev
```