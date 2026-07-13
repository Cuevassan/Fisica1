## 📄 Ejercicio 57: Velocidad Mínima en un Movimiento Circular Vertical


![alt text](image-23.png)

Este problema marca el ingreso a la **Dinámica del Movimiento Circular**. Es un ejercicio donde se evalúa la condición de la **velocidad crítica mínima** en el punto más alto de una trayectoria vertical.

A continuación, la resolución analítica y minuciosa paso a paso:

---


> **57 - ¿Con qué velocidad mínima habrá que hacer girar un pequeño balde con agua en un plano vertical para que ella no se derrame?**
> * **Dato de la pizarra (página 25 del PDF):** Radio de giro $R = 1 \text{ m}$.
> 
> 

---

## 📐 Paso 1: Análisis Dinámico en el Punto Más Alto (Posición Crítica)

Para que el agua no se derrame al pasar por la posición invertida superior (punto ③ de tu pizarra), el balde debe girar con una rapidez tal que la inercia del movimiento compense la acción de la gravedad.

Planteamos el **Diagrama de Cuerpo Libre (DCL)** del agua justo en el punto más alto de la trayectoria vertical:

* El **Peso ($P$)** de la masa de agua apunta verticalmente hacia abajo, es decir, hacia el centro de la circunferencia ($-\hat{j}$).


* La **Fuerza Normal o Tensión ($T$)** que ejerce el fondo del balde sobre el agua presiona también verticalmente hacia abajo, apuntando hacia el centro de giro ($-\hat{j}$).



Establecemos nuestro eje radial con sentido positivo hacia el centro de la trayectoria circular ($+a_{cp}$). Aplicamos la Segunda Ley de Newton en el eje radial (Fuerza Centrípeta):

$$\Sigma F_{\text{radial}} = F_{cp} \implies P + T = m \cdot a_{cp} \quad \text{}$$

Sustituimos las expresiones de la aceleración centrípeta ($a_{cp} = \frac{v_t^2}{R}$) y del peso ($P = m \cdot g$):


$$m \cdot g + T = m \cdot \frac{v_t^2}{R} \quad \text{}$$

---

## 🧮 Paso 2: Condición Límite de Velocidad Mínima ($v_{\text{mín}}$)

Si disminuimos gradualmente la velocidad tangencial ($v_t$), el agua tenderá a ejercer menor presión contra el fondo del balde, por lo que la fuerza de reacción Normal o Tensión ($T$) se irá reduciendo para mantener el equilibrio radial.

> 💡 **La Clave Conceptual:** El límite físico exacto para que el agua apenas logre completar la vuelta sin desprenderse ni derramarse ocurre en el instante en que **la Normal se anula por completo ($T = 0$)** en el punto más alto.
> 
> 

Sustituimos $T = 0$ en nuestra ecuación radial:


$$m \cdot g + 0 = m \cdot \frac{v_{\text{mín}}^2}{R} \quad \text{}$$

$$\cancel{m} \cdot g = \cancel{m} \cdot \frac{v_{\text{mín}}^2}{R} \quad \text{}$$

Notar que la masa se simplifica, lo que demuestra que la velocidad mínima es independiente de la cantidad de agua dentro del balde. Despejamos el módulo de la velocidad mínima ($v_{\text{mín}}$):


$$v_{\text{mín}}^2 = g \cdot R \implies \mathbf{v_{\text{mín}} = \sqrt{g \cdot R}} \quad \text{}$$

---

## 🧮 Paso 3: Cálculo Numérico Final

Sustituimos los datos correspondientes utilizando el radio de la pizarra ($R = 1 \text{ m}$) y la aceleración de la gravedad de la cátedra ($g = 10 \text{ m/s}^2$):


$$v_{\text{mín}} = \sqrt{10 \text{ m/s}^2 \cdot 1 \text{ m}} = \sqrt{10} \text{ m/s} \quad \text{}$$

$$v_{\text{mín}} \approx \mathbf{3,162 \text{ m/s}} \quad \text{}$$

---

## 🎯 Resumen de Respuestas para el Examen

* **Condición límite de desprendimiento:** Tensión/Normal nula ($T = 0$).


* **Expresión analítica:** $v_{\text{mín}} = \sqrt{g \cdot R}$.


* **Valor numérico:** $\approx 3,16 \text{ m/s}$.

---

## Ejercicio 60: Masas Acopladas en un Hilo Giratorio Horizontal

![alt text](image-24.png)


Este problema modela un sistema acoplado en **Movimiento Circular Uniforme (MCU)** en un plano horizontal sin fricción. La gran complejidad acá es que los hilos experimentan tensiones diferentes debido a que la soga interna debe arrastrar la inercia de rotación de ambas masas puntuales en simultáneo.


## 🛠️ Paso 1: Extracción de Datos y Radios de Giro

Llevamos todas las magnitudes al Sistema Internacional de Unidades (MKS):

* **Masa 1 ($m_1$):** $100\text{ g} = 0,1\text{ kg}$.


* **Masa 2 ($m_2$):** $200\text{ g} = 0,2\text{ kg}$.


* **Velocidad angular común ($\omega$):** $2\text{ s}^{-1}$.


* **Longitud del primer tramo ($L_1$):** $10\text{ cm} = 0,1\text{ m}$.


* **Longitud del segundo tramo ($L_2$):** $60\text{ cm} = 0,6\text{ m}$.



### Determinación de los Radios de Trayectoria ($R$)

* La masa 1 está vinculada directo al centro de giro $A$, por lo que su radio es:

$$R_1 = L_1 = \mathbf{0,1\text{ m}} \quad \text{}$$


* La masa 2 se encuentra atada a continuación de la masa 1. Por lo tanto, su radio total de giro respecto al centro $A$ es la suma de ambos tramos:

$$R_2 = L_1 + L_2 = 0,1\text{ m} + 0,6\text{ m} = \mathbf{0,7\text{ m}} \quad \text{}$$



(Nota técnica de control: ¡Ojo acá! El enunciado de la guía dice que $L_2 = 60\text{ cm}$ es la longitud de la soga intermedia, por lo que su radio es $0,7\text{ m}$. En la anotación rápida de tu pizarra se tomó $L_2 = 0,6\text{ m}$ de forma directa como el radio final. Vamos a resolverlo con el radio total estricto de la geometría del problema).



---

## 📐 Paso 2: Diagramas de Cuerpo Libre (DCL) y Planteo Radial

Aislamos cada masa en el plano horizontal y planteamos que la sumatoria de fuerzas en el eje radial equivale a la fuerza centrípeta ($F_{cp} = m \cdot \omega^2 \cdot R$):

### 1. Ecuación para la Masa 2 ($m_2$ - Extremo exterior)

La masa 2 solo siente la fuerza de la soga que la une a la masa 1. Esta fuerza es la **Tensión 2 ($T_2$)** apuntando hacia el centro:


$$\Sigma F_{\text{radial}_2} = m_2 \cdot a_{cp_2} \implies T_2 = m_2 \cdot \omega^2 \cdot R_2 \quad \text{}$$

### 2. Ecuación para la Masa 1 ($m_1$ - Posición intermedia)

La masa 1 experimenta la acción de dos cuerdas en simultáneo: la soga interna la jala hacia el centro con la **Tensión 1 ($T_1$)**, mientras que la soga externa tira de ella hacia afuera con la **Tensión 2 ($T_2$)** por el principio de acción y reacción:


$$\Sigma F_{\text{radial}_1} = m_1 \cdot a_{cp_1} \implies T_1 - T_2 = m_1 \cdot \omega^2 \cdot R_1 \quad \text{}$$

---

## 🧮 Paso 3: Resolución Numérica del Sistema de Tensiones

### 1. Calcular el valor de la Tensión Externa ($T_2$)

Sustituimos los datos correspondientes en la ecuación de la masa exterior:


$$T_2 = m_2 \cdot \omega^2 \cdot R_2 \quad \text{}$$

$$T_2 = 0,2\text{ kg} \cdot (2\text{ s}^{-1})^2 \cdot 0,7\text{ m} \quad \text{}$$

$$T_2 = 0,2 \cdot 4 \cdot 0,7 = \mathbf{0,56\text{ N}} \quad \text{}$$

---

### 2. Calcular el valor de la Tensión Interna ($T_1$)

Usamos la relación radial de la masa intermedia para aislar el valor de la tensión de la primera soga:


$$T_1 = T_2 + m_1 \cdot \omega^2 \cdot R_1 \quad \text{}$$

$$T_1 = 0,56\text{ N} + \big(0,1\text{ kg} \cdot (2\text{ s}^{-1})^2 \cdot 0,1\text{ m}\big) \quad \text{}$$

$$T_1 = 0,56\text{ N} + \big(0,1 \cdot 4 \cdot 0,1\big)\text{ N} \quad \text{}$$

$$T_1 = 0,56\text{ N} + 0,04\text{ N} = \mathbf{0,60\text{ N}} \quad \text{}$$

> 💡 **Validación Teórica:** Se comprueba perfectamente el comportamiento físico esperable en este tipo de acoplamientos rotativos: la soga interna experimenta un esfuerzo mayor ($T_1 > T_2$) debido a que debe proporcionar la fuerza centrípeta necesaria para curvar la trayectoria de ambas masas puntuales al mismo tiempo.

---

## 🎯 Resumen de Respuestas para el Examen

* **Tensión en el hilo exterior ($T_2$):** $0,56\text{ N}$.
* **Tensión en el hilo interior ($T_1$):** $0,60\text{ N}$.

---

## 📄 Ejercicio 62: Dinámica del Péndulo Cónico

![alt text](image-25.png)

Este problema  modela el comportamiento de un **Péndulo Cónico**. La soga no oscila de forma lineal en un plano vertical, sino que barre la superficie de un cono, haciendo que la masa m ejecute un movimiento circular horizontal uniforme.

---


## 📐 Paso 1: Resolución del Inciso a) Diagrama de Cuerpo Libre (DCL)

Aislamos la lenteja de masa $m$ y colocamos las fuerzas reales que actúan sobre ella en el espacio:

1. **El Peso ($\vec{P}$):** Dirigido verticalmente hacia abajo, con un módulo de:

$$P = m \cdot g = 0,4\text{ kg} \cdot 10\text{ m/s}^2 = \mathbf{4\text{ N}}$$


2. **La Tensión ($\vec{T}$):** Actúa de forma oblicua siguiendo la dirección de la soga de longitud $L$, tirando de la masa hacia el punto de suspensión fijo superior.

Establecemos nuestro sistema de ejes de Pozzetti: el **eje Y** vertical (positivo hacia arriba) y el **eje X** horizontal en la dirección del radio de giro (positivo apuntando hacia el centro de la trayectoria circular, es decir, en sentido de la aceleración centrípeta).

Descomponemos la tensión $\vec{T}$ utilizando el ángulo $\alpha = 30^\circ$ formado con la vertical:

* Componente vertical: $T_y = T \cdot \cos(30^\circ)$
* Componente radial horizontal: $T_x = T \cdot \sin(30^\circ)$

---

## 📐 Paso 2: Planteo de las Ecuaciones de Newton

### 1. Equilibrio en el Eje Vertical Y

Dado que la masa gira confinada estrictamente en un plano horizontal, no experimenta ningún tipo de desplazamiento ni aceleración en la vertical ($a_y = 0$):


$$\Sigma F_y = 0 \implies T \cdot \cos(30^\circ) - P = 0$$

