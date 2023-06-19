# Projekt-Dokumentation: Kochrezept-Website

Melon: Müller, Erismann, Bächli, Manser

| Datum | Version | Zusammenfassung                                              |
| ----- | ------- | ------------------------------------------------------------ |
| 2.5.2023| 0.0.1   | Grundriss der Webseite erstellt |
| 9.5.2023| 0.0.2   | Settings Menü erstellt, Webseite besser gestaltet |
| 16.5.2023| 0.0.3  | Webseite mit mehreren Rezepten gefüllt, neu gestaltet |
| 23.5.2023| 0.0.4  | Darkmode Setting angefangen zu implementieren  |
| 30.5.2023| 0.0.5  | Filtersystem Angefangen, Darkmode Fertig gemacht  |
| 6.6.2023| 0.0.6  | Filtersystem Fertig gemacht  |
| 13.6.23| 1.0.0  | Projekt fertig gemacht|
## 1 Informieren

### 1.1 Ihr Projekt

Unsere Kochrezept-Website bietet Nutzern eine umfassende Sammlung von Rezepten für eine Vielzahl von Gerichten aus verschiedenen Küchen der Welt.

### 1.2 User Stories

| US-№ | Verbindlichkeit | Typ  | Beschreibung                                                                                     |
| ---- | --------------- | ---- | ------------------------------------------------------------------------------------------------ |
| 1    | Muss            | Funktional | Als ein Nutzer möchte ich nach Rezepten suchen können, um gezielt ein bestimmtes Gericht zu finden. |
| 2    | Muss            | Funktional | Als ein Nutzer möchte ich in der Lage sein, Rezepte zu filtern und zu sortieren, um sie einfacher zu durchsuchen. |
| 3    | Muss            | Funktional | Als ein Nutzer möchte ich in der Lage sein, ein Rezept anzuzeigen und detaillierte Anweisungen zum Kochen zu erhalten. |
| 4    | Muss            | Funktional | Als ein Nutzer möchte ich in der Lage sein, meine Lieblingsrezepte zu speichern und später darauf zurückzugreifen. |
| 5    | Kann            | Funktional | Als ein Nutzer möchte ich Rezepte bewerten und Kommentare hinterlassen können, um anderen Nutzern Feedback zu geben. |
| 6    | Kann            | Qualität   | Als ein Nutzer möchte ich sicherstellen können, dass die Website auf verschiedenen Geräten und Browsern einwandfrei funktioniert. |
| 7    | Muss            | Qualität   | Als Nutzer möchte ich in den Darkmode wechseln können, damit ich die Website anders sehen kann.|
| 8    | Muss            | Funktional | Als Nutzer möchte ich die Sprache ändern können, um das Rezept auch in einer anderen Sprache nutzen zu können.|
| 9    | kann            | Qualität   | Als Nutzer möchte ich, dass die Webseite Visuel schön und simpel gestaltet ist.|
| 10   | muss            | Funktional | Als Nutzer möchte ich die Mengenangaben in richtigen Masseinheiten angezeigt haben, damit ich das Rezept richtig machen kann. |
| 11   | kann            | Qualität   | Als ein Benutzer möchte ich die benötigte zeit für ein Rezept sehen, um abschätzen zu können, wie viel Zeit ich einplanen muss. |
| 12   | muss            | Qualität   | Zutaten sollen nacheinander eingeblendet werden |
| 13   | muss            | Funktional | Als Nutzer möchte ich Suchfilter verwenden können, damit ich meine Rezepte schneller finden kann. |
| 14 |  muss             | Funktional  | Als Benutzer möchte ich die Rezepte in einem Drop Down Menu angezeigt haben, damit ich mehrere Rezeptnamen auf einmal sehen kann.|
 

 

### 1.3 Testfälle

| TC-№ | Ausgangslage | Eingabe | Erwartete Ausgabe                                                                                                          |
| ---- | ------------ | ------- | -------------------------------------------------------------------------------------------------------------------------- |
| 1.1  | Website-Startseite | Suchbegriff "Kuchen" | Es werden alle Rezepte aufgelistet, die das Keyword "Kuchen" enthalten. |
| 1.2  | Suchergebnisseite | "Kuchen"-Rezept auswählen | Das Kuchen-Rezept wird angezeigt, einschließlich einer Liste aller erforderlichen Zutaten und einer schrittweisen Anleitung zum Kochen. |
| 2.1  | Suchergebnisseite | Filtern nach Art des Gerichts | Nur Rezepte der ausgewählten Art werden angezeigt. |
| 2.2  | Suchergebnisseite | Sortieren nach Bewertung | Die höchstbewerteten Rezepte werden zuerst aufgelistet. |
| 3.1  | Rezeptseite | Klicken auf den "Zutaten"-Tab | Eine Liste aller erforderlichen Zutaten wird angezeigt. |
| 3.2  | Rezeptseite | Klicken auf den "Anleitung"-Tab | Eine schrittweise Anleitung zum Kochen des Gerichts wird angezeigt. |
| 4.1  | Rezeptseite | Klicken auf "Favoriten hinzufügen" | Das Rezept wird zu den Favoriten des Benutzers hinzugefügt. |
| 4.2  | Website-Startseite | Klicken auf "Favoriten" | Eine Liste aller vom Benutzer gespeicherten Rezepte wird angezeigt. |
| 5.1  | Rezeptseite | Klicken auf "Bewertung abgeben" | Eine Bewertung und ein Kommentar können eingegeben und gespeichert werden. |
| 6.1  | Anderes Gerät  | 
| 7.1  | Website starten| auf Darkmode klicken | Die Website wird in den Darkmode gestellt. |
| 8.1  | Website starten | klicken auf französisch klicken | die Website wird auf französisch angezeigt. |
| 10.1  | Website starten  | Rezept auswählen | Mengenangaben für das Rezept werden angezeigt. |
| 11.1 | Website starten | Rezept auswählen  | Die benötigte Zeit wird angezeigt. |
| 12.1| Website gestartet| Filter auswählen| Rezepte werden in einem Drop Down angezeigt|


