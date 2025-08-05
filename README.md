# LUH Poster LaTeX Template

Dies ist ein Template für ein Poster mit LaTeX im Stil des Corporate Designs der Leibniz Universität Hannover.

![](example_poster.png)

## Schriftart Rotis verwenden

Die Hausschrift Rotis kann unter https://www.intern.uni-hannover.de/de/themenbereiche/oeffentlichkeitsarbeit-marketing/design/logo-und-hausschrift/ heruntergeladen werden und als OpenType font im Ordner `font/rotis/` installiert werden.

Ggf. muss vor dem Erzeugen der PDF einmal folgender Befehl ausgeführt werden:
`luaotfload-tool --update`
Dieser bereitet die Schriftart für LuaLaTeX vor.

## PDF erzeugen

Die Erzeugung wurde nur mit TeX Live 2022 getestet, vorherige Versionen enthalten eventuell nicht alle notwendigen Pakete. 

Die PDF kann auf der Kommandozeile mit folgendem Befehl erzeugt werden:
`lualatex example_poster.tex` oder `latexmk -pdflua example_poster.tex`

Bei grafischen Oberflächen, wie zum Beispiel TeXstudio, muss ggf. die Umgebung auf LuaLaTeX gestellt werden (statt LaTeX).

