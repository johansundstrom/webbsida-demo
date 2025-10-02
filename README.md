# Konstruera webbsida med VS Code

Målet här är att påvisa tillvägagångssättet och att skapa en enkel webbsida mha VS Code. Användning av Emmet samt extensions beskrivs också här.

## Förutsättningar

I denna anvisning används följande extensions. Kontrollera att dessa är installerade annars installera dem.

* Live server (Ritwick Dey)
* Lorem Ipsum (Daniel Imms)

## Emmet

Skapa en ny fil och ge den namnet ```index.html```. I dokumentfönstret, skriv utropstecken och tryck [tab]

```html
!
```

Emmet-uttrycket expanderas till följande...

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

Gå in mellan ```<body>```-elementen och skriv...

```emmet
h1
```

När ```Emmet Abbrivation``` visas, tryck [tab] för att expandera. Följande kommer att visas...

```html
<h1></h1>
```

Ange en lämplig rubrik inom ```<h1>...</h1>```

Hitta Emmet Lathund https://docs.emmet.io/cheat-sheet/

## Lorem-tillägg

På nästa rad skriv...

```html
p>lorem
```

```Emmet Abbrivation``` visas, tryck [tab] för att expandera. Följande kommer att visas...

```html
<p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Earum reiciendis tenetur doloremque quas excepturi dicta esse ipsum porro! Nisi esse provident maxime natus quos ab consequuntur quaerat, ipsa quia hic.</p>
```
## Command Palette

Starta *Command Palette* genom att för...

* PC - tryck Ctrl + Shift + P
* Mac - Command (⌘) + Shift + P

## Live Server

Eftersom Live Server tillägget är installerat går det nu att i *Command Palette* skriva ```live``` och välja ```Live Server: Open with Live Server``` och trycka [enter]

Nu visas resultatet av koden i webbläsaren.

![Alt text](/assets/images/web-result.jpg "Simpel webbsida")