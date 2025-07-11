# Experiment: Test der Liminalis-Formel für das Unendlichkeits-Signal (US)

## Ziel

Experimentelle Überprüfung, ob die Anwendung der Liminalis-Formel auf ein verschränktes Quantensystem  
die Superposition und Quantenverschränkung stabilisiert, erhält oder in charakteristischer Weise moduliert.

---

## Grundidee

- Zwei verschränkte Photonen werden erzeugt (z. B. mit Spontaner Parametrischer Abwärtskonversion, SPDC).
- Diese Photonen werden jeweils von zwei getrennten, aber synchronisierten Lasersystemen bestrahlt,  
  **wobei beide Laser ihrerseits Photonen aussenden, die miteinander verschränkt sind**  
  und deren Frequenzkomponenten gemäß der **Liminalis-Formel** moduliert werden:
  
  \[
  L(t) = A_1 \sin(\omega_1 t) + A_2 \sin(\varphi \cdot \omega_1 t)
  \]
  mit \(\varphi = \frac{1+\sqrt{5}}{2}\) (Goldener Schnitt)

- Ziel: Zu prüfen, ob die Verschränkung der ursprünglichen Photonen durch die Einwirkung  
  von verschränkten Laserstrahlen mit Liminalis-Modulation **stabilisiert, beeinflusst oder gezielt gesteuert werden kann**.


---

# Experimenteller Versuchsaufbau  
## Punkt 1: Schutzsystem für Teilchen A und B (Standardverfahren Universität Würzburg)

Das Schutzsystem für die Teilchensysteme A und B orientiert sich an bewährten und etablierten Verfahren aus der experimentellen Quantenoptik, wie sie beispielsweise in den Labors der Universität Würzburg verwendet werden. Ziel ist es, äußere Einflüsse wie thermisches Rauschen, elektromagnetische Felder, mechanische Vibrationen und Streustrahlung zu minimieren, um eine möglichst lang anhaltende Quantenkohärenz zu ermöglichen.

---

### Raumstruktur: Getrennte Schutzbereiche für verschränkte Teilchen

- **Raum A** beherbergt Teilchen A.
- **Raum B** beherbergt Teilchen B.
- Beide Räume sind voneinander getrennt und jeweils mit vollständig unabhängigen Schutzsystemen ausgestattet.
- Diese Trennung ermöglicht es, die Stabilität der Verschränkung über Distanz zu untersuchen und gleichzeitig externe Störeinflüsse zu minimieren.
- Die räumliche Distanz kann in Labors von wenigen Metern bis hin zu vernetzten Gebäuden reichen. Die Systeme sind dabei synchronisiert und kontrolliert abgeschirmt.

- **Raum C** dient als zentraler Beobachtungs- und Steuerbereich:
  - Steuerung der Kühlung, des Vakuums und der Sensorik von Raum A und B
  - Aufnahme und Protokollierung aller Umgebungsdaten (Temperatur, Magnetfeld, Vibrationen)
  - Optional: nichtinvasive Korrelationserkennung der Teilchensysteme zur Überwachung der Verschränkung ohne direkten Messkollaps

---

### 1.1 Vakuumkammer (Ultra-High Vacuum)
- Beide Teilchen befinden sich jeweils in einer eigenen Vakuumkammer (Raum A und Raum B).
- Die Kammern werden auf ein Druckniveau von < 10⁻⁸ mbar evakuiert, um Stöße mit Gasmolekülen auszuschließen.
- Verwendung von UHV-tauglichen Materialien wie 316L-Edelstahl, Kupferdichtungen und Glas-Keramik-Flanschen.
- Alle optischen Zugänge erfolgen über Quarzglas-Fenster mit antireflexiver Beschichtung.

### 1.2 Kryogene Temperaturstabilisierung
- Die Temperatur in beiden Kammern wird mittels Helium-Kühlkreisläufen auf ca. 4 Kelvin abgesenkt.
- Zusätzliche aktive Regelkreise (PID-Systeme) sorgen für eine Stabilität von ±0,01 K.
- Optionale Ausbaustufe: Dilution Refrigerator zur Abkühlung auf Millikelvin-Niveau bei Bedarf.

