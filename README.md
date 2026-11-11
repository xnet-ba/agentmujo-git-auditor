# AgentMujoGitAuditor

OpenCode skill za nezavisni audit repozitorija: sigurnost, ispravnost, arhitektura, testovi, performanse, licence.

## Instalacija

```bash
# kao OpenCode skill (GitHub izvor)
# dodaj u opencode.json ili preuzmi SKILL.md u svoj skills folder
git clone https://github.com/xnet-ba/agentmujo-git-auditor
cp agentmujo-git-auditor/SKILL.md ~/.config/opencode/skills/agentmujo-git-auditor/SKILL.md
```

## Upotreba

Pozovi skill kada trebaš audit repoa u trenutnom radnom direktoriju:

- `AgentMujoGitAuditor` — puni audit, izvještaj u `audit/AUDIT_REPORT.md`
- Fokus: svaki nalaz mora imati dokaz (`fajl:linija` + citat), oznaku pouzdanosti `[POTVRĐENO]` / `[VJEROVATNO]` / `[NEPROVJERENO]`
- Skill ne mijenja kod — samo čita i izvještava

## Struktura

- `SKILL.md` — cijeli skill (faze 0–6, format izvještaja, kriteriji ozbiljnosti, samoprovjera)
- `audit/` — primjer placeholder; stvarni izvještaji nastaju u auditovanom repou, ne ovdje

## Licenca

MIT
