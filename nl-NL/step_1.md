![Een webpagina met een tekstblok, dan een afbeeldingsblok en dan nog een tekstblok. Elk blok heeft dezelfde hoogte.](images/three-tiles.PNG)

In het codevoorbeeld worden drie tegels gemaakt. De eerste tegel bevat tekst, de tweede tegel is een afbeelding en de derde tegel bevat tekst. De twee tekstblokken zijn van gelijke hoogte met behulp van de `tile` class.

- `xcenter` plaatst de tekst horizontaal in het midden
- `ycenter` plaatst de tekst verticaal in het midden
- `tile` stelt een vaste hoogte in voor de `div`-inhoud

## --- code ---

language: HTML
filename: index.html
line_numbers: true
line_number_start:
line_highlights:
-----------------------------------------------------

```
  <section class="wrap">
    <div class="tertiary xcenter ycenter tile">
      <p>Voeg hier tekst toe.</p>
    </div>
    <img src="placeholder.png" alt="Description of the image.">
    <div class="tertiary xcenter ycenter tile">
      <p>Voeg hier tekst toe.</p>
    </div>
  </section>
```

\--- /code ---

Als je de hoogte van de tekstvakken wilt aanpassen, dan kun je de CSS-code wijzigen.

## --- code ---

language: CSS
filename: style.css
line_numbers: true
line_number_start:
line_highlights:
-----------------------------------------------------

.tile {
height: 9.4rem;
}
\--- /code ---
