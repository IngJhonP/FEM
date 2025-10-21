# Inductancia

## Definición

La inductancia es la propiedad de un circuito de oponerse a cambios en la corriente eléctrica.

## Autoinductancia

### Definición

```
L = Φ_B / I
```

O equivalentemente:
```
ε = -L * dI/dt
```

Donde:
- L: Inductancia (H, henry)
- Φ_B: Flujo magnético total
- I: Corriente

### Solenoide

```
L = μ₀ * n² * A * l
```

Donde:
- n: Número de vueltas por unidad de longitud
- A: Área de la sección transversal
- l: Longitud del solenoide

Con núcleo:
```
L = μᵣ * μ₀ * n² * A * l
```

### Toroide

```
L = (μ₀ * N² * A) / (2π * r)
```

## Inductancia Mutua

Acoplamiento entre dos circuitos:

```
M₁₂ = M₂₁ = M
ε₂ = -M * dI₁/dt
```

Coeficiente de acoplamiento:
```
k = M / √(L₁ * L₂)
```

Donde 0 ≤ k ≤ 1

## Energía Almacenada

Energía en un inductor:

```
U = (1/2) * L * I²
```

Densidad de energía magnética:

```
u_B = B² / (2μ₀)
```

## Circuito RL

### Ecuación diferencial

```
V = I*R + L*dI/dt
```

### Corriente creciente (conexión)

```
I(t) = (V/R) * (1 - e^(-t/τ))
```

### Corriente decreciente (desconexión)

```
I(t) = I₀ * e^(-t/τ)
```

### Constante de tiempo

```
τ = L/R
```

- Tiempo para alcanzar ~63% del valor final (creciente)
- Tiempo para disminuir a ~37% del valor inicial (decreciente)

## Combinación de Inductores

### Serie

```
L_eq = L₁ + L₂ + L₃ + ...
```

(Sin inductancia mutua)

### Paralelo

```
1/L_eq = 1/L₁ + 1/L₂ + 1/L₃ + ...
```

## Reactancia Inductiva

En circuitos AC:

```
X_L = ω*L = 2πf*L
```

Impedancia:
```
Z = √(R² + X_L²)
```

## Aplicaciones

1. **Filtros**: Bloquean altas frecuencias
2. **Transformadores**: Transferencia de energía
3. **Motores eléctricos**: Almacenamiento de energía
4. **Fuentes de alimentación**: Suavizado de corriente
5. **Circuitos resonantes**: Radio, TV

## Ejemplo 1

Solenoide: n = 1000 vueltas/m, A = 10 cm², l = 50 cm

```
L = (4π × 10⁻⁷) * (1000)² * (10 × 10⁻⁴) * 0.5
L = 6.28 × 10⁻⁴ H = 0.628 mH
```

## Ejemplo 2

Circuito RL: L = 10 mH, R = 50 Ω, V = 12 V

Constante de tiempo:
```
τ = L/R = 0.01/50 = 2 × 10⁻⁴ s = 0.2 ms
```

Corriente final:
```
I_final = V/R = 12/50 = 0.24 A
```

En t = τ:
```
I(τ) = 0.24 * (1 - e⁻¹) = 0.24 * 0.632 = 0.152 A
```
