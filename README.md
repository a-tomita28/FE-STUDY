## 初回設定

### Pythonインストール(Pythonが入っていない場合)

```bash
brew install pyenv

# pyenvの初期化設定を.zshrcに追記
echo 'export PYENV_ROOT="$HOME/.pyenv"' >> ~/.zshrc
echo 'export PATH="$PYENV_ROOT/bin:$PATH"' >> ~/.zshrc
echo 'eval "$(pyenv init -)"' >> ~/.zshrc

# zshrcを再読み込み
source ~/.zshrc

pyenv install 3.13.3
pyenv global 3.13.3

# ここでバージョンが表示されればPythonのインストール完了
python --version
# → Python 3.13.3
```

### 必要なパッケージのインストール

```bash
# Python仮想環境の作成
python -m venv venv
source venv/bin/activate
# pipのアップグレード
pip install --upgrade pip
# MkDocs + Materialテーマのインストール
pip install -r requirements.txt
```

## 起動方法

```bash
# venv環境
source venv/bin/activate
# mkdocsの起動
mkdocs serve
```

### 補足情報

```bash
# venv環境から抜ける場合
deactivate
```
