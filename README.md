# Voice-changing App

语音变声应用，支持跨平台（Windows/macOS/Linux/Android/iOS）。

## 功能特性

- 实时语音变声
- 多种音色选择
- 跨平台支持
- 流式处理
- INT8量化推理
- 音色克隆

## 项目结构

```
Voice-changing app/
├── core/              # 核心功能模块
├── platforms/         # 平台特定实现
│   ├── windows/      # Windows平台
│   ├── android/      # Android平台
│   └── ios/          # iOS/macOS平台
├── tests/             # 测试文件
├── docs/              # 文档
└── scripts/           # 辅助脚本
```

## 安装

```bash
pip install -r requirements.txt
```

## 运行

```bash
python main.py
```

## 测试

```bash
pytest tests/
```

## CI/CD

项目使用GitHub Actions进行持续集成和部署：
- CI流水线：多版本Python测试和跨平台验证
- 代码质量检查：Ruff、Mypy、Bandit
- 自动发布：PyPI和GitHub Release

## 贡献

欢迎提交Issue和Pull Request！

## 许可证

MIT License