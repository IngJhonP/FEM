# Ley de Ampère

## Definición

La Ley de Ampère relaciona la circulación del campo magnético a lo largo de una curva cerrada con la corriente que atraviesa la superficie limitada por esa curva.

## Forma Integral

```
∮ B⃗ · dl⃗ = μ₀ * I_enc
```

Donde:
- ∮: Integral de línea sobre una curva cerrada
- B⃗: Campo magnético
- dl⃗: Elemento diferencial de longitud
- I_enc: Corriente total que atraviesa la superficie (corriente encerrada)
- μ₀: Permeabilidad del vacío

## Forma Diferencial

```
∇ × B⃗ = μ₀ * J⃗
```

Donde:
- ∇ × B⃗: Rotacional del campo magnético
- J⃗: Densidad de corriente

## Aplicaciones

### 1. Alambre Recto Infinito

Usando una curva amperiana circular:

```
B * 2πr = μ₀ * I
B = (μ₀ * I) / (2π * r)
```

### 2. Solenoide Largo

```
B * L = μ₀ * n * L * I
B = μ₀ * n * I
```

Donde n = N/L es el número de vueltas por unidad de longitud.

### 3. Toroide

Dentro del toroide:
```
B * 2πr = μ₀ * N * I
B = (μ₀ * N * I) / (2π * r)
```

Fuera: B = 0

### 4. Cable Coaxial

Entre conductores internos y externos:
```
B = (μ₀ * I) / (2π * r)
```

## Simetría Requerida

Para aplicar la Ley de Ampère efectivamente:
- Simetría cilíndrica (alambre infinito)
- Simetría planar (lámina de corriente)
- Simetría toroidal (toroide)

## Comparación con Ley de Gauss

| Ley de Gauss (eléctrica) | Ley de Ampère |
|--------------------------|---------------|
| ∮ E⃗ · dA⃗ = Q_enc/ε₀ | ∮ B⃗ · dl⃗ = μ₀*I_enc |
| Superficie cerrada | Curva cerrada |
| Flujo eléctrico | Circulación magnética |

## Ley de Ampère-Maxwell

Forma completa con corriente de desplazamiento:

```
∮ B⃗ · dl⃗ = μ₀ * (I_enc + ε₀ * dΦ_E/dt)
```

## Ejemplo

Solenoide con n = 1000 vueltas/m, I = 5 A:

```
B = (4π × 10⁻⁷) * 1000 * 5
B = 6.28 × 10⁻³ T = 6.28 mT
```
