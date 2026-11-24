# Advent of Germany: 24 AI tools for life in Germany 🎄

One AI tool per day, 1–24 December 2026, for anyone building a life in Germany: language and grammar, everyday life, travel, making friends, and work.

**The rule:** every door does something a single chat prompt can't. Each one uses at least one of: live or verified data, memory over time, photo or voice input, an interactive game or visualisation, automation that runs on its own, or a real algorithm. And every door is **tested and reports a number**, not just a demo.

Built by [Mahnaz Jaldi](https://www.linkedin.com/in/mahnaz-jaldi/) with Claude, n8n and Notion.

## The 24 doors

| # | Date | Tool | Theme | What it does | Technique | Status |
|---|---|---|---|---|---|---|
| 01 | 2026-12-01 | [Brückentage-Optimierer](doors/01-brueckentage-optimierer/) | Life | Plans your 2027 vacation for your Bundesland: the fewest vacation days for the longest breaks, ready for your calendar | Optimisation algorithm + verified holiday data | ⏳ |
| 02 | 2026-12-02 | [Der-Die-Das-Detektiv](doors/02-der-die-das-detektiv/) | Language | Article trainer that learns your weak nouns and shows an error heatmap by word ending (-ung, -chen, -e …) | Spaced repetition + learning analytics | ⏳ |
| 03 | 2026-12-03 | [Mülltrennungs-Scanner](doors/03-muelltrennungs-scanner/) | Life | Photo of an item → which bin it goes in, by your city's rules, with the reason | Vision + knowledge base with sources | ⏳ |
| 04 | 2026-12-04 | [Weihnachtsmarkt-Route](doors/04-weihnachtsmarkt-route/) | Travel | Pick the Christmas markets in your city and your free evening; get an ordered route on a map that respects opening hours | Geo data + route optimisation | ⏳ |
| 05 | 2026-12-05 | [Zettel-Decoder](doors/05-zettel-decoder/) | Life | Photo of a neighbour's note → passive-aggressiveness meter, what they really mean, and a polite German reply | Vision + classification + rewrite | ⏳ |
| 06 | 2026-12-06 | [Wichtel-Generator](doors/06-wichtel-generator/) | Social | Nikolaus special: Secret Santa draw with constraints (no couples, budget) and gift ideas | Constraint logic in code + AI suggestions | ⏳ |
| 07 | 2026-12-07 | [Vertrags-Wächter](doors/07-vertrags-waechter/) | Life | Tracks your contracts (gym, mobile, insurance), reminds you before notice deadlines and drafts the cancellation letter for your approval | Scheduled workflow + human-in-the-loop | ⏳ |
| 08 | 2026-12-08 | [Kasus-Kompass](doors/08-kasus-kompass/) | Language | Build a sentence by tapping words; cases light up in colour and the tool explains why it is Dativ or Akkusativ | Structured grammar parsing + interactive UI | ⏳ |
| 09 | 2026-12-09 | [Deutschlandticket-Radar](doors/09-deutschlandticket-radar/) | Travel | Map of day trips you can reach from your city within X hours using only regional trains | Agent with a data tool + map visualisation | ⏳ |
| 10 | 2026-12-10 | [Dialekt-Landkarte](doors/10-dialekt-landkarte/) | Language | Interactive map of regional words (bread roll, goodbye …) plus a quiz that guesses your region | Curated dataset + interactive map | ⏳ |
| 11 | 2026-12-11 | [Foto-Vokabeln](doors/11-foto-vokabeln/) | Language | Photo of your fridge or a supermarket shelf → labelled words with articles, added to your door-2 deck | Vision + structured output | ⏳ |
| 12 | 2026-12-12 | [Sprachcafé-Würfel](doors/12-sprachcafe-wuerfel/) | Social | Conversation dice for language cafés, levels A2–C1, with follow-up questions | Level-controlled generation | ⏳ |
| 13 | 2026-12-13 | [Kompositum-Baukasten](doors/13-kompositum-baukasten/) | Language | Game: build and break long German compound words, piece by piece | Word-structure analysis + game | ⏳ |
| 14 | 2026-12-14 | [Wohnungs-Check](doors/14-wohnungs-check/) | Life | Paste or screenshot a flat ad → scam red flags, rent compared with the local range, and questions to ask the landlord | Vision + rules engine + evaluation set | ⏳ |
| 15 | 2026-12-15 | [Behörden-Brief](doors/15-behoerden-brief/) | Life | Explains German official letters: what they want, the deadline and the next step (existing skill, polished) | Claude Skill + safety rules (no legal advice) | ⏳ |
| 16 | 2026-12-16 | [Sprachtagebuch](doors/16-sprachtagebuch/) | Language | Speak one minute a day; it transcribes, corrects and builds a monthly progress dashboard | Speech-to-text pipeline + classification + dashboard | ⏳ |
| 17 | 2026-12-17 | [Stammtisch-Radar](doors/17-stammtisch-radar/) | Social | Weekly email with language and social events in your city, matched to your interests | Scheduled workflow + relevance scoring | ⏳ |
| 18 | 2026-12-18 | [Was Deutschland googelt](doors/18-was-deutschland-googelt/) | Data | Data story of what Germany searches in December: gifts, Glühwein, Silvester | Data analysis + storytelling dashboard | ⏳ |
| 19 | 2026-12-19 | [Plätzchen-Rechner](doors/19-plaetzchen-rechner/) | Life | Scales German Christmas cookie recipes and explains unfamiliar ingredients (flour types, Backpulver, Hirschhornsalz) | Unit scaling in code + knowledge base | ⏳ |
| 20 | 2026-12-20 | [Vorsatz-Coach](doors/20-vorsatz-coach/) | Life | Turns a 2027 goal (for example B2 by June) into a calendar plan with automatic weekly check-ins | Planning + scheduled check-ins | ⏳ |
| 21 | 2026-12-21 | [Bewerbungs-Tracker](doors/21-bewerbungs-tracker/) | Career | Logs every application, detects replies in Gmail, reminds you to follow up and drafts the follow-up for approval | Agent with tools + human-in-the-loop | ⏳ |
| 22 | 2026-12-22 | [Telefon-Trainer](doors/22-telefon-trainer/) | Language | Voice role-play for phone calls in German: doctor, landlord, recruiter, with feedback | Voice role-play + rubric grading | ⏳ |
| 23 | 2026-12-23 | [Was 22 Posts mir zeigten](doors/23-post-analyse/) | Data | Analyses this calendar's own LinkedIn numbers: what worked, what didn't, and why | Marketing analytics + dashboard | ⏳ |
| 24 | 2026-12-24 | [Deutschland-OS](doors/24-deutschland-os/) | Finale | Finale: all 24 tools in one hub page and one repo, with each tool's results and the lessons learned | Version control + automated evaluation + publishing | ⏳ |

Status: ⏳ planned · 🔧 building · ✅ live

## How each door is organised

```
doors/NN-name/
├── README.md        problem, how it works, evaluation results, lessons learned
├── prompt/          system prompt / skill instructions (versioned)
├── app/             artifact HTML or exported n8n workflow (JSON, no credentials)
└── eval/
    ├── cases.csv    test cases with expected results
    └── results.md   score per version (v1, v2, …)
```

See [docs/procedures.md](docs/procedures.md) for the build workflow, the evaluation method and the rules every door follows.

## Disclaimer

These tools help with everyday life in Germany; they are not legal, tenancy, immigration or financial advice. Tools touching official processes link to official sources. Rules such as waste separation differ by city. No real personal data is stored in this repository.

## License

MIT
