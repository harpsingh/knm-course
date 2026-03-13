# Skill: KNM Folder Onboarding

Dit bestand bevat instructies voor Gemini CLI om nieuwe mappen toe te voegen aan de KNM cursus.
(This file contains instructions for Gemini CLI to add new folders to the KNM course.)

## Workflow

Wanneer een nieuwe map met studiemateriaal wordt aangeboden, volg dan deze stappen:
(When a new folder with study material is provided, follow these steps:)

1.  **Analyseren (Analyze):** Lees alle tekstbestanden, .mhtml bestanden en bekijk de afbeeldingen in de nieuwe map.
    (Read all text files, .mhtml files, and view images in the new folder.)
2.  **Vertalen (Translate):** Genereer een Engelse vertaling voor de kernteksten.
    (Generate an English translation for the core texts.)
3.  **Keywords Identificeren (Identify Keywords):** Selecteer belangrijke KNM begrippen en markeer deze **dikgedrukt** in beide talen.
    (Select important KNM terms and mark them in **bold** in both languages.)
4.  **Markdown Pagina Maken (Create Markdown Page):**
    *   Gebruik een zij-aan-zij tabel (Optie A) voor de vergelijking Nederlands/Engels.
    *   (Use a side-by-side table (Option A) for the Dutch/English comparison.)
    *   Maak een aparte sectie voor "Belangrijke Begrippen" (Important Terms).
    *   (Create a separate section for "Important Terms".)
5.  **Overview Bijwerken (Update Overview):** Voeg het nieuwe thema toe aan `Course_Overview.md` met een korte beschrijving en een link naar de nieuwe pagina.
    (Add the new theme to `Course_Overview.md` with a short description and a link to the new page.)

## Formaat (Format)

Gebruik de volgende structuur voor de nieuwe pagina:
(Use the following structure for the new page:)

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
