# <img src="./favicon.ico"> Primer on Statistics

這是一本記錄基礎統計學的書，並且盡可能都有程式碼能做範例。

## 在本地開發

須先安裝 [poetry](https://python-poetry.org/)

```bash
pip install poetry
```

然後建立虛擬環境與安裝需要的套件

```bash
poetry env use [PYTHON_PATH]

poetry install
```

再來就可以在本地架起這本書了

```bash
poetry run jb build .
```

可以在 `./_build/html`找到編譯的結果。

## License

[MIT](https://github.com/r05323028/primer-on-statistics/LICENSE)
