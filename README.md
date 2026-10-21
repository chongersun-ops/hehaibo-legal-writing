# hehaibo-legal-writing

Agent skill generated from *《法学论文写作》* by 何海波 (北京大学出版社 2014) with [book-to-skill](https://github.com/virgiliojr94/book-to-skill). It turns the book's frameworks for Chinese legal academic writing — 选题、文献、调查、论证、论文各部分、行文、学术伦理 — into a toolkit an agent can apply when drafting, reviewing or revising a Chinese law paper or dissertation.

The content is synthesized summaries and extracted frameworks, not the book text. The source book is copyrighted; keep this repository private.

## Install

```bash
npx skills add https://github.com/chongersun-ops/hehaibo-legal-writing --skill hehaibo-legal-writing
```

Or clone into your skills folder, e.g. `~/.claude/skills/hehaibo-legal-writing`.

## Files

| File | Contents |
|---|---|
| `SKILL.md` | Core frameworks, chapter index, topic index |
| `chapters/ch01-xuanti.md` … `ch07-lunli.md` | One study-depth note per 讲 |
| `glossary.md` | Key terms (pinyin order) |
| `patterns.md` | Actionable techniques |
| `cheatsheet.md` | Decision rules, thresholds, red flags |
