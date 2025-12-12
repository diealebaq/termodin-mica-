# Proyecto: Primera y Segunda Ley de la Termodinámica

Este repositorio contiene una explicación completa, organizada y entendible de las dos leyes fundamentales de la termodinámica.

## Contenido del proyecto

- [Primera Ley de la Termodinámica](primera_ley.md)
- [Segunda Ley de la Termodinámica](segunda_ley.md)
- [Ejemplos y aplicaciones](ejemplos.md)

## Objetivo del repositorio
Servir como material académico para comprender:
- Conservación de energía
- Transferencia de calor y trabajo
- Entropía
- Irreversibilidad
- Máquinas térmicas y eficiencia
# Primera Ley de la Termodinámica

La Primera Ley establece que:

> **La energía no se crea ni se destruye, solo se transforma.**


# Segunda Ley de la Termodinámica

La Segunda Ley introduce el concepto de **entropía** y establece la dirección natural de los procesos, en esta , diversos autores han hecho aportes a la intepretacion de esta ley, las cuales permitireon llegar hasta la intepretacion actual.

# Definiciones de Entropía según diferentes autores

La entropía es uno de los conceptos más importantes y complejos de la termodinámica. A lo largo de la historia, diferentes autores la han definido según el enfoque teórico utilizado: termodinámico clásico, estadístico, físico-químico o ingenieril. A continuación se presentan las principales definiciones, ampliadas y ordenadas cronológicamente.

---

## 1. Rudolf Clausius (1850–1865)
**Padre del concepto de entropía.**  
Clausius introdujo el término entropía y la relacionó con la energía térmica no disponible para realizar trabajo.

**Definición:**
> "La entropía es una magnitud del estado que describe la parte de la energía que no puede transformarse en trabajo mecánico".

Además, estableció la famosa relación:

                                                        𝑑𝑆=𝛿𝑄rev/𝑇

Clausius también formuló la expresión:
> *"La entropía del universo tiende a un máximo."*

Esta fue la primera articulación clara de la irreversibilidad de los procesos naturales.

---

## 2. Ludwig Boltzmann (1877)
Boltzmann dio a la entropía una interpretación estadística profunda.

**Definición:**
> "La entropía es una medida del número de microestados accesibles por un sistema".

                                                         𝑆=𝑘ln⁡Ω

Donde:
- \( \Omega \) es el número de microestados compatibles con un macroestado,
- \( k \) es la constante de Boltzmann.

**Aporte clave:**  
Introduce la idea de que la entropía está relacionada con el **desorden molecular**, dando una base microscópica a la termodinámica.

---

## 3. J. Willard Gibbs (1902)
Gibbs extendió y generalizó la definición estadística de la entropía.

**Definición:**
> "La entropía es una función que depende de la probabilidad de los microestados y mide la distribución de energía en un sistema".

                                                        𝑆=−𝑘∑𝑝𝑖ln𝑝𝑖
													   
Es fundamental para describir sistemas con microestados no equiprobables.

---

## 4. Max Planck (1900–1917)
Planck utilizó la entropía como fundamento para su formulación de la teoría cuántica.

**Definición:**
> "La entropía es una función que determina la dirección natural de los procesos y cuya variación describe la irreversibilidad".

Para él, la entropía era la clave para entender la naturaleza del equilibrio y la radiación.

---

## 5. Peter Atkins (2014)
Atkins modernizó el concepto para facilitar su comprensión en química física.

**Definición:**
> "La entropía es una medida de la dispersión de la energía y del modo en que se distribuye en un sistema".

**Aporte clave:**  
Sustituye el concepto tradicional de “desorden” por **dispersión de energía**, evitando interpretaciones ambiguas.

---

## 6. P. W. Bridgman (1961)
Bridgman, premio Nobel, enfatizó el carácter experimental y operacional.

**Definición:**
> "La entropía es una medida de la irreversibilidad de un proceso y del desgaste energético inevitable que limita el trabajo útil".

Describe la entropía en términos de la imposibilidad práctica de revertir un proceso real.

---

## 7. Herbert Callen (1985)
Callen ofreció una formulación matemática rigurosa de la termodinámica.

**Definición:**
> "La entropía es la función que establece la estructura de equilibrio de la termodinámica y determina la dirección de la evolución espontánea".

