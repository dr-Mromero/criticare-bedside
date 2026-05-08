# CritCare Bedside 🫀

**Herramienta integral de soporte a la decisión clínica en UCI para residentes de medicina interna y medicina crítica.**

## 🔗 Demo en vivo
👉 [Abrir CritCare Bedside](https://<tu-usuario>.github.io/critcare-bedside/)

## 📋 Características

### 🧮 Calculadora Hemodinámica
- **Hemodinamia**: PAM, presión de pulso, índice de choque, CRT (ANDROMEDA-SHOCK-2)
- **Oxigenación**: SpO2/FiO2, PaO2/FiO2, gradiente A-a con corrección por altitud (30+ ciudades mexicanas per Vázquez García & Pérez Padilla, 2000)
- **Mecánica ventilatoria**: Driving pressure, compliance estática, poder mecánico, PBW, Vt ideal (modalidad presión/volumen)
- **Corrección de CO2**: Ajustes de FR y Vt para meta de PaCO2
- **Gasometría completa**: pH, AG corregido, delta gap, delta ratio, Winter, trastornos primarios y mixtos
- **Correcciones hidroelectrolíticas**: Déficit de agua libre, sodio, potasio y bicarbonato con metas y velocidad de reposición

### 📊 Scores de Gravedad
- **SOFA-2** (Ranzani/Moreno, JAMA 2025): NE+EPI sumados, hemostasia recalibrada, ECMO, delirio, soporte ventilatorio expandido
- **APACHE II** (Knaus, 1985): 12 variables fisiológicas + edad + enfermedad crónica

### 🫘 Renal — KDIGO 2026
- Clasificación de 3 ejes: Creatinina (C0-C3), Gasto Urinario (U0-U3), Biomarcadores de Daño (B0-B1)
- Ventana temporal de creatinina (48h vs 7d)
- TFGe por CKD-EPI 2021 (race-free)
- Dropdown de biomarcadores (TIMP-2×IGFBP7, NGAL, KIM-1, CCL-14, Cistatina C)

### 📖 Atlas PPG
- 8 patrones de onda pletismográfica con diagramas SVG anotados
- Traducción hemodinámica completa (5 ejes) por patrón

### 📚 Referencias
- Todas las fuentes bibliográficas con enlaces directos a PubMed/JAMA/NEJM/Lancet

## 🏥 Evidencia integrada
| Fuente | Año | Integración |
|--------|-----|-------------|
| SSC 2026 | 2026 | Vasopresores, fluidos, metas PAM, antimicrobianos |
| SOFA-2 (JAMA) | 2025 | Score completo recalibrado |
| ANDROMEDA-SHOCK-2 (JAMA) | 2025 | Algoritmo CRT-PHR con fenotipos |
| BICAR-ICU 2 (JAMA) | 2025 | Actualización NaHCO3 en acidosis+LRA |
| KDIGO 2026 | 2026 | Clasificación 3 ejes C/U/B |
| SEPSISPAM (NEJM) | 2014 | Meta PAM en HTA crónica |
| Seymour (JAMA) | 2019 | Fenotipos α/β/γ/δ |
| PROSEVA (NEJM) | 2013 | Prono en SDRA severo |
| CKD-EPI 2021 (NEJM) | 2021 | TFGe race-free |

## 🚀 Despliegue

### GitHub Pages (recomendado)
1. Crear repositorio nuevo en GitHub
2. Subir `index.html`
3. Settings → Pages → Source: main branch → Save
4. Tu app estará en `https://<usuario>.github.io/<repo>/`

### Local
Simplemente abrir `index.html` en cualquier navegador.

## ⚠️ Disclaimer
Esta herramienta es un sistema de apoyo educativo a la decisión clínica. **No sustituye el juicio médico profesional**, la evaluación clínica integral ni el monitoreo hemodinámico avanzado. Todo hallazgo debe correlacionarse con el contexto clínico individual del paciente.

## 📄 Licencia
Proyecto educativo. Uso libre con atribución.
