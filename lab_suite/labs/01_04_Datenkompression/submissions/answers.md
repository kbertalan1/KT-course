# Fragebogen: Wort-Entropie (word_dictionary.py)

Nach dem Ausführen von `word_dictionary.py` mit eigenem Text in `sampletext.txt`:

**Konsolenausgabe einfügen:** Nutze das Merge-Symbol in der Task-Card, um die Ausgabe aus `console_log.txt` hier einzufügen. Anschließend die Ausgabe **kommentieren**.

---

**1. Konsolenausgabe**

*(Wird per „Konsolenausgabe einfügen“ unten eingefügt. Danach bitte kommentieren.)*

---

**2. Deine Kommentierung**

- Wie unterscheidet sich die Wort-Entropie von der Zeichen-Entropie (entropy1.py)?  
  Bei der Wort-Entropie betrachten wir ganze Wörter als einzelne Symbole anstatt einzelner Buchstaben. Der Entropiewert pro Symbol ist hier höher (6,27 bit/Wort), da das "Alphabet" viel größer ist als nur 26 Buchstaben. Dafür ist die Gesamtanzahl der Symbole im Text viel geringer.

- Was sagt die Entropie in Byte im Vergleich zur tatsächlichen Dateigröße aus?  
  Die Entropie (hier 106 Bytes) ist das theoretische absolute Minimum, auf das der Text komprimiert werden könnte, ohne Informationen zu verlieren. Die echte Dateigröße (847 Bytes) ist fast achtmal so groß, weil der Computer stur jedes einzelne Zeichen mit 8 Bit speichert. Der krasse Unterschied zeigt einfach, wie extrem redundant menschliche Sprache ist.

---


## Konsolenausgabe

