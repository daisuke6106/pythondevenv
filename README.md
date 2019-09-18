# python develop envbase

# 元リポジトリでやること
## activate
source venv/bin/activate

## 依存ライブラリを出力
pip freeze > requirements.txt
git add requirements.txt
git commit

# クローン先のリポジトリのやること
## activate
source venv/bin/activate

## 依存ライブラリのインストール
pip install -r requirements.txt

## 参考
https://qiita.com/m-masaki72/items/7ba34e31d9f08662f1ee
