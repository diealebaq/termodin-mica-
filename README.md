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

**La energía no se crea ni se destruye, solo se transforma.**

# Definición Histórica de Entropía

La entropía es una función de estado cuya variación se define clásicamente mediante la relación dS =δQrev​​/T, que expresa cómo cambia la entropía cuando un sistema intercambia calor de manera reversible a una temperatura dada. Según la interpretación presentada en el texto, esta magnitud puede entenderse como una medida del grado de dispersión o distribución de la energía en el sistema: cuanto más extensamente puede repartirse la energía entre los distintos estados posibles bajo condiciones macroscópicas fijas, mayor es la entropía. Así, la formulación clásica describe cuantitativamente el cambio de entropía en términos de calor reversible, mientras que su significado físico se relaciona con la tendencia natural de la energía a difundirse dentro del sistema.

## Clausius definio la entropía como:

                                                                 dS =δQrev​​/T

Clausius introdujo por primera vez la palabra entropía, para describir una magnitud de estado asociada al calor, donde:


-  DS= Cambio infinitesimal de entropía

- δQrev= Calor intercambiado de forma irreversible

- T= Temperatura absoluta

Para Clausius, la entropía es la magnitud que permite cuantificar el cambio del calor cuando este se reparte en un sistema a una temperatura dada durante un proceso reversible. Ese reparto del calor implica una disminución en su capacidad para producir trabajo, lo que constituye la esencia de la irreversibilidad.

## Ejemplos donde se aplica

1. Expansión libre de un gas

1 mol de gas ideal se encuentra en un recipiente con volumen inicial 
𝑉𝑖=2L y se expande libremente hasta 𝑉𝑓=6L a temperatura constante 𝑇=300K
No hay intercambio de calor con el entorno (expansión libre = adiabática e irreversible).


                                                                ΔS=nRln(Vi/​Vf)​​


ΔS≈8.314×1.0986≈9.13J/K

La energía cinética de las moléculas se distribuye ahora en un volumen mayor → mayor dispersión de energía.

La entropía aumenta Δ𝑆>0, reflejando irreversibilidad según Clausius.

2. Transferencia de calor entre cuerpos a distinta temperatura

Un bloque caliente de metal (𝐶ℎ=200J/K ,𝑇ℎ=400 K) cede calor a un bloque frío de agua (𝐶𝑐=100J/K, 𝑇𝑐=300K) hasta que alcanzan equilibrio térmico.

Tf=366.67K

Cambio de entroía en cada cuerpo:

                                                                ΔS=Cln(Ti/​Tf)


Bloque caliente: ΔSh=200ln(366.67/400)​=200ln 0.9167≈200×(−0.087)≈−17.4J/K​​

Bloque frío: ΔSc​=100ln(366.67/​300)=100ln 1.222≈100×0.200≈20.0J/K

Entropía total= ΔStotal​=ΔSh​+ΔSc​=−17.4+20.0≈2.6J/K

La entropía total aumenta, cumpliendo la segunda ley de termodinámica

El calor se dispersa del bloque caliente al frío, disminuyendo la energía utilizable para trabajo.

Representa la dispersión de energía térmica hacia estados menos concentrados y la irreversibilidad del proceso.
## Referencias

1. https://espanol.libretexts.org/Bookshelves/Quimica/Qu%C3%ADmica_General/Libro%3A_Chem1_%28Inferior%29/15%3A_Termodin%C3%A1mica_de_Equilibrios_Qu%C3%ADmicos/15.03%3A_La_Segunda_Ley_de_la_Termodin%C3%A1mica
2. https://www.britannica.com/science/entropy-physics

## Definiciones alternativas y modernas de entropía
---
### Entropía como propiedad de la termodinámica 

***Se denomina entropía a la magnitud que indica la energía que no puede realizar un trabajo útil en un proceso termodinámico.***