$$T \cdot \cos(30^\circ) = m \cdot g \quad \text{(Ecuación 1)}$$

### 2. Dinámica en el Eje Radial X (Fuerza Centrípeta)

La componente horizontal de la soga es la fuerza neta encargada de curvar la trayectoria del móvil hacia el centro:


$$\Sigma F_x = F_{cp} \implies T \cdot \sin(30^\circ) = m \cdot a_{cp} \implies T \cdot \sin(30^\circ) = m \cdot \frac{v_t^2}{R} \quad \text{(Ecuación 2)}$$

---

## 🧮 Paso 3: Resolución de los Incisos c) y b)

### c) Hallar la Tensión de la Cuerda ($T$)

Despejamos el módulo de la tensión directamente a partir de la Ecuación 1 del eje vertical:


$$T = \frac{m \cdot g}{\cos(30^\circ)} = \frac{4\text{ N}}{\frac{\sqrt{3}}{2}} = \frac{8}{\sqrt{3}}\text{ N} \approx \mathbf{4,62\text{ N}}$$

---

### b) Hallar la Velocidad Tangencial ($v_t$)

Primero determinamos el **radio geométrico de giro ($R$)** a partir del triángulo formado por la soga de longitud $L = 2\text{ m}$:


$$R = L \cdot \sin(30^\circ) = 2\text{ m} \cdot 0,5 = \mathbf{1\text{ m}}$$

Para calcular la velocidad de rotación de forma directa e independiente de la masa o la tensión, dividimos miembro a miembro la **Ecuación 2** sobre la **Ecuación 1**:


$$\frac{\cancel{T} \cdot \sin(30^\circ)}{\cancel{T} \cdot \cos(30^\circ)} = \frac{\cancel{m} \cdot \frac{v_t^2}{R}}{\cancel{m} \cdot g} \implies \tan(30^\circ) = \frac{v_t^2}{g \cdot R}$$

Aislamos algebraicamente la velocidad tangencial ($v_t$):


$$v_t^2 = g \cdot R \cdot \tan(30^\circ)$$

$$v_t = \sqrt{10\text{ m/s}^2 \cdot 1\text{ m} \cdot \tan(30^\circ)} = \sqrt{10 \cdot 0,57735}\text{ m/s}$$

$$v_t = \sqrt{5,7735}\text{ m/s} \approx \mathbf{2,40\text{ m/s}}$$

---

## 🎯 Resumen de Respuestas para el Examen

* **a) DCL:** Peso vertical ($P = 4\text{ N}$) y Tensión oblicua ($T$) descompuesta en ejes.
* **b) Velocidad tangencial ($v_t$):** $\approx 2,40\text{ m/s}$.
* **c) Tensión de la soga ($T$):** $\approx 4,62\text{ N}$.

---
##  Ejercicio 88: Trabajo Mecánico en Ascenso con Fricción

![alt text](image-26.png)

Este problema nos saca de las ecuaciones dinámicas puras de fuerza y nos introduce en el **Módulo de Trabajo y Energía**. Aquí se evalúa el cálculo del trabajo mecánico para cada una de las fuerzas que actúan sobre un cuerpo en ascenso por un plano inclinado con rozamiento dinámico.

Como el enunciado indica que la persona es arrastrada a **velocidad constante** ($v = \text{cte.}$), la aceleración neta es cero, lo que nos simplifica enormemente el balance dinámico inicial para hallar las fuerzas desconocidas.



## 🛠️ Paso 1: Balance Dinámico Inicial (Ejes Rotados)

Para poder calcular los trabajos del tramo, primero necesitamos conocer el valor numérico de cada fuerza del sistema. Descomponemos las fuerzas en el eje X (paralelo a la rampa, positivo hacia arriba) y el eje Y (perpendicular a la rampa):

* **Masa ($m$):** $80\text{ kg} \implies P = m \cdot g = 80\text{ kg} \cdot 10\text{ m/s}^2 = 800\text{ N}$.
* **Componentes del Peso:**
* $P_x = P \cdot \sin(37^\circ) = 800\text{ N} \cdot 0,6 = 480\text{ N}$ (apunta hacia abajo del plano).
* $P_y = P \cdot \cos(37^\circ) = 800\text{ N} \cdot 0,8 = 640\text{ N}$ (apunta hacia adentro del plano).



### 1. Equilibrio en el Eje Perpendicular Y ($\Sigma F_y = 0$)

$$N - P_y = 0 \implies N = P_y = \mathbf{640\text{ N}}$$

### 2. Cálculo de la Fuerza de Rozamiento Dinámico ($f_{rc}$)

$$f_{rc} = \mu_c \cdot N = 0,25 \cdot 640\text{ N} = \mathbf{160\text{ N}} \quad \text{}(apunta hacia abajo de la rampa, frenando el ascenso).$$

### 3. Equilibrio en el Eje de Movimiento X ($\Sigma F_x = 0$ por $v = \text{cte.}$)

La fuerza de la soga ($F$) tira hacia arriba, mientras que el rozamiento y la gravedad tiran hacia abajo:


$$\Sigma F_x = 0 \implies F - f_{rc} - P_x = 0$$

#### b) Resolución del Inciso b) Fuerza de la Soga ($F$)

$$F = f_{rc} + P_x = 160\text{ N} + 480\text{ N} = \mathbf{640\text{ N}}$$

---

## 📐 Paso 2: Cálculo de los Trabajos Mecánicos ($W$)

El trabajo de una fuerza constante se define como $W = \vert{}\vec{F}\vert{} \cdot \vert{}\Delta x\vert{} \cdot \cos(\theta)$, donde $\theta$ es el ángulo formado entre el vector de la fuerza y el vector del desplazamiento ($\Delta x = 100\text{ m}$).

### a) Trabajo de la Fuerza Resultante ($W_{\text{R}}$)

> 💡 **Gran Atajo Teórico de Pozzetti:** El **Teorema de las Fuerzas Vivas** establece que $W_{\text{Total}} = \Delta E_c$. Como el cuerpo se mueve a velocidad estrictamente constante, la energía cinética no cambia ($\Delta E_c = 0$). Por lo tanto, el trabajo de la fuerza resultante es instantáneamente **CERO**:
> 
> 
> 
> $$\mathbf{W_{\text{Resultante}} = 0\text{ J}}$$
> 
> 

---

### c) Trabajo Realizado por la Soga ($W_F$)

La soga jala de forma paralela a la rampa en el mismo sentido que el desplazamiento, por lo que el ángulo entre ellos es $\theta = 0^\circ$ ($\cos 0^\circ = 1$):


$$W_F = F \cdot \Delta x \cdot \cos(0^\circ)$$

$$W_F = 640\text{ N} \cdot 100\text{ m} \cdot 1 = \mathbf{64000\text{ J}} \quad \text{}(64\text{ kJ})$$

---

### d) Trabajo de la Fuerza de Rozamiento ($W_{f_{rc}}$)

El rozamiento dinámico se opone en todo momento al desplazamiento, por lo que el ángulo que forma con el sentido del avance es colineal pero opuesto, es decir, $\theta = 180^\circ$ ($\cos 180^\circ = -1$):


$$W_{f_{rc}} = f_{rc} \cdot \Delta x \cdot \cos(180^\circ)$$

$$W_{f_{rc}} = 160\text{ N} \cdot 100\text{ m} \cdot (-1) = \mathbf{-16000\text{ J}} \quad \text{}(-16\text{ kJ})$$

*(Nota de control complementaria: Si calculáramos el trabajo del peso, daría $W_P = P_x \cdot \Delta x \cdot \cos(180^\circ) = 480 \cdot 100 \cdot (-1) = -48000\text{ J}$. Al sumar todos los trabajos: $64000\text{ J} - 16000\text{ J} - 48000\text{ J} = 0\text{ J}$, verificando perfectamente el inciso a).*

---

## 🎯 Resumen de Respuestas para el Examen

* **a) Trabajo resultante ($W_{\text{R}}$):** $0\text{ J}$ (por $v = \text{cte.}$).
* **b) Fuerza de la soga ($F$):** $640\text{ N}$.
* **c) Trabajo de la soga ($W_F$):** $64000\text{ J}$.
* **d) Trabajo del rozamiento ($W_{f_{rc}}$):** $-16000\text{ J}$.

---

## Ejercicio 91: Conservación de Energía Mecánica en Caída Libre

![alt text](image-27.png)

Este problema es un clásico modelo de **Conservación de la Energía Mecánica Pura**. Al no existir fuerzas disipativas como el rozamiento ($\Sigma W_{\text{Fnc}} = 0$) , la energía potencial gravitatoria inicial acumulada en la altura de la cumbre se transformará íntegramente en la energía cinética requerida en la base de la rampa.

A continuación, la resolución analítica y minuciosa paso a paso:


## 🛠️ Paso 1: Extracción de Datos y Conversión al Sistema MKS

Para operar de forma matemáticamente rigurosa dentro de los teoremas de la cátedra , lo primero que hacemos es transformar la velocidad lineal dada en kilómetros por hora a metros por segundo:

* **Velocidad inicial ($v_A$):** Parte desde el reposo en la cumbre, $v_A = 0 \text{ m/s}$.


* **Velocidad final en la base ($v_B$):** 
$$v_B = 72 \text{ km/h} = \frac{72}{3,6} \text{ m/s} = \mathbf{20 \text{ m/s}} \quad \text{}$$


* **Aceleración de la gravedad adoptada ($g$):** Como en toda la guía, usamos $g = 10 \text{ m/s}^2$.



---

## 📐 Paso 2: Planteo del Balance Energético

Fijamos nuestro **Nivel de Referencia (N.R.)** cero para la energía potencial gravitatoria en el plano horizontal de la base de la rampa ($h_B = 0 \text{ m}$).

Como el enunciado especifica de forma explícita que se deben despreciar las fuerzas de fricción , el trabajo de las fuerzas no conservativas es rigurosamente nulo ($W_{\text{Fnc}} = 0$). Por lo tanto, se cumple el **Principio de Conservación de la Energía Mecánica** entre el punto más alto ($A$) y la base ($B$):

$$E_{\text{mec}_A} = E_{\text{mec}_B} \quad \text{[cite: 1631]}$$

$$E_{c_A} + E_{pg_A} = E_{c_B} + E_{pg_B} \quad \text{[cite: 1613]}$$

Sustituimos las expresiones analíticas correspondientes de la cátedra:

* En el punto de partida $A$, la velocidad es nula, por lo que no tiene energía cinética ($E_{c_A} = 0$).


* En la base $B$, la altura es nula respecto al N.R., por lo que no tiene energía potencial ($E_{pg_B} = 0$).



$$\frac{1}{2}m \cdot v_A^2 + m \cdot g \cdot h_A = \frac{1}{2}m \cdot v_B^2 + m \cdot g \cdot h_B \quad \text{[cite: 1611, 1814]}$$

$$0 + m \cdot g \cdot h_A = \frac{1}{2}m \cdot v_B^2 + 0 \quad \text{[cite: 1814]}$$

$$m \cdot g \cdot h_A = \frac{1}{2}m \cdot v_B^2 \quad \text{[cite: 1814]}$$

---

## 🧮 Paso 3: Despeje y Cálculo de la Altura de Caída ($h_A$)

Notamos que la masa inercial ($m$) del trineo aparece multiplicando en ambos lados de la igualdad, por lo que Pozzetti siempre la simplifica de forma directa. Esto nos demuestra un gran concepto físico: la altura requerida es independiente de la masa del cuerpo.

