# Ecuaciones de Maxwell - Forma Diferencial

## Las Cuatro Ecuaciones

### 1. Ley de Gauss (Eléctrica)

```
∇ · E⃗ = ρ / ε₀
```

**Significado**: La divergencia del campo eléctrico es proporcional a la densidad de carga.

- ∇ · E⃗: Divergencia del campo eléctrico
- ρ: Densidad volumétrica de carga (C/m³)

### 2. Ley de Gauss (Magnética)

```
∇ · B⃗ = 0
```

**Significado**: El campo magnético es solenoidal (sin divergencia).

### 3. Ley de Faraday-Lenz

```
∇ × E⃗ = -∂B⃗/∂t
```

**Significado**: El rotacional del campo eléctrico es igual al negativo de la derivada temporal del campo magnético.

- ∇ × E⃗: Rotacional del campo eléctrico

### 4. Ley de Ampère-Maxwell

```
∇ × B⃗ = μ₀ * J⃗ + μ₀*ε₀ * ∂E⃗/∂t
```

**Significado**: El rotacional del campo magnético depende de la densidad de corriente y del cambio temporal del campo eléctrico.

- J⃗: Densidad de corriente (A/m²)
- μ₀*ε₀ * ∂E⃗/∂t: Término de corriente de desplazamiento

## Operadores Diferenciales

### Gradiente
```
∇V = ∂V/∂x * x̂ + ∂V/∂y * ŷ + ∂V/∂z * ẑ
```

### Divergencia
```
∇ · F⃗ = ∂Fx/∂x + ∂Fy/∂y + ∂Fz/∂z
```

### Rotacional
```
∇ × F⃗ = |x̂    ŷ    ẑ  |
        |∂/∂x ∂/∂y ∂/∂z|
        |Fx   Fy   Fz  |
```

### Laplaciano
```
∇²V = ∂²V/∂x² + ∂²V/∂y² + ∂²V/∂z²
```

## Forma en Medios Materiales

```
∇ · D⃗ = ρ_free

∇ · B⃗ = 0

∇ × E⃗ = -∂B⃗/∂t

∇ × H⃗ = J⃗_free + ∂D⃗/∂t
```

## Potenciales Electromagnéticos

### Potencial Escalar

```
E⃗ = -∇V - ∂A⃗/∂t
```

### Potencial Vector

```
B⃗ = ∇ × A⃗
```

Satisfacen automáticamente ∇ · B⃗ = 0

## Gauge de Lorenz

```
∇ · A⃗ + μ₀*ε₀ * ∂V/∂t = 0
```

Con esta condición:

### Ecuación de onda para V
```
∇²V - μ₀*ε₀ * ∂²V/∂t² = -ρ/ε₀
```

### Ecuación de onda para A⃗
```
∇²A⃗ - μ₀*ε₀ * ∂²A⃗/∂t² = -μ₀*J⃗
```

## Ecuación de Continuidad

Tomando la divergencia de la Ley de Ampère-Maxwell:

```
∇ · (∇ × B⃗) = 0 = μ₀ * ∇ · J⃗ + μ₀*ε₀ * ∂(∇ · E⃗)/∂t
```

Usando ∇ · E⃗ = ρ/ε₀:

```
∇ · J⃗ + ∂ρ/∂t = 0
```

**Conservación de la carga eléctrica**

## Ecuación de Onda en el Vacío

Aplicando ∇× a las ecuaciones de Faraday y Ampère-Maxwell (sin fuentes):

```
∇²E⃗ - μ₀*ε₀ * ∂²E⃗/∂t² = 0

∇²B⃗ - μ₀*ε₀ * ∂²B⃗/∂t² = 0
```

Velocidad de propagación:
```
c = 1/√(μ₀*ε₀) ≈ 3 × 10⁸ m/s
```

## Simetrías

### Dualidad Electromagnética

En el vacío (sin fuentes), las ecuaciones muestran simetría:

```
E⃗ ↔ c*B⃗
B⃗ ↔ -E⃗/c
```

### Invariancia de Gauge

Los potenciales A⃗ y V no son únicos. Transformaciones de gauge:

```
A⃗' = A⃗ + ∇χ
V' = V - ∂χ/∂t
```

No cambian E⃗ y B⃗.

## Teoremas Importantes

### Teorema de Helmholtz

Un campo vectorial está completamente especificado por:
- Su divergencia (∇ · F⃗)
- Su rotacional (∇ × F⃗)
- Condiciones de frontera

### Identidades Vectoriales

```
∇ · (∇ × F⃗) = 0
∇ × (∇f) = 0
∇ × (∇ × F⃗) = ∇(∇ · F⃗) - ∇²F⃗
```

## Aplicaciones

1. **Análisis de campos**: Cálculo directo
2. **Problemas de frontera**: Condiciones en interfaces
3. **Ondas guiadas**: Guías de onda, fibras ópticas
4. **Radiación**: Antenas, dipolo oscilante
5. **Física computacional**: Simulaciones numéricas