La entropía se define como la medida de la dispersión de la energía en un sistema. Cuanto mayor es la entropía de un sistema, mayor es su grado de aleatoridad. Se puede pensar en la entropía como una medida de la cantidad de posibles configuraciones que puede tener un sistema, considerando todas las posibles combinaciones de partículas y energía. Se denota con la letra S y se expresa en unidades de energía dividida por temperatura, generalmente en julios por kelvin (J/K).

La entropía física, en su forma clásica, es definida por la ecuación propuesta por Rudolf Clausius:

*dS=dQ/T*

Esta es una magnitud termodinámica definida originalmente como criterio para predecir la evolución de los sistemas termodinámicos. En todo proceso irreversible, el desorden del sistema aumenta y por lo tanto, la entropía aumenta. Si el proceso es reversible, la variación de entropía es nula.

La entropía de un sistema es una función de estado de carácter extensivo. El valor de esta magnitud física, en un sistema aislado, crece en el transcurso de un proceso que se da de forma natural. El concepto de entropía describe cómo es de irreversible un sistema termodinámico.

En resumen, es un concepto fundamental en la termodinámica que se utiliza para medir la dispersión de la energía en un sistema y esta afecta la capacidad de un sistema para realizar trabajo útil.

**Aplicaciones:**

- Podemos encontrar la aplicación de la entropía en las reacciones químicas. La variación de entropía nos muestra la variación del orden molecular ocurrido en una reacción química. Si el incremento de entropía es positivo, los productos presentan un mayor desorden molecular (mayor entropía) que los reactivos. En cambio, cuando el incremento es negativo, los productos son más ordenados. Hay una relación entre la entropía y la espontaneidad de una reacción química, que viene dada por la energía libre de Gibbs.

---
**Referencias:** 
1. https://solar-energia.net/termodinamica/propiedades-termodinamicas/entropia
2. https://conceptos.es/entropia-en-termodinamica
3. https://www.quimica.es/enciclopedia/Entrop%C3%ADa_%28termodin%C3%A1mica%29.html#Evidencias

---
### Entropía como calidad de información
*"La entropía en la teoría mide la incertidumbre de los resultados y se aplica en la codificación para optimizar la comprensión y transmisión de datos."*

La entropía en la teoría de la información mide la incertidumbre o la cantidad de información contenida en fuentes de datos. Una mayor entropía indica una mayor incertidumbre y variabilidad de los datos. 

En codificación, se busca minimizar la longitud promedio de los códigos mediante comprensión, directamente influenciada por la entropía.

**Algunos esquemas de codificación importantes incluyen:**

- **Codificación Huffman:** Utiliza frecuencias de aparición de los símbolos para crear un árbol binario que asigna códigos más cortos a los símbolos más comunes y códigos más largos a los menos comunes.

- **Codificación Shannon-Fano:** Divide los símbolos en grupos basados en sus probabilidades y asigna códigos de manera recursiva, asegurando que los símbolos más probables tengan códigos más cortos.

- **Codificación Aritmética:** Representa un mensaje como un número real en el intervalo [0,1), asignando subintervalos a cada símbolo basado en su probabilidad, permitiendo una compresión cercana a la entropía teórica.
compresión cercana a la entropía teórica.

**Aplicaciones Prácticas**

El uso de la entropía y métodos de codificación eficientes es crítico en diversas aplicaciones prácticas, como:

- **Compresión de datos:** Algoritmos como ZIP y JPEG utilizan técnicas basadas en la entropía para reducir el tamaño de archivos y mejorar la eficiencia del almacenamiento y la transmisión de datos.

- **Transmisión de información:** En sistemas de comunicación, minimizar la redundancia y optimizar la codificación es esencial para maximizar la tasa de transmisión y reducir errores.

- **Criptografía:** La entropía se utiliza para evaluar la seguridad de sistemas criptográficos, garantizando que las claves y mensajes sean lo suficientemente impredecibles.

---
**Referencias:** 

1. https://www.thermal-engineering.org/es/la-entropia-en-la-teoria-de-la-informacion-y-la-codificacion/

---
### Entropía como entrelazamiento de la información 

