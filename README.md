```
Problem 1- Three uncharged capacitors and an ideal battery are combined to
form the circuit shown to the right. Switch S1 is a simple open/closed switch,
while switch S2 can be toggled between poles a and b. The values for the
various circuit elements are as follows:
ΔVB = 24 V  C1 = 6.0 µF  C2 = 2.0 µF  C3 = 4.0 µF
C2 and C3 are parallel
C1 and C23 are serial
C1 is connected +
C23 is connected -

Switch S2 is closed, as shown, and the circuit is allowed to reach equilibrium.
(a) Find the charges on all three capacitors when the circuit is in equilibrium.
Ans) 𝑄1 = 72μC  ​𝑄2 = 24μC  𝑄3 = 48μC
(b) How much work does the battery do while the array is reaching equilibrium? How much
potential energy is stored in the capacitor array?
Ans) Battery work: 1728𝜇J, Stored energy:  864𝜇J


First switch S1 is opened, and then switch S2 is thrown to pole b, as shown below. The circuit is again allowed to reach equilibrium. 
(C1 = 6.0 µF, C2 = 2.0 µF, and C3 = 4.0 µF are now connected in closed loop, isolated from the battery, 𝑄1 = 72μC  ​𝑄2 = 24μC  𝑄3 = 48μC, Battery work: 1728𝜇J, Stored energy:  864𝜇J)

(c) Find the charges on all three capacitors when the circuit has reached its new equilibrium.
(d) How much potential energy is now stored in the capacitor array
```
Here are the **assumptions** applied in the problem and solutions, written in English:

---

### ✅ **Assumptions Used**

1. **All capacitors are ideal** (no internal resistance or leakage).
2. **The battery is ideal**, supplying constant voltage without internal resistance.
3. **There is no energy loss** during charge redistribution (e.g., no heat or radiation).
4. **Electrostatic energy is conserved** after the battery is disconnected.
5. **Switching is instantaneous and lossless.**
6. **Voltage across parallel capacitors is the same.**
7. **Charge across series-connected capacitors is the same.**
8. **Initial capacitors are uncharged.**
9. **The system reaches equilibrium after each switch operation.**

---

Let me know if you want these translated to Korean as well.

---

## ✅ Problem Overview

You have **three uncharged capacitors**:

* C₁ = 6.0 μF
* C₂ = 2.0 μF
* C₃ = 4.0 μF
* Battery voltage: ΔV<sub>B</sub> = 24 V

At first:

* C₂ and C₃ are connected **in parallel**
* That group is connected **in series** with C₁
* The battery is connected across the whole series circuit

Later:

* Switch S1 is opened (disconnecting the battery)
* Switch S2 is moved, so C₁, C₂, and C₃ form a **closed loop** in series

---

## 🔹 (a) What are the charges on the capacitors at the beginning?

**Step 1: Find equivalent capacitance**

* C₂ and C₃ are in parallel:

  $$
  C_{23} = C_2 + C_3 = 2.0 + 4.0 = 6.0\,\mu\text{F}
  $$
* C₁ and C₂∥C₃ are in series:

  $$
  \frac{1}{C_{\text{eq}}} = \frac{1}{6.0} + \frac{1}{6.0} = \frac{1}{3}
  \Rightarrow C_{\text{eq}} = 3.0\,\mu\text{F}
  $$

**Step 2: Total charge from battery**

$$
Q = C_{\text{eq}} \cdot V = 3.0\,\mu\text{F} \cdot 24\,\text{V} = 72\,\mu\text{C}
$$

**Step 3: Voltage across each capacitor**

* C₁:

  $$
  V_1 = \frac{Q}{C_1} = \frac{72}{6.0} = 12\,\text{V}
  $$
* C₂ and C₃ (parallel) also share 12 V:

  $$
  Q_2 = C_2 \cdot 12 = 2.0 \cdot 12 = 24\,\mu\text{C}
  $$

  $$
  Q_3 = C_3 \cdot 12 = 4.0 \cdot 12 = 48\,\mu\text{C}
  $$

