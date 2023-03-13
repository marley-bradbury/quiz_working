# Question 1
## Finding discharge $q$ from flow velocity $v$ and water depth $y$
$q$ = $vy$

## Finding Critical Depth $y_c$
$g$ = $9.81\frac{m}{s^2}$

$y_c$ = $\frac{y_c^2}{g}^\frac 13$

# Question 2
## Testing the Critical State with the Froude Number $Fr$
$g$ = $9.81\frac{m}{s^2}$

$Fr$ = $\sqrt\frac{q^2}{gy^3}$

Check that $Fr$ > $1$

## Calculate Virtual Head at Start from discharge $q$ and intial depth $y_1$
$E_1$ = $y_1+\frac{q^2}{2gy_1^3}$

## Finding Critical Depth $y_c$
$y_c$ = $\frac{y_c^2}{g}^\frac 13$

## Calculate Critical Head after Step
$E_c$ = $y_c+\frac{q^2}{2gy_c^3}$

## Calculate Step Height $\delta z$
$\delta z$ = $E_c$ - $E_1$

# Question 3
## Integrating $\frac{\delta^2u}{\delta y^2}$

$\frac{\delta^2u}{\delta y^2}$ = $\frac{1}{\mu}\frac{\delta P}{\delta x}$

$\frac{\delta u}{\delta y}$ = $\frac{y}{\mu}\frac{\delta P}{\delta x}+C_1$

$u$ = $\frac{y^2}{2\mu}\frac{\delta P}{\delta x}+yC_1+C_2$

## Conditions

when $y$ = $0$ , $u$ = $C_2$ $\leftarrow$ speed of bottom plate due to no slip condition

when $y$ = $h$ , $u$ = $0$

$0$ = $\frac{y^2}{2\mu}\frac{\delta P}{\delta x}+yC_1+C_2$

$C_1$ = $-\frac{h}{2\mu}\frac{\delta P}{\delta x}-\frac{C_2}{h}$

## Substituting $C_1$

$u$ = $\frac{y^2}{2\mu}\frac{\delta P}{\delta x}+yC_1+C_2$

$u$ = $\frac{y^2}{2\mu}\frac{\delta P}{\delta x}-\frac{hy}{2\mu}\frac{\delta P}{\delta x}-\frac{C_2y}{h}+C_2$

## Integrating Across the Flow

$\int^h_0u\delta y$ = $q$

$q$ = $[\frac{y^3}{6\mu}\frac{\delta P}{\delta x}-\frac{y^2h}{4\mu}\frac{\delta P}{\delta x}-\frac{C_2y^2}{2h}+yC_2]^h_0$

$q$ = $\frac{h^3}{6\mu}\frac{\delta P}{\delta x}-\frac{h^3}{4\mu}\frac{\delta P}{\delta x}-\frac{C_2h^2}{2h}+hC_2$

$q$ = $\frac{\delta P}{\delta x}(\frac{h^3}{6\mu}-\frac{h^3}{4\mu})+\frac{C_2h}{2}$

$q - \frac{C_2h}{2}$ = $-\frac{\delta P}{\delta x}\frac{h^3}{12\mu}$

$\frac{\delta P}{\delta x}$ = $-\frac{12\mu(q-\frac{C_2h}{2})}{h^3}$ $\leftarrow$ in $Pa$, to convert to $kPa$ flip negative sign and divide the final answer by 1000
