# Separador de Monedas – Diseño Mecánico

Avances del diseño mecánico del **separador de monedas** del proyecto *Sistema de Logística de Monedas Inteligentes*, desarrollado en la Universidad Militar Nueva Granada (Ingeniería Mecatrónica).

> 🚧 **Estado:** en desarrollo. Este repositorio contiene únicamente los avances del diseño mecánico.

---

## 📌 Descripción

Mecanismo mecánico encargado de **clasificar y separar monedas colombianas** por denominación, a partir de su diámetro (y, si aplica, su espesor). El diseño contempla las denominaciones de la serie **antigua** y la **nueva**:

| Denominación | Serie antigua | Serie nueva |
|:------------:|:-------------:|:-----------:|
| $50          | ✅ | ✅ |
| $100         | ✅ | ✅ |
| $200         | ✅ | ✅ |
| $500         | ✅ | ✅ |
| $1.000       | ✅ | ✅ |

## 🎯 Objetivos

- Separar las 5 denominaciones (50, 100, 200, 500 y 1.000) en sus dos series.
- Diseñar un mecanismo que funcione por geometría/gravedad (sin sensores en esta etapa) *(ajustar según su diseño)*.
- Obtener piezas fabricables (impresión 3D / corte láser) *(ajustar)*.
- Servir como base física para el sistema de logística y la simulación del proyecto final.

## 📐 Dimensiones de las monedas

Valores medidos con calibrador (mm). *Completar con sus mediciones reales.*

| Moneda | Serie | Diámetro (mm) | Espesor (mm) | Masa (g) |
|:------:|:-----:|:-------------:|:------------:|:--------:|
| $50    | Antigua | – | – | – |
| $50    | Nueva   | – | – | – |
| $100   | Antigua | – | – | – |
| $100   | Nueva   | – | – | – |
| $200   | Antigua | – | – | – |
| $200   | Nueva   | – | – | – |
| $500   | Antigua | – | – | – |
| $500   | Nueva   | – | – | – |
| $1.000 | Antigua | – | – | – |
| $1.000 | Nueva   | – | – | – |

> Algunas monedas de series distintas tienen diámetros muy parecidos, por lo que la tolerancia de cada ranura es un punto crítico del diseño.

## ⚙️ Principio de funcionamiento

1. **Ingreso:** las monedas entran por la tolva / canal de alimentación.
2. **Separación:** *(describir: rampa inclinada con ranuras de ancho creciente, disco rotatorio, tamiz, etc.)*.
3. **Clasificación:** cada moneda cae por la ranura que corresponde a su diámetro, de menor a mayor.
4. **Salida:** cada denominación termina en su propio depósito.

*(Agregar aquí un diagrama o imagen del mecanismo.)*

## 🗂️ Estructura del repositorio

```
.
├── README.md
├── cad/              # Archivos CAD (SolidWorks, Fusion, STEP, etc.)
├── stl/              # Piezas listas para impresión 3D
├── planos/           # Planos 2D (PDF/DXF)
├── docs/
│   ├── imagenes/     # Renders, fotos y capturas del avance
│   └── videos/       # Videos / GIFs de pruebas
└── calculos/         # Cálculos y hojas de dimensionamiento
```

## 🖼️ Avances

### Diseño CAD
*(Insertar render del diseño)*

```markdown
![Vista general del CAD](docs/imagenes/cad_vista_general.png)
```

### Prototipo / pruebas
*(Insertar fotos o GIF de pruebas)*

```markdown
![Prueba del separador](docs/imagenes/prueba_separador.gif)
```

## 📋 Bitácora de avances

| Fecha | Avance | Observaciones |
|:-----:|--------|---------------|
| 2026-__-__ | Medición de monedas | – |
| 2026-__-__ | Primer diseño en CAD | – |
| 2026-__-__ | Primera impresión / prueba | – |

## ✅ Estado del proyecto

- [x] Levantamiento de dimensiones de las monedas
- [ ] Diseño CAD del mecanismo
- [ ] Planos de fabricación
- [ ] Fabricación del prototipo
- [ ] Pruebas con monedas de serie antigua y nueva
- [ ] Ajuste de tolerancias
- [ ] Integración con el sistema completo

## 🛠️ Herramientas

- CAD: *(SolidWorks / Fusion 360 / Inventor…)*
- Fabricación: *(impresión 3D / corte láser…)*
- Cálculos: Python

## 👥 Autores

- Julián Camilo Pérez Torres
- *(agregar compañeros)*

Universidad Militar Nueva Granada – Ingeniería Mecatrónica, 2026-2.

## 🔗 Proyecto relacionado

Simulación, dashboard y código del sistema completo: [Dispensador-de-Monedas-Proyecto-Final](https://github.com/JulianCPT/Dispensador-de-Monedas-Proyecto-Final)
