---
title: Mechanics
description: Unit 2 of Physics
---
> Unit 2: Mechanics

# Motion

## Basic Concept of Motion

`Distance` is a measurement of how far an object have traveled. Distance is a scaler. The vector counterpart of distance, `displacement` ($s$) measures the distance from the start to the end of a motion. It also includes the measurement of direction. The SI Unit of displacement is `meters`. If a object travels in a circle, the distance is the circumference of the circle, but the displacement *would be zero*.

`Speed` denotes the rate of change of distance. Speed is a vector. `Velocity` measures both rate of change of displacement and change in direction. A change in *velocity* might not be a change in `speed`.

`Acceleration` is the change in velocity. Acceleration is a vector. There is no scaler equivalent of acceleration. Acceleration also measures the change it direction. Thus, in circular motion, an object is *always* accelerating.

### Average Versus Instantaneous

We commonly measure rate of change with respect to time. For example, to find the velocity of a bike, we measure the displacement over a period of 5 seconds. This is the average velocity.

Average velocity accounts for all the changes in velocity during the time period of measurement. Instantaneous velocity is the velocity of the bike at the exact time. This instantaneous velocity may not be exactly the same as the average velocity.

# Graphing Motion

Often times, motion of an object can be graphed. These graphs gives us a lot of information.

## Position Time Graph

![A position time graph of a bike over time](./figures/position-time.jpg)

The change in Y values is the displacement. The change in X value is the change in time. The gradient of the line is the velocity.

![A curved position time graph](./figures/position-time-curve.jpg)

Note, if the curve is non-linear, the average velocity would be the average slope. The instantaneous velocity is the slope of the tangent line.

## Velocity Time graph

![image](./figures/velocity-time.jpg)

The Y intercept of the graph is the initial velocity. The change in Y is the change in velocity. The change in X is the change in time. The gradient of the graph is the acceleration (use tangent line if we need the instantaneous acceleration). The area under the curve is the
displacement.

## Acceleration Time graph

![Acceleration Time graph](./figures/acceleration-time.jpg)

The area under the curve is the change in velocity.

## Free fall air resistance

![Velocity time graph of an object in free fall](./figures/velocity-freefall.jpg)

# SUVAT

The SUVAT equations describe the relationship acceleration, displacement, velocity, and time.

$$\begin{aligned}
    v = u + at \\
    s = ut + \frac{1}{2}at^2 \\
    v^2 = u^2 + 2as \\
    s = (\frac{v+u}{2})t\end{aligned}$$

$v$ final velocity, $u$ is initial velocity. $t$ is time. $a$ is acceleration.

# Projectile Motion

In a projectile motion, a object is accelerated in a certain direction. During flight, no additional force acts on said object. Projectile motion ends when the object impact the ground.

When analyzing projectile motion, split the variables into horizontal and vertical components. After the initial force, the horizontal acceleration is zero (horizontal velocity maintains constant), while the vertical acceleration remains constant ($g$, acceleration due to gravity). To find the net force/acceleration/velocity, we can use Pythagorean Theorem to combine the $x$ and $y$ components.

$$
\begin{aligned}
    V_{net} = \sqrt{V_{vertical}^2 + {V_{horizontal}}^2}
\end{aligned}
$$

# Forces

## Newton's Laws of Motion

1.  An object continues to remain stationary or to move at a constant
    velocity unless an external force acts on it.
2.  $F=ma$, $f = \frac{\Delta mv}{t}$, impulse is equal to change in
    momentum.
3.  Every action has an equal and opposite reaction.

## Free-Body Diagram

Free body diagrams are often used to show the forces acting on an object. Forces are drawn as arrows, with the direction of the arrow representing the direction of the force. And the length of the arrow representing magnitude. All forces need to have clear labels.

When drawing a free-body diagram, it is easier to represent the mass as a dot. All arrows start from the dot.

Note, if an object falls a long period of time, it may hit terminal velocity. This is when air resistance increases a velocity increases, and eventually counteracts the force due to gravity.

## Translational Equilibrium

Net force is the combination of all the forces acting on a body. Adding forces as vectors requires taking in account of direction. An object will accelerate according to the net force. If the net force of an object is zero, then the object is in translational equilibrium. This means the object is moving at constant velocity, or stationary.

# Friction

