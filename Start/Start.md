# Obsidian Basics

Obsidian ist ein **Markdown** Editor. [Siehe Obsidian Hilfeseite für Markdown Syntax](https://help.obsidian.md/Editing+and+formatting/Basic+formatting+syntax)

Obsidian speichert Markdowndateien auf eurem Rechner lokal. Die Funktionalitäten werden in Obsidian mit Hilfe von Plugins (Offizielle & Community) erweitert z.B. für [[Excalidraw]] oder [[Zotero]]

## Verlinkungen

Obsidian ist besonders stark darin Verlinkungen herzustellen. 

Wird ein Text in zwei eckige Klammern gesetzt so `[[Beispiellink]]` wird ein Link erzeugt: [[Beispiellink]]

Falls die Datei noch nicht erstellt wird, so erfolgt dies spätestens wenn man auf den Link klickt 

## LaTeX

Innerhalb von Obsidian kann LaTeX verwendet werden.  Im Plugin [[Exalidraw]]
zum erstelle von Zeichnungen kann ebenfalls LaTeX verwendet werden.

Inline LaTeX: `$a^2 + b^2 = c^2$` : $a^2 + b^2 = c^2$

Block LaTex: `$$a^2 + b^2 = c^2$$` : $$a^2 + b^2 = c^2$$
Mit dem `\tag` Befehl innerhalb des LaTeX Blocks können Referenzen erzeugt werden.
$$a^2 + b^2 = c^2\tag{1}$$
Das **Plugin LaTeX Suite** ermöglicht einfacheres Schreiben von mathematischen Formeln durch Abkürzungen

## Tabellen

Dank dem Plugin **Advanced Tables** können Markdown Tabellen sehr bequem erstellt werden:

| Überschrift 1 | Überschrift 2 |
| ---- | ---- |
| Inhalt 1     |   Inhalt 2   |

## Callouts

Für besondere Aufmerksamkeit gibt es verschiedene Callouts:

> [!question] Frage/Hilfe/FAQ
> Beispiel für eine Frage

> [!todo] Info
> Hier ist eine Information

... und viele mehr in [Obsidian Hilfe zu Callouts](https://help.obsidian.md/Editing+and+formatting/Callouts)

# Zeichnen mit Excalidraw

Mit dem roten Button des Stiftes in dem Menü auf der linken Seite kann eine [[Excalidraw]] Zeichnung direkt in die aktuelle Seite eingefügt und geöffnet werden. Diese wird dann im Ordner `Excalidraw` gespeichert

![[Beispiel.excalidraw|700]]

# Literatur mit Zotero

Es kann eine eigene Zoterodatenbank mit Obsidian verknüpft werden und z.B. auch automatisch alle pdf's und Markierungen in Obsidian importiert werden. Der Workflow ist sehr gut in diesem Video beschrieben:

<iframe title="So verbindest du Zotero mit deinem Obsidian Vault" src="https://www.youtube.com/embed/0Ki7FVqIW5c?feature=oembed" height="113" width="200" allowfullscreen="" allow="fullscreen" style="aspect-ratio: 1.76991 / 1; width: 100%; height: 100%;"></iframe>
# Präsentationen mit Obsidian

[[Standardpräsentationen]]

Präsentationen mit dem Plugin [[Advanced Slides]]

# ToDos

Syntax:
```
- [ ] Aufgabe 
```

- [ ] Aufgabe nicht erfüllt
- [x] Aufgabe erfüllt ✅ 2023-04-27

**Plugin Checklist** - ToDo's in der Seitenleiste darstellen (hastag Sortierung aus)
**Plugin Tasks** - Deadlines uvm. hinzufügen 

# Nützliche Plugins

## Folder Note

Plugin was eine Notiz für einen Ordner erstellt (über gleichen Namen zugeordnet wie hier in dem Beispiel **Start**). Dies kann sehr gut verwendet werden um **Maps of Content**, also Übersichten zu erstellen.

