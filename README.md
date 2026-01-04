# SKY Carpet Urban (Project Owner Case Study)**  
### *E‑commerce projekt pre koberce mestského štýlu*

---

# **SKY Carpet Urban – E‑commerce Launch (Project Owner Case Study)**

SKY Carpet Urban bol projekt zameraný na vytvorenie moderného e‑commerce riešenia pre predaj **mestských, dizajnových kobercov** pre mladšiu cieľovú skupinu.  
Značka bola postavená na **emócii, štýle a identite**, nie na tradičnom „kobercovom“ segmente.

Ako **Project Owner** som zastrešil návrh, špecifikáciu, UX, procesný dizajn, technickú implementáciu a integrácie potrebné pre spustenie projektu.

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
- **Definícia cieľovej skupiny a hodnotovej ponuky**  
- **UX/UI návrhy a prototypovanie**  
- **Kompletná konfigurácia a customizácia Upgates platformy**  
- **Integrácia Google Merchant, Google Analytics, Tag Manager**  
- **Návrh dátového modelu pre produkty a varianty, kompatibilné s platformou Upgates**  
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
- Wireframy a UI návrhy  
- Návrh vizuálnej identity e‑shopu  
- Customer Journey Map
- Informačná architektúra  
- Návrh kategorizácie produktov tak aby boli zodpovedané základné otázky rozhodovania sa klienta (kam, veľkosť, design)

### 🔹 **3. Technical Implementation**
- Customizácia Upgates šablón pre moderný vizuálny štýl - Uprava tém v Latte 
- Nastavenie produktových feedov  
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

---

## 🖼️ **Screenshots & Artefacts**

### 🔹 **1. Stakeholder Presentation (Canva)**

- Brand positioning  
- Cieľová skupina  
- Návrh hodnotovej ponuky  
- UX koncept  
- MVP definícia  

### 🔹 **2. Screenshots e‑shopu**
www.sky-carpet-urban.sk

- Domovská stránka  
- Produktové kategórie  
- Detail produktu  
- Custom úpravy šablón  

---

## 📚 **What I Learned (Transferable Skills)**

- Ako navrhovať digitálny produkt pre špecifickú cieľovú skupinu  
- Ako premeniť emóciu a brand na funkčný UX  
- Ako komunikovať hodnotu projektu stakeholderom  
- Ako definovať MVP a prioritizovať požiadavky  
- Ako kombinovať BA, UX a technické skilly v jednom projekte  
- Ako navrhovať low‑cost riešenia v early‑stage projektoch  

---

## 📝 **Why the Project Ended**

Projekt bol ukončený po zmene majiteľa a zmene strategických priorít.  
Ukončenie nebolo spojené s kvalitou riešenia, ale s reorganizáciou firmy.
