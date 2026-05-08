# Vibe Coding A4

## 运行方式

```bash
/Users/qiudianer/Desktop/pycharm/.venv311/bin/python -m streamlit run app.py
```

运行后浏览器访问 Streamlit 给出的本地地址，通常是 `http://localhost:8501`。

## 文件说明

- `app.py`：核心源码，包含交互式 Web app 与四个机器学习演示模块。
- `make_report.py`：生成截图和 PDF 实验报告的脚本。
- `screenshots/`：报告中使用的截图。
- `outputs/Vibe_Coding_A4_Report.pdf`：PDF 实验报告。
- `data/`：可选数据目录。如果有真实 CIFAR-10 Python batch 数据，可放在 `data/cifar-10-batches-py/`；没有时程序会使用离线 CIFAR-10 风格图像数据完成演示。

## 使用的 Agent / LLM

- Codex（GPT-5 系列）
