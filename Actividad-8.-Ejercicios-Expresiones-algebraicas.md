# Actividad-8.-Ejercicios-Expresiones-algebraicas
# Ejercicios de Conversión Numérica

## Realiza las conversiones de binario a decimal

### 73) $00001111 = 15_{10}$

**Procedimiento:**

* $2^0 \cdot 1 = 1$
* $2^1 \cdot 1 = 2$
* $2^2 \cdot 1 = 4$
* $2^3 \cdot 1 = 8$

**Suma:**

$$
1 + 2 + 4 + 8 = 15_{10}
$$

### 74) $10011001 = 153_{10}$

**Procedimiento:**

* $2^0 \cdot 1 = 1$
* $2^3 \cdot 1 = 8$
* $2^4 \cdot 1 = 16$
* $2^7 \cdot 1 = 128$

**Suma:**

$$
128 + 16 + 8 + 1 = 153_{10}
$$

### 75) $11001100 = 204_{10}$

**Procedimiento:**

* $2^2 \cdot 1 = 4$
* $2^3 \cdot 1 = 8$
* $2^6 \cdot 1 = 64$
* $2^7 \cdot 1 = 128$

**Suma:**

$$
128 + 64 + 8 + 4 = 204_{10}
$$

### 76) $01111011 = 251_{10}$

**Procedimiento:**

* $2^0 \cdot 1 = 1$
* $2^1 \cdot 1 = 2$
* $2^3 \cdot 1 = 8$
* $2^4 \cdot 1 = 16$
* $2^5 \cdot 1 = 32$
* $2^6 \cdot 1 = 64$
* $2^7 \cdot 1 = 128$

**Suma:**

$$
128 + 64 + 32 + 16 + 8 + 2 + 1 = 251_{10}
$$

### 77) $0000000011111111 = 255_{10}$

**Procedimiento:**

* $2^0 = 1$
* $2^1 = 2$
* $2^2 = 4$
* $2^3 = 8$
* $2^4 = 16$
* $2^5 = 32$
* $2^6 = 64$
* $2^7 = 128$

**Suma:**

$$
128 + 64 + 32 + 16 + 8 + 4 + 2 + 1 = 255_{10}
$$

### 78) $0000001000000000 = 512_{10}$

**Procedimiento:**

* $2^9 = 512$

---

## Convierte binario a octal

> **Tabla de equivalencia (Binario - Octal):**
>
> | Binario | Octal | Binario | Octal |
> | ----- | ----- | ----- | ----- |
> | $000$ | $0$ | $100$ | $4$ |
> | $001$ | $1$ | $101$ | $5$ |
> | $010$ | $2$ | $110$ | $6$ |
> | $011$ | $3$ | $111$ | $7$ |

### 79) $11010101$

* $011 \rightarrow 3$
* $010 \rightarrow 2$
* $101 \rightarrow 5$

**Resultado:** $325_8$

### 80) $01101110$

* $001 \rightarrow 1$
* $101 \rightarrow 5$
* $110 \rightarrow 6$

**Resultado:** $156_8$

### 81) $10110011$

* $010 \rightarrow 2$
* $110 \rightarrow 6$
* $011 \rightarrow 3$

**Resultado:** $263_8$

### 82) $0000000011111111$

* $000 \rightarrow 0$
* $000 \rightarrow 0$
* $000 \rightarrow 0$
* $011 \rightarrow 3$
* $111 \rightarrow 7$
* $111 \rightarrow 7$

**Resultado:** $377_8$

### 83) $0000001111000000$

* $000 \rightarrow 0$
* $000 \rightarrow 0$
* $011 \rightarrow 3$
* $110 \rightarrow 6$
* $000 \rightarrow 0$
* $000 \rightarrow 0$

**Resultado:** $003_8600_8$

### 84) $0000010101010101$

* $000 \rightarrow 0$
* $000 \rightarrow 0$
* $010 \rightarrow 2$
* $101 \rightarrow 5$
* $010 \rightarrow 2$
* $101 \rightarrow 5$

**Resultado:** $002_8525_8$

---

## Binario a hexadecimal

> **Tabla de equivalencia (Binario - Hexadecimal):**
>
> | Binario | Hex | Binario | Hex |
> | ----- | ----- | ----- | ----- |
> | $0000$ | $0$ | $1000$ | $8$ |
> | $0001$ | $1$ | $1001$ | $9$ |
> | $0010$ | $2$ | $1010$ | $\text{A (10)}$ |
> | $0011$ | $3$ | $1011$ | $\text{B (11)}$ |
> | $0100$ | $4$ | $1100$ | $\text{C (12)}$ |
> | $0101$ | $5$ | $1101$ | $\text{D (13)}$ |
> | $0110$ | $6$ | $1110$ | $\text{E (14)}$ |
> | $0111$ | $7$ | $1111$ | $\text{F (15)}$ |

### 85) $11011010$

* $1101 \rightarrow \text{D}$
* $1010 \rightarrow \text{A}$

**Resultado:** $\text{DA}_{16}$

