# Ineffiziente Wintertransfers
## Auswirkungen von Wintertransfers auf die Leistungen der Super-League-Teams seit 2005¶

## Ausgangslage
Wintertransfers haben in Fussballkreisen einen schlechten Ruf. Da Verträge normalerweise von Saison zu Saison (also von Sommer zu Sommer) laufen, entspringen Wechsel im Winter oft kurzfristigen Entscheiden oder gar Notsituationen (sportlich schlingernde Clubs, unzufriedene Spieler,...). Doch haben die Wintertransfers ihren schlechten Ruf auch wirklich verdient? 

## These
Fussballclubs, die im Winter stark an Wert zulegen (also entweder viele Transfers tätigten oder einen ganz wertvollen Spieler verpflichten), können dies sportlich in der Rückrunde nicht in Punkte ummünzen.

## Hinweis zum zweiten Projekt zu Zuschauerzahlen (Zuschauerzahlen.ipynb)
Zunächst hatte ich ein anderes Projekt als Diplomarbeit geplant. Anhand von Wetter-, Zuschauer- und Spieldaten wollte ich aufzeigen, wie stark sich das Wetter (und andere Faktoren wie Erfolg, Spielbeginn, Spieltag, TV-Spiel, etc.) sich auf die Zuschauerzahlen in der Super League auswirkt. Die Wetterdaten habe ich von Meteo Swiss erhalten. Viel Merge-Arbeit und Daten-Cleaning stellten sich aber als sehr zeitaufwändig heraus. Noch immer ist es mein Ziel, das Zuschauer-Projekt zu beenden - für die Diplomarbeit hat es aber nicht gereicht. Ich reiche nun das Wintertransfer-Projekt ein, das ich auf Ende des Wintertransferfensters Mitte Februar ohnehin publizierte. Die Spieldaten, die ich fürs Wintertransfer-Projekt verwende, stammen vom Zuschauer-Projekt. Deshalb habe ich den Code von "Zuschauerzahlen.ibynb" auch angehängt.

## Vorgehen
Anhand der Daten der Fussball-Plattform transfermarkt.ch habe ich die Wintertransfers in der Super League der vergangenen 13 Saisons (seit 2005) untersucht. Der Grund für die zeitlich eher enge Beschränkung: In den Saisons vor 2005 sind die Transferdaten lückenhaft.

Transfermarkt.ch schätzt die Werte aller Spieler. Diese Schätzungen weisen gemäss Fussballkennern grundsätzlich eine hohe Genauigkeit auf. Anhand dieser Werte rechne ich Wertsteigerungen bzw. -verminderungen der Teams aufgrund der Wintertransfers aus und vergleiche sie mit den Hin- und Rückrundenresultaten in der betreffenden Saison.

Insgesamt wären es also 130 Fälle von Team-Wintertransfers, die ich untersuche (13 Saisons à 10 Teams. In wirklichkeit sind es aber nur 129. Denn eine Besonderheit nimmt die Saison 2011/12 ein: Neuenburg Xamax wurde damals wegen finanzieller Verfehlungen im Winter, also Mitte Saison, zwangsrelegiert. Für die nicht ausgetragenen Spiele gegen Xamax in jener Rückrunde habe ich allen anderen Teams drei Punkten zugeschrieben. Würde ich das nicht tun, wiesen die Teams in jener Saison tendenziell alle schwächere Rückrunden auf - was meiner These ungerechtfertigt Vorschub leisten würde.


## Abschätzen von Aufwand/Ertrag

Der Aufwand für das Scrapen ist überschaubar, da die Daten auf Transfermarkt.com schon gut strukturiert sind. Die Daten für die Spiele/Punkte der Teams sind zudem bereits von einem anderen Projekt (Zuschauerzahlen.ipynb, ebenfalls im Repository) vorhanden. Aufwändig dürfte aber das Zusammenführen und Vergleichen der beiden Datensätze sein. Der Aufwand dürfte sich aber auch deshalb lohnen, weil die Datensätze (und die Scraping-Technik) für ähnliche Projekte wieder zur Anwendung kommen können.

## Knackpunkt
Das Zusammenführen von Spiel-/Punktedaten mit den Transferdaten war letzlich tatsächlich ein sehr aufwändiger Schritt - und gewissermassen eine Hauptschwierigkeit. Ein anderer Knackpunkt war die grafische Aufbereitung auf wenig Platz, zusammen mit dem Infografikteam.

## Briefingpersonen
Der Spielerberater Michele Cedrola sowie der FCSG-Sportchef Alain Sutter haben mit ihren Aussagen die These zu den Wintertransfers gestützt: Wechsel im Winter sind selten von Erfolg gekrönt. 

