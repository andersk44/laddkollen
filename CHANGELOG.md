# Ändringslogg

Alla viktiga ändringar i Laddkollen dokumenteras här.
Formatet följer [Keep a Changelog](https://keepachangelog.com/sv/1.1.0/)
och versionerna följer [Semantisk versionering](https://semver.org/lang/sv/).

## [1.3.0] – 2026-11-21
### Tillagt
- Laddkollen kan ta emot värden i länken: `?soc=80&target=100&battery=74&power=11`.
  Home Assistant kan då öppna Laddkollen med bilens aktuella laddnivå redan ifylld.
- Kort rad som visar att laddnivån kommer från bilen via Home Assistant.
- Önskad laddnivå och laddeffekt som saknas i listorna läggs till automatiskt när de kommer via länken.

## [1.2.2] – 2026-11-20
### Rättat
- Ikonen: bilen pekar nu åt höger så att det verkligen är höger sida som syns, med laddsladden på höger bakskärm.

## [1.2.1] – 2026-11-20
### Ändrat
- Ikonen: bilen visas från höger sida och laddsladden sitter på höger bakskärm, som på en Ioniq 5.

## [1.2.0] – 2026-11-20
### Tillagt
- Egen app-ikon på temat "Jag gör det med sladd": en elbil som sladdar med laddsladden som sladdmärke.
- Webbappsmanifest, så att Laddkollen kan installeras på hemskärmen och öppnas som en egen app utan adressfält.
- Färska priser hämtas automatiskt när appen öppnas igen.

## [1.1.0] – 2026-11-19
### Tillagt
- Informationsruta med klockslag och kr/kWh vid tryck på staplarna i diagrammet (fungerar i mobil och på dator).
- Versionsnummer längst ner på sidan, med länk till denna ändringslogg.

## [1.0.0] – 2026-11-19
### Tillagt
- Första publicerade versionen på GitHub Pages.
- Billigaste laddstart, kostnad vid vald start, kostnad vid start nu, besparing genom att vänta och möjlig besparing totalt.
- 48-timmarsdiagram över laddpriset med billigaste laddperioden markerad.
- Spotpriser för SE3 från Elpriset just nu.se, med val mellan tim- och kvartspriser.
- Inställningar sparas lokalt i användarens egen mobil.

### Ändrat
- Batteristorlek och laddeffekt flyttade sist på sidan.
- Kostnad vid billigaste start visas i fetstil.
