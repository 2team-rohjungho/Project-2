

```markdown
# プロジェクト 2: 観光客向けカフェ推薦ウェブアプリケーション

## プロジェクト概要
このプロジェクトは、日本の特定地域（例：神戸）で韓国人観光客がカフェを推薦されるウェブアプリケーションです。ユーザーの音声入力をSTT（Speech to Text）を通じてテキストに変換し、ChatGPT APIを使用して条件に合ったカフェリストと生成された画像を提供します。

## 機能
- 音声認識（STT）を通じたユーザー入力の処理
- ChatGPT APIを用いたカフェ推薦の生成
- カフェ関連の画像生成と視覚的な推薦

## 使用技術
- **バックエンド**: FastAPI、Python
- **フロントエンド**: HTML、CSS、JavaScript
- **API**: Google STT API、OpenAI ChatGPT API
- **その他**: JSONフォーマット、外部API連携

## インストール方法
1. このリポジトリをクローンします。
   ```bash
   git clone https://github.com/username/project2.git
