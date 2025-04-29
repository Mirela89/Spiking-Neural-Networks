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

Model:  
- **ANN**: Acuratețe = 86.5%, Timp Antrenare = 30s  
- **SNN (simplu)**: Acuratețe = 86.2%, Timp Antrenare = 120s  
- **SNN (CNN)**: Acuratețe = 88.5%, Timp Antrenare = 180s  


