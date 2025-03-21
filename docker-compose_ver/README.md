# My FastAPI App

這是一個使用 FastAPI 框架構建的應用程式，旨在展示商品列表並提供購買功能。

## 專案結構

```
my-fastapi-app
├── src
│   └── main.py          # 應用程式的主要入口點
├── templates
│   ├── index.html       # 主頁的 HTML 模板，顯示所有商品的列表
│   ├── item.html        # 顯示單個商品詳細資訊的 HTML 模板
│   └── final.html       # 顯示購買結果的 HTML 模板
├── Dockerfile            # Docker 的配置文件
├── docker-compose.yml    # Docker Compose 的配置文件
└── README.md             # 專案的文檔
```

## 使用指南

1. **安裝依賴**：
   確保您已安裝 Docker 和 Docker Compose。

2. **構建和運行應用**：
   在專案根目錄下運行以下命令：
   ```
   docker-compose up --build
   ```

3. **訪問應用**：
   打開瀏覽器並訪問 `http://localhost:8787` 以查看應用。

## 功能

- 顯示所有商品的列表。
- 查看單個商品的詳細資訊。
- 模擬購買商品的過程。

## 貢獻

歡迎任何形式的貢獻！請提交問題或拉取請求。