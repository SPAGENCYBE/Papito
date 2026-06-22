Papito Firebase definitief

Deze versie gebruikt Firebase voor online berichten en foto-uploads.

Upload:
1. Pak deze ZIP uit.
2. Vervang alle bestanden in je GitHub repository Papito.
3. Commit + push.
4. Open https://spagencybe.github.io/Papito/

Admin:
https://spagencybe.github.io/Papito/?admin=1
Code: papi1948

Belangrijk:
Zet in Firebase regels:
- Firestore: zie firestore.rules.txt
- Storage: zie storage.rules.txt

Functies:
- bezoekers plaatsen tekst + foto
- bericht verschijnt pas na goedkeuring
- admin kan goedkeuren/verwijderen
- admin kan foto downloaden
- backup downloaden
- fotopagina blijft werken
- livestream NL/ES blijft werken



EmailJS toegevoegd:
- Service ID: service_x1wh7b8
- Template ID: template_a1becoi
- Public Key: GZ26ksQVkIaUV3FMg

Bij elke nieuwe herinnering probeert de website automatisch een mail te sturen via EmailJS.
Template-velden:
- {{from_name}}
- {{relation}}
- {{message}}
- {{language}}
- {{date}}
- {{photo_url}}
