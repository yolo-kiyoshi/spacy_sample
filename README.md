Dockerコンテナ上にEDA実行環境を構築します。

# 前提

- MacあるいはLinuxであること
- Dockerをインストールしていること  

# Dockerイメージの作成とコンテナ実行

## jupyter notebookでのスクリプト実行

以下のコマンドによりDockerコンテナをバックグラウンドで実行する。
```
docker-compose up -d
```

完了後、以下にアクセスする。  
<http://localhost:8080/lab>

## Dockerコンテナ内でのスクリプトの実行

以下のコマンドによりコンテナ内で`bash`を実行できます。

```
docker-compose run eda bash
```