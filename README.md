# Strategic Management Accounting — Practice Quiz

An interactive, self-paced revision quiz for Strategic Management Accounting. Forty multiple-choice questions across four topic areas, with instant feedback, worked rationales, and a per-topic score breakdown.

**▶ Live site:** https://andrewprimmer.github.io/sma-quiz/

## Topics covered

- Costing & ABC/ABM
- Performance measurement (Balanced Scorecard, ROI, RI, EVA, KPIs)
- Strategic positioning & the value chain (Porter, target & life-cycle costing)
- Budgeting & variance analysis

## How to use it

Open the live link, answer each question, and read the rationale that appears. At the end you get an overall score and a breakdown showing which topics to revise. Click **Retake quiz** to start again.

## Embedding in Blackboard

Add an HTML content item and paste:

```html
<iframe src="https://YOUR-USERNAME.github.io/sma-quiz/"
        width="100%" height="800" style="border:0;"
        title="SMA Practice Quiz"></iframe>
```

If your Blackboard instance strips iframes, use a **Web Link** pointing at the live URL instead.

## Editing the questions

Everything lives in a single file, `index.html`. The questions are a JavaScript array (`QUESTIONS`) near the bottom — each entry has the question text, four options, the index of the correct answer (`a`, zero-based), and an explanation (`e`). Edit, commit, and the live site updates within a minute.

## About

Built as a teaching demonstration for a session on AI in accounting education at Aston University — an example of using AI to lower the cost of producing good formative assessment. No frameworks, no build step, no dependencies: one HTML file served by GitHub Pages.
