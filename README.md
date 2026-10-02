# picoTracker-Theme-Studio


## Development Visualization

<video src="https://raw.githubusercontent.com/itsdarklikehell/picoTracker-Theme-Studio/main/gource.mp4" controls width="100%"></video>

*Gource visualization showing the repository's commit history. See the [Gource workflow](.github/workflows/gource.yml) for details.*


<img src="https://img.shields.io/github/stars/itsdarklikehell/picoTracker-Theme-Studio?style=flat-square&color=blue" alt="Stars">
<img src="https://img.shields.io/github/forks/itsdarklikehell/picoTracker-Theme-Studio?style=flat-square&color=green" alt="Forks">
<img src="https://img.shields.io/github/license/itsdarklikehell/picoTracker-Theme-Studio?style=flat-square" alt="License">
<img src="https://img.shields.io/github/actions/workflow/status/itsdarklikehell/picoTracker-Theme-Studio/ci.yml?branch=main&label=CI&style=flat-square" alt="CI Status">

A browser-based theme editor for the [picoTracker](https://github.com/synthetos/picoTracker) — design and export `.PTT` theme files without leaving your browser.

## Installatie

### Online gebruik

Gebruik de live editor hier: <https://itsdarklikehell.github.io/picoTracker-Theme-Studio/>

### Lokaal draaien

```bash
git clone https://github.com/itsdarklikehell/picoTracker-Theme-Studio.git
cd picoTracker-Theme-Studio/static-app
python3 -m http.server 8000
```

Dan open <http://localhost:8000> in je browser.

## Gebruik

1. Open de editor in je browser
2. Kies een thema om te bewerken
3. Pas kleuren, fonts en layout aan
4. Exporteer als `.PTT` bestand
5. Importeer het thema in picoTracker

## Bijdragers

- [itsdarklikehell](https://github.com/itsdarklikehell) — Onderhouder
- [synthetos](https://github.com/synthetos) — picoTracker creator

## Licentie

MIT — zie [LICENSE](LICENSE) voor details.
