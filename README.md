# Fyuk-CSS
自作のCSSライブラリ(？)  
npmなどでの配布予定は今のところないです。  
あくまで自分用に開発しているので、サポートや、詳しいガイドなどは作成しない予定です。  
もし何かあればissuesにどうぞ。

## ファイル構成

```
FYUK-CSS/
├── dist/
│   └── fyuk.css                 # コンパイル済みCSSファイル
├── src/
│   ├── base/                    # 基礎設定
│   │   ├── _mixins.scss         # 再利用可能なmixin関数
│   │   ├── _reset.scss          # ブラウザデフォルトスタイルのリセット
│   │   ├── _root.scss           # CSS変数・ルート設定
│   │   ├── _typography.scss     # 見出し、段落、フォント設定
│   │   └── _variables.scss      # SCSS変数定義
│   ├── components/              # UIコンポーネント
│   │   ├── _alerts.scss         # アラート・通知メッセージ
│   │   ├── _badges.scss         # バッジ・ラベル
│   │   ├── _buttons.scss        # ボタンコンポーネント
│   │   ├── _cards.scss          # カードコンポーネント
│   │   ├── _forms.scss          # フォーム要素（input、select等）
│   │   ├── _modals.scss         # モーダルウィンドウ
│   │   ├── _navigation.scss     # ナビゲーション・メニュー
│   │   └── _tables.scss         # テーブルスタイル
│   ├── layout/                  # レイアウト構造
│   │   ├── _footer.scss         # フッター部分
│   │   ├── _grid.scss           # グリッドシステム
│   │   ├── _header.scss         # ヘッダー部分
│   │   └── _sidebar.scss        # サイドバー
│   ├── utilities/               # ユーティリティクラス
│   │   ├── _colors.scss         # 背景色・文字色クラス
│   │   ├── _display.scss        # display・visibility関連
│   │   ├── _layout.scss         # flex・grid・container等
│   │   ├── _sizing.scss         # width・height関連
│   │   ├── _spacing.scss        # margin・padding関連
│   │   └── _text.scss           # text-align・font-weight等
│   └── main.scss                # 全ファイルのインポート統合
├── README.md                    # プロジェクト説明書
└── test.html                    # テスト・デモ用HTMLファイル
```

### 各ディレクトリの役割

- **base/**: ライブラリの基礎となる設定（変数、リセット、タイポグラフィ等）
- **components/**: 再利用可能なUIコンポーネント（ボタン、カード、フォーム等）
- **layout/**: ページ全体の構造に関わるスタイル（ヘッダー、フッター、グリッド等）
- **utilities/**: 単一目的の補助クラス（余白、色、サイズ等）
- **dist/**: コンパイル済みの配布用CSSファイル

あ、ライセンスは気にしていないです。  
好きに使ってください。（もしよければオープンソースで）
