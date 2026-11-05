VP3D Konfigurator – Server-Version
==================================
Dateien (alle zusammen in denselben Ordner hochladen):
  index.html  – der Konfigurator. Pro Firma: index.html?firma=KUERZEL
  admin.html  – deine Verwaltung (Firmen, Logins, Abos, Zahlungen)
  vp3d.png    – Logo für die Verwaltung

Datenbank: Supabase-Projekt "VP3D" (EU). Ohne ?firma=... läuft index.html wie bisher (Einstellungen im Browser / settings.json).

Nach dem Hochladen einmalig in Supabase einstellen:
  Authentication -> URL Configuration -> Site URL = https://DEINE-ADRESSE/admin.html
  und dieselbe Adresse unter "Redirect URLs" eintragen.
