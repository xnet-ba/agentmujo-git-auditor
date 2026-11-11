<div align="center">

# 🔍 AgentMujoGitAuditor

### *Nezavisni audit repozitorija — bez nagađanja, sve s dokazom.*

[![MIT License](https://img.shields.io/badge/license-MIT-green.svg)](LICENSE)
[![OpenCode Skill](https://img.shields.io/badge/opencode-skill-blueviolet)](https://opencode.ai)
[![Jezik: BS](https://img.shields.io/badge/jezik-bosanski-blue)](SKILL.md)
[![Audit](https://img.shields.io/badge/audit-security%20%7C%20arch%20%7C%20quality-orange)](SKILL.md)

<em>Sigurnost · Ispravnost · Arhitektura · Testovi · Performanse · Licence</em>

</div>

---

## <img src="https://img.shields.io/badge/🔍-audit-blue?style=flat-square" width="20"/> Šta radi

<table>
<tr><td>🛡️ <b>Sigurnost</b></td><td>Tajne u kodu i historiji, injection, auth, kriptografija, zavisnosti, Docker/CI</td></tr>
<tr><td>🔧 <b>Ispravnost</b></td><td>Logičke greške, race conditions, izuzeci, resursi, konkurentnost</td></tr>
<tr><td>🏛️ <b>Arhitektura</b></td><td>Moduli, ciklične zavisnosti, duplikati, mrtav kod, konvencije</td></tr>
<tr><td>✅ <b>Testovi</b></td><td>Postojanje, pokretanje s tačnim rezultatom, kvalitet, CI blokade</td></tr>
<tr><td>⚡ <b>Performanse</b></td><td>N+1, I/O petlje, indeksi — samo potkrijepljeno kodom</td></tr>
<tr><td>📄 <b>Licence</b></td><td>README vs. stvarnost, kompatibilnost licenci</td></tr>
</table>

## 📥 Instalacija

```bash
git clone https://github.com/xnet-ba/agentmujo-git-auditor
mkdir -p ~/.config/opencode/skills/agentmujo-git-auditor
cp agentmujo-git-auditor/SKILL.md ~/.config/opencode/skills/agentmujo-git-auditor/SKILL.md
```

## 🚀 Upotreba

> Pozovi sa **`AgentMujoGitAuditor`** — puni audit repoa u trenutnom direktoriju, izvještaj u `audit/AUDIT_REPORT.md`.

<ul>
<li>🔒 <b>Svaki nalaz mora imati dokaz</b> — <code>fajl:linija</code> + citat koda, inače ne ulazi u izvještaj</li>
<li>🏷️ <b>Oznake pouzdanosti:</b> <code>[POTVRĐENO]</code> · <code>[VJEROVATNO]</code> · <code>[NEPROVJERENO]</code></li>
<li>✋ <b>Ne mijenja kod</b> — samo čita i izvještava, bez izričitog zahtjeva ništa ne popravlja</li>
</ul>

## 📁 Struktura

| Fajl | Opis |
|---|---|
| `SKILL.md` | Cijeli skill — faze 0–6, format izvještaja, kriteriji ozbiljnosti, samoprovjera |
| `LICENSE` | MIT |

---

<div align="center">

<sub>Napravljeno za <b>OpenCode</b> · <a href="https://github.com/xnet-ba">AgentMujo</a> · MIT</sub>

</div>
