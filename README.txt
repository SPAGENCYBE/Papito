Papito - veilige adminversie

BELANGRIJK:
Deze versie gebruikt Firebase Authentication voor de admin.
Alleen ingelogde admin kan goedkeuren, verwijderen en foto's verwijderen/downloaden.

Te doen in Firebase:
1. Authentication > Sign-in method > Email/Password aanzetten.
2. Authentication > Users > Add user:
   e-mail: carlos.van.nieuwenborgh@gmail.com
   wachtwoord: kies zelf een sterk wachtwoord
3. Firestore Rules vervangen door firestore.rules.txt
4. Storage Rules vervangen door storage.rules.txt
5. Websitebestanden uploaden naar GitHub.

Admin:
https://spagencybe.github.io/Papito/?admin=1

Je logt dan in met:
carlos.van.nieuwenborgh@gmail.com
+ je zelf gekozen wachtwoord

Waarom:
In de vorige versie stonden update/delete open in Firebase Rules.
Daardoor kon iemand technisch gezien verwijderen.
Deze versie sluit dat af.


FIX:
Deze versie zet alle Nederlandse teksten ook rechtstreeks in de HTML.
Daardoor verdwijnen titels/teksten niet meer als Firebase of JavaScript even traag laadt of blokkeert.
