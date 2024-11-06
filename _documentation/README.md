# Dokumentation

- [HTML Structure](#html)
- [Project Only HTML](#webseiten-referenz-only-html)
- [CSS Structure](#css)
- [Fontawsome anbinden](#einbindung-von-fontawsome)
- [Project with CSS](#webseiten-referenz-with-css)

---

### HTML
Um eine Visuelle Web-Oberfläche zu erstellen braucht es HTML. HTML auch genannt **Hypertext Markup Language**, wird für Statische Webseiten benutzt.

Um nun eine eigene HTML Seite zu bauen muss man ein .html File erstellen.
```bash
# Eingabe Windows
type con > index.html

# Eingabe Linux
touch index.html
```

Wenn es dir aufgefallen ist, nenne ich das Dokument `index.html`. Mit diesem Vorwort Index, sage ich dem Browser das in meinem Ordener, dieses File das Start, respektive **Index** Punkt ist.

Nun haben wir das Dokument erstellt und können die Struktur bauen. Jedes HTML File benutzt `<!DOCTYPE html>`. Aus dem Englischen übersetzt-Eine Dokumenttypdeklaration oder DOCTYPE ist eine Anweisung, die ein bestimmtes XML- oder SGML-Dokument mit einer Dokumenttypdefinition verknüpft.

```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
</head>
<body>
    
</body>
</html>
```

HTML benutzt

Mit [W3School](https://www.w3schools.com/html/default.asp) kann man alles über HTML sehr gut lernen und die einzelnen Tag lernen.

### Webseiten Referenz (only HTML)
![](/_images/Referenz-Bild-HTML.png)

---

# CSS

Um eine statische Webseite gestalterisch zu verhübschern, benötigt man CSS. CSS auch genannt **Cascading Stylesheet** ist eine Stylingsprache für HTML. Ansich kann man CSS nicht brauchen.

Um nun CSS auf einer HTML Seite anzuwenden, muss man diese Files verbinden. Man kann dies ausschliesslich im `Head` anbinden.

```html
<link rel="stylesheet" href="./style.css">
```

Wichtige Informaition für CSS:
- . = klasse (z.B. **class="box"**)
- #. = id (z.B. **id="spungbrett"**) 

Wie die CSS Syntax funktioniert, findet man unter [W3Schools](https://www.w3schools.com/css/default.asp).

# Einbindung von Fontawsome
[Fontawsome](https://fontawesome.com/?utm_source=v4_homepage&utm_medium=display&utm_campaign=fa5_released&utm_content=banner) ist eine Libary welche Icon durch CSS Styling erstellt hat und nun für uns zur Verfügung stellt. Man muss Grundsätzlich nur diese Datei runterladden und anbinden oder nur über ein Link anbinden.

```html
<link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.2.0/css/all.min.css"
        integrity="sha512-xh6O/CkQoPOWDdYTDqeRdPCVd1SpvCA9XXcUnZS2FmJNp1coAFzvtCN9BmamE+4aHK8yyUHUSCcJHgXloTyT2A=="
        crossorigin="anonymous" referrerpolicy="no-referrer">
```

# Webseiten Referenz (with CSS)
![](/_images/Referenz-Bild-CSS.png)