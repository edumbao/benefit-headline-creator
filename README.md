# Benefit Headline Creator

A small public copywriting tool that helps turn vague website headlines into clearer action-benefit headlines.

**Live tool:** https://edumbao.github.io/benefit-headline-creator/

**Repository:** https://github.com/edumbao/benefit-headline-creator

## Project status

**Working learning project**

The tool is public and functional. I built it as a practical copywriting experiment, not as a full landing-page optimization platform.

The current version focuses on one specific problem: helping someone move from a vague headline to clearer headline options that explain what the visitor can do, what they get, and why the offer matters.

## Why I built it

In content and copywriting work, I often see headlines that sound polished but do not explain the offer clearly enough.

I wanted a simple way to work through a more direct structure:

- What does the visitor do?
- What benefit do they get?
- What proof, timeframe, or specificity can strengthen the claim?
- What friction can be removed?
- What tone fits the offer?

I built this tool to turn that thinking process into a repeatable browser workflow.

It also gave me a small technical project where I could practice HTML, CSS, JavaScript, GitHub Pages, input handling, and documentation while working on a problem connected to copywriting.

## What the tool does

The Benefit Headline Creator asks for:

1. **Current headline**
2. **Target audience**
3. **Product or offer**
4. **Visitor action**
5. **Visitor benefit**
6. **Specific proof, number, or timeframe**
7. **Friction removed**
8. **Tone**

The tool then generates eight headline options based on those inputs.

It also includes:

- an action-benefit summary
- a quick review checklist
- a tone note
- a sample-data loader
- copy-to-clipboard
- clear/reset controls
- sharing and embed options

## How it works

```text
Current headline
      ↓
Audience
      ↓
Offer
      ↓
Action
      ↓
Benefit
      ↓
Proof / timeframe
      ↓
Friction removed
      ↓
Tone
      ↓
Headline options
```

The current version runs entirely in the browser and does not require an account or backend.

## Tech stack

- HTML
- CSS
- Vanilla JavaScript
- GitHub Pages

The project is intentionally lightweight. I did not use a framework, API, database, or server because the current workflow does not require one.

## Current features

- Current-headline input
- Audience input
- Product/offer input
- Action input
- Benefit input
- Proof/timeframe input
- Friction-removal input
- Tone selector
- Eight generated headline variations
- Quick review checklist
- Load-example button
- Copy output
- Clear/reset
- Share and embed options
- Responsive layout

## What it does not do

The current version does **not**:

- evaluate conversion performance
- run A/B tests
- analyze live landing pages
- score headlines with an AI model
- validate product claims
- replace copy review
- guarantee that a generated headline will perform better

I think those boundaries matter. This is a structured headline-writing aid, not a conversion-optimization platform.

## Run it locally

Clone the repository:

```bash
git clone https://github.com/edumbao/benefit-headline-creator.git
```

Move into the project:

```bash
cd benefit-headline-creator
```

Because the project is a static site, you can open `index.html` directly in a browser or serve it locally.

For example, with Python:

```bash
python -m http.server 8000
```

Then open:

```text
http://localhost:8000/
```

## Project structure

```text
benefit-headline-creator/
├── index.html
└── README.md
```

The application currently lives in a single `index.html` file, including the page structure, styles, and JavaScript.

## What worked

A few parts of the project worked well for what I wanted to test:

- The tool turns a repeated copywriting exercise into a simple browser workflow.
- Requiring an action and a benefit keeps the generated options focused on something concrete.
- The tool can clean up some common input phrasing before building the headline variations.
- Tone options create slightly different framing without requiring a large AI system.
- The example loader makes the workflow easier to understand without reading instructions first.
- The project works without a backend or account system.

## What confused me or still needs work

The tool is functional, but there are still parts I want to improve.

### Feedback messages

The current version still uses browser alerts for validation and copy confirmation. I want to replace those with inline feedback so the experience feels cleaner.

### Project documentation

The repository originally had no README. Improving the documentation is part of the project because I want the repository to explain the problem, scope, setup, limitations, and lessons, not only show the code.

### Sharing interface

The current sharing interface includes more options than the core tool probably needs. I may reduce it to a smaller set of useful actions.

### Visual consistency

The tool started with a more generic SaaS-style design. I am gradually aligning my public tools with the visual identity of my personal portfolio so they feel like part of the same body of work.

## What I learned

This project reinforced a few things for me:

- A small tool can come directly from a repeated writing problem.
- Input cleanup matters when generated text depends on user phrasing.
- Clear constraints can be more useful than adding more features.
- A static HTML/CSS/JavaScript project can be enough for a focused workflow.
- Documentation is part of the project, not something separate from the build.
- A public tool should make its limitations clear instead of presenting itself as more capable than it is.

## How this connects to my content and copywriting work

The project came from a practical writing question:

> Can a first-time visitor understand what this company does and what they get from the headline alone?

The workflow makes me clarify:

- the visitor action
- the benefit
- the proof
- the friction removed
- the tone

Turning that process into a small tool made the exercise easier to repeat and gave me hands-on practice with front-end code and technical documentation.

## What I want to try next

The next improvements I am considering are:

1. Replace browser alerts with inline feedback.
2. Align the design with my personal portfolio.
3. Add dark and light theme support.
4. Simplify the sharing interface if the current options are not useful.
5. Keep the README and build notes updated as the tool changes.

I do not want to add features just to make the project look larger. The goal is to keep it focused, useful, and understandable.

## About this project

I am a content and SEO professional learning more about GitHub, APIs, automation, and coding by building small tools around problems I encounter in my work.

This repository is part of that learning process.

More projects and build notes: https://edumbao.com/lab/
