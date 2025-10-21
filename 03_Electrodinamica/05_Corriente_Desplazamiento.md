# Corriente de Desplazamiento

## Motivación

La Ley de Ampère clásica tiene una inconsistencia con la ecuación de continuidad cuando hay cargas acumulándose (ej: capacitor cargándose).

## Definición de Maxwell

Maxwell modificó la Ley de Ampère agregando un término: la corriente de desplazamiento.

### Corriente de Desplazamiento

```
I_d = ε₀ * dΦ_E/dt
```

Densidad de corriente de desplazamiento:
```
J⃗_d = ε₀ * ∂E⃗/∂t
```

Donde:
- I_d: Corriente de desplazamiento (A)
- Φ_E: Flujo eléctrico (V·m)
- E⃗: Campo eléctrico

## Ley de Ampère-Maxwell

### Forma Completa

```
∮ B⃗ · dl⃗ = μ₀ * (I_enc + I_d)
∮ B⃗ · dl⃗ = μ₀ * (I_enc + ε₀ * dΦ_E/dt)
```

### Forma Diferencial

```
∇ × B⃗ = μ₀ * J⃗ + μ₀*ε₀ * ∂E⃗/∂t
```

## Capacitor Cargándose

Ejemplo clásico que muestra la necesidad de I_d:

Entre las placas de un capacitor:
- No hay corriente de conducción (I_c = 0)
- Hay campo eléctrico creciente
- Corriente de desplazamiento: I_d = ε₀ * dΦ_E/dt

Resultado: I_d = I_c (continuidad de corriente)

## Significado Físico

1. **Campo eléctrico variable** actúa como fuente de campo magnético
2. Permite **ondas electromagnéticas** en el vacío
3. Completa la **simetría** de las ecuaciones de Maxwell
4. No es una corriente real (sin carga en movimiento)

## Cálculo para Capacitor de Placas Paralelas

Campo eléctrico entre placas:
```
E = σ/ε₀ = Q/(ε₀*A)
```

Flujo eléctrico:
```
Φ_E = E * A = Q/ε₀
```

Corriente de desplazamiento:
```
I_d = ε₀ * dΦ_E/dt = ε₀ * d(Q/ε₀)/dt = dQ/dt = I
```

¡La corriente de desplazamiento igual a la corriente de conducción!

## Campo Magnético en Capacitor

Usando Ampère-Maxwell en región entre placas:

```
B * 2πr = μ₀ * I_d
B = (μ₀ * I_d) / (2πr)
```

Mismo resultado que para alambre con corriente I.

## Importancia Histórica

- Predicción teórica de Maxwell (1861)
- Permitió derivar ondas electromagnéticas
- Velocidad calculada: c = 1/√(μ₀ε₀) ≈ 3 × 10⁸ m/s
- Confirmó naturaleza electromagnética de la luz

## Comparación

| Corriente de Conducción | Corriente de Desplazamiento |
|------------------------|----------------------------|
| Carga en movimiento | Campo eléctrico variable |
| J⃗_c = ρv⃗ | J⃗_d = ε₀∂E⃗/∂t |
| Causa calentamiento | No disipa energía |
| En conductores | En vacío/dieléctricos |

## Ejemplo

Capacitor: A = 0.01 m², d = 1 mm, cargándose con I = 2 A

Tasa de cambio del campo eléctrico:
```
dE/dt = I / (ε₀*A)
dE/dt = 2 / (8.85 × 10⁻¹² × 0.01)
dE/dt = 2.26 × 10¹³ V/(m·s)
```

Corriente de desplazamiento:
```
I_d = ε₀ * A * dE/dt = 2 A
```

Campo magnético a r = 5 mm del centro:
```
B = (4π × 10⁻⁷ × 2) / (2π × 0.005)
B = 8 × 10⁻⁵ T = 80 μT
```
