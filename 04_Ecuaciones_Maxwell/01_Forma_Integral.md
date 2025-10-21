# Ecuaciones de Maxwell - Forma Integral

## Las Cuatro Ecuaciones

### 1. Ley de Gauss (Eléctrica)

```
∮ E⃗ · dA⃗ = Q_enc / ε₀
```

**Significado**: El flujo eléctrico a través de una superficie cerrada es proporcional a la carga encerrada.

- E⃗: Campo eléctrico
- dA⃗: Elemento de área (vector normal)
- Q_enc: Carga total encerrada
- ε₀: Permitividad del vacío

**Consecuencias**:
- Las cargas eléctricas son fuentes del campo eléctrico
- Las líneas de campo eléctrico comienzan y terminan en cargas

### 2. Ley de Gauss (Magnética)

```
∮ B⃗ · dA⃗ = 0
```

**Significado**: El flujo magnético neto a través de cualquier superficie cerrada es cero.

- B⃗: Campo magnético
- 0: No hay monopolos magnéticos

**Consecuencias**:
- No existen monopolos magnéticos aislados
- Las líneas de campo magnético son cerradas
- Siempre hay polo norte y sur juntos

### 3. Ley de Faraday-Lenz

```
∮ E⃗ · dl⃗ = -dΦ_B/dt
```

**Significado**: Un campo magnético variable en el tiempo induce un campo eléctrico.

- dl⃗: Elemento de longitud
- Φ_B = ∫ B⃗ · dA⃗: Flujo magnético
- El signo negativo es la Ley de Lenz

**Consecuencias**:
- Base de generadores y transformadores
- Campo eléctrico inducido es no conservativo
- Inducción electromagnética

### 4. Ley de Ampère-Maxwell

```
∮ B⃗ · dl⃗ = μ₀ * (I_enc + ε₀ * dΦ_E/dt)
```

**Significado**: Corrientes y campos eléctricos variables generan campos magnéticos.

- I_enc: Corriente encerrada
- Φ_E = ∫ E⃗ · dA⃗: Flujo eléctrico
- μ₀: Permeabilidad del vacío
- ε₀ * dΦ_E/dt: Corriente de desplazamiento

**Consecuencias**:
- Corrientes eléctricas generan campos magnéticos
- Campos eléctricos variables generan campos magnéticos
- Permite ondas electromagnéticas

## Forma en Medios Materiales

### Con campos D⃗ y H⃗

```
∮ D⃗ · dA⃗ = Q_free_enc

∮ B⃗ · dA⃗ = 0

∮ E⃗ · dl⃗ = -dΦ_B/dt

∮ H⃗ · dl⃗ = I_free_enc + d/dt ∫ D⃗ · dA⃗
```

Donde:
- D⃗ = ε₀*E⃗ + P⃗: Desplazamiento eléctrico
- H⃗ = B⃗/μ₀ - M⃗: Campo magnético
- P⃗: Polarización
- M⃗: Magnetización

## Relaciones Constitutivas

En medios lineales, homogéneos e isótropos:

```
D⃗ = ε * E⃗
B⃗ = μ * H⃗
J⃗ = σ * E⃗
```

Donde:
- ε: Permitividad del medio
- μ: Permeabilidad del medio
- σ: Conductividad

## Ecuación de Continuidad

Derivada de las ecuaciones de Maxwell:

```
∇ · J⃗ + ∂ρ/∂t = 0
```

Conservación de la carga eléctrica.

## Resumen Visual

```
Ley de Gauss (E):     Cargas → Campo E
Ley de Gauss (B):     No monopolos
Ley de Faraday:       ∂B/∂t → Campo E
Ley de Ampère-Maxwell: Corrientes + ∂E/∂t → Campo B
```

## Aplicaciones

1. **Análisis de campos estáticos**: Electrostática y magnetostática
2. **Circuitos**: Inductancia, capacitancia
3. **Ondas**: Radio, luz, microondas
4. **Guías de onda**: Fibra óptica, cables coaxiales
5. **Antenas**: Transmisión y recepción
