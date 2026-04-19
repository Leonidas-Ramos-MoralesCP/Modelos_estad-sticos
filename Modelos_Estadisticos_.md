# Tabla 1: Modelos Estadísticos para Análisis Descriptivo, Correlacional y Causal

## ANÁLISIS DESCRIPTIVO
Describir, resumir y explorar datos electorales, políticos y de políticas públicas.

| Modelo | Definición Breve |
|--------|-----------------|
| Media, Mediana, Moda | Promedio, valor central, valor más frecuente |
| Desviación Estándar | Variabilidad típica alrededor de la media |
| Rango, Percentiles | Diferencia min-max; posición en distribución |
| Tablas de Frecuencia | Cuenta de casos por categoría |
| Histogramas, Gráficos | Visualización distribuciones |
| Box Plots | Detecta outliers y asimetría |
| Análisis Bivariado | Compara dos variables |
| Tablas Cruzadas | Relación entre categorías |

---

## ANÁLISIS CORRELACIONAL
Medir asociación entre variables sin inferir causalidad.

| Modelo | Definición Breve |
|--------|-----------------|
| Correlación de Pearson (r) | Relación lineal entre variables continuas (-1 a 1) |
| Correlación de Spearman (ρ) | Relación ordinal o no-lineal |
| Correlación de Kendall (τ) | Concordancia en rankings |
| Matriz de Correlación | Todas las correlaciones pairwise simultáneamente |
| Chi-Cuadrado (χ²) | Asociación entre variables categóricas |
| Phi, Cramér's V | Fuerza de asociación categórica |
| Regresión Lineal Simple | Y = a + bX; una variable predictora |
| Regresión Múltiple (OLS) | Y = β₀ + β₁X₁ + β₂X₂ + ...; múltiples predictores |
| Regresión Polinómica | Relaciones curvilíneas (grado 2, 3, etc) |
| Regresión Exponencial | Crecimiento exponencial Y = e^(β₀ + β₁X) |
| Regresión Logística (Binaria) | P(Y=1) = 1/(1+e^(-X)); predice probabilidad |
| Regresión Ordinal | Y ordinal (bajo-medio-alto); orden importa |
| Regresión Multinomial | Y múltiples categorías no ordenadas |
| Regresión Poisson | Y conteos (eventos raros); log(λ) = β₀ + β₁X |
| Regresión Binomial Negativa | Y conteos sobredispersos; Var > Media |

---

## ANÁLISIS CAUSAL
Inferir relaciones causa-efecto; control de confundidores.

| Modelo | Definición Breve |
|--------|-----------------|
| Análisis DAG (Grafo Acíclico Dirigido) | Mapea teoría causal explícita: confundidores, mediadores |
| Variables de Control | Aísla efecto causal manteniendo otras constantes |
| Estratificación | Divide en subgrupos homogéneos y analiza dentro cada uno |
| Regresión con Controles | Y = β₀ + β₁T + β₂C₁ + ...; T es tratamiento |
| Propensity Score Matching (PSM) | Empareja tratados-control con probabilidad similar de tratamiento |
| Estratificación por PS | Estratos equiprobables en recepción tratamiento |
| Inverse Probability Weighting (IPW) | Pondera por inverso de propensity score |
| Difference-in-Differences (DiD) | Cambio diferencial antes-después x grupo control-trat |
| Regresión Discontinuidad (RDD) | Explota umbral causal (ej: edad 18 años) |
| Variables Instrumentales (IV/VI) | Maneja endogeneidad; instrumento correlado con X, no con error |
| Two-Stage Least Squares (2SLS) | Estima IV en dos etapas: Etapa 1 Y-hat; Etapa 2 Y = β₀ + β₁Y-hat |
| Efectos Fijos / Aleatorios | Panel data; controla heterogeneidad no observada por unidad |
| Diseño Cuasi-Experimental | Explota variación natural para simular experimento |
| Análisis de Mediación | Descompone: efecto directo + efecto indirecto (vía mediador) |
| Análisis de Moderación | Efecto heterogéneo; depende del valor de moderador |
| Causal Forest (ML) | Árboles para estimar efectos heterogéneos |
| BART (ML) | Bayesian Additive Regression Trees; efectos heterogéneos |
| DoWhy (Causal Package) | Framework: Identify -> Estimate -> Refute causalidad |
| Synthetic Control | Construye contrafáctico ponderando unidades de control |
| Multiple Treatment Arms | Compara 3+ políticas/tratamientos simultáneamente |

---

Creado para: Doctores en Ciencia Política y Especialistas en Políticas Públicas