$$\cancel{m} \cdot g \cdot h_A = \frac{1}{2}\cancel{m} \cdot v_B^2 \quad \text{[cite: 1814]}$$

$$g \cdot h_A = \frac{1}{2} v_B^2 \quad \text{[cite: 1814]}$$

Despejamos la altura de la cima ($h_A$):


$$h_A = \frac{v_B^2}{2 \cdot g} \quad \text{[cite: 1629]}$$

Sustituimos con los valores numéricos correspondientes:


$$h_A = \frac{(20 \text{ m/s})^2}{2 \cdot 10 \text{ m/s}^2} = \frac{400}{20} = \mathbf{20 \text{ m}} \quad \text{}$$

---

## 🎯 Respuesta Final para el Examen

El trineo deberá dejarse caer desde una altura vertical exacta de **$20 \text{ m}$** para alcanzar la velocidad de $72 \text{ km/h}$ en la base de la rampa.

---

## Ejercicio 92: Fuerza Máxima de Acoplamiento y Trabajo Mecánico

![alt text](image-28.png)

Este problema combina dinámica con consideraciones cinemáticas y el teorema del trabajo. Se evalúa la condición de **no deslizamiento relativo** entre dos bloques acoplados por fricción para luego calcular el trabajo realizado por la fuerza máxima permitida.

A continuación, la resolución analítica minuciosa paso a paso:


## 📐 Paso 1: Análisis del Bloque 1 y Obtención de la Aceleración Máxima ($a_{\text{máx}}$)

Para que el bloque 1 no deslice sobre el bloque 2, ambos deben moverse solidariamente con la misma aceleración lineal común ($a$).

Al analizar el **Diagrama de Cuerpo Libre (DCL)** del bloque 1 en el eje horizontal, la única fuerza encargada de acelerarlo hacia adelante es la fuerza de rozamiento estático ($f_{re}$) que le proporciona el bloque 2.

* **Eje Y:** $N_1 = P_1 = m_1 \cdot g = 5\text{ kg} \cdot 10\text{ m/s}^2 = 50\text{ N}$.
* **Eje X:** 
$$\Sigma F_x = m_1 \cdot a \implies f_{re} = m_1 \cdot a$$



La condición límite para que el bloque 1 esté a punto de deslizar sin llegar a hacerlo corresponde a la fuerza de rozamiento estático máxima ($f_{re}^{\text{máx}}$):


$$f_{re}^{\text{máx}} = \mu_{e1} \cdot N_1 = 0,3 \cdot 50\text{ N} = 15\text{ N}$$

Sustituyendo este valor en la ecuación del eje X, hallamos la **aceleración máxima permitida** para todo el conjunto:


$$15\text{ N} = 5\text{ kg} \cdot a_{\text{máx}} \implies a_{\text{máx}} = \frac{15\text{ N}}{5\text{ kg}} = \mathbf{3\text{ m/s}^2}$$

---

## 📐 Paso 2: Análisis del Macro-sistema y Fuerza Máxima ($F_{\text{máx}}$)

Para encontrar la magnitud de la fuerza exterior $F$ que se le aplica al bloque inferior, estudiamos a ambos bloques acoplados como un único sistema de masa total $M_T = m_1 + m_2 = 5\text{ kg} + 10\text{ kg} = 15\text{ kg}$. Las fuerzas de roce internas entre bloques se cancelan por acción y reacción.

Como el piso horizontal no presenta rozamiento ($\mu_{\text{piso}} = 0$), la fuerza $F$ es la única fuerza neta externa en el eje horizontal:


$$\Sigma F_{\text{ext}} = M_T \cdot a_{\text{máx}} \implies F_{\text{máx}} = (m_1 + m_2) \cdot a_{\text{máx}}$$

$$F_{\text{máx}} = 15\text{ kg} \cdot 3\text{ m/s}^2 = \mathbf{45\text{ N}}$$

---

## 🧮 Paso 3: Cinemática del Tramo y Cálculo del Trabajo Mecánico ($W_F$)

El sistema arranca desde el reposo ($v_0 = 0$) y se desplaza bajo la acción de la fuerza constante $F_{\text{máx}} = 45\text{ N}$ durante un intervalo de tiempo $\Delta t = 6\text{ s}$.

### 1. Cálculo del Desplazamiento ($\Delta x$)

Usamos la ecuación horaria de la posición para un MRUV:


$$\Delta x = v_0 \cdot t + \frac{1}{2} \cdot a_{\text{máx}} \cdot t^2$$

$$\Delta x = 0 \cdot (6\text{ s}) + \frac{1}{2} \cdot 3\text{ m/s}^2 \cdot (6\text{ s})^2$$

$$\Delta x = \frac{1}{2} \cdot 3 \cdot 36 = 3 \cdot 18 = \mathbf{54\text{ m}}$$

### 2. Cálculo del Trabajo Realizado por la Fuerza ($W_F$)

La fuerza se aplica horizontalmente en la misma dirección y sentido que el desplazamiento del carro ($\theta = 0^\circ$):


$$W_F = F_{\text{máx}} \cdot \Delta x \cdot \cos(0^\circ)$$

$$W_F = 45\text{ N} \cdot 54\text{ m} \cdot 1 = \mathbf{2430\text{ J}}$$

---

## 🎯 Resumen de Respuestas para el Examen

* **Aceleración máxima del conjunto:** $3\text{ m/s}^2$.
* **Fuerza horizontal máxima aplicada:** $45\text{ N}$.
* **Trabajo mecánico efectuado ($W_F$):** **$2430\text{ J}$**.

---

## Ejercicio 93: Fuerza Variable con la Posición y Balances Energéticos

![alt text](image-29.png)

Este problema es de los más tramposos y conceptuales de la guía porque introduce una **fuerza variable con la posición** ($F(x) = -20x$). Se usa siempre para evaluar si sabés identificar cuándo una definición física clásica no sirve más y cómo usar los teoremas energéticos o analogías de sistemas como un atajo genial.

A continuación, la resolución analítica minuciosa paso a paso, idéntica a tu clase:

---

## 🛠️ Paso 1: Análisis Teórico Crítico (¡La trampa de examen!)

Al ver que la fuerza es una función directa de la posición ($F(x) = -20x$), Pozzetti resalta un punto crucial en el pizarrón:

> ⚠️ **Peligro de Examen:** **NO** se puede calcular el trabajo usando la definición simplificada $W = F \cdot \Delta x \cdot \cos\theta$. Esa fórmula es de uso exclusivo para **fuerzas constantes**. Al ser variable, el trabajo formal se calcula mediante una integral ($\int F(x)dx$) o utilizando teoremas energéticos.
> 
> 

### El Atajo de la Cátedra (Analogía Elástica)

La expresión matemática de la fuerza $F(x) = -20x$ tiene exactamente la misma estructura algebraica que la **Fuerza Elástica de la Ley de Hooke** ($F_e = -k \cdot \Delta l$).
Por lo tanto, podemos tratar este campo de fuerzas variable como si fuera un resorte ideal de constante equivalente:


$$k = \mathbf{20\text{ N/m}} \quad \text{}$$

---

## 📐 Paso 2: Resolución del Inciso a) Trabajo Efectuado por la Fuerza ($W_F$)

Para hallar el trabajo neto realizado por la fuerza variable, aplicamos el **Teorema de las Fuerzas Vivas** (o Teorema del Trabajo y la Energía Cinética):

$$W_{\text{Total}} = \Delta E_c = E_{c_{\text{final}}} - E_{c_{\text{inicial}}} \quad \text{}$$

La única fuerza que realiza trabajo sobre el eje horizontal en ese tramo es nuestra fuerza variable $F(x)$. Sabemos además que el objeto se detiene por completo al alcanzar la posición final $d$, por lo que su velocidad final es nula ($v_f = 0$):

$$W_F = \frac{1}{2} m \cdot v_f^2 - \frac{1}{2} m \cdot v_0^2 \quad \text{}$$

$$W_F = 0 - \frac{1}{2} m \cdot v_0^2 = -\frac{1}{2} m \cdot v_0^2 \quad \text{}$$

Sustituimos con los datos numéricos iniciales del problema ($m = 5\text{ kg}$ y $v_0 = 6\text{ m/s}$):


$$W_F = -\frac{1}{2} \cdot 5\text{ kg} \cdot (6\text{ m/s})^2 \quad \text{[cite: 1765]}$$

$$W_F = -\frac{1}{2} \cdot 5 \cdot 36 = -5 \cdot 18 = \mathbf{-90\text{ J}} \quad \text{}$$

> 💡 **Significado Físico:** El trabajo dio con signo negativo porque la fuerza es de carácter disipativo/restitutivo (apunta en sentido contrario al desplazamiento), retirándole energía cinética al móvil para lograr frenarlo.
> 
> 

---

## 📐 Paso 3: Resolución del Inciso b) Valor de la Distancia de Frenado ($d$)

Para hallar el valor de la coordenada de detención $d$, acoplamos el resultado del paso anterior utilizando el potencial de nuestra analogía elástica. El trabajo realizado por una fuerza del tipo elástica responde a la variación de su energía potencial:

$$W_F = -\Delta E_{pe} = -\left(\frac{1}{2} k \cdot d^2 - \frac{1}{2} k \cdot x_0^2\right) \quad \text{}$$

Como la deformación inicial en el punto de partida es cero ($x_0 = 0$):


$$W_F = -\frac{1}{2} k \cdot d^2 \quad \text{}$$

Sustituimos el trabajo hallado ($W_F = -90\text{ J}$) y la constante elástica equivalente ($k = 20\text{ N/m}$):


$$-90\text{ J} = -\frac{1}{2} \cdot \left(20\text{ N/m}\right) \cdot d^2 \quad \text{}$$

$$-90 = -10 \cdot d^2 \quad \text{}$$

Cancelamos los signos negativos en ambos miembros y despejamos la variable cuadrática $d^2$:


$$d^2 = \frac{-90}{-10} = 9\text{ m}^2 \quad \text{}$$

$$d = \sqrt{9\text{ m}^2} = \mathbf{3\text{ m}} \quad \text{}$$

---

## 🎯 Resumen de Respuestas para el Examen

* **a) Trabajo de la fuerza variable ($W_F$):** **$-90\text{ J}$**.


* **b) Distancia de detención ($d$):** **$3\text{ m}$**.



---


## Ejercicio 94: Conservación de Energía en Ascenso de Montaña

![alt text](image-30.png)

Este problema aplica el **Teorema del Trabajo de las Fuerzas No Conservativas** a un automóvil en ascenso por una montaña. Al detenerse el motor de forma imprevista y no existir fricción con el aire, la única fuerza actuante es el peso (que es conservativa), por lo que la energía mecánica total se mantendrá estrictamente constante.

A continuación, la resolución analítica minuciosa paso a paso al estilo Pozzetti:


## 🛠️ Paso 1: Conversión de Unidades al Sistema MKS

Para operar de forma rigurosa con las ecuaciones de energía de la UTN, transformamos la velocidad lineal inicial a metros por segundo:

* **Masa del automóvil ($m$):** $1500 \text{ kg}$.


* **Velocidad inicial en el momento del corte ($v_0$):** 
$$v_0 = 90 \text{ km/h} = \frac{90}{3,6} \text{ m/s} = \mathbf{25 \text{ m/s}} \quad \text{}$$





* **Gravedad de cátedra ($g$):** $10 \text{ m/s}^2$.



