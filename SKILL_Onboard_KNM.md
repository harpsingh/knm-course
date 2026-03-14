# Skill: KNM Folder Onboarding

This file contains instructions for Gemini CLI to add new folders to the KNM course.

## Workflow

When a new folder with study material is provided, follow these steps:

1.  **Analyze:** Read all text files and analyze text contents in images (OCR) in the new folder.
2.  **Translate:** Generate an English translation that is not just literal but captures the context of the course material.
3.  **Identify Keywords:** Select important KNM terms (legal, cultural, or administrative) and mark them in **bold** in both languages.
4.  **Create Markdown Page:**
    *   **Introduction:** Start with a short paragraph in both languages introducing the theme.
    *   **Topic-Based Paragraphs:** For each sub-topic, write a cohesive paragraph (4-6 sentences) that explains the concept in detail.
    *   **Side-by-Side Comparison:** Use a side-by-side layout (tables are acceptable if they contain full paragraphs) to allow for easy language comparison.
    *   **Glossary:** Create a separate section at the end for "Belangrijke Begrippen" (Important Terms) with clear definitions.
5.  **Update Overview:** Add the new theme to `Course_Overview.md` with a short description and a link to the new page.

## Format

Use the following structure for the new page:

```markdown
# Thema [Nummer]: [Naam] (Theme [Number]: [Name])

[Short introductory paragraph in Dutch.]
([Short introductory paragraph in English.])

## [Sub-topic Name]

| Nederlands | English |
| :--- | :--- |
| **[Sub-topic Title]**<br><br>[Full paragraph in Dutch explaining the topic. This should feel like a textbook, explaining *why* things are a certain way or *how* a process works. Use **bold** for key terms.] | **[Sub-topic Title]**<br><br>[Full paragraph in English. Ensure the translation matches the Dutch paragraph and maintains the **bold** key terms.] |

## Belangrijke Begrippen (Important Terms)
| Nederlands | English | Definitie / Context |
| :--- | :--- | :--- |
| **Term** | **Translation** | A short explanation of when to use this term or what it specifically means in the KNM context. |
```
