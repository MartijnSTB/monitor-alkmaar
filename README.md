# Gemeentemonitor Dijk en Waard

Volgt automatisch wat de gemeente Dijk en Waard publiceert, besluit en wijzigt, en wat de media erover schrijven.
Dashboard: https://martijnstb.github.io/monitor-alkmaar/

Bronnen:
- Officiële bekendmakingen (KOOP): vergunningen, verordeningen, besluiten uit het Gemeenteblad
- Raad: vergaderingen, raadsstukken, moties, amendementen en overzichten uit het iBabs-portaal
  (dijkenwaard.bestuurlijkeinformatie.nl)
- College: besluitenlijsten B&W (uit hetzelfde portaal)
- Nieuws van dijkenwaard.nl
- In de media: Google Nieuws op Dijk en Waard, Langedijk en de woonplaatsen

De monitor draait elke 30 minuten (GitHub Actions, aangezet via cron-job.org).
Trefwoorden voor directe pushmeldingen staan in `trefwoorden.txt`.
