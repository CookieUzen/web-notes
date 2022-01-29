---
title: Measurements and Uncertainties
description: Unit 1 of Physics
---
> Unit 1: Measurements and Uncertainties

# Measurements in Physics

## Physical Quantities and Units

### Physical Quantities

All measurements are made of the *seven* basic quantities, or `SI Base Units`.
The table shows their quantities and their units.

|      Quantity       |    SI Unit    | Symbol |
| :-----------------: | :-----------: | :----: |
|        Time         |    second     |  $s$   |
|   Distance/Length   | meters/metres |  $m$   |
|        Mass         |   kilograms   |  $kg$  |
|       Current       |    amperes    |  $A$   |
|     Temperature     |    kelvin     |  $k$   |
| Amount of Substance |     mole      | $mol$  |
| Luminous Intensity  |    candela    |  $cd$  |

### Derived Quantities

These quantities are derived from and `Physical Quantities`, AKA `SI Derived Quantities`. 
The table below show some common derived quantities (you do not need to remember this).

| Quantities                                    |         Symbol         | SI Derivation                            |         SI Unit          |            Commonly Used Form             |
| :-------------------------------------------- | :--------------------: | :--------------------------------------- | :----------------------: | :---------------------------------------: |
| Plane Angle                                   |      Rad/$\theta$      | $\frac{m}{m}$                            | Radians ($Rad$/$\theta$) |  $1Rad = 1^{\circ} \cdot \frac{π}{180}$   |
| Velocity                                      |          $v$           | $m \cdot s^{-1}$                         |                          |                                           |
| Acceleration                                  |          $a$           | $m \cdot s^{-2}$                         |                          |                                           |
| (Gravitational Field Strength)                |          $g$           | $N \cdot kg^{-1}$                        |                          |             $m \cdot s^{-2}$              |
| Force / Weight                                |          $F$           | $kg \cdot m \cdot s^{-2}$                |       Newton ($N$)       |                                           |
| Energy \ Work                                 | $E$ \ $W$ \ $Q (heat)$ | $kg \cdot m^{2} \cdot s^{-2}$            |       Joule ($J$)        |             $J \cdot s^{-1}$              |
| Power                                         |          $P$           | $kg⋅m^{2}⋅s^{−3}$                        |        Watt ($W$)        |                                           |
| Momentum                                      |          $p$           | $kg \cdot m \cdot s^{-1}$                |                          |                                           |
| Pressure                                      |          $p$           | $kg \cdot m^{-1} \cdot s^{-2}  $         |      Pascal ($Pa$)       |             $N \cdot m^{-2} $             |
| Frequency                                     |          $f$           | $s^{-1}$                                 |       Hertz ($Hz$)       | $f = \frac{1}{T}$ where $T$ Is the period |
| Electrical Resistance                         |          $R$           | $kg \cdot m^2 \cdot s^{-3} \cdot A^{-2}$ |      Ohm ($\Omega$)      |             $V \cdot A^{-1}$              |
| Electric Charge                               |          $C$           | $A \cdot s$                              |      Coulomb ($C$)       |                                           |
| Electric Potential Difference (Voltage) \ EMF |    $V$ \ $\epsilon$    | $kg⋅m^{2}⋅s^{-3}⋅A^{−1}$                 |       Volts ($V$)        |      $\frac{W}{A}$ or $\frac{J}{s}$       |
| Capacitance                                   |          $F$           | $kg^{−1}⋅m^{−2}⋅s^{4}⋅A^{2}$             |       Farad ($F$)        |               $\frac{C}{V}$               |
| Magnetic Flux                                 |          $Wb$          | $kg⋅m^{2}⋅s^{−2}⋅A^{−1}$                 |       Weber ($Wb$)       |                $V \cdot s$                |
| Magnetic Flux Density/Field Strength          |          $T$           | $kg⋅s^{−2}⋅A^{−1}$                       |       Tesla ($T$)        |            $\frac{Wb}{m^{2}}$             |
| Temperature                                   |      $\theta$/$T$      | $K$                                      |  Celcius ($^{\circ}C$)   |     $-273.15^{\circ}C = 1 ^{\circ}K$      |
| Radioactivity ($\frac{decays}{time}$)         |          $Bq$          | $s^{-1}$                                 |     Becquerel ($Bq$)     |                                           |


