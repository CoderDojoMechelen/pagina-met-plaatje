# Pagina met plaatje

We bouwen verder op de vorige oefenening [Mijn eerste webpagina](https://github.com/CoderDojoMechelen/mijn-eerste-webpagina), dus laten we even kijken wat we nu al hebben.

```
<html>
    <head></head>
    <body>
        Hallo Wereld!
    </body>
</html>
```

## De opdracht

We gaan nu leren om een plaatje te plaatsen in de web pagina. 

## De aanpak

Een plaatje kan geplaatst worden met de `<img>` tag, alleen moeten we in de tag de locatie van het plaatje meegeven. Hiervoor gebruiken we het `src` argument.

Wanneer het plaatje op de zelfde locatie staat als de web pagina kun je het volgende schrijven:

```
<img src="plaatje.jpg">
```

Maar je kunt ook meteen een plaatje van het internet toevoegen:

```
<img src="http://codeweekeu.s3.amazonaws.com/event_picture/Website_logo.jpg">
```

Wil je het nu zelf proberen? Open dan je `hallo.html` van de [vorige oefening](https://github.com/CoderDojoMechelen/mijn-eerste-webpagina) en voeg het meegeleverde `plaatje.jpg` toe in deze pagina.

Als het goed is, moet je nu de volgende code hebben staan.

```
<html>
    <head></head>
    <body>
        Hallo Wereld!
        <img src="plaatje.jpg">
    </body>
</html>
```

Kijk eens aan, we hebben tekst en een plaatje al op onze webpagina staan!