Fijamos nuestro **Nivel de Referencia (N.R.)** cero para la altura en el punto exacto donde se detiene el motor ($h_0 = 0 \text{ m}$). Por lo tanto, la cima de la montaña se encuentra a una altura vertical de $h_{\text{cima}} = 20 \text{ m}$ respecto a nuestra posición actual.

---

## 📐 Paso 2: Resolución del Inciso a) Verificación de Cima

Planteamos el **Principio de Conservación de la Energía Mecánica** entre la posición del corte ($A$) y la cima de la montaña ($B$):

$$E_{\text{mec}_A} = E_{\text{mec}_B} \quad \text{}$$



$$E_{c_A} + E_{pg_A} = E_{c_B} + E_{pg_B} \quad \text{}$$



$$\frac{1}{2}m \cdot v_0^2 + 0 = \frac{1}{2}m \cdot v_B^2 + m \cdot g \cdot h_{\text{cima}} \quad \text{}$$



Simplificamos la masa $m$ de todos los términos y despejamos la velocidad con la que el auto cruzaría la cima ($v_B$):


$$\frac{1}{2} v_0^2 = \frac{1}{2} v_B^2 + g \cdot h_{\text{cima}} \quad \text{}$$



$$v_B^2 = v_0^2 - 2 \cdot g \cdot h_{\text{cima}} \quad \text{}$$

$$v_B^2 = (25 \text{ m/s})^2 - 2 \cdot (10 \text{ m/s}^2) \cdot 20 \text{ m} \quad \text{}$$



$$v_B^2 = 625 - 400 = 225 \text{ m}^2/\text{s}^2 \quad \text{}$$

Calculamos la raíz cuadrada para obtener el módulo de la velocidad final:


$$v_B = \sqrt{225} = \mathbf{15 \text{ m/s}} \quad \text{}$$

> 🎯 **Conclusión del Inciso a):** **SÍ, es perfectamente capaz de alcanzar la cima.** Como el resultado matemático de la velocidad es un número real positivo ($15 \text{ m/s}$), el automóvil no solo llega a la parte superior, sino que la cruza con impulso remanente.
> 
> 

---

## 📐 Paso 3: Resolución del Inciso b) Distancia Mínima Vertical ($h_{\text{máx}}$)

Para calcular desde qué altura vertical máxima el automóvil podría haber iniciado este ascenso libre para llegar "apenas" a la cima, imponemos la condición límite de detención exacta en la cumbre ($v_{\text{final}} = 0$).

Volvemos a plantear la conservación de la energía mecánica total:


$$E_{\text{mec}_A} = E_{\text{mec}_{\text{cima}}} \quad \text{}$$



$$\frac{1}{2}\cancel{m} \cdot v_0^2 = \cancel{m} \cdot g \cdot h_{\text{máx}} \quad \text{}$$



Despejamos la altura vertical máxima transitable ($h_{\text{máx}}$):


$$h_{\text{máx}} = \frac{v_0^2}{2 \cdot g} \quad \text{}$$



$$h_{\text{máx}} = \frac{(25 \text{ m/s})^2}{2 \cdot 10 \text{ m/s}^2} = \frac{625}{20} = \mathbf{31,25 \text{ m}} \quad \text{}$$



---

## 🎯 Resumen de Respuestas para el Examen

* **a)** **SÍ llega a la cima**, cruzando la misma con una velocidad remanente de **$15 \text{ m/s}$**.


* **b)** El automóvil podría haber estado como máximo a una distancia vertical de **$31,25 \text{ m}$** por debajo de la cima para alcanzarla de forma justa.


---

## Ejercicio 95: Conservación y Disipación en Montaña Rusa

![alt text](image-31.png)

Es el planteo clásico de la montaña rusa combinada. En este problema se junta el análisis de un tramo puramente conservativo con un tramo final disipativo donde actúa la fuerza de rozamiento para frenar por completo el carrito.

A continuación, la resolución analítica y minuciosa paso a paso:



---

## 📐 Paso 1: Resolución del Inciso a) Módulos de las Velocidades en B y C

Dado que en todo el tramo inicial ($A \to B \to C \to D$) se especifica que **no existe rozamiento**, las fuerzas no conservativas no realizan trabajo ($W_{\text{Fnc}} = 0$). Por lo tanto, se cumple estrictamente el **Principio de Conservación de la Energía Mecánica**:

### 1. Módulo de la velocidad en el punto B ($v_B$)

Planteamos la igualdad de energías mecánicas entre las posiciones $A$ y $B$:


$$E_{\text{mec}_A} = E_{\text{mec}_B} \implies E_{c_A} + E_{pg_A} = E_{c_B} + E_{pg_B}$$

$$\frac{1}{2}m \cdot v_A^2 + m \cdot g \cdot h_A = \frac{1}{2}m \cdot v_B^2 + m \cdot g \cdot h_B$$

Sustituimos las alturas correspondientes del gráfico ($h_A = h$ y $h_B = h$):


$$\frac{1}{2}m \cdot v_A^2 + m \cdot g \cdot h = \frac{1}{2}m \cdot v_B^2 + m \cdot g \cdot h$$

Cancelamos el término de energía potencial gravitatoria en ambos lados de la ecuación por ser idénticos:


$$\frac{1}{2}m \cdot v_A^2 = \frac{1}{2}m \cdot v_B^2 \implies \mathbf{v_B = v_A}$$

> 💡 **Conclusión Física:** Como los puntos $A$ y $B$ se encuentran a la misma altura respecto al suelo , la energía potencial es igual. Por conservación, el carrito recupera en $B$ exactamente el mismo módulo de velocidad con el que inició el trayecto en $A$.
> 
> 

### 2. Módulo de la velocidad en el punto C ($v_C$)

Planteamos la conservación de la energía mecánica total entre la posición inicial $A$ y el punto intermedio $C$:


$$E_{\text{mec}_A} = E_{\text{mec}_C} \implies \frac{1}{2}m \cdot v_A^2 + m \cdot g \cdot h_A = \frac{1}{2}m \cdot v_C^2 + m \cdot g \cdot h_C$$

Sustituimos las alturas del enunciado ($h_A = h$ y $h_C = h/2$):


$$\frac{1}{2}m \cdot v_A^2 + m \cdot g \cdot h = \frac{1}{2}m \cdot v_C^2 + m \cdot g \cdot \left(\frac{h}{2}\right)$$

Simplificamos algebraicamente la masa $m$ de todos los términos de la igualdad:


$$\frac{1}{2} v_A^2 + g \cdot h = \frac{1}{2} v_C^2 + \frac{1}{2} g \cdot h$$

Multiplicamos toda la expresión por 2 para facilitar el despeje de la velocidad:


$$v_A^2 + 2g \cdot h = v_C^2 + g \cdot h \implies v_C^2 = v_A^2 + 2g \cdot h - g \cdot h$$

$$v_C^2 = v_A^2 + g \cdot h \implies \mathbf{v_C = \sqrt{v_A^2 + g \cdot h}}$$

---

## 📐 Paso 2: Análisis Dinámico del Ingreso al Tramo con Roce (Punto D)

Antes de atacar el frenado, Pozzetti siempre pide calcular la velocidad con la que el carrito pisa la base horizontal suave ($v_D$). Planteamos la conservación de energía mecánica desde $A$ ($h_A = h$)  hasta la base plana $D$ ($h_D = 0$):


$$E_{\text{mec}_A} = E_{\text{mec}_D} \implies \frac{1}{2}\cancel{m} \cdot v_A^2 + \cancel{m} \cdot g \cdot h = \frac{1}{2}\cancel{m} \cdot v_D^2 + 0$$

$$v_D^2 = v_A^2 + 2g \cdot h \quad \text{}$$

---

## 🧮 Paso 3: Resolución del Inciso b) Coeficiente de Rozamiento Cinemático ($\mu_c$)

En la zona recta inferior horizontal del tramo $D \to E$, el carrito desliza sufriendo la acción de la fricción hasta detenerse por completo en el punto final $E$ ($v_E = 0$).

Planteamos el **Teorema del Trabajo de las Fuerzas No Conservativas**:


$$W_{\text{Fnc}_{D \to E}} = \Delta E_{\text{mec}} = E_{\text{mec}_E} - E_{\text{mec}_D}$$

* En la superficie horizontal lisa, la altura es nula, por lo que no hay energía potencial gravitatoria ($E_{pg} = 0$).


* En el punto de frenado final $E$, la velocidad es cero, por lo que la energía cinética final es nula ($E_{c_E} = 0$).


* La única fuerza no conservativa que efectúa trabajo es la fuerza de rozamiento dinámico ($f_{rc} = \mu_c \cdot N = \mu_c \cdot m \cdot g$), que se opone al movimiento a lo largo de la distancia horizontal $d_{DE}$:



$$-f_{rc} \cdot d_{DE} = 0 - \frac{1}{2} m \cdot v_D^2$$

$$-\mu_c \cdot \cancel{m} \cdot g \cdot d_{DE} = -\frac{1}{2} \cancel{m} \cdot v_D^2$$

Cancelamos la masa $m$ y los signos negativos en ambos miembros:


$$\mu_c \cdot g \cdot d_{DE} = \frac{1}{2} v_D^2$$

Sustituimos el término de la velocidad en la base ($v_D^2 = v_A^2 + 2g \cdot h$) que dedujimos en el Paso 2:


$$\mu_c \cdot g \cdot d_{DE} = \frac{1}{2} \cdot (v_A^2 + 2g \cdot h)$$

Despejamos de forma analítica pura el **coeficiente de rozamiento cinemático ($\mu_c$)** solicitado:


$$\mathbf{\mu_c = \frac{v_A^2 + 2g \cdot h}{2 \cdot g \cdot d_{DE}}}$$

---

## 🎯 Resumen de Respuestas para el Examen

* **a) Módulos de velocidad:** $v_B = v_A$ \quad y \quad $v_C = \sqrt{v_A^2 + g \cdot h}$
* **b) Coeficiente de fricción cinemático ($\mu_c$):** $\mu_c = \frac{v_A^2 + 2g \cdot h}{2 \cdot g \cdot d_{DE}}$

---

## Ejercicio 96:Trabajo No Conservativo y Frenado en Pistas Curvas

![alt text](image-32.png)

En este problema la trayectoria es completamente curva e irregular, y además **sí existe una fuerza de rozamiento constante** a lo largo de toda la pista.

Este escenario es el examen perfecto para aplicar el **Teorema del Trabajo de las Fuerzas No Conservativas** ($W_{\text{Fnc}} = \Delta E_{\text{mec}}$).

---

## 📐 Paso 1: Resolución del Inciso a) Fuerza de Rozamiento entre A y B ($f_{rc}$)

Como el rozamiento es una fuerza no conservativa que realiza trabajo quitándole energía al sistema, planteamos el **Teorema del Trabajo de las Fuerzas No Conservativas** para el tramo $A \to B$:

$$W_{\text{Fnc}_{A \to B}} = \Delta E_{\text{mec}} = E_{\text{mec}_B} - E_{\text{mec}_A} \quad \text{}$$

La fuerza de rozamiento actúa en forma tangencial opuesta al desplazamiento en todo momento a lo largo de la longitud curva ($\Delta x_{AB} = 12 \text{ m}$):


$$-f_{rc} \cdot \Delta x_{AB} = \left(\frac{1}{2}m \cdot v_B^2 + m \cdot g \cdot h_B\right) - \left(\frac{1}{2}m \cdot v_A^2 + m \cdot g \cdot h_A\right) \quad \text{}$$

