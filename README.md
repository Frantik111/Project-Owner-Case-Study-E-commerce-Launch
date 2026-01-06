# **SKY Carpet Urban – E‑commerce Launch (Project Owner Case Study)**
### *E‑commerce projekt pre koberce mestského štýlu*

Projekt som viedol end‑to‑end — od definície hodnotovej ponuky a procesnej analýzy až po UX návrhy, technickú implementáciu a marketingové integrácie.

**Project Summary**
- **End‑to‑end e‑commerce projekt pre mestskú lifestyle značku.**
- **Ako Project Owner som zastrešil business analýzu, UX návrh, procesný dizajn,**
- **Customizáciu Upgates platformy a marketingové integrácie.**
- **Súčasťou projektu bol aj Python/Django nástroj pre správu skladových zásob.**

**Relevantné BA kompetencie**
- Requirements engineering
- Procesná analýza (AS‑IS / TO‑BE)
- Návrh dátových tokov
- User stories + acceptance criteria
- Prioritizácia (MVP, MoSCoW)
- Stakeholder management
- UX research & prototypovanie

SKY Carpet Urban bol projekt zameraný na vytvorenie moderného e‑commerce riešenia pre predaj **kusových kobercov** pre mladšiu cieľovú skupinu.
Značka bola postavená na **emócii, štýle a identite**, nie na tradičnom „kobercovom“ segmente.
Projekt komunikuje štýl veľkomesta, životný štýl, dynamiku a rôznorodosť.

Ako **Project Owner** som zastrešil návrh, špecifikáciu, UX, procesný dizajn, technickú implementáciu a integrácie potrebné pre spustenie projektu.

![Screenshot](Screenshots-&-Artefacts/preview.jpg)

---

## 🚀 **Project Overview**

Cieľom projektu bolo vytvoriť:

- moderný e‑shop pre mladú klientelu (25-45) ktorá sa stotožnuje s mestským životným štýlom,  
- vizuálne atraktívnu značku, ktorá predáva emóciu a štýl,  
- jednoduchý a rýchly nákupný proces,  
- platformu pripravenú na marketingové kampane a budúce škálovanie.

Projekt bol postavený na platforme **Upgates**, ktorú som výrazne prispôsobil špecifickým požiadavkám značky.

---

## 👤 **My Role: Project Owner (Business Analysis + UX + Implementation Coordination)**

Moje zodpovednosti zahŕňali:

- **Business analysis & requirements engineering**
- **Preklad biznisových potrieb do technických špecifikácií**
- **Definícia cieľovej skupiny a hodnotovej ponuky**  
- **UX/UI návrhy a prototypovanie**  
- **Kompletná konfigurácia a customizácia Upgates platformy**  
- **Integrácia Google Merchant, Google Analytics, Tag Manager**  
- **Návrh dátového modelu pre produkty a varianty, kompatibilný s platformou Upgates**  
- **Stakeholder management a prezentácie pre vedenie**  
- **Prioritizácia požiadaviek a definícia MVP**  
- **Koordinácia implementácie a testovania**

---

## 🧩 **Key Deliverables**

### 🔹 **1. Business & Product Analysis**
- Definícia cieľovej skupiny (urban, mladá, vizuálne orientovaná)  
- Hodnotová ponuka: „štýl, identita, atmosféra veľkomesta“  
- Návrh dátových tokov medzi systémami  

### 🔹 **2. UX & Brand Design**
- Návrh vizuálnej identity e‑shopu  
- UI návrhy a vizuálne štýly
- Design manual (komentované vzory)
- Návrh kategorizácie produktov – postavený na 3 základných otázkach zákazníka (kam, veľkosť, dizajn)

### 🔹 **3. Technical Implementation**
- Customizácia Upgates šablón pre moderný vizuálny štýl - Uprava tém v Latte 
- Nastavenie produktových feedov - custom xml parser v pythone pre Google Merchant Center
- Integrácia Google Merchant Center + platená reklama 
- Integrácia Google Analytics + Tag Manager  
- Návrh a implementácia manuálneho skladového workflowu (viď nižšie)

---

## 🛠️ **Python/Django – Custom Stock Sync Workflow**

V počiatočnej fáze projektu nebol rozpočet na externé skladové integrácie.  
Navrhol som preto **manuálny, ale efektívny a bezplatný workflow**, ktorý:

