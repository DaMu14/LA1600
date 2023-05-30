# Projekt-Dokumentation: Kochrezept-Website

Melon: Müller, Erismann, Bächli, Manser

| Datum | Version | Zusammenfassung                                              |
| ----- | ------- | ------------------------------------------------------------ |
| 2.5.2023| 0.0.1   | Grundriss der Webseite erstellt |
| 9.5.2023| 0.0.2   | Settings Menü erstellt, Webseite besser gestaltet |
| 16.5.2024| 0.0.3  | Webseite mit mehreren Rezepten gefüllt, neu gestaltet |
|       | 1.0.0   ||

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
| 7    | Muss            | Qualität   | Als Nutzer möchte ich in den Darkmode wechseln können.|
| 8    | Muss            | Funktional | Als Nutzer möchte ich die Sprache ändern können, um das Rezept auch in einer anderen Sprache nutzen zu können.|
| 9    | kann            | Qualität   | Als Nutzer möchte ich, dass die Webseite Visuel schön und simpel gestaltet ist.|
| 10   | muss             |             | Als Nutzer möchte ich die Mengenangaben in richtigen Masseinheiten angezeigt haben, damit ich das Rezept richtig machen kann. |
| 11   | kann            |             | Als ein Benutzer möchte ich die benötigte zeit für ein Rezept sehen, um abschätzen zu können, wie viel Zeit ich einplanen muss. |
| 12   |                 |             | |
 

### 1.3 Testfälle

| TC-№ | Ausgangslage | Eingabe | Erwartete Ausgabe                                                                                                          |
| ---- | ------------ | ------- | -------------------------------------------------------------------------------------------------------------------------- |
| 1.1  | Website-Startseite | Suchbegriff "Lasagne" | Es werden alle Rezepte aufgelistet, die das Keyword "Lasagne" enthalten. |
| 1.2  | Suchergebnisseite | "Lasagne"-Rezept auswählen | Das Lasagne-Rezept wird angezeigt, einschließlich einer Liste aller erforderlichen Zutaten und einer schrittweisen Anleitung zum Kochen. |
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


### 1.4 Diagramme
![LA_1600_USECASE](https://github.com/DaMu14/LA1600/assets/110892537/9c0eb5ac-47ef-4c79-b124-69627c4f5af9)



## 2 Planen 

| AP-№ | Frist | Zuständig | Beschreibung | geplante Zeit |
| ---- | ----- | --------- | ------------ | ------------- |
| 1.A  | 9.5.23| Bächli Manser| Erstellen der Userstories| 45|
| 1.B  | 9.5.23| Bächli, Müller| Erstellen der Testfälle | 45|
| 2.A  | 16.5.23|Erisman|Erstellen des Grundrisses der Website mithilfe von HTML und CSS|2x 45|
| 3.A  | 23.5.23|Erisman|Erstellen eines Dark Mode Switch| 45|
| 3.B  | 23.5.23|Erisman|Erstellen einer Suchleiste und eines Filtersystems| 4x45


Total: 

✍️ Die Nummer hat das Format `N.m`, wobei `N` die Nummer der User Story ist, auf die sich das Arbeitspaket bezieht, und `m` von `A` an nach oben buchstabiert. Beispiel: Das dritte Arbeitspaket, das die zweite User Story betrifft, hat also die Nummer `2.C`.

✍️ Ein Arbeitspaket sollte etwa 45' für eine Person in Anspruch nehmen. Die totale Anzahl Arbeitspakete sollte etwa Folgendem entsprechen: `Anzahl R-Sitzungen` ╳ `Anzahl Gruppenmitglieder` ╳ `4`. Wenn Sie also zu dritt an einem Projekt arbeiten, für welches zwei R-Sitzungen geplant sind, sollten Sie auf `2` ╳ `3` ╳`4` = `24` Arbeitspakete kommen. Sollten Sie merken, dass Sie hier nicht genügend Arbeitspakte haben, denken Sie sich weitere "Kann"-User Stories für Kapitel 1.2 aus.

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
| 1.1  |       |          |        |
| ...  |       |          |        |

✍️ Vergessen Sie nicht, ein Fazit hinzuzufügen, welches das Test-Ergebnis einordnet.

## 6 Auswerten

✍️ Fügen Sie hier eine Verknüpfung zu Ihrem Lern-Bericht ein.
schnäbi
