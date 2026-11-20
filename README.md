# ✏️ Aventuri cu litere

Fișe de limba română pentru copii de 6–8 ani: litere, silabe, cuvinte, propoziții și ghicitori. Se pot rezolva direct pe ecran (cu verificare automată) sau se pot tipări pe A4.

## Ce conține

- **Litera fugită** – cuvinte cu o literă lipsă (două la nivelul Greu); albinuța zboară spre floare la fiecare cuvânt corect.
- **Trenul silabelor** – copilul numără silabele; la răspunsul bun apare trenul cu cuvântul despărțit în silabe.
- **Literele amestecate** – literele unui cuvânt trebuie puse în ordinea corectă.
- **Propoziții încurcate** – cuvintele se ating în ordine ca să formeze propoziția (cu literă mare la început și punct la final).
- **Ghicitorile bufniței** – ghicitori scurte, cu câte o căsuță pentru fiecare literă a răspunsului.

## Funcții

- 🔄 **Fișă nouă**: generează alte cuvinte pentru o fișă sau pentru toate.
- Nivel de dificultate: Ușor, Mediu sau Greu (cuvinte mai lungi, mai multe silabe, propoziții mai lungi, mai puține indicii).
- 🔤 Butoane pentru diacritice (Ă, Â, Î, Ș, Ț), utile pe tabletă și telefon.
- ✅ Verificare automată și stele pentru fiecare fișă rezolvată; dacă lipsesc doar diacriticele, copilul primește un indiciu.
- 🖨️ Tipărire pe A4 (o fișă sau toate), cu loc pentru nume și dată și căsuțe goale.
- Progresul se păstrează în browser (localStorage), separat de fișele de matematică.

Cuvintele, despărțirea în silabe, propozițiile și ghicitorile sunt scrise în cod, iar răspunsurile copilului se verifică automat față de ele.

## Publicare pe GitHub Pages

1. Urcă `index.html` și `README.md` într-un repository.
2. **Settings → Pages → Deploy from a branch**, alege `main` și `/ (root)`.
3. Site-ul va fi la `https://<utilizator>.github.io/<repository>/`.

Dacă vrei să o ții în același repository cu fișele de matematică, pune cele două fișiere într-un folder `romana/`; pagina va fi la `https://<utilizator>.github.io/<repository>/romana/`.

Totul este într-un singur fișier HTML, fără server și fără instalare.
