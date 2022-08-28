# Lern-Bericht
✍️ ggf. Ihr Gruppenname und Ihre Gruppenmitglieder

## Einleitung

Ich habe eine webbasierte Konfiguration eines Avatars in Pokémon Go implementiert.

## Was habe ich gelernt?

Ich kann mittels JSF ein Bild als Link in einer Website implementieren.

## Beschreibung

Ich habe ein Bild mit folgendem Code als Link erstellt. Wenn darauf geklickt wird, wird der Benutzer zur nächsten Webseite weitergeleitet.
```
<h:commandLink action="step2.xhtml" value="">
  <h:graphicImage library="img" name="h.png" width ="200px" />
</h:commandLink>
```
So sieht es auf der Webseite aus:
![grafik](https://user-images.githubusercontent.com/89772768/187091668-45c84c4f-23f6-48ba-a10a-73ef183489e7.png)

## Verifikation

Im Code ist zu sehen, wie die Grafik im Link eingebunden ist.

# Reflektion zum Arbeitsprozess

👍 Ich habe dieses Projekt von Grund auf neu erstellt und habe es das erste Mal geschafft, dass es beim ersten Mal durchführen keine Fehlanzeige gibt.

👎 Das verlinken des Bildes funktionierte zuerst nicht. Ich habe dann nach einigem Recherchieren herausgefunden, dass ich die library vergessen habe, anzugeben.

**VBV**: Das nächste Mal sollte ich mich über ein solches Problem direkt im Internet informieren gehen.
