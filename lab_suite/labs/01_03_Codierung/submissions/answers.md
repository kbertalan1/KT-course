# Fragebogen: Huffman-Codierung (huffman.py)

Nach dem Ausführen des Skripts und **Einfügen der Konsolenausgabe** (Merge-Symbol in der Task-Card):

---

**1. Konsolenausgabe**

*(Wird per „Konsolenausgabe einfügen“ unten eingefügt. Danach bitte kommentieren.)*

**2. Deine Kommentierung**

- Was zeigen die ausgegebenen Huffman-Codes?  
  Die Codes zeigen die binäre Repräsentation jedes Zeichens, die durch den Huffman-Baum optimiert wurde. In diesem speziellen Fall haben alle Zeichen eine Länge von 2 Bits (z. B. 'C' = 11), da die Häufigkeiten im String (2, 2, 2, 1) sehr nah beieinander liegen und die Anzahl der verschiedenen Symbole gering ist.

- Warum haben häufigere Zeichen kürzere Codewörter?  
  Um die Gesamtzahl der Bits zu minimieren, weist man den Zeichen mit hoher Wahrscheinlichkeit kurze Codes zu. Dadurch wird die durchschnittliche Codewortlänge reduziert.

---

## Konsolenausgabe

```
Enter the string to compute Huffman Code Tree: ---------------------------------------------------------
Dictionary of Characters with char frequency:       {'A': 1, 'C': 2, 'D': 2, 'S': 2}
Dictionary converted into a list:                   dict_items([('A', 1), ('C', 2), ('D', 2), ('S', 2)])
List of characters sorted to descending frequency:  [('C', 2), ('D', 2), ('S', 2), ('A', 1)]
Huffman Code Dictionary:                            {'A': '00', 'S': '01', 'D': '10', 'C': '11'}

 Char | Huffman code 
----------------------
 'C'  |          11
 'D'  |          10
 'S'  |          01
 'A'  |          00
```
