# Hi, I'm Kartik Nair

Offensive security researcher and systems programmer.
I find real bugs in production code.

## Security Research

| Advisory | Target | Severity | Status |
|---|---|---|---|
| GHSA-6457-j4jq-j7b5 | Spring AI Alibaba | Critical 9.9 | Pending CVE |
| GHSA-h2c7-rx9m-j6rr | Spring AI Alibaba | High 8.1 | Pending CVE |
| GHSA-q83f-9wj5-xrmc | Spring AI Alibaba | High 7.5 | Pending CVE |
| DJL JAR bypass | deepjavalibrary/djl | Critical 9.8 | Huntr — pending |
| Kubeflow CUSTOM RCE | kubeflow | Critical 9.9 | Huntr — pending |
| smolagents numpy DoS | huggingface/smolagents | Medium | Huntr — pending |
| GHSA-cxjq-35gw-4m9f | MLflow LangChain | High | Credited in PR #23292 |

## Linux Kernel Contributions

| Patch | Subsystem | Status |
|---|---|---|
| net/llc: fix UBSAN array-index-out-of-bounds in llc_conn_state_process | Networking | ⏳ Under review — David Miller, Eric Dumazet |
| cfg80211: validate chandef before set_monitor_channel | WiFi/Networking | ⏳ Under review — Johannes Berg |
| mm/hugetlb: fix deadlock in __hugetlb_zap_begin() | Memory Management | ⏳ In discussion |
| accel/rocket: fix ignored return value | Rockchip NPU Driver | ⏳ Under review |
| zsmalloc: zero-initialize zspage memory | Memory Management | ⚠️ Merged by Andrew Morton → triggered investigation by Herbert Xu into 842 decompressor |

All patches visible at [lore.kernel.org](https://lore.kernel.org/all/?q=Kartik+Nair)

## Tools

| Tool | What it does |
|---|---|
| [mlflow-audit](https://github.com/Carrtik/mlflow-audit) | Static analyzer detecting unguarded pickle deserialization in MLflow codebases |
| [Valkyrie](https://github.com/Carrtik/Valkyrie) | Linux privilege escalation auditor mapped to MITRE ATT&CK |
| [Cylock](https://github.com/Carrtik/Cylock) | Multi-threaded network scanner built from raw TCP/IP primitives |
| [Dynamic-Honeypot-RL](https://github.com/Carrtik/Dynamic-Honeypot-RL) | Adaptive honeypot using Q-learning to respond to live attacker behaviour |
| [Shield-Cloud](https://github.com/Carrtik/Shield-Cloud) | Self-healing cloud with CRYSTALS-Kyber + AES-256-GCM, autonomous key rotation |

## Writing

- [My Linux kernel patch got merged by Andrew Morton. Then it got removed. Here's why that's still a win.](https://medium.com/@contact.kartikn/my-linux-kernel-patch-got-merged-by-andrew-morton-then-it-got-removed-heres-why-that-s-still-a-win)
- [I submitted 4 Linux kernel patches in one night as a final year student](https://medium.com/@contact.kartikn/i-submitted-4-linux-kernel-patches-in-one-night-as-a-final-year-student-188ba790eb17)
- [I found a bug in software running on millions of routers](https://medium.com/@contact.kartikn/i-found-a-bug-in-software-running-on-millions-of-routers-my-first-cve-6e98f4ebda27)

## Stack

Python · C · Bash · Linux Internals · Raw Sockets · Docker · CRYSTALS-Kyber · MITRE ATT&CK
