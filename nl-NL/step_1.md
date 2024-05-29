The starter project has 20 fonts already imported from the Google Fonts library.

**Tip:** If you have used one of the CSS colour palettes included in the starter project, a matching font has already been assigned. You can replace this font if you would like to use a different one.

De meegeleverde lettertypen zijn:

![alt=""](images/font-list.png)

Ga naar `default.css` of de bestandsnaam van het door jou gekozen kleurenpalet (bijvoorbeeld `festival.css`).

Replace the existing `header-font`, `title-font`, and `quote-font` with the name of your chosen font.

## --- code ---

language: html
filename: default.css
line_numbers: false
--------------------------------------------------------

\--body-font: 1rem Verdana, sans-serif;
\--header-font: lighter 3rem "spirax", cursive;
\--title-font: lighter 2rem "spirax", cursive;
\--quote-font: lighter 1.5rem "spirax", cursive;

\--- /code ---

You can add also add your font variables to existing classes or use them when you make your own classes.

## --- code ---

language: html
filename: default.css
line_numbers: false
line_number_start: 1
line_highlights: 3
-------------------------------------------------------

.bigfont {
font-size: 3rem;
font: var(--header-font);
}

\--- /code ---
