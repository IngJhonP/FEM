# Energía y Momento Electromagnético

## Vector de Poynting

### Definición

```
S⃗ = (1/μ₀) * (E⃗ × B⃗)
```

**Significado**: Flujo de energía electromagnética (potencia por unidad de área)

**Unidades**: W/m²

**Dirección**: Dirección de propagación de la energía

### Teorema de Poynting

```
-∂u/∂t = ∇ · S⃗ + J⃗ · E⃗
```

Donde:
- u: Densidad de energía electromagnética
- J⃗ · E⃗: Potencia disipada por unidad de volumen

**Interpretación**: Conservación de energía electromagnética

## Densidad de Energía

### Energía Eléctrica

```
u_E = (ε₀/2) * E²
```

### Energía Magnética

```
u_B = (1/(2μ₀)) * B²
```

### Energía Total

```
u = u_E + u_B = (ε₀/2) * E² + (1/(2μ₀)) * B²
```

Para ondas electromagnéticas: u_E = u_B

## Flujo de Energía

### Potencia a través de una superficie

```
P = ∫ S⃗ · dA⃗
```

### Para onda plana

Intensidad promedio:
```
I = <S> = (ε₀*c/2) * E₀²
```

## Momento Electromagnético

### Densidad de Momento

```
g⃗ = S⃗/c² = (ε₀/c) * (E⃗ × B⃗)
```

### Momento Total

```
p⃗ = ∫ g⃗ dV = (1/c²) ∫ S⃗ dV
```

### Relación con Energía

```
p = U/c
```

## Presión de Radiación

### Absorción Completa

```
P_rad = I/c = <S>/c
```

### Reflexión Completa

```
P_rad = 2I/c = 2<S>/c
```

### Fuerza sobre una Superficie

```
F = P_rad * A
```

## Tensor de Esfuerzos de Maxwell

Describe la densidad de fuerza electromagnética:

```
T_ij = ε₀ * (E_i*E_j - (1/2)*δ_ij*E²) + (1/μ₀) * (B_i*B_j - (1/2)*δ_ij*B²)
```

Fuerza por unidad de volumen:
```
f⃗ = ∇ · T - ε₀*μ₀ * ∂S⃗/∂t
```

## Aplicaciones

### 1. Láser

Presión de radiación en manipulación de partículas:
- Pinzas ópticas
- Enfriamiento láser de átomos

### 2. Velas Solares

Propulsión espacial usando presión de radiación solar.

### 3. Efecto Compton

Colisión de fotón con electrón (conserva momento).

### 4. Cola de Cometas

Presión de radiación solar empuja polvo y gas.

## Radiación de una Carga Acelerada

### Potencia Radiada (Fórmula de Larmor)

Para velocidad no relativista:

```
P = (μ₀*q²*a²)/(6π*c)
```

Donde:
- q: Carga
- a: Aceleración

### Patrón de Radiación

Intensidad angular:
```
I(θ) ∝ sin²(θ)
```

Máxima perpendicular a la aceleración, cero en la dirección de aceleración.

## Radiación de Dipolo

### Potencia Total

```
P = (μ₀*c/6π) * p̈²
```

Donde p̈ es la segunda derivada temporal del momento dipolar.

### Campos Radiados (zona lejana)

```
E = (μ₀/4π) * (p̈ * sin(θ)) / r
B = E/c
```

## Conservación de Energía y Momento

Las ecuaciones de Maxwell garantizan:

1. **Conservación de energía**:
   - Teorema de Poynting

2. **Conservación de momento**:
   - Momento electromagnético + momento mecánico

3. **Conservación de momento angular**:
   - Polarización circular lleva momento angular

## Ejemplo 1 - Presión de Radiación Solar

Intensidad solar en la Tierra: I = 1370 W/m²

Presión por absorción:
```
P = I/c = 1370/(3 × 10⁸) = 4.57 × 10⁻⁶ Pa
```

Fuerza sobre vela de 1 km² (reflexión):
```
F = 2 * P * A = 2 * 4.57 × 10⁻⁶ * 10⁶ = 9.14 N
```

## Ejemplo 2 - Láser

Láser de 1 W, diámetro de haz 1 mm:

Área: A = π * (0.5 × 10⁻³)² = 7.85 × 10⁻⁷ m²

Intensidad:
```
I = P/A = 1/(7.85 × 10⁻⁷) = 1.27 × 10⁶ W/m²
```

Presión de radiación (absorción):
```
P_rad = I/c = 4.24 × 10⁻³ Pa
```

## Ejemplo 3 - Radiación de Electrón

Electrón acelerado: q = 1.6 × 10⁻¹⁹ C, a = 10²⁰ m/s²

```
P = (4π × 10⁻⁷ × (1.6 × 10⁻¹⁹)² × (10²⁰)²) / (6π × 3 × 10⁸)
P = 5.69 × 10⁻¹¹ W
```
