# mobapp_2026_MLiveScore
Praćenje lige u sportu(AplikacijaMartin)
Praćenje lige u sportu je Android aplikacija namenjena ljubiteljima domaćeg fudbala za efikasno praćenje rezultata i statistike mečeva. Aplikacija omogućava digitalni pregled odigranih utakmica, detaljnu statistiku po svakom meču, kao i uvid u tabelu prvenstva radi lakšeg praćenja uspeha timova.
Lista funkcionalnosti
Obavezne funkcionalnosti (Must-have):
* Autentifikacija: Početni ekran sa validacijom korisničkog imena i lozinke pre pristupa aplikaciji.
* Filtriranje utakmica: Pregled liste utakmica za specifičan tim izabran putem Spinner-a.
* Detaljna statistika meča: Unos i prikaz specifičnih podataka kao što su posed lopte, broj šuteva, korneri, kartoni i događaji (golovi).
* Tabela prvenstva: Povezivanje timova sa njihovim bodovnim učinkom i prikazom trenutne forme (W/D/L).
* Lokalni prikaz podataka: Korišćenje modela podataka za trajno i stabilno prikazivanje informacija unutar aplikacije.

Tehnologije
* Jezik: Java
* Arhitektura: Slojeviti dizajn (UI -> Adapter -> Model)
* UI Komponente: Material Design 3, EdgeToEdge, RecyclerView sa Custom Adapterima, ProgressBar za vizuelizaciju poseda.
* Mehanizam prenosa: Intent putExtra za asinhroni prenos kompleksnih podataka o utakmicama između ekrana.
Kako se pokreće
1. Kloniranje: Klonirajte repozitorijum sa GitHuba.
2. Android Studio: Otvorite projekat u Android Studiju.
3. Gradle: Sačekajte sinhronizaciju Gradle-a.
4. Instalacija: Pokrenite aplikaciju na emulatoru ili fizičkom uređaju.


Test podaci
* Demo utakmica: Crvena zvezda - Napredak, Rezultat: 2-0, Posed: 40% - 60%.
* Demo tabela: Vojvodina (1. mesto, 15 bodova), Crvena zvezda (2. mesto, 13 bodova).
* Validacija: Pokušajte da kliknete na dugme za login bez unetog korisničkog imena ili lozinke da biste videli upozorenje.
Poznati problemi
* Podaci su trenutno statički definisani unutar koda, planirano je da ova aplikacija pokazuje uživo prenos utakmica svih fudbalskih liga medjutim doslo je do problema sa API-jem i uneti su staticki podaci.
Autor
Ime i prezime: [Martin Mladenović]
Broj indeksa: [1B1/0013/23]
