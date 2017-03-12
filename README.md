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

## Een beetje moeilijker

Natuurlijk is het leuk om het plaatje op de website te zetten. Stel je voor dat het een héél groot plaatje is, dan willen we daar ook de grootte van kunnen bepalen.

### Weet-je-datje

Een plaatje wordt altijd uitgedrukt in het aantal **pixels** in de **breedte** en in de **hoogte**. Een pixel ("px") is de eenheid voor beeldschermen. Jouw laptop beeldscherm is bijvoorbeeld 1024px breed. Dus als je een plaatje hebt van 600px breed, dan is dit plaatje meer dan de helft van je beeldscherm.

Het plaatje in deze oefening [`plaatje.jpg`](plaatje.jpg) is 160px breed en 160px hoog. In HTML kunnen we bij de `<img>` tag de argumenten `width` voor de breedte en `height` voor de hoogte meegeven.

Dus als wij het 100px breed en 100px hoog willen maken, kunnen we het volgende schrijven:

```
<html>
    <head></head>
    <body>
        Hallo Wereld!
        <img src="plaatje.jpg" width="100" height="100">
    </body>
</html>
```

Probeer maar eens. Het plaatje wordt zo kleiner gemaakt. Leuk hé.

Wat gebeurd er wanneer je het plaatje 50px breed maakt en 200px hoog? Is het dan nog steeds een mooi plaatje?
