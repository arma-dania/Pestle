# PESTLE-værkstedet

Interaktiv læringsside om PESTLE-analysen til Markedsføringsøkonom (AK) på Erhvervsakademi Dania. Lavet af Arnes Uglebureau.

## Indhold

- **Overblik** – de seks faktorer (Politiske, Økonomiske, Sociokulturelle, Teknologiske, Legale, Miljømæssige) med "hvad hører til", spørgsmål, eksempler og typiske forvekslinger. Makromiljø-skiven øverst kan klikkes.
- **Sådan gør du** – seks trin til en god analyse og de typiske fejl.
- **Sortér** – 12 forhold, der skal placeres under den rigtige faktor, med forklaring.
- **Quiz** – 10 spørgsmål om formål, faktorer og sammenhængen med SWOT.
- **Din analyse** – arbejdsark med prioriteringsmatrix (sandsynlighed × betydning), der kan kopieres som tekst. Gemmes kun i den studerendes egen browser (localStorage).

## Brug

Det er én selvstændig `index.html` uden byggetrin. Åbn filen i en browser for at se den lokalt. Siden henter kun skrifttyperne fra Google Fonts.

**Netlify:** Sitet udgives fra grenen `main`. `netlify.toml` kopierer `index.html` til `dist/` og udgiver den mappe, så Netlify skal ikke have andre indstillinger. Opsætning første gang: Netlify → Add new site → Import an existing project → GitHub → `arma-dania/Pestle` → Branch to deploy: `main` → Deploy. Herefter udgives hver push til `main` automatisk.

## Design

Samme udtryk som *Konjunkturvurdering* (`arma-dania/konjunkturvurdering`): én fast lys papirflade (#f7f1e3), navy, bordeaux og guld, Fraunces til overskrifter, Source Serif 4 til brødtekst og JetBrains Mono til små etiketter, firkantede kort, nummereret menulinje, boksen "Efter siden kan du / Det vigtigste på 30 sekunder", øvelsesbokse i creme og Forrige/Næste nederst. De seks faktorer har hver sin fagfarve i samme dæmpede familie som graferne i Konjunkturvurdering.

## Kilder

- IJDR (2025): *How to Create the Best PESTEL Analysis*
- CIPD: *PESTLE analysis* factsheet
- B2B International (2025): *PESTLE analysis*
- Aguilar, F. (1967): *Scanning the Business Environment*
