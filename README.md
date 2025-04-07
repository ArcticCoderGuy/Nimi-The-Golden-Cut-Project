Projektin nimi: The-Golden-Cut-Project – HTML + CSS -toteutus

# Tavoite:
Toteuttaa tehtävänannon mukainen responsiivinen HTML/CSS-sivu,
jossa on kolme kuvaa, tekstejä ja hover-efekti, sekä huolellinen rakenne ja kommentointi.

---

## Toteutusvaiheet ja MVP:t:

[OK] 1. Rakennettu kansiorakenne (images, styles.css, index.html, README.md)
[OK] 2a. Luotu HTML-runko (header, main, footer) sekä GitHub-integrointi VS Codeen
[OK] 2b. Testattu että commit ja push toimivat sekä styles ja html keskustelevat
[OK] 2c. HTML- ja CSS-rungot luotu VS Codessa (boilerplate valmis, `<link rel>` yhdistetty)
[OK] 2d. Kuvat ja responsiivinen skaalaus (HTML + CSS). Kuvien alt-tekstit lisätty saavutettavuuden vuoksi.

---

### MVP 3: Kuvien rakenne

[OK] 3a. Lisätty kolme kuvaa omiin section-elementteihin
[OK] 3b. Kuvien tiedostonimet, kansiot ja alt-tekstit kunnossa

---

### MVP 4: Tekstit ja hoverit

[OK] 4a. Lisätty jokaiselle kuvalle otsikko (<h2>) ja lyhyt teksti (<p>)
[OK] 4b. Lisätty hover-efekti (scale, opacity, box-shadow, transition, cursor)

---

### MVP 5: Layout, fontit ja värit

[[OK] 5a. Rakenne eroteltu semanttisiin lohkoihin: header, main, footer  
[OK] 5b. Tekstien asettelu CSS:llä (text-align, font-size, värit, riviväli)  
[OK] 5c. Väriteema yhtenäistetty (taustakuva, fontit, hover-efekti, värikoodit)  
[OK] 5d. Kuvien asettelu ja marginaalit viimeistelty (flex, `margin-top: 12rem`)

---

### MVP 6: Viimeistely ja validointi

[OK] 6a. Responsiivisuus testattu (desktop, tablet, mobile):  
Testattu seuraavilla laitenäkymillä VS Code DevToolsilla:

- 📱 Mobile (max-width: 600px): 1 kuva per rivi
- 💻 Tablet (601px–1024px): 2 kuvaa vierekkäin
- 🖥️ Desktop (min-width: 1025px): 3 kuvaa vierekkäin  
- iPad Pro tablettinäkymä, Pixel7 puhelinnäkymä (Android), iPhone 14/SE/XR
→ Skaalaus toimii oikein kaikilla laitteilla.

[OK ] 6b. Koodin kommentointi selkeää ja ammattimaista
[OK ] 6c. Testattu Live Serverillä ja tarkistettu ettei virheitä

---

### MVP 7: OL/UL lista ja punainen 1 sekä ©-"Fixed" paikka oikea alareuna

[ ] 7a. Punainen ol/ul lista jossa punainen numero 1.
[ ] 7b. Asemointi ©-toteutettu `position: fixed` TESTIÄ!

---

### MVP 8: Luovutus

[ ] 8. Projekti luovutettu opettajalle (Timo) ja dokumentaatio valmis

---

Tekijä: Markus "NorthFox" Kaprio  
Päivämäärä: 6.4.2025  

Erityismaininnat: Pekka Takala, koodari-velho ja Henrik Veso Azure-moniosaaja jotka auttoivat projektin dokumentoinnin sekä Pekan sanoin "koodarin mindset:in saavuttelusta". 

							
			            -Tapahtumaloki- 


   Projektin ensimäinen työvaihe: repo + versiohallinta + yhteistyö


1. Tehdään VS Code:en uusi hakemisto "The Golden Cut of the Golden Retriever" ja luodaan kansiorakenne (index.html,styles.css,images/, README.txt).

2. Tehdään VS Code:een ja GitHub:iin kokonaan uusi (myös VS Code:een integroitu) hakemistorakenne -> Kansio "The golden cut" omalle desktop:lle.

3. Avasin terminaali (CTRL + ö) ja nyt kun on aivan uusi hakemisto se pitää perustaa VS Code:een ja linkittää GitHub:iin tämä -The Cut of the Golden Retriever-hakemisto. 

4.  'git init' alustetaan ensin Git-repo sitten komento-> 'git add .' jolla lisäsin filet versionhallintaan

5.  git commit -m "initial commit", jonka jälkeen luotiin uusi repo mun "ArcticCoderGuy"- GitHub profiiliin

6.Linkitetään paikallinen kansio GitHub:iin: git remote add origin https://github.com/ArcticCoderGuy/the-golden-cut.git -> 'git branch -M main' -> 'git push -u origin main'

7. Tarkistin että GitHub:ssa näkyy kaikki tiedostot: 'git add .' -> git commit -m "Eka muutos readme.txt tiedostoon" -> 'git push' 

8. Testataaan vielä varmuudeksi että commit:oimnti toimii ja toimii varmisti




