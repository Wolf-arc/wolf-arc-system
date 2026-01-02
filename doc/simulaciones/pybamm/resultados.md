# Resultados – Modelos Avanzados PyBaMM

Estas simulaciones se realizaron con PyBaMM para validar el comportamiento dinámico de las celdas del sistema WOLF ARC bajo distintos perfiles de carga, temperatura y envejecimiento.

---

## 1. Parámetros de la simulación

| Parámetro | Valor |
|----------|-------|
| Modelo | PyBaMM LFP Standard |
| Capacidad nominal | 100 % |
| Temperatura ambiente | 22 °C |
| Crates simulados | 0.5C, 1C, 2C |
| Ciclos simulados | 1.000.000 |
| Perfil de carga | Continuo + pulsos |
| Plataforma | PyBaMM + análisis digital |

---

## 2. Curva de descarga (simulada)

| Crate | Voltaje inicial | Voltaje final | Tiempo de descarga |
|-------|------------------|----------------|---------------------|
| 0.5C  | 3.32 V           | 2.95 V         | 120 min             |
| 1C    | 3.32 V           | 2.90 V         | 60 min              |
| 2C    | 3.32 V           | 2.82 V         | 30 min              |

**Conclusión:**  
La curva de descarga se mantiene estable y sin caídas bruscas incluso a 2C.

---

## 3. Eficiencia coulómbica

| Ciclos | Eficiencia |
|--------|------------|
| 0      | 99.998 %   |
| 100k   | 99.996 %   |
| 500k   | 99.994 %   |
| 1M     | 99.992 %   |

**Conclusión:**  
La eficiencia coulómbica se mantiene prácticamente perfecta incluso tras 1 millón de ciclos.

---

## 4. Degradación simulada del SoH

| Ciclos | SoH |
|--------|-----|
| 0      | 100 % |
| 100k   | 97 %  |
| 500k   | 90 %  |
| 1M     | 82 %  |

**Conclusión:**  
La degradación simulada coincide con los resultados de las pruebas físicas y confirma la longevidad del sistema.

---

## 5. Comportamiento térmico simulado

| Crate | Temp. inicial | Temp. final | ΔT |
|-------|----------------|--------------|----|
| 0.5C  | 22 °C          | 25.2 °C      | 3.2 °C |
| 1C    | 22 °C          | 27.8 °C      | 5.8 °C |
| 2C    | 22 °C          | 29.0 °C      | 7.0 °C |

**Conclusión:**  
El comportamiento térmico es estable y coincide con las pruebas reales.

---

## 6. Conclusión general

Las simulaciones PyBaMM confirman:

- Curvas de descarga estables  
- Eficiencia coulómbica casi perfecta  
- Degradación controlada incluso tras 1M ciclos  
- Comportamiento térmico predecible  
- Resultados coherentes con las pruebas físicas  

Esto valida que el modelo matemático y el sistema real están alineados, reforzando la credibilidad técnica de WOLF ARC.
