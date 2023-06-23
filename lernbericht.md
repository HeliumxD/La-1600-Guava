# Lern-Bericht

Von der Gruppe Guava 

## Einleitung

Wir haben eine Website erstellt, auf der umfassende Informationen über ein fiktives Chicken-Restaurant zu finden sind.

## Was habe ich gelernt?

In diesem Projekt haben wir gelernt, wie man eine Navbar erstellt, die beim Überfahren mit der Maus eine animierte Reaktion zeigt.

## Beschreibung

✍️ Verwenden Sie drei verschiedene Medien, um zu zeigen, was Sie gelernt haben. Zum Beispiel:

![LA_1600 website](https://github.com/HeliumxD/La-1600-Guava/assets/111046337/e83180d7-d9dc-41c7-8d95-26bde51ee546)

```css
.navbar {
    width: 85%;
    margin: auto;               
    padding: 35px 0;                /* Grösse und Positionierung der Navbar definieren.*/
    display: flex;
    align-items:center;
    justify-content:space-between ;

}
.logo{ 
    width: 120px;
    cursor: pointer;

}

.navbar ul li { 

    list-style: none;
    display:inline-block;       
    margin: 0 20px;                 /* Positionierung der Navbar. */
    position: relative;
}


.navbar ul li a{
    text-decoration: none;
    color: #fff;                  /*  Entfernen der Unterstreichung, Textfarbe auf Weiß, Text in Großbuchstaben umwandeln.*/
    text-transform:uppercase; 
}

.navbar ul li::after{
    content:'';
    height: 3px;
    width:0;
    background:#009688;       /* Pseudo-Element für einen Balken nach jedem Listenelement: Unsichtbarer Inhalt und zusätzlich ein Übergangseffekt von 0,5 Sekunden. */
    position: absolute;
    left:0;
    bottom:-10px;
    transition:0.5s;
    

}


.navbar ul li:hover::after{
                            
    width: 100% ;           /* Styling für den Balken, wenn das Listenelement beim Überfahren mit der Maus: Breite auf 100% setzen. */
    
}

``` 
* Eine textliche Beschreibung
* Ein deutliches, aussagekräftiges Bild oder eine kommentierte Bildschirm-Aufnahme
* Ein gut dokumentierter Code-Fetzen

## Verifikation

✍️ Erklären Sie kurz und bündig, inwiefern die von Ihnen verwendeten Medien zeigen, was Sie gelernt haben.

# Reflektion zum Arbeitsprozess

👍 Überlegen Sie sich jeweils etwas, was gut an Ihrer Arbeit lief; 

👎 und etwas, was nicht gut lief.

**VBV**: ✍️ Formulieren Sie davon ausgehend einen *handelbaren* Verbesserungsvorschlag.