## Physical Quantities and Calculations

When plugging in quantities into an equation, **always be aware of unit conversion.**
A method to avoid calculation error with unit conversion is to treat the units as mathematical entities.
This is called quantity calculus.

For example:

$$
\begin{aligned}
	F &= ma \\
	  &= 500 g \cdot 10 ms^{-1} \\
	  &= 500 g \cdot \frac{1 kg}{1000 g} \cdot 10 km \cdot \frac{1000 m}{1 km} \cdot h^{-1} \cdot \frac{h}{60 \cdot 60 s} \\
	  &= 0.5 kg \cdot \frac{10^{4}}{3600} \cdot ms^{-1} \\
	  &= 1.39 N \\
\end{aligned}
$$

## Scientific Notation

`Scientific Notation` leaves only one digit, and concatenate the rest as powers of ten.
For example: $4. 2 \cdot 10^4$.
The decimal places indicate how many digits of `significant figures` is the number accurate to.

### SI Prefix

A common list of `SI Prefixes` can be found below:

 Factor    | Name    | Symbol   | English     | Factor       | Name    | Symbol   | English
:---------:|:-------:|:--------:|:-----------:|:------------:|:-------:|:--------:|:-------------
 $10^1$    | deca    | $da$     | Ten         | $10^{-1}$    | deci    | $d$      | Tenth
 $10^2$    | hecto   | $h$      | Hundred     | $10^{-2}$    | centi   | $c$      | Hundredth
 $10^3$    | kilo    | $k$      | Thousand    | $10^{-3}$    | milli   | $m$      | Thousandth
 $10^6$    | mega    | $M$      | Million     | $10^{-6}$    | micro   | $\mu$    | Millionth
 $10^9$    | giga    | $G$      | Billion     | $10^{-9}$    | nano    | $n$      | Billionth
 $10^{12}$ | tera    | $T$      | Trillion    | $10^{-12}$   | pico    | $p$      | Trillionth
 $10^{15}$ | peta    | $P$      | Quadrillion | $10^{-15}$   | femto   | $f$      | Quadrillionth
 $10^{18}$ | exa     | $E$      | Quintillion | $10^{-18}$   | atto    | $a$      | Quintillionth
 $10^{21}$ | zetta   | $Z$      | Sextillion  | $10^{-21}$   | zepto   | $z$      | Sextillionth
 $10^{24}$ | yotta   | $Y$      | Septillion  | $10^{-24}$   | yocto   | $y$      | Septillionth

These values are very important during calculations, and thus it would be a good idea to remember prefixes from `giga` to `pico`, for example "giga-watts" ($GW$), or "pico-farads" ($pF$). A good way to start is to remember that from `deca` up to `kilo`, we have [$10^1 - 10^3$]. After that we start jumping by 3 zeroes, or $10^{x+3}$ [^1] . The same method works if we go down from `deci.` Except after the third sub-zero value `milli`, we jump by 3 decimal places instead, or **$10^{-x-3}$**. Keep in mind that one has no special name and is equal to $10^0$.



### Significant Figures

Significant Figures determines the amount of digits that is accurate in a certain calculation.
To find the significant figure of a number, we use the following rules: 

- Left most *non-zero* digit is the `most significant digit` 
- If there is no decimal points, the rightmost digit *non zero* digit is the `least significant digit`
- If there is a decimal point, the rightmost digit is the `least significant digit`
- All digits between the `most significant digit` and the `least significant digit` is significant.

When rounding, round up with numbers above and including 5, and down with numbers below 5.

{% include alert.html type="warning" title="Be aware" content="When doing a calculation, always round to the smallest significant figure." %}

[^1]: Why? The most common everyday values are in the *tens* (10s), *hundreds* (100s), or *thousands* (100s), so we leave them be. After that, values are just multiples of these (*i.e. ten-thousand*), or of values starting from *one million* ($10^6$), such as "*one hundred million,*" or "*one hundred billion*." Notice how we don't have specific names like "*million*" and "billion" for values like "*one-hundred-thousand*."

