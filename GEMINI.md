# GEMINI.md - KNM Course Project Overview

## Project Overview
This project is a repository for the **Kennis van de Nederlandse Maatschappij (KNM)** course material, designed to help students prepare for the Dutch integration exam. It features a collection of study themes presented in a dual-language (Dutch/English), mobile-friendly Markdown format.

## Directory Structure
- **Root Directory:** Contains the main navigation (`README.md`), individual theme pages (e.g., `Wonen.md`, `Gezondheid.md`), and the operational skill/SOP (`SKILL_Onboard_KNM.md`).
- **Content/**: Organized by theme number (e.g., `1. Wonen`, `2. Omgaan met anderen`). This directory contains the source materials, including:
  - `.txt` files: Raw text content from the curriculum.
  - `.png` files: Visual materials and infographics (often requiring OCR analysis).

## Key Files
- **README.md**: The landing page and table of contents for the entire course. It tracks the status of available themes and provides links to each study page.
- **SKILL_Onboard_KNM.md**: The **Foundational Mandate** for this project. It defines the exact workflow and formatting standards for adding new content.
- **Thema [Number]: [Name].md**: The finalized study pages (e.g., `Politiek_en_rechtspraak.md`).

## Development Workflow (SOP)
When adding or updating content, strictly follow the rules in `SKILL_Onboard_KNM.md`:

1.  **Analyze Source:** Read all text files and perform OCR on images in the corresponding `Content/` subfolder. Ensure 100% coverage of details, stories, and examples.
2.  **Dual-Language Layout:** Every section must have a Dutch version followed by an English translation.
    - **Dutch (NL):** Primary text.
    - **English (EN):** Secondary text, wrapped in `<small>` tags for a subtle appearance.
3.  **Keywords:** Identify critical KNM terms (legal, cultural, administrative) and mark them in **bold** in both languages.
4.  **Header Format:** Use `# Thema [Number]: [Name] ([Translation])`.
5.  **Glossary:** Every theme page must conclude with a "Belangrijke Begrippen (Important Terms)" section.
6.  **Update Navigation:** Ensure the new theme is added to the `README.md` list in the correct numerical order.

## Standards & Conventions
- **Mobile-First:** Use a stacked layout (Dutch on top of English) to ensure readability on narrow screens.
- **Tone:** Professional yet accessible, suitable for language learners.
- **No Summarization:** The goal is comprehensive coverage of the source material to ensure students don't miss exam-relevant details.