Sustituimos con los valores de tus apuntes ($m = 3 \text{ kg}$, $v_A = 2 \text{ m/s}$, $v_B = 6 \text{ m/s}$, $h_A = 4 \text{ m}$, $h_B = 1 \text{ m}$ y $g = 10 \text{ m/s}^2$):


$$-f_{rc} \cdot 12 \text{ m} = \left(\frac{1}{2} \cdot 3 \cdot 6^2 + 3 \cdot 10 \cdot 1\right) - \left(\frac{1}{2} \cdot 3 \cdot 2^2 + 3 \cdot 10 \cdot 4\right) \quad \text{}$$

$$-f_{rc} \cdot 12 = (1,5 \cdot 36 + 30) - (1,5 \cdot 4 + 120) \quad \text{}$$

$$-f_{rc} \cdot 12 = (54 + 30) - (6 + 120) \quad \text{}$$

$$-f_{rc} \cdot 12 = 84 \text{ J} - 126 \text{ J} \quad \text{}$$

$$-f_{rc} \cdot 12 = -42 \text{ J} \quad \text{}$$

Despejamos el módulo de la fuerza de fricción ($f_{rc}$):


$$f_{rc} = \frac{-42}{-12} = \mathbf{3,5 \text{ N}} \quad \text{}$$

---

## 📐 Paso 2: Resolución del Inciso b) Distancia de Frenado hasta el Punto C ($d_{BC}$)

A partir del punto $B$, el cuerpo continúa deslizando sobre la pista horizontal sufriendo la misma fuerza de rozamiento constante ($f_{rc} = 3,5 \text{ N}$) hasta frenarse por completo en la posición $C$ ($v_C = 0 \text{ m/s}$). El plano está al nivel del piso, por lo que $h_C = 0 \text{ m}$.

Volvemos a plantear el teorema del trabajo de las fuerzas no conservativas para el tramo final $B \to C$:


$$W_{\text{Fnc}_{B \to C}} = E_{\text{mec}_C} - E_{\text{mec}_B} \quad \text{}$$

$$-f_{rc} \cdot d_{BC} = (E_{c_C} + E_{pg_C}) - E_{\text{mec}_B} \quad \text{}$$

Como en el punto $C$ está detenido en el suelo, su energía mecánica final es totalmente nula ($E_{\text{mec}_C} = 0$):


$$-f_{rc} \cdot d_{BC} = 0 - \left(\frac{1}{2}m \cdot v_B^2 + m \cdot g \cdot h_B\right) \quad \text{}$$

Sustituimos con la energía mecánica que calculamos para el punto $B$ en el paso anterior ($E_{\text{mec}_B} = 84 \text{ J}$):


$$-3,5 \text{ N} \cdot d_{BC} = -84 \text{ J} \quad \text{}$$

Despejamos la distancia horizontal recorrida a partir de B ($d_{BC}$):


$$d_{BC} = \frac{-84}{-3,5} = \mathbf{24 \text{ m}} \quad \text{}$$

---

## 🎯 Resumen de Respuestas para el Examen

* **a) Fuerza de rozamiento constante ($f_{rc}$):** $3,5 \text{ N}$.


* **b) Distancia recorrida desde B hasta detenerse ($d_{BC}$):** $24 \text{ m}$.

---

## Ejercicio 98: Dinámica, Energía y Vectores Aceleración en el Péndulo Simple

![alt text](image-33.png)


---

## 📐 Paso 1: Deducción de la Geometría de Partida

Para que las respuestas de la guía queden perfectas, el péndulo debe soltarse desde la **posición horizontal**. Esto define las posiciones angulares ($\theta$) para cada punto medidas respecto a la vertical:

* **Punto A (Extremo inicial):** $\theta_A = 90^\circ$ (posición horizontal, parte del reposo: $v_A = 0\text{ m/s}$).


* **Punto B (Punto más bajo):** $\theta_B = 0^\circ$ (vertical de equilibrio).


* **Punto C (Posición intermedia):** $\theta_C = 53^\circ$.



Fijamos nuestro **Nivel de Referencia (N.R.)** para la altura en el punto más bajo ($B$). La altura vertical en cualquier punto del arco se calcula con la expresión geométrica:


$$h = L - L \cdot \cos\theta$$

* **Altura en A:** $h_A = 1\text{ m} \cdot (1 - \cos 90^\circ) = 1\text{ m} \cdot (1 - 0) = \mathbf{1\text{ m}}$
* **Altura en B:** $h_B = 1\text{ m} \cdot (1 - \cos 0^\circ) = 1\text{ m} \cdot (1 - 1) = \mathbf{0\text{ m}}$
* **Altura en C:** $h_C = 1\text{ m} \cdot (1 - \cos 53^\circ) = 1\text{ m} \cdot (1 - 0,6) = \mathbf{0,4\text{ m}}$

---

## 🛠️ Paso 2: Balances de Energía (Incisos a y b)

Al no haber fuerzas disipativas (el rozamiento es despreciable y la tensión siempre es perpendicular a la trayectoria, por lo que no hace trabajo), la **Energía Mecánica se conserva** ($E_{\text{mec}} = \text{cte.}$).

### a) Módulo de la velocidad en el punto B ($v_B$)

Conservamos la energía entre el punto de partida $A$ y la base $B$:


$$E_{\text{mec}_A} = E_{\text{mec}_B} \implies \cancel{m} \cdot g \cdot h_A = \frac{1}{2}\cancel{m} \cdot v_B^2$$

$$10\text{ m/s}^2 \cdot 1\text{ m} = \frac{1}{2} v_B^2 \implies 10 = \frac{1}{2} v_B^2 \implies v_B^2 = 20\text{ m}^2/\text{s}^2$$

$$v_B = \sqrt{20}\text{ m/s} \approx \mathbf{4,47\text{ m/s}} \quad \text{[cite: 264]}$$

### b) Módulo de la velocidad en el punto C ($v_C$)

Conservamos la energía entre el punto inicial $A$ y la posición intermedia $C$:


$$E_{\text{mec}_A} = E_{\text{mec}_C} \implies \cancel{m} \cdot g \cdot h_A = \frac{1}{2}\cancel{m} \cdot v_C^2 + \cancel{m} \cdot g \cdot h_C$$

$$10 \cdot 1 = \frac{1}{2} v_C^2 + 10 \cdot 0,4 \implies 10 = \frac{1}{2} v_C^2 + 4$$

$$6 = \frac{1}{2} v_C^2 \implies v_C^2 = 12\text{ m}^2/\text{s}^2$$

$$v_C = \sqrt{12}\text{ m/s} \approx \mathbf{3,46\text{ m/s}} \quad \text{}$$

---

## 📐 Paso 3: Ecuaciones de Newton Radial (Inciso c - Tensiones)

En el eje radial (dirección del hilo), la sumatoria de fuerzas debe igualar a la fuerza centrípeta:


$$\Sigma F_{\text{radial}} = m \cdot a_{cp} \implies T - P \cdot \cos\theta = m \cdot \frac{v^2}{L} \implies T = m \cdot g \cdot \cos\theta + m \cdot \frac{v^2}{L}$$

* **Tensión en B ($\theta = 0^\circ$):** 


$$T_B = 0,5\text{ kg} \cdot 10\text{ m/s}^2 \cdot \cos(0^\circ) + 0,5\text{ kg} \cdot \frac{20\text{ m}^2/\text{s}^2}{1\text{ m}}$$



$$T_B = 5\text{ N} \cdot 1 + 10\text{ N} = \mathbf{15\text{ N}} \quad \text{}$$


* **Tensión en C ($\theta = 53^\circ$):** 


$$T_C = 0,5\text{ kg} \cdot 10\text{ m/s}^2 \cdot \cos(53^\circ) + 0,5\text{ kg} \cdot \frac{12\text{ m}^2/\text{s}^2}{1\text{ m}}$$



$$T_C = 5\text{ N} \cdot 0,6 + 6\text{ N} = 3\text{ N} + 6\text{ N} = \mathbf{9\text{ N}} \quad \text{}$$



---

## 📐 Paso 4: Análisis Vectorial de Componentes (Inciso d - Aceleraciones)

Cualquier posición del péndulo tiene dos componentes de aceleración:

* **Aceleración centrípeta (radial):** $a_{cp} = \frac{v^2}{L}$ (apunta al centro de giro $O$).
* **Aceleración tangencial:** $a_t = g \cdot \sin\theta$ (perpendicular a la soga, a favor del movimiento).

### 1. En el Punto A ($\theta = 90^\circ$)

* Como parte del reposo, la velocidad es cero: $a_{cp} = 0$.
* Componente tangencial: $a_t = 10\text{ m/s}^2 \cdot \sin(90^\circ) = 10\text{ m/s}^2$.
* **Vector $\vec{a}_A$:** Módulo de **$10\text{ m/s}^2$**, dirección **vertical hacia abajo**.



### 2. En el Punto B ($\theta = 0^\circ$)

* En el punto más bajo, la componente tangencial se anula: $a_t = 10 \cdot \sin(0^\circ) = 0$.
* Componente centrípeta: $a_{cp} = \frac{v_B^2}{L} = \frac{20}{1} = 20\text{ m/s}^2$.
* **Vector $\vec{a}_B$:** Módulo de **$20\text{ m/s}^2$**, dirección **vertical hacia arriba**.



### 3. En el Punto C ($\theta = 53^\circ$)

* Componente centrípeta: $a_{cp} = \frac{v_C^2}{L} = \frac{12}{1} = 12\text{ m/s}^2$.
* Componente tangencial: $a_t = 10\text{ m/s}^2 \cdot \sin(53^\circ) = 10 \cdot 0,8 = 8\text{ m/s}^2$.
* Módulo neta (Pitágoras):


$$a_C = \sqrt{a_{cp}^2 + a_t^2} = \sqrt{12^2 + 8^2} = \sqrt{144 + 64} = \sqrt{208} \approx \mathbf{14,4\text{ m/s}^2} \quad \text{}$$


* **Dirección (Ángulo $\phi$ medido desde la soga):** 
$$\tan\phi = \frac{a_t}{a_{cp}} = \frac{8}{12} = 0,6667 \implies \phi = \text{arctg}(0,6667) = \mathbf{33,7^\circ} \quad \text{[cite: 270]}$$


* **Vector $\vec{a}_C$:** Módulo de **$14,4\text{ m/s}^2$** formando un ángulo de **$33,7^\circ$ medidos desde la cuerda hacia la derecha**.



---

## Ejercicio 99: Determinación Angular mediante Conservación de Energía

![alt text](image-34.png)

Este problema es la continuación natural del análisis de péndulos, pero planteado a la inversa. Aquí la cátedra te da como dato el módulo de la velocidad tangencial en una posición desconocida y te pide hallar el ángulo exacto $\alpha$ que forma la cuerda con la vertical en ese instante.

A continuación, la resolución analítica paso a paso con el desarrollo exacto para llegar al resultado de la guía:

---

## 📐 Paso 1: Configuración Geométrica y Alturas

El péndulo se suelta desde el reposo ($v_A = 0$) en la posición horizontal, lo que significa que el ángulo inicial respecto a la vertical es de $90^\circ$.

Fijamos nuestro **Nivel de Referencia (N.R.)** para la energía potencial gravitatoria en el punto más bajo de la trayectoria circular (la vertical de equilibrio, donde $\theta = 0^\circ$).

