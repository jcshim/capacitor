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
