# Text

Dit is de vaste repository voor alles wat nodig is voor **Text** binnen het KCD-project.

## Vaste keten

Text input → Text Collector → beveiliging/codering → Text Opslag → verwerking → antwoord/output.

## Wat hier onder Text valt

- tekstinput uit chat/API
- Text Collector
- beveiliging, IDs/codes en metadata vóór opslag
- Text Opslag
- normalisatie en verwerking van tekst
- conversation- en session-koppeling
- foutregistratie en feedback voor Text
- retrieval/memory-koppelingen voor goedgekeurde kennis
- koppeling met de text/AI-engine
- checks voor veilige opslag, correcte routing en fallbacks

## Wat deze repo bewaart

- code
- configuratie
- API-key **namen/verwijzingen** die de code nodig heeft

Geen gebruikersdata, chatinhoud of verzamelde data wordt hier opgeslagen.

## Secrets

Echte API keys, tokens en wachtwoorden horen niet in GitHub. De waarden blijven in Railway secrets/environment variables; deze repo bevat alleen de code die naar die variabelen verwijst.
