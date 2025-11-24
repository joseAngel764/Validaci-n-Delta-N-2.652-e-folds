# ⚛️ Estudio Comparativo: Modelo CLÍA-M vs. T-Model ($\alpha$-Attractors)

## 🌟 Resumen del Proyecto

Este repositorio contiene el código de análisis y el manuscrito preliminar para la validación del **Modelo CLÍA-M** dentro de la clase de atractores-$\alpha$.

El hallazgo clave es la demostración de una **mayor eficiencia inflacionaria** de CLÍA-M ($\alpha=0.936$) en comparación con el límite T-Model de Iacconi ($\alpha=1$).

## 🎯 Resultados Clave

El estudio se centra en el número de e-folds ($N$) necesarios para que el modelo sea consistente con el índice espectral ($n_s$) observado.

| Métrica | Valor Clave | Implicación |
| :--- | :--- | :--- |
| **Diferencia de e-folds ($\Delta N$)** | $\mathbf{2.652 \text{ e-folds}}$ | El modelo CLÍA-M requiere $\mathbf{2.652}$ e-folds menos de inflación. |
| **Eficiencia Relativa** | $\mathbf{4.40\%}$ más eficiente | Ofrece una mayor flexibilidad para la fase de Recalentamiento (Reheating). |
| **Predicción $r$** | $r \approx \mathbf{0.00306}$ | Posiciona al modelo en el rango de detección de LiteBIRD y CMB-S4. |

---

## 📁 Estructura del Repositorio

| Directorio | Contenido |
| :--- | :--- |
| `CODIGO_ANALISIS/` | Script Python (`clia_m_calculos.py`) utilizado para la validación del modelo y el cálculo de $\Delta N$. |
| `PAPEL_PRINCIPAL/` | Archivos fuente LaTeX (`arXiv_Manuscript.tex`) y PDF del manuscrito para envío a arXiv. |
| `RESULTADOS/` | Documentación de los resultados (`Analisis_DeltaN.md`) y la gráfica del plano $n_s-r$ (imagen generada). |

---

## 🛠️ Uso y Validación del Código

El código principal de validación es:

```python
CODIGO_ANALISIS/clia_m_calculos.py
