# <img src="assets/crimsonforge.png" alt="CrimsonForge Logo" width="60"/> CrimsonForge

**CrimsonForge** is an open-source project dedicated to building highly optimized GPU kernels and MLIR-based compiler pipelines for modern AI workloads, with a focus on AMD Instinct GPUs (like the MI300 series).  
Our mission is to create a community-driven hub for accelerating open-source LLMs (DeepSeek, LLaMA, Qwen, and beyond) on AMD hardware.

---

## 🚀 Features

- ⚡ **GPU Kernel Development**  
  Write efficient custom kernels tailored for AMD GPUs using MLIR and ROCm.

- 🧩 **Compiler Infrastructure**  
  MLIR passes and transformations for deep learning workloads.

- 🧠 **LLM Optimization**  
  Function libraries and optimizations targeting open-source LLMs.

- 🔥 **AMD-Centric**  
  Focused on unlocking the full potential of AMD Instinct accelerators.

---

## 📂 Repository Structure

```
CrimsonForge/
├── mlir-passes/       # Custom MLIR passes and dialects
├── kernels/           # Hand-written GPU kernels
├── models/            # Integrations with LLMs (DeepSeek, LLaMA, Qwen, etc.)
├── tests/             # Unit and performance tests
├── benchmarks/        # Benchmark scripts and results
├── docs/              # Documentation
└── assets/            # Logos, diagrams, and media
```

---

## 🛠️ Getting Started

### Prerequisites
- ROCm stack installed (latest version recommended).
- LLVM + MLIR (built with AMDGPU support).
- Python 3.10+ (for scripts, model integration).
- CMake + Ninja for builds.

### Build Instructions
```bash
git clone git@github.com:Uzair-90/CrimsonForge.git
cd CrimsonForge
mkdir build && cd build
cmake ..
make -j$(nproc)
```

### Running Tests
```bash
ctest
```

---

## 🤝 Contributing

We welcome contributions from GPU enthusiasts, compiler developers, and AI researchers.  
Please read our [CONTRIBUTING.md](docs/CONTRIBUTING.md) before submitting a PR.

---

## 📜 License

This project is licensed under the **MIT License** – see the [LICENSE](LICENSE) file for details.  
**Note:** Please give credit to **CrimsonForge** when using or referencing this project.

---

## 🌐 Community

- 💬 Discussions: [GitHub Discussions](https://github.com/Uzair-90/CrimsonForge/discussions)  
- 🐦 Twitter/X: *Coming soon*  
- 🌍 Website: *Coming soon*  

---

### 🔥 Forging the future of AI on AMD.
