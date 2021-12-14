# 🐳

## 環境構築

### 1. 「docker-4-books-manager」リポジトリをテンプレートとして、自身のGithubに「books_manager」リポジトリを作成

### 2. ローカルにcloneする

### 3. 「Dockerの起動」と「Laravelのインストール」

```bash
$ make create-project # Install the latest Laravel project
```

### 4. Laravelがインストールできているか確認

http://localhost

## その他コマンド

### 使われているポートの確認

```bash
$ docker ps
```

### 使われているポートのkill
```bash
$ docker kill [CONTAINER ID]
```
