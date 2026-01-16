🎯 KEZDŐ KÖZÖS PROJEKT:
CLI Jegyzetkezelő (Python + GitHub)

📌 Mit tudjon?
Egy parancssoros program, amiben jegyzeteket lehet:

hozzáadni

kilistázni

törölni

fájlba menteni / betölteni

👉 nincs grafika, nincs web, csak tiszta Python + Git

📁 Kötelező projektstruktúra
notes-app/
 ├─ main.py          # program indítása
 ├─ notes.py         # jegyzetek kezelése
 ├─ storage.py       # fájlkezelés (JSON)
 ├─ README.md

👥 Feladatfelosztás (ÍGY CSINÁLJÁTOK)
🧑‍💻 Te:

notes.py

jegyzet hozzáadás

jegyzet törlés

lista kezelése

🧑‍💻 Haverod:

storage.py

mentés fájlba

betöltés fájlból

🤝 Közös:

main.py

menü

input kezelés

funkciók összekötése

🧠 Funkcióspecifikáció (EZ NAGYON FONTOS)
notes.py
def add_note(notes: list, text: str) -> list:
    """Új jegyzet hozzáadása"""

def delete_note(notes: list, index: int) -> list:
    """Jegyzet törlése index alapján"""

def list_notes(notes: list) -> None:
    """Jegyzetek kilistázása"""

storage.py
def save_notes(notes: list, filename: str = "notes.json") -> None:
    """Jegyzetek mentése fájlba"""

def load_notes(filename: str = "notes.json") -> list:
    """Jegyzetek betöltése fájlból"""

main.py
1. betölti a jegyzeteket
2. menüt megjelenít
3. kezeli a felhasználói inputot
4. meghívja a notes.py / storage.py függvényeit

📋 Elvárt működés (példa)
1 - Jegyzet hozzáadása
2 - Jegyzetek listázása
3 - Jegyzet törlése
4 - Kilépés

Választás: 1
Jegyzet szövege: Bevásárlás

🧪 EXTRA (ha már megy)

üres lista kezelése

hibás index esetén hibaüzenet

automatikus mentés minden változás után

dátum hozzáadása jegyzethez

🧠 GitHub feladatlista (issue-ként)

1️⃣ Projekt struktúra létrehozása
2️⃣ notes.py megírása
3️⃣ storage.py megírása
4️⃣ main.py összerakása
5️⃣ README.md

📌 Mit tanultok ebből?

✔ közös kódolás
✔ moduláris gondolkodás
✔ Git branch + PR
✔ alap Python best practice

Ez tökéletes első közös repo.
