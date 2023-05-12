# Aufgabe 5: Bind-Mount zur Weiterentwicklung der API

Hier ist eine einfache NodeJS Web-API, die du schon kennst.
Sie verwendet keine Datenbank, sondern speichert die Daten in einer Liste im Memory ab.
Wir würden gerne diese API weiterentwickeln und testen, ohne bei jeder Änderung den Container neu erstellen zu müssen.

## Lernziele
- Verwendung von Bind-Mount zur automatischen Synchronisation des Sourcecode zwichen Lapi und Container.
- Synchronisation von Unterverzeichnissen (node_modules) unterbinden.
- Verwendung von nodemon um Änderungen sofort aktiv zu machen.

## Aufgabe
- Erstelle ein Dockerfile für diese Applikation (Der Command von CMD ändert sich zu npm run dev).
- Nutze dabei die Eigenschaft von Docker Layers zu cachen, um nicht bei jeder Änderung im Code die Installation von den Node-Modulen zu wiederholen.
- Erstelle ein Bind-Mount um den Sourcecode automatisch zu sychronisieren.
- Lade das fertige Image wiederum auf Docker-Hub hoch.
- Wie lautet der Docker-Command mit dem ich dein Image auf meinem Rechner laufen lassen kann


### Antwort
