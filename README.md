# Rust GPU SMI

**A lightweight GPU monitoring tool for Linux, written in Rust.**

Rust GPU SMI is a terminal-based application designed to monitor GPU information and system metrics in real time.

The project aims to provide a lightweight, efficient, and easy-to-use monitoring experience for Linux environments.

## Features

- Real-time GPU monitoring.
- GPU utilization monitoring.
- GPU memory usage.
- GPU temperature monitoring.
- Power consumption monitoring.
- GPU performance information.
- Lightweight implementation using Rust.
- Terminal-based interface.

## Screenshots

<!-- Add application screenshots here -->

## Downloads

Download the latest version from GitHub Releases.

**[Download Latest Release](https://github.com/ptarcode/rgpu-smi/releases/latest)**

### Supported Platforms

| Platform | Architecture | Minimum glibc |
|---|---|---|
| Linux | x86_64 | 2.17 |
| Linux | aarch64 | 2.17 |

Choose the appropriate package for your Linux architecture.

### Available Packages

- `rust-gpu-smi-linux-x86_64-glibc217.tar.gz`
- `rust-gpu-smi-linux-aarch64-glibc217.tar.gz`

## Installation

### 1. Download

For Linux x86_64:

```bash
wget https://github.com/SEU_USUARIO/rgpu-smi/releases/latest/download/rust-gpu-smi-linux-x86_64-glibc217.tar.gz
```

For Linux ARM64:

```bash
wget https://github.com/SEU_USUARIO/rgpu-smi/releases/latest/download/rust-gpu-smi-linux-aarch64-glibc217.tar.gz
```

### 2. Extract

```bash
tar -xzf rust-gpu-smi-linux-x86_64-glibc217.tar.gz
```

### 3. Make executable

```bash
chmod +x rust_gpu_smi
```

### 4. Run

```bash
./rust_gpu_smi
```

## Verify Download Integrity

SHA256 checksums are provided with each release.

To verify your downloaded package:

```bash
sha256sum -c SHA256SUMS
```

The result should display:

```text
rust-gpu-smi-linux-x86_64-glibc217.tar.gz: OK
```

## Requirements

- Linux operating system.
- Compatible CPU architecture.
- Compatible NVIDIA GPU and driver, if using NVIDIA monitoring features.
- Required runtime libraries for GPU monitoring.

## Compatibility

The GNU/Linux binaries are built targeting glibc 2.17 to maximize compatibility with Linux distributions.

Supported architectures:

- x86_64 (Intel / AMD)
- aarch64 (ARM64)

Actual compatibility also depends on the system libraries and GPU driver requirements.

## Versioning

This project follows Semantic Versioning.

Release versions are available on the [Releases page](https://github.com/SEU_USUARIO/rgpu-smi/releases).

## License

See the repository's LICENSE file for licensing information.

## Feedback and Contributions

Found a bug or have a suggestion?

Please open an issue in the GitHub repository.

---

**Developed with Rust.**