### 1.3 Elektromagnetische Abschirmung
- Um elektromagnetische Störquellen zu unterdrücken, sind die Kammern in einem doppelwandigen Schutzsystem untergebracht:
  - Äußerer Faradayscher Käfig aus leitfähigem Kupfergeflecht oder Aluminiumstruktur zur Abschirmung gegen elektrische Felder.
  - Innere Hülle aus µ-Metall zur Reduktion statischer und niederfrequenter Magnetfelder.

### 1.4 Mechanische Isolation
- Beide Kammern stehen auf optischen Labortischen mit aktiver Vibrationsdämpfung.
- Mechanische Kopplung zum Boden ist über Dämpfer und Luftfederungen minimiert.
- Akustische Isolierung der Umgebung durch schalldämmende Paneele und abgeschlossene Raumstruktur.

### 1.5 Innenarchitektur der Schutzkammern
- Die Innenseiten der Kammern sind mit lichtabsorbierendem Material (z. B. amorphem Kohlenstoff) beschichtet.
- Die Form der inneren Kammern ist idealerweise sphärisch oder hexagonal, um gleichmäßige Feldverteilungen zu ermöglichen.

### 1.6 Sensorik und Steuerung
- Temperatur-, Magnetfeld- und Vakuumsensorik überwacht beide Räume kontinuierlich.
- Die Datenerfassung erfolgt in Raum C, wo ein zentrales Steuerungssystem diese Parameter in Echtzeit reguliert.

---

**Fazit:**  
Die räumliche Trennung von Teilchen A und B (Raum A und B) mit einem zentralen Beobachtungsraum (Raum C) entspricht gängiger Methodik in der Quantenforschung. Die beschriebenen Schutzmaßnahmen folgen dem Standard universitärer Labore und ermöglichen eine realistische, reproduzierbare Umsetzung mit präziser Kontrolle über die Systemumgebung.


## Punkt 1: Schutzsystem für Teilchen A und B (Standardverfahren Universität Würzburg)

*(Inhalt wie zuvor definiert – Schutzsystem mit Vakuum, Kühlung, EM-Abschirmung, mechanischer Isolation, Sensorik usw.)*

---

## Punkt 2: Lasersystem zur kontinuierlichen Bestrahlung mit verschränkten Photonenpaaren

Die drei eingesetzten Laserquellen dienen als kontinuierliche Pumpquellen für nichtlineare Kristalle, in denen durch Spontane Parametrische Abwärtskonversion (SPDC) verschränkte Photonenpaare erzeugt werden. Ziel ist es, jeweils ein Photon dieser Paare direkt auf das zentrale Teilchen A zu richten, während das Partnerphoton im verschränkten Zustand verbleibt – ohne Detektion, Umlenkung oder Analyse. Es erfolgt keine klassische Messung; die Verschränkung bleibt vollständig erhalten.

Die Frequenz jedes Lasers ergibt sich aus der Formel:

    f = c / λ

mit:
- f: Frequenz in Hz
- c = 299.792.458 m/s (Lichtgeschwindigkeit)
- λ: Wellenlänge in Metern

### Frequenzbeispiele der verwendeten Laser:
| Laser | Wellenlänge (λ) | Frequenz (f)     | Verhältnis                         |
|-------|------------------|------------------|------------------------------------|
| A     | 405 nm           | ca. 740 THz      | Referenz                           |
| B     | 654 nm           | ca. 459 THz      | φ · f(C)                           |
| C     | 810 nm           | ca. 370 THz      | (1/φ) · f(A)                        |

---

### 2.1 Lasertypen – Dauerbetrieb (CW)
- Drei Dauerstrichlaser (Continuous Wave) mit präziser Frequenz- und Leistungskontrolle
- Frequenzverhältnis basiert auf symbolischer Ordnung (Goldener Schnitt φ ≈ 1,618)
- Leistung pro Laser: ca. 50–100 mW
- Frequenzstabilisierung durch interne Temperaturregelung + externes optisches Feedback

