# RUSTのテスト

## 環境構築
curl https://sh.rustup.rs -sSf | sh

## パスを通す
source ~/.cargo/

## rust最新版
rustup default nightly

## wasm32
rustup target add wasm32-unknown-unknown

## ファイル実行
rustc 実行ファイル