Solid friction is a type of friction that occurs where two surfaces are in contact. There is two types of solid friction, static friction and dynamic friction.

## Static Friction

Static friction occurs when there is no movement between two objects. Static friction increases with the force acting on an object until hitting a certain point. After reaching the point, the object begins to accelerate, and friction transfers to dynamic friction.

Static friction can be represented by: $$F_t \le \mu_s R$$

## Dynamic Friction

Dynamic friction happens when an object is moving. Dynamic friction is modeled by this equation: $$F_t = {\mu}_d R$$ Where $F_t$ is the force due to friction. $\mu$ is the coefficient of friction. $R$ is the normal force acting on the object.

# Work, Energy, and Power

Energy is stored in many forms. Below is a list of some common ways of
storing energy.

-   Kinetic
-   Gravitational Potential
-   Electric/Magnetic
-   Chemical
-   Nuclear
-   Elastic
-   Thermal
-   Mass
-   Vibration
-   Light

Energy is often transformed into many different forms. One way to describe energy is through work.

## Work

Work ($W$), has the SI Unit of Joules ($J$). The definition of work is the amount of energy required to move a mass of $1 kg$ over a distance of $1m$. The equation for work is: $$W = F \cdot s$$ Where $s$ is displacement, and $F$ is force.

Note, if the force is exerted at an angle to the direction of displacement, we have to use trig ratios to find the component of the force that is parallel to the direction of displacement. Often times, work is multiplied by $\cos\theta$ (where $\theta$ is the angle between the force and the direction of motion) in order to account the difference in angles.

Sometimes, there is a resistive force done against the direction of travel. In this case, there would be work done by the force and work done by the resistive force.

## Force Distance Graph

In a force distance graph, area under the curve is the work done.

## Power

Power ($P$) is defined as the rate of doing work. The SI Unit of power is watts. $$P = \frac{W}{t}$$ In which $t$ represents time.

## Kinetic Energy

Kinetic Energy (KE) is defined as the energy objects have due to its motion. The SI Unit of kinetic energy is Joules.

$$KE = \frac{1}{2}mv^2$$

## Gravitational Potential Energy

Gravitational Energy (GPE) is defined as the energy an object gains due to its height. $$GPE = mgh$$ In which, $m$ is mass, $g$ is the acceleration due to gravity, and $h$ is the height from a reference point.

$g$ is a constant. IB defines the acceleration due to gravitational on Earth's surface as $9.8 m\cdot s^{-2}$.

## Conservation of Energy

In a close system, energy is always conserved. For example, when dropping an object from a height, gravitational energy converts of kinetic energy. You can write this in an equation: $$\frac{1}{2}mv^2 = mgh$$

Sometimes, there is some energy lost in the transition. For example, kinetic energy may be lost to heat (thermal energy).

## Elastic Potential Energy

The force due to elasticity can be modeled by Hooke's law. $$F = kx$$ Where $x$ is the displacement from the spring's central position and $k$ is the spring constant. The central point is also where the spring is at equilibrium, where the net force is zero.

## Efficiency

The efficiency of a system is how much energy was useful. $$\textrm{efficiency} = \frac{ \textrm{useful work out} }{ \textrm{total energy in} }$$

# Momentum

Momentum ($p$) is the product of the mass of an object and its velocity. $$p = mv$$ Where $p$ is momentum, $m$ is mass, and $v$ is velocity. Momentum is a vector.

## Impulse

The change in momentum is equals to impulse. Impulse is defined by force multiplied by time. $$pv = ft$$

## Conservation of Momentum

In a close system, momentum is always conserved. This means the change in momentum of one object may contribute to the change in momentum of another object.

## Force-Time Graphs

The area under a force-time graph is the impulse, or the change in momentum.

## Collisions

There is three types of collisions: elastic, inelastic, and completely inelastic collision.

In an elastic collision, kinetic energy of the system is conserved. In an inelastic collision, some kinetic energy is waste, converted into heat, sound, etc. In a completely inelastic collision, the two objects stick together, kinetic energy is not conserved.

Note, in all collisions, momentum is conserved.

In an explosion, momentum is not conserved, as there is an external force acting on the object.

## Energy and Momentum

Since the equation for kinetic energy and momentum are both based on mass and velocity, we can find a relationship between the kinetic energy and the momentum of an object. This is a useful shortcut. $$KE = \frac{p^2}{2m}$$
