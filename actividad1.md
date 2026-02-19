# Actividad: Números Binarios

---

## 1. Sistema Binario

### 1.1 Convierte el número decimal 22 a binario

| 16 | 8 | 4 | 2 | 1 |
|----|---|---|---|---|
| 1  | 0 | 1 | 1 | 0 |

**Resultado:**  
22₁₀ = 10110₂

---

### 1.2 Convierte el número binario 10110 a decimal

Descomposición por potencias de 2:

10110₂ = (1·16) + (0·8) + (1·4) + (1·2) + (0·1)

16 + 4 + 2 = 22

**Resultado:**  
10110₂ = 22₁₀

---

## 2. Representación de Diferentes Tipos de Datos en el Mundo Digital

### 2.1 ¿Qué número binario representa el carácter 'C' en ASCII?

- Valor decimal de 'C': 67  
- Conversión a binario (8 bits):

**Resultado:**  
'C' = 01000011₂

---

### 2.2 Convierte el número flotante 5.75 a binario

#### Parte entera: 5

| División | Cociente | Residuo |
|----------|----------|----------|
| 5 ÷ 2    | 2        | 1        |
| 2 ÷ 2    | 1        | 0        |
| 1 ÷ 2    | 0        | 1        |

Leyendo los residuos de abajo hacia arriba:

5₁₀ = 101₂

---

#### Parte decimal: 0.75

| Operación | Resultado | Bit |
|------------|------------|------|
| 0.75 × 2   | 1.5        | 1    |
| 0.5 × 2    | 1.0        | 1    |

Se detiene cuando el resultado decimal llega a 0:

0.75₁₀ = 0.11₂

---

### Resultado completo

5.75₁₀ = 101.11₂

---

## 3. Almacenamiento Digital de Datos

### 3.1 ¿Cuántos bytes se necesitan para almacenar la palabra “Hola” en ASCII?

Cada carácter en ASCII ocupa 1 byte.

Hola → 4 caracteres

4 × 1 byte = 4 bytes

**Resultado:**  
Se necesitan 4 bytes.

---

### 3.2 ¿Cuántos bits hay en 5 KB?

Equivalencias:

- 1 byte = 8 bits  
- 1 KB = 1024 bytes  

Cálculo:

5 KB = 5 × 1024 = 5120 bytes  
5120 × 8 = 40 960 bits

**Resultado:**  
5 KB = 40 960 bits

---

## 4. Otras Temáticas Relevantes

### 4.1 Convierte el número decimal 255 a hexadecimal

Divisiones entre 16:

255 ÷ 16 = 15 → F  
15 ÷ 16 = 0 → F  

Leyendo de abajo hacia arriba:

**Resultado:**  
255₁₀ = FF₁₆

---

### 4.2 ¿Cuál es el valor hexadecimal de la secuencia binaria 11010110?

Agrupamos en bloques de 4 bits:

1101   0110

Conversión:

1101 → D  
0110 → 6  

**Resultado:**  
11010110₂ = D6₁₆

---

## 5. Ejercicios Finales de Repaso

### 5.1 ¿Por qué las computadoras usan el sistema binario?

Las computadoras utilizan el sistema binario porque trabajan con componentes electrónicos que solo pueden estar en dos estados: encendido (1) o apagado (0).  

Esto permite procesar información de manera rápida, confiable y con menor probabilidad de errores. Gracias al sistema binario, se pueden representar números, textos, imágenes y sonidos de forma eficiente.

---

### 5.2 Convierte el número binario 10011011 a decimal y hexadecimal

#### A decimal

10011011₂ =  
(1·128) + (0·64) + (0·32) + (1·16) + (1·8) + (0·4) + (1·2) + (1·1)

128 + 16 + 8 + 2 + 1 = 155

**Resultado:**  
10011011₂ = 155₁₀

---

#### A hexadecimal

Agrupamos en bloques de 4 bits:

1001   1011

Conversión:

1001 → 9  
1011 → B  

**Resultado:**  
10011011₂ = 9B₁₆

---

### 5.3 ¿Cómo se representa una imagen PNG en el disco?

Una imagen en formato PNG no se guarda como un dibujo, sino como datos estructurados.  

El archivo almacena información sobre:

- Dimensiones de la imagen  
- Colores  
- Píxeles  
- Metadatos  

Todos estos datos se representan en números binarios, lo que permite que la imagen se abra correctamente en distintos dispositivos sin perder calidad.

---

### 5.4 ¿Qué pasa si intentas almacenar el número 300 en un byte? ¿Cómo lo maneja Python?

#### En un byte

Un byte puede representar valores entre:

0 y 255

El número 300 no cabe en un byte.

En lenguajes de bajo nivel (como C), puede ocurrir **overflow**, es decir, el valor se desborda.

Ejemplo:

300 - 256 = 44  
Se almacenaría 44 en lugar de 300.

---

#### En Python

Python no tiene este problema porque:

- Los enteros no tienen tamaño fijo.
- Python usa automáticamente más memoria cuando la necesita.

```python
x = 300
