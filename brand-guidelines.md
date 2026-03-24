# Brand Guidelines — DimitriEngelhardt.design

## Identity

**Name:** DimitriEngelhardt.design
**Domain:** dimitriengelhardt.design
**Role:** Medienkünstler & Maker
**Tagline:** An der Schnittstelle von Technologie, Kunst und digitalem Handwerk.
**Wordmark:** `DE.` — Initials with accent dot, or full name in display type.

---

## Brand Personality

| Trait | Expression |
|---|---|
| **Präzise** | Klare Struktur, kein Überfluss |
| **Experimentell** | Ungewöhnliche Kombinationen, Brüche |
| **Handwerklich** | Sorgfalt im Detail, spürbare Qualität |
| **Direkt** | Wenig Worte, starke Aussage |
| **Technisch-poetisch** | Code trifft Kunst, Logik trifft Gefühl |

---

## Color System

```
Primary Background    #080808   Near-black — Tiefe, Fokus
Surface               #111111   Karten, Panel-Hintergründe
Border                #1C1C1C   Subtile Trennlinien
Accent (Signal)       #FF3D00   Elektrisches Orange-Rot — Energie, Präsenz
Text Primary          #F2EDE4   Warmes Off-White — kein hartes Weiß
Text Secondary        #888888   Gedämpfte Inhalte, Labels
Text Muted            #444444   Sehr zurückhaltend, dekorativ
```

**Accent-Psychologie:** `#FF3D00` — Das Orange steht für Energie, Wärme und handwerklichen Impuls. Es ist das Signal im Rauschen. Sparsam einsetzen für maximale Wirkung.

---

## Typography

| Rolle | Font | Gewicht | Eigenschaften |
|---|---|---|---|
| **Display / Headlines** | Space Grotesk | 700 | letter-spacing: -0.04em, geometrisch |
| **Body / Fließtext** | Inter | 300–400 | 16px, line-height 1.7 |
| **Mono / Labels / Code** | JetBrains Mono | 400–500 | letter-spacing: 0.05–0.2em, uppercase |

**Hierarchie:**
- H1: `clamp(56px, 10vw, 160px)` — Hero, Maximalwirkung
- H2: `clamp(28px, 4vw, 48px)` — Section Titles
- H3: `clamp(22px, 3vw, 40px)` — Projekt-Titel
- Body: `16px` — Lesbarkeit, Ruhe
- Labels: `10–12px` Mono, Uppercase — Technisch, strukturierend

---

## Logo / Wordmark Usage

- **Primär:** `DE.` — Initials + Akzent-Punkt in Orange
- **Sekundär:** `DIMITRI ENGELHARDT.` — Vollname in Display Bold
- **Regel:** Punkt immer in `#FF3D00`
- **Mindestgröße:** 18px für `DE.`, 32px für den Vollnamen
- **Freiraum:** Mindestens `0.5×` der Buchstabenhöhe als Freiraum

---

## Visuelles System

**Gitter:** Sichtbares 80px-Raster als Hintergrundstruktur im Hero (Opazität 0.4)
**Noise:** Feines Filmkorn-Overlay (4% Opazität) für analoge Wärme
**SVG-Geometrie:** Abstrakte, technische Zeichnungen als Projekt-Thumbnails
**Trennlinien:** `1px solid #1C1C1C` — Grid-basiert, keine Schatten
**Radius:** 0–2px — Fast keine Rundungen, kantig und präzise

---

## Ton & Sprache

- **Sprache:** Primär Deutsch, technische Begriffe Englisch
- **Stimme:** Knapp, direkt, selbstbewusst — kein Marketing-Jargon
- **Verben:** bauen, schaffen, erkunden, reagieren, stören, berühren
- **Keine:** Buzzwords, Superlativen, übertriebene Adjektive

**Beispiele:**
- ✅ „Lass uns etwas bauen."
- ✅ „Ich schaffe Erfahrungen, die man anfassen kann."
- ❌ „Innovative, cutting-edge media experiences."

---

## Design-Prinzipien

1. **Typografie als Gestaltung** — Text ist das visuelle Element
2. **Weniger ist präziser** — Jedes Element hat eine Funktion
3. **Sichtbare Struktur** — Grids und Linien als gestalterisches Mittel
4. **Signal im Rauschen** — Akzent sparsam, dafür wirkungsvoll
5. **Craft-Qualität** — Jedes Detail ist eine Entscheidung
6. **Skills** – Nutze die skills frontend-design und ui-ux-pro-max
7. **Planung** – Erstelle vorher einen Plan und frage ob ich alles für gut befinde

---

## CSS Design Tokens

```css
:root {
  /* Colors */
  --c-bg:          #080808;
  --c-surface:     #111111;
  --c-border:      #1C1C1C;
  --c-accent:      #FF3D00;
  --c-accent-glow: rgba(255, 61, 0, 0.15);
  --c-text-1:      #F2EDE4;
  --c-text-2:      #888888;
  --c-text-3:      #444444;

  /* Fonts */
  --f-display: 'Space Grotesk', -apple-system, sans-serif;
  --f-mono:    'JetBrains Mono', 'Courier New', monospace;
  --f-body:    'Inter', -apple-system, sans-serif;

  /* Easing */
  --ease-out-expo: cubic-bezier(0.16, 1, 0.3, 1);
}
```
