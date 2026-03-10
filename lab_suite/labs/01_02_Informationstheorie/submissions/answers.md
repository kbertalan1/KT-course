# Fragebogen: Entropie-Analyse (entropy1.py)

Nach dem Ausführen von `entropy1.py` mit eigenem Text in `sampletext.txt`:

**Konsolenausgabe einfügen:** Nutze das Merge-Symbol in der Task-Card, um die Ausgabe aus `console_log.txt` hier einzufügen. Anschließend die Ausgabe **kommentieren**.

---

**1. Konsolenausgabe**

*(Wird per „Konsolenausgabe einfügen“ unten eingefügt. Danach bitte kommentieren.)*

---

**2. Deine Kommentierung:**

- Was fällt dir bei der Entropie deines Textes auf?  

Der Wert von H = 4,299 bit/char zeigt eine hohe Redundanz, da er weit unter dem Maximum (8 bit) liegt. Die ungleichmäßige Verteilung (Space und 'e' dominieren) macht den Text sehr effizient komprimierbar. Seltene Zeichen wie 'q' haben zwar eine hohe Einzelentropie, beeinflussen den Durchschnitt aber kaum.

## Konsolenausgabe

```
Analyze the file:  C:\Users\kissb\_Git\KT-course\lab_suite\labs\01_02_Informationstheorie\sidedata/sampletext.txt

-----File Contents:---------------------------------------------------
World War II was not only a conflict of armies but also a war of technologies and intelligence. One of the most significant breakthroughs was the decryption of the Enigma machine by Alan Turing and his team at Bletchley Park. This feat of cryptography and early computing is estimated to have shortened the war by at least two years.



The era also saw the rapid development of radar, jet engines, and the first programmable electronic computers, such as the Colossus. These innovations transformed the battlefield and laid the groundwork for the digital age we live in today. Understanding these systems requires a deep knowledge of signal processing and electronic engineering, principles that remain fundamental in modern technology. The shift from mechanical to electronic computation during these years was a pivotal moment in human history.
Number of characters: 845
Character Dictionary: {'W': 2, 'o': 50, 'r': 43, 'l': 31, 'd': 26, ' ': 132, 'a': 62, 'I': 2, 'w': 10, 's': 43, 'n': 56, 't': 60, 'y': 14, 'c': 24, 'f': 17, 'i': 48, 'm': 22, 'e': 81, 'b': 6, 'u': 13, 'h': 32, 'g': 21, '.': 7, 'O': 1, 'k': 4, 'p': 14, 'E': 1, 'A': 1, 'T': 5, 'B': 1, 'P': 1, 'v': 5, '\n': 2, ',': 4, 'j': 1, 'C': 1, 'U': 1, 'q': 1}

-------Table of characters:----------------
       | cnt=132    p=0.156   H=2.678 bit/char  H_av=0.418 bit/char
 e     | cnt= 81    p=0.096   H=3.383 bit/char  H_av=0.324 bit/char
 a     | cnt= 62    p=0.073   H=3.769 bit/char  H_av=0.277 bit/char
 t     | cnt= 60    p=0.071   H=3.816 bit/char  H_av=0.271 bit/char
 n     | cnt= 56    p=0.066   H=3.915 bit/char  H_av=0.259 bit/char
 o     | cnt= 50    p=0.059   H=4.079 bit/char  H_av=0.241 bit/char
 i     | cnt= 48    p=0.057   H=4.138 bit/char  H_av=0.235 bit/char
 r     | cnt= 43    p=0.051   H=4.297 bit/char  H_av=0.219 bit/char
 s     | cnt= 43    p=0.051   H=4.297 bit/char  H_av=0.219 bit/char
 h     | cnt= 32    p=0.038   H=4.723 bit/char  H_av=0.179 bit/char
 l     | cnt= 31    p=0.037   H=4.769 bit/char  H_av=0.175 bit/char
 d     | cnt= 26    p=0.031   H=5.022 bit/char  H_av=0.155 bit/char
 c     | cnt= 24    p=0.028   H=5.138 bit/char  H_av=0.146 bit/char
 m     | cnt= 22    p=0.026   H=5.263 bit/char  H_av=0.137 bit/char
 g     | cnt= 21    p=0.025   H=5.330 bit/char  H_av=0.132 bit/char
 f     | cnt= 17    p=0.020   H=5.635 bit/char  H_av=0.113 bit/char
 y     | cnt= 14    p=0.017   H=5.915 bit/char  H_av=0.098 bit/char
 p     | cnt= 14    p=0.017   H=5.915 bit/char  H_av=0.098 bit/char
 u     | cnt= 13    p=0.015   H=6.022 bit/char  H_av=0.093 bit/char
 w     | cnt= 10    p=0.012   H=6.401 bit/char  H_av=0.076 bit/char
 .     | cnt=  7    p=0.008   H=6.915 bit/char  H_av=0.057 bit/char
 b     | cnt=  6    p=0.007   H=7.138 bit/char  H_av=0.051 bit/char
 T     | cnt=  5    p=0.006   H=7.401 bit/char  H_av=0.044 bit/char
 v     | cnt=  5    p=0.006   H=7.401 bit/char  H_av=0.044 bit/char
 k     | cnt=  4    p=0.005   H=7.723 bit/char  H_av=0.037 bit/char
 ,     | cnt=  4    p=0.005   H=7.723 bit/char  H_av=0.037 bit/char
 W     | cnt=  2    p=0.002   H=8.723 bit/char  H_av=0.021 bit/char
 I     | cnt=  2    p=0.002   H=8.723 bit/char  H_av=0.021 bit/char
 b'\n' | cnt=  2    p=0.002   H=8.723 bit/char  H_av=0.021 bit/char
 O     | cnt=  1    p=0.001   H=9.723 bit/char  H_av=0.012 bit/char
 E     | cnt=  1    p=0.001   H=9.723 bit/char  H_av=0.012 bit/char
 A     | cnt=  1    p=0.001   H=9.723 bit/char  H_av=0.012 bit/char
 B     | cnt=  1    p=0.001   H=9.723 bit/char  H_av=0.012 bit/char
 P     | cnt=  1    p=0.001   H=9.723 bit/char  H_av=0.012 bit/char
 j     | cnt=  1    p=0.001   H=9.723 bit/char  H_av=0.012 bit/char
 C     | cnt=  1    p=0.001   H=9.723 bit/char  H_av=0.012 bit/char
 U     | cnt=  1    p=0.001   H=9.723 bit/char  H_av=0.012 bit/char
 q     | cnt=  1    p=0.001   H=9.723 bit/char  H_av=0.012 bit/char
-------------------------------------------

Average Entropy H = 4.299 bit/char
Total Entropy of 845 characters H=3632.69 bit = 455.00 byte
```
