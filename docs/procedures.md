# Procedures

## 1. Build workflow (every door)

1. **Define** (15 min): user, input, output, one sentence of "done". Fill the top of the door README.
2. **Test set first** (30 min): collect 10–20 real or anonymised cases into `eval/cases.csv` with the expected result. Decide the pass rule before building.
3. **Build v1** (30–60 min): prompt / skill / artifact / n8n workflow. Save the prompt in `prompt/v1.md`.
4. **Evaluate v1**: run every case, mark pass/fail, write the score in `eval/results.md`.
5. **Iterate** (1–2 rounds): change one thing at a time, save as v2, re-run, record the new score.
6. **Publish**: demo video (≤30 s), door README, LinkedIn post, update the status in the main README and Notion.

## 2. Definition of Done

- [ ] Works on a fresh input that was not in the test set
- [ ] `eval/results.md` shows at least v1 and final score
- [ ] Door README complete (problem, how it works, result, lesson)
- [ ] No personal data, no API keys, no credentials in the repo
- [ ] Disclaimer added where the topic touches legal/official processes
- [ ] Anything that sends, deletes or submits requires human approval
- [ ] Demo video recorded, post scheduled, Notion row updated

## 3. Evaluation method

- **Cases**: 10–20 per door; mix easy, typical and tricky inputs. Include both marketing and quality-engineering examples where relevant.
- **Pass rule**: written before building (for example "all must-have requirements found, no invented ones").
- **Score**: passed cases / total cases. Record per version.
- **Model comparison** (where relevant): same cases, two models; record score, cost per run and time per run.
- **LLM-as-judge**: allowed only with a written rubric, and checked against your own rating on at least 5 cases.
- **Honest reporting**: report the real number, including what still fails.

## 4. Rules

- **Privacy**: anonymise CVs, emails and letters. For job ads store the link plus your own labels, or a short excerpt, not full copies.
- **Secrets**: API keys live in `.env` or n8n credentials, never in the repo. Exported n8n workflows are checked for credentials before commit.
- **Human in the loop**: no tool sends an email, message or application on its own.
- **Not advice**: degree recognition, official letters and reference letters: explain and link to official sources; no legal advice.
- **Transparency**: every post says it was built with AI tools and what your part was.

## 5. Rhythm

- Build **2 days ahead** (hard doors: 3 days). Weekends are for hard doors and light posts.
- **Sunday**: plan the week, check the buffer, swap a hard door with an easy one if you are behind.
- **Daily**: publish, reply to every comment in the first hour, log the metrics next day.
