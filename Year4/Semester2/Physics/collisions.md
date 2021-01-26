# Study of Collisions: Conservation of Momentum and Energy


## Procedure

Note: a slightly modified procedure was utilized as there were technical difficulties with Logger Pro which should be fixed soon.

![selfie](images/selfie.gif)

1. Two channels of the same length were constructed.
2. Each channel was inclined to the same angle, and made to connect to each other at the lowest point.
3. Two billiard balls of similar mass were place in the channels, one at the low point and one a measured distance up one of the inclined channels.
4. The elevated billiard ball was released, and the distance the balls traveled up the opposite slope was measured.


## Data

Mass of billiard balls: 0.17890 kg
Initial angle of channels: 4°
Initial distance of primary ball: 0.500 m
Final distance of primary ball: 0.060 m
Final distance of secondary ball: 0.123 m


## Analysis

The acceleration due to gravity is calculated as

```
a = sin(theta) * 9.8 m/s^s
a = sin(4°) * 9.8 m/s^s
a = 0.684 m/s^2
```

The velocity of the primary ball at impact is calculated to be

```
v^2 = v^2_0 + 2a(x - x_0)
v = sqrt(2 * (0.684 m/s^2) * 0.500 m)
v = 0.827 m/s
```

which is then used to find the momentum of the primary ball:

```
p = mv
p = 0.17890 kg * 0.827 m/s
p = 0.1479 kg m/s
```

The final momentums of the balls can be solved for in the same fashion:

```
v^2 = v^2_0 + 2a(x - x_0)
v = sqrt(2 * (0.684 m/s^2) * 0.060 m)
v = 0.2865 m/s

p_primary = mv
p_primary = 0.17890 kg * 0.2865 m/s
p_primary = 0.051 kg m/s

v^2 = v^2_0 + 2a(x - x_0)
v = sqrt(2 * (0.684 m/s^2) * 0.123 m)
v = 0.4102 m/s

p_secondary = mv
p_secondary = 0.17890 kg * 0.4102 m/s
p_secondary = 0.073 kg m/s
```

Then by comparing the initial and final momentums, we see that

```
0.1479 kg m/s = 0.051 kg m/s + 0.073 kg m/s
0.1479 kg m/s != 0.124 kg m/s
```

where the final momentum is less than the initial momentum. This is likely due to the rolling friction of the balls against the cardboard channels, an amount of elastic friction within the balls during collision, and bumps in the track which absorbed some momentum.
