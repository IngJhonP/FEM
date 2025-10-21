# Ley de Faraday

## Definición

La Ley de Faraday establece que un campo magnético variable en el tiempo induce una fuerza electromotriz (FEM) en un circuito.

## Forma Integral

```
ε = -dΦ_B/dt
```

Donde:
- ε: Fuerza electromotriz inducida (V)
- Φ_B: Flujo magnético (Wb, weber)
- El signo negativo indica la Ley de Lenz

## Flujo Magnético

```
Φ_B = ∫ B⃗ · dA⃗
```

Para campo uniforme y superficie plana:
```
Φ_B = B * A * cos(θ)
```

## Ley de Faraday con N Espiras

```
ε = -N * dΦ_B/dt
```

## Forma Diferencial

```
∇ × E⃗ = -∂B⃗/∂t
```

El rotacional del campo eléctrico es igual a la tasa de cambio negativa del campo magnético.

## Ley de Lenz

La corriente inducida crea un campo magnético que se opone al cambio del flujo magnético que la produce.

Regla práctica:
1. Determinar si Φ_B aumenta o disminuye
2. La corriente inducida crea B_ind que se opone a este cambio
3. Usar regla de la mano derecha para encontrar dirección de I

## Causas de la FEM Inducida

1. **Cambio en B**: Campo magnético variable
2. **Cambio en A**: Área del circuito variable
3. **Cambio en θ**: Orientación del circuito variable
4. **Combinación**: Cualquier combinación de los anteriores

## FEM de Movimiento

Para un conductor moviéndose en un campo magnético:

```
ε = B * L * v
```

Donde:
- L: Longitud del conductor
- v: Velocidad perpendicular a B

## Aplicaciones

1. **Generadores eléctricos**: Conversión de energía mecánica a eléctrica
2. **Transformadores**: Cambio de voltaje AC
3. **Tarjetas magnéticas**: Lectura de datos
4. **Cocinas de inducción**: Calentamiento por corrientes inducidas
5. **Frenos electromagnéticos**: Disipación de energía

## Ejemplo 1

Espira circular (r = 10 cm) en B perpendicular que varía de 0 a 0.5 T en 2 s:

```
Φ_i = 0
Φ_f = 0.5 * π * (0.1)² = 1.57 × 10⁻² Wb
ε = -(1.57 × 10⁻² - 0) / 2 = -7.85 × 10⁻³ V
|ε| = 7.85 mV
```

## Ejemplo 2

Varilla de L = 0.5 m moviéndose a v = 10 m/s en B = 0.8 T:

```
ε = 0.8 * 0.5 * 10 = 4 V
```
