# Python

## 使用環境
Python: 3.13.1
### Linter
- Flake8

### Formatter
- Black

## ディレクトリ構成について
```
current/
├── .gitattributes
├── .gitignore
├── .flake8
├── .pyproject.toml
├── .github/
├── .venv/
├── .vscode/
├── README.md
├── src/
│   └── __init__.py
└── tests/
    └── __init__.py

```

## 環境構築

### VSCODE開発で必須の拡張機能
- ms-python.python
- ms-python.debugpy
- ms-python.black-formatter
- ms-python.flake8

### 依存ライブラリのインストール
```
pip install -r requirements.txt
```

### 依存ライブラリを `requirements.txt` に出力する方法
```
pip freeze > requirements.txt
```