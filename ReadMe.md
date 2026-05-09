# Prema Sanskrit App — The Living Seed

> **Boiled eggs never hatch.**  
> ゆで卵は決して孵化しない。

We are not here to re-cook the result.  
We are here to plant the **Living Seed**: Sanskrit.

## Overview

This project is a linguistic entry gate for **Prema OS: Sanskrit-Based Ethical Language Architecture**.

It is not intended as a replacement for orthodox Sanskrit philology or traditional religious practice. Rather, it is an applied experiment that selects a limited set of Sanskrit-derived ethical words and reorganizes them as an **ethical vocabulary** for education, reflection, and AI ethics.

The first public implementation of this idea is the **8-Word Cube App**, a small browser-based tool that helps users select meaningful words, form ethical pairs, and carry those words into a deeper dialogue with NotebookLM.

This repository is intended as the first public doorway to that broader project.

## Why Sanskrit?

Sanskrit is not used here as an exotic ornament.

In Japan, many Buddhist concepts rooted in Sanskrit entered through translated scriptures and became part of Japanese thought, literature, ritual, and vocabulary over many centuries. This project revisits some of those words in a form that modern learners can approach through Japanese, English, and simple interactive study.

At the same time, this project clearly distinguishes itself from traditional Sanskrit scholarship. The vocabulary design used here is an applied ethical framework, not a claim to represent Sanskrit in its full historical, grammatical, or liturgical depth.

## Five Guides

This project is designed around five symbolic guides:

- Ganesha
- Hanuman
- Prince Shōtoku
- Murasaki Shikibu
- Kūkai

At the current stage of implementation, the app primarily works with **Ganesha** and **Hanuman**.

The two Indian figures represent wisdom, courage, and movement through difficulty. The three Japanese figures represent future expansion: how Sanskrit-derived Buddhist culture was received, transformed, and expressed in Japanese politics, literature, and religious thought.

## How the App Works

The first implementation is the **8-Word Cube App**.

Basic flow:

1. Start from a base set of 27 core words related to truth, goodness, and beauty.
2. Choose 4 words that feel important to you right now.
3. For each of the 4 words, select 1 opposite or complementary word from 3 candidates.
4. This produces 8 words in total, arranged as 4 paired axes.
5. Copy the resulting 8-word set and bring it into NotebookLM together with a diary entry or reflective note.

In practice, the user encounters up to 39 words in the process: 27 base words plus 12 candidate opposite/complementary words, with some overlap.

## NotebookLM Workflow

The HTML app and NotebookLM play different roles.

- The HTML app is the lightweight front door.
- NotebookLM is the deeper interpretive layer.
- The selected 8 words become a structured prompt for reflection.
- In the current setup, Ganesha and Hanuman respond as symbolic guide voices rather than as a generic assistant.

This structure allows a simple browser-based interface to open into a deeper narrative and ethical dialogue without requiring a complex installation.

## Mathematical & Linguistic Foundation

This project is part of a broader conceptual framework within Prema OS.

Key terms include:

- **Prema⁰**: a zero-point field of love
- **DEGF**: Deterministic Ethical Geometric Frame
- **EOL 70**: a library of core ethical Sanskrit roots
- **8-Word Cube**: the first practical interface for reflective selection and alignment

These ideas are not presented here as final doctrine, but as working concepts for educational, ethical, and language-based experimentation.

## Project Structure

```text
prema-sanskrit-app/
├── README.md
├── LICENSE
├── .gitignore
├── docs/
│   ├── index.html
│   ├── style.css
│   ├── app.js
│   ├── .nojekyll
│   ├── data/
│   │   ├── words-27.json
│   │   ├── words-70.json
│   │   ├── guides-ja.json
│   │   └── notebooklm-prompts-ja.md
│   ├── app-8words/
│   │   ├── index.html
│   │   ├── style.css
│   │   ├── app.js
│   │   └── data/
│   ├── app-mandala/
│   │   ├── index.html
│   │   ├── style.css
│   │   ├── app.js
│   │   └── data/
│   ├── assets/
│   └── references/
└── archive/
```

The repository is intended to include two HTML apps:

1. **8-Word Cube App** — a selection tool for choosing 8 words and carrying them into NotebookLM.
2. **Mandala / Flashcard App** — a second app for learning a wider set of 37 words.

## GitHub Pages

This project is intended to be published with GitHub Pages.

Recommended publishing source:

- Branch: `main`
- Folder: `/docs`

GitHub Pages will use `docs/index.html` as the public entry page.

## License

License to be decided.

Until a proper license is added, all rights remain reserved by default.
