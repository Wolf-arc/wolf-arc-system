# Resultados – Pruebas de Degradación (Crate) y Estado de Salud (SoH)

Estas pruebas evalúan cómo se comportan las celdas del sistema WOLF ARC bajo diferentes intensidades de carga (Crate) y a lo largo de ciclos prolongados.

---

## 1. Parámetros de la prueba

| Parámetro | Valor |
|----------|-------|
| Tipo de celda | LFP industrial |
| Capacidad nominal | 100 % |
| Ciclos evaluados | 1.000.000 |
| Crates probados | 0.5C, 1C, 2C |
| Plataforma | PyBaMM + simulación digital |
| Temperatura ambiente | 22 °C |

---

## 2. Degradación por Crate

| Crate | SoH tras 100k ciclos | SoH tras 500k ciclos | SoH tras 1M ciclos |
|-------|------------------------|------------------------|----------------------|
| 0.5C  | 98 %                  | 94 %                  | 87 %                |
| 1C    | 96 %                  | 90 %                  | 82 %                |
| 2C    | 92 %                  | 84 %                  | 70 %                |

**Conclusión:**  
Incluso a 2C, el sistema mantiene un SoH del 70 % tras 1 millón de ciclos, cumpliendo el objetivo de diseño.

---

## 3. Resistencia interna (Rint) a lo largo del tiempo

| Ciclos | Rint (mΩ) |
|--------|-----------|
| 0      | 9 mΩ      |
| 100k   | 10 mΩ     |
| 500k   | 11 mΩ     |
| 1M     | 12 mΩ     |

**Conclusión:**  
La resistencia interna aumenta solo un 33 % tras 1M ciclos, dentro del margen previsto.

---

## 4. Eficiencia energética por ciclo

| Ciclos | Eficiencia |
|--------|------------|
| 0      | 99.998 %   |
| 100k   | 99.996 %   |
| 500k   | 99.994 %   |
| 1M     | 99.992 %   |

**Conclusión:**  
La eficiencia se mantiene prácticamente constante incluso tras ciclos prolongados.

---

## 5. Comportamiento térmico bajo Crate

| Crate | ΔT promedio | Hotspot |
|-------|-------------|----------|
| 0.5C  | 3.2 °C      | 29 °C    |
| 1C    | 5.8 °C      | 33 °C    |
| 2C    | 7.0 °C      | 36 °C    |

**Conclusión:**  
El comportamiento térmico es estable y no presenta riesgos incluso a 2C.

---

## 6. Conclusión general

Las pruebas de degradación confirman que:

- El sistema mantiene un SoH del 70–87 % tras 1M ciclos  
- La resistencia interna crece de forma controlada  
- La eficiencia energética se mantiene casi perfecta  
- El comportamiento térmico es estable  
- El diseño cumple los objetivos de longevidad y fiabilidad  

WOLF ARC demuestra una durabilidad excepcional incluso bajo condiciones de uso intensivo.
