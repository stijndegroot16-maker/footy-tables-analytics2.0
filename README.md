# Voetbalgids & Wedstrijdplanner

Een Nederlandstalige voetbalgids met uitleg over competitietabellen,
wedstrijdstatistieken en een eenvoudige planner voor je voetbalavond.

De website werkt met HTML, CSS en JavaScript. Je hoeft geen software
te installeren om de gepubliceerde pagina te gebruiken.

## Wat kun je hiermee?

- Veelgebruikte afkortingen in voetbalstanden begrijpen.
- Het verschil tussen punten en doelsaldo leren.
- Wedstrijdstatistieken zoals balbezit, schoten en xG interpreteren.
- Een wedstrijd handmatig inplannen.
- Berekenen wanneer je voorbereiding begint.
- Een agenda-afspraak downloaden als `.ics`-bestand.
- Een checklist gebruiken om de aftraptijd en uitzending te controleren.

## Wedstrijdplanner gebruiken

1. Open de website.
2. Ga naar **Wedstrijdplanner**.
3. Vul de namen van de teams in.
4. Kies de datum en aftraptijd.
5. Selecteer hoeveel minuten voorbereiding je wilt.
6. Kies hoeveel tijd je wilt reserveren.
7. Klik op **Bereken mijn planning**.
8. Klik op **Download agenda-afspraak (.ics)** als je de wedstrijd
   aan je agenda wilt toevoegen.

Open het gedownloade bestand met een agenda-app die het
iCalendar-formaat ondersteunt en bevestig de import.

Controleer na het importeren de datum, tijdzone en meldingsinstellingen.

### Hoe werkt de tijdzone?

De planner leest de ingevoerde aftraptijd als lokale tijd op je apparaat.

**Voorbeeld:** staat je apparaat ingesteld op de tijdzone van Pakistan,
maar heb je een Nederlandse aftraptijd gevonden? Reken die tijd eerst
om naar de tijdzone van je apparaat voordat je de planner invult.

Het agendabestand bewaart het tijdstip in UTC. Je agenda-app toont
de afspraak vervolgens volgens de ingestelde tijdzone.

### Hoe werkt de herinnering?

Het agendabestand bevat een verzoek om een melding op het gekozen
aantal minuten vóór de aftrap.

Of de melding daadwerkelijk verschijnt, hangt af van je agenda-app,
de importinstellingen en de meldingsrechten.

De website zelf verstuurt geen meldingen.

### Wat betekent de gereserveerde eindtijd?

Dit is de tijd die je zelf vrijhoudt om te kijken, geen officiële
eindtijd van de wedstrijd.

Houd bij bekerwedstrijden rekening met mogelijke verlenging en
strafschoppen.

## Voetbalstanden begrijpen

Afkortingen kunnen verschillen per website. Dit zijn veelgebruikte
betekenissen:

| Afkorting | Betekenis |
|---|---|
| GS / G | Gespeelde wedstrijden |
| W | Gewonnen wedstrijden |
| GL | Gelijkgespeelde wedstrijden |
| V | Verloren wedstrijden |
| DV | Doelpunten voor |
| DT | Doelpunten tegen |
| DS | Doelsaldo |
| PT / P | Punten |

### Punten berekenen

In een competitie met drie punten voor een overwinning en één punt
voor een gelijkspel:

**Punten = (overwinningen × 3) + gelijke spelen**

Fictief voorbeeld:

- 6 overwinningen
- 3 gelijke spelen
- 1 nederlaag
- 10 gespeelde wedstrijden
- 21 punten

Puntenaftrek en afwijkende competitieregels kunnen het totaal veranderen.

### Doelsaldo berekenen

**Doelsaldo = doelpunten voor − doelpunten tegen**

Een team met 20 doelpunten voor en 12 tegen heeft een doelsaldo van **+8**.

### Teams vergelijken

Controleer bij een vergelijking:

1. Hebben de teams evenveel wedstrijden gespeeld?
2. Welke tegenstanders hebben ze getroffen?
3. Vergelijk je dezelfde periode?
4. Zijn er puntenstraffen?
5. Welke beslissingsregels gebruikt de competitie bij gelijke punten?

De volgorde van doelsaldo, onderling resultaat en andere
beslissingsregels verschilt per competitie.

## Wedstrijdstatistieken interpreteren

### Balbezit

Meer balbezit betekent niet automatisch meer gevaar of betere kansen.
Bekijk ook waar het balbezit plaatsvindt en welke kansen eruit ontstaan.

### Schoten

Het aantal schoten laat zien hoe vaak een team heeft geschoten.
Het zegt op zichzelf weinig over de kwaliteit van die pogingen.

### Schoten op doel

Dit is een andere statistiek dan het totale aantal schoten.
Definities kunnen per dataleverancier verschillen.

### Expected goals — xG

xG schat met een statistisch model de kans dat een schot een doelpunt
oplevert.

