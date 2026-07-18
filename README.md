# Projektarbeit ERP-Systeme — LaTeX-Quellen

LaTeX-Quelle der Projektarbeit *„Analyse von Prozessineffizienzen durch Process Mining
in ERP-Systemen: Eine Untersuchung der Datenstrukturen und Algorithmen am Beispiel des
Order-to-Cash-Prozesses"* (FOM, Modul ERP-Systeme, SoSe 2026).

Dieses Repository ist mit einem **Overleaf-Projekt** synchronisiert. Hauptdokument: `main.tex`.

## Struktur

| Datei/Ordner | Inhalt |
|---|---|
| `main.tex` | Hauptdatei: Präambel, Titelblatt, Verzeichnisse, bindet alles ein |
| `titlepage.tex` | Titelblatt |
| `abkuerzungsverzeichnis.tex` | Abkürzungsverzeichnis |
| `chapters/sec_01.tex` … `sec_08.tex` | Kapitel 1–8 (Fließtext, Tabellen, Abbildungen, Fußnoten) |
| `anhang.tex` | Anhang A1–A3 |
| `literatur.tex` | Literaturverzeichnis |
| `kiverzeichnis.tex` | KI-Verzeichnis (Pflichtangabe) |
| `figures/` | Abbildungen 1–7 (PNG) |

## Titelblatt ausfüllen

Die drei offenen Platzhalter stehen als Befehle oben in `main.tex` — einmal ändern, überall wirksam:

```latex
\newcommand{\standort}{[Standort]}
\newcommand{\studiengang}{[Studiengang]}
\newcommand{\matrikelnummer}{[Matrikelnummer]}
```

## Zitierweise

Deutsche Zitierweise mit Fußnoten (`\footnote{}`); das Literaturverzeichnis ist manuell
in `literatur.tex` gesetzt. Kompiliert mit `pdflatex` (Overleaf-Standard).

Der Praxisteil (Datensimulation und Process-Mining-Analyse) liegt im separaten Repository
`ERP_O2C_Process_Mining`.
