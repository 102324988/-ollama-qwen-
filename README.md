# 文章总结API系统

基于 Ollama 的批量文章总结分析 RESTful API 服务。

## 快速开始

### Windows 系统
1. 运行 `setup_environment.bat` 设置Python环境
2. 运行 `install_ollama.ps1` 安装Ollama
3. 运行 `python run_api.py` 启动服务

### Linux/Mac 系统
1. `chmod +x setup_environment.sh && ./setup_environment.sh`
2. `chmod +x install_ollama.sh && ./install_ollama.sh`  
3. `python run_api.py`

## API 使用
- 健康检查: `GET /api/health`
- API文档: `GET /api/docs`
- 开始分析: `POST /api/summary/start`
- 单篇总结: `POST /api/summary/single`