Para Callen, la entropía es la **función fundamental del equilibrio**.

---

## 8. Smith, Van Ness y Abbott (Termodinámica Química, 2005)
Autores clave para ingeniería química.

**Definición:**
> "La entropía es una propiedad que describe el grado de dispersión de la energía y el número de configuraciones moleculares accesibles".

Integra el enfoque energético y estadístico en una sola definición.

---

## 9. Çengel y Boles (Ingeniería, 2015)
Muy usado en ingeniería mecánica y química.

**Definición:**
> "La entropía es una medida cuantitativa del desorden molecular y del grado de irreversibilidad asociado a un proceso".

Destaca la conexión entre entropía, aleatoriedad molecular e irreversibilidad.

---

## 10. Ilya Prigogine (Sistemas alejados del equilibrio)
Premio Nobel por estudios sobre termodinámica del no equilibrio.

**Definición:**
> "La entropía describe la producción de irreversibilidad en sistemas alejados del equilibrio y su tendencia natural hacia nuevas estructuras o estados".

Fue pionero en entender cómo sistemas complejos pueden generar orden mientras aumenta la entropía global.

---
# Entropía del Universo, del Sistema y del Entorno

La entropía es una propiedad termodinámica fundamental para entender la dirección natural de los procesos y la irreversibilidad. Para analizar un fenómeno se divide el universo en dos partes:

- **Sistema:** la porción del universo que se estudia.
- **Entorno (o alrededores):** todo lo que rodea al sistema.

La suma de ambos constituye el **universo termodinámico**.

---

# 1. Entropía del Universo

La entropía total del universo se define como la suma de la entropía del sistema y la del entorno:


                                             ΔS universo = ΔS sistema + ΔS entorno

De acuerdo con la **segunda ley de la termodinámica**:

- **Procesos espontáneos:**
   
                                                     ΔS universo > 0

- **Procesos reversibles:**
  
                                                     ΔS universo = 0

- **Procesos imposibles físicamente:**
  
                                                     ΔS universo < 0


### Interpretación:
La entropía del universo mide la **irreversibilidad global**.  
Toda fricción, resistencia, mezcla, disipación de calor o turbulencia incrementa la entropía del universo.

Por eso afirmamos que:

> **La entropía del universo siempre aumenta para cualquier proceso real.**

---

# 2. Entropía del Sistema

El sistema es la parte que se analiza: un gas, una sustancia, una reacción química, un motor, etc.

La entropía del sistema varía según los cambios internos de energía y el estado termodinámico.

### Para procesos reversibles:

                                                      dS sistema = δQrev/T

### Para cambios de estado a temperatura constante:

                                                      dS sistema = Qrev/T

### Propiedades importantes:

- El sistema **puede ganar o perder entropía**.
- La entropía del sistema **no determina la espontaneidad** por sí sola.
- Depende del estado interno, del volumen, temperatura y microestados accesibles.

### Interpretación:
La entropía del sistema mide:

- El **grado de dispersión** de la energía interna.  
- El **número de configuraciones microscópicas** posibles.  
- El **nivel de desorden molecular**.

---

# 3. Entropía del Entorno (o Alrededores)

En la mayoría de análisis, el entorno se modela como un **reservorio térmico** grande cuya temperatura no cambia.

Si el sistema intercambia calor Q con el entorno:

### Si el sistema recibe calor:

                                                        S = -Q / T entorno

### Si el sistema pierde calor:

                                                        S = +Q / T entorno

### Interpretación:
La entropía del entorno representa cómo afecta el proceso al resto del universo.  
Es siempre opuesta al cambio de entropía del sistema porque el calor ganado por uno es perdido por el otro.

---

# 4. Ejemplo: Fusión del hielo

**Sistema:** hielo que se derrite.  
**Entorno:** ambiente.

1. El sistema (hielo) **absorbe calor**:  
   \[
   \Delta S_{\text{sistema}} > 0
   \]

2. El entorno **pierde calor**:  
   \[
   \Delta S_{\text{entorno}} < 0
   \]

3. El aumento del sistema es mayor que la disminución del entorno:  
   \[
   \Delta S_{\text{universo}} > 0
   \]

**Resultado:** el proceso es espontáneo.

---
