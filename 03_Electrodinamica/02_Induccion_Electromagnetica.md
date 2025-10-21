# Inducción Electromagnética

## Conceptos Fundamentales

La inducción electromagnética es el proceso mediante el cual un campo magnético variable genera un campo eléctrico.

## Corrientes de Foucault (Eddy Currents)

### Definición
Corrientes circulares inducidas en conductores por campos magnéticos variables.

### Características
- Crean pérdidas de energía por calentamiento (I²R)
- Se oponen al movimiento (fuerza de frenado)
- Pueden reducirse con laminaciones

### Aplicaciones
1. **Frenos**: Trenes de alta velocidad
2. **Amortiguadores**: Sistemas mecánicos
3. **Calentamiento por inducción**: Cocinas, hornos industriales
4. **Detección de metales**: Seguridad, arqueología

## Generadores

### Generador AC Simple

FEM generada por espira rotando en campo magnético:

```
ε(t) = N * B * A * ω * sin(ωt)
```

Donde:
- N: Número de espiras
- B: Campo magnético
- A: Área de la espira
- ω: Velocidad angular

FEM máxima:
```
ε_max = N * B * A * ω
```

### Generador DC

- Usa conmutador para rectificar la corriente
- Produce corriente pulsante unidireccional

## Transformadores

### Principio de Funcionamiento
Basado en inducción mutua entre bobinas.

### Relaciones

Voltajes:
```
V_s / V_p = N_s / N_p
```

Corrientes (transformador ideal):
```
I_s / I_p = N_p / N_s
```

Potencia (sin pérdidas):
```
P_s = P_p
V_s * I_s = V_p * I_p
```

Donde:
- Subíndice p: Primario
- Subíndice s: Secundario

### Tipos
1. **Elevador**: N_s > N_p (aumenta voltaje)
2. **Reductor**: N_s < N_p (disminuye voltaje)
3. **Aislamiento**: N_s = N_p (aislamiento eléctrico)

### Eficiencia

```
η = P_salida / P_entrada × 100%
```

Pérdidas típicas:
- Corrientes de Foucault en el núcleo
- Resistencia de los devanados
- Histéresis magnética
- Flujo disperso

## Inductancia Mutua

Cuando dos bobinas están cerca:

```
ε₂ = -M * dI₁/dt
```

Donde M es la inductancia mutua.

Para dos solenoides coaxiales:
```
M = μ₀ * n₁ * n₂ * A * L
```

## Autoinducción

FEM inducida en una bobina por su propia corriente variable:

```
ε = -L * dI/dt
```

## Ejemplo - Transformador

Transformador: N_p = 100, N_s = 500, V_p = 120 V

Voltaje secundario:
```
V_s = V_p * (N_s/N_p) = 120 * (500/100) = 600 V
```

Si I_s = 2 A (ideal):
```
I_p = I_s * (N_s/N_p) = 2 * (500/100) = 10 A
```

## Ejemplo - Generador

Espira: N = 100, A = 0.1 m², B = 0.5 T, f = 60 Hz

ω = 2πf = 377 rad/s

```
ε_max = 100 * 0.5 * 0.1 * 377 = 1885 V
```
