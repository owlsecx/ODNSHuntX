# 🦉 ODNSHuntX

<p align="center">
  <img src="https://img.shields.io/badge/Platform-Linux-0a0c10?style=flat-square"/>
  <img src="https://img.shields.io/badge/Category-OReconnaissance-blue?style=flat-square"/>
  <img src="https://img.shields.io/badge/License-MIT-green?style=flat-square"/>
  <img src="https://img.shields.io/badge/Part%20of-OwlSec%20Toolkit-7b5ea7?style=flat-square"/>
  <img src="https://img.shields.io/badge/Version-1.1-cyan?style=flat-square"/>
</p>

> **ODNSHuntX** — DNSSEC Audit & Advanced Subdomain Discovery ║

---

> ⚠️ **AUTHORISED USE ONLY** — Use only on systems you own or have explicit written permission to test. Unauthorised use is illegal.

---

## 📌 Overview

ODNSHuntX extends DNS reconnaissance with DNSSEC auditing, wildcard detection, record analysis, and related discovery checks. It helps defenders validate DNS posture—including CAA/DS/DNSKEY chains and cloud-provider clues—while enumerating subdomains on authorised targets. Rich export and dashboard-oriented output support assessment reporting.

---

## ✨ Features

- Multi-threaded subdomain enumeration with wildcard detection
- DNSSEC chain and CAA/DS/DNSKEY oriented validation checks
- DNS record analysis with zone-transfer attempt visibility
- Reverse DNS and port-scan correlation helpers
- Cloud provider detection signals during discovery
- Live dashboard style feedback with rich export options

---

## ⚙️ Requirements

- **Linux**
- **No Python installation needed** — runs as a standalone executable

---

## 🚀 Usage

```bash
./ODNSHuntX
./ODNSHuntX --help
```

---

## 📦 Part of OwlSec Toolkit

This tool is part of the **OwlSec** suite — a collection of 300+ security and privacy tools.

🔗 [owlsec.org](https://owlsec.org)

---

## ©️ License

MIT License — © Khaled S. Haddad

*Tools are distributed as pre-built executables. Source code is proprietary.*
