# Lost in Tra(i)nslation

_Projectdocumentatie & Prototyping_

##  Over het project

**Lost in Tra(i)nslation** is een webgebaseerd documentatie- en prototypingproject, ontwikkeld door **Diana Biygereyeva (1GDM2)** in het kader van het vak **Prototyping Tools**.  
De website fungeert als centrale hub waarin het volledige ontwerpproces wordt vastgelegd — van eerste low-fidelity concepten tot uitgewerkte HTML-schermen en interactieve Figma-prototypes. Zowel mobiele als desktopervaringen worden gedocumenteerd en overzichtelijk gepresenteerd.

---

##  Doelstellingen

- Structuur en visuele kwaliteit brengen in projectdocumentatie
- Testen en presenteren van **niet-interactieve HTML-schermen**
- Integreren van **interactieve mobiele prototypes via Figma**
- Oefenen met **HTML, CSS, TailwindCSS en JavaScript**
- Ontwikkelen van een **consistente visuele stijl en UX-flow**

---

##  Projectstructuur

###  Hoofdbestanden

**index.html**

- Hero-sectie
- Wekelijkse documentatie (Week 01 → Week 12 Final)
- Overzicht van interactieve en niet-interactieve prototypes

**contact.html**

- Contactformulier (mailto-integratie)
- Custom cursor interacties
- Validatie + succesmelding

---

###  Mappenstructuur

/assets
├─ styles.css
├─ nav.css
├─ typography.css
├─ flexboxes.css
├─ forms.css
└─ \*.webp

/public/assets/schermen
├─ overzichtscherm.html
├─ perronscherm.html
└─ wagonindelingsscherm.html

/dist
└─ output.css (Tailwind build – optioneel)

---

##  Functionaliteiten

###  Navigatie

- Responsieve navigatiebalk
- Mobiel hamburger-menu
- Smooth scroll
- Duidelijke actieve states

###  Custom Cursor

- Volgt muis
- Hover- en click-animaties
- Versterkt visuele beleving

###  Wekelijkse Documentatie

- Volledig proces van **Week 01 → Week 12**
- Duidelijke evolutie van concept → final prototype
- Individuele HTML-documentatiepagina’s

###  Prototypes

**Niet-interactief (HTML)**

- Overzichtsscherm
- Perronscherm
- Wagonindelingsscherm

**Interactief (Figma)**

- Mobiele prototypes
- Presentatiemodus en gebruikersflow

🔗 _Figma-link kan hier toegevoegd worden_

---

##  Contactformulier

- Invoervalidatie
- Privacy akkoord
- Automatische mailto-verzending
- Visuele bevestiging bij succesvol versturen

---

##  Technologieën

- HTML5
- CSS3
- TailwindCSS (CDN)
- JavaScript (navigatie, cursor, forms)
- Figma
- Google Fonts

---

##  Styling & Typografie

**Fonts**

```css
@import url("https://fonts.googleapis.com/css2?family=Roboto:wght@100;300;400;500;700;900&display=swap");
@import url("https://fonts.googleapis.com/css2?family=Montserrat:wght@100..900&display=swap");
```
