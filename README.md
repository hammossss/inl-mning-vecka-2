# inl-mning-vecka-2

Beskriv skillnaden mellan vattenfallsmodellen och agil metodik.
När bör man använda vilken, och varför?

Waterfall 
Plan: Allt bestäms i detalj i början (krav, design, tid, kostnad).
Process: Faser i följd — krav → design → utveckling → test → lansering.
Resultat: Förutsägbart om inget ändras, men lång tid till första version och svårt att ändra vid ny information.

Agile
Plan: Grov plan och prioriterad lista med funktioner.
Process: Utveckla, testa och släpp ofta. Justera efter användarnas feedback.
Resultat: Snabbt ut till användare, lätt att ändra och förbättra, mindre risk att bygga fel saker.

Det bäst att använda Watterfallmodellen för stabila projekt som har stora krav och agile metodik är mer lämplig för dynamiska projekt där förändringar är vanliga.



Vad är ett Git-commit och varför är det viktigt?
Beskriv ett verkligt scenario där Git hjälper dig undvika problem.

En Git-commit är en sparad version av en kod med ett meddelande om vad man har ändrat. Man kan se alla ändringar, man kan gå tillkbaka till en tidigare version om man har gjort något fel eller något har gått snett. Och flera personer kan jobba på en och samma projekt utan att det ska krocka.

Till exempel : Man jobbar med en webbplats och fixar en ny funktion, och efter man har tryckt på commit så uppstår det en bugg, istället för hålla på och leta efter det så kan man gå tillbaka till den senaste fungerande versionen med Git, man fixar buggen och gör ett nytt commit när man är klar, för Git hjälper dig att hantera ändringar och undvika problem.



Vad innebär samarbete med GitHub? Vad är pull requests, branches och merge?

Att flera utvecklare kan jobba på samma projekt enkelt.
PR: gör det möjligt för ett team att diskutera och göra kodändringar innan det blir en del av projektet.
Branches : en kopia av koden för att göra ändringar utan att påverka huvudversionen.
Merge : att kombinera ändringar från en bransh till huvudversionen när PR är godkänd.
Med Github kan utvecklare använda brancches för ändringar, Pr för granskning och merge för att slå samman kod, detta förenklar arbetet.
