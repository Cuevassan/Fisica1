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

$$-90 = -10 \cdot d^2 \quad \text{[cite: 1766]}$$

Cancelamos los signos negativos en ambos miembros y despejamos la variable cuadrática $d^2$:


$$d^2 = \frac{-90}{-10} = 9\text{ m}^2 \quad \text{}$$

$$d = \sqrt{9\text{ m}^2} = \mathbf{3\text{ m}} \quad \text{}$$

---

## 🎯 Resumen de Respuestas para el Examen

* **a) Trabajo de la fuerza variable ($W_F$):** **$-90\text{ J}$**.


* **b) Distancia de detención ($d$):** **$3\text{ m}$**.



---