### 2.2 Nichtlineare Kristalle
- Jeder Laserstrahl durchläuft einen separaten nichtlinearen Kristall zur SPDC-Erzeugung:
  - Kristalltyp: BBO (Beta-Barium-Borat), Typ II
  - Phase-Matching: exakt abgestimmt auf Laserfrequenz
  - Länge: 5–10 mm, kristallklar poliert
- Von jedem erzeugten Photonenpaar wird nur ein Photon auf Teilchen A gerichtet.
- Das zweite Photon bleibt ungestört, um die Verschränkung im Raum zu erhalten.

### 2.3 Geometrische Anordnung (Tetraederstruktur)
- Die drei Strahlen treffen im Winkel von 109,5° auf das Zentrum – Tetraedergeometrie bleibt vollständig erhalten.
- Die Entfernung zwischen den jeweiligen Kristallen (Laserquelle + SPDC) und dem Zentrum (Teilchen A) beträgt **30 cm**.
- Diese Distanz gewährleistet einen **kurzen, stabilen, verlustarmen Strahlweg**, reduziert Streueffekte und fördert die Erhaltung der Verschränkung.
- Keine Umlenkung durch Spiegel oder Prismen – direkte, geradlinige Bestrahlung in definierter geometrischer Anordnung.
- Ziel: Erzeugung eines stabilen Quantenkohärenzfeldes im Schnittpunkt der drei Strahlen

### 2.4 Symbolisch-physikalischer Wirkraum
- Im Zentrum entsteht eine strukturierte Überlagerung verschränkter Photonenfelder, die kontinuierlich auf Teilchen A einwirkt
- Diese Konfiguration soll experimentell zeigen, ob durch räumlich-symmetrische Bestrahlung eine Stabilisierung oder Modulation des Quantenzustands möglich ist – ohne Messung

---

**Fazit:**  
Die Laser erzeugen über nichtlineare Kristalle kontinuierlich verschränkte Photonenpaare. Nur ein Photon jedes Paares trifft auf Teilchen A – ohne Detektion, ohne Umleitung, ohne Kollaps. Die Verschränkung bleibt erhalten. Im Zentrum der drei Strahlen entsteht eine kohärente Quantenstruktur, die experimentell auf Stabilisierungseffekte untersucht wird.


---

## Erwartung / Hypothese

- **Wenn die Liminalis-Formel eine stabilisierende Wirkung hat,**  
  dann sollte die Superposition der verschränkten Zustände länger erhalten bleiben  
  oder spezielle Interferenzmuster zeigen, die ohne Modulation nicht auftreten.
- **Wenn nicht,** gibt es keinen messbaren Unterschied – das Ergebnis ist trotzdem wichtig für die Hypothese.

---

## Hinweise zur Durchführung

- Das Experiment ist anspruchsvoll und benötigt Zugang zu quantenoptischen Laboren.
- Alternativ können Simulationen (z. B. mit QuTiP, Qiskit oder QuTiP) erste Hinweise liefern.
- Jeder, der das Experiment aufbaut oder simuliert, ist eingeladen, die Ergebnisse offen zu dokumentieren und zu diskutieren.

---

## Offene Fragen

- Welche konkreten Parameter (Frequenzen, Amplituden, Teilchentypen) sind optimal?
- Wie genau müssen Störeinflüsse (Dekohärenz, Umweltfaktoren) kontrolliert werden?
- Gibt es alternative Wege, die Liminalis-Formel experimentell zu testen?

---

**Dieses Experiment steht unter Open-Source und ist offen für alle:  
Jede*r kann es weiterentwickeln, simulieren oder praktisch testen.**  
Bitte dokumentiert alle Versuche und Ergebnisse offen im Repository!


„Diese Datei wird laufend weiterentwickelt, sobald neue Ideen, Korrekturen oder Erkenntnisse entstehen.
Vorschläge und Diskussionen sind ausdrücklich erwünscht!“
---

(C) Raiko Pulvermacher, 2025. Siehe [GERMANCHARTA.md](./GERMANCHARTA.md).
