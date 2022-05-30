Om html en pdfs te kunnen bouwen: 

1. Installeer asciidoctor -> https://asciidoctor.org
2. Ga naar de directory waar de adoc files zijn opgeslagen
3. Genereer de indexpagina met het commando: asciidoctor index.adoc
4. Open de gegenereerde index pagina in dezelfde directory

Met bovenstaande werkwijze zal ook de aanwezige javascript goed werken. 

Om ook pdf's te kunnen genereren moet asciidoctor-pdf nog geinstalleerd worden:
https://asciidoctor.org/docs/asciidoctor-pdf/
Het te runnen commando luiste dan: asciidoctor-pdf index.adoc.
PS: De kleuren in de tekst komen (nog) niet goed door.
