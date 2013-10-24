# Class Diagram

## Aufgabe:
> Analysieren Sie Ihre Use Cases und leiten Sie daraus Analyseklassen ab

## Classes:
Cocktailmischer
	steuert den Ablauf, weist "Dosierer" an, �berwacht die Waage
Rezeptbuch
	wird beim Starten mit allen mischbaren Rezepten geladen
Rezept
	enth�lt alle notwendigen Rezeptschritte
Rezeptschritt
	enth�lt "Zutat" und Menge
"Dosierer" -> Dosierer, Mischer, Stampfer, Mischbeh�lter
	on/off gibt "Zutat" in/aus dem Mischbeh�lter
Waage
	misst den Inhalt des Mischbeh�lters