### ✅ Final Answer (a):

* Q₁ = 72 μC
* Q₂ = 24 μC
* Q₃ = 48 μC

---

## 🔹 (b) How much work does the battery do? How much energy is stored?

* **Work done by battery**:

  $$
  W = Q \cdot V = 72\,\mu\text{C} \cdot 24\,\text{V} = 1728\,\mu\text{J}
  $$

* **Stored energy in capacitors**:

  $$
  U = \frac{1}{2} C_{\text{eq}} V^2 = 0.5 \cdot 3.0 \cdot 24^2 = 864\,\mu\text{J}
  $$

### ✅ Final Answer (b):

* Battery work = 1728 μJ
* Stored energy = 864 μJ

---

## 🔹 (c) What are the charges after the battery is removed and capacitors form a closed loop?

Now:

* The battery is disconnected
* C₁, C₂, and C₃ form a **closed loop in series**
* **Energy is conserved** (no losses assumed)

**Step 1: New equivalent capacitance**

$$
\frac{1}{C_{\text{eq}}} = \frac{1}{6.0} + \frac{1}{2.0} + \frac{1}{4.0} = \frac{11}{12}
\Rightarrow C_{\text{eq}} = \frac{12}{11} ≈ 1.09\,\mu\text{F}
$$

**Step 2: Total voltage in loop (using energy conservation)**

$$
U = \frac{1}{2} C_{\text{eq}} V^2 \Rightarrow
V = \sqrt{\frac{2U}{C_{\text{eq}}}} ≈ 39.8\,\text{V}
$$

**Step 3: New charge on each capacitor**
(All capacitors in series → same charge)

$$
Q = C_{\text{eq}} \cdot V ≈ 1.09\,\mu\text{F} \cdot 39.8\,\text{V} ≈ 43.4\,\mu\text{C}
$$

### ✅ Final Answer (c):

* Q₁ = Q₂ = Q₃ = 43.4 μC

---

## 🔹 (d) How much energy is now stored in the system?

Even though the configuration changed, **total energy remains the same**, because:

* Battery is disconnected
* No energy was lost (ideal case)

$$
U = 864\,\mu\text{J}
$$

### ✅ Final Answer (d):

* Stored energy = 864 μJ (same as before)

---

## ✅ Summary Table

| Part | Q₁ (μC) | Q₂ (μC) | Q₃ (μC) | Battery Work (μJ) | Stored Energy (μJ) |
| ---- | ------- | ------- | ------- | ----------------- | ------------------ |
| (a)  | 72      | 24      | 48      | 1728              | 864                |
| (c)  | 43.4    | 43.4    | 43.4    | —                 | 864                |

---

Here are the **physics laws** applied in solving the capacitor problem, written in English:

---

### ✅ **Physics Laws Applied**

1. **Kirchhoff’s Voltage Law (KVL)**
   The sum of voltages around any closed loop is zero.
   → Used to relate voltages across capacitors in series and loops.

2. **Conservation of Energy**
   The total electrostatic energy in the system is conserved (after battery is disconnected).
   → Used to calculate new voltage and charge after switch changes.

3. **Capacitor Charge-Voltage Relation**

   $$
   Q = C \cdot V
   $$

   → Fundamental definition of how capacitors store charge.

4. **Equivalent Capacitance Rules**

   * **Series**:

     $$
     \frac{1}{C_{\text{eq}}} = \frac{1}{C_1} + \frac{1}{C_2} + \cdots
     $$
   * **Parallel**:

     $$
     C_{\text{eq}} = C_1 + C_2 + \cdots
     $$

   → Used to simplify the circuit.

5. **Charge Conservation in Series**
   In a series circuit, all capacitors share the **same charge**.

6. **Voltage Equality in Parallel**
   In a parallel connection, all capacitors share the **same voltage**.

7. **Work-Energy Theorem (for electric potential energy)**

   $$
   U = \frac{1}{2} C V^2
   $$

   → Used to compute stored energy in capacitors.

---

