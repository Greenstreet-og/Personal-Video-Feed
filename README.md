# Abofeed

Eine einzelne statische Seite, die nur die Videos deiner YouTube-Abos zeigt, streng chronologisch, ohne Empfehlungen.

- Abos per Google-Anmeldung (YouTube Data API v3, nur Lesezugriff), alternativ CSV aus Google Takeout oder einzelne Kanäle.
- Videos laufen im Player von youtube-nocookie.com, als Overlay über dem Feed.
- Alle Daten (Abos, API-Schlüssel, gesehene Videos) bleiben im Browser (localStorage). Im Repo liegt nichts Persönliches.

Läuft über GitHub Pages: https://greenstreet-og.github.io/Personal-Video-Feed/

Die Google-OAuth-Client-ID steht in `index.html`. Sie ist nicht geheim, funktioniert aber nur von den in der Google Cloud eingetragenen JavaScript-Ursprüngen aus.
