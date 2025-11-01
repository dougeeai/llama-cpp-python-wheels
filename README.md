# llama-cpp-python-wheels

Pre-built wheels for llama-cpp-python across platforms and CUDA versions.

## Available Wheels

| File | OS | Python | CUDA | Driver | GPU Support | Size |
|------|-----|--------|------|--------|-------------|------|
| [llama_cpp_python-0.3.16+cuda13.0.sm86.ampere-cp313-cp313-win_amd64.whl](https://github.com/DougRahden/llama-cpp-python-wheels/releases/download/v0.3.16-cuda13.0-py313/llama_cpp_python-0.3.16%2Bcuda13.0.sm86.ampere-cp313-cp313-win_amd64.whl) | Windows 10/11 | 3.13 | 13.0 | 580+ | RTX 30 series (Ampere, sm_86) | 61.4 MB |

## Installation

Download wheel from [Releases](../../releases) and install:
```bash
pip install llama_cpp_python-0.3.16+cuda13.0.sm86.ampere-cp313-cp313-win_amd64.whl
```

## Verification
```python
from llama_cpp import Llama
print("llama-cpp-python with CUDA support installed successfully")
```

## Build Notes

Built with:
- Visual Studio 2022 Build Tools
- CUDA Toolkit 13.0
- CMAKE_CUDA_ARCHITECTURES=86

## License

MIT

Wheels are built from [llama-cpp-python](https://github.com/abetlen/llama-cpp-python) (MIT License)


## Contributing

**Need a different configuration?**
Open an [issue](https://github.com/DougRahden/llama-cpp-python-wheels/issues) with:
- OS (Windows/Linux/macOS)
- Python version
- CUDA version (if applicable)
- GPU model

I'll try to build it if I have access to similar hardware.

## Contact

Questions or issues? Open a [GitHub issue](https://github.com/DougRahden/llama-cpp-python-wheels/issues).
