# Hi, I'm Kartik Nair

Offensive security researcher and systems programmer. 
I find real bugs in production code.

## Security Research

| Advisory | Target | Severity | Status |
|---|---|---|---|
| GHSA-728f-j9w9-m8c3 | Haystack AI (deepset) | Critical 9.8 | Pending CVE |
| GHSA-cxjq-35gw-4m9f | MLflow LangChain | High | Pending CVE |
| DJL JAR bypass | deepjavalibrary/djl | Critical 9.8 | Huntr — pending |
| Kubeflow CUSTOM RCE | kubeflow | Critical 9.9 | Huntr — pending |
| smolagents numpy DoS | huggingface/smolagents | Medium | Huntr — pending |

## Linux Kernel Contributions

| Patch | Subsystem | Status |
|---|---|---|
| zsmalloc: zero-initialize zspage memory | Memory Management (mm) | ✅ Merged — Andrew Morton, cc:stable |
| cfg80211: validate chandef before set_monitor_channel | Networking (WiFi) | ⏳ Under review — Johannes Berg |
| accel/rocket: fix ignored return value | Rockchip NPU Driver | ⏳ Under review — Tomeu Vizoso |

All patches visible at [lore.kernel.org](https://lore.kernel.org/all/?q=Kartik+Nair)

## Tools

| Tool | What it does |
|---|---|
| [mlflow-audit](https://github.com/Carrtik/mlflow-audit) | Static analyzer detecting unguarded pickle deserialization in MLflow codebases |
| [Valkyrie](https://github.com/Carrtik/Valkyrie) | Linux privilege escalation auditor mapped to MITRE ATT&CK |
| [Cylock](https://github.com/Carrtik/Cylock) | Multi-threaded network scanner built from raw TCP/IP primitives |
| [Dynamic-Honeypot-RL](https://github.com/Carrtik/Dynamic-Honeypot-RL) | Adaptive honeypot using Q-learning to respond to live attacker behaviour |

## Writing

- [I found a bug in software running on millions of routers](https://medium.com/@contact.kartikn) — miniupnpd responsible disclosure
- [I submitted 4 Linux kernel patches in one night](https://medium.com/@contact.kartikn) — cfg80211, zsmalloc, kernel methodology

## Stack

Python · C · Bash · Linux Internals · Raw Sockets · Docker · CRYSTALS-Kyber · MITRE ATT&CK