La entropía de entrelazamiento es una medida de cuánta información se comparte entre diferentes partes de un sistema. Cuando dos sistemas están entrelazados, conocer el estado de uno nos da información sobre el estado del otro. En nuestro caso, consideramos un sistema central (llamémoslo sistema-A) y un sistema de baño más grande (sistema-B). Estos dos sistemas están conectados, y sus tamaños pueden cambiar mientras que el tamaño total se mantiene fijo.

A medida que varía el tamaño de estos sistemas, sus propiedades de entrelazamiento también cambian. Las leyes de conservación de la energía guían estas variaciones, lo que significa que la energía se equilibra entre ambos sistemas.

Cuando exploramos la entropía del sistema de baño en relación con el sistema central, surgen dos conceptos importantes: "islas" e "icebergs".

- Islas se refieren a regiones específicas dentro del baño que contribuyen a la entropía total. Estas regiones están generalmente separadas del sistema principal, pero juegan un papel crucial en cómo se comparte la información.
- Icebergs son considerados como contribuciones más pequeñas a la entropía que, aunque no sean tan significativas por sí solas, juntas forman una parte importante de la entropía total.
  
Tanto las islas como los icebergs ayudan a crear una comprensión más completa de cómo opera el entrelazamiento dentro de estos sistemas.

La interacción entre el sistema-A y el sistema-B puede cambiar dependiendo de sus tamaños individuales. Cuando el sistema-B es significativamente más grande que el sistema-A, la relación entre sus entropías se vuelve más clara. En casos donde el sistema-B es pequeño, las contribuciones de las islas y los icebergs pueden desconectarse, llevando a valores de entropía calculados de manera independiente.

Sin embargo, a medida que los sistemas crecen y varían en tamaño, su entrelazamiento también se vuelve estrechamente vinculado. La entropía del baño puede verse influenciada significativamente en función de cuán grande es el sistema-A, reforzando la idea de conservación de la entropía local.

Para calcular la entropía de entrelazamiento, primero se calcula la matriz densidad reducida para uno de los subsistemas, digamos A:

*ρA=TrB(|ψAB⟩⟨ψAB|)*

Luego, se computa la entropía de von Neumann de ρA:

*SA=–Tr(ρAlogρA)*

Esta cantidad, SA, es la entropía de entrelazamiento del sistema conjunto AB. En sistemas bipartitos puramente entrelazados, la entropía de entrelazamiento es máxima, indicando una fuerte correlación cuántica.

**Aplicaciones**

- Un ejemplo clásico de un estado entrelazado es el estado de Bell, que es una superposición de dos estados cuánticos base:

  *|ψAB⟩=12–√(|00⟩+|11⟩)*

  En este caso, si se efectúa una medida en uno de los subsistemas, el estado del otro subsistema queda instantáneamente determinado, mostrando una correlación perfecta entre A y B.

- Otro ejemplo es en la termodinámica, donde la entropía clásica mide el desorden o la incertidumbre en un sistema. De manera similar, la entropía de entrelazamiento puede interpretarse como una medida de la incertidumbre o la correlación intrínseca entre los subsistemas en un estado cuántico.
  
  Un aspecto fascinante de la entropía de entrelazamiento es su comportamiento en fases críticas de la materia. En física de la materia condensada, se ha observado que la entropía de entrelazamiento puede revelar información sobre transiciones de fase cuántica y la estructura de correlación en sistemas de muchos cuerpos.

  Además, en el contexto de la gravitación cuántica y la teoría de cuerdas, la entropía de entrelazamiento juega un papel crucial en la comprensión de la dinámica de agujeros negros y la holografía. Por ejemplo, el principio holográfico sugiere que toda la información contenida en un volumen de espacio puede ser descrita por una teoría que reside en su frontera. En estos estudios, la entropía de entrelazamiento es esencial para entender cómo se almacena y se transfiere la información.

---
**Referencias:** 

1. https://modern-physics.org/entropia-de-entrelazamiento-vision-general-y-significado/ 

2. https://modern-physics.org/entropia-de-entrelazamiento-vision-general-y-significado/
   
---

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
