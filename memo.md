１章まとめ

#　Node.js（Nodeのパッケージ管理ツールnpm）をインストールするメリット
- パフォーマンス最適化のためにJSやCSSを少数のファイルにまとめる(バンドル)
- 最新の機能を使用しているJSのコードをブラウザ実行時にpolyfilするのではなく最初からコンパイルしておく。
    polyfillは最近の機能をサポートしていない古いブラウザでも、その機能を使えるよう古い仕様に合わせてコードを自動的に変換すること。
- 開発中にローカルファイルをそのまま読み込ませず、ローカル環境で開発用のHTTPサーバを起動してそれ経由でアプリケーションを稼働させる。
- テストツールを用いてユニットテストやE2Eテストを記述する。
- ソフトウェアテストやコードの構文解析をローカル環境で実行する。
-