```
Analyze the file:  C:\Users\kissb\_Git\KT-course\lab_suite\labs\01_04_Datenkompression\sidedata/sampletext.txt
Total number of words:     134
Number of different words: 97

-------Table of words:-----------------------------------------
                            the | cnt= 10    p=0.075   H=3.744 bit/word   H_av=0.279 bit/word
                             of | cnt=  7    p=0.052   H=4.259 bit/word   H_av=0.222 bit/word
                            and | cnt=  6    p=0.045   H=4.481 bit/word   H_av=0.201 bit/word
                              a | cnt=  4    p=0.030   H=5.066 bit/word   H_av=0.151 bit/word
                            was | cnt=  3    p=0.022   H=5.481 bit/word   H_av=0.123 bit/word
                     electronic | cnt=  3    p=0.022   H=5.481 bit/word   H_av=0.123 bit/word
                             in | cnt=  3    p=0.022   H=5.481 bit/word   H_av=0.123 bit/word
                           also | cnt=  2    p=0.015   H=6.066 bit/word   H_av=0.091 bit/word
                            war | cnt=  2    p=0.015   H=6.066 bit/word   H_av=0.091 bit/word
                             by | cnt=  2    p=0.015   H=6.066 bit/word   H_av=0.091 bit/word
                             at | cnt=  2    p=0.015   H=6.066 bit/word   H_av=0.091 bit/word
                             to | cnt=  2    p=0.015   H=6.066 bit/word   H_av=0.091 bit/word
                          years | cnt=  2    p=0.015   H=6.066 bit/word   H_av=0.091 bit/word
                            The | cnt=  2    p=0.015   H=6.066 bit/word   H_av=0.091 bit/word
                          these | cnt=  2    p=0.015   H=6.066 bit/word   H_av=0.091 bit/word
                          World | cnt=  1    p=0.007   H=7.066 bit/word   H_av=0.053 bit/word
                            War | cnt=  1    p=0.007   H=7.066 bit/word   H_av=0.053 bit/word
                             II | cnt=  1    p=0.007   H=7.066 bit/word   H_av=0.053 bit/word
                            not | cnt=  1    p=0.007   H=7.066 bit/word   H_av=0.053 bit/word
                           only | cnt=  1    p=0.007   H=7.066 bit/word   H_av=0.053 bit/word
                       conflict | cnt=  1    p=0.007   H=7.066 bit/word   H_av=0.053 bit/word
                         armies | cnt=  1    p=0.007   H=7.066 bit/word   H_av=0.053 bit/word
                            but | cnt=  1    p=0.007   H=7.066 bit/word   H_av=0.053 bit/word
                   technologies | cnt=  1    p=0.007   H=7.066 bit/word   H_av=0.053 bit/word
                   intelligence | cnt=  1    p=0.007   H=7.066 bit/word   H_av=0.053 bit/word
                            One | cnt=  1    p=0.007   H=7.066 bit/word   H_av=0.053 bit/word
                           most | cnt=  1    p=0.007   H=7.066 bit/word   H_av=0.053 bit/word
                    significant | cnt=  1    p=0.007   H=7.066 bit/word   H_av=0.053 bit/word
                  breakthroughs | cnt=  1    p=0.007   H=7.066 bit/word   H_av=0.053 bit/word
                     decryption | cnt=  1    p=0.007   H=7.066 bit/word   H_av=0.053 bit/word
                         Enigma | cnt=  1    p=0.007   H=7.066 bit/word   H_av=0.053 bit/word
                        machine | cnt=  1    p=0.007   H=7.066 bit/word   H_av=0.053 bit/word
                           Alan | cnt=  1    p=0.007   H=7.066 bit/word   H_av=0.053 bit/word
                         Turing | cnt=  1    p=0.007   H=7.066 bit/word   H_av=0.053 bit/word
                            his | cnt=  1    p=0.007   H=7.066 bit/word   H_av=0.053 bit/word
                           team | cnt=  1    p=0.007   H=7.066 bit/word   H_av=0.053 bit/word
                      Bletchley | cnt=  1    p=0.007   H=7.066 bit/word   H_av=0.053 bit/word
                           Park | cnt=  1    p=0.007   H=7.066 bit/word   H_av=0.053 bit/word
                           This | cnt=  1    p=0.007   H=7.066 bit/word   H_av=0.053 bit/word
                           feat | cnt=  1    p=0.007   H=7.066 bit/word   H_av=0.053 bit/word
                   cryptography | cnt=  1    p=0.007   H=7.066 bit/word   H_av=0.053 bit/word
                          early | cnt=  1    p=0.007   H=7.066 bit/word   H_av=0.053 bit/word
                      computing | cnt=  1    p=0.007   H=7.066 bit/word   H_av=0.053 bit/word
                             is | cnt=  1    p=0.007   H=7.066 bit/word   H_av=0.053 bit/word
                      estimated | cnt=  1    p=0.007   H=7.066 bit/word   H_av=0.053 bit/word
                           have | cnt=  1    p=0.007   H=7.066 bit/word   H_av=0.053 bit/word
                      shortened | cnt=  1    p=0.007   H=7.066 bit/word   H_av=0.053 bit/word
                          least | cnt=  1    p=0.007   H=7.066 bit/word   H_av=0.053 bit/word
                            two | cnt=  1    p=0.007   H=7.066 bit/word   H_av=0.053 bit/word
                            era | cnt=  1    p=0.007   H=7.066 bit/word   H_av=0.053 bit/word
                            saw | cnt=  1    p=0.007   H=7.066 bit/word   H_av=0.053 bit/word
                          rapid | cnt=  1    p=0.007   H=7.066 bit/word   H_av=0.053 bit/word
                    development | cnt=  1    p=0.007   H=7.066 bit/word   H_av=0.053 bit/word
                          radar | cnt=  1    p=0.007   H=7.066 bit/word   H_av=0.053 bit/word
                            jet | cnt=  1    p=0.007   H=7.066 bit/word   H_av=0.053 bit/word
                        engines | cnt=  1    p=0.007   H=7.066 bit/word   H_av=0.053 bit/word
                          first | cnt=  1    p=0.007   H=7.066 bit/word   H_av=0.053 bit/word
                   programmable | cnt=  1    p=0.007   H=7.066 bit/word   H_av=0.053 bit/word
                      computers | cnt=  1    p=0.007   H=7.066 bit/word   H_av=0.053 bit/word
                           such | cnt=  1    p=0.007   H=7.066 bit/word   H_av=0.053 bit/word
                             as | cnt=  1    p=0.007   H=7.066 bit/word   H_av=0.053 bit/word
                       Colossus | cnt=  1    p=0.007   H=7.066 bit/word   H_av=0.053 bit/word
                          These | cnt=  1    p=0.007   H=7.066 bit/word   H_av=0.053 bit/word
                    innovations | cnt=  1    p=0.007   H=7.066 bit/word   H_av=0.053 bit/word
                    transformed | cnt=  1    p=0.007   H=7.066 bit/word   H_av=0.053 bit/word
                    battlefield | cnt=  1    p=0.007   H=7.066 bit/word   H_av=0.053 bit/word
                           laid | cnt=  1    p=0.007   H=7.066 bit/word   H_av=0.053 bit/word
                     groundwork | cnt=  1    p=0.007   H=7.066 bit/word   H_av=0.053 bit/word
                            for | cnt=  1    p=0.007   H=7.066 bit/word   H_av=0.053 bit/word
                        digital | cnt=  1    p=0.007   H=7.066 bit/word   H_av=0.053 bit/word
                            age | cnt=  1    p=0.007   H=7.066 bit/word   H_av=0.053 bit/word
                             we | cnt=  1    p=0.007   H=7.066 bit/word   H_av=0.053 bit/word
                           live | cnt=  1    p=0.007   H=7.066 bit/word   H_av=0.053 bit/word
                          today | cnt=  1    p=0.007   H=7.066 bit/word   H_av=0.053 bit/word
                  Understanding | cnt=  1    p=0.007   H=7.066 bit/word   H_av=0.053 bit/word
                        systems | cnt=  1    p=0.007   H=7.066 bit/word   H_av=0.053 bit/word
                       requires | cnt=  1    p=0.007   H=7.066 bit/word   H_av=0.053 bit/word
                           deep | cnt=  1    p=0.007   H=7.066 bit/word   H_av=0.053 bit/word
                      knowledge | cnt=  1    p=0.007   H=7.066 bit/word   H_av=0.053 bit/word
                         signal | cnt=  1    p=0.007   H=7.066 bit/word   H_av=0.053 bit/word
                     processing | cnt=  1    p=0.007   H=7.066 bit/word   H_av=0.053 bit/word
                    engineering | cnt=  1    p=0.007   H=7.066 bit/word   H_av=0.053 bit/word
                     principles | cnt=  1    p=0.007   H=7.066 bit/word   H_av=0.053 bit/word
                           that | cnt=  1    p=0.007   H=7.066 bit/word   H_av=0.053 bit/word
                         remain | cnt=  1    p=0.007   H=7.066 bit/word   H_av=0.053 bit/word
                    fundamental | cnt=  1    p=0.007   H=7.066 bit/word   H_av=0.053 bit/word
                         modern | cnt=  1    p=0.007   H=7.066 bit/word   H_av=0.053 bit/word
                     technology | cnt=  1    p=0.007   H=7.066 bit/word   H_av=0.053 bit/word
                          shift | cnt=  1    p=0.007   H=7.066 bit/word   H_av=0.053 bit/word
                           from | cnt=  1    p=0.007   H=7.066 bit/word   H_av=0.053 bit/word
                     mechanical | cnt=  1    p=0.007   H=7.066 bit/word   H_av=0.053 bit/word
                    computation | cnt=  1    p=0.007   H=7.066 bit/word   H_av=0.053 bit/word
                         during | cnt=  1    p=0.007   H=7.066 bit/word   H_av=0.053 bit/word
                        pivotal | cnt=  1    p=0.007   H=7.066 bit/word   H_av=0.053 bit/word
                         moment | cnt=  1    p=0.007   H=7.066 bit/word   H_av=0.053 bit/word
                          human | cnt=  1    p=0.007   H=7.066 bit/word   H_av=0.053 bit/word
                        history | cnt=  1    p=0.007   H=7.066 bit/word   H_av=0.053 bit/word
-----------------------------------------------------------------

Average Entropy H = 6.270 bit/word
Total Entropy of 134 words H=840.211 bit (106 bytes)
Size of text file: 847 bytes
```
