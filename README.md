# Jobstart Germany: an advent calendar of 24 AI tools 🎄

One practical AI tool per day, 1–24 December 2026, for international professionals and new graduates looking for a job in Germany.

Every tool solves one real job-search problem (language, German application standards, few junior roles, long search times) and shows one **professional AI technique**: structured output, knowledge bases with citations, agents with tools, human-in-the-loop approval, model comparison and, above all, **measured evaluation**. Each door reports a number, not just a demo.

Built by [Mahnaz Jaldi](https://www.linkedin.com/in/mahnaz-jaldi/) with Claude, n8n and Notion.

## The 24 doors

| # | Date | Tool | What it does | Technique | Built with | Status |
|---|---|---|---|---|---|---|
| 01 | 2026-12-01 | [Stellenanzeigen-Decoder](doors/01-stellenanzeigen-decoder/) | Paste a German job ad; get must-haves vs nice-to-haves, hidden requirements, a 'really junior?' score and likely interview questions | Structured output (JSON schema) + evaluation set | Claude Artifact | ⏳ |
| 02 | 2026-12-02 | [Lebenslauf-Konverter](doors/02-lebenslauf-konverter/) | Turns an international CV into a German tabular Lebenslauf (order, dates, photo/personal-data conventions explained) | Structured output + template rendering | Claude Artifact | ⏳ |
| 03 | 2026-12-03 | [ATS-Check](doors/03-ats-check/) | Compares a CV with a job ad: keyword coverage, missing skills, wording suggestions | Model comparison (quality vs cost vs speed) | Claude Artifact | ⏳ |
| 04 | 2026-12-04 | [Zwei-Wege-CV](doors/04-zwei-wege-cv/) | One experience history, two tailored CVs: marketing/automation track and quality-engineering track | Reusable Claude Skill (packaged instructions + examples) | Claude Skill | ⏳ |
| 05 | 2026-12-05 | [Floskel-Detektor](doors/05-floskel-detektor/) | Highlights cliché phrases in a cover letter and suggests concrete replacements | Classification + rewrite with examples | Claude Artifact | ⏳ |
| 06 | 2026-12-06 | [Wichtel-Generator](doors/06-wichtel-generator/) | Nikolaus fun: Secret Santa draw for a team with constraints and gift ideas by budget | Constraint logic in code + AI suggestions | Claude Artifact | ⏳ |
| 07 | 2026-12-07 | [Bewerbungs-Tracker](doors/07-bewerbungs-tracker/) | Logs every application, detects replies in Gmail, sends follow-up reminders and drafts the follow-up for approval | Agent with tools + human-in-the-loop approval | n8n + Notion + Gmail | ⏳ |
| 08 | 2026-12-08 | [Interview-Coach](doors/08-interview-coach/) | German mock interview for marketing/quality roles with separate feedback on language and content | Rubric-based grading (LLM-as-judge) | Claude Artifact | ⏳ |
| 09 | 2026-12-09 | [Fachwortschatz-Karten](doors/09-fachwortschatz-karten/) | Extracts professional vocabulary from a job ad and makes flashcards with example sentences | Structured output -> spaced repetition data | Claude Artifact | ⏳ |
| 10 | 2026-12-10 | [Höflichkeits-Check](doors/10-hoeflichkeits-check/) | Rates an email's formality, du/Sie consistency and politeness; suggests better phrases | Classification + evaluation set | Claude Artifact | ⏳ |
| 11 | 2026-12-11 | [Behörden-Brief](doors/11-behoerden-brief/) | Explains German official letters: what they want, deadline, next step (existing skill, polished) | Claude Skill + safety rules (no legal advice) | Claude Skill | ⏳ |
| 12 | 2026-12-12 | [Dankesmail](doors/12-dankesmail/) | Writes a short thank-you / follow-up email after an interview from your notes | Few-shot style control | Claude Artifact | ⏳ |
| 13 | 2026-12-13 | [Kontakt-Nachricht](doors/13-kontakt-nachricht/) | Drafts a LinkedIn message to someone you don't know (alumni, team lead) in German or English | Personalisation from a profile summary | Claude Artifact | ⏳ |
| 14 | 2026-12-14 | [Anerkennung-Navigator](doors/14-anerkennung-navigator/) | Step-by-step guide to recognising a foreign degree, answering only from official sources with links | Knowledge base / retrieval with citations | Claude Project / Artifact | ⏳ |
| 15 | 2026-12-15 | [Zeugnis-Decoder](doors/15-zeugnis-decoder/) | Decodes the hidden grading language of a German Arbeitszeugnis and explains each sentence | Knowledge base of phrase scale + evaluation | Claude Artifact | ⏳ |
| 16 | 2026-12-16 | [KMU-Radar](doors/16-kmu-radar/) | Finds lesser-known mid-sized companies (Mittelstand) by region and industry, with careers-page links | Agent with web-search tool + source checking | Claude + Web search | ⏳ |
| 17 | 2026-12-17 | [Job-Digest-Agent](doors/17-job-digest-agent/) | Weekly email with new roles scored against your profile, with a one-line reason per role | Scheduled workflow + scoring with structured output | n8n + RSS + Gmail | ⏳ |
| 18 | 2026-12-18 | [Fehler-Dashboard](doors/18-fehler-dashboard/) | Collects your corrected German texts and shows which mistakes you repeat most | Data pipeline: classify -> store -> dashboard | n8n + Notion | ⏳ |
| 19 | 2026-12-19 | [Smalltalk-Coach](doors/19-smalltalk-coach/) | Practice small talk for the office Christmas party: topics, phrases, what to avoid | Role-play with scenario presets | Claude Artifact | ⏳ |
| 20 | 2026-12-20 | [Profil-Audit](doors/20-profil-audit/) | Audits a LinkedIn profile from a German recruiter's view: headline keywords, DE/EN, gaps | Checklist-based evaluation skill | Claude Skill | ⏳ |
| 21 | 2026-12-21 | [Absagen-Analyse](doors/21-absagen-analyse/) | Reads rejection emails, classifies stage and reason, shows patterns on a dashboard | Classification + aggregation + dashboard | n8n + Gmail + Sheets | ⏳ |
| 22 | 2026-12-22 | [Initiativ-Pipeline](doors/22-initiativ-pipeline/) | Company list -> research -> personalised speculative application drafts; nothing is sent without approval | Multi-agent chain + human approval gate | n8n + Claude | ⏳ |
| 23 | 2026-12-23 | [Telefon-Trainer](doors/23-telefon-trainer/) | Prepares and rehearses a phone screening or call to a recruiter in German | Scenario role-play + feedback rubric | Claude Artifact | ⏳ |
| 24 | 2026-12-24 | [Jobsuche-OS](doors/24-jobsuche-os/) | Finale: all 24 tools in one public repo with an index, automated eval checks and lessons learned | Version control + automated evaluation + publishing | GitHub (+ Claude Code) | ⏳ |

Status: ⏳ planned · 🔧 building · ✅ live

## How each door is organised

```
doors/NN-name/
├── README.md        problem, user, how it works, evaluation results, lessons learned
├── prompt/          system prompt / skill instructions (versioned)
├── app/             artifact HTML or exported n8n workflow (JSON, no credentials)
└── eval/
    ├── cases.csv    test cases with expected results
    └── results.md   score per version (v1, v2, …)
```

See [docs/procedures.md](docs/procedures.md) for the build workflow, the evaluation method and the rules every door follows.

## Disclaimer

These tools support a job search; they are not legal, immigration or career advice. Tools that touch official processes (degree recognition, official letters, reference letters) link to official sources. No real personal data is stored in this repository.

## License

MIT
