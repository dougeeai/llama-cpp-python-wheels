# llama-cpp-python-wheels
Pre-built wheels for llama-cpp-python across platforms and CUDA versions.

## Available Wheels

### Datacenter Blackwell (sm_100)
**Supported GPUs:** B100, B200, B300, GB200, GB300

> Note: Consumer Blackwell (RTX 50 series) and workstation Blackwell (RTX PRO 6000/5000/4500/4000 Blackwell) use compute capability 12.0 (sm_120), **not** sm_100. These wheels will not run natively on those cards — sm_120 wheels are a separate build (coming with llama-cpp-python 0.3.20).

| File | llama_cpp | OS | Python | CUDA | Driver | Size |
|------|-----------|-----|--------|------|--------|------|
| [llama_cpp_python-0.3.16+cuda13.0.sm100.blackwell-cp313-cp313-win_amd64.whl](https://github.com/dougeeai/llama-cpp-python-wheels/releases/download/v0.3.16-cuda13.0-sm100-py313/llama_cpp_python-0.3.16+cuda13.0.sm100.blackwell-cp313-cp313-win_amd64.whl) | 0.3.16 | Windows | 3.13 | 13.0 | 580+ | 65.9 MB |
| [llama_cpp_python-0.3.16+cuda13.0.sm100.blackwell-cp312-cp312-win_amd64.whl](https://github.com/dougeeai/llama-cpp-python-wheels/releases/download/v0.3.16-cuda13.0-sm100-py312/llama_cpp_python-0.3.16+cuda13.0.sm100.blackwell-cp312-cp312-win_amd64.whl) | 0.3.16 | Windows | 3.12 | 13.0 | 580+ | 65.9 MB |
| [llama_cpp_python-0.3.16+cuda13.0.sm100.blackwell-cp311-cp311-win_amd64.whl](https://github.com/dougeeai/llama-cpp-python-wheels/releases/download/v0.3.16-cuda13.0-sm100-py311/llama_cpp_python-0.3.16+cuda13.0.sm100.blackwell-cp311-cp311-win_amd64.whl) | 0.3.16 | Windows | 3.11 | 13.0 | 580+ | 65.9 MB |
| [llama_cpp_python-0.3.16+cuda13.0.sm100.blackwell-cp310-cp310-win_amd64.whl](https://github.com/dougeeai/llama-cpp-python-wheels/releases/download/v0.3.16-cuda13.0-sm100-py310/llama_cpp_python-0.3.16+cuda13.0.sm100.blackwell-cp310-cp310-win_amd64.whl) | 0.3.16 | Windows | 3.10 | 13.0 | 580+ | 65.9 MB |

### RTX 40 Series & Ada Professional (Ada Lovelace - sm_89)
**Supported GPUs:** RTX 4060, RTX 4060 Ti, RTX 4070, RTX 4070 Ti, RTX 4070 Ti Super, RTX 4080, RTX 4080 Super, RTX 4090, RTX 6000 Ada, RTX 5000 Ada, RTX 4500 Ada, RTX 4000 Ada, RTX 4000 SFF Ada, L40, L40S, L4

| File | llama_cpp | OS | Python | CUDA | Driver | Size |
|------|-----------|-----|--------|------|--------|------|
| [llama_cpp_python-0.3.16+cuda13.0.sm89.ada-cp313-cp313-win_amd64.whl](https://github.com/dougeeai/llama-cpp-python-wheels/releases/download/v0.3.16-cuda13.0-sm89-py313/llama_cpp_python-0.3.16+cuda13.0.sm89.ada-cp313-cp313-win_amd64.whl) | 0.3.16 | Windows | 3.13 | 13.0 | 580+ | 61.4 MB |
| [llama_cpp_python-0.3.16+cuda13.0.sm89.ada-cp312-cp312-win_amd64.whl](https://github.com/dougeeai/llama-cpp-python-wheels/releases/download/v0.3.16-cuda13.0-sm89-py312/llama_cpp_python-0.3.16+cuda13.0.sm89.ada-cp312-cp312-win_amd64.whl) | 0.3.16 | Windows | 3.12 | 13.0 | 580+ | 61.4 MB |
| [llama_cpp_python-0.3.16+cuda13.0.sm89.ada-cp311-cp311-win_amd64.whl](https://github.com/dougeeai/llama-cpp-python-wheels/releases/download/v0.3.16-cuda13.0-sm89-py311/llama_cpp_python-0.3.16+cuda13.0.sm89.ada-cp311-cp311-win_amd64.whl) | 0.3.16 | Windows | 3.11 | 13.0 | 580+ | 61.4 MB |
| [llama_cpp_python-0.3.16+cuda13.0.sm89.ada-cp310-cp310-win_amd64.whl](https://github.com/dougeeai/llama-cpp-python-wheels/releases/download/v0.3.16-cuda13.0-sm89-py310/llama_cpp_python-0.3.16+cuda13.0.sm89.ada-cp310-cp310-win_amd64.whl) | 0.3.16 | Windows | 3.10 | 13.0 | 580+ | 61.3 MB |
| [llama_cpp_python-0.3.16+cuda12.1.sm89.ada-cp313-cp313-win_amd64.whl](https://github.com/dougeeai/llama-cpp-python-wheels/releases/download/v0.3.16-cuda12.1-sm89-py313/llama_cpp_python-0.3.16+cuda12.1.sm89.ada-cp313-cp313-win_amd64.whl) | 0.3.16 | Windows | 3.13 | 12.1 | 525.60.13+ | 100.6 MB |
| [llama_cpp_python-0.3.16+cuda12.1.sm89.ada-cp312-cp312-win_amd64.whl](https://github.com/dougeeai/llama-cpp-python-wheels/releases/download/v0.3.16-cuda12.1-sm89-py312/llama_cpp_python-0.3.16+cuda12.1.sm89.ada-cp312-cp312-win_amd64.whl) | 0.3.16 | Windows | 3.12 | 12.1 | 525.60.13+ | 100.6 MB |
| [llama_cpp_python-0.3.16+cuda12.1.sm89.ada-cp311-cp311-win_amd64.whl](https://github.com/dougeeai/llama-cpp-python-wheels/releases/download/v0.3.16-cuda12.1-sm89-py311/llama_cpp_python-0.3.16+cuda12.1.sm89.ada-cp311-cp311-win_amd64.whl) | 0.3.16 | Windows | 3.11 | 12.1 | 525.60.13+ | 100.6 MB |
| [llama_cpp_python-0.3.16+cuda12.1.sm89.ada-cp310-cp310-win_amd64.whl](https://github.com/dougeeai/llama-cpp-python-wheels/releases/download/v0.3.16-cuda12.1-sm89-py310/llama_cpp_python-0.3.16+cuda12.1.sm89.ada-cp310-cp310-win_amd64.whl) | 0.3.16 | Windows | 3.10 | 12.1 | 525.60.13+ | 100.6 MB |
| [llama_cpp_python-0.3.16+cuda11.8.sm89.ada-cp313-cp313-win_amd64.whl](https://github.com/dougeeai/llama-cpp-python-wheels/releases/download/v0.3.16-cuda11.8-sm89-py313/llama_cpp_python-0.3.16+cuda11.8.sm89.ada-cp313-cp313-win_amd64.whl) | 0.3.16 | Windows | 3.13 | 11.8 | 450.80.02+ | 100.5 MB |
| [llama_cpp_python-0.3.16+cuda11.8.sm89.ada-cp312-cp312-win_amd64.whl](https://github.com/dougeeai/llama-cpp-python-wheels/releases/download/v0.3.16-cuda11.8-sm89-py312/llama_cpp_python-0.3.16+cuda11.8.sm89.ada-cp312-cp312-win_amd64.whl) | 0.3.16 | Windows | 3.12 | 11.8 | 450.80.02+ | 100.5 MB |
| [llama_cpp_python-0.3.16+cuda11.8.sm89.ada-cp311-cp311-win_amd64.whl](https://github.com/dougeeai/llama-cpp-python-wheels/releases/download/v0.3.16-cuda11.8-sm89-py311/llama_cpp_python-0.3.16+cuda11.8.sm89.ada-cp311-cp311-win_amd64.whl) | 0.3.16 | Windows | 3.11 | 11.8 | 450.80.02+ | 100.5 MB |
| [llama_cpp_python-0.3.16+cuda11.8.sm89.ada-cp310-cp310-win_amd64.whl](https://github.com/dougeeai/llama-cpp-python-wheels/releases/download/v0.3.16-cuda11.8-sm89-py310/llama_cpp_python-0.3.16+cuda11.8.sm89.ada-cp310-cp310-win_amd64.whl) | 0.3.16 | Windows | 3.10 | 11.8 | 450.80.02+ | 100.5 MB |

### RTX 30 Series & Ampere Professional (Ampere - sm_86)
**Supported GPUs:** RTX 3060, RTX 3060 Ti, RTX 3070, RTX 3070 Ti, RTX 3080, RTX 3080 Ti, RTX 3090, RTX 3090 Ti, RTX A2000, RTX A4000, RTX A4500, RTX A5000, RTX A5500, RTX A6000

| File | llama_cpp | OS | Python | CUDA | Driver | Size |
|------|-----------|-----|--------|------|--------|------|
| [llama_cpp_python-0.3.16+cuda13.0.sm86.ampere-cp313-cp313-win_amd64.whl](https://github.com/dougeeai/llama-cpp-python-wheels/releases/download/v0.3.16-cuda13.0-sm86-py313/llama_cpp_python-0.3.16+cuda13.0.sm86.ampere-cp313-cp313-win_amd64.whl) | 0.3.16 | Windows | 3.13 | 13.0 | 580+ | 61.4 MB |
| [llama_cpp_python-0.3.16+cuda13.0.sm86.ampere-cp312-cp312-win_amd64.whl](https://github.com/dougeeai/llama-cpp-python-wheels/releases/download/v0.3.16-cuda13.0-sm86-py312/llama_cpp_python-0.3.16+cuda13.0.sm86.ampere-cp312-cp312-win_amd64.whl) | 0.3.16 | Windows | 3.12 | 13.0 | 580+ | 61.4 MB |
| [llama_cpp_python-0.3.16+cuda13.0.sm86.ampere-cp311-cp311-win_amd64.whl](https://github.com/dougeeai/llama-cpp-python-wheels/releases/download/v0.3.16-cuda13.0-sm86-py311/llama_cpp_python-0.3.16+cuda13.0.sm86.ampere-cp311-cp311-win_amd64.whl) | 0.3.16 | Windows | 3.11 | 13.0 | 580+ | 61.4 MB |
| [llama_cpp_python-0.3.16+cuda13.0.sm86.ampere-cp310-cp310-win_amd64.whl](https://github.com/dougeeai/llama-cpp-python-wheels/releases/download/v0.3.16-cuda13.0-sm86-py310/llama_cpp_python-0.3.16+cuda13.0.sm86.ampere-cp310-cp310-win_amd64.whl) | 0.3.16 | Windows | 3.10 | 13.0 | 580+ | 61.4 MB |
| [llama_cpp_python-0.3.16+cuda12.1.sm86.ampere-cp313-cp313-win_amd64.whl](https://github.com/dougeeai/llama-cpp-python-wheels/releases/download/v0.3.16-cuda12.1-sm86-py313/llama_cpp_python-0.3.16+cuda12.1.sm86.ampere-cp313-cp313-win_amd64.whl) | 0.3.16 | Windows | 3.13 | 12.1 | 525.60.13+ | 92.2 MB |
| [llama_cpp_python-0.3.16+cuda12.1.sm86.ampere-cp312-cp312-win_amd64.whl](https://github.com/dougeeai/llama-cpp-python-wheels/releases/download/v0.3.16-cuda12.1-sm86-py312/llama_cpp_python-0.3.16+cuda12.1.sm86.ampere-cp312-cp312-win_amd64.whl) | 0.3.16 | Windows | 3.12 | 12.1 | 525.60.13+ | 61.4 MB |
| [llama_cpp_python-0.3.16+cuda12.1.sm86.ampere-cp311-cp311-win_amd64.whl](https://github.com/dougeeai/llama-cpp-python-wheels/releases/download/v0.3.16-cuda12.1-sm86-py311/llama_cpp_python-0.3.16+cuda12.1.sm86.ampere-cp311-cp311-win_amd64.whl) | 0.3.16 | Windows | 3.11 | 12.1 | 525.60.13+ | 61.4 MB |
| [llama_cpp_python-0.3.16+cuda12.1.sm86.ampere-cp310-cp310-win_amd64.whl](https://github.com/dougeeai/llama-cpp-python-wheels/releases/download/v0.3.16-cuda12.1-sm86-py310/llama_cpp_python-0.3.16+cuda12.1.sm86.ampere-cp310-cp310-win_amd64.whl) | 0.3.16 | Windows | 3.10 | 12.1 | 525.60.13+ | 61.4 MB |
| [llama_cpp_python-0.3.16+cuda11.8.sm86.ampere-cp313-cp313-win_amd64.whl](https://github.com/dougeeai/llama-cpp-python-wheels/releases/download/v0.3.16-cuda11.8-sm86-py313/llama_cpp_python-0.3.16+cuda11.8.sm86.ampere-cp313-cp313-win_amd64.whl) | 0.3.16 | Windows | 3.13 | 11.8 | 450.80.02+ | 100.6 MB |
| [llama_cpp_python-0.3.16+cuda11.8.sm86.ampere-cp312-cp312-win_amd64.whl](https://github.com/dougeeai/llama-cpp-python-wheels/releases/download/v0.3.16-cuda11.8-sm86-py312/llama_cpp_python-0.3.16+cuda11.8.sm86.ampere-cp312-cp312-win_amd64.whl) | 0.3.16 | Windows | 3.12 | 11.8 | 450.80.02+ | 100.6 MB |
| [llama_cpp_python-0.3.16+cuda11.8.sm86.ampere-cp311-cp311-win_amd64.whl](https://github.com/dougeeai/llama-cpp-python-wheels/releases/download/v0.3.16-cuda11.8-sm86-py311/llama_cpp_python-0.3.16+cuda11.8.sm86.ampere-cp311-cp311-win_amd64.whl) | 0.3.16 | Windows | 3.11 | 11.8 | 450.80.02+ | 100.6 MB |
| [llama_cpp_python-0.3.16+cuda11.8.sm86.ampere-cp310-cp310-win_amd64.whl](https://github.com/dougeeai/llama-cpp-python-wheels/releases/download/v0.3.16-cuda11.8-sm86-py310/llama_cpp_python-0.3.16+cuda11.8.sm86.ampere-cp310-cp310-win_amd64.whl) | 0.3.16 | Windows | 3.10 | 11.8 | 450.80.02+ | 100.6 MB |

### RTX 20 Series & Turing Professional (Turing - sm_75)
**Supported GPUs:** RTX 2080 Ti, RTX 2080 Super, RTX 2080, RTX 2070 Super, RTX 2070, RTX 2060 Super, RTX 2060, TITAN RTX, GTX 1660 Ti, GTX 1660 Super, GTX 1660, GTX 1650 Super, GTX 1650, GTX 1630, Quadro RTX 8000, RTX 6000, RTX 5000, RTX 4000, Tesla T4

| File | llama_cpp | OS | Python | CUDA | Driver | Size |
|------|-----------|-----|--------|------|--------|------|
| [llama_cpp_python-0.3.16+cuda13.0.sm75.turing-cp313-cp313-win_amd64.whl](https://github.com/dougeeai/llama-cpp-python-wheels/releases/download/v0.3.16-cuda13.0-sm75-py313/llama_cpp_python-0.3.16+cuda13.0.sm75.turing-cp313-cp313-win_amd64.whl) | 0.3.16 | Windows | 3.13 | 13.0 | 580+ | 63.1 MB |
| [llama_cpp_python-0.3.16+cuda13.0.sm75.turing-cp312-cp312-win_amd64.whl](https://github.com/dougeeai/llama-cpp-python-wheels/releases/download/v0.3.16-cuda13.0-sm75-py312/llama_cpp_python-0.3.16+cuda13.0.sm75.turing-cp312-cp312-win_amd64.whl) | 0.3.16 | Windows | 3.12 | 13.0 | 580+ | 63.1 MB |
| [llama_cpp_python-0.3.16+cuda13.0.sm75.turing-cp311-cp311-win_amd64.whl](https://github.com/dougeeai/llama-cpp-python-wheels/releases/download/v0.3.16-cuda13.0-sm75-py311/llama_cpp_python-0.3.16+cuda13.0.sm75.turing-cp311-cp311-win_amd64.whl) | 0.3.16 | Windows | 3.11 | 13.0 | 580+ | 63.1 MB |
| [llama_cpp_python-0.3.16+cuda13.0.sm75.turing-cp310-cp310-win_amd64.whl](https://github.com/dougeeai/llama-cpp-python-wheels/releases/download/v0.3.16-cuda13.0-sm75-py310/llama_cpp_python-0.3.16+cuda13.0.sm75.turing-cp310-cp310-win_amd64.whl) | 0.3.16 | Windows | 3.10 | 13.0 | 580+ | 63.1 MB |
| [llama_cpp_python-0.3.16+cuda12.1.sm75.turing-cp313-cp313-win_amd64.whl](https://github.com/dougeeai/llama-cpp-python-wheels/releases/download/v0.3.16-cuda12.1-sm75-py313/llama_cpp_python-0.3.16+cuda12.1.sm75.turing-cp313-cp313-win_amd64.whl) | 0.3.16 | Windows | 3.13 | 12.1 | 525.60.13+ | 103.5 MB |
| [llama_cpp_python-0.3.16+cuda12.1.sm75.turing-cp312-cp312-win_amd64.whl](https://github.com/dougeeai/llama-cpp-python-wheels/releases/download/v0.3.16-cuda12.1-sm75-py312/llama_cpp_python-0.3.16+cuda12.1.sm75.turing-cp312-cp312-win_amd64.whl) | 0.3.16 | Windows | 3.12 | 12.1 | 525.60.13+ | 103.5 MB |
| [llama_cpp_python-0.3.16+cuda12.1.sm75.turing-cp311-cp311-win_amd64.whl](https://github.com/dougeeai/llama-cpp-python-wheels/releases/download/v0.3.16-cuda12.1-sm75-py311/llama_cpp_python-0.3.16+cuda12.1.sm75.turing-cp311-cp311-win_amd64.whl) | 0.3.16 | Windows | 3.11 | 12.1 | 525.60.13+ | 103.5 MB |
| [llama_cpp_python-0.3.16+cuda12.1.sm75.turing-cp310-cp310-win_amd64.whl](https://github.com/dougeeai/llama-cpp-python-wheels/releases/download/v0.3.16-cuda12.1-sm75-py310/llama_cpp_python-0.3.16+cuda12.1.sm75.turing-cp310-cp310-win_amd64.whl) | 0.3.16 | Windows | 3.10 | 12.1 | 525.60.13+ | 103.5 MB |
| [llama_cpp_python-0.3.16+cuda11.8.sm75.turing-cp313-cp313-win_amd64.whl](https://github.com/dougeeai/llama-cpp-python-wheels/releases/download/v0.3.16-cuda11.8-sm75-py313/llama_cpp_python-0.3.16+cuda11.8.sm75.turing-cp313-cp313-win_amd64.whl) | 0.3.16 | Windows | 3.13 | 11.8 | 450.80.02+ | 103.5 MB |
| [llama_cpp_python-0.3.16+cuda11.8.sm75.turing-cp312-cp312-win_amd64.whl](https://github.com/dougeeai/llama-cpp-python-wheels/releases/download/v0.3.16-cuda11.8-sm75-py312/llama_cpp_python-0.3.16+cuda11.8.sm75.turing-cp312-cp312-win_amd64.whl) | 0.3.16 | Windows | 3.12 | 11.8 | 450.80.02+ | 103.5 MB |
| [llama_cpp_python-0.3.16+cuda11.8.sm75.turing-cp311-cp311-win_amd64.whl](https://github.com/dougeeai/llama-cpp-python-wheels/releases/download/v0.3.16-cuda11.8-sm75-py311/llama_cpp_python-0.3.16+cuda11.8.sm75.turing-cp311-cp311-win_amd64.whl) | 0.3.16 | Windows | 3.11 | 11.8 | 450.80.02+ | 103.5 MB |
| [llama_cpp_python-0.3.16+cuda11.8.sm75.turing-cp310-cp310-win_amd64.whl](https://github.com/dougeeai/llama-cpp-python-wheels/releases/download/v0.3.16-cuda11.8-sm75-py310/llama_cpp_python-0.3.16+cuda11.8.sm75.turing-cp310-cp310-win_amd64.whl) | 0.3.16 | Windows | 3.10 | 11.8 | 450.80.02+ | 103.5 MB |

## Installation
Download the appropriate wheel from [Releases](../../releases) and install:
```bash
pip install llama_cpp_python-[version]+cuda[cuda_version].sm[arch].[gpu]-cp[python]-cp[python]-win_amd64.whl
```

## Verification
```python
from llama_cpp import Llama
print("llama-cpp-python with CUDA support installed successfully")
```

## Build Notes
Built with:
- Visual Studio 2019/2022 Build Tools
- CUDA Toolkit 11.8, 12.1, 13.0
- CMAKE_CUDA_ARCHITECTURES=75 (Turing), 86 (Ampere), 89 (Ada), 100 (Datacenter Blackwell), 120 (Consumer/Workstation Blackwell)

## License
MIT

Wheels are built from [llama-cpp-python](https://github.com/abetlen/llama-cpp-python) (MIT License)

## Contributing
**Need a different configuration?**
Open an [issue](https://github.com/dougeeai/llama-cpp-python-wheels/issues) with:
- OS (Windows/Linux/macOS)
- Python version
- CUDA version (if applicable)
- GPU model

I'll try to build it if I have access to similar hardware.

## Contact
Questions or issues? Open a [GitHub issue](https://github.com/dougeeai/llama-cpp-python-wheels/issues).
