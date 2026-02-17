# Phase Changes and Heating Curve

## States of Matter

| State | Shape | Volume | Particle arrangement |
|---|---|---|---|
| Solid | Definite | Definite | Tightly bound, vibrate in place |
| Liquid | Variable (takes container shape) | Definite | Close but can slide past each other |
| Gas | Variable | Variable | Far apart, move freely |

## Phase Transitions

| Transition | From | To |
|---|---|---|
| Melting (fusion) | Solid | Liquid |
| Freezing (solidification) | Liquid | Solid |
| Vaporization / Boiling | Liquid | Gas |
| Condensation (liquefaction) | Gas | Liquid |
| Sublimation | Solid | Gas |
| Deposition | Gas | Solid |

## Sensible Heat

Heat that causes a **temperature change** within a single phase:

$$Q = m \cdot c \cdot \Delta T$$

where:
- $Q$ — heat $[\text{J}]$ or $[\text{cal}]$
- $m$ — mass $[\text{kg}]$ or $[\text{g}]$
- $c$ — specific heat capacity $[\text{J/(kg·°C)}]$ or $[\text{cal/(g·°C)}]$
- $\Delta T = T_f - T_i$ — temperature change $[\text{°C}]$ or $[\text{K}]$

## Latent Heat

Heat absorbed or released during a **phase change** at constant temperature:

$$Q = m \cdot L$$

where:
- $Q$ — heat $[\text{J}]$ or $[\text{cal}]$
- $m$ — mass $[\text{kg}]$ or $[\text{g}]$
- $L$ — specific latent heat $[\text{J/kg}]$ or $[\text{cal/g}]$
  - $L_f$ — latent heat of fusion
  - $L_v$ — latent heat of vaporization

## Heating Curve

The heating curve plots **temperature vs. heat absorbed** (or time at constant power) for a pure substance at constant pressure.

- **Sloped segments**: temperature rises within a single phase (sensible heat, $Q = mc\Delta T$)
- **Horizontal plateaus**: phase transition occurs at constant temperature (latent heat, $Q = mL$)

### Total heat for a complete solid → gas transition

$$Q_{\text{total}} = \underbrace{m \cdot c_s \cdot (T_f^{\text{melt}} - T_i)}_{\text{heating solid}} + \underbrace{m \cdot L_f}_{\text{melting}} + \underbrace{m \cdot c_l \cdot (T_b - T_f^{\text{melt}})}_{\text{heating liquid}} + \underbrace{m \cdot L_v}_{\text{boiling}}$$

where:
- $c_s$ — specific heat of the solid phase
- $c_l$ — specific heat of the liquid phase
- $T_f^{\text{melt}}$ — melting temperature
- $T_b$ — boiling temperature
- $T_i$ — initial temperature

### Reference values for water

| Property | Value |
|---|---|
| $c_{\text{ice}}$ | $0.5\ \text{cal/(g·°C)}$ |
| $c_{\text{water}}$ | $1\ \text{cal/(g·°C)}$ or $4186\ \text{J/(kg·°C)}$ |
| $L_f$ (fusion) | $80\ \text{cal/g}$ |
| $L_v$ (vaporization) | $540\ \text{cal/g}$ or $2260\ \text{kJ/kg}$ |
