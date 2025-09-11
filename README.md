# EcoEnergy Solutions - Sito Web Aziendale

Un sito web moderno e professionale per aziende specializzate in energia rinnovabile e impianti fotovoltaici, con design responsive e palette di colori personalizzata.

## 🎨 Caratteristiche del Design

### Palette Colori
- **Colore Primario**: Verde Smeraldo (#059669)
- **Colore Secondario**: Blu Cielo (#0ea5e9) 
- **Colore Accent**: Ciano (#06b6d4)
- **Colori Neutri**: Grigi moderni per testo e sfondi

### Differenze dal Sito Originale
- Palette completamente diversa (verde/blu invece di arancione)
- Layout modernizzato con gradienti e animazioni
- Tipografia Inter per un look più contemporaneo
- Effetti hover e transizioni fluide
- Contenuti specifici per energia rinnovabile

## 🚀 Funzionalità

### Sezioni Principali
- **Header**: Navigazione fissa con menu mobile responsive
- **Hero Section**: Sezione principale con animazioni floating per energia solare
- **Servizi**: Griglia di servizi energia rinnovabile con icone specifiche
- **Chi Siamo**: Informazioni aziendali con statistiche animate
- **Progetti**: Showcase impianti fotovoltaici installati
- **Contatti**: Form preventivo gratuito con validazione
- **Footer**: Link utili e informazioni di contatto

### Interattività
- Menu mobile hamburger
- Scroll smooth per navigazione
- Animazioni on-scroll
- Contatori animati per statistiche impianti
- Form preventivo con validazione completa
- Notifiche toast per feedback utente
- Effetti parallax leggeri
- Hover effects su card e elementi

## 📱 Responsive Design

Il sito è completamente responsive e ottimizzato per:
- **Desktop**: Layout a griglia con sidebar
- **Tablet**: Layout adattato con colonne ridotte
- **Mobile**: Layout a singola colonna con menu hamburger

## 🛠️ Tecnologie Utilizzate

- **HTML5**: Struttura semantica
- **CSS3**: Styling moderno con variabili CSS e Flexbox/Grid
- **JavaScript ES6+**: Interattività e animazioni
- **Font Awesome**: Icone vettoriali
- **Google Fonts**: Tipografia Inter

## 📁 Struttura File

```
paneli/
├── index.html          # Pagina principale
├── styles.css          # Stili CSS
├── script.js           # JavaScript per interattività
└── README.md           # Documentazione
```

## 🚀 Come Utilizzare

1. **Aprire il sito**: Apri `index.html` nel browser
2. **Personalizzare contenuti**: Modifica il testo in `index.html`
3. **Cambiare colori**: Modifica le variabili CSS in `styles.css`
4. **Aggiungere funzionalità**: Estendi `script.js`

## 🎨 Personalizzazione Colori

Per cambiare la palette colori, modifica le variabili CSS in `styles.css`:

```css
:root {
    --primary-color: #6366f1;      /* Colore principale */
    --secondary-color: #8b5cf6;    /* Colore secondario */
    --accent-color: #06b6d4;       /* Colore accent */
    /* ... altre variabili */
}
```

## 📝 Personalizzazione Contenuti

### Modificare Testi
- Apri `index.html`
- Trova le sezioni da modificare
- Sostituisci i testi con i tuoi contenuti

### Aggiungere Servizi
```html
<div class="service-card">
    <div class="service-icon">
        <i class="fas fa-solar-panel"></i>
    </div>
    <h3>Nuovo Servizio</h3>
    <p>Descrizione del servizio energetico...</p>
    <ul class="service-features">
        <li>Caratteristica 1</li>
        <li>Caratteristica 2</li>
    </ul>
</div>
```

### Aggiungere Progetti Portfolio
```html
<div class="portfolio-item">
    <div class="portfolio-image">
        <div class="project-placeholder">
            <i class="fas fa-home"></i>
        </div>
    </div>
    <div class="portfolio-content">
        <h3>Nuovo Impianto</h3>
        <p>Descrizione impianto fotovoltaico...</p>
        <div class="portfolio-tech">
            <span class="tech-tag">10kW</span>
            <span class="tech-tag">Batteria 15kWh</span>
        </div>
    </div>
</div>
```

## 🔧 Funzionalità JavaScript

### Form Preventivo
- Validazione email e telefono automatica
- Selezione servizio obbligatoria
- Feedback visivo con notifiche
- Prevenzione spam con controlli

### Animazioni
- Intersection Observer per animazioni on-scroll
- Contatori animati per statistiche
- Effetti parallax leggeri
- Transizioni fluide

### Navigazione
- Menu mobile responsive
- Scroll smooth tra sezioni
- Header trasparente con effetto scroll

## 📱 Browser Supportati

- Chrome 60+
- Firefox 55+
- Safari 12+
- Edge 79+

## 🎯 SEO e Accessibilità

- Struttura HTML semantica
- Meta tag per viewport mobile
- Alt text per immagini
- Focus styles per navigazione tastiera
- Contrasti colori conformi WCAG

## 📈 Performance

- CSS e JS ottimizzati
- Immagini lazy loading ready
- Debounced scroll events
- Animazioni hardware-accelerated

## 🔒 Sicurezza

- Validazione input form
- Sanitizzazione dati utente
- Prevenzione XSS base

---

**Nota**: Questo sito è stato creato come alternativa moderna al sito di riferimento (solutiontechnology.eu), mantenendo la stessa struttura funzionale per il business dell'energia rinnovabile ma con design e colori completamente diversi (verde/blu invece di arancione) per evitare somiglianze.
