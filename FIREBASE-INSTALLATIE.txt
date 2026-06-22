Papito website - definitief herstelde versie

Wat is aangepast:
- Firebase-config opnieuw correct gezet in index.html en fotos.html.
- JavaScript Firestore query-fouten hersteld.
- Admin-login werkt via Firebase Authentication.
- Bezoekers kunnen herinneringen en foto's uploaden, maar niet verwijderen.
- Alleen admin kan goedkeuren, verwijderen, foto's downloaden en backup maken.
- Query's zijn zo aangepast dat er geen samengestelde Firestore-index nodig is.
- Oude lokale/backend-waarschuwing verwijderd.
- Conflict/merge-problemen verwijderd.

Admin openen:
https://spagencybe.github.io/Papito/?admin=1

Admin gebruiker:
carlos.van.nieuwenborgh@gmail.com

Let op:
Het wachtwoord staat niet in de website. Dit beheer je in Firebase > Authentication > Users.

Firebase vereist:
1. Authentication > Sign-in method > Email/Password = Enabled
2. Authentication > Users > gebruiker carlos.van.nieuwenborgh@gmail.com bestaat
3. Firestore Rules vervangen door firestore.rules.txt
4. Storage Rules vervangen door storage.rules.txt
5. GitHub Pages cache verversen via Ctrl + F5 of ?v=4 achter de URL
