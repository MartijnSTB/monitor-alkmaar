# Gemeentemonitor Alkmaar

Volgt automatisch wat de gemeente Alkmaar publiceert, besluit en wijzigt, en wat de media erover schrijven.
Dashboard: https://martijnstb.github.io/monitor-alkmaar/

Bronnen:
- Officiële bekendmakingen (KOOP): vergunningen, verordeningen, besluiten uit het Gemeenteblad
- College: B&W-agenda's en openbare besluitenlijsten (alkmaar.bestuurlijkeinformatie.nl)
- Raad: raadsstukken, moties en vergaderingen via Open Raadsinformatie. Let op: ORI loopt soms
  maanden achter. Het raadsinformatiesysteem van de gemeente zelf heeft een beveiligingscontrole
  en wordt daarom niet rechtstreeks gevolgd.
- Nieuws van alkmaar.nl
- In de media: Google Nieuws op Alkmaar en de kernen (AZ-voetbal wordt eruit gefilterd)

De monitor draait elke 30 minuten (GitHub Actions, aangezet via cron-job.org).
Trefwoorden voor directe pushmeldingen staan in `trefwoorden.txt`.
