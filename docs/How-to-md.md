# Nutzung von Docfx und GitHub Pages

## Prerequisites

Das Repository besitzt zwei branches.
Der *main*-branch dient zu Änderungen von Inhalten.
Der *gh-pages*-branch deployed die Webseite.

Möglicherweise muss nach [*Schritt 1*](#1-github-repo-lokal-in-visual-studio-code-öffnen) ein lokaler *build* durchgeführt werden.

## Standard Updateprozess

1. Änderungen über VSC vornehmen und speichern
2. lokalen *build* mithilfe der *docfx.json*-Datei ausführen
   1. docfx docfx.json
3. Änderungen über VSC in den *Main-branch* committen.
<br>

## Erstellung einer neuen Page mit docfx
<br>

### 1. GitHub Repo lokal in Visual Studio Code öffnen

Das Repository mit der Dokumentation auf gewohntem Wege in VSC klonen und abspeichern.
<br>

### 2. Erstellen einer neuen Markdown Seite

Zuerst muss eine Markdown-Datei im Ordner */_site/docs* erstellt werden.
Als Benennung für Datei zur App-Dokumentation bietet sich *LeBit-App-Name.md* an.
Die erstellte Datei kann mit der Dokumentation gefüllt werden.<br>
Informationen zur Syntax und Einfügen von Bildern sind [*hier*](#markdown-syntax)  zu finden. <br>

### 3. Aufnahme in das Inhaltsverzeichnis

Damit die Page in das Inhaltsverzeichnis aufgenommen wird, muss die Datei in der Table of Contents Datei */_site/docs/toc.yml* hnzugefügt werden. <br>
 

Bsp.:

```yaml

- name: How to Markdown (Anzeige im ToC)
  href: How-to-md.md (Dateiname, Case Sensitive)

```

### 4. Lokalen *Build* durchführen

Durch den lokalen *build* werden das Inhaltsverzeichnis und die Markdown Dateien in *html*-Pages umgewandelt, die vom Browser angezeigt werden können. <br><br>

In Powershell muss zuerst zum Ordner verwiesen werden und daraufhin kann folgende Syntax zum *Build* ausgeführt werden.

```shell

docfx.exe

```
Dies führt den lokalen *build* der Seite aus.

Alternativ kann mit dem Command

```shell

docfx docfx.json --serve

```

die Webseite im Localhost geöffnet werden. <br>
[*Localhost:8080*](Localhost:8080)
<br>
### 5. GitHub *build*

Der *build*  der GitHub Pages Seite wird beim pushen von Changes automatisch durch die GitHub Action in *main.yml* durchgeführt.
<br>

### Markdown Syntax

Im Internet gibt es einige Syntax Cheatsheets, die bei der Erfassung helfen können. Beispielsweise [*hier*](https://www.markdownguide.org/basic-syntax/).
<br>

#### Bilder einbeziehen

Zum Nutzen von Bildern in der Dokumentation müssen diese im Ordner */_site/images/* gespeichert werden.

Als Dateiformate werden *.jpg*, *.jpeg* und *.png* verarbeitet. Dateiformate können in der *docfx.json*-Datei hinzugefügt werden.

Damit die Bilder richtig auf der Webseite angezeigt werden ist folgende Syntax notwendig.

```markdown

	![Alternativtext](../images/"Name des Bildes")
    <figcaption>Bildunterschrift</figcaption>   

```

Beispiel

```markdown


	![Bild von Hund](../images/Hund.jpg)
    <figcaption>Hund</figcaption>  

```

#### Alerts

> [!NOTE]
> Dies sollte als Notiz angezeigt werden.

```
> [!NOTE]
> Dies sollte als Notiz angezeigt werden.
```

>[!TIP]
> Dies ist ein Tipp.

```
>[!TIP]
> Dies ist ein Tipp.
```

>[!IMPORTANT]
>Sehr wichtige Informationen befinden sich hier.

```
>[!IMPORTANT]
> Sehr wichtige Informationen befinden sich hier.
```

>[!CAUTION]
> Achtung das ist ein Test!

```
>[!CAUTION]
> Achtung das ist ein Test!
```

>[!WARNING]
> Letzte Warnung!

```
>[!WARNING]
> Letzte Warnung!
```