### 1.4 Diagramme
![LA_1600_USECASE](https://github.com/DaMu14/LA1600/assets/110892537/9c0eb5ac-47ef-4c79-b124-69627c4f5af9)
![LA_1600_SKIZZE](https://github.com/DaMu14/LA1600/assets/110892330/3421a289-03a4-4243-b561-c1aabb3161dc)



## 2 Planen 

| AP-№ |   Frist   |    Zuständig    |                   Beschreibung                   | geplante Zeit |
|:----:|:---------:|:---------------:|:-----------------------------------------------:|:-------------:|
| 1.A  | 2.5.23    | Müller          | Implementierung der Rezept-Suchfunktion          | 45            |
| 1.B  | 2.5.23    | Erisman         | Implementierung der Filter- und Sortierfunktionen | 2x45          |
| 1.C  | 2.5.23    | Bächli          | Implementierung der Rezeptdetailansicht          | 45            |
| 4.A  | 9.5.23    | Müller          | Implementierung der Favoritenfunktion            | 45            |
| 5.A  | 16.5.23   | Manser, Müller  | Implementierung der Bewertungs- und Kommentarfunktion | 2x45       |
| 6.A  | 16.5.23   | Erisman, Bächli | Überprüfung der Website-Kompatibilität auf verschiedenen Geräten und Browsern | 2x45 |
| 7.A  | 30.5.23   | Manser          | Implementierung der Darkmode-Funktion             | 45            |
| 8.A  | 30.5.23   | Erisman, Bächli | Implementierung der Sprachauswahl-Funktion        | 2x45          |
| 9.A  | 6.6.23    | Müller          | Gestaltung der Website-Benutzeroberfläche         | 3x45          |
| 10.A | 6.6.23    | Bächli          | Anpassung der Mengenangaben in den Rezepten        | 45            |
| 11.A | 13.6.23   | Manser          | Anzeige der benötigten Zeit für ein Rezept         | 45            |
| 12.A | 13.6.23   | Erisman         | Einblenden der Zutaten nacheinander                | 45            |
| 13.A | 13.6.23   | Bächli, Müller  | Implementierung der Suchfilterfunktion             | 2x45          |
| 14.A | 13.6.23   | Erisman, Manser | Implementierung des Drop-Down-Menüs               | 2x45          |
 


Total: 

 

## 3 Entscheiden

✍️ Dokumentieren Sie hier Ihre Entscheidungen und Annahmen, die Sie im Bezug auf Ihre User Stories und die Implementierung getroffen haben.

## 4 Realisieren

| AP-№ | Datum | Zuständig | geplante Zeit | tatsächliche Zeit |
| ---- | ----- | --------- | ------------- | ----------------- |
| 1.A  |9.5.23| Bächli, Manser | 45              |    45               |
| 1.B     |9.5.23| Bächli, Müller |  45         |       45        |            
| 2.A     |9.5.23| Erisman |       2x45    |     45          |              
| 2.A     |16.5.23| Erisman |     2x45      |     45          |           
| 3.A     |23.5.23| Erisman |    45       |    300           | 


✍️ Tragen Sie jedes Mal, wenn Sie ein Arbeitspaket abschließen, hier ein, wie lang Sie effektiv dafür hatten.

## 5 Kontrollieren

| TC-№ | Datum | Resultat | Tester |
| ---- | ----- | -------- | ------ |
| 1.1  | 13.6.23|  keine Suchleiste| Müller|
|1.2|  13.6.23| Rezept wird angezeigt| Müller|
| 2.1 | 13.6.23| Filtersystem ist vorhanden funktioniert nicht| Müller|
| 2.2 | 13.6.23| nicht möglich| Müller|
|3.1 |13.6.23| Liste wird angezeigt| Müller|
| 3.2 | 13.6.23| Anleitung wird angezeigt| Müller|
| 4.1|13.6.23| nicht möglich| Müller|
| 4.2|13.6.23| nicht vorhanden| Müller|
| 5.1| 13.6.23| nicht möglich| Müller|
|6.1 | 13.6.23| ist auf mobile Grät möglich| Müller|
|7.1| 13.6.23| ist in Dark Mode sichtbar| Müller|
| 8.1 | 13.6.23 |nicht möglich| Müller|
| 10.1 | 13.6.23 | wird angezeigt | Müller|
| 11.1 | 13.6.23 | Zeit wird angezeigt| Müller|
| 12.1 | 13.6.23 |


Wir haben viele Testfälle geschafft sodass die Website um Grunde funktioniert. Wir haben einfach nicht alle Testfälle geschafft.

## 6 Auswerten

✍️ Fügen Sie hier eine Verknüpfung zu Ihrem Lern-Bericht ein.
 
