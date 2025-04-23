# CDISC-CORE-Rule-Browser

日本語ページはこちら [README-ja.md](https://github.com/HajimeShimizu/CDISC-CORE-Rule-Browser/blob/main/README-ja.md).

## Overview
CDISC is developing [CDISC Open Rules Engine (CORE)](https://github.com/cdisc-org/cdisc-rules-engine). This tool enables users to validate their deliverables based on CDISC standards. In CORE, many rules are executed, but the details of each rules are not open to general users. This tool lists all rules for specific standard and specific version and allows users to drill down details of each rule.

## Download
Visit release page（[Here](https://github.com/HajimeShimizu/CDISC-CORE-Rule-Browser/releases)）. In addition to this tool, rule cache file created by CORE is required.

## How to set up
- This tool refers cache file created by CORE
- Cache file should be located at folder "/resources/cache"
- More guide is found in this [page](https://note.com/cdisc/n/n2e23f6e1dad1).

## How to use
Tool is booted by double clicking .exe file\
\
<img width="600" alt="image" src="core_rule_browser.png">

### パラメータの指定
- 標準：COREのルールを確認したい標準を選びます
- バージョン：確認したい標準のバージョンを選びます

上記を指定後、「表示」ボタンを押してください

### ルールの検索
ルールはランダムな順番で表示されます（※意味のある順番にソートすることができません）。実際的には、リストされた一覧から関心のあるルールを検索することになります。検索ボックスにキーワードを入れ、リターンキーを押すことで、データが絞り込まれます。キーワードが空の状態でリターンキーを押すと、元の状態（最初の検索結果）に戻ります。

検索のヒント
- ドメイン名の指定は非現実的です。変数名など、別の条件を指定しましょう

### ルールの詳細
初期状態では、ルールのID・ドメイン情報・チェックの概要・エラーメッセージのみが表示されています。さらに詳しい情報を知りたい場合、任意のルールをダブルクリックします（ロジック部分の解読は難しいため、別途解説を用意する予定です）。

<img width="350" alt="image" src="core_rule_browser_detail.png">




