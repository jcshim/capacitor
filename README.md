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

(b) How much work does the battery do while the array is reaching equilibrium? How much
potential energy is stored in the capacitor array?

First switch S1 is opened, and then switch S2 is thrown to pole b, as shown below. The circuit is again allowed to reach equilibrium.

(c) Find the charges on all three capacitors when the circuit has reached its new equilibrium.

(d) How much potential energy is now stored in the capacitor array
```
이 문제는 **축전기 회로**와 **에너지 계산**에 대한 전형적인 물리 문제입니다.
각 항목을 차근차근 한글로 풀이해드릴게요.

---

## 🧮 주어진 정보:

* 전압: ΔVB = 24 V
* C₁ = 6.0 µF
* C₂ = 2.0 µF
* C₃ = 4.0 µF
* C₂와 C₃는 병렬 (→ C₂₃)
* C₁과 C₂₃는 직렬
* C₁: +극 연결
* C₂₃: -극 연결
* 초기에는 모두 충전되지 않음

---

Let's solve **Problem 1** step by step.

---

### **Circuit Description (Initial Configuration):**

* **Battery voltage**: $\Delta V_B = 24\, \text{V}$

* **Capacitor values**:
  $C_1 = 6.0\, \mu\text{F}$,
  $C_2 = 2.0\, \mu\text{F}$,
  $C_3 = 4.0\, \mu\text{F}$

* **Connection**:

  * $C_2$ and $C_3$ are in **parallel**:
    → Combine into $C_{23} = C_2 + C_3 = 2.0 + 4.0 = 6.0\, \mu\text{F}$
  * $C_1$ and $C_{23}$ are in **series**:
    → Effective capacitance:

    $$
    \frac{1}{C_{\text{eq}}} = \frac{1}{C_1} + \frac{1}{C_{23}} = \frac{1}{6.0} + \frac{1}{6.0} = \frac{2}{6.0} \Rightarrow C_{\text{eq}} = 3.0\, \mu\text{F}
    $$

---

### **(a) Find the charge on each capacitor:**

In series, **charge is the same** on all capacitors:

$$
Q = C_{\text{eq}} \cdot V = 3.0\, \mu\text{F} \cdot 24\,\text{V} = \boxed{72\, \mu\text{C}}
$$

* So, charge on:

  * $C_1$: $Q_1 = 72\, \mu\text{C}$
  * $C_{23}$: $Q_{23} = 72\, \mu\text{C}$

Now split the charge across $C_2$ and $C_3$ (in parallel):

* In parallel, **voltage is the same**.
* Voltage across $C_{23}$:

  $$
  V_{23} = \frac{Q_{23}}{C_{23}} = \frac{72}{6.0} = 12\,\text{V}
  $$

Then:

* $Q_2 = C_2 \cdot V_{23} = 2.0 \cdot 12 = \boxed{24\, \mu\text{C}}$
* $Q_3 = C_3 \cdot V_{23} = 4.0 \cdot 12 = \boxed{48\, \mu\text{C}}$

✅ Final answer for (a):

* $Q_1 = \boxed{72\, \mu\text{C}}$
* $Q_2 = \boxed{24\, \mu\text{C}}$
* $Q_3 = \boxed{48\, \mu\text{C}}$

---

### **(b) Battery work and stored potential energy**

#### 🔹 Work done by the battery:

$$
W = Q_{\text{total}} \cdot \Delta V = 72\, \mu\text{C} \cdot 24\,\text{V} = \boxed{1.728\, \text{mJ}}
$$

#### 🔹 Total energy stored in capacitors:

$$
U = \frac{1}{2} C_{\text{eq}} V^2 = \frac{1}{2} \cdot 3.0\, \mu\text{F} \cdot (24)^2 = \frac{1}{2} \cdot 3.0 \cdot 576 = 864\, \mu\text{J} = \boxed{0.864\, \text{mJ}}
$$

✅ Final answer for (b):

* **Work done by battery**: $\boxed{1.728\, \text{mJ}}$
* **Energy stored in capacitors**: $\boxed{0.864\, \text{mJ}}$

(Note: The other 0.864 mJ is lost as heat during redistribution of charge.)

---

Let’s now solve **(c)** and **(d)** of **Problem 1**, using the new configuration:

---

### ✅ After switches are changed:

* **S1 is open** (battery disconnected)
* **S2 is thrown to pole b**
* The three capacitors **C1 = 6.0 µF**, **C2 = 2.0 µF**, and **C3 = 4.0 µF** are now connected in **series**, isolated from the battery.
* **Total charge remains conserved** because no external source/sink is connected.
* **Initial total charge** (from part a):
  Total charge stored in the system was on C1:

  $$
  Q_{\text{initial}} = 72\, \mu\text{C}
  $$

---

### ⚠️ Key idea:

In series, all capacitors carry **equal charge**, so:

$$
Q_1 = Q_2 = Q_3 = Q
$$

Let’s find **equilibrium charge** $Q$ using **conservation of charge** and energy.

---

### Step 1: Find equivalent capacitance of series connection

$$
\frac{1}{C_{\text{eq}}} = \frac{1}{C_1} + \frac{1}{C_2} + \frac{1}{C_3}
= \frac{1}{6} + \frac{1}{2} + \frac{1}{4}
= \frac{2 + 6 + 3}{12} = \frac{11}{12}
\Rightarrow C_{\text{eq}} = \frac{12}{11}\, \mu\text{F}
$$

---

### Step 2: Total energy available (conserved from part b):

From part (b), the energy stored before S1 was opened was:

$$
U = 0.864\, \text{mJ}
$$

This energy is **conserved**, so now:

$$
U = \frac{1}{2} C_{\text{eq}} V_{\text{eq}}^2
\Rightarrow V_{\text{eq}}^2 = \frac{2U}{C_{\text{eq}}}
= \frac{2 \cdot 0.864 \times 10^{-3}}{12/11 \times 10^{-6}}
= \frac{1.728 \times 10^{-3}}{12/11 \times 10^{-6}}
= \frac{1.728 \cdot 11}{12 \cdot 10^{-6}} = \frac{18.998}{12 \times 10^{-6}} \approx 1.583 \times 10^{6}
\Rightarrow V_{\text{eq}} \approx \sqrt{1.583 \times 10^6} \approx 125.7\, \text{V}
$$

---

### Step 3: Find charge using $Q = C_{\text{eq}} \cdot V$

$$
Q = \frac{12}{11} \cdot 125.7 \approx 137.2\, \mu\text{C}
$$

✅ Therefore, all capacitors now have the same charge:

$$
Q_1 = Q_2 = Q_3 = \boxed{137.2\, \mu\text{C}}
$$

---

### Step 4: (d) How much potential energy is now stored?

This energy **remains the same** as in part (b), since the system is **isolated** (no battery, no current flow in/out):

$$
U_{\text{final}} = \boxed{0.864\, \text{mJ}}
$$

---

### ✅ Final Answers:

**(c) Capacitor charges at new equilibrium:**

* $Q_1 = Q_2 = Q_3 = \boxed{137.2\, \mu\text{C}}$

**(d) Stored energy:**

* $U = \boxed{0.864\, \text{mJ}}$

Let me know if you’d like the voltage across each capacitor as well!



### ✨ (a) 회로가 평형 상태에 도달했을 때, 세 축전기에 저장된 전하를 구하시오

### 1️⃣ C₂와 C₃는 병렬 연결:

$$
C_{23} = C_2 + C_3 = 2.0 \, \mu F + 4.0 \, \mu F = 6.0 \, \mu F
$$

### 2️⃣ C₁과 C₂₃는 직렬 연결:

직렬 연결에서는 전하가 같고, 전압이 나뉩니다.

등가 정전용량:

$$
\frac{1}{C_{eq}} = \frac{1}{C_1} + \frac{1}{C_{23}} = \frac{1}{6.0} + \frac{1}{6.0} = \frac{2}{6} = \frac{1}{3} \Rightarrow C_{eq} = 3.0 \, \mu F
$$

### 3️⃣ 전체 회로에 흐르는 전하:

$$
Q = C_{eq} \cdot V = 3.0 \, \mu F \cdot 24 \, V = 72 \, \mu C
$$

### 4️⃣ 직렬이므로 C₁과 C₂₃는 **같은 전하 Q = 72 µC**를 가짐

---

### ✅ 따라서:

* **C₁**:
  $Q_1 = 72 \, \mu C$
  $V_1 = \frac{Q}{C} = \frac{72}{6.0} = 12 \, V$

* **C₂₃ (병렬)**:
  전체 전하 $Q_{23} = 72 \, \mu C$, 전압도 12V

병렬에서는 전압이 같고 전하는 나뉩니다.

* **C₂**:
  $Q_2 = C_2 \cdot V = 2.0 \cdot 12 = 24 \, \mu C$

* **C₃**:
  $Q_3 = C_3 \cdot V = 4.0 \cdot 12 = 48 \, \mu C$

---

### ✅ (a) 정답 요약:

| 축전기 | 전하 (Q) | 전압 (V) |
| --- | ------ | ------ |
| C₁  | 72 µC  | 12 V   |
| C₂  | 24 µC  | 12 V   |
| C₃  | 48 µC  | 12 V   |

---

## ✨ (b) 배터리가 한 일, 저장된 전기 위치 에너지

### 🔋 배터리가 한 일 (전하 × 전압):

$$
W = Q_{total} \cdot \Delta V = 72 \, \mu C \cdot 24 \, V = 1,728 \, \mu J = 1.728 \, mJ
$$

### ⚡ 커패시터에 저장된 에너지:

전체 에너지 저장량:

$$
U = \frac{1}{2} C_{eq} \cdot V^2 = \frac{1}{2} \cdot 3.0 \, \mu F \cdot (24)^2 = 0.5 \cdot 3.0 \cdot 576 = 864 \, \mu J = 0.864 \, mJ
$$

---

### 🔍 (b) 정답 요약:

* **배터리가 한 일**:
  $1.728 \, \text{mJ}$

* **커패시터에 저장된 에너지**:
  $0.864 \, \text{mJ}$

(※ 나머지는 열 손실로 사라짐)

---

좋습니다. 이제 \*\*(c)\*\*와 **(d)** 항목에 대해 한글로 자세히 풀이해드리겠습니다.

---

## 🔄 상황 변경:

* S1: 열려 있음 → **배터리와 회로 단절됨 (외부 에너지 공급 없음)**
* S2: **a에서 b로 변경됨**
* → 이제 **C2와 C3는 병렬 연결 해제 → 직렬 연결**
* → 전체 회로는 **C1, C2, C3가 서로 병렬로 연결된 상태**
* 총 전하는 **보존**되어야 함:
  회로가 고립되었기 때문에 초기 총 전하량은 그대로 보존됩니다.

---

## ✅ (c) 스위치 S1이 열리고, S2가 b에 연결된 후 평형 상태에서의 전하 (Q)

### 이전 상태 요약 (기억하기):

* C₁: 72 µC, 12 V
* C₂: 24 µC, 12 V
* C₃: 48 µC, 12 V
  → 전하 총합:

$$
Q_{\text{total}} = Q_1 + Q_2 + Q_3 = 72 + 24 + 48 = 144 \, \mu C
$$

---

### 🔧 새로운 회로 구조 (S1 open, S2 → b):

모든 축전기가 병렬로 연결됨 → 전압은 동일하고, 총 전하는 보존됨

### 병렬이므로:

$$
V_{final} = \frac{Q_{total}}{C_{total}} = \frac{144 \, \mu C}{C_1 + C_2 + C_3}
= \frac{144}{6.0 + 2.0 + 4.0} = \frac{144}{12} = 12 \, V
$$

전압은 12V로 동일하고, 각 축전기의 전하는:

* $Q_1 = C_1 \cdot V = 6.0 \cdot 12 = 72 \, \mu C$
* $Q_2 = 2.0 \cdot 12 = 24 \, \mu C$
* $Q_3 = 4.0 \cdot 12 = 48 \, \mu C$

### ✅ 결론 (c):

| 축전기 | 전하 (Q) | 전압 (V) |
| --- | ------ | ------ |
| C₁  | 72 µC  | 12 V   |
| C₂  | 24 µC  | 12 V   |
| C₃  | 48 µC  | 12 V   |

> (이전과 **전혀 동일한 값**입니다 — 왜냐하면 전기적 구조가 바뀌었지만 전하가 분포할 수 있는 방식은 같기 때문입니다.)

---

## 💡 (d) 현재 커패시터에 저장된 에너지

전체 축전기 전기 에너지:

$$
U = \sum \frac{1}{2} C_i V^2
= \frac{1}{2}(6.0 + 2.0 + 4.0)\cdot (12)^2
= \frac{1}{2} \cdot 12.0 \cdot 144 = 864 \, \mu J = 0.864 \, mJ
$$

---

### ✅ 결론 (d):

* **저장된 총 전기 위치 에너지**:
  $\boxed{0.864 \, \text{mJ}}$

---
