🔗 サーバーレスURL短縮サービス

このプロジェクトは、サーバーを必要とせずにブラウザ上で動作するシンプルなURL短縮サービスです。短縮されたURLの情報は、ブラウザのローカルストレージに保存されます。

🚀 概要

ウェブサイトのURLを短縮し、その短縮URLを生成します。生成された短縮URLは、同じブラウザでアクセスした場合に元のURLにリダイレクトされます。

主な特徴:

サーバー不要: Python (Flask) などのバックエンドサーバーは必要ありません。すべてのロジックはHTMLファイル内のJavaScriptで完結します。

ローカルストレージ保存: 短縮されたURLとその元のURLのマッピングは、ユーザーのブラウザのローカルストレージに保存されます。

シンプルなUI: 直感的で使いやすいインターフェースを提供します。

ダークモード対応: システム設定に応じて、自動的にライトテーマとダークテーマが切り替わります。

レスポンシブデザイン: 様々なデバイスの画面サイズに適応します。

✨ 機能

URL短縮: 長いURLを短くします。

短縮URLの表示: 生成された短縮URLをすぐに表示します。

短縮URLのコピー: ワンクリックで短縮URLをクリップボードにコピーできます。

フォームのリセット: 入力フォームを簡単にリセットし、新しいURLを短縮できます。

著作権表示の自動更新: フッターの著作権表示が自動的に現在の年に更新されます。

クライアントサイドリダイレクト: 短縮URLにアクセスすると、JavaScriptによって元のURLにリダイレクトされます。

💡 使い方

このプロジェクトのindex.htmlファイル（現在右側に表示されているコード）を、お好みのテキストエディタで開き、index.htmlという名前で保存します。

もしウェブサイトのアイコンを表示したい場合は、icon.svgファイルをindex.htmlと同じフォルダに配置してください。

保存したindex.htmlファイルをウェブブラウザ（Chrome, Firefox, Safariなど）で直接開きます。

表示された入力欄に短縮したいURLを入力し、「短縮する」ボタンをクリックします。

短縮されたURLが表示されるので、「コピー」ボタンでクリップボードにコピーできます。

コピーした短縮URLを同じブラウザのアドレスバーに貼り付けてアクセスすると、元のURLにリダイレクトされます。

⚠️ 注意点

このサービスはサーバーにデータを保存しないため、短縮されたURLは、そのURLを作成したブラウザでのみ機能します。

別のブラウザ、別のデバイス、またはブラウザのローカルストレージをクリアした場合、以前に生成した短縮URLは機能しなくなります。

これは、個人利用やテスト目的、または特定のブラウザ内でのみ有効な短縮リンクが必要な場合に適しています。

📚 使用ライブラリ

このプロジェクトは、主に標準のウェブ技術（HTML, CSS, JavaScript）とブラウザの組み込み機能を使用しています。

Google Fonts: フォントの表示に利用しています。

'M PLUS Rounded 1c'

'Comic Neue'

ブラウザの組み込みAPI:

localStorage (データの保存)

navigator.clipboard または document.execCommand('copy') (クリップボードへのコピー)

window.location.hash (URLハッシュの操作)

その他の標準的なDOM操作、イベントリスナー、Dateオブジェクトなど

📄 ライセンス

このプロジェクトはMITライセンスの下で公開されています。

MIT License

Copyright (c) 2025 hamusata

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


👨‍💻 開発者

@hamusata
