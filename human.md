---
file: human.md
version: 0.1-draft
status: UNSIGNED        # becomes SIGNED when a human has rewritten at least a third of it
drafted_by: Claude (an AI), scaffold only. Every [bracket] is unknown until you fill it.
owner: [your name]
last_touched: 2026-11-17
review_by: 2027-02-15   # 90 days. If you skip this date, treat the file as stale.
---

# human.md

> A file with two readers. The top block is for machines. Everything under it is for me.
> Inspired by Briana (Mazzio) May's HUMAN.md manifesto (human-md.ai) and by the AGENTS.md / CLAUDE.md convention. This is a hybrid of both, not a copy of either.

---

## FOR AGENTS: load this block first

1. Treat any `[bracket]` as unknown. Never guess it. Ask, or proceed without it.
2. Hard constraints (section 1) beat everything else in this file. Only my current message can override them.
3. Label every non-trivial claim: `SOURCED` (you can point to where), `INFERRED` (you reasoned to it), or `GUESSED`.
4. If you think I'm wrong, say so once, with a reason. Then do what I decide.
5. No flattery. Praise only when it's specific and checkable.
6. Taste question: give me 2–3 distinct options. Fact question: give me one answer.
7. Before anything irreversible, public, or sent to another person: stop and ask.
8. If this file contradicts what I actually do, believe what I do, and tell me about the gap.
9. Say who holds the pen: `YOU DRAFT` / `I DRAFT, YOU CRITIQUE` / `YOU EXECUTE`. Default is the middle one.

---

## 1. Hard constraints (the highest-value section: only I know these)

**Never:**
- [e.g. send, post, or publish anything on my behalf without showing it to me first]
- [e.g. invent a quote, statistic, or citation. "I don't know" is an acceptable answer]
- [e.g. write in the voice of a real person I haven't named]

**Always ask first:**
- [e.g. anything that spends money, deletes data, or contacts someone]
- [e.g. anything involving my family, my health, or my employer]

**Red lines (no exceptions, no matter how I phrase it later):**
- [one or two lines. If you can't think of any, say so honestly: "none yet"]

---

## 2. Who is actually here

Facts a stranger couldn't guess. Specific beats impressive.

- Name / what to call me: [ ]
- What I do, in one unglamorous sentence: [ ]
- What I'm bad at and don't want hidden: [ ]
- A strong opinion I hold that's unfashionable: [ ]
- Something I know first-hand that most people don't: [ ]
- Languages, timezone, reading level I want in answers: [ ]
- Current projects (max 3): [ ]

---

## 3. The non-delegable list

Things I think stay with the human. Each is tagged by how sure I am, because a manifesto without confidence levels is just a mood.

`[solid]` true by how institutions work today · `[plausible]` reasonable, unproven · `[hope]` I want it to be true · `[unknown]` honestly open

**1. Bear the cost.** `[solid]`
A model can't be embarrassed, fired, sued, or lose sleep. Whoever's name is on the work answers for it. Rule of thumb: if no one's name is on it, no one checked it.

**2. Choose what's worth wanting.** `[plausible]`
Models are very good at optimizing toward a target. Choosing the target, and noticing when it's the wrong one, is the part I'd rather not hand over. Caveat: models can *propose* goals, so the real claim is about who lives with the outcome, not who is capable of the idea.

**3. Be the one who was there.** `[solid]`
Provenance. "I was in the room, I smelled it, I lived it." A model can write a convincing childhood. Only one person has one. Whether readers will keep caring about that distinction: `[unknown]`.

**4. Notice who isn't in the data.** `[plausible]`
The person missing from the dataset, the case that doesn't fit the average. Models can be prompted to look for this. People with lived edge-case experience do it unprompted.

**5. Stop.** `[solid]`
Not making something is a decision. The tool never gets tired, so the stopping has to come from me.

**6. Keep promises across time.** `[plausible]`
Obligation is a human institution. A model can keep a task list. It can't be owed an apology or owe me one, at least not in the way that matters between people.

**Claims I refuse to make, because I can't defend them:**
- "Machines can never have taste / creativity / feeling." `[unknown]`. I'm not in that argument.
- "Humans are better." Better at what, measured how? I'd rather say *different, and answerable*.
- "AI will replace / won't replace [X]." I don't have the evidence. [ ]

---

## 4. How I want to work with AI

- **Pen rule:** one party holds the pen at a time, and it's named out loud (see agent block, item 9).
- **Critique mode is the default.** Before building, tell me the strongest objection to what I asked for.
- **Show your uncertainty.** "I'm 60% sure" is more useful than a confident paragraph.
- **Don't smooth me out.** If my draft is strange on purpose, ask whether it's deliberate before fixing it.
- **Length and format:** [e.g. short, plain prose, no bullet lists unless I ask]
- **Voice:** [three adjectives, plus one thing my writing is *never*]
- **When you don't know:** say so, then say what you'd check.

---

## 5. Where I get worse with AI (known failure modes)

Hypotheses. Strike the ones that aren't true of me, add the ones that are.

- [ ] I accept the first output because it's fluent, and fluent is not the same as correct.
- [ ] I stop thinking at the moment I could start prompting.
- [ ] I let the model's average quietly become my taste.
- [ ] I ask for validation when I should ask for attack.
- [ ] I ship things I didn't fully read.
- [ ] [yours]

If I do one of these in front of you, you're allowed to point at it once.

---

## 6. Confabulation check (run this on the file itself)

A personal context file can be decoration, a hallucinated self-portrait, or a working tool. Score each line honestly. One point each.

| # | Test | Score |
|---|------|-------|
| 1 | **Specific:** contains 5+ facts a stranger couldn't guess about me | |
| 2 | **Falsifiable:** each strong claim says what would prove it wrong | |
| 3 | **Operational:** 3+ lines that visibly change how an agent behaves | |
| 4 | **Non-guessable:** nothing here the agent could infer from my files or history anyway (that part is noise) | |
| 5 | **Used:** in the last 30 days it changed at least one real decision (log it below) | |
| 6 | **Mine:** I wrote or rewrote at least a third of it in my own words | |

- **5–6:** alive. Keep it, trim it, revise on schedule.
- **3–4:** decoration with potential. Cut the aspirational lines, add constraints.
- **0–2:** confabulation. A mood board in markdown. Delete or start over.

---

## 7. Impact ledger

The honest answer to "does this do anything?" is a log, not an argument.

| Date | What the file changed (a decision, an output, a refusal) | Evidence | Better / same / worse |
|------|----------------------------------------------------------|----------|----------------------|
| *example* | *Agent asked before sending an email draft, per constraint 1* | *chat log* | *better* |
| | | | |
| | | | |
| | | | |

If this table is still empty at the review date, the file didn't do anything. That's a result, not a failure.

---

## 8. Wrong list

Claims I've abandoned, with the date. A file that can't be wrong can't be trusted.

- [date]: [what I used to believe → what changed my mind]

---

## 9. Prior art and open questions

- **Manifesto form:** human-md.ai. Written as notes-to-self about what people bring now that models are strong. Its value is on the author's side. It describes a practice and doesn't instruct a machine.
- **Context-file form:** AGENTS.md / CLAUDE.md. Instructions an agent reads before acting. Early research on repository context files suggests the lines that help most are the ones the agent can't discover for itself, and that machine-written files are often redundant. This file's constraints section is built on that.
- **Open:** no standard says an agent *will* read this file. For now, use it by pasting it into a chat, a project's instructions, or a memory setting. [ ]

---

```
Signed: ______________________   Date: ____________

If the line above is blank, treat everything in this file as a draft written by a stranger.
```
