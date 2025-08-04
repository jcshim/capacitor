GitHub markdown does not support LaTeX-style math (`$$...$$` or `\(...\)`) directly. To ensure your equations render properly on GitHub, you need to:

* **Replace all LaTeX with inline math using Unicode or plain text.**
* **Use code formatting or descriptive math notation**.

Here’s the **GitHub-compatible version** of your explanation with **all equations rewritten in readable plain-text form**:

---

### ✅ Problem 1 (Original Configuration)

**Three uncharged capacitors** and an **ideal battery** are connected as shown.

* **Battery voltage**: ΔV\_B = 24 V
* **Capacitors**:
  C₁ = 6.0 μF
  C₂ = 2.0 μF
  C₃ = 4.0 μF
* **Switches**:

  * S1: ON/OFF switch
  * S2: toggles between positions *a* and *b*
* Configuration:

  * C₂ and C₃ are in **parallel**
  * Their combination (C₂ || C₃) is in **series** with C₁
  * C₁ is connected to the **+ terminal** of the battery
  * C₂ || C₃ is connected to the **− terminal**

---

### (a) Find the charge on each capacitor (with S1 closed, S2 at a)

1. **C₂ and C₃ in parallel**:
   C₂₃ = C₂ + C₃ = 2.0 μF + 4.0 μF = **6.0 μF**

2. **Series with C₁**:
   1 / C\_eq = 1 / C₁ + 1 / C₂₃
   → 1 / C\_eq = 1/6.0 + 1/6.0 = 1/3.0
   → C\_eq = **3.0 μF**

3. **Total charge from battery**:
   Q\_total = C\_eq × V = 3.0 μF × 24 V = **72 μC**

4. **C₁ (in series) gets the full charge**:
   Q₁ = **72 μC**

5. **C₂ and C₃ (parallel) share 12 V**:
   Q₂ = C₂ × 12 V = 2.0 × 12 = **24 μC**
   Q₃ = C₃ × 12 V = 4.0 × 12 = **48 μC**

---

### (b) Battery work and stored energy

* **Work by battery**:
  W = Q\_total × V = 72 μC × 24 V = **1728 μJ**

* **Stored energy in capacitors**:
  U = 0.5 × C\_eq × V² = 0.5 × 3.0 × 576 = **864 μJ**

> ⚠️ Half of the work is not stored — it is dissipated (e.g., as heat).

---

### ⚙️ Modified Configuration (S1 open, S2 switched to b)

After initial charging:

* S1 is **opened** → Battery is **disconnected**
* S2 is thrown to **b**
* Now C₁, C₂, and C₃ form a **closed loop**
* No external voltage source; charge redistributes internally

---

### (c) Charges on capacitors in new equilibrium

Capacitors are now in **series**, and in a series:

* **All capacitors share the same charge**
  → Q₁ = Q₂ = Q₃ = **48 μC**

---

### (d) Energy stored in the capacitor array

Total stored energy is:

```
U = 0.5 × (Q² / C₁ + Q² / C₂ + Q² / C₃)
  = 0.5 × (48² / 6.0 + 48² / 2.0 + 48² / 4.0)
  = 0.5 × (384 + 1152 + 576)
  = 0.5 × 2112 = **1056 μJ**
```

---

### 📊 Final Summary

| Part | Description                        | Answer                             |
| ---- | ---------------------------------- | ---------------------------------- |
| (a)  | Initial charges                    | Q₁ = 72 μC, Q₂ = 24 μC, Q₃ = 48 μC |
| (b)  | Battery work and stored energy     | Work = 1728 μJ, Stored = 864 μJ    |
| (c)  | Charges after battery disconnected | Q₁ = Q₂ = Q₃ = 48 μC               |
| (d)  | Stored energy in closed loop       | 1056 μJ                            |

---

### ❓ Key Insights

* In a **series circuit**, charge (Q) is always **equal** across all capacitors.
* Even if capacitors had different polarities originally, connecting them in a loop is valid — charges redistribute naturally.
* **Charge is conserved**, but **energy is not**. Some energy is lost during redistribution.

---

