<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:1f3a5f,100:4a7fb0&height=200&section=header&text=Jinhyoung%20Ahn&fontSize=56&fontColor=ffffff&fontAlignY=38&desc=AI%20%C2%B7%20Drug%20Discovery%20%C2%B7%20Algorithm&descAlignY=60&descSize=20" alt="header" />

<p>
  <img src="https://img.shields.io/badge/Gachon%20Univ.-Biologics%20%26%20Smart%20Security-1f3a5f?style=flat-square" />
  <img src="https://img.shields.io/badge/focus-computational%20chemistry-4a7fb0?style=flat-square" />
  <img src="https://img.shields.io/badge/status-learning%20by%20building-2e7d5b?style=flat-square" />
</p>

</div>

## 👋 About

I'm an undergraduate at Gachon University, majoring in Biologics and double-majoring in Smart Security. I'm interested in **AI-driven and computational drug discovery**, the idea of filtering drug candidates on a computer before they reach the bench. In my undergraduate research lab, I work on peptide synthesis and molecular docking.

## 🧪 Research

<table>
<tr>
<td width="50%" valign="top">

**Multi-Pharmacology Structure-Activity Relationship lab (undergraduate researcher)**
- Solid-phase peptide synthesis (SPPS) of cyclic hexapeptides
- Molecular docking practice in Schrödinger Maestro
- Molecular dynamics (MD): currently in the theory-learning stage

</td>
<td width="50%" valign="top">

**Interests**
- AI-based drug candidate discovery and computational drug design
- Structure-based drug design and interpreting docking results

</td>
</tr>
</table>

**Algorithm lab**

https://ce.gachon.ac.kr/algorithm-lab

## 🛠 Stack

<p>
  <img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white" />
  <img src="https://img.shields.io/badge/Lua-2C2D72?style=flat-square&logo=lua&logoColor=white" />
  <img src="https://img.shields.io/badge/C++-00599C?style=flat-square&logo=cplusplus&logoColor=white" />
  <img src="https://img.shields.io/badge/Claude%20API-D97757?style=flat-square" />
</p>

## 🚀 Projects

<details>
<summary><b>📄 pdf-reflux</b> — Automatic classification and archiving system for paper PDFs</summary>

<br/>

- **Detection**: A Windows `PowerShell FileSystemWatcher` watches for download changes and calls the classification script via `wsl -d Ubuntu`. WSL2 does not receive inotify events for `/mnt/c` changes, so watching runs natively on Windows.
- **Classification**: A system prompt is generated at runtime from a user-defined YAML file (category list and boundary rules). The Claude API (Haiku) returns structured JSON in the form `{category, confidence, reason}`.
- **Data**: Implemented with SQLite; migration to Supabase (Postgres) is in progress. SHA-256 file hashes catch re-downloads even when the path differs. API failures and low-confidence unclassified files are recorded separately via `error_type`.
- **Safeguards**: A PreToolUse hook restricts file move destinations to a whitelist of paths. The PDF parser (pdfminer.six) has its dependency version floor pinned to avoid known CVEs.

</details>

<details>
<summary><b>🔐 Wargame & Security</b> — Dreamhack practice</summary>

<br/>

Practicing binary exploitation, cryptography, reverse engineering, and smart contract security through Dreamhack challenges.

</details>

<details>
<summary><b>🧮 Competitive Programming</b> — BOJ</summary>

<br/>

<a href="https://solved.ac/profile/aunps"><img src="https://mazassumnida.wtf/api/v2/generate_badge?boj=aunps" alt="Solved.ac profile" /></a>

Mainly solving in Lua, also C++.

</details>

## 🔗 Links

- ⛓️ Research notes: [`Articles`](https://github.com/hyper-cloud10/Articles) — Celestia DA, zkVM, on-chain IP licensing
- 🏫 Gairos — Gachon University Blockchain Society
- 📫 X: [@unsafe_rust](https://x.com/unsafe_rust)

## 📊 Languages

<img src="https://github-readme-stats.vercel.app/api/top-langs/?username=hyper-cloud10&layout=compact&theme=tokyonight&hide_border=true" alt="Top Languages" />
