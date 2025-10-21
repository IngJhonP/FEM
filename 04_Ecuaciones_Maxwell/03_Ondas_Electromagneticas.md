# Ondas Electromagnéticas

## Ecuación de Onda

En el vacío, sin fuentes (ρ = 0, J⃗ = 0):

```
∇²E⃗ - (1/c²) * ∂²E⃗/∂t² = 0
∇²B⃗ - (1/c²) * ∂²B⃗/∂t² = 0
```

Velocidad de la luz:
```
c = 1/√(μ₀*ε₀) ≈ 2.998 × 10⁸ m/s
```

## Ondas Planas

### Forma General

```
E⃗(r⃗, t) = E⃗₀ * cos(k⃗ · r⃗ - ωt + φ)
B⃗(r⃗, t) = B⃗₀ * cos(k⃗ · r⃗ - ωt + φ)
```

Donde:
- E⃗₀, B⃗₀: Amplitudes
- k⃗: Vector de onda (dirección de propagación)
- ω: Frecuencia angular
- φ: Fase inicial

### Relación de Dispersión

```
ω = c * |k⃗|
```

O equivalentemente:
```
f = c / λ
```

Donde:
- f: Frecuencia (Hz)
- λ: Longitud de onda (m)

## Propiedades de Ondas EM

### 1. Transversalidad

```
E⃗ ⊥ B⃗ ⊥ k⃗
```

Los campos son perpendiculares entre sí y a la dirección de propagación.

### 2. Relación entre Amplitudes

```
|B⃗| = |E⃗| / c
```

### 3. Misma Fase

E⃗ y B⃗ oscilan en fase (máximos y mínimos simultáneos).

### 4. Vector de Poynting

Dirección y magnitud del flujo de energía:

```
S⃗ = (1/μ₀) * (E⃗ × B⃗)
```

Magnitud:
```
S = (1/μ₀) * E * B = (1/(μ₀*c)) * E²
```

## Energía y Momentum

### Densidad de Energía

Energía eléctrica:
```
u_E = (ε₀/2) * E²
```

Energía magnética:
```
u_B = (1/(2μ₀)) * B²
```

Total:
```
u = u_E + u_B = ε₀ * E²
```

(Igual contribución de E y B)

### Intensidad

Valor promedio de |S⃗|:

```
I = <S> = (ε₀*c/2) * E₀² = (c/2μ₀) * B₀²
```

En términos de campo RMS:
```
I = ε₀*c * E_rms²
```

### Presión de Radiación

Para absorción completa:
```
P = I/c
```

Para reflexión completa:
```
P = 2I/c
```

## Polarización

### Polarización Lineal

Campo eléctrico oscila en un plano fijo.

### Polarización Circular

Campo eléctrico rota uniformemente.

Derecha o izquierda según sentido de rotación.

### Polarización Elíptica

Caso general, combinación de las anteriores.

## Espectro Electromagnético

| Tipo | Frecuencia | Longitud de onda | Aplicaciones |
|------|-----------|------------------|--------------|
| Radio | < 3 GHz | > 10 cm | Comunicación |
| Microondas | 3 GHz - 300 GHz | 1 mm - 10 cm | Radar, cocina |
| Infrarrojo | 300 GHz - 430 THz | 700 nm - 1 mm | Termografía |
| Visible | 430 - 750 THz | 400 - 700 nm | Visión |
| Ultravioleta | 750 THz - 30 PHz | 10 - 400 nm | Esterilización |
| Rayos X | 30 PHz - 30 EHz | 0.01 - 10 nm | Medicina |
| Rayos γ | > 30 EHz | < 0.01 nm | Nuclear |

## Ondas en Medios Materiales

Velocidad en medio:
```
v = c/n
```

Donde n es el índice de refracción:
```
n = √(εᵣ * μᵣ) = √(ε/ε₀) * √(μ/μ₀)
```

## Reflexión y Refracción

### Ley de Snell

```
n₁ * sin(θ₁) = n₂ * sin(θ₂)
```

### Ángulo Crítico

Para n₁ > n₂:
```
θc = arcsin(n₂/n₁)
```

Para θ₁ > θc: reflexión total interna

### Coeficientes de Fresnel

Determinan amplitud de ondas reflejadas y transmitidas.

## Efecto Doppler

Para fuente en movimiento:

```
f' = f * √((1 ± β)/(1 ∓ β))
```

Donde β = v/c

- (+) si se acercan
- (-) si se alejan

## Ejemplo 1

Onda con E₀ = 100 V/m:

Campo magnético:
```
B₀ = E₀/c = 100/(3 × 10⁸) = 3.33 × 10⁻⁷ T
```

Intensidad:
```
I = (ε₀*c/2) * E₀²
I = (8.85 × 10⁻¹² × 3 × 10⁸ / 2) * (100)²
I = 13.3 W/m²
```

## Ejemplo 2

Luz amarilla: λ = 580 nm

Frecuencia:
```
f = c/λ = (3 × 10⁸)/(580 × 10⁻⁹) = 5.17 × 10¹⁴ Hz
```

En agua (n = 1.33):
```
v = c/n = 2.26 × 10⁸ m/s
λ' = v/f = 436 nm
```
