# 🦉 OConsulX

<p align="center">
  <img src="https://img.shields.io/badge/Platform-Linux-0a0c10?style=flat-square"/>
  <img src="https://img.shields.io/badge/Category-ONetwork-blue?style=flat-square"/>
  <img src="https://img.shields.io/badge/License-Proprietary-orange?style=flat-square"/>
  <img src="https://img.shields.io/badge/Part%20of-OwlSec%20Toolkit-7b5ea7?style=flat-square"/>
  <img src="https://img.shields.io/badge/Version-1.0.0-cyan?style=flat-square"/>
</p>

> **OConsulX** — Service-Discovery / Distributed KV Config Auditor

---

> ⚠️ **AUTHORISED USE ONLY** — Use only on systems you own or have explicit written permission to test. Unauthorised use is illegal.

---

## 📌 Overview

OConsulX — Service-Discovery / Distributed KV Config Auditor. It provides stdlib HCL / JSON / YAML-lite / ETCD_* env / --flag parsers; Consul — ACL default policy, script checks RCE, remote exec, gossip key strength, verify_* mTLS, UI / API exposure, CORS, plaintext tokens, Connect CA. Built-in demo/self-test paths and severity gates help validate detections without touching production when those flags are used.

---

## ✨ Features

- Stdlib HCL / JSON / YAML-lite / ETCD_* env / --flag parsers
- Consul — ACL default policy, script checks RCE, remote exec, gossip key strength, verify_* mTLS, UI / API exposure, CORS, plaintext tokens, Connect CA
- etcd — client / peer TLS, client-cert-auth, auto-tls, pprof, metrics, v2 API, quota, data-dir / snapshot permissions, auth-token mode
- Nomad — ACL, TLS http / rpc, raw_exec, privileged docker, capabilities, host volumes, Vault / Consul integration tokens and TLS verification
- Secrets masked everywhere; --root discovery; CWE + MITRE
- Export TXT / Markdown / JSON / CSV / SARIF 2.1.0

---

## ⚙️ Requirements

- **Linux**
- **No Python installation needed** — runs as a standalone executable

---

## 🚀 Usage

```bash
./OConsulX                                     # interactive menu
./OConsulX --scan -r /path/to/root
./OConsulX --demo
./OConsulX --help
```

---

## 📦 Part of OwlSec Toolkit

This tool is part of the **OwlSec** suite — a collection of 275+ security and privacy tools.

🔗 [owlsec.org](https://owlsec.org)

---

## ©️ License

Proprietary — © 2026 Owlsec LLC. All rights reserved.

*Tools are distributed as pre-built executables. Source code is proprietary.*

---

## 🔍 Verification & Transparency

This tool is closed-source. These files let you see exactly what is inside it,
without the source:

- [`SBOM.cdx.json`](SBOM.cdx.json) — CycloneDX inventory: SHA-256 of this
  binary, bundled CPython version, and every bundled library with its exact
  version and license. Feed it to Grype, Trivy or Dependency-Track to audit
  our dependencies for CVEs yourself.
- [`THIRD-PARTY-NOTICES.md`](THIRD-PARTY-NOTICES.md) — the full license text
  of every third-party component, extracted from this binary.

**No telemetry, no analytics, no licence check-in.** This tool does not phone
home. Verify that claim yourself:

```bash
sudo strace -f -e trace=network ./OConsulX --help   # watch every network call
firejail --net=none ./OConsulX --help               # deny the network entirely
```

Release signing, GPL compliance and vulnerability reporting:
[**TRUST.md**](https://github.com/owlsecx/owl-os/blob/main/TRUST.md)
