# My Data Science 100 Knocks Solutions

データサイエンス100本ノック（構造化データ）を自分のペースで進めるリポジトリです。

## クイックリンク
作業効率化のために直接アクセスできるようにリンクを貼っています。

- [Python版 解答はこちら](./docker/work/preprocess_knock_Python.ipynb)
- [R版 解答はこちら](./docker/work/preprocess_knock_R.ipynb)
- [SQL版 解答はこちら](./docker/work/preprocess_knock_SQL.ipynb)

## 学習進捗
- **Python**: 9/100 問
<progress value="9" max="100"></progress>
- **R**: 1/100 問
<progress value="1" max="100"></progress>
- **SQL**: 1/100 問
<progress value="1" max="100"></progress>

## 実行環境
このリポジトリはDockerを使用して分析環境を構築します。
### 1. **コンテナの起動・終了**
WSL（Ubuntu）のターミナルで、リポジトリのルートディレクトリに移動して実行します。
- **起動**: `docker compose up -d`
- **終了**: `docker compose down`
### 2. **接続**
VSCodeなどのエディタでいずれかのファイルを開き、「カーネルの選択 (Select Kernel)」→「既存のJupyterサーバー (Existing Jupyter Server)」を選択。  
URLとして`http://localhost:8888`を入力
### 3. **カーネルの選択**
- Python/SQL: `Python3(ipykernel)(preprocess_knock_Python.ipynb) localhost`を選択
  - ※ SQLはPythonノートブック内でマジックコマンド（`%%sql`など）を使用して実行します。
- R: `R /R(localhost)`を選択

## LICENSE & Credits
- 元リポジトリ: [The-Japan-DataScientist-Society/100knocks-preprocess](https://github.com/The-Japan-DataScientist-Society/100knocks-preprocess)
- 本リポジトリ内のファイルは、元プロジェクトのMITライセンスに従います。
- `docker/doc/100knocks_guide.pdf` はCC-BY-NDライセンスです。