# **UT2 – Sistemas electrónicos analógicos y digitales**

## Contenido

1. Fundamentos básicos de las señales eléctricas.  
2. Señales continuas y alternas.  
3. Señales periódicas y aleatorias.  
4. Amplitud, frecuencia y periodo de una señal periódica.  
5. Señales en tiempo continuo y discreto.  
6. Conversión analógico-digital: muestreo, cuantificación y codificación.

---

## 1. Fundamentos básicos de las señales eléctricas

Las señales eléctricas son variaciones de magnitudes como la **tensión (V)** o la **corriente (I)** a lo largo del tiempo.  
Constituyen la base de la electrónica y las telecomunicaciones.

- **Corriente (I):** flujo de carga eléctrica por un conductor.  
- **Tensión (V):** diferencia de potencial eléctrico entre dos puntos.  
- **Resistencia (R):** oposición al paso de la corriente.  
- **Potencia (P):** energía consumida o generada por unidad de tiempo.  
  - $P = V \cdot I$  
- **Energía (E):** capacidad de realizar un trabajo eléctrico.  
  - $E = P \cdot t$

---

## 2. Señales continuas y alternas

- **Señal continua (DC):** mantiene su valor constante en el tiempo.  
  Ejemplo: la tensión de una pila o batería.

- **Señal alterna (AC):** varía periódicamente de valor, cambiando de polaridad.  
  Ejemplo: la tensión de la red eléctrica.

---

## 3. Señales periódicas y aleatorias

- **Señales periódicas:** se repiten de forma regular en el tiempo.  
  
  - Ejemplo: una onda senoidal, cuadrada o triangular.  

- **Señales aleatorias:** no siguen un patrón fijo y son impredecibles.  
  
  - Ejemplo: ruido eléctrico captado por una antena.

---

## 4. Amplitud, frecuencia y periodo

- **Amplitud (A):** valor máximo que alcanza la señal.  
- **Periodo (T):** tiempo que tarda la señal en repetirse.  
- **Frecuencia (f):** número de repeticiones por segundo.  
  - Relación: $f = \dfrac{1}{T}$  

Ejemplo:  
Una señal con $T = 0,01 \, s$ tiene una frecuencia de $f = 100 \, Hz$.

---

## 5. Señales en tiempo continuo y discreto

- **Tiempo continuo:** la señal está definida en todos los instantes.  
  Ejemplo: la salida de un micrófono.  

- **Tiempo discreto:** la señal solo se define en determinados instantes de tiempo.  
  Ejemplo: los datos obtenidos al muestrear una señal analógica con un ordenador.

---

## 6. Conversión analógico-digital (A/D)

La conversión A/D permite transformar una señal **analógica** (continua) en una **digital** (discreta) para poder ser procesada por un ordenador o microcontrolador.  
Consta de tres etapas:

1. **Muestreo:** se toman muestras de la señal en intervalos regulares.  
   
   - Definido por la **frecuencia de muestreo** ($f_s$).  
   - Según el **teorema de Nyquist**, $f_s \geq 2 \cdot f_{máx}$ de la señal.  

2. **Cuantificación:** cada muestra se aproxima a un valor discreto entre un número limitado de niveles.  

3. **Codificación:** los valores cuantificados se representan en forma binaria.  
   
   - Depende de la **resolución del conversor**, expresada en **bits**.  
   - Un ADC de 8 bits puede representar $2^8 = 256$ niveles.  

Ejemplo:  
Una señal de audio de 20 kHz necesita muestrearse, al menos, a $40 kHz$ para ser digitalizada sin pérdidas.

---

## Resumen gráfico

- **DC:** valor constante (batería).  
- **AC periódica:** onda senoidal de la red eléctrica.  
- **Señal discreta:** valores digitalizados en el tiempo.  
- **Conversión A/D:** señal analógica → muestreo → cuantificación → código binario.

---
