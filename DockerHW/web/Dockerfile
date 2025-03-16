FROM python:3.9

# 設定工作目錄
WORKDIR /app

# 複製應用程式到容器
COPY . /app

# 安裝 Flask
RUN pip install flask

# 指定 Flask 入口點
CMD ["python", "main.py"]

# 允許外部訪問 5000 端口
EXPOSE 5000