### 86) $01111100$

* $0111 \rightarrow 7$
* $1100 \rightarrow \text{C}$

**Resultado:** $7\text{C}_{16}$

### 87) $10110101$

* $1011 \rightarrow \text{B}$
* $0101 \rightarrow 5$

**Resultado:** $\text{B}5_{16}$

### 88) $1111000010100101$

* $1111 \rightarrow \text{F}$
* $0000 \rightarrow 0$
* $1010 \rightarrow \text{A}$
* $0101 \rightarrow 5$

**Resultado:** $\text{F0A5}_{16}$

### 89) $0000111100001111$

* $0000 \rightarrow 0$
* $1111 \rightarrow \text{F}$
* $0000 \rightarrow 0$
* $1111 \rightarrow \text{F}$

**Resultado:** $0\text{F}0\text{F}_{16}$

### 90) $1000000000000001$

* $1000 \rightarrow 8$
* $0000 \rightarrow 0$
* $0000 \rightarrow 0$
* $0001 \rightarrow 1$

**Resultado:** $8001_{16}$

---

## Convierte de octal a binario

### 91) $325_8$

* $3 \rightarrow 011$
* $2 \rightarrow 010$
* $5 \rightarrow 101$

**Resultado:** $11010101_2$

### 92) $156_8$

* $1 \rightarrow 001$
* $5 \rightarrow 101$
* $6 \rightarrow 110$

**Resultado:** $01101110_2$

### 93) $377_8$

* $3 \rightarrow 011$
* $7 \rightarrow 111$
* $7 \rightarrow 111$

**Resultado:** $11111111_2$

### 94) $01777_8$

* $0 \rightarrow 000$
* $1 \rightarrow 001$
* $7 \rightarrow 111$
* $7 \rightarrow 111$
* $7 \rightarrow 111$

**Resultado:** $000001111111111_2$

### 95) $03700_8$

* $0 \rightarrow 000$
* $3 \rightarrow 011$
* $7 \rightarrow 111$
* $0 \rightarrow 000$
* $0 \rightarrow 000$

**Resultado:** $000011111000000_2$ (ó $11111000000_2$)

### 96) $05255_8$

* $0 \rightarrow 000$
* $5 \rightarrow 101$
* $2 \rightarrow 010$
* $5 \rightarrow 101$
* $5 \rightarrow 101$

**Resultado:** $000101010101101_2$ (ó $101010101101_2$)

---

## Convierte de hexadecimal a binario

### 97) $\text{DA}_{16}$

* $\text{D} \rightarrow 1101$
* $\text{A} \rightarrow 1010$

**Resultado:** $11011010_2$

### 98) $7\text{C}_{16}$

* $7 \rightarrow 0110$
* $\text{C} \rightarrow 1100$

**Resultado:** $01101100_2$

### 99) $\text{B}5_{16}$

* $\text{B} \rightarrow 1011$
* $5 \rightarrow 0101$

**Resultado:** $10110101_2$

### 100) $\text{F0A5}_{16}$

* $\text{F} \rightarrow 1111$
* $0 \rightarrow 0000$
* $\text{A} \rightarrow 1010$
* $5 \rightarrow 0101$

**Resultado:** $1111000010100101_2$

### 101) $0\text{F}0\text{F}_{16}$

* $0 \rightarrow 0000$
* $\text{F} \rightarrow 1111$
* $0 \rightarrow 0000$
* $\text{F} \rightarrow 1111$

**Resultado:** $0000111100001111_2$ (ó $111100001111_2$)

### 102) $8001_{16}$

* $8 \rightarrow 1000$
* $0 \rightarrow 0000$
* $0 \rightarrow 0000$
* $1 \rightarrow 0001$

**Resultado:** $1000000000000001_2$

---

## Nombrar a sus polinomios por su exponente más alto y número de términos

### 103) $5n + 5$
* **Clasificación:** Binomio lineal
* **Grado:** $1$ (lineal)
* **Términos:** $2$ (binomio)

### 104) $-10p^3 - 6 + 9p^2 - 4p^5 - 2p^8$
* **Clasificación:** Polinomio de octavo grado con cinco términos
* **Grado:** $8$
* **Términos:** $5$

### 105) $7x^8$
* **Clasificación:** Monomio de octavo grado
* **Grado:** $8$
* **Términos:** $1$ (monomio)

### 106) $-2n + n^4 + 10n^6$
* **Clasificación:** Trinomio de sexto grado
* **Grado:** $6$
* **Términos:** $3$ (trinomio)

### 107) $5$
* **Clasificación:** Monomio constante
* **Grado:** $0$ (constante)
* **Términos:** $1$ (monomio constante)

### 108) $5v^7$
* **Clasificación:** Monomio de séptimo grado
* **Grado:** $7$ (séptimo)
* **Términos:** $1$ (monomio)

---

## Resuelve las siguientes preguntas

### 109) Amy puede verter una gran entrada de concreto en ocho horas. Un día su amiga Jill la ayudó y solo tomó 3.08 horas. Encuentra cuánto le tomaría a Jill hacerlo sola.

