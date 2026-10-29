# Física de los Semiconductores — Laboratorio Virtual y Simuladores Interactivos

![HTML5]([suspicious link removed])
![CSS3]([suspicious link removed])
![JavaScript]([suspicious link removed])
![UNSL]([suspicious link removed])

Repositorio oficial del **Laboratorio Virtual de Física de los Semiconductores**, desarrollado para la **Facultad de Ingeniería y Ciencias Agropecuarias (FICA)** de la **Universidad Nacional de San Luis (UNSL)**.

Este portal reúne una suite de **simuladores web interactivos** diseñados para facilitar la visualización e intuición física de conceptos cuánticos, transporte de portadores, junturas semiconductoras y transistores de efecto de campo y bipolares en la carrera de Ingeniería Electrónica.

---

## 🏛️ Información Institucional

* **Institución:** Universidad Nacional de San Luis (UNSL)
* **Facultad:** Facultad de Ingeniería y Ciencias Agropecuarias (FICA)
* **Departamento:** Departamento de Electrónica
* **Asignatura:** Física de los Semiconductores
* **Profesor Responsable:** José Luis Bossa

---

## 🚀 Acceso en Vivo (GitHub Pages)

Podés acceder al portal interactivo desplegado en tiempo real a través del siguiente enlace:

👉 **[Portal del Laboratorio Virtual de Física de los Semiconductores](https://jlbossa-git.github.io/simuladores-fisica-semiconductores/)

---

## 🔬 Simuladores Incluidos

El repositorio contiene los siguientes módulos interactivos, accesibles desde el panel central (`index.html`):

| Módulo | Tema / Concepto Clave | Archivo HTML |
| :--- | :--- | :--- |
| **01. Modelo Clásico vs. Bohr** | Cuantización de órbitas, niveles energéticos atómicos y fallas del modelo clásico. | `unidad1_modelo_clasico_vs_bohr.html` |
| **02. Nivel de Fermi y Dopaje** | Ocupación electrónica, corrimiento de $E_F$, efecto de la temperatura y dopaje N/P. | `unidad2_simulador_fermi.html` |
| **03. Transporte de Portadores** | Mecanismos de Arrastre (*Drift*) y Difusión (*Diffusion*), movilidad y relación de Einstein. | `unidad3_simuladores_transporte.html` |
| **04. Característica I-V del Diodo** | Curva exponencial de la juntura PN, polarización directa, inversa y efecto térmico. | `unidad4_simulacion_diodo.html` |
| **05. Dinámica de Juntura PN** | Zona de agotamiento, distribución de carga espacial, campo eléctrico interno y $V_0$. | `unidad4_simulacion_pn.html` |
| **06. Transistor Bipolar (BJT)** | Regiones de operación (corte, activa, saturación) e inyección de portadores minoritarios. | `unidad5_simulacion_bjt.html` |
| **07. Transistor JFET** | Efecto de campo por juntura, estrangulamiento de canal (*Pinch-off*) y conductancia. | `unidad6_simulacion_jfet.html` |
| **06. Estructura MOS y MOSFET** | Regímenes de acumulación, deplexión e inversión, tensión de umbral $V_T$ y canal N. | `unidad7_simulacion_mosfet.html` |
| **09. Comparativa JFET vs. MOSFET** | Análisis comparativo de impedancias, estructuras aisladas (MOS) y curvas características. | `unidad7_simulacion_jfet_vs_mosfet.html` |

---

## 🛠️ Tecnologías Utilizadas

* **HTML5 & CSS3:** Estructura semántica con diseño adaptable (*responsive*) y tema oscuro personalizado.
* **Vanilla JavaScript:** Lógica de simulación física en tiempo real sin dependencias externas pesadas.
* **MathJax v3:** Renderizado de ecuaciones matemáticas en formato LaTeX.
* **FontAwesome 6 & Google Fonts (Inter):** Iconografía técnica y tipografía legible.

---

## 💻 Uso Local (En tu computadora)

Si querés probar o modificar los simuladores localmente en tu computadora:

1. **Cloná el repositorio:**
   ```bash
   git clone [suspicious link removed]