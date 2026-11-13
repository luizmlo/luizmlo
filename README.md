## Luiz Felipe Melo

Security engineer and ML researcher based in Tubarão, Brazil. I work at the intersection of offensive security and
machine learning: how models fail, how to look inside them, and how to fix them. I have about 8 years of experience
in software development and 4 in cybersecurity.

[ORCID](https://orcid.org/0009-0007-5134-9914) · [LinkedIn](https://www.linkedin.com/in/luiz-felipe-melo-067722213)

### Highlights

- **Research (2026):** *Agentic Weight-Space Programming as an Alternative to Fine-Tuning in Small Language Models*.
  Claude agents repair a thinking loop in a small language model by editing its weights directly.
  [Pre-paper](https://doi.org/10.5281/zenodo.24208535) ·
  [code, data and lab notebook](https://github.com/luizmlo/agentic-weight-editing)
- **Security:** built and led a vulnerability-management service monitoring 15,000+ assets for 25+ corporate clients.
- **CTF:** 1st place in the RNP CTF at Campus Party Brasília 2019.

### Research

**Agentic weight editing** (2026) · [pre-paper, DOI 10.5281/zenodo.24208535](https://doi.org/10.5281/zenodo.24208535) ·
[repository](https://github.com/luizmlo/agentic-weight-editing)
- **Question:** can an AI agent repair a defect in a language model by editing its weights directly, without training?
- **What I did:** Claude agents read the weights of Qwen3.5-0.8B and wrote at most four rank-1 edits that stop its
  endless reasoning loops, on a single gaming GPU. On locked GSM8K test problems, accuracy went from 15.5% to
  61.5–68%, and six agent runs of the same protocol all repaired the defect.
- **Compared against:** the edit that GPT-6 Astra wrote in MIT CSAIL's *Sparks of Weight-Space Programming*, which
  reaches the same accuracy only with about twice the tokens; LoRA fine-tuning, which falls well short; and simple
  decoding baselines, which come close. Switching thinking off is cheaper still.
- **Method:** every prediction was pre-registered in a public lab notebook, two test sets stayed locked until the end,
  and the predictions that failed are reported. The same method failed on a diffuse defect, and the paper says why.

Interests: mechanistic interpretability, weight-space editing, LLM agents, AI security.

### Security

- **Vulnerability management at scale.** At OSTEC Business Security I built and led a continuous
  vulnerability-management service from scratch. It monitored 15,000+ assets daily for 25+ corporate clients in
  industry, retail and critical infrastructure (Tenable Nessus and in-house Python automation).
- **Penetration testing.** I have tested web applications, APIs and networks for large companies in retail and
  construction, including a publicly listed multinational, from kick-off to executive report. Clients are under NDA.
- **Attack-surface mapping.** I built Scandara, an event-driven scanning platform (FastAPI, Arq, PostgreSQL, Redis)
  that processes about 50,000 URLs a day.
- **CTF.** At Campus Party Brasília 2019 I placed 1st in the RNP CTF and 2nd in the Decred CTF.

### Talks

All talks were given at Universidade do Sul de Santa Catarina (Unisul), Tubarão.

| Year | Talk |
|---|---|
| 2026 | *End of the World by AI: Where Are We on the Timeline?* |
| 2026 | *Real Bitcoin: Myths, Blockchain and Decentralization* |
| 2025 | *Practical AI: Self-hosting LLMs* (workshop) |
| 2023 | *Exploits in Web Applications and APIs* (live red-team demo, OWASP Top 10) |

### Now

- **Scale Tech:** software developer and head of support. I contribute to Scale One, a CRM in which Claude agents run
  WhatsApp sales conversations, and I build the support team's tooling, including an episode classifier running in
  shadow mode.
- **Codara:** security and platform engineer.
- **DATUS** (Unisul's IT student association): events director. So far I have organised two hackathons, an AI
  workshop and technical talks.
- **Unisul:** BSc in Computer Science, expected 2027.

### Selected open source

| Project | Description |
|---|---|
| [agentic-weight-editing](https://github.com/luizmlo/agentic-weight-editing) | Claude agents edit the weights of Qwen3.5-0.8B to fix its thinking loops: code, lab notebook, every edit (Python, PyTorch, llama.cpp) |
| [a3_botnet](https://github.com/luizmlo/a3_botnet) | Botnet research prototype in Python (asyncio, WebSockets) |
| [dit](https://github.com/luizmlo/dit) | HTML page, form and field classifier (logistic regression + CRF), in Go |
| [EasyLSTM](https://github.com/luizmlo/EasyLSTM) | Data shaping, training and inference for LSTM networks in Keras |
| [aim-ml](https://github.com/luizmlo/aim-ml) | Training neural networks from screenshots |
| [aic8800d80-kernel7](https://github.com/luizmlo/aic8800d80-kernel7) | AIC8800D80 USB Wi-Fi driver patched for Linux kernel 7.0 |

### Tools

```
ML        PyTorch · transformers · llama.cpp · Keras · scikit-learn
Security  Burp Suite · Nmap · Metasploit · Tenable Nessus · Wazuh
Code      Python · Go · C/C++ · JavaScript · SQL
Systems   Linux · Docker · PostgreSQL · Redis · FastAPI
```

Languages: Portuguese (native), English (fluent), Spanish (basic).
