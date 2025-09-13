---
title: Meshtastic im Rheinland – Köln, Düsseldorf, Bonn, Aachen
description: "Einstieg in Meshtastic im Rheinland mit einheitlichem ShortSlow‑Profil (EU868), aktiver WhatsApp‑Community mit über 200 Mitgliedern und Infos für Köln, Düsseldorf, Bonn, Aachen, Wuppertal, Leverkusen, Krefeld, Mönchengladbach u. a."
nav_order: 1
layout: default
permalink: /
---

<div class="hero">
  <img src="https://meshtastic.org/design/logo/svg/Mesh_Logo_Black.svg" alt="Meshtastic Logo" style="height:56px; vertical-align:middle; opacity:.95;">
  <h1>Meshtastic Rheinland</h1>
  <p>Einfacher Einstieg für Meshtastic im Rheinland – mit gemeinsamen Standard‑Einstellungen (ShortSlow) und lokalen Tipps.</p>
  <p>
    <a class="btn" href="#shortslow">Profil: ShortSlow</a>
    <a class="btn btn-secondary" href="#quickstart">Schnellstart</a>
    <a class="btn btn-secondary" href="#community">Community</a>
  </p>
</div>

Willkommen auf der Info-Seite für Meshtastic Nutzer im Rheinland. Du findest hier den Schnellstart, die in der Region genutzten Grundeinstellungen und die wichtigsten Links.

Meshtastic wird im gesamten Rheinland eingesetzt – rund um Köln, Düsseldorf, Bonn, Aachen, Wuppertal, Leverkusen, Krefeld, Mönchengladbach sowie in den Kreisen Rhein‑Erft, Rhein‑Sieg, Rhein‑Berg, Rhein‑Kreis Neuss, Heinsberg, Düren, Euskirchen und dem Bergischen Land. 

## TL;DR

- Region/Band: EU868 (Deutschland/EU)
- Modem‑Profil: **ShortSlow** (Rheinland‑Standard)
- Trete der Community bei: siehe unten (über 200 Mitglieder)

> Achtung: Lokale Vorschriften
> Bitte beachte lokale Funkrichtlinien (z. B. Duty Cycle im 868‑MHz‑Band). Stelle in Meshtastic die richtige Region ein und nutze angemessene Sendeleistung. Details siehe Radio‑Konfiguration in der Meshtastic‑Doku.
{: .warning }

## Schnellstart {#quickstart}

1. Geräte‑Firmware flashen und App koppeln.
2. In den LoRa‑Einstellungen die Region auf EU868 stellen.
3. „Modem preset“ auf ShortSlow setzen.
4. Kanal einstellen (Schlüssel optional) und mit dem Mesh testen.

Mehr Details findest du in Setup‑Basics weiter unten.

## Profil: ShortSlow (Rheinland‑Standard) {#shortslow}

Im Rheinland nutzen wir einheitlich das Modem‑Profil „ShortSlow“. Das sorgt für gute Reichweite bei vertretbarem Durchsatz und erleichtert die Interoperabilität im Mesh.

> Warum ShortSlow?
> - robuste Reichweite in urbanen und hügeligen Gebieten
> - geringe Airtime, bessere Mesh‑Durchdringung
> - einheitliche Basis für Events und Community‑Tests
{: .note }

So stellst du es ein:

1. In der App: Geräteeinstellungen → LoRa/Modem.
2. Region/Band: EU868 (Europa/Deutschland) wählen.
3. „Modem preset“: „ShortSlow“ auswählen und speichern.

Mehr Hintergründe: Radio‑Konfiguration (Modem‑Parameter)
- https://meshtastic.org/docs/configuration/radio/

## Community & Mesh Map {#community}

- WhatsApp‑Community (über 200 Mitglieder): {{ site.whatsapp_invite_url }}
- Mesh Map: {{ site.mesh_map_url }}

> Hinweis: Der WhatsApp‑Einladungslink wird noch ergänzt. In `_config.yml` unter `whatsapp_invite_url` pflegen.
{: .note }

### Lokal vernetzt in vielen Städten

Köln, Düsseldorf, Bonn, Aachen, Wuppertal, Leverkusen, Krefeld, Mönchengladbach, Neuss, Solingen, Remscheid, Bergisch Gladbach und umliegende Kreise: Das Rheinland‑Mesh wächst stetig. Schau in die WhatsApp‑Gruppe für lokale Kontakte, Treffpunkte und Testrunden.

## Setup‑Basics (EU/DE) {#setup}

1) Firmware & App
- Offizielle Downloads: https://meshtastic.org/docs/downloads/
- Getting Started (Flashen/Verbinden): https://meshtastic.org/docs/getting-started/

2) Region/Band: EU868
- LoRa‑Einstellungen → Region auf EU868 setzen
- Radio‑Konfiguration: https://meshtastic.org/docs/configuration/radio/

3) Kanäle
- Öffentlich zum Testen oder privat mit Schlüssel
- Kanal‑Doku: https://meshtastic.org/docs/configuration/channels/

4) Rollen & Strom
- Geräte‑Rollen (Router/Client/etc.): https://meshtastic.org/docs/configuration/device/
- Power‑Tipps: https://meshtastic.org/docs/configuration/power/

## Häufige Fragen (FAQ) {#faq}

- Gibt es Gruppen in Köln, Düsseldorf, Bonn, Aachen?
  Ja, die Rheinland‑Community deckt diese Städte und Umgebung ab. Einstieg über die WhatsApp‑Gruppe (über 200 Mitglieder) weiter oben.
- Welche Hardware eignet sich?
  Geräte mit EU868‑Unterstützung und guter Antenne. Wichtig sind korrekte Regionseinstellungen und saubere Montage (Freisicht, Höhe, Abstand zu Metall).
- Wie verbessere ich Reichweite in der Stadt?
  Antenne möglichst hoch und frei platzieren, ShortSlow nutzen, Router‑Knoten strategisch setzen.

<script type="application/ld+json">
{
  "@context": "https://schema.org",
  "@type": "WebSite",
  "name": "Meshtastic Rheinland",
  "url": "https://meshtastic-rheinland.github.io/",
  "inLanguage": "de",
  "about": {
    "@type": "Thing",
    "name": "Meshtastic im Rheinland (Köln, Düsseldorf, Bonn, Aachen)"
  }
}
</script>

## Offizielle Ressourcen {#resources}

- Meshtastic Dokumentation: https://meshtastic.org/docs
- Radio‑Konfiguration: https://meshtastic.org/docs/configuration/radio/
- Getting Started: https://meshtastic.org/docs/getting-started/

### Suchbegriffe (lokal)

Zur leichteren Auffindbarkeit erscheinen hier relevante Begriffe: meshtastic köln, meshtastic düsseldorf, meshtastic bonn, meshtastic aachen, meshtastic wuppertal, meshtastic leverkusen, meshtastic krefeld, meshtastic mönchengladbach, meshtastic neuss, meshtastic rhein‑erft, meshtastic rhein‑sieg, meshtastic bergisch gladbach, meshtastic rheinland.

## Fragen? {#faq}

- Funkregeln beachten (Duty Cycle im 868‑MHz‑Band).
- Probleme beim Einstieg? Frag in der WhatsApp‑Gruppe.
- Du hast Tipps oder möchtest mitmachen? PRs willkommen!

> Diese Seite ist bewusst minimal und leicht zu pflegen. Beiträge gerne per Pull Request!
{: .warning }