# Uncertainties and Error

In physics, there will always be issues with uncertainty and errors in quantitative data.
It is important to take these into account when doing calculations with the data.

## Quantifying Uncertainties

An uncertainty of $2mm$ means that the actual value of the measurement may be $2mm$ higher or lower than the measured value.
The symbol for uncertainty is $\Delta$, where $\Delta l$ is the uncertainty of $l$.
Uncertainty can be written like this: $10mm \pm 1mm$.

Uncertainty is either provided in question or calculated from the measurement device (in an experiment).
An analog measuring device has an uncertainty of $\frac{x}{2}$, where $x$ is the smallest unit of measurement the measuring device can measure.
A digital measuring device has an uncertainty of $x$.
This is because a digital device truncates (always rounds down) the smallest digit.

Percent uncertainty is calculated as $\frac{\Delta x}{x}$, where $x$ is the resulted measurement.
Percent uncertainty is used in calculating multi variable uncertainty.

## Combining Uncertainties

Most equations have more than one variable.
In an equation with many variables, there are also many uncertainty.
When adding two variable, the uncertainty of the variables are added.

$$
\begin{aligned}
	y &= a \pm b \\
	\Delta y &= \Delta a + \Delta b
\end{aligned}
$$

When multiplying two variable, the percentage uncertainty of the variables are added.

$$
\begin{aligned}
	y &= \frac{ab}{c} \\
	\frac{\Delta y}{y} &= \frac{\Delta a}{a} + \frac{\Delta b}{b} + \frac{\Delta c}{c}
\end{aligned}
$$

## Displaying Uncertainties

When graphing data, uncertainty should be displayed.
Error bar are added to each data point to display uncertainty.
With the y error bar representing the dependent (y) variable uncertainty, and x error bar representing the independent (x) variable uncertainty.
When calculating a line of best fit, ensure that the line passes through the error bars of every point.

> TODO: Graph here

## Displaying Data

When graphing data, the following information should be shown:
- Title (X Versus Y)
- Caption (Fig 1: graph of X versus Y)
- For x and y variables
	* variable
	* unit
	* uncertainty
	* intercepts
	* error bars
- For curve fit
	* Fits through error bar
	* Equation

> TODO: Graph here

# Vectors and Scalars

Physical quantities can be grouped into two different categories, scalars and vectors.

## Define Scalars and Vectors

**Scalars** are units of measurement that only describe the magnitude of an object.
For example, distance is a scalar.
If a line is drawn between two points, the distance is the length of said line (for example, *10 meters*).

**Vectors** are units of measurement describing both magnitude and a direction.
For example, displacement is a vector. 
Using the same line, displacement is the vector representation of the line.
It measures both the length of the line and the angle of the line to a reference point (for example, 10 meters at a bearing of 30 degrees).

Below is a list of common scalars and vectors:

| Scalars                          | Vectors                                  |
| -------------------------------- | ---------------------------------------- |
| Speed                            | Velocity (Speed counterpart) [^2]        |
| Distance                         | Displacement (Distance counterpart) [^2] |
| Energy (of any kind) \ Work      | Acceleration                             |
| Power                            | Force                                    |
| Temperature                      | Momentum                                 |
| Pressure                         | Impulse                                  |
| Electric/Gravitational Potential | Electric/Gravitational Field Strength    |
| Mass                             |                                          |
| Volume \ Density                 |                                          |

[^2]: A vector counterpart cannot be derived from a scalar, for example, you cannot obtain average velocity from distance.

## Working with Vectors

We tend to break vectors into the x direction and the y direction.
This way, we can represent the `vectors` with positive and negative values.
For example, a force applied on a object upwards can be indicated with a positive sign, and a downwards force represented by a negative sign.

To separate the x and y direction, we usually use trig function ($\sin$ $\cos$ $\tan$).
A free body diagram is often used to separate the forces.

> TODO: Free body diagram here

# Footnotes
