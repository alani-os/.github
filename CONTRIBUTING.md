## `CONTRIBUTING.md`

```markdown
# Contributing to Alani

Thank you for your interest in contributing to Alani, the cognitive microkernel operating system [1].

## Table of Contents

- [Code of Conduct](#code-of-conduct)
- [Getting Started](#getting-started)
- [Development Environment](#development-environment)
- [Making Contributions](#making-contributions)
- [Pull Request Process](#pull-request-process)
- [Testing](#testing)
- [Architecture Guidelines](#architecture-guidelines)

## Code of Conduct

Please read and follow our [Code of Conduct](CODE_OF_CONDUCT.md).

## Getting Started

1. **Fork and Clone**
   ```bash
   git clone git@github.com:alani-os/alani-kernel.git
   cd kernel
   ```

2. **Build the Kernel**
   ```bash
   cargo build
   cargo test
   ```

3. **Create a Feature Branch**
   ```bash
   git checkout -b feature/cognitive-scheduler
   ```

## Development Environment

### Prerequisites

- Rust (latest stable version)
- Git
- Linux/Unix environment recommended

### Build the Kernel

```bash
# Debug build
cargo build

# Release build
cargo build --release

# Run tests
cargo test
```

## Making Contributions

### Types of Contributions

- **Kernel Development**: Core microkernel features
- **Cognitive Devices**: Model inference engines
- **Agents**: Userspace agent framework
- **Documentation**: Specs, guides, API docs
- **Tests**: Unit, integration, benchmark tests
- **Security**: Vulnerability fixes, hardening

### Architecture Principles

Alani is governed by five foundational design principles [1]. Contributions should align with:

1. Intelligence as a kernel-managed resource
2. Syscall-mediated cognitive protocol
3. Separation of cognitive control from model execution
4. Verifiable execution traces
5. Standardized cognitive syscall ABI [1]

### Commit Guidelines

- Use clear, descriptive commit messages
- Reference issues when applicable
- Keep commits atomic and focused

Example:
```
feat: add cognitive syscall scheduling

- Implement priority-based cognitive workload scheduling
- Add isolation boundaries for cognitive tasks
- Include execution trace logging

Fixes #45
```

## Pull Request Process

1. **Create PR**: Open a pull request from your feature branch
2. **Description**: Clearly describe changes and motivation
3. **Tests**: Ensure all tests pass
4. **Review**: Address reviewer feedback
5. **Merge**: Once approved, PR will be merged

## Testing

### Test Types

- **Unit Tests**: Individual component testing
- **Integration Tests**: Cross-component testing
- **Cognitive Trace Tests**: Execution trace validation
- **Performance Tests**: Benchmark cognitive operations

```bash
# Run all tests
cargo test

# Run specific test suite
cargo test --test cognitive_traces

# Benchmark
cargo bench
```

## Architecture Guidelines

Refer to the system architecture [1]:

| Layer | Responsibility |
|-------|----------------|
| Hardware | CPU, RAM, GPU/TPU/NPU |
| Kernel | Scheduling, memory, IPC, cognitive control |
| Cognitive Devices | Model inference, semantic memory |
| Userspace | Agents, workflows, applications |
| Interfaces | Shells, APIs, external systems |

## Questions?

Reach out to maintainers or open an issue for questions about contributing.

Thank you for contributing to Alani! 🧠
```

---