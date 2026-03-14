# Skill: KNM Folder Onboarding

This file contains instructions for Gemini CLI to add new folders to the KNM course.

## Workflow

When a new folder with study material is provided, follow these steps:

1.  **Analyze:** Read all text files and read text contents in images (OCR) in the new folder.
2.  **Translate:** Generate an English translation for the core texts.
3.  **Identify Keywords:** Select important KNM terms and mark them in **bold** in both languages.
4.  **Create Markdown Page:**
    *   Use a side-by-side table (Option A) for the Dutch/English comparison.
    *   Create a separate section for "Important Terms".
5.  **Update Overview:** Add the new theme to `Course_Overview.md` with a short description and a link to the new page.

## Format

Use the following structure for the new page:

```markdown
# Thema [Nummer]: [Naam] (Theme [Number]: [Name])

## Belangrijke Begrippen (Important Terms)
| Nederlands | English |
| :--- | :--- |
| **Term** | **Translation** |

## Informatie (Information)
| Nederlands | English |
| :--- | :--- |
| **Zin in het Nederlands.** | **Sentence in English.** |
```
