# ElectraCalc — Electronics Laws Calculator

A comprehensive electronics laws calculator covering all major laws used in circuit analysis. Pure HTML/CSS/JS — no backend, no API, no database.

## ⚡ Laws Covered

| Law | Formulas |
|-----|----------|
| **Ohm's Law** | V=IR, I=V/R, R=V/I |
| **Electric Power Law** | P=VI, P=I²R, P=V²/R, V=P/I |
| **Kirchhoff's Current Law (KCL)** | 2-branch, 3-branch, find missing current |
| **Kirchhoff's Voltage Law (KVL)** | 2-drop, 3-drop, loop verification |
| **Capacitor Laws** | Q=CV, Energy, Series, Parallel, RC time constant |
| **Inductor Laws** | EMF, Energy, RL time constant, Series |
| **Faraday's Law** | Induced EMF, Magnetic Flux |
| **Resonance Frequency** | LC resonance, Inductive reactance, Capacitive reactance |
| **Resistor Combinations** | Series (2,3), Parallel (2,3) |
| **Thevenin's Theorem** | V_th, Load current |
| **Voltage & Current Divider** | Voltage divider, Current divider |
| **Coulomb's / Electric Field** | Force, Electric field, Electric potential |

## 🔄 How It Works

1. **Select a Law** from the grid
2. **Choose a Formula** variant (e.g. solve for V, I, or R)
3. **Enter the known values**
4. **Get the result** with all related quantities shown

## 🚀 Deploy on GitHub Pages

1. Upload this repo to GitHub
2. Go to **Settings → Pages → Source: main / (root)**
3. Live at `https://yourusername.github.io/electronics-calc`

## 🛠 Tech Stack

- Pure HTML, CSS, JavaScript — zero dependencies
- Single `index.html` file
- Works offline, no internet needed after load (except Google Fonts)

## 📁 Structure

```
electronics-calc/
├── index.html
└── README.md
```
