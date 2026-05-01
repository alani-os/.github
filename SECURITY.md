## `SECURITY.md`

# Security Policy

## Supported Versions

| Version | Supported |
| ------- | --------- |
| 1.x.x   | ✅ |
| < 1.0   | ❌ |

## Reporting a Vulnerability

We take the security of Alani's cognitive kernel seriously.

### How to Report

**Do not** report security vulnerabilities through public GitHub issues.

Instead:
- **Email**: security@alani.dev
- **GitHub**: Use "Report a vulnerability" in Security tab

### What to Include

1. Description of the vulnerability
2. Steps to reproduce
3. Potential impact assessment
4. Suggested fixes (if applicable)
5. Contact information

### Response Timeline

- **Acknowledgment**: Within 48 hours
- **Initial Assessment**: Within 5 business days
- **Resolution**: Based on severity

### Severity Levels

| Severity | Response Time | Resolution Target |
|----------|---------------|-------------------|
| Critical | 24 hours | 7 days |
| High | 48 hours | 14 days |
| Medium | 5 days | 30 days |
| Low | 10 days | Next release |

## Security Considerations for Alani

Given Alani's architecture as a cognitive microkernel [1]:

1. **Cognitive Syscall Security**: All cognitive syscalls must be validated
2. **Model Isolation**: Models run as isolated devices
3. **Execution Traces**: All reasoning must be auditable [1]
4. **Memory Safety**: Kernel memory must be protected
5. **IPC Security**: Inter-process communication must be secured

## Security Updates

Announced via:
- GitHub Security Advisories
- Release notes
- Security mailing list

Thank you for helping keep Alani secure! 🔒
```

---