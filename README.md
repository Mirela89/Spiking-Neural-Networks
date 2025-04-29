# Spiking Neural Networks (SNN) pentru Fashion MNIST

Acest proiect implementează o rețea neuronală spiking (SNN) pentru clasificarea imaginilor din setul de date [Fashion MNIST](https://github.com/zalandoresearch/fashion-mnist).

---

## Descriere

Proiectul include:

- Implementarea unui model SNN cu neuroni de tip **Leaky Integrate-and-Fire (LIF)**
- Codare **Poisson** pentru transformarea imaginilor în spike-uri
- Antrenare și evaluare pe setul **Fashion MNIST**
- Comparație cu o rețea neuronală clasică (**ANN**)

---


## Rezultate

+---------------+------------+----------------+
|     Model     | Acuratețe  | Timp Antrenare |
+---------------+------------+----------------+
| ANN           |   86.5%    | 30 secunde     |
| SNN (simplu)  |   86.2%    | 120 secunde    |
| SNN (CNN)     |   88.5%    | 180 secunde    |
+---------------+------------+----------------+

