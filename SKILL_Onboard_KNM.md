# Skill: KNM Folder Onboarding

This file contains instructions for Gemini CLI to add new folders to the KNM course.

## Workflow

When a new folder with study material is provided (e.g., `8. Politiek en rechtspraak`), follow these steps:

1.  **Analyze:** Read all text files and analyze text contents in images (OCR) in the new folder. Ensure **100% coverage** of all information found in these sources. Do not summarize; include all relevant details, stories, and examples.
2.  **Identify Theme Number:** Extract the number from the beginning of the folder name (e.g., if the folder is `8. Politiek en rechtspraak`, the theme number is **8**). This number MUST be used in the header and in the `Course_Overview.md` update.
3.  **Translate:** Generate an English translation that is not just literal but captures the context of the course material.
4.  **Identify Keywords:** Select important KNM terms (legal, cultural, or administrative) and mark them in **bold** in both languages.
5.  **Create Markdown Page (Mobile-Friendly):**
    *   **Header:** Use the format `# Thema [Number]: [Name] ([Translation])`.
    *   **Introduction:** Start with a short paragraph in both languages introducing the theme.
    *   **Topic-Based Sections:** For each sub-topic, use a stacked layout (Dutch followed by English) to ensure readability on mobile devices.
    *   **Glossary:** Create a separate section at the end for "Belangrijke Begrippen" (Important Terms) using a list or a simple table that doesn't overflow on small screens.
6.  **Update Overview:** Add the new theme to `Course_Overview.md` using the correct theme number, a short description, and a link to the new page.

## Format (Mobile-Friendly)

Use the following structure for the new page:

```markdown
# Thema [Nummer]: [Naam] (Theme [Number]: [Name])

[Short introductory paragraph in Dutch.]
([Short introductory paragraph in English.])

## [Sub-topic Name]

### 🇳🇱 Nederlands
**[Sub-topic Title]**

[Full paragraph in Dutch explaining the topic. Include all details from the source text. Use **bold** for key terms.]

### 🇬🇧 English
**[Sub-topic Title]**

[Full paragraph in English. Ensure the translation matches the Dutch paragraph exactly and maintains the **bold** key terms.]

---

## Belangrijke Begrippen (Important Terms)

- **[Term]** ([Translation]): [Definition in Dutch] / [Definition in English].
```