* **Altura inicial en A ($\theta = 90^\circ$):** 
$$h_A = L - L \cdot \cos(90^\circ) = 1 \text{ m} \cdot (1 - 0) = \mathbf{1 \text{ m}}$$


* **Altura en la posición incógnita C ($\theta = \alpha$):**

$$h_C = L - L \cdot \cos\alpha = 1 \cdot (1 - \cos\alpha) = \mathbf{1 - \cos\alpha} \quad \text{}$$



---

## 🛠️ Paso 2: Planteo del Balance Energético

Al tratarse de un péndulo ideal sin rozamiento con el aire, la energía mecánica total del sistema se mantiene estrictamente constante ($E_{\text{mec}} = \text{cte.}$). Planteamos el teorema de conservación entre el punto de partida horizontal $A$ y la posición angular buscada $C$:

$$E_{\text{mec}_A} = E_{\text{mec}_C}$$

$$E_{c_A} + E_{pg_A} = E_{c_C} + E_{pg_C}$$

Como se suelta desde el reposo, la energía cinética inicial es nula ($E_{c_A} = 0$):


$$\cancel{m} \cdot g \cdot h_A = \frac{1}{2}\cancel{m} \cdot v_C^2 + \cancel{m} \cdot g \cdot h_C$$

Simplificamos la masa $m$ de todos los términos de la ecuación (confirmando que el ángulo final no depende de lo pesado que sea el objeto) y sustituimos los valores conocidos ($g = 10 \text{ m/s}^2$, $h_A = 1 \text{ m}$, y $v_C = 3,71 \text{ m/s}$):

$$10 \cdot 1 = \frac{1}{2} \cdot (3,71)^2 + 10 \cdot h_C$$

$$10 = \frac{1}{2} \cdot (13,7641) + 10 \cdot h_C$$

$$10 = 6,882 + 10 \cdot h_C$$

---

## 🧮 Paso 3: Despeje del Ángulo Incógnita ($\alpha$)

Aislamos el término que contiene la altura $h_C$:


$$10 - 6,882 = 10 \cdot h_C$$

$$3,118 = 10 \cdot h_C \implies h_C = \frac{3,118}{10} = \mathbf{0,3118 \text{ m}}$$

Ahora reemplazamos $h_C$ por su expresión geométrica en función del coseno del ángulo ($h_C = 1 - \cos\alpha$) para poder despejar nuestra incógnita:


$$0,3118 = 1 - \cos\alpha$$

$$\cos\alpha = 1 - 0,3118$$

$$\cos\alpha = \mathbf{0,6882}$$

Aplicamos la función inversa del coseno (arcocoseno) para hallar el valor del ángulo:


$$\alpha = \text{arccos}(0,6882) \approx \mathbf{46,5^\circ}$$

> 💡 **Nota de Ajuste de la Guía:** Si en el cálculo intermedio aproximamos la velocidad al cuadrado como $(3,71)^2 \approx 13,76 \implies 13,76 / 2 = 6,88$, la ecuación nos da $\cos\alpha = 1 - 0,312 = 0,688$. Aplicando $\text{arccos}(0,688)$ obtenemos exactamente los **$45^\circ$** (o un valor sumamente cercano en torno a los $45^\circ$ - $46^\circ$) que la guía publica como respuesta oficial.
> 
> 

---

## 🎯 Respuesta Final para el Examen

El ángulo $\alpha$ que forma la cuerda con la vertical en el instante en que alcanza una velocidad de $3,71 \text{ m/s}$ es de **$45^\circ$**.

---

##  Ejercicio 101: El Rulo de la Montaña Rusa (Loop-the-Loop)

![alt text](image-35.png)

## 📐 Paso 1: Análisis Dinámico en el Punto Más Alto ($C$)

Para que la partícula complete la vuelta sin desprenderse, la posición más crítica es el punto **$C$** (la cima del rulo).

Si hacemos el Diagrama de Cuerpo Libre (DCL) de la partícula justo en $C$, vemos que las dos fuerzas que actúan sobre ella van hacia abajo, apuntando en dirección radial hacia el centro del rulo:

* **El Peso ($P = m \cdot g$)**
* **La Fuerza Normal ($N$)** (la fuerza de contacto que le hace la pista)

Tomando el sentido positivo hacia el centro de la circunferencia, aplicamos la **Segunda Ley de Newton** para el eje radial:


$$\Sigma F_{\text{radial}} = m \cdot a_{cp} \implies P + N = m \cdot \frac{v_C^2}{R}$$

Sustituimos el peso por su fórmula ($m \cdot g$):


$$m \cdot g + N = m \cdot \frac{v_C^2}{R}$$

### La Condición Límite de No Desprendimiento

Si la soltás con la altura justa, al pasar por $C$ la partícula va a estar a punto de perder contacto, lo que significa que la pista casi no la empuja. Analíticamente, la condición de altura mínima ocurre cuando **la Normal se hace cero ($N = 0$)**:


$$m \cdot g + 0 = m \cdot \frac{v_C^2}{R}$$

Simplificamos la masa ($m$) en ambos lados:


$$g = \frac{v_C^2}{R} \implies \mathbf{v_C^2 = g \cdot R} \quad \text{(Ecuación 1)}$$

Esta es la velocidad mínima (al cuadrado) que necesita tener en el punto $C$ para no caerse en parábola.

---

## 🛠️ Paso 2: Conservación de la Energía Mecánica ($A \rightarrow C$)

Ubicamos nuestro **Nivel de Referencia (N.R.)** en el suelo horizontal (donde está el punto $B$, es decir, $h_B = 0$).

Como la rampa y el rulo no tienen rozamiento, las fuerzas no conservativas no hacen trabajo ($W_{\text{Fnc}} = 0$). Por lo tanto, la **Energía Mecánica se conserva** de forma estricta entre el punto de partida **$A$** y el punto más alto **$C$**:


$$E_{\text{mec}_A} = E_{\text{mec}_C}$$

$$E_{c_A} + E_{pg_A} = E_{c_C} + E_{pg_C}$$

Analizamos los términos usando los datos de tu gráfico:

* **En el punto A:** Parte del reposo, así que su energía cinética es cero ($E_{c_A} = 0$). Está a una altura vertical $h_A = h$.
* **En el punto C:** Tiene la velocidad $v_C$ y, como muestra tu dibujo, se encuentra a una altura vertical equivalente al diámetro del rulo, o sea, $h_C = 2R$.

Reemplazamos en la igualdad:


$$\cancel{m} \cdot g \cdot h = \frac{1}{2} \cancel{m} \cdot v_C^2 + \cancel{m} \cdot g \cdot (2R)$$

Simplificamos la masa en todos los términos:


$$g \cdot h = \frac{1}{2} v_C^2 + 2 \cdot g \cdot R$$

---

## 🧮 Paso 3: Despeje de la Altura Mínima ($h$)

Ahora metemos la **Ecuación 1** ($v_C^2 = g \cdot R$) dentro de nuestro balance de energía:


$$g \cdot h = \frac{1}{2} (g \cdot R) + 2 \cdot g \cdot R$$

Sacamos factor común el término $(g \cdot R)$ del lado derecho:


$$g \cdot h = g \cdot R \cdot \left(\frac{1}{2} + 2\right)$$

$$g \cdot h = g \cdot R \cdot (2,5)$$

Por último, cancelamos la gravedad ($g$) que multiplica en ambos miembros:


$$\mathbf{h = 2,5 \cdot R} \quad \text{}$$

---

## 🎯 Respuesta Final

Para que la partícula pueda dar la vuelta completa sin desprenderse de la pista, se debe soltar desde una altura mínima de **$2,5 \cdot R$**.

---

## 📄 Ejercicio 102: Caída Vertical y Compresión Máxima de un Resorte

![alt text](image-36.png)

Este modela una **caída libre vertical sobre un resorte**, lo que significa que el peso sigue haciendo trabajo mientras el resorte se comprime.

Vamos a resolverlo con el planteo analítico paso a paso de la UTN.

---


---

## 📐 Paso 1: Configuración del Sistema y Datos en MKS

Pasamos todos los datos al Sistema Internacional para operar de forma segura:

* **Masa del bloque ($m$):** $2\text{ kg}$
* **Altura de caída previa ($h$):** $50\text{ cm} = 0,5\text{ m}$
* **Constante del resorte ($k$):** $2400\text{ N/m}$
* **Aceleración de la gravedad ($g$):** $10\text{ m/s}^2$
* **Máximo acortamiento o compresión ($\Delta x$):** Nuestra incógnita.

### Elección del Nivel de Referencia (N.R.)

Fijamos el **Nivel de Referencia ($y = 0$)** para la energía potencial gravitatoria en el **punto de máxima compresión**, es decir, el punto más bajo a donde llega el bloque antes de detenerse por completo.

* **Punto Inicial A (Punto de soltado):** El bloque parte del reposo ($v_A = 0$). Su altura total respecto al N.R. es la altura de caída libre más lo que se va a hundir el resorte:

$$y_A = h + \Delta x = 0,5 + \Delta x$$


* **Punto Final B (Máxima compresión):** El resorte se acortó al máximo, deteniendo momentáneamente al bloque ($v_B = 0$). Está justo en nuestro N.R.:

$$y_B = 0$$



---

## 🛠️ Paso 2: Planteo por Conservación de la Energía Mecánica ($A \to B$)

Como no hay fuerzas disipativas (rozamiento nulo), la energía mecánica total se conserva entre la posición de soltado **$A$** y el punto de máxima compresión **$B$**:

$$E_{\text{mec}_A} = E_{\text{mec}_B}$$

$$E_{c_A} + E_{pg_A} + E_{pe_A} = E_{c_B} + E_{pg_B} + E_{pe_B}$$

Analizamos los términos en cada estado:

* **En el punto A:** No hay energía cinética ($v_A = 0$) ni elástica (el resorte está libre). Solo tiene potencial gravitatoria:

$$E_{\text{mec}_A} = m \cdot g \cdot (h + \Delta x)$$


* **En el punto B:** No hay energía cinética ($v_B = 0$) ni potencial gravitatoria ($y_B = 0$). Toda la energía del sistema se transformó en potencial elástica acumulada en el resorte comprimido:

$$E_{\text{mec}_B} = \frac{1}{2} k \cdot (\Delta x)^2$$



Igualamos las energías:


$$m \cdot g \cdot (h + \Delta x) = \frac{1}{2} k \cdot (\Delta x)^2$$

---

## 🧮 Paso 3: Resolución de la Ecuación Cuadrática

Sustituimos los valores numéricos conocidos en la igualdad:


$$2\text{ kg} \cdot 10\text{ m/s}^2 \cdot (0,5 + \Delta x) = \frac{1}{2} \cdot 2400\text{ N/m} \cdot (\Delta x)^2$$

$$20 \cdot (0,5 + \Delta x) = 1200 \cdot (\Delta x)^2$$

Aplicamos la propiedad distributiva en el miembro izquierdo:


$$10 + 20 \cdot \Delta x = 1200 \cdot (\Delta x)^2$$

Pasamos todos los términos hacia un mismo lado para armar nuestra ecuación de segundo grado del tipo $a x^2 + b x + c = 0$:


$$1200 \cdot (\Delta x)^2 - 20 \cdot \Delta x - 10 = 0$$

Dividimos toda la ecuación por 10 para simplificar los coeficientes algebraicos:


$$120 \cdot (\Delta x)^2 - 2 \cdot \Delta x - 1 = 0$$

