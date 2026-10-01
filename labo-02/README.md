# Labo 2 - reflecties

Naam: Ethan Allains

## 2. Selectors lezen

Welke elementen raakt elke selector? Eén zin per selector.

- a. `header nav ul li a`: alle a-elementen die ergens binnen een li staan, die binnen een ul staat, binnen een nav, binnen een header. De spaties betekenen "ergens daarbinnen", op eender welke diepte.
- b. `article > p`: alleen de p-elementen die een rechtstreeks kind zijn van een article. 
- c. `.uren li:nth-child(3)`: een li binnen een element met class uren, maar alleen als die li het derde kind van zijn ouder is.
- d. `h2 ~ p`: alle p-elementen die ná een h2 komen en dezelfde ouder hebben. Dat is dus niet alleen de eerste p erna (dat zou h2 + p zijn), maar alle volgende.
- e. `.rassen li:first-child`: de li die het eerste kind van zijn ouder is, binnen een element met class rassen. 

## 3. Voorspel, dan kijk

Vul de eerste twee kolommen in vóór je de pagina opent. Trede: herkomst, specificiteit, volgorde of overerving (of iets anders, benoem het).

| vraag | mijn voorspelling (kleur) | beslissende trede | uitkomst in de browser | juist? |
|---|---|---|---|---|
| 1 |groen |specificiteit |groen |juist |
| 2 | blauw|volgorde |blauw |juist |
| 3 |rood |specificiteit |rood |juist |
| 4 | rood| specificiteit|rood |juist |
| 5 | blauw|specificiteit |blauw |juist |
| 6 | blauw|specificiteit | blauw| juist|
| 7 | rood|overerving |rood |juist |
| 8 | blauw|herkomst |blauw |juist |
| 9 | rood |!important |rood |juist |
| 10 |groen |css fout |groen |juist|

Bij welke vraag zat je fout, en wat was de reden? (Alles juist? Welke vraag duurde het langst, en waarom?)

## 4. De nabouw

- Welke selector koos je voor de links in de navigatie, en waarom geen class?
Ik koos voor nav a, omdat daarmee alleen de links binnen de navigatie geselecteerd worden. Een class is niet nodig, omdat de HTML-structuur al duidelijk genoeg is om deze links specifiek te selecteren.

- Welke regel kostte je het meeste tijd, en wat was uiteindelijk de oorzaak?
De hover- en focusregels voor de verschillende links kostten mij het meeste tijd. De oorzaak was dat de links in de navigatie, main en footer elk een andere opmaak nodig hebben. Daarom moesten ze met aparte selectors zoals nav a, main a en footer a geselecteerd worden.

## 6. Je site

- Welke drie waarden staan in je tokenblok, en waarom die?
- Wat verandert er in je site als je één token wijzigt?

## Thuis: R2.3 (met AI)

Prompt en onbewerkte output staan in `review/`. Minstens vijf bevindingen, elk met een verwijzing naar de sectie of het foutnummer:

1. 
2. 
3. 
4. 
5. 