| Persona | Horas |
| ----- | ----- |
| Amy | $8\text{ hrs}$ |
| Amy y Jill | $3.08\text{ hrs}$ |
| Jill | $t$ |

**Ecuación de trabajo:**

$$
\text{Trabajo de Amy} + \text{Trabajo de Jill} = \text{Trabajo total}
$$

$$
\frac{1}{8}(3.08) + \frac{1}{t}(3.08) = 1
$$

$$
\frac{3.08}{8} + \frac{3.08}{t} = 1
$$

$$
0.385 + \frac{3.08}{t} = 1
$$

$$
\frac{3.08}{t} = 1 - 0.385
$$

$$
\frac{3.08}{t} = 0.615
$$

$$
t = \frac{3.08}{0.615}
$$

**Resultado:** $t = 5.008\text{ horas}$

### 110) Jaidee puede cavar un hoyo de $10\text{ pies}$ por $10\text{ pies}$ en cinco horas. Ted puede cavar el mismo hoyo en $7\text{ horas}$. Si trabajaran juntos, ¿cuánto tiempo les tomaría?

* $10 \cdot 10\text{ pies} = 30.48\text{ metros}$ (1 hueco)
* **Jaidee:** $5\text{ horas}$
* **Ted:** $7\text{ horas}$

$$
\text{Jaidee} + \text{Ted} = \text{Tiempo total}
$$

$$
\text{Tasa de Jaidee} = \frac{1}{5}, \quad \text{Tasa de Ted} = \frac{1}{7}
$$

$$
\frac{1}{5} + \frac{1}{7} = \frac{7 + 5}{35} = \frac{12}{35}
$$

$$
\text{Tiempo} = \frac{35}{12}
$$

**Resultado:** $2.916\text{ horas}$

### 111) Un avión de carga salió de Los Ángeles y voló hacia Moscú. Un avión de la fuerza aérea salió cuatro horas después volando a $310\text{ km/h}$ en un esfuerzo por alcanzar al avión de carga. Después de volar durante seis horas, el avión de la fuerza aérea finalmente lo alcanzó. ¿Cuál era la velocidad promedio del avión de carga?

**Datos del avión de la fuerza aérea:**

* Velocidad = $310\text{ km/h}$
* Tiempo = $6\text{ horas}$
* $\text{Distancia} = 310 \cdot 6 = 1860\text{ km}$

**Datos del avión de carga:**

* $\text{Distancia} = 1860\text{ km}$
* Tiempo = $6 + 4 = 10\text{ horas}$

$$
\text{Velocidad promedio} = \frac{1860}{10}
$$

**Resultado:** $186\text{ km/h}$

### 112) Un tren de carga viajó a Nueva York y de regreso. En el viaje de ida viajó a $35\text{ km/h}$ y en el viaje de regreso fue a $49\text{ km/h}$. ¿Cuánto tiempo tomó el viaje de ida si el viaje de regreso tomó diez horas?

* $t = \frac{d}{v}$
* $\text{Distancia (regreso)} = 49\text{ km/h} \cdot 10\text{ h} = 490\text{ km}$

$$
\text{Tiempo de ida} = \frac{490\text{ km}}{35\text{ km/h}}
$$

**Resultado:** $14\text{ horas}$

### 113) $1\text{ yd}^3$ de tierra que contenía $30\%$ de arena se mezcló con $4\text{ yd}^3$ de tierra que contenía $20\%$ de arena. ¿Cuál es el contenido de arena de la mezcla?

$$
\text{Tierra total} = 1\text{ yd}^3 + 4\text{ yd}^3 = 5\text{ yd}^3
$$

$$
\begin{cases} 1 \cdot 0.30 = 0.30\text{ yd}^3 \\ 4 \cdot 0.20 = 0.80\text{ yd}^3 \end{cases} \implies 0.30 + 0.80 = 1.10\text{ yd}^3\text{ de arena}
$$

$$
\text{Porcentaje} = \frac{1.10}{5} = 0.22 \times 100
$$

**Resultado:** $22\%\text{ de arena}$

### 114) Para su fiesta de cumpleaños, James mezcló $7\text{ L}$ de ponche de frutas de la marca A y $6\text{ L}$ de la marca B. La marca A contiene $11\%$ de jugo de fruta y la marca B contiene $24\%$ de jugo de fruta. ¿Qué porcentaje de la mezcla es jugo de fruta?

$$
\text{Volumen total} = 7\text{ L} + 6\text{ L} = 13\text{ L}
$$

$$
\begin{cases} \text{Marca A:} & 7 \cdot 0.11 = 0.77\text{ L} \\ \text{Marca B:} & 6 \cdot 0.24 = 1.44\text{ L} \end{cases} \implies 0.77 + 1.44 = 2.21\text{ L de jugo}
$$

$$
\text{Porcentaje} = \frac{2.21}{13} \approx 0.17 \times 100
$$

**Resultado:** $17\%$
