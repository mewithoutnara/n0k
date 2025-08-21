Seminararbeit - Form und Formalismus <br> 
Entwendete Mathematik<br>
Shuoxin Tan



# Der nullte Körper



*„We don’t want to count, we want to think the count.“ — Alain Badiou[^1]*
<br>

## Einführung

Seit langem ging ich um dieselbe Stelle drumherum, bevor ich etwas aufschreiben konnte. Weil ich überlegte, wie ich mit diesem Thema umgehen sollte, das mich interessiert und das mir zugleich einen Mangel an Wissen erschloß. 

Was ich hier erörtern möchte, ist genau wie dieser Moment, diese Bewegung, von denen ich anfange, aufzuschreiben - Ich werde etwas aus dem Nichts schreiben. Bei dem Etwas geht es um die Null, und zwar die Leermenge, von der eine wiederholende Fortbewegung generiert wird - „Zählung-als-Eins“[^2]. 

Bevor ich damit anfange, muss ich kurz einen Umweg machen. Denn was ich heute erläutern möchte, ist weder ein mathematisches noch logisches Problem, sondern wie man eine mathematische Denkweise entwendet und in seinem eigenen logischen Diskurs verwendet.  Da muss ich zuerst auf Jacques Lacan eingehen, dann komme ich zu seinen Nachfolgern - Jacques-Alain Miller und Alain Badiou.


## *Jacques Lacan* - Mathematische Formalisierung

Der Psychoanalytiker und Theoretiker Jacques Lacan versucht, die psychoanalytische Theorie eher rational als intuitiv zu verstehen. In seiner Untersuchung verfolgt Lacan grundsätzlich zwei Ansätze, wobei einer aus der Linguistik stammt, der ein von Saussure inspiriertes Sprachmodell als System der Signifikanten verwendet. Der andere ist die mathematische Formalisierung - Algebra und Topologie spielen die größte Rolle, während die Konzepte in Umfang der Mengentheorie und Zahlentheorie auch in seinen frühen Forschungen verwendet wurden.

„Die mathematische Formalisierung ist unser Ziel, unser Ideal“[^3], so behauptete Lacan.

Sein Ziel der mathematischen Formalisierung dient jedoch nicht dazu, die Mehrdeutigkeit von der Sprache zu eliminieren, sondern die vielseitigen Effekte der Äquivokation hervorzuheben.


## *Lacan’sche Ontologie* - das Subjekt und sein Mangel des Seins

Jacques Lacan begreift das Subjekt als „Mangel an Sein“[^4] - als Fehlen eines Signifikanten, als Leerstelle. Das Sein gehört zur symbolischen Ordnung und in der Beziehung zum Anderen findet sich das Sein seinen Status. Diese Beziehung wird durch einen Mangel gekennzeichnet. Dass das Subjekt aus dem Mangel besteht und stets nach diesem Mangel fragt, ruft das Begehren hervor, sein zu wollen.

Um die Beziehung zwischen dem Subjekt und dem Anderen zu verdeutlichen, hat Lacan bezüglich der Ordinalzahl betont, dass „Die Zahlenfolge nur darstellbar ist, wenn man die Null einführt. Die Null ist die Präsenz des Subjekts, das auf dieser Ebene, zusammenzählt. Wir können die Null nicht aus der Dialektik von Subjekt und anderem herausziehen.“[^5]


## *Die natürlichen Zahlen* als geordnete Mengen

Schon viele haben danach gefragt, wo die natürlichen Zahlen beginnen sollten, bei 0 oder bei 1? Es gibt verschiedene Konstruktionen der natürlichen Zahlen, die durch unterschiedliche mengentheoretische Modelle die Reihe der Ordinalzahlen aufbauen können. 

### Zermelos Zahlenreihe von 1908[^6]

```text
0 := { } = ∅
1 := {0} = {∅}
2 := {1} = {{∅}}
.
.
.
n := {n−1} = {{{∅}}}
```

