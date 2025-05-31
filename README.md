# XIUM – Sovereign Crypto Platform

Welcome to the official repository of **XIUM** – a fully self-sovereign cryptocurrency platform.  
No cloud. No KYC. No tracking. Your data, your device, your rules.

This repository hosts:
- The official binaries (see [Releases](https://github.com/xium-ai/xium/releases))

## Quick Links
- 🌐 [Visit Website](https://xium.ai)
- ⬇️ [Download Software](https://github.com/xium-ai/xium/releases)

> Built for those who take sovereignty seriously.

## 🔐 Verifying Official Releases

All binaries are signed with the official XIUM GPG key.

**Public Key:** [xium.asc](https://xium.ai/xium.asc)  
**Fingerprint:** `2891 CE24 C0BF 6F33 7B7C  350F 6BE8 091C A137 AEDA`

### Verify with GPG

```bash
# Import the public key
curl -O https://xium.ai/xium.asc
gpg --import xium.asc

# Check the fingerprint
gpg --fingerprint info@xium.ai

# Verify the binary
gpg --verify Xium_<version>.sig Xium_<version>