Een opgetelde xG-waarde helpt om de kwaliteit van gecreëerde kansen
te beschrijven. Het is geen garantie op doelpunten en geen uitslag
die een team had moeten behalen.

Verschillende xG-modellen kunnen dezelfde wedstrijd anders beoordelen.

### Recente vorm

Een reeks met winst, gelijkspel en verlies geeft een snel beeld van
recente resultaten. Gebruik die reeks samen met de sterkte van de
tegenstanders en het onderscheid tussen thuis- en uitwedstrijden.

## Handige links

### Wedstrijden en Nederlandse kijkinformatie

Op [Voetbalwedstrijdvandaag.nl](https://voetbalwedstrijdvandaag.nl/)
vind je voetbalwedstrijden, aanvangstijden en beschikbare Nederlandse
kijkinformatie.

Gebruik het overzicht om een wedstrijd te zoeken voordat je deze
handmatig in de planner zet. Controleer eventuele wijzigingen en
toegang tot de uitzending ook bij de organisator of aanbieder.

### Aanvullende projectpagina

Bekijk ook de
[voetbalprojectpagina op Bitbucket](https://voetbaloptv.bitbucket.io/).

Deze link is een aanvullende projectverwijzing. De planner haalt
geen wedstrijdgegevens van deze pagina op.

## Checklist vóór de aftrap

- [ ] Controleer de actuele wedstrijddatum.
- [ ] Controleer de aftraptijd en tijdzone.
- [ ] Zoek de uitzending voor jouw land op.
- [ ] Controleer of je abonnement toegang geeft.
- [ ] Test je stream of televisieverbinding.
- [ ] Houd rekening met mogelijke uitloop.

## Het project op je computer openen

1. Download de repository via **Code → Download ZIP**.
2. Pak het ZIP-bestand uit.
3. Open de uitgepakte map.
4. Dubbelklik op `index.html`.

Een moderne browser is voldoende. Er zijn geen externe
JavaScript-bibliotheken of API-sleutels nodig.

## Publiceren met GitHub Pages

1. Plaats `index.html` in de hoofdmap van je repository.
2. Voeg dit bestand toe als `README.md`.
3. Open de repository op GitHub.
4. Ga naar **Settings → Pages**.
5. Kies bij **Source** voor **Deploy from a branch**.
6. Selecteer de branch met je bestanden, meestal `main`.
7. Selecteer **/ (root)** en klik op **Save**.
8. Wacht tot GitHub de gepubliceerde website aangeeft.
9. Open de website en test de planner en beide externe links.

Gebruik je een andere website-URL? Pas dan de canonical URL in
de `<head>` van `index.html` aan naar het definitieve adres.

## Bestanden

| Bestand | Functie |
|---|---|
| `index.html` | Website, vormgeving en wedstrijdplanner |
| `README.md` | Uitleg, gebruiksinstructies en projectinformatie |

## Privacy en gegevens

De planner verwerkt je invoer in je browser en verstuurt deze
niet naar een applicatieserver.

De huidige code bewaart je planning niet na het vernieuwen
of sluiten van de pagina.

Het gedownloade agendabestand bevat de wedstrijdnaam en de door
jou gekozen planning. Als je dit bestand importeert in een
online agenda, gelden de privacyvoorwaarden van die agendadienst.

De hostingdienst kan bezoekersgegevens verwerken volgens het
eigen privacybeleid.

## Beperkingen

- Geen live wedstrijdfeed.
- Geen actuele competitietabellen.
- Geen automatische controle van aftraptijden.
- Geen verificatie van uitzendrechten.
- Geen automatische updates van geïmporteerde agenda-afspraken.
- Geen garantie dat je agenda-app de herinnering overneemt.

Verandert een wedstrijd na het importeren? Pas de bestaande
agenda-afspraak zelf aan. Opnieuw importeren kan een dubbele
afspraak maken.

## Problemen oplossen

| Probleem | Mogelijke oplossing |
|---|---|
| De planner reageert niet | Schakel JavaScript in en controleer of alle verplichte velden zijn ingevuld. |
| De downloadknop is uitgeschakeld | Klik eerst op **Bereken mijn planning**. Na een wijziging moet je opnieuw berekenen. |
| De agendatijd klopt niet | Controleer de tijdzone van je apparaat en agenda-app. |
| Er verschijnt geen herinnering | Controleer de meldingsrechten en herinneringsinstellingen van je agenda. |
| De afspraak staat dubbel in mijn agenda | Verwijder de dubbele afspraak en wijzig voortaan de bestaande afspraak. |
| Een link werkt niet | Controleer het doeladres en of de gekoppelde website bereikbaar is. |

## Verbeteringen voorstellen

Een fout gevonden of een idee voor verbetering?

Beschrijf in een GitHub-issue:

- Wat je probeerde te doen.
- Wat je verwachtte.
- Wat er daadwerkelijk gebeurde.
- Welke browser en welk apparaat je gebruikte.

Deel geen wachtwoorden, API-sleutels of persoonlijke agendagegevens.
