# 学園アイドルマスター IME辞書

[![GitHub Pages](https://img.shields.io/badge/GitHub%20Pages-配布サイト-blue?logo=github)](https://andam0202.github.io/gakumasu_dict.github.io/)
[![License](https://img.shields.io/badge/License-MIT-green)](LICENSE)

学園アイドルマスターの登場人物名・楽曲名・用語を効率的に入力できるWindows向けIME辞書です。

## 📋 概要

「**清夏**」「**琴歌**」「**環**」など、学園アイドルマスターには変換が難しい名前がたくさんあります。この辞書を使用することで、読み方を入力するだけで一発変換が可能になります。

### ✨ 特徴

- 🎯 **登場人物名** - 月村手毬、花海咲季、藤田ことね など
- 🎵 **楽曲名** - 各種楽曲タイトルを収録
- 📚 **専門用語** - 学マス関連の用語を網羅
- ⚡ **即座に変換** - 読み方を入力するだけで一発変換
- 🆓 **完全無料** - GitHub経由で安全にダウンロード

## 🚀 クイックスタート

### 1. 辞書ファイルをダウンロード
[**📥 配布サイトからダウンロード**](https://andam0202.github.io/gakumasu_dict.github.io/)

### 2. IMEに登録
1. タスクバーの「あ」または「A」を右クリック
2. 「プロパティ」→「詳細設定」→「辞書/学習」タブ
3. 「追加」ボタンをクリックして辞書ファイルを選択

### 3. 動作確認
メモ帳で「てまり」と入力し、変換候補に「手毬」が表示されれば成功！

## 📖 使用例

| 読み | 変換結果 |
|------|----------|
| `せいか` | 清夏 |
| `ことか` | 琴歌 |
| `たまき` | 環 |
| `てまり` | 手毬 |
| `さき` | 咲季 |
| `ことね` | ことね |

## 🛠️ 開発・貢献

### ローカル環境での実行

```bash
# リポジトリをクローン
git clone https://github.com/andam0202/gakumasu_dict.github.io.git
cd gakumasu_dict.github.io

# Jekyll環境のセットアップ
cd docs
bundle install

# ローカルサーバーを起動
bundle exec jekyll serve
```

### ディレクトリ構成

```
├── docs/                    # GitHub Pages用ディレクトリ
│   ├── _config.yml         # Jekyll設定
│   ├── index.md           # メインページ
│   ├── assets/
│   │   └── gakumasu_dict.txt  # 辞書ファイル
│   └── ...
├── CLAUDE.md              # AI開発用指針
├── dev.md                 # 開発手順メモ
└── README.md              # このファイル
```

### 貢献方法

1. このリポジトリをフォーク
2. 新しいブランチを作成 (`git checkout -b feature/improvement`)
3. 変更をコミット (`git commit -am 'Add some improvement'`)
4. ブランチにプッシュ (`git push origin feature/improvement`)
5. プルリクエストを作成

## 🔄 更新履歴

定期的に以下の改善を行っています：

- 新しいキャラクターの追加
- 楽曲名の更新
- 変換精度の向上
- ユーザビリティの改善

最新版は常に[配布サイト](https://andam0202.github.io/gakumasu_dict.github.io/)からダウンロードできます。

## ❓ よくある質問

**Q: 他のIME（Google日本語入力など）でも使えますか？**  
A: 現在はMicrosoft IME向けの形式です。他のIME対応も検討中です。

**Q: 辞書の内容を確認したい**  
A: [辞書ファイル](docs/assets/gakumasu_dict.txt)はテキスト形式なので、直接確認できます。

**Q: 不具合や追加要望がある場合は？**  
A: [Issues](https://github.com/andam0202/gakumasu_dict.github.io/issues)でお気軽にご報告ください。

## 📝 ライセンス

このプロジェクトは[MITライセンス](LICENSE)の下で公開されています。

## 🎵 クレジット

学園アイドルマスターの世界観とキャラクターは株式会社バンダイナムコエンターテインメントに帰属します。

---

<div align="center">
  <strong>🎵 学園アイドルマスターファンの皆様の快適な創作活動を応援します！</strong>
</div>