# Howdy, I'm Vedanth Dharnish

I'm a Honors Computer Science student at Texas A&M University class of 2028,
building AI-powered developer tools and researching adversarial machine
learning.

---

## 🎬 Featured: reeltime

**A deterministic record/replay debugger for LLM agents.** `pip install reeltime`

[![PyPI](https://img.shields.io/pypi/v/reeltime.svg)](https://pypi.org/project/reeltime/)
[![Downloads](https://static.pepy.tech/badge/reeltime)](https://pepy.tech/project/reeltime)
[![Tests](https://img.shields.io/badge/tests-882%20passing-brightgreen.svg)](https://github.com/vedanth2406/reeltime)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://github.com/vedanth2406/reeltime/blob/main/LICENSE)

Agent runs are nondeterministic, so failures can't be reproduced — you re-run
and the bug moves. reeltime records every source of nondeterminism at four
boundaries and replays a run exactly: offline, instantly, for free.

- **Intercepts at the transport layer, not the SDK** — one shim covers `httpx`,
  `httpx2`, `requests` and `urllib3`, so OpenAI, Anthropic, Bedrock/`boto3` and
  anything else HTTP is recorded without knowing they exist
- **Replay survives an edited prompt** via three-tier call matching — the case
  content-hash tools fail by construction
- **Fork from step N** to test one changed variable with the first N steps free
- **MCP sessions and LangChain/LangGraph** structure as first-class events
- **Streaming captured chunk-exact**, including Bedrock's binary event stream
- **~0.2 ms** overhead per recorded HTTP call; **882 tests**, 95% coverage

Shipped **1.0** across seven releases. Python 3.9+, zero runtime dependencies.

**[→ github.com/vedanth2406/reeltime](https://github.com/vedanth2406/reeltime)**

---

## 💼 Experience

**AI Engineering Intern** · Cacti Industries, Austin TX · *Summer 2026*
Voice interface for robot fleets — ROS 2 and locally-hosted LLMs.

**Undergraduate Research Assistant** · Texas A&M, advised by Prof. Marcus Botacin
Adversarial machine learning for phishing detection: a perturbation-under-fire
framework evaluating model robustness against TextFooler and PWDGAN-style
evasion attacks.

**Executive Committee** · TAMU Engineering Honors
Co-organize the EH Career Fair and Research Lab Open House.

---

## 🔬 What I work on

**AI tooling and reliability.** reeltime came out of a real frustration:
debugging an agent that failed differently every run. Most of the engineering
went into the parts that make a debugger trustworthy — matching that survives
code edits, redaction that runs before anything reaches disk, and a rule that
the tool fails loudly rather than quietly doing the wrong thing.

**Adversarial ML and security.** My research is on how text classifiers behave
when someone is actively trying to fool them, which is the same question as
"what does this model actually key on?"

**Computer vision.** [Oculon](https://github.com/vedanth2406) — AI traffic
incident detection using YOLOv8, OpenCV and Flask, detecting collisions from
live traffic video and triggering alerts.

---

## 🛠 Tech

**Languages** · Python · C/C++ · Java · TypeScript/JavaScript · SQL

**ML & AI** · PyTorch · YOLOv8 · OpenCV · Hugging Face · LangChain · MCP

**Backend & Infra** · FastAPI · Flask · Postgres · Docker · AWS · ROS 2

**Practices** · pytest · CI/CD · semantic versioning · packaging & release
engineering

---

## 📫 Reach me

- **GitHub** · [@vedanth2406](https://github.com/vedanth2406)
- **Email** · vedanth2406@gmail.com

*Looking for Summer 2027 software engineering internships.*
