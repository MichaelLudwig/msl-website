# MSL GmbH — Website

Statische Unternehmenswebsite der MSL GmbH (Console-Variante), zweisprachig (DE/EN).
Deployment als **Azure Static Web App** unter **www.msl-labs.de**.

## Struktur

```
index.html                 Single-Page-Site (JS-gerendert, Content-Objekt C)
impressum.html             Impressum (statisch, DE/EN)
datenschutz.html           Datenschutzerklärung (statisch, DE/EN)
staticwebapp.config.json   Azure SWA Routing/Config
assets/
  favicon.svg
  michael-ludwig.jpg       Portrait Geschäftsführer
```

## Build

Kein Build-Schritt. Reines HTML/CSS/JS, App-Location = Repo-Root.

## Deployment

Azure Static Web Apps, CI/CD über GitHub Actions (Push auf `main` deployt automatisch).