Auf diese Weise werden die natürlichen Zahlen rekursiv definiert, indem die Null die Leermenge ist, und ist auf verschiedene Art und Weise in ihren Nachfolgern wiederholend enthalten. Was ein wenig problematisch ist, ich aber trotzdem interessant finde, ist die Kardinalität: Außer der Kardinalität der leeren Menge 0, bleibt die Kardinalität aller Nachfolgermengen immer 1. 

**Kardinalität:**

```text
0 = { }   -> 0
1 = { 0 } -> 1
2 = { 1 } -> 1
3 = { 2 } -> 1
4 = { 3 } -> 1
```

### von Neumanns Modell der natürlichen Zahlen[^7]

```text
0 :=        { }              = ∅
1 := 0’ = {0}             = {∅}
2 := 1’ = {0, 1}         = {∅, {∅}}
3 := 2’ = {0, 1, 2}     = {∅, {∅}, {∅, {∅}}}
4 := 3’ = {0, 1, 2, 3} = {∅, {∅}, {∅, {∅}}, {∅, {∅}, {∅, {∅}}}}
.
.
.
(n+1) := n’ = {0, 1,…, n} = n ∪ {n}
```

Nach dem Leermengenaxiom[^8] von Zermelo gibt es eine Menge ohne Elemente - die leere Menge. Die Null „0“ ist der Leermenge ∅ zugeordnet worden. Die Nachfolgermenge ist definiert als die Vereinigung der Vorgängermengen und der Menge, die die Vorgängermenge enthält. Das von Neumanns Modell ist allgemein angenommen, denn die Ordinalzahl einer Menge und ihre Kardinalität sind gleich.

**Kardinalität:**

```text
0 = { } -> 0
1 = { 0 } -> 1
2 = { 0, 1 } -> 2
3 = { 0, 1, 2 } -> 3
4 = { 0, 1, 2, 3 } -> 4
```


## Die *Null* und die *Eins*

Für die Ordinalzahlen sind die hauptsächlichen Begriffe: die Null, die Zahl, und der Nachfolger. Was funktioniert so, dass es diese nachfolgende Fortbewegung vom Anfang an generiert? Und was versichert den Fortschritt, stets von *n* nach *n + 1* voranzukommen ? 

Alle Fragen kommen zu der Null und der Eins: Das „Zählung-als-Eins“ des Nichts ist die Leere Menge, in der es nichts gibt und die kein Element enthält. Die Null ist der Leermenge zugeordnet und dann wird sie als „Eins“ gezählt. Die Nachfolger entstehen aus diesem wiederholenden „Zählung-als-Eins“. 

Bei diesem kleinen „Aus dem Nichts“ Schritt gibt es eine interessante logische Diskordanz, die nicht einheitlich verstanden wird. Deswegen haben viele von unterschiedlichen Standpunkten aus die Diskordanz in ihren eigenen Disziplinen verwendet und analysiert. 


## Jacques-Alain Miller - „Suture“[^9], Nähen im Denken[^10]

Das Wort „Suture“ wurde von Miller aus dem alltäglichen Leben gezogen und in einem ungewöhnlichen Kontext - also in seinem eigenen logischen Diskurs über die Lacan’sche Psychoanalyse, und zwar das Subjekt und seinen Mangel, die Logik des Signifikanten bzw. das Verhältnis von Subjekt zur Signifikantenkette, eingesetzt. Dieser Ansatz ist ähnlich dem, was Marcel Duchamp für seine künstlerische experimentelle Praxis gemacht hat.[^11] Weiterhin machte Lacan es auch so. Als Nachfolger von Lacan tat Miller es mit „Suture“ ebenfalls.

Miller analysiert die Entstehung der Ordinalzahlen einerseits anhand des Konzepts der Null von Frege, die Frege von Leibniz[^12] ausgeliehen und entwickelt hat. Die Null steht für den Begriff des Nicht-Selbstidentischen. Andererseits argumentierte Miller bezüglich der Logik des Objekts von Frege, dass dieser Mangel an Objekt genau als die Subjektivität der Nicht-Selbstidentität erscheint. Diese steht an der Leerstelle und unter diese fällt kein Objekt. Doch existiert das Subjekt als Unmöglichkeit des Objekts.

