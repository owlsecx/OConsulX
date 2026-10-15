# 🦉 OConsulX

<p align="center">
  <img src="https://img.shields.io/badge/Platform-Linux-0a0c10?style=flat-square"/>
  <img src="https://img.shields.io/badge/Category-ONetwork-blue?style=flat-square"/>
  <img src="https://img.shields.io/badge/License-MIT-green?style=flat-square"/>
  <img src="https://img.shields.io/badge/Part%20of-OwlSec%20Toolkit-7b5ea7?style=flat-square"/>
  <img src="https://img.shields.io/badge/Version-1.0.0-cyan?style=flat-square"/>
</p>

> **OConsulX** — Service-Discovery / Distributed KV Config Auditor

---

> ⚠️ **AUTHORISED USE ONLY** — Use only on systems you own or have explicit written permission to test. Unauthorised use is illegal.

---

## 📌 Overview

Consul / etcd / Nomad configuration security auditor

---

## ✨ Features

- Stdlib HCL / JSON / YAML-lite / ETCD_* env / --flag parsers
- Consul — ACL default policy, script checks RCE, remote exec, gossip key strength, verify_* mTLS, UI / API exposure, CORS, plaintext tokens, Connect CA
- etcd — client / peer TLS, client-cert-auth, auto-tls, pprof, metrics, v2 API, quota, data-dir / snapshot permissions, auth-token mode
- Nomad — ACL, TLS http / rpc, raw_exec, privileged docker, capabilities, host volumes, Vault / Consul integration tokens and TLS verification
- Secrets masked everywhere; --root discovery; CWE + MITRE
- Export TXT / Markdown / JSON / CSV / SARIF 2.1.0
- Self-test --demo, CI gates --fail-on / --min-severity

---

## ⚙️ Requirements

- **Linux**
- **No Python installation needed** — runs as a standalone executable

---

## 🚀 Usage

```bash
./OConsulX
```

---

## 📦 Part of OwlSec Toolkit

This tool is part of the **OwlSec** suite — a collection of 300+ security and privacy tools.

🔗 [owlsec.org](https://owlsec.org)

---

## ©️ License

MIT License — © Khaled S. Haddad

*Tools are distributed as pre-built executables. Source code is proprietary.*
