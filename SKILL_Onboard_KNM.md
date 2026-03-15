# Skill: KNM Folder Onboarding

This file contains instructions for Gemini CLI to add new folders to the KNM course.

## Workflow

When a new folder with study material is provided (e.g., `8. Politiek en rechtspraak`), follow these steps:

1.  **Analyze:** Read all text files and analyze text contents in images (OCR) in the new folder. Ensure **100% coverage** of all information found in these sources. Do not summarize; include all relevant details, stories, and examples.
2.  **Identify Theme Number:** Extract the number from the beginning of the folder name (e.g., if the folder is `8. Politiek en rechtspraak`, the theme number is **8**). This number MUST be used in the header and in the `README.md` update.
3.  **Translate:** Generate an English translation that is not just literal but captures the context of the course material.
4.  **Identify Keywords:** Select important KNM terms (legal, cultural, or administrative) and mark them in **bold** in both languages.
5.  **Create Markdown Page (Mobile-Friendly):**
    *   **Header:** Use the format `# Thema [Number]: [Name] ([Translation])`.
    *   **Introduction:** Start with a short paragraph in both languages introducing the theme. The English part should be in a `<small>` tag.
    *   **Topic-Based Sections:** For each sub-topic, use a stacked layout (Dutch followed by English).
    *   **English Blocks:** Use `<small>` tags for all English blocks to keep them subtle and less prominent than the Dutch text.
    *   **Glossary:** Create a separate section at the end for "Belangrijke Begrippen" (Important Terms) using a list or a simple table that doesn't overflow on small screens.
6.  **Update Overview:** Add the new theme to `README.md` using the correct theme number, a short description, and a link to the new page. Keep the list in order (1, 2, 3...).

## Format (Mobile-Friendly)

Use the following structure for the new page:

```markdown
# Thema [Nummer]: [Naam] (Theme [Number]: [Name])

[Short introductory paragraph in Dutch.]
<small>([Short introductory paragraph in English.])</small>

## [Sub-topic Name]

### 🇳🇱 Nederlands
**[Sub-topic Title]**

[Full paragraph in Dutch explaining the topic. Include all details from the source text. Use **bold** for key terms.]

### 🇬🇧 English
<small>
**[Sub-topic Title]**

[Full paragraph in English. Ensure the translation matches the Dutch paragraph exactly and maintains the **bold** key terms.]
</small>

---

## Belangrijke Begrippen (Important Terms)

- **[Term]** ([Translation]): [Definition in Dutch] / <small>[Definition in English].</small>
```

