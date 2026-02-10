# Flash Attention v2 Windows Prebuild

针对 Windows 环境下 ComfyUI训练编译的 Flash Attention v2 预编译包。

## 📦 环境信息 (Environment)
- **Python**: 3.11
- **Torch**: 2.8.0.dev (或你实际的 2.8.0 版本)
- **CUDA**: 12.8
- **Arch**: sm_89 (适合 NVIDIA RTX 40 系列显卡)
- **OS**: Windows 10/11

## 🚀 安装方法 (Installation)
1. 下载 `Release` 中的 `.whl` 文件。
2. 在你的 Python 环境中运行：
   ```bash
   pip install flash_attn-2.8.3-cp311-cp311-win_amd64.whl
