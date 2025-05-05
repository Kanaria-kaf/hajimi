# 使用你在 GitHub Container Registry (GHCR) 上的镜像作为基础镜像
FROM ghcr.io/Kanaria-kaf/hajimi:latest

# 容器内部暴露的端口
EXPOSE 7860

# 启动命令 —— 用 Uvicorn 启动 FastAPI 应用
CMD ["uvicorn", "app.main:app", "--host", "0.0.0.0", "--port", "7860"]
