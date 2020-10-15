---
title: Praxis | Datenvisualisierung

header:
  image: "/assets/images/00-unit-splash.jpg"
  caption: 'Photo: [**Environmental Informatics Marburg**](https://www.flickr.com/environmentalinformatics-marburg/)'

---

***Visualisierung von Daten im Rahmen der Kommunikation und kritisch-reflexiven Analyse.***

Nach der Bearbeitung dieser Übung sollen Sie in der Lage sein

  * verschiedene Diagrammtypen zu unterscheiden,
  * Diagramme angemessen zu entwicklen,
  * Diagramme zu analysieren, 
  * Diagramme kritisch zu reflektieren.

Für die Bearbeitung dieser Aufgabe benötigen Sie

  * Tabellenkalkulationssoftware — z. B. [Microsoft Excel](http://office.microsoft.com/en-001/excel/){:target="_blank"}, [OpenOffice Calc](http://www.openoffice.org/product/calc.html){:target="_blank"}, [LibreOffice Calc](https://www.libreoffice.org/discover/calc/){:target="_blank"} oder [Google Sheets](https://support.google.com/docs/answer/7068618?visit_id=637377655720779457-1326340163&hl=en&rd=4){:target="_blank"}.
  * Klimastation Cölbe - ein Datensatz der Klimstation Cölbe des DWD (siehe Interner Datensatz Klimadaten (**Verlinkung führt ins Nichts**))

## Walter-Lieth-Diagramm

Walter-Lieth-Diagramme sind trotzt aller Ungenauigkeit immer noch ein beliebtes Darstellungsformat für die hydroklimatologische Charakterisierung eines Ortes in Schulbüchern und Atlanten. Im Rahmen dieses Arbeitsblatts sollen Sie sowohl das hygrische Klima mittels eines Walter-Lieth-Diagramms als auch eine Verdunstungsabschätzung nach Haude vergleichen.

Bitte erstellen Sie ein Walter-Lieth-Diagramm auf Basis der langjährigen mittleren monatlichen Lufttemperatur und der langjährigen mittleren monatlichen Niederschlagssumme für die Station Cölbe auf Basis des in der zur Verfügung gestellten Datei enthaltenen Zeitraums. Lücken in der zur Verfügung gestellten Zeitserie müssen Sie dabei nicht explizit berücksichtigen.

## Verdunstung nach Haude

Zur Einschätzung des Walter-Lieth-Diagramms sollen Sie die potentielle Evapotranspiration nach einer Abschätzung von Haude berechnen und den Niederschlägen an der Station Cölbe gegenüberstellen.

Die Berechnung basiert auf dieser Formel:

PET = k ∗ e ∗ (1 - F / 100) [mm/d]
{: .notice--info}

mit PET als die potentielle Evapotranspiration, k als der Haude-Faktor (siehe Tabelle), e als der Sättigungsdampfdruck um 14:00 in hPa, F als die relative Luftfeuchte in Prozent.

Der Sättigungsdampfdruck e [hPa] kann nach der Magnus-Formel z. B. wie folgt berechnet werden:

e = 6,11 ∗ 10^(7,48 ∗ T / (237 + T)) [hPa]
{: .notice--info}

mit T als in diesem Falle die maximale Lufttemperatur in Grad Celsius.

Im Rahmen dieser Aufgabe können Sie anstelle der Temperatur um 14:00 Uhr die mittlere maximale Lufttemperatur sowie anstelle der Luftfeuchte um 14:00 Uhr die mittlere Luftfeuchte verwenden.

Die Haude-Faktoren sind in der nachfolgenden Tabelle dargestellt [Chmielewski et al. (1998)](https://www.zotero.org/envin_umr/items/2XPZN65N){:target="_blank"}:

Januar | 0,20 |
Februar | 0,20 |
März | 0,21 |
April | 0,29 |
Mai | 0,29 |
Juni | 0,28 |
Juli | 0,26 |
August | 0,25 |
September | 0,23 |
Oktober | 0,22 |
November | 0,20 |
Dezember | 0,20 |

Berechnen Sie die potentielle Evapotranspiration auf Basis der langjährigen Monatsmittel in mm und stellen Sie diese in einem Diagramm der langjährigen monatlichen Niederschlagssumme gegenüber.

Diskutieren Sie das Diagramm im Vergleich zur Walter-Lieth-Visualisierung im Rahmen einer kurzen, mündlichen Präsentation.