Diese Diskordanz, dass das Selbstidentische das Nicht-selbstidentische repräsentiert, wurde von Miller als „Suture“ bezeichnet. Die Null ersetzt[^13] den Mangel und näht das Nichts mit dem Etwas versetzt zusammen – D.h., die Null ist die „Zählung-als-Eins“ des Nichts. Das Nichts ist nicht mit sich selbst identisch, doch ist die Null. Die Null ist schon die Eins – der Name einer Zahl.

Dieser paradoxe Zustand erzeugt die Genesis der Ordinalzahlen und versichert den Fortschritt, wie ein Open-Close-Prozess.

Durch die Metonymie mit der Null und der Nachfolgenden Ordinalzahlen wurde die Diskordanz der Signifikanten im Sinne von Lacan, dass „Ein Signifikant ist, was ein Subjekt repräsentiert für einen anderen Signifikanten.“[^14], verdeutlicht. 

Ist „Suture“ auch das, wovon Alain Badiou gesprochen hat, „Nähen im Denken“?


## Alain Badiou - Mathematische Ontologie

Badiou ist von der Lacan’schen Ontologie beeinflußt und sein Verständnis der Mathematik als Ontologie ist kontrovers. Das Konzept „Suture“ von Miller hat Badiou auch stark beeinflußt, weswegen Badiou in *„Being and Event[^15]“*, *“Number and Numbers[^16]“* seine Erkenntnisse im ganzen Spektrum erläutert hat. Darüberhinaus setzte sich Badiou mit der Ontologie der Ordinalzahlen auf einer höheren Ebene auseinander und forderte das moderne Denken über die Zahl heraus.

Was sich auf das Thema bezieht und mich sehr stark beeinflußt, möchte ich zum Ende erwähnen. Es geht um den Diskurs von Badiou über die Ontologie des Nichts. Meine Frage dazu:

*What is Nothing? Is Nothing a-Thing?*

Nach Badiou gibt es ein Sein des ‚Nichts‘, die Form des Unpräsentierbaren. Das ‚Nichts‘ bezeichnet die nicht wahrnehmbare Kluft, die wiederholend aufgehoben und erneuert wird, zwischen Konkordanz und Diskordanz. Das ‚Nichts‘ ist weder ein Ort noch ein Begriff des Zustands. Denn alles, was „Zählung-als-Eins“ werden kann, liegt in der Konkordanz und ist präsentierbar. 

*„There is not a-nothing, there is ‚nothing.“[^17]*


## Ausklang

Etwas habe ich gerade aus dem Nichts aufgeschrieben, das mir einen Mangel an Wissen erschlossen hat. Das Wissen ist das, was man die Form genannt hat. In Platon ist die Form dieses Wissen, das das Sein füllt.[^18] Und über das, was nicht demonstriert werden kann, kann doch etwas Wahres gesagt werden. [^19] 

Am Ende würde ich gerne schweigen, die Diskordanz hinterlassen.

```supercollider
[  ].bubble.unbubble
[  ].unbubble.bubble
```
<br>
<br>




