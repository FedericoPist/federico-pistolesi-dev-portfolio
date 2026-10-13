# Federico Pistolesi — Developer Portfolio

Raccolta dei miei progetti software. Ogni progetto mantiene la propria
repository e la propria cronologia Git ed è collegato a questo portfolio come
submodule.

**Sito:** [federicopist.github.io/federico-pistolesi-dev-portfolio](https://federicopist.github.io/federico-pistolesi-dev-portfolio/)

## Progetti

### GareIT Radar

Piattaforma full-stack per raccogliere, normalizzare e consultare bandi di gara
pubblicati dai portali della Pubblica Amministrazione italiana. Integra scraping
asincrono, ricerca e filtri, API REST, diagnostica e un'interfaccia web.

**Stack:** Python, FastAPI, Pydantic, httpx, Beautiful Soup, Playwright, PHP,
Laravel, Blade, JavaScript, CSS, MariaDB, SQLite, Docker Compose e Nginx.

- [Repository originale](https://github.com/FedericoPist/gareit-radar)
- Percorso nel portfolio: `projects/gareit-radar`

### PriceAdv

Applicazione per monitorare i prezzi di un catalogo WooCommerce e confrontarli
con le schede prodotto sponsorizzate nella SERP Google. Include importazione da
URL e CSV, ricerche in Chrome, verifica delle corrispondenze, storico dei prezzi,
dashboard dei competitor ed esportazione CSV.

**Stack:** PHP, Laravel, Blade, JavaScript, Node.js, SQLite e Chrome DevTools Protocol.

- [Repository originale](https://github.com/FedericoPist/priceadv)
- Percorso nel portfolio: `projects/priceadv`

### Link Discovery

Applicazione locale per individuare link esterni non funzionanti e opportunità
di broken link building. Esplora pagine e sitemap, conserva anchor text e
metadati SEO, rispetta robots.txt e distingue link mancanti, accessi negati ed
errori temporanei. Include scansioni riprendibili, storico e report CSV filtrabili.

**Stack:** PHP, Laravel, Blade, CSS, SQLite, Symfony DomCrawler e PHPUnit.

- [Repository originale](https://github.com/FedericoPist/link-discovery)
- Percorso nel portfolio: `projects/link-discovery`

## Clonare il portfolio

Per scaricare anche tutti i progetti collegati:

```bash
git clone --recurse-submodules https://github.com/FedericoPist/federico-pistolesi-dev-portfolio.git
```

Se il portfolio è già stato clonato:

```bash
git submodule update --init --recursive
```
