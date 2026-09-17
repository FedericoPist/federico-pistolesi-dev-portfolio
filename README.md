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

## Clonare il portfolio

Per scaricare anche tutti i progetti collegati:

```bash
git clone --recurse-submodules https://github.com/FedericoPist/federico-pistolesi-dev-portfolio.git
```

Se il portfolio è già stato clonato:

```bash
git submodule update --init --recursive
```
