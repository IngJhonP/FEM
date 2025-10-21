# Ley de Biot-Savart

## Definición

La Ley de Biot-Savart permite calcular el campo magnético generado por una corriente eléctrica.

## Forma General

Para un elemento de corriente:

```
dB⃗ = (μ₀/4π) * (I * dl⃗ × r̂) / r²
```

Donde:
- dB⃗: Campo magnético diferencial (T)
- μ₀: Permeabilidad del vacío (μ₀ = 4π × 10⁻⁷ T·m/A)
- I: Corriente eléctrica (A)
- dl⃗: Elemento diferencial de longitud del conductor
- r: Distancia al punto de observación
- r̂: Vector unitario desde dl⃗ hacia el punto

## Campo Magnético Total

```
B⃗ = ∫ dB⃗ = (μ₀*I/4π) ∫ (dl⃗ × r̂) / r²
```

## Aplicaciones Comunes

### 1. Alambre Recto Infinito

```
B = (μ₀ * I) / (2π * r)
```

Dirección: Regla de la mano derecha

### 2. Espira Circular

En el centro:
```
B = (μ₀ * I) / (2 * R)
```

En el eje (distancia z del centro):
```
B = (μ₀ * I * R²) / (2 * (R² + z²)^(3/2))
```

### 3. Solenoide

En el interior de un solenoide largo:
```
B = μ₀ * n * I
```

Donde n es el número de vueltas por unidad de longitud.

### 4. Arco de Circunferencia

Campo en el centro de un arco de ángulo θ:
```
B = (μ₀ * I * θ) / (4π * R)
```

## Comparación con Campo Eléctrico

| Campo Eléctrico | Campo Magnético |
|-----------------|-----------------|
| E⃗ = k*q/r² * r̂ | B⃗ requiere corriente |
| Cae con 1/r² | Cae con 1/r² |
| Radial | Circular (alambre recto) |

## Ejemplo

Calcular B a 5 cm de un alambre recto con I = 10 A:

```
B = (4π × 10⁻⁷ × 10) / (2π × 0.05)
B = 4 × 10⁻⁵ T = 40 μT
```
