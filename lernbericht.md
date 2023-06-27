# Lern-Bericht

Gruppe Guava | Nicola, Gabriel, Kilian

## Einleitung

Wir haben eine Website erstellt, auf der umfassende Informationen über ein fiktives Chicken-Restaurant zu finden sind.

## Was habe ich gelernt?

In diesem Projekt haben wir gelernt, wie man eine Navbar erstellt, die beim Überfahren mit der Maus eine animierte Reaktion zeigt.

## Beschreibung

Das GIF zeigt unsere implementierte Website mit der funktionierenden Navbar.

![navbar](https://github.com/HeliumxD/La-1600-Guava/assets/111046337/50699476-3a5d-4581-96dc-59c1f9dec028)



Hier ist der CSS-Code, den wir für die Gestaltung der Navbar verwendet haben.

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
Der gegebene CSS-Code implementiert eine stilvolle Navbar für eine Website. Die Navbar wird horizontal zentriert, hat eine bestimmte Breite und einen definierten Innenabstand. Die Listenelemente in der Navbar werden nebeneinander angezeigt und haben einen Abstand voneinander. Zusätzlich gibt es einen visuellen Effekt, der aktiviert wird, wenn man mit der Maus über die Listenelemente fährt.

Der visuelle Effekt wird durch den Einsatz von CSS-Pseudo-Elementen und Übergangseigenschaften erzeugt. Für jedes Listenelement in der Navbar wird ein zusätzliches Element erstellt, das den animierten Balken repräsentiert. Anfangs ist der Balken unsichtbar und hat eine Breite von 0.
Wenn der Mauszeiger über ein Listenelement schwebt, wird die Breite des Balkens auf 100% erhöht. Dies geschieht allmählich und mit einer fliessenden Animation, die dem Element eine markante Betonung verleiht.
Auf diese Weise entsteht der visuelle Effekt, dass der Balken beim Überfahren mit der Maus von links nach rechts wächst und dem Listenelement eine ansprechende Darstellung verleiht.

## Verifikation

Wir haben gelernt, wie man den visuellen Effekt eines wachsenden Balkens erzeugt, wenn der Mauszeiger über ein Listenelement schwebt, indem ein Pseudoelement, in diesem Fall "::after" und Übergangseigenschaften Transitions verwendet wird.
Ausserdem haben wir gelernt, wie man durch die Verwendung von Flexbox, ein Element horizontal ausrichtet und gleichmässig verteilt.

# Reflexion zum Arbeitsprozess

Wir haben während des gesamten Projekts effizient gearbeitet. Wir kamen gut voran und konnten uns gut gegenseitig helfen.

Es gab gelegentlich Probleme bei der Kommunikation und der Zuweisung von Aufgaben. Leider haben wir manche Code-Abschnitte doppelt geschrieben und dafür andere gar nicht, wo wir später dann noch nachholen mussten.

**VBV**: Ein Verbesserungsvorschlag könnte darin bestehen, die Anzahl der Teammeetings zu erhöhen, um den Fortschritt und den aktuellen Stand der Dinge besser miteinander zu kommunizieren.
