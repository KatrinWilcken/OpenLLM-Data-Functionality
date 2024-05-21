# OpenLLM-Data-Functionality
Es soll das Natrual Language Precessing und das Masked Language Processing mit dem Programm Meta 3 in vier verschiedenen Szenarien auf Englisch und auch teilweise auf Deutsch untersucht werden, um anschließend Vergleiche mit anderen LLMs anzustellen.

1.Aufgabe: Was wollen Sie testen (gerne mit Beispielen)?
Es soll das Natrual Language Processing und das Masked Language Processing in Meta 3 getestet werden. Dies soll mithilfe verschiedener Textsorten getestet werden. Die Hauptsprache ist dabei Englisch. Insgesamt soll es vier Szenarien geben:
1. Szenario: Normale Sätze sollen angefangen werden und dann von Meta 3 (OpenLLM) beendet werden. Beispielsweise: Was ist die Hauptstadt von... usw. 
2. Szenario: Die OpenLLM soll Witze beenden. Man gibt de OpenLLM Anfänge von Sätzen vor und die soll dann daraus Witze kreieren. Dabei steht natürlich im Vordergrund die Frage, ob der Witz an sich funktioniert. 
3. Szenario: Man gibt der OpenLLM Sätze oder Reime vor und die OpenLLM soll einen Reim dazu erstellen. 
4. Szenario: Sätze sollen auch hier wieder vorgegeben werden und dann von der OpenLLM beendet wären. Dabei sollen Unterschiede beim Prompt im Vorfeld angegeben werden. Einmal soll die Ausgabe extra umgangssprachlich ausgegeben werden und einmal soll die Ausgabe extra formal angegeben werden.
  
Dann soll noch der Unterschied zwischen der englischen und deutschen Sprache beim Output dargestellt werden. Dies soll vor allem durch die Beispiele mit den Witzen (Szenario 2) veranschaulicht werden. Da sollen die Ausgaben nicht nur auf Englisch, sondern auch auf Deutsch ausgegeben werden.

Die letzte Aufgabe wäre es dann, die Outputs von dem Modell Meta 3, auch mit anderen bekannten Modellen zu vergleichen. Beispielsweise: ChatGPT und Mistral.

(Diese Fragestellung wurde zusammen mit Jonathan Voß aus dem Kurs 'Wie konkurrenzfähig sind Open LLMs?' erarbeitet. Jeder von uns arbeitet mit einem anderen Modell und benutzt einen jeweils anderen Datensatz).



2.Aufgabe: Bezug zu Datenbasis (Medium, Sprache, Quelle)?

 -Medium: Text

 -Sprache: Hauptsprache Englisch und zusätzlich Deutsch

 -Quelle: Internet. Szenario 1: Youtube Kommentare. Szenario 2: Witze-Webseite. Szenario 3: Reime-Webseite. Szenario 4: Alltägliche Sätze (Mischung aus selbstgeschriebene Beispielsätze und Sätze aus dem Internet).

 

3.Aufgabe: OpenLLM, das verwendet werden soll?

Meta 3 - https://huggingface.co/meta-llama/Meta-Llama-3-8B-Instruct

  

4.Aufgabe: Experimentdesign - wie wollen Sie vorgehen und wie die Ergebnisse beurteilen? Testen Sie vielleicht, wie geläufige LLMs die Aufgaben erledigen?

1. Zu jedem Szenario soll eine Tabelle (GoogleDoc) erstellt werden, die dann ausgewertet werden soll. Dies soll im Hinblick auf alle Szenarien gemacht werden.
2. Dann soll auch noch eine Tabelle erstellt werden, die die Unterschiede auf Englisch und deutsch darstellt.
3. Bei der dritten Aufgabe, soll dann noch ein genereller Vergleich (auch in einer Tabelle) zwischen Meta 3 und ChatGPT und Mistral veranschaulicht werden.

