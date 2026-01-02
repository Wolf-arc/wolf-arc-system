# Resultados – Cable Wolf-Arc P

Este documento recoge los resultados de las pruebas eléctricas realizadas sobre el cable híbrido WolfLinkP, encargado de transportar simultáneamente energía y datos sin pérdida de integridad.

---

## 1. Caída de tensión (Vdrop)

| Corriente (A) | Caída medida (V) | Caída esperada (V) | Diferencia |
|---------------|------------------|---------------------|------------|
| 20 A          | 0.24 V           | 0.25 V              | -0.01 V    |
| 40 A          | 0.48 V           | 0.50 V              | -0.02 V    |
| 60 A          | 0.72 V           | 0.75 V              | -0.03 V    |

**Conclusión:**  
La caída de tensión se mantiene dentro de los márgenes de diseño (±0.05 V).  
El comportamiento es estable incluso a 60 A continuos.

---

## 2. Resistencia interna del cable

| Estado del cable | Resistencia (mΩ) |
|------------------|------------------|
| Nuevo            | 9 mΩ             |
| 500.000 ciclos   | 11 mΩ            |
| 1.000.000 ciclos | 12 mΩ            |

**Conclusión:**  
La resistencia aumenta solo un 33 % tras 1 millón de ciclos, dentro del margen previsto.

---

## 3. Temperatura del cable bajo carga

| Corriente (A) | Temp. ambiente (°C) | Temp. cable (°C) | ΔT |
|---------------|----------------------|-------------------|----|
| 20 A          | 22 °C                | 28.5 °C           | 6.5 °C |
| 40 A          | 22 °C                | 34.2 °C           | 12.2 °C |
| 60 A          | 22 °C                | 41.0 °C           | 19.0 °C |

**Conclusión:**  
Incluso a 60 A, el cable se mantiene por debajo de 45 °C, cumpliendo el límite térmico del diseño.

---

## 4. Integridad de datos con potencia simultánea

| Parámetro | Resultado |
|----------|-----------|
| BER (Bit Error Rate) | 0 |
| Retransmisiones | 0 |
| QoS | 95–96 % |
| Latencia | 3 ms |

**Conclusión:**  
La transmisión de datos no se ve afectada por la potencia.  
No se detectaron errores ni degradación de calidad.

---

## 5. Conclusión general

El cable WolfLinkP cumple con todos los requisitos eléctricos y de comunicación:

- Caída de tensión dentro de los márgenes  
- Resistencia interna estable incluso tras 1M ciclos  
- Temperatura controlada bajo carga  
- Integridad de datos perfecta
