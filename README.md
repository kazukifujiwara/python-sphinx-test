# python-sphinx-test

## インストール済 Sphinx関連ライブラリ

```
$ pip3 freeze | grep sphinx
sphinx-rtd-theme==1.0.0
sphinxcontrib-applehelp==1.0.2
sphinxcontrib-devhelp==1.0.2
sphinxcontrib-htmlhelp==2.0.0
sphinxcontrib-jsmath==1.0.1
sphinxcontrib-qthelp==1.0.3
sphinxcontrib-serializinghtml==1.1.5
```

## フォルダ構成

```./docs/``` 配下はsphinxコマンドで生成されたファイル

```
.
├── README.md
├── docs
│   ├── Makefile
│   ├── _build
│   │   ├── _static
│   │   │   └── (省略)
│   │   ├── index.html
│   │   └── objects.inv
│   ├── _static
│   ├── _templates
│   ├── conf.py
│   ├── index.rst
│   ├── main.rst
│   ├── make.bat
│   └── modules.rst
└── main.py
```

[Sphinxの使い方．docstringを読み込んで仕様書を生成](https://qiita.com/futakuchi0117/items/4d3997c1ca1323259844) に従い、以下のファイルを書き換えた。

* conf.py
* index.rst



## 参考

* [Sphinxの使い方．docstringを読み込んで仕様書を生成](https://qiita.com/futakuchi0117/items/4d3997c1ca1323259844)