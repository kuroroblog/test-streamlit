# test-streamlit
test用streamlitです。

## zipをダウンロードしてから動作確認する

1. https://github.com/kuroroblog/test-streamlit へアクセスする。
2. 緑色の「Code」と書かれたボタンを選択
3. 「Download ZIP」を選択
4. ダウンロードされたzipファイルをデスクトップへ移動
5. zipファイルをダブルクリック
6. ターミナルを開く。
7. ターミナルを活用して、zipを展開して生成されたフォルダへ移動する。(`$ cd Desktop/test-streamlit-master`)
8. `$ git init`を実行する。
9. `$ git add .`を実行する。
10. `$ git commit -m "first commit"`を実行する。
11. `$ heroku create`を実行する。
12. `$ git push heroku master`を実行する。
13. `$ heroku open`を実行する。

## 実行結果
<img width="1680" alt="screenshot 2021-12-31 9 27 01" src="https://user-images.githubusercontent.com/23373288/147796304-4b9fda59-eb43-45a8-ad4b-61c72bad14f5.png">

## 参考文献
- https://note.nkmk.me/python-pip-install-requirements/
