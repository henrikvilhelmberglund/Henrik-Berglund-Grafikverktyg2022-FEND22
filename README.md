# Inlämningsuppgift Grafikverktyg 2022 Henrik Berglund FEND22

## Om sidan

Detta är ett Figmaprojekt med en design för en desktop-app kallad Midiraku för skapande och redigering av MIDI-filer (.mid) i en browser.

## Dependencies

Appen använder Tailwind CSS för färger och styling. [Hjälp för installation av Tailwind](https://tailwindcss.com/docs/installation)

## Sidor (routes)

### / (index)

/ är indexrouten med logo, välkomsttext samt en knapp för att gå vidare till /editorrouten.

### /editor

/editor är huvudsidan för appen där man skapar MIDI-filer genom att placera ut noter i en så kallad piano roll.

### /play

/play är en sida där man kan spela ett virtuellt piano med olika instrument.

### /help

/help är en sida som förklarar hur man använder appen och dess funktionalitet.

## Färger 

Sidan använder Tailwind CSS för färger. Därför finns 10 nyanser per färg i Colors and typography-sidan i Figma för att de färgerna finns ändå inkluderade i Tailwind ändå och det blir enklare att iterera i designen när man har fler alternativ i Figma.

Färgtema ändras i /editor-routen beroende på aktiv MIDIkanal (aka aktivt instrument).

## Font
Sidan använder en font: [M PLUS1](https://fonts.google.com/specimen/M+PLUS+1)

Det finns bara en font för snabbare laddtid. Den är även variabel så den kan användas för logo, rubrike och brödtext. 

Just denna font används för den har stöd för Japanska (sidan kommer stödja Engelska men även Japanska).

För att vidare spara på filstorlek kommer fonten självhostas med [Fontsource: m-plus-1](https://fontsource.org/fonts/m-plus-1) där man kan importera de font weights som faktiskt används.

## Skuggor

Designen använder vissa skuggor (shadow-1 och shadow-2) för att ge skuggor till vissa element.

## Rasterbilder

Det finns bara en rasterbild som används i designen på indexsidan. Den kommer från [Unsplash](http://unsplash.com) finns i .webp-format för att spara på filstorlek men det finns även en fallback-bild med .jpg-format för browsers som inte stödjer .webp än.

Bilden är även sparad i originalstorlek i /images/original ifall det skulle behövas flera storlekar, annan komprimering eller nya format (t.ex avif) senare.

## Vektorbilder (ikoner)

Det finns vissa ikoner i SVG-format som kommer från [Fontawesome](https://fontawesome.com/download). Anledningen för SVG är att de ger snabbare laddtid för man behöver inte importera en hel fontfil utan kan importera bara de ikoner man använder.

## References

Det finns en mapp /references med screenshots av existerande applikationer som kan användas för inspiration. Dessa bilder i sig kommer inte användas i designen men kan hjälpa till för att skapa en slutgiltig design.