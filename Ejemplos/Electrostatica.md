# Ejemplos de Electrostática

## Ejemplo 1: Fuerza entre Cargas

**Enunciado**: Dos cargas puntuales q₁ = +3 μC y q₂ = -5 μC están separadas por una distancia de 20 cm en el vacío. Calcular la fuerza eléctrica entre ellas.

**Datos**:
- q₁ = 3 × 10⁻⁶ C
- q₂ = -5 × 10⁻⁶ C
- r = 0.2 m
- k = 8.99 × 10⁹ N·m²/C²

**Solución**:

Usando la Ley de Coulomb:

```
F = k * |q₁ * q₂| / r²
F = (8.99 × 10⁹) * (3 × 10⁻⁶) * (5 × 10⁻⁶) / (0.2)²
F = (8.99 × 10⁹) * (15 × 10⁻¹²) / 0.04
F = 3.37 N
```

**Resultado**: F = 3.37 N (atractiva, ya que las cargas tienen signos opuestos)

---

## Ejemplo 2: Campo Eléctrico de un Dipolo

**Enunciado**: Un dipolo eléctrico consiste en dos cargas ±q = ±10 nC separadas por d = 2 mm. Calcular el campo eléctrico en el eje del dipolo a una distancia z = 10 cm del centro.

**Datos**:
- q = 10 × 10⁻⁹ C
- d = 2 × 10⁻³ m
- z = 0.1 m
- k = 8.99 × 10⁹ N·m²/C²

**Solución**:

Para z >> d, el campo en el eje del dipolo:

```
E = 2k * p / z³
```

Momento dipolar:
```
p = q * d = (10 × 10⁻⁹) * (2 × 10⁻³) = 2 × 10⁻¹¹ C·m
```

Campo:
```
E = 2 * (8.99 × 10⁹) * (2 × 10⁻¹¹) / (0.1)³
E = 3.596 × 10⁻¹ / 0.001
E = 359.6 N/C
```

**Resultado**: E = 360 N/C (aproximadamente)

---

## Ejemplo 3: Capacitor de Placas Paralelas

**Enunciado**: Un capacitor de placas paralelas tiene placas de área A = 500 cm² separadas por d = 2 mm. Se conecta a una batería de 12 V. Calcular:
a) La capacitancia
b) La carga almacenada
c) El campo eléctrico entre las placas
d) La energía almacenada

**Datos**:
- A = 500 × 10⁻⁴ m² = 0.05 m²
- d = 2 × 10⁻³ m
- V = 12 V
- ε₀ = 8.85 × 10⁻¹² F/m

**Solución**:

a) Capacitancia:
```
C = ε₀ * A / d
C = (8.85 × 10⁻¹²) * 0.05 / (2 × 10⁻³)
C = 2.21 × 10⁻¹⁰ F = 221 pF
```

b) Carga:
```
Q = C * V
Q = (2.21 × 10⁻¹⁰) * 12
Q = 2.65 × 10⁻⁹ C = 2.65 nC
```

c) Campo eléctrico:
```
E = V / d
E = 12 / (2 × 10⁻³)
E = 6000 V/m = 6 kV/m
```

d) Energía:
```
U = (1/2) * C * V²
U = (1/2) * (2.21 × 10⁻¹⁰) * 144
U = 1.59 × 10⁻⁸ J = 15.9 nJ
```

**Resultados**:
- C = 221 pF
- Q = 2.65 nC
- E = 6 kV/m
- U = 15.9 nJ

---

## Ejemplo 4: Esfera Conductora Cargada

**Enunciado**: Una esfera conductora de radio R = 10 cm tiene una carga total Q = 50 μC. Calcular el campo eléctrico y el potencial a:
a) r = 5 cm (dentro)
b) r = 10 cm (superficie)
c) r = 20 cm (fuera)

**Datos**:
- R = 0.1 m
- Q = 50 × 10⁻⁶ C
- k = 8.99 × 10⁹ N·m²/C²

**Solución**:

a) Dentro (r = 0.05 m < R):
```
E_in = 0 (conductor)
V_in = k * Q / R = (8.99 × 10⁹) * (50 × 10⁻⁶) / 0.1 = 4.495 × 10⁶ V
```

b) Superficie (r = R = 0.1 m):
```
E_surf = k * Q / R² = (8.99 × 10⁹) * (50 × 10⁻⁶) / (0.1)²
E_surf = 4.495 × 10⁷ V/m
V_surf = 4.495 × 10⁶ V
```

c) Fuera (r = 0.2 m > R):
```
E_out = k * Q / r² = (8.99 × 10⁹) * (50 × 10⁻⁶) / (0.2)²
E_out = 1.124 × 10⁷ V/m
V_out = k * Q / r = (8.99 × 10⁹) * (50 × 10⁻⁶) / 0.2 = 2.248 × 10⁶ V
```

**Resultados**:
- Interior: E = 0, V = 4.495 MV
- Superficie: E = 44.95 MV/m, V = 4.495 MV
- Exterior: E = 11.24 MV/m, V = 2.248 MV
