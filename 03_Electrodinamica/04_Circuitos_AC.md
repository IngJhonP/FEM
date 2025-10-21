# Circuitos de Corriente Alterna (AC)

## Señal AC Sinusoidal

### Voltaje

```
v(t) = V_max * sin(ωt + φ)
```

Donde:
- V_max: Amplitud (voltaje pico)
- ω = 2πf: Frecuencia angular
- φ: Fase inicial

### Corriente

```
i(t) = I_max * sin(ωt + φ)
```

## Valores Característicos

### Valor RMS (Root Mean Square)

```
V_rms = V_max / √2
I_rms = I_max / √2
```

El voltaje doméstico (120 V o 220 V) está en valores RMS.

### Valor Promedio

Para sinusoide pura sobre un ciclo completo: 0

Para rectificación de media onda:
```
V_avg = V_max / π
```

## Elementos en AC

### Resistencia

- Voltaje y corriente en fase (φ = 0)
- V_R = I * R
- Potencia: P = I²R (disipada como calor)

### Capacitancia

Reactancia capacitiva:
```
X_C = 1/(ω*C) = 1/(2πf*C)
```

- Corriente adelanta al voltaje por 90° (φ = -90°)
- V_C = I * X_C
- Potencia promedio: 0 (almacenada/liberada)

### Inductancia

Reactancia inductiva:
```
X_L = ω*L = 2πf*L
```

- Voltaje adelanta a la corriente por 90° (φ = +90°)
- V_L = I * X_L
- Potencia promedio: 0 (almacenada/liberada)

## Circuito RLC Serie

### Impedancia

```
Z = √(R² + (X_L - X_C)²)
```

Forma compleja:
```
Z = R + j(X_L - X_C)
```

### Corriente

```
I = V / Z
```

### Ángulo de Fase

```
tan(φ) = (X_L - X_C) / R
```

- φ > 0: Circuito inductivo
- φ < 0: Circuito capacitivo
- φ = 0: Circuito resistivo (resonancia)

## Resonancia

Ocurre cuando X_L = X_C

Frecuencia de resonancia:
```
f₀ = 1 / (2π√(LC))
```

En resonancia:
- Z = R (mínima)
- I = máxima
- Factor de calidad: Q = ω₀L/R = 1/(ω₀RC)

## Potencia en AC

### Potencia Instantánea

```
p(t) = v(t) * i(t)
```

### Potencia Promedio (Real)

```
P = V_rms * I_rms * cos(φ)
```

Donde cos(φ) es el factor de potencia.

### Potencia Reactiva

```
Q = V_rms * I_rms * sin(φ)
```

Unidad: VAR (volt-ampere reactivo)

### Potencia Aparente

```
S = V_rms * I_rms
```

Unidad: VA (volt-ampere)

Relación:
```
S² = P² + Q²
```

## Factor de Potencia

```
FP = cos(φ) = P/S = R/Z
```

- FP = 1: Circuito puramente resistivo (ideal)
- FP < 1: Energía reactiva presente

## Diagrama de Fasores

Representación vectorial de cantidades AC:
- Longitud: Amplitud
- Ángulo: Fase
- Rotación: ω (antihoraria)

## Aplicaciones

1. **Transmisión de energía**: Alta eficiencia a largo alcance
2. **Transformadores**: Solo funciona con AC
3. **Motores AC**: Industria, electrodomésticos
4. **Electrónica**: Fuentes de alimentación

## Ejemplo

Circuito RLC: R = 50 Ω, L = 100 mH, C = 10 μF, V = 120 V, f = 60 Hz

X_L = 2π × 60 × 0.1 = 37.7 Ω
X_C = 1/(2π × 60 × 10 × 10⁻⁶) = 265.3 Ω

Z = √(50² + (37.7 - 265.3)²) = 232.8 Ω

I = 120/232.8 = 0.515 A

tan(φ) = (37.7 - 265.3)/50 = -4.55
φ = -77.6° (capacitivo)

Factor de potencia = cos(-77.6°) = 0.215

Frecuencia de resonancia:
f₀ = 1/(2π√(0.1 × 10 × 10⁻⁶)) = 159.2 Hz
