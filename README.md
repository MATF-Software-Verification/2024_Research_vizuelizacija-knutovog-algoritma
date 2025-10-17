# 2024_Research_vizuelizacija-knutovog-algoritma

## 🔹 Informacije o autorima
Projekat su izradili studenti u okviru istraživačkog rada iz oblasti **verifikacije softvera**, sa ciljem da se prikaže i vizualizuje **Knutov algoritam za profajliranje programa**.  
Aplikacija omogućava interaktivno razumevanje algoritma kroz vizuelizaciju grafa kontrolnog toka i zadatke koji proveravaju razumevanje koncepta instrumentalizacije.  

**Autori:**  
- Dimitrije Petrović 1032/2024
- Dimitrije Vranić 1046/2024

## 🔹 Na koji način se projekat može prevesti i pokrenuti

### Zahtevi
Za pokretanje aplikacije potrebno je imati instalirano:  
- **Node.js** (verzija 18 ili novija)  
- **Angular CLI** (verzija 17 ili novija)  
- **Git** (opciono, za preuzimanje repozitorijuma)  

### Instalacija i pokretanje
1. Klonirati repozitorijum:
   ```bash
   git clone https://github.com/dimepetrovic/knuth-profiler.git
   ```
2. Ući u direktorijum projekta:
   ```bash
   cd knuth-profiler
   ```
3. Instalirati sve potrebne zavisnosti:
   ```bash
   npm install
   ```
4. Pokrenuti razvojni server:
   ```bash
   ng serve
   ```
5. Aplikacija će biti dostupna na adresi:  
   [http://localhost:4200](http://localhost:4200)

### Build za produkciju
Za kreiranje optimizovane verzije koja se može hostovati na **GitHub Pages** ili bilo kom drugom serveru:
```bash
ng build --base-href "/knuth-profiler/"
```

Zatim se sadržaj iz `dist/knuth-profiler/browser` direktorijuma može postaviti na hosting po izboru.  

---

## 🔹 Na koji način se izvršna verzija koristi

Aplikacija omogućava edukativno istraživanje Knutovog algoritma kroz tri osnovne celine:

1. **Почетна страна**.  
2. **Теорија** – detaljno objašnjenje koraka Knutovog algoritma kroz tekst i dijagrame.  
3. **Визуализација** – interaktivna vizualizacija Knutovog algoritma.

Korisnik prelazi kroz zadatke redom, a nakon uspešnog rešavanja može se vratiti na početnu stranicu.

---

## 🔹 Koji ulazni primeri se mogu koristiti za upotrebu i testiranje programa

Aplikacija koristi **ugrađene primere grafa kontrolnog toka (CFG)** koji predstavljaju tipične situacije iz realnih programa.  
Primeri uključuju:
- Graf sa jednostavnim grananjem (`if-else` struktura).  
- Graf sa ciklusima (`while` i `for` petlje).  
- Graf sa više izlaznih tačaka (kompleksniji slučajevi).  

Svaki primer ima jasno označene **sentinel grane** (ulaznu i izlaznu), kao i mogućnost da korisnik vizuelno prati promene u instrumentaciji.  

---

## 🔹 Spisak alata koji su korišćeni za analizu

Za izradu projekta korišćeni su sledeći alati i biblioteke:  
- **Angular 17+** – glavni frontend okvir.  
- **TypeScript** – programski jezik.  
- **Tailwind CSS** – stilizacija korisničkog interfejsa.  
- **Cytoscape.js** – biblioteka za prikaz i manipulaciju grafovima.  
- **ELK Layout (elkjs)** – automatsko raspoređivanje čvorova grafa.  
- **GitHub Pages** – hosting izvršne verzije projekta.  
- **Visual Studio Code / IntelliJ IDEA** – razvojna okruženja.  
