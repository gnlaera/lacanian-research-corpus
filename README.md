# Lacanian Research Corpus

A structured, source-grounded Markdown corpus for research on Jacques Lacan, Freud, and later Lacanian thought, organized for retrieval and analysis in Gemini Notebook.

This repository is the ten-volume Notebook ingestion edition of a larger 46-file archival corpus. It is designed to make the corpus available as ten stable GitHub Pages web sources while preserving the internal source boundaries and corpus IDs 00–45.

It is a research corpus, not an official or authorized edition of Lacan, Freud, or any later author. It does not claim textual-critical perfection or official completeness.

## Corpus structure

Primary Lacan material is concentrated in the Écrits component of M01 and the seminar volumes M02–M06. Freud foundations are in M09. Later Lacanian interpreters are in M07. Companion and clinical material is in M08. M10 contains cross-source synthesis, while M01 also provides the reference, chronology, and terminology apparatus used to navigate the corpus.

| Volume | Contents | Recommended Gemini Notebook source |
|---|---|---|
| M01 | Reference, chronology, terms, and Écrits | [https://gnlaera.github.io/lacanian-research-corpus/M01_REFERENCE_CHRONOLOGY_TERMS_ECRITS/](https://gnlaera.github.io/lacanian-research-corpus/M01_REFERENCE_CHRONOLOGY_TERMS_ECRITS/) |
| M02 | Seminars IV–VI | [https://gnlaera.github.io/lacanian-research-corpus/M02_LACAN_SEMINARS_IV_TO_VI/](https://gnlaera.github.io/lacanian-research-corpus/M02_LACAN_SEMINARS_IV_TO_VI/) |
| M03 | Seminar VII | [https://gnlaera.github.io/lacanian-research-corpus/M03_LACAN_SEMINAR_VII_ETHICS/](https://gnlaera.github.io/lacanian-research-corpus/M03_LACAN_SEMINAR_VII_ETHICS/) |
| M04 | Seminars VIII–IX | [https://gnlaera.github.io/lacanian-research-corpus/M04_LACAN_SEMINARS_VIII_TO_IX/](https://gnlaera.github.io/lacanian-research-corpus/M04_LACAN_SEMINARS_VIII_TO_IX/) |
| M05 | Seminars X–XI | [https://gnlaera.github.io/lacanian-research-corpus/M05_LACAN_SEMINARS_X_TO_XI/](https://gnlaera.github.io/lacanian-research-corpus/M05_LACAN_SEMINARS_X_TO_XI/) |
| M06 | Late Lacan: XVI, XVII, XX, XXIII | [https://gnlaera.github.io/lacanian-research-corpus/M06_LATE_LACAN_XVI_XVII_XX_XXIII/](https://gnlaera.github.io/lacanian-research-corpus/M06_LATE_LACAN_XVI_XVII_XX_XXIII/) |
| M07 | Major interpreters | [https://gnlaera.github.io/lacanian-research-corpus/M07_MAJOR_INTERPRETERS/](https://gnlaera.github.io/lacanian-research-corpus/M07_MAJOR_INTERPRETERS/) |
| M08 | Companions and clinical material | [https://gnlaera.github.io/lacanian-research-corpus/M08_COMPANIONS_AND_CLINICAL/](https://gnlaera.github.io/lacanian-research-corpus/M08_COMPANIONS_AND_CLINICAL/) |
| M09 | Freud foundations | [https://gnlaera.github.io/lacanian-research-corpus/M09_FREUD_FOUNDATIONS/](https://gnlaera.github.io/lacanian-research-corpus/M09_FREUD_FOUNDATIONS/) |
| M10 | Cross-source synthesis | [https://gnlaera.github.io/lacanian-research-corpus/M10_CROSS_SOURCE_SYNTHESIS/](https://gnlaera.github.io/lacanian-research-corpus/M10_CROSS_SOURCE_SYNTHESIS/) |

The rendered GitHub Pages versions above are the recommended inputs for Gemini Notebook. The original archival corpus IDs 00–45 remain embedded inside the masters and should be used for internal navigation and provenance.

## Provenance and method

The masters preserve source boundaries, chronology, edition and translation distinctions, formal notation, and uncertainty markers from the archival corpus. Translation variants are not silently harmonized. Where the archival corpus marks uncertain extraction, symbols, formulas, diagrams, or source gaps, those markers remain part of the ingestion edition.

GitHub Pages safety is handled structurally rather than by rewriting corpus notation. Each master has a stable permalink and its complete substantive Markdown body is enclosed in a Jekyll/Liquid raw block after front matter. Liquid therefore emits the body literally before the Markdown renderer processes it. This protects notation such as `{{S1}, {S1, S2}}` while preserving normal Markdown rendering.

## Create the Gemini Notebook

1. Create a new Gemini Notebook.
2. Add the ten GitHub Pages URLs in the M01–M10 table above as web sources.
3. Wait until all ten sources have been ingested.
4. Open [`GEMINI_NOTEBOOK_FIRST_CHAT_PROMPT.md`](GEMINI_NOTEBOOK_FIRST_CHAT_PROMPT.md), copy its contents, and paste them into the Notebook chat.
5. Use the embedded corpus IDs 00–45 when tracing claims back to the archival source structure.

For deployment and integrity checks, see [`GITHUB_PAGES_QA.md`](GITHUB_PAGES_QA.md).