1. **Stiahol skladové zásoby od dodávateľov**  
   - email → CSV  
   - FTP → CSV  

2. **Django aplikácia spracovala CSV**  
   - aktualizovala databázu produktov  
   - označila zmeny (delta)

3. **Jedným kliknutím sa vygeneroval Upgates‑kompatibilný CSV export**  
   - pripravený na import do e‑shopu  
   - bez potreby platiť za integráciu

`[Stock Sync Django Tool – GitHub Repository](URL sem)`

4. **Vytvorený jednoduchý XML parser**  
   - integrovaný upgates feed neodzrkadloval potreby kobercového segmentu
   - spracuje existujúce cvs dáta z upgates
   - vytvorí na ftp xml súbor kompatibilný s Google Merchant Center
  
---

## 🖼️ **Screenshots & Artefacts**

### 🔹 **1. Stakeholder Presentation (Canva)**

- Brand positioning  
- Cieľová skupina  
- Návrh hodnotovej ponuky  
- UX koncept  
- MVP definícia
  
![Screenshot](Screenshots-&-Artefacts/Stakeholder-Presentation.png)

### 🔹 **2. Screenshots e‑shopu**
www.sky-carpet-urban.sk

- [Domovská stránka](Screenshots-&-Artefacts/homepage.jpeg)
- [Produktové kategórie](Screenshots-&-Artefacts/category.jpeg)
- [Detail produktu](Screenshots-&-Artefacts/product.jpeg)
- Custom úpravy šablón - viď nižšie screenshoty
  
Rozbalovacia informácia o skladovej dostupnosti každej veľkosti koberca - hĺkbová úprava Latte témy + CSS
- Štandardná šablóna toto riešenie nepodporuje
- komplet napísané obslužné mini skripty a podmienky
- UX spracovanie

![Rozbalovacia informácia o skladovej dostupnosti každej veľkosti koberca](Screenshots-&-Artefacts/customized-size-availability.jpg)
  
Animovaný štýtok - CSS dúhová zmena borderu
- Jednoduchý vizuálny pútač - UX
  
![Animovaný štýtok - CSS dúhová zmena borderu](Screenshots-&-Artefacts/customized-animated-tag.jpg)
  
Dynamické rozloženie sekcie - HTML + CSS
- Prispôsobí sa rozlíšeniu zobrazovacieho zariadenia
- Pomoc s navigáciou na stránke
  
![Dynamické rozloženie sekcie](Screenshots-&-Artefacts/customized-section.jpg)
  
Custom FAQ - HTML compatibile with schema.org microdata + CSS pre SEO
- SEO kompatibilné vďaka microdata
- Hodnota pre užívateľa

![Custom FAQ - HTML compatibile with schema.org/](Screenshots-&-Artefacts/customized-faq.jpg)

---

## 📚 **What I Learned (Transferable Skills)**

- Ako navrhovať digitálny produkt pre špecifickú cieľovú skupinu  
- Ako premeniť emóciu a brand na funkčný UX  
- Ako komunikovať hodnotu projektu stakeholderom  
- Ako definovať MVP a prioritizovať požiadavky  
- Ako kombinovať BA, UX a technické skilly v jednom projekte  
- Ako navrhovať low‑cost riešenia v early‑stage projektoch  

Projekt mi umožnil spojiť business analýzu, UX a technické myslenie do jedného celku — čo je kombinácia, ktorú chcem ďalej rozvíjať v roli Business Analytika.

## 🌟 **Business Impact (kvalitatívny)**
- Zjednotenie brand identity do moderného vizuálneho štýlu
- Zjednodušenie nákupného procesu pre cieľovú skupinu
- Zavedenie merateľných marketingových nástrojov (Analytics, Merchant)
- Zníženie nákladov na integrácie vďaka vlastnému Python workflowu
- Pripravenosť platformy na budúce kampane a škálovanie

---

## 📝 **Why the Project Ended**

Projekt bol ukončený po zmene majiteľa a zmene strategických priorít.  
Ukončenie nebolo spojené s kvalitou riešenia, ale s reorganizáciou firmy.

## 📜 License

This project is published under the **CC BY-NC-ND 4.0 license**.  
It is intended as a portfolio showcase for job applications.  
You may view and share it for non-commercial, educational or evaluative purposes only.

© Zdenko Siegel, 2026