[^1]: Cantor: ‚Well-Orderedness‘ and the Ordinals; In: Number and Numbers. New York: Polity Press, 2008.  
[^2]: „compte-pour-un“ im Originaltext von Alain Badiou; „count-as-one“ in der englischen Version.  
[^3]: Lacan, Jacques (1973): Fadenringe. In: Das Seminar, Buch XX, Encore. Berlin: Quadriga, 1986.  
[^4]: „manque-à-être“  
[^5]: Lacan, Jacques (1964): Das Subjekt und der/das Andere (II): Aphanisis. In: Das Seminar, Buch XI, Die vier Grundbegriffe der Psychoanalyse. Turia + Kant, 1986.  
[^6]: „Die menge Z_0 enthält die Elemente 0, {0}, {{0}} usw. und möge als ‚Zahlreihe‘ bezeichnet werden, weil ihre Elemente die Stelle der Zahlzeichen vertreten können.“ Zermelo, Ernst (1908): Untersuchungen über die Grundlagen der Mengenlehre I. In: Mathematische Annalen, S. 267.  
[^7]: https://de.wikipedia.org/wiki/Nat%C3%BCrliche_Zahl  
[^8]: https://de.wikipedia.org/wiki/Zermelo-Fraenkel-Mengenlehre  
[^9]: Miller, Jacques-Alain (1965): Suture (Elements of the Logic of the Signifier). In: Screen, Volume 18, Issue 4, Winter 1977, Pages 24–34. Der originale Titel: La Suture (Éléments de la logique du signifiant).  
[^10]: Nancy, J.-L., Badiou, A., Völker, J. (2017): Deutsche Philosophie. Ein Dialog (Fröhliche Wissenschaft). Berlin: Matthes & Seitz, 2017.  
[^11]: Bekanntlich versuchte Duchamp mit 3 Standardstopps (1913-1914) und Brunnen (1917), dass ein Objekt, das außerhalb der Kunst ist und bereits üblich definiert wird, als eine epistemische Sache erneut zu erkennen und zu verstehen, was es sein könnte.  
[^12]: Leibniz: „Those things are identical of which one can be substituted for the other salva veritate, without loss of truth.“ In: Miller, Jacques-Alain (1965): Suture (Elements of the Logic of the Signifier).  
[^13]: The French gives 'tenant-lieu', literally a 'holding-the-place-of', in the sense of substitute; it has been variously translated as 'stand-in', 'taking-the-place-of', etc. In: Miller, Jacques-Alain (1965): Suture (Elements of the Logic of the Signifier).  
[^14]: Lacan, Seminar XI. Die vier Grundbegriffe der Psychoanalyse, S. 208  
[^15]: Badiou, Alain (1988): Being and Event. London: Continuum, 2005.  
[^16]: Badiou, Alain (1990): Number and Numbers. New York: Polity Press, 2008.  
[^17]: Badiou, Alain (1988): The Void: Proper name of being. In: Being and Event. London: Continuum, 2005.  
[^18]: Lacan, Jacques (1973): Fadenringe.  
[^19]: Ein Auszug von Gödelscher Unvollständigkeitssatz. In: Lacan, Jacques (1973): Fadenringe.


## Literatur

- Badiou, A. (1988). *Being and Event*. London: Continuum.  
  (Kapitel: *The Void: Proper name of being; One, count-as-one, unicity, and forming-into-one*).  

- Badiou, A. (1990). *Number and Numbers*. New York: Polity Press.  
  (Kapitel: *Frege; Additional Note on a Contemporary Usage of Frege; Cantor: „Well-Orderedness“ and the Ordinals; Succession and Limit. the Infinite*).  

- Badiou, A., Mackay, R., & Brassier, R. (2012). Alain Badiou, Philosophy, Sciences, Mathematics (Interview). In: *Collapse*, Volume I, 11–26.  
  Verfügbar unter: [urbanomic.com](https://www.urbanomic.com/chapter/collapse-i-alain-badiou-philosophy-sciences-mathematics/)  

- Lacan, J. (1964). *Das Seminar, Buch XI: Die vier Grundbegriffe der Psychoanalyse*. Wien: Turia + Kant, 1986.  

- Lacan, J. (1973). *Das Seminar, Buch XX: Encore (Fadenringe)*. Berlin: Quadriga, 1986.  

- Miller, J.-A. (1965). Suture (Elements of the Logic of the Signifier). *Screen*, 18(4), 24–34.  

- Nancy, J.-L., Badiou, A., & Völker, J. (2017). *Deutsche Philosophie. Ein Dialog (Fröhliche Wissenschaft)*. Berlin: Matthes & Seitz.  