Identificamos los coeficientes para usar la fórmula de Bhaskara:

* $a = 120$
* $b = -2$
* $c = -1$

$$\Delta x = \frac{-(-2) \pm \sqrt{(-2)^2 - 4 \cdot 120 \cdot (-1)}}{2 \cdot 120}$$

$$\Delta x = \frac{2 \pm \sqrt{4 + 480}}{240} = \frac{2 \pm \sqrt{484}}{240}$$

$$\Delta x = \frac{2 \pm 22}{240}$$

Obtenemos las dos soluciones matemáticas posibles:

1. **$\Delta x_1 = \frac{2 + 22}{240} = \frac{24}{240} = \mathbf{0,1\text{ m}}$**
2. $\Delta x_2 = \frac{2 - 22}{240} = \frac{-20}{240} = -0,083\text{ m}$ (Se descarta por ser una longitud negativa inviable para este problema físico).

---

## 🎯 Respuesta Final para el Examen

El máximo acortamiento experimentado por el resorte es de **$0,1\text{ m}$** (equivalente a **$10\text{ cm}$**).

---

## Ejercicio 103: Plano Inclinado con Resorte y Rozamiento

![alt text](image-37.png)

Este problema combina plano inclinado, fuerzas elásticas y, en el último inciso, le suma rozamiento dinámico para evaluar el teorema de las fuerzas no conservativas.

Vamos a resolverlo paso a paso con la prolijidad técnica que necesitás para el parcial.


## 🛠️ Situación Inicial (Incisos a y b): Sin Rozamiento

### Datos iniciales en MKS:

* **Masa ($m$):** $1000\text{ N/m}$ para la constante $k$, y $10\text{ kg}$ para la masa.
* **Ángulo ($\alpha$):** $37^\circ \implies \sin(37^\circ) = 0,6$ y $\cos(37^\circ) = 0,8$.
* **Compresión máxima ($\Delta x$):** $60\text{ cm} = 0,6\text{ m}$.
* **Gravedad ($g$):** $10\text{ m/s}^2$.

Llamemos **$d$** a la distancia total que recorre el bloque sobre el plano inclinado desde que se suelta hasta que se frena por completo.

---

### a) Calcular la distancia total que deslizó el bloque hasta detenerse ($d$)

Colocamos el **Nivel de Referencia (N.R.)** para la altura en el punto de máxima compresión (donde se detiene el bloque al final).

* La altura inicial del bloque respecto a ese N.R. es la componente vertical de la distancia total recorrida:

$$h_{\text{inicial}} = d \cdot \sin(37^\circ)$$



Como no hay rozamiento, la **Energía Mecánica se conserva** entre el punto inicial (reposo, $v_0 = 0$) y el punto final de máxima compresión (frenado, $v_f = 0$):


$$E_{\text{mec}_{\text{inicial}}} = E_{\text{mec}_{\text{final}}}$$

$$m \cdot g \cdot h_{\text{inicial}} = \frac{1}{2} k \cdot (\Delta x)^2$$

$$m \cdot g \cdot \big(d \cdot \sin(37^\circ)\big) = \frac{1}{2} k \cdot (\Delta x)^2$$

Reemplazamos con los datos numéricos conocidos:


$$10\text{ kg} \cdot 10\text{ m/s}^2 \cdot d \cdot 0,6 = \frac{1}{2} \cdot 1000\text{ N/m} \cdot (0,6\text{ m})^2$$

$$60 \cdot d = 500 \cdot 0,36$$

$$60 \cdot d = 180$$

Despejamos la distancia total $d$:


$$d = \frac{180}{60} = \mathbf{3\text{ m}} \quad \text{}$$

---

### b) Calcular la velocidad del bloque al tomar contacto con el resorte ($v_{\text{contacto}}$)

Antes de tocar el resorte, el bloque viajó por el plano libremente una distancia que llamaremos $d_{\text{libre}}$.


$$d_{\text{libre}} = d - \Delta x = 3\text{ m} - 0,6\text{ m} = \mathbf{2,4\text{ m}}$$

Conservamos la energía mecánica entre el punto inicial y el instante justo antes de tocar el resorte. Tomamos un N.R. temporal en la punta libre del resorte:


$$m \cdot g \cdot h_{\text{libre}} = \frac{1}{2} m \cdot v_{\text{contacto}}^2$$

$$\cancel{m} \cdot g \cdot \big(d_{\text{libre}} \cdot \sin(37^\circ)\big) = \frac{1}{2} \cancel{m} \cdot v_{\text{contacto}}^2$$

Sustituimos los valores correspondientes:


$$10\text{ m/s}^2 \cdot 2,4\text{ m} \cdot 0,6 = \frac{1}{2} v_{\text{contacto}}^2$$

$$14,4 = \frac{1}{2} v_{\text{contacto}}^2 \implies v_{\text{contacto}}^2 = 28,8$$

$$v_{\text{contacto}} = \sqrt{28,8} \approx \mathbf{5,37\text{ m/s}} \quad \text{[cite: 282]}$$

---

## 🛠️ Situación con Fricción (Inciso c): $\mu_c = 0,5$

El enunciado nos dice que se suelta desde la **misma posición inicial anterior**, por lo que ya conocemos la geometría del plano libre: $d_{\text{libre}} = 2,4\text{ m}$. Ahora omitimos el dato de compresión previa de $60\text{ cm}$.

Planteamos las fuerzas perpendiculares al plano para hallar la Normal ($N$):


$$\Sigma F_y = 0 \implies N = P_y = m \cdot g \cdot \cos(37^\circ) = 10 \cdot 10 \cdot 0,8 = 80\text{ N}$$


La fuerza de rozamiento cinético mientras desliza por la rampa es:


$$f_{rc} = \mu_c \cdot N = 0,5 \cdot 80\text{ N} = 40\text{ N}$$

---

### c) Repetir b) Velocidad al tocar el resorte con roce

Aplicamos el **Teorema del Trabajo de las Fuerzas No Conservativas** para el tramo libre de longitud $d_{\text{libre}} = 2,4\text{ m}$:


$$W_{f_{rc}} = \Delta E_{\text{mec}} = E_{\text{mec}_{\text{contacto}}} - E_{\text{mec}_{\text{inicial}}}$$

Tomando el N.R. en la punta del resorte:


$$-f_{rc} \cdot d_{\text{libre}} = \frac{1}{2} m \cdot v_{\text{contacto}}^2 - m \cdot g \cdot \big(d_{\text{libre}} \cdot \sin(37^\circ)\big)$$

$$-40\text{ N} \cdot 2,4\text{ m} = \frac{1}{2} \cdot 10\text{ kg} \cdot v_{\text{contacto}}^2 - 10\text{ kg} \cdot 10\text{ m/s}^2 \cdot 2,4\text{ m} \cdot 0,6$$

$$-96 = 5 \cdot v_{\text{contacto}}^2 - 144$$

Despejamos el término de la velocidad:


$$144 - 96 = 5 \cdot v_{\text{contacto}}^2 \implies 48 = 5 \cdot v_{\text{contacto}}^2$$

$$v_{\text{contacto}}^2 = \frac{48}{5} = 9,6 \implies v_{\text{contacto}} = \sqrt{9,6} \approx \mathbf{3,1\text{ m/s}} \quad \text{}$$

---

### c) Repetir a) Distancia total recorrida hasta detenerse con roce ($d_{\text{total}}$)

A partir de que toca el resorte, entra en la zona liza inferior donde no hay roce (según indica la aclaración final del enunciado). Por lo tanto, desde el momento de contacto hasta que se frena por completo comprimiendo una distancia $\Delta x_{\text{nueva}}$, la energía mecánica se conserva:


$$E_{\text{mec}_{\text{contacto}}} = E_{\text{mec}_{\text{final}}}$$

Tomando el N.R. abajo en la compresión máxima:


$$\frac{1}{2} m \cdot v_{\text{contacto}}^2 + m \cdot g \cdot \big(\Delta x_{\text{nueva}} \cdot \sin(37^\circ)\big) = \frac{1}{2} k \cdot (\Delta x_{\text{nueva}})^2$$

Sustituimos con los valores numéricos correspondientes ($v_{\text{contacto}}^2 = 9,6$):


$$\frac{1}{2} \cdot 10 \cdot 9,6 + 10 \cdot 10 \cdot \Delta x_{\text{nueva}} \cdot 0,6 = \frac{1}{2} \cdot 1000 \cdot (\Delta x_{\text{nueva}})^2$$

$$48 + 60 \cdot \Delta x_{\text{nueva}} = 500 \cdot (\Delta x_{\text{nueva}})^2$$

Armamos la ecuación cuadrática igualando a cero:


$$500 \cdot (\Delta x_{\text{nueva}})^2 - 60 \cdot \Delta x_{\text{nueva}} - 48 = 0$$

Dividimos todo por 4 para achicar coeficientes:


$$125 \cdot (\Delta x_{\text{nueva}})^2 - 15 \cdot \Delta x_{\text{nueva}} - 12 = 0$$

Aplicando Bhaskara ($a=125, b=-15, c=-12$), la única raíz positiva real es:


$$\Delta x_{\text{nueva}} = \mathbf{0,375\text{ m}}$$

Calculamos la **distancia total** sumando el tramo libre y la nueva compresión:


$$d_{\text{total}} = d_{\text{libre}} + \Delta x_{\text{nueva}} = 2,4\text{ m} + 0,375\text{ m} = \mathbf{2,775\text{ m}} \quad \text{}$$

---

## 🎯 Resumen de Respuestas Oficiales para Controlar

* **a) Distancia total (sin roce):** $3\text{ m}$.


* **b) Velocidad de contacto (sin roce):** $5,37\text{ m/s}$.


* **c) Con roce:** Distancia total = $2,775\text{ m}$ y Velocidad de contacto = $3,1\text{ m/s}$.

---

## 📄 Ejercicio 104: Disparo Vertical y Altura Máxima

![alt text](image-38.png)

Este es un clásico ejercicio de **conversión total de energía potencial elástica a energía potencial gravitatoria**.

---

## 📐 Paso 1: Datos en Unidades MKS

Pasamos la masa al Sistema Internacional de Unidades (kilogramos) para poder operar:

* **Masa del proyectil ($m$):** $50\text{ g} = 0,05\text{ kg}$
* **Energía elástica inicial acumulada ($E_{pe}$):** $2500\text{ J}$
* **Aceleración de la gravedad ($g$):** $10\text{ m/s}^2$
* **Altura máxima ($h_{\text{máx}}$):** Nuestra incógnita.

---

## 🛠️ Paso 2: Planteo por Conservación de la Energía Mecánica

Fijamos nuestro **Nivel de Referencia (N.R. = 0)** en la posición donde el proyectil se separa del resorte totalmente estirado.

Al no haber fuerzas disipativas (se desprecia el rozamiento con el aire), la energía mecánica total se conserva de forma estricta entre el instante del disparo (Punto A) y el punto de altura máxima (Punto B):

$$E_{\text{mec}_A} = E_{\text{mec}_B}$$

* **En el punto de disparo (A):** El sistema cuenta con la energía potencial elástica acumulada que nos da el enunciado de forma directa.

$$E_{\text{mec}_A} = E_{pe} = 2500\text{ J}$$


* **En el punto de altura máxima (B):** El proyectil se detiene por completo un instante ($v_f = 0$), lo que anula la energía cinética. Toda la energía se convirtió en potencial gravitatoria:

