# Moment of Inertia Lab

Diagram of the components:
```
┌───────┐
│ C-B-D │
│     |	│
│     A │
└───────┘
```

| Part | Mass (g) | Length (cm) | OD (cm) | ID (cm) |
|:----:|:--------:|:-----------:|:-------:|:-------:|
|   A  |  133.08  |     55.5    |   2.15  |   1.5   |
|   B  |   72.79  |     30.5    |   2.15  |   1.5   |
|   C  |   12.77  |     2.5     |   2.81  |   2.15  |
|   D  |   33.37  |     7.2     |   2.81  |   2.15  |


### 1. Calculate the moment of inertia of the apparatus using measurements of the length and mass of each component. Show and label each step of the calculation.

```
1/12 * (2(0.1277 kg + 0.7279 kg) + 0.3337 kg) * (2(0.025 m + 0.305 m) + 0.072 m)^2
0.09129 kg m^2
```


### 2. Perform two experiments using different hanging masses, record Ө, t, m, Δy, and r in a data table format.

| mass (g) | time (s) |
|:--------:|:--------:|
|   200.   |   8.92   |
|   500.   |   5.20   |


### 3. Draw a free body diagram showing and labeling all forces and torques.

```
	┌───────────────────────┐
	│S						│
	│	╠══╦══╣				│
	│	   ║				│
	│	   ║				│
	│	   ║─────┐			│
	│	   ╩     │  │		│
	│	    	 │  │ mg	│
	│			 │	V		│
	│			 ▓			│
	│						│
	└───────────────────────┘
	┌───────────────────────┐
	│T						│
	│     .-x^x-.	Ө = 90°	│
	│	 x       x			│
	│	|         |			│
	│   X	 O────X─┐		│
	│   |         |Ө│		│
	│    x       x  │  │	│
	│     ~-x_x-~   │  │ τ	│
	│      			│  V	│	
	│      			│		│
	│						│
	└───────────────────────┘
	       
```    


### 4. Write the two Newton’s second law equations derived from the free body diagram.

```
F = mg
```
```
F = 0.200 kg * 9.8 m/s^2
F = 1.96 N

τ = r⊥F
τ = 0.0215 m * 1.96 N
τ = 0.04124 m*N
```
```
F = 0.500 kg * 9.8 m/s^2
F = 4.9 N

τ = r⊥F
τ = 0.0215 m * 4.9 N
τ = 0.10535 m*N
```


### 5. Use the experimental data to calculate I for the apparatus. Show each mathematical step. Provide a caption describing the purpose of each step.

The angular acceleration was first found by multiplying the tangential acceleration by the radius
```
α = a_tan / r
α = 8.92 rad/s^2 * 0.0215 m
α = 0.192 rad/s^2
```

And the inertia was found by solving the following equation
```
Στ = Ια
```
```
0.04124 m*N = Ι * 0.192 rad/s^2
Ι = 0.04124 m*N / 0.192 rad/s^2
Ι = 0.215
```


### 6. Compare the calculated I with the experimentally determined I. Analyze sources of error associated with each method used to determine I.
The calculated Ι was far smaller than the experimentally found Ι, which was almost certainly due to errors in the experimental calculations.
