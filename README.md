# Ineffiziente Wintertransfers
## Auswirkungen von Wintertransfers auf die Leistungen der Super-League-Teams seit 2005¶

## Ausgangslage
Wintertransfers werden in Fussballkreisen kritischer beäugt als Sommertransfers. Da Verträge normalerweise von Saison zu Saison (also von Sommer zu Sommer) laufen, entspringen Wechsel im Winter oft kurzfristigeren Entscheiden oder gar Notsituationen (sportlich schlingernde Clubs, unzufriedene Spieler,...). Doch haben die Wintertransfers ihren schlechten Ruf auch wirklich verdient? 

## These
Fussballclubs, die im Winter stark an Wert zulegen (also entweder viele Transfers tätigten oder einen ganz wertvollen Spieler verpflichten), können dies sportlich in der Rückrunde nicht in Punkte ummünzen.

## Hinweis zu zweitem Projekt zu Zuschauerzahlen (Zuschauerzahlen.ipynb)
Zunächst hatte ich ein anderes Projekt als Diplomarbeit geplant. Anhand von Wetterdaten und Zuschauerzahlen will ich aufzeigen, wie stark sich das Wetter (und andere Faktoren wie Erfolg, Spielbeginn, Spieltag, TV-Spiel, etc.) sich auf die Zuschauerzahlen auswirkt. Die Wetterdaten habe ich von Meteo Swiss erhalten. Sehr viel Merge-Arbeit und Daten-Cleaning hat mir das Leben aber schwer gemacht. Noch immer ist es mein Ziel, das Projekt zu beenden - für die Diplomarbeit hat es aber nicht gereicht. Da ich ohnehin zuvor schon das Wintertransfer-Projekt angegangen bin (dieses eilte, weil das Transferfenster Mitte Februar schloss), reiche ich dieses ein. Die Spieldaten, die ich fürs vorliegende Projekt brauche, stammen aber vom Zuschauer-Projekt. Deshalb habe ich jenes auch angehängt.

## Vorgehen
Anhand der Daten der Fussball-Plattform transfermarkt.ch werden die vergangenen 13 Saisons (seit 2005) untersucht. Der Grund für diese zeitlich eher enge Beschränkung: In den Saisons zuvor scheinen die Lücken der Transferdaten grösser zu werden.

Transfermarkt schätzt die Werte aller Spieler. Diese Schätzungen weisen gemäss Fussballkennern grundsätzlich eine hohe Genauigkeit auf. Anhand dieser Werte rechne ich Wertsteigerungen bzw. -verminderungen der Teams aus und vergleiche sie mit den Hin- und Rückrundenresultaten in der betreffenden Saison.

Insgesamt wären es also 130 Team-Wintertransfers, die ich untersuche (13 Saisons à 10 Teams. In wirklichkeit sind es aber nur 129. Denn eine Besonderheit nimmt die Saison 2011/12 ein: Neuenburg Xamax wurde damals wegen finanzieller Verfehlungen im Winter, als Mitte Saison, zwangsrelegiert. Die fehlenden Spiele gegen Xamax in jener Rückrunde habe ich allen anderen Teams mit drei Punkten berechnet. Würde ich das nicht tun, würden die Teams in jener Saison tendenziell alle schwächere Rückrunden aufweisen - was meiner These ungerechtfertigt Vorschub leisten würde.


## Abschätzen von Aufwand/Ertrag

Der Aufwand für das Scrapen ist grundsätzlich nicht allzu hoch, da die Daten auf Transfermarkt.com schon gut strukturiert sind. Wenn zudem in meinem Fall die Daten für die Erfolge/Punkte der Teams bereits von einem anderen Projekt (Zuschauerzahlen.ipynb, ebenfalls im Repository) vorhanden sind, ist der Aufwand überschaubar. 

## Knackpunkt
Das Zusammenführen von Spielen/Punkten mit den Transferdaten war letzlich dennoch sehr aufwändig. Die Daten dürften aber immer wieder auch für andere Projekte interessant sein, von daher dürfte sich der Aufwand dennnoch gelohnt haben. Anderer Knackpunkt war die grafische Aufbereitung - die im fertigen, vorliegenden Projekt wohl noch immer verbesserungswürdig wäre.

## Briefingpersonen
Spielerberater Michele Cedrola sowie FCSG-Sportchef Alain Sutter haben mit ihren Aussagen die These zu den Wintertransfers gestützt: Wechsel im Winter sind selten von Erfolg gekrönt.

