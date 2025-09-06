# Data Lifecycle – Stacked Cards (Power BI HTML)

A no-JS, accessible stacked-card walkthrough of the data lifecycle, designed for embedding in Power BI’s HTML visual.

## Files
- `index.html` – the standalone HTML (copy from your DAX string but remove the outer quotes).
- `assets/images/` – optional local images.
- `LICENSE` – MIT recommended.

## Use in Power BI
1. Create a Text/HTML measure named `Data_Lifecycle_HTML` with the provided string.
2. Add an HTML Content visual and bind it to the measure.
3. Adjust stack spacing by editing `translateY`/`scale` in the CSS.
4. Replace image URLs with org-approved assets if needed.

## Accessibility
- Radio inputs remain screen-reader accessible.
- Labels act as “next” buttons; final card loops to the first.

## Customisation
- Edit header colours in the “Header Colour Accents” section.
- Tweak heights via `section{ height: 520px; }`.
