# コンテナのビルド

## 手動でビルドする場合

```bash
$ docker buildx bake -f docker-compose.yml
$ docker compose up -d
```

## vscodeのremote containerでビルドする場合

`Open Folder in Container`でルートディレクトリを開く

# cmakeの利用方法

## ビルド

```bash
$ cmake -S . -B build
$ cmake --build build
```

## 実行

```bash
$ ./build/hello 
Hello World!
```
