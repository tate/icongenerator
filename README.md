# 🎨 アイコン生成ツール

シンプルで使いやすいWebベースのアイコン生成ツールです。文字列と図形を組み合わせて、複数サイズのPNGアイコンを一度に生成できます。

![アイコン生成ツール](https://img.shields.io/badge/HTML5-Canvas-orange?style=flat-square&logo=html5)
![JavaScript](https://img.shields.io/badge/JavaScript-Vanilla-yellow?style=flat-square&logo=javascript)
![PNG](https://img.shields.io/badge/Output-PNG-blue?style=flat-square)

## ✨ 機能

- **文字入力**: 任意の文字列でアイコンを作成
- **図形選択**: 丸、正方形、長方形、または図形なしを選択可能
- **色カスタマイズ**: 文字色と図形色を自由に設定
- **複数サイズ出力**: 16×16, 32×32, 48×48, 128×128ピクセル
- **PNG形式**: 高品質で透明度サポート
- **リアルタイムプレビュー**: 設定変更時に即座にプレビュー更新
- **一括ダウンロード**: 全サイズを一度にダウンロード可能

## 🚀 使い方

1. **インストール不要**: HTMLファイルをブラウザで開くだけ
2. **文字列入力**: アイコンに表示したい文字を入力
3. **設定選択**: 図形、文字色、図形色を選択
4. **生成**: 「アイコンを生成」ボタンをクリック
5. **ダウンロード**: 個別または一括でPNGファイルをダウンロード

## 📁 ファイル構成

```
icon-generator/
├── icon-generator.html    # メインファイル（ツール本体）
└── README.md             # このファイル
```

## 🌐 デモ

### スクリーンショット例

アプリケーションの主な画面：
- 入力フォーム（文字列、図形選択、色選択）
- リアルタイムプレビュー（4種類のサイズ）
- ダウンロードボタン

### 出力ファイル名

生成されるファイル名の形式：
- `icon16.png` (16×16ピクセル)
- `icon32.png` (32×32ピクセル) 
- `icon48.png` (48×48ピクセル)
- `icon128.png` (128×128ピクセル)

## 🔧 技術仕様

- **HTML5**: 構造とマークアップ
- **CSS3**: レスポンシブデザインとスタイリング
- **JavaScript (Vanilla)**: Canvas APIを使用した描画処理
- **Canvas API**: 図形描画とテキストレンダリング
- **Blob API**: PNG形式でのファイル生成

## 🎯 対応ブラウザ

- Chrome 50+
- Firefox 45+
- Safari 10+
- Edge 79+

## 📝 ライセンス

MIT License

```
MIT License

Copyright (c) 2025 [Your Name]

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.
```

## 🤝 貢献

プルリクエストや課題の報告を歓迎します！

1. このリポジトリをフォーク
2. 新しい機能ブランチを作成 (`git checkout -b feature/amazing-feature`)
3. 変更をコミット (`git commit -m 'Add some amazing feature'`)
4. ブランチにプッシュ (`git push origin feature/amazing-feature`)
5. プルリクエストを作成

## 📊 今後の改善予定

- [ ] SVG出力フォーマット対応
- [ ] より多くの図形オプション（三角形、星形など）
- [ ] グラデーション色対応
- [ ] カスタムフォント選択
- [ ] 画像インポート機能
- [ ] バッチ処理機能

## 🐛 バグ報告・機能要求

GitHubのIssuesページにて報告をお願いします。

## 📞 お問い合わせ

プロジェクトに関するご質問は、GitHubのIssuesにお願いします：
- GitHub: [@tate](https://github.com/tate)

---

⭐ このプロジェクトが少しでも役立った場合は、スターを付けていただけると嬉しいです！
