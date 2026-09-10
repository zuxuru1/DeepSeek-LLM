# Security Policy

## Reporting a Vulnerability

If you discover a security vulnerability within DeepSeek LLM, please report it responsibly by emailing **service@deepseek.com**.

Please do NOT create public GitHub issues for security vulnerabilities.

### What to include in your report:
- A description of the vulnerability and its potential impact.
- Detailed steps to reproduce the issue.
- Any proof-of-concept code or payload, if available.

We will acknowledge receipt of your vulnerability report and work to address it promptly.

## Security Best Practices

When deploying or using DeepSeek LLM:
- **Model Weight Verification**: Verify checksums and download sources when loading model weights. Exercise caution when using options such as `trust_remote_code=True`.
- **Input/Output Sanitization**: Treat model inputs and generated outputs as untrusted. Validate and sanitize inputs/outputs before passing them to downstream systems or code execution environments.
