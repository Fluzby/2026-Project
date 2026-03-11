# Real Estate CRM Dashboard

## Projekti ülevaade

See projekt on **kinnisvara CRM dashboard**, mis on loodud praktikaprojekti raames. Süsteemi eesmärk on pakkuda kinnisvaramaakleritele keskset platvormi, kus hallata kinnisvaraobjekte, kliente, ajakava ning arhiveeritud andmeid.

CRM võimaldab kasutajatel:

- hallata kinnisvaraobjekte
- jälgida kliente ja potentsiaalseid ostjaid
- planeerida kohtumisi ja tegevusi
- hoida kogu töövoog ühes süsteemis

Rakendus töötab **sisselogimisega**, kus kasutaja autentimine ja andmete salvestamine toimub **Supabase’i** kaudu.

Süsteemi peamine eesmärk on **lihtsustada kinnisvaramaakleri igapäevast tööprotsessi**, koondades kliendihalduse, kinnisvara halduse ja ajaplaneerimise ühte rakendusse.

---

# Süsteemi põhiosad

## Dashboard

Dashboard annab ülevaate kinnisvara portfelli hetkeseisust.

### Peamised funktsioonid

- kinnisvara statistika  
- klientide arv  
- kinnisvara saadavuse ülevaade  
- hiljuti lisatud objektid  
- järeltegevused ja aktiivsus  
- kalendri kiire ülevaade  

---

## Houses (Kinnisvara objektid)

Houses moodul võimaldab hallata kinnisvaraobjekte.

### Peamised funktsioonid

- kinnisvaraobjektide nimekiri  
- otsing ja filtreerimine  
- objekti saadavuse staatus  
- sildid ja kategooriad  
- objekti detailid (hind, toad, pindala)  
- mitme objekti korraga haldamine  

---

## Clients (Kliendid)

Clients moodul on mõeldud klientide ja potentsiaalsete ostjate haldamiseks.

### Peamised funktsioonid

- kliendi kontaktandmed  
- otsing ja filtreerimine  
- märkmete lisamine  
- kliendi eelistused  
- kliendi sidumine kinnisvaraobjektiga  

See võimaldab maakleritel paremini jälgida, millised kliendid on huvitatud millistest objektidest.

---

## Calendar (Kalender)

Calendar moodul aitab planeerida kohtumisi ja ülesandeid.

### Funktsioonid

- kohtumised  
- kinnisvara vaatamised  
- tähtajad  
- järeltegevused  
- kuuvaade  

See aitab maakleritel organiseerida oma päevast tööd ja kohtumisi.

---

## Archive (Arhiiv)

Archive sektsioon sisaldab **arhiveeritud või kustutatud kirjeid**.

See võimaldab säilitada vanu andmeid ilma, et need segaksid aktiivset töövaadet.

---

## Settings (Seaded)

Settings moodul võimaldab kasutajatel kohandada CRM keskkonda.

### Seadete hulka kuuluvad

- keele valik  
- teema (theme)  
- dashboardi widgetid  
- shortcutid  

---

# Süsteem

Süsteem on ehitatud järgmiste tehnoloogiatega:

- **Vue.js** – frontend raamistik  
- **Vue Router** – lehtede navigeerimine  
- **Supabase** – autentimine ja andmebaas  
- **TailwindCSS** – kasutajaliidese stiil  
- **JavaScript** – rakenduse loogika  

---

# Tulevased arendused

## 1. Töövoo haldus

- tehingute pipeline  
- kinnisvara vaatamiste haldus  
- pakkumised ja läbirääkimised  
- tehingu lõpetamise protsess  

---

## 2. Kliendi ja kinnisvara sobitamine

- parem kliendi ja objekti matching süsteem  
- filtrid kliendi eelistuste põhjal  
- automaatsed kinnisvara soovitused  

---

## 3. Koostöö funktsioonid

- ülesannete määramine agentidele  
- kommentaarid  
- tegevuste omanikud  
- meeldetuletused  

---

## 4. Andmete kvaliteedi parandamine

- andmete import  
- valideerimine  
- rikkalikum kinnisvara metadata  
- fotode haldus  

---

## 5. Analüütika ja raportid

- konversiooni statistika  
- agentide tulemused  
- kinnisvara müügikiirus  
- turu nõudluse trendid  

---

## 6. Automatiseerimine

- automaatsed järeltegevused  
- korduvad ülesanded  
- staatuse põhised teavitused  
- Outlook API integratsioon  

---

## 7. Kasutajakogemuse parandamine

- detailsemad objekti ja kliendi lehed  
- parem navigeerimine  
- kiirem töövoog dashboardist  

---

# Kokkuvõte

Praeguses seisus on süsteem **toimiv sisemine CRM dashboard kinnisvarameeskonnale**.

Järgmine arendusetapp on muuta see **täielikuks töövahendiks**, mis toetab kogu kinnisvaratehingu protsessi alates **kliendi haldusest kuni tehingu lõpetamiseni**.
