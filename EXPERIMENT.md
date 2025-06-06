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

## Versuchsaufbau (vereinfachtes Beispiel)

1. **Erzeugung von verschränkten Photonenpaaren**  
   (z. B. mit einem Kristall durch Spontane Parametrische Abwärtskonversion – SPDC)

2. **Modulation eines Photons:**  
   - Das Photon A wird durch ein klassisches, externes Feld (z. B. Laser, modulierte Spannung, elektromagnetisches Feld) manipuliert.
   - Die Modulation erfolgt nach der Liminalis-Formel, z. B. mit zwei Frequenzkomponenten im Goldenen-Schnitt-Verhältnis.

3. **Messung beider Photonen:**  
   - Standardmessung von Verschränkung (z. B. mit Bell-Test, Interferometrie, Koinzidenzdetektion).
   - Spezifisch gesucht:  
     - Bleibt die Verschränkung erhalten?
     - Entstehen charakteristische Muster in der Koinzidenzrate oder in den statistischen Verteilungen der Messergebnisse?

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
