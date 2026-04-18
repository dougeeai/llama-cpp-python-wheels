# llama-cpp-python-wheels
Pre-built wheels for llama-cpp-python across platforms and CUDA versions.

## Available Wheels

### Consumer & Workstation Blackwell (sm_120)
**Supported GPUs:** RTX 5090, 5080, 5070 Ti, 5070, 5060 Ti, 5060, 5050, RTX 5090 Laptop, RTX 5080 Laptop, RTX 5070 Ti Laptop, RTX 5070 Laptop, RTX 5060 Laptop, RTX 5050 Laptop, RTX PRO 6000 Blackwell Workstation Edition, RTX PRO 6000 Blackwell Max-Q, RTX PRO 6000 Blackwell Server Edition, RTX PRO 5000 Blackwell, RTX PRO 4500 Blackwell, RTX PRO 4000 Blackwell, RTX PRO 4000 SFF Blackwell, RTX PRO 2000 Blackwell, RTX PRO 5000 Blackwell Laptop, RTX PRO 4000 Blackwell Laptop, RTX PRO 3000 Blackwell Laptop, RTX PRO 2000 Blackwell Laptop, RTX PRO 1000 Blackwell Laptop, RTX PRO 500 Blackwell Laptop

| File | llama_cpp | OS | Python | CUDA | Driver | Size |
|------|-----------|-----|--------|------|--------|------|
| [llama_cpp_python-0.3.20+cuda13.0.sm100.sm120.blackwell-py3-none-win_amd64.whl](https://github.com/dougeeai/llama-cpp-python-wheels/releases/download/v0.3.20-cuda13.0-sm100-sm120/llama_cpp_python-0.3.20+cuda13.0.sm100.sm120.blackwell-py3-none-win_amd64.whl) | 0.3.20 | Windows | 3.10–3.13 | 13.0 | 580+ | 184.3 MB |

### Datacenter Blackwell (sm_100)
**Supported GPUs:** B100, B200, B300 (Blackwell Ultra), GB200, GB300

> **Note:** The `sm100.sm120` wheel below covers both datacenter (sm_100) and consumer/workstation (sm_120) Blackwell in a single build. The older sm_100-only wheels remain available for anyone who specifically wants a smaller datacenter-only build.

| File | llama_cpp | OS | Python | CUDA | Driver | Size |
|------|-----------|-----|--------|------|--------|------|
| [llama_cpp_python-0.3.20+cuda13.0.sm100.sm120.blackwell-py3-none-win_amd64.whl](https://github.com/dougeeai/llama-cpp-python-wheels/releases/download/v0.3.20-cuda13.0-sm100-sm120/llama_cpp_python-0.3.20+cuda13.0.sm100.sm120.blackwell-py3-none-win_amd64.whl) | 0.3.20 | Windows | 3.10–3.13 | 13.0 | 580+ | 184.3 MB |
| [llama_cpp_python-0.3.16+cuda13.0.sm100.blackwell-cp313-cp313-win_amd64.whl](https://github.com/dougeeai/llama-cpp-python-wheels/releases/download/v0.3.16-cuda13.0-sm100-py313/llama_cpp_python-0.3.16+cuda13.0.sm100.blackwell-cp313-cp313-win_amd64.whl) | 0.3.16 | Windows | 3.13 | 13.0 | 580+ | 65.9 MB |
| [llama_cpp_python-0.3.16+cuda13.0.sm100.blackwell-cp312-cp312-win_amd64.whl](https://github.com/dougeeai/llama-cpp-python-wheels/releases/download/v0.3.16-cuda13.0-sm100-py312/llama_cpp_python-0.3.16+cuda13.0.sm100.blackwell-cp312-cp312-win_amd64.whl) | 0.3.16 | Windows | 3.12 | 13.0 | 580+ | 65.9 MB |
| [llama_cpp_python-0.3.16+cuda13.0.sm100.blackwell-cp311-cp311-win_amd64.whl](https://github.com/dougeeai/llama-cpp-python-wheels/releases/download/v0.3.16-cuda13.0-sm100-py311/llama_cpp_python-0.3.16+cuda13.0.sm100.blackwell-cp311-cp311-win_amd64.whl) | 0.3.16 | Windows | 3.11 | 13.0 | 580+ | 65.9 MB |
| [llama_cpp_python-0.3.16+cuda13.0.sm100.blackwell-cp310-cp310-win_amd64.whl](https://github.com/dougeeai/llama-cpp-python-wheels/releases/download/v0.3.16-cuda13.0-sm100-py310/llama_cpp_python-0.3.16+cuda13.0.sm100.blackwell-cp310-cp310-win_amd64.whl) | 0.3.16 | Windows | 3.10 | 13.0 | 580+ | 65.9 MB |


### RTX 40 Series & Ada Professional (Ada Lovelace - sm_89)
**Supported GPUs:** RTX 4060, RTX 4060 Ti, RTX 4070, RTX 4070 Ti, RTX 4070 Ti Super, RTX 4080, RTX 4080 Super, RTX 4090, RTX 6000 Ada, RTX 5000 Ada, RTX 4500 Ada, RTX 4000 Ada, RTX 4000 SFF Ada, L40, L40S, L4

| File | llama_cpp | OS | Python | CUDA | Driver | Size |
|------|-----------|-----|--------|------|--------|------|
| [llama_cpp_python-0.3.20+cuda13.0.sm89.ada-py3-none-win_amd64.whl](https://github.com/dougeeai/llama-cpp-python-wheels/releases/download/v0.3.20-cuda13.0-sm89/llama_cpp_python-0.3.20+cuda13.0.sm89.ada-py3-none-win_amd64.whl) | 0.3.20 | Windows | 3.10–3.13 | 13.0 | 580+ | 91.8 MB |
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
| [llama_cpp_python-0.3.20+cuda13.0.sm86.ampere-py3-none-win_amd64.whl](https://github.com/dougeeai/llama-cpp-python-wheels/releases/download/v0.3.20-cuda13.0-sm86/llama_cpp_python-0.3.20+cuda13.0.sm86.ampere-py3-none-win_amd64.whl) | 0.3.20 | Windows | 3.10–3.13 | 13.0 | 580+ | 91.9 MB |
| [llama_cpp_python-0.3.16+cuda13.0.sm86.ampere-cp313-cp313-win_amd64.whl](https://github.com/dougeeai/llama-cpp-python-wheels/releases/download/v0.3.16-cuda13.0-py313/llama_cpp_python-0.3.16+cuda13.0.sm86.ampere-cp313-cp313-win_amd64.whl) | 0.3.16 | Windows | 3.13 | 13.0 | 580+ | 61.4 MB |
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
| [llama_cpp_python-0.3.20+cuda13.0.sm75.turing-py3-none-win_amd64.whl](https://github.com/dougeeai/llama-cpp-python-wheels/releases/download/v0.3.20-cuda13.0-sm75/llama_cpp_python-0.3.20+cuda13.0.sm75.turing-py3-none-win_amd64.whl) | 0.3.20 | Windows | 3.10–3.13 | 13.0 | 580+ | 97.7 MB |
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
pip install llama_cpp_python-[version]+cuda[cuda_version].sm[arch].[gpu]-[python_tag]-[abi_tag]-win_amd64.whl
```

**Runtime requirement:** These wheels require the **matching CUDA Toolkit installed on the target machine** (specifically `cublas64_XX.dll`, which ships with the Toolkit — the NVIDIA driver alone does not include it). Install the CUDA Toolkit matching the wheel's CUDA version (11.8 / 12.1 / 13.0).

## Verification
```python
from llama_cpp import Llama
print("llama-cpp-python with CUDA support installed successfully")
```

## Build Notes
Built with:
- Visual Studio 2019/2022 Build Tools (0.3.16) and Visual Studio 2026 Community (0.3.20)
- CUDA Toolkit 11.8, 12.1, 13.0 (0.3.20 CUDA 13.0 builds use 13.0 Update 3)
- CMAKE_CUDA_ARCHITECTURES=75 (Turing), 86 (Ampere), 89 (Ada), 100 (Datacenter Blackwell), 120 (Consumer/Workstation Blackwell)
- 0.3.20 wheels use the `py3-none-win_amd64` tag (single wheel for Python 3.10–3.13 — llama-cpp-python loads its compiled libraries via ctypes, so no CPython ABI lock-in)

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
