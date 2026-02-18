# Laws of Thermodynamics

## Zeroth Law — Thermal Equilibrium

If body A is in thermal equilibrium with body C, and body B is also in thermal equilibrium with body C, then A and B are in thermal equilibrium with each other (i.e., $T_A = T_B = T_C$).

This law establishes **temperature** as a well-defined, transitive property.

## First Law — Conservation of Energy

The change in internal energy of a system equals the heat added minus the work done by the system:

$$\Delta U = Q - W \qquad \text{or equivalently} \qquad Q = W + \Delta U$$

where:
- $\Delta U$ — change in internal energy $[\text{J}]$
- $Q$ — heat added to the system $[\text{J}]$ ($Q > 0$ if absorbed, $Q < 0$ if released)
- $W$ — work done **by** the system $[\text{J}]$ ($W > 0$ if expansion, $W < 0$ if compression)

### First Law Applied to Special Processes

| Process | Condition | Consequence |
|---|---|---|
| Isothermal ($T = \text{const}$) | $\Delta U = 0$ | $Q = W$ |
| Isochoric ($V = \text{const}$) | $W = 0$ | $Q = \Delta U$ |
| Isobaric ($P = \text{const}$) | — | $Q = W + \Delta U$, with $W = P\,\Delta V$ |
| Adiabatic ($Q = 0$) | No heat exchange | $\Delta U = -W$ |

### Work in an Isothermal Process

$$W = n\,R\,T\,\ln\!\left(\frac{V_f}{V_i}\right)$$

where:
- $V_f$ — final volume
- $V_i$ — initial volume
- $\ln$ — natural logarithm

## Second Law — Entropy and Irreversibility

In any thermodynamic process, the total entropy of an isolated system always increases or remains constant; it never decreases.

### Entropy change (reversible process)

$$\Delta S = \frac{Q_{\text{rev}}}{T}$$

where:
- $Q_{\text{rev}}$ — heat exchanged reversibly $[\text{J}]$
- $T$ — absolute temperature at which the exchange occurs $[\text{K}]$

### Clausius statement

Heat cannot spontaneously flow from a colder body to a hotter body without external work.

### Kelvin–Planck statement

No cyclic heat engine can convert **all** absorbed heat into work — some heat must always be rejected.

### Heat Engine

A heat engine operates between a hot reservoir ($T_H$) and a cold reservoir ($T_C$):

$$W = |Q_H| - |Q_C|$$

where:
- $Q_H$ — heat absorbed from the hot source $[\text{J}]$
- $Q_C$ — heat rejected to the cold sink $[\text{J}]$

**Thermal efficiency:**

$$\eta = \frac{W}{Q_H} = 1 - \frac{|Q_C|}{Q_H}$$

> Efficiency is always $\eta < 1$ (i.e., less than 100%).

## Third Law — Nernst Theorem

As the temperature of a system approaches absolute zero ($T \to 0\ \text{K}$), the entropy of a perfect crystal approaches zero:

$$\lim_{T \to 0} S = 0$$

It is impossible to reach absolute zero in a finite number of steps.

## Carnot Cycle

The **Carnot cycle** defines the maximum possible efficiency for any heat engine operating between two temperatures. It consists of four reversible steps:

1. **Isothermal expansion** ($A \to B$) at $T_H$ — gas absorbs $Q_H$
2. **Adiabatic expansion** ($B \to C$) — temperature drops from $T_H$ to $T_C$
3. **Isothermal compression** ($C \to D$) at $T_C$ — gas releases $Q_C$
4. **Adiabatic compression** ($D \to A$) — temperature rises from $T_C$ back to $T_H$

### Carnot's theorem (heat ratio)

$$\frac{|Q_C|}{Q_H} = \frac{T_C}{T_H}$$

### Carnot efficiency (maximum possible)

$$\eta_{\text{Carnot}} = 1 - \frac{T_C}{T_H}$$

where:
- $T_H$ — absolute temperature of the hot reservoir $[\text{K}]$
- $T_C$ — absolute temperature of the cold reservoir $[\text{K}]$

> No real engine can exceed Carnot efficiency between the same two temperatures.

---
Back to: [[index]]
