# Sentinel Journal - DeepSeek LLM Security Learnings

## 2024-09-12 - Initial Security Baseline
**Vulnerability:** Lack of explicit security disclosure policy (SECURITY.md) and risk of accidental commit of secret/key files (.env.*, *.pem, *.key).
**Learning:** Pure documentation/model repositories still need security policies and strict gitignore rules for credentials/certificates to prevent leakages during evaluation or local testing.
**Prevention:** Establish standard SECURITY.md for responsible reporting and enforce gitignore rules for private key/secret extensions.
