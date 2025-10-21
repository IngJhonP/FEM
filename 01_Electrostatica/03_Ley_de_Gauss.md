# Ley de Gauss

## Definición

La Ley de Gauss relaciona el flujo eléctrico a través de una superficie cerrada con la carga total encerrada.

## Forma Integral

```
∮ E⃗ · dA⃗ = Q_enc / ε₀
```

Donde:
- ∮: Integral sobre una superficie cerrada
- E⃗: Campo eléctrico
- dA⃗: Elemento diferencial de área (vector normal a la superficie)
- Q_enc: Carga total encerrada
- ε₀: Permitividad del vacío (ε₀ ≈ 8.85 × 10⁻¹² C²/N·m²)

## Forma Diferencial

```
∇ · E⃗ = ρ / ε₀
```

Donde:
- ∇ · E⃗: Divergencia del campo eléctrico
- ρ: Densidad de carga volumétrica

## Aplicaciones

### 1. Campo de una esfera uniformemente cargada

Para r > R (fuera de la esfera):
```
E = k * Q / r²
```

Para r < R (dentro de la esfera):
```
E = k * Q * r / R³
```

### 2. Campo de un cilindro infinito

```
E = λ / (2πε₀r)
```

Donde λ es la densidad lineal de carga.

### 3. Campo de un plano infinito

```
E = σ / (2ε₀)
```

Donde σ es la densidad superficial de carga.

## Superficie Gaussiana

Para aplicar la Ley de Gauss eficientemente, se elige una superficie que:
- Tenga simetría con la distribución de carga
- Permita que E⃗ sea constante o cero en partes de la superficie
- Tenga E⃗ perpendicular o paralelo a dA⃗

## Ejemplo

Calcular el campo eléctrico a 2 m de un plano infinito con σ = 5 × 10⁻⁶ C/m²:

```
E = σ / (2ε₀)
E = (5 × 10⁻⁶) / (2 × 8.85 × 10⁻¹²)
E = 2.82 × 10⁵ N/C
```

Nota: El campo es independiente de la distancia al plano.
