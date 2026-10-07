# research-methods-skill

**Stuck on a research gap? Writing a grant proposal at 2am? Not sure whether a paper's claim is backed by evidence?**

This is a Claude Code skill that turns a set of practical research-workflow methods into on-demand guidance. Ask a question in your normal research flow and Claude loads the relevant method: step-by-step procedures, decision rules, and checklists, not generic advice.

中文版见 [README.zh-CN.md](README.zh-CN.md)。

## What you get

- **Find a research gap, then prove it is real.** Build a literature knowledge base, intersect keyword groups, look for pairs of papers with contradictory results, and run a four-question test on every candidate gap.
- **Write a grant proposal whose every claim has evidence.** A seven-paragraph skeleton (significance, bottleneck, existing approaches, limits, gap, your method and pilot data, key scientific questions) with a logic chain you can check.
- **Debug an experiment like code.** Isolate variables, substitute components, eliminate causes, and decompose the problem instead of changing everything at once.
- **Write a paper sentence by sentence.** Every claim needs a visible "fact → logic → conclusion" bridge; a sentence-bank method for introductions; plagiarism thresholds.
- **Self-check before submission.** Go through one defect class per pass: formatting, citations, cross-references, internal contradictions, and evidence.
- **Choose an advisor with numbers.** Compare candidate PIs by publication rate and delay rate, ranked by your post-graduation goal.
- **Keep going when research feels hopeless.** Practical tools for procrastination, focus loss, rejection, and decision paralysis.

## Core principles

- Every claim needs evidence and a logic bridge. A sentence without one should not be written.
- Build one continuously updated knowledge base instead of starting from zero each time.
- Test beats inference: search, grouping, experiments, and writing all improve through feedback.
- A fuzzy correct answer beats a precise wrong one. Estimates can be rough; the direction must be right.

## Try it

Ask Claude something like:

> I want to find a research gap in corrosion of additively manufactured alloys, then write the significance section of a proposal. Where should I start?

or

> My experiment does not reproduce. Give me a debugging order that changes one thing at a time.

Claude will load the matching reference files and follow their steps.

## Install

Copy the skill folder into your Claude Code skills directory:

```bash
cp -r research-and-paper-writing-method ~/.claude/skills/
```

## Repository layout

```
research-and-paper-writing-method/
├── SKILL.md                              entry point: triggers, index, core principles
└── references/
    ├── 01-topic-selection-and-literature.md
    ├── 02-experimental-debugging.md
    ├── 03-paper-writing-method.md
    ├── 04-writing-checklist.md
    ├── 05-keyan-advisor-selection.md
    ├── 06-keyan-sentence-bank-writing.md
    ├── 07-keyan-literature-search-grouping.md
    ├── 08-keyan-topic-selection-and-ideas.md
    ├── 09-keyan-secondary-grouping-verification.md
    ├── 10-keyan-paper-selfcheck-checklist.md
    ├── 11-keyan-mindset-modular-tools.md
    └── 12-keyan-proposal-writing.md
```

## About the sources

The methods are generalized from published and publicly available research-methodology sources. Book- and course-specific examples, names, institutions, and case studies have been removed; any remaining examples are labelled as hypothetical. This repository does not reproduce source text.

If you are a rights holder and believe any content infringes your rights, please open an issue and the affected content will be removed.