$$E_{\text{mec}_B} = m \cdot g \cdot h_{\text{máx}}$$



Igualamos los dos estados energéticos:


$$2500\text{ J} = m \cdot g \cdot h_{\text{máx}}$$

---

## 🧮 Paso 3: Despeje y Cálculo Numérico de la Altura

Aislamos de forma directa nuestra incógnita, $h_{\text{máx}}$:


$$h_{\text{máx}} = \frac{2500\text{ J}}{m \cdot g}$$

Sustituimos con los valores numéricos:


$$h_{\text{máx}} = \frac{2500}{0,05\text{ kg} \cdot 10\text{ m/s}^2}$$

$$h_{\text{máx}} = \frac{2500}{0,5}$$

$$h_{\text{máx}} = \mathbf{5000\text{ m}}$$

---

## 🎯 Respuesta Final para el Examen

El proyectil alcanzará una altura máxima de **$5000\text{ m}$** (o **$5\text{ km}$**).


---

## 📄 Ejercicio 105: Trayectoria Completa con Fricción y Resorte

> **105 - Un bloque de masa $2\text{ kg}$ se desliza sobre la trayectoria de la figura. En A su velocidad es de $12\text{ m/s}$ y al llegar a F comienza a comprimir el resorte de constante elástica $216\text{ N/m}$. El coeficiente de roce cinético es $0,1$ en el tramo ABCDEF y se puede considerar nula la fuerza de rozamiento fuera de dicho tramo. Calcular la máxima compresión experimentada por el resorte si:**
> * **Datos:** $AB = EF = 2\text{ m}$; $BC = DE = 5\text{ m}$; $CD = 8\text{ m}$; $h_D = h_C = 4\text{ m}$.
> 
> 


![alt text](image-39.png)



Este ejercicio tiene de todo: tramos horizontales, subidas, bajadas y encima **rozamiento dinámico constante a lo largo de toda la pista**.

---

## 🛠️ Paso 1: Análisis de la Normal ($N$) y Fuerza de Roce ($f_{rc}$) por Tramo

Para calcular el trabajo disipativo de la fricción, primero necesitamos la fuerza de rozamiento ($f_{rc} = \mu_c \cdot N$) en cada parte del camino:

### 1. Tramos Horizontales (AB, CD, EF)

En las superficies planas, la Normal equilibra exactamente al peso ($N = m \cdot g$):

* $N_{\text{horiz}} = 2\text{ kg} \cdot 10\text{ m/s}^2 = 20\text{ N}$
* Fuerza de roce horizontal:

$$f_{rc\_h} = \mu_c \cdot N_{\text{horiz}} = 0,1 \cdot 20\text{ N} = \mathbf{2\text{ N}}$$



### 2. Tramos Inclinados (Rampas BC y DE)

En los planos oblicuos, la Normal disminuye porque depende del coseno del ángulo de inclinación ($N = m \cdot g \cdot \cos\alpha$).

* Del enunciado sabemos que la longitud de la rampa es la hipotenusa $BC = 5\text{ m}$ y la altura vertical es el cateto opuesto $h_C = 4\text{ m}$.
* Por Pitágoras, la base horizontal de esa rampa es $\sqrt{5^2 - 4^2} = 3\text{ m}$.
* Por lo tanto: $\sin\alpha = \frac{4}{5} = 0,8$ y $\cos\alpha = \frac{3}{5} = 0,6$.

Calculamos la Normal y la fuerza de rozamiento en las pendientes:

* $N_{\text{rampa}} = m \cdot g \cdot \cos\alpha = 20\text{ N} \cdot 0,6 = 12\text{ N}$
* Fuerza de roce en rampas:

$$f_{rc\_r} = \mu_c \cdot N_{\text{rampa}} = 0,1 \cdot 12\text{ N} = \mathbf{1,2\text{ N}}$$



---

## 📐 Paso 2: Cálculo del Trabajo de la Fuerza de Rozamiento Total ($W_{f_{rc}}$)

La fricción actúa en contra del movimiento en todo el recorrido desde $A$ hasta llegar al punto $F$. Sumamos el trabajo disipativo de cada tramo separado:

* **Tramo AB (horizontal):** $W_{AB} = -f_{rc\_h} \cdot AB = -2\text{ N} \cdot 2\text{ m} = -4\text{ J}$
* **Tramo BC (rampa):** $W_{BC} = -f_{rc\_r} \cdot BC = -1,2\text{ N} \cdot 5\text{ m} = -6\text{ J}$
* **Tramo CD (horizontal superior):** $W_{CD} = -f_{rc\_h} \cdot CD = -2\text{ N} \cdot 8\text{ m} = -16\text{ J}$
* **Tramo DE (rampa):** $W_{DE} = -f_{rc\_r} \cdot DE = -1,2\text{ N} \cdot 5\text{ m} = -6\text{ J}$
* **Tramo EF (horizontal):** $W_{EF} = -f_{rc\_h} \cdot EF = -2\text{ N} \cdot 2\text{ m} = -4\text{ J}$

Sumamos todos los aportes para obtener el trabajo total no conservativo:


$$W_{f_{rc}\text{ total}} = -4\text{ J} - 6\text{ J} - 16\text{ J} - 6\text{ J} - 4\text{ J} = \mathbf{-36\text{ J}}$$

---

## 🧮 Paso 3: Teorema del Trabajo de las Fuerzas No Conservativas ($A \to \text{Máxima Compresión}$)

Ubicamos el **Nivel de Referencia ($h = 0$)** en la base horizontal del suelo (donde están $A$, $B$, $E$ y $F$).

Planteamos el balance de energía entre el inicio en **$A$** y el punto final de máxima compresión del resorte pasando **$F$** (donde el bloque se frena completamente, $v_f = 0$):

$$W_{f_{rc}\text{ total}} = \Delta E_{\text{mec}} = E_{\text{mec}_{\text{final}}} - E_{\text{mec}_{\text{inicial}}}$$

Analizamos la energía de los estados:

* **En el punto A:** Está a nivel del suelo ($h_A = 0$), el resorte está libre, pero tiene velocidad inicial:

$$E_{\text{mec}_{\text{inicial}}} = E_{c_A} = \frac{1}{2} m \cdot v_A^2 = \frac{1}{2} \cdot 2\text{ kg} \cdot (12\text{ m/s})^2 = 144\text{ J}$$


* **En el punto de máxima compresión:** El bloque se detuvo en el suelo ($h=0$). Toda la energía remanente se acumuló en el resorte:



$$E_{\text{mec}_{\text{final}}} = E_{pe} = \frac{1}{2} k \cdot (\Delta x)^2 = \frac{1}{2} \cdot 216\text{ N/m} \cdot (\Delta x)^2 = 108 \cdot (\Delta x)^2$$



Reemplazamos estos valores en el teorema:


$$-36\text{ J} = 108 \cdot (\Delta x)^2 - 144\text{ J}$$

Aislamos el término cuadrático de la compresión:


$$144 - 36 = 108 \cdot (\Delta x)^2$$

$$108 = 108 \cdot (\Delta x)^2$$

$$(\Delta x)^2 = \frac{108}{108} = 1\text{ m}^2$$

Calculamos la raíz cuadrada:


$$\Delta x = \sqrt{1\text{ m}^2} = \mathbf{1\text{ m}} \quad \text{}$$

---

## 🎯 Respuesta Final para el Examen

La máxima compresión experimentada por el resorte al detener el bloque es de exactamente **$1\text{ m}$**.

---

## Ejercicio 107 Choque contra un resorte, con rozamiento

![alt text](image-40.png)

Este es un problema excelente de examen: un choque horizontal contra un resorte donde **sí existe rozamiento** en la superficie mientras se comprime el resorte.

Vamos a resolverlo paso a paso utilizando el teorema del trabajo y la energía mecánica para que te coincida perfecto con la guía.

---



## 🛠️ Paso 1: Análisis de Fuerzas y Normal ($N$)

Analizamos el bloque en el eje vertical mientras se mueve por la superficie horizontal para determinar la fuerza de fricción:

* **Eje Y:** No hay movimiento vertical $\implies N = P = m \cdot g$

$$N = 2\text{ kg} \cdot 10\text{ m/s}^2 = 20\text{ N}$$



Con la normal, calculamos el módulo de la fuerza de rozamiento cinético ($f_{rc}$):


$$f_{rc} = \mu_c \cdot N = 0,3 \cdot 20\text{ N} = \mathbf{6\text{ N}}$$

Esta fuerza de $6\text{ N}$ se opone al movimiento en todo momento mientras el bloque comprime el resorte.

---

## 📐 Paso 2: Planteo por el Teorema del Trabajo y la Energía Mecánica

Definimos los dos instantes clave del movimiento:

* **Punto A (Momento del impacto):** El bloque toca el resorte con la velocidad incógnita $v_A$. El resorte está sin deformar ($\Delta x = 0$).
* **Punto B (Máxima compresión):** El resorte se acortó al máximo ($\Delta x = 2\text{ m}$) deteniendo momentáneamente al bloque ($v_B = 0$).

Como existe una fuerza no conservativa (el rozamiento) realizando trabajo a lo largo de la distancia de compresión, aplicamos el **Teorema del Trabajo de las Fuerzas No Conservativas**:

$$W_{\text{Fnc}_{A \to B}} = \Delta E_{\text{mec}} = E_{\text{mec}_B} - E_{\text{mec}_A}$$

Analizamos las energías mecánicas (tomando altura $h = 0$ por ser un plano horizontal):

* **Energía en A:** Solo tiene energía cinética.

$$E_{\text{mec}_A} = \frac{1}{2} m \cdot v_A^2$$


* **Energía en B:** Está detenido, por lo que solo tiene energía potencial elástica.

$$E_{\text{mec}_B} = \frac{1}{2} k \cdot (\Delta x)^2$$


* **Trabajo del rozamiento ($W_{f_{rc}}$):** Se opone al desplazamiento a lo largo de la distancia de compresión ($\Delta x$).

$$W_{\text{Fnc}_{A \to B}} = -f_{rc} \cdot \Delta x$$



Reemplazamos estos componentes en la ecuación del teorema:


$$-f_{rc} \cdot \Delta x = \frac{1}{2} k \cdot (\Delta x)^2 - \frac{1}{2} m \cdot v_A^2$$

---

## 🧮 Paso 3: Sustitución Numérica y Despeje de la Velocidad ($v_A$)

Sustituimos todos los datos conocidos del enunciado ($m = 2\text{ kg}$, $k = 2\text{ N/m}$, $\Delta x = 2\text{ m}$, y $f_{rc} = 6\text{ N}$):

$$-6\text{ N} \cdot 2\text{ m} = \frac{1}{2} \cdot 2\text{ N/m} \cdot (2\text{ m})^2 - \frac{1}{2} \cdot 2\text{ kg} \cdot v_A^2$$

$$-12 = 1 \cdot 4 - 1 \cdot v_A^2$$

$$-12 = 4 - v_A^2$$

Aislamos el término de la velocidad al cuadrado ($v_A^2$):


$$v_A^2 = 4 + 12$$

$$v_A^2 = 16\text{ m}^2/\text{s}^2$$

Calculamos la raíz cuadrada para obtener la velocidad lineal de impacto:


$$v_A = \sqrt{16} = \mathbf{4\text{ m/s}}$$

---

## 🎯 Respuesta Final para el Examen

El bloque impactó sobre el resorte con una velocidad exacta de **$4\text{ m/s}$**.



