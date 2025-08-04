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
```

First switch S1 is opened, and then switch S2 is thrown to pole b, as shown below. The circuit is again allowed to reach equilibrium. 
(C1 = 6.0 µF, C2 = 2.0 µF, and C3 = 4.0 µF are now connected in closed loop, isolated from the battery, 𝑄1 = 72μC  ​𝑄2 = 24μC  𝑄3 = 48μC, Battery work: 1728𝜇J, Stored energy:  864𝜇J)

(c) Find the charges on all three capacitors when the circuit has reached its new equilibrium.
(d) How much potential energy is now stored in the capacitor array

아주 좋은 질문입니다. 왜 매번 계산할 때마다 다른 값이 나오는지를 정확하게 짚고 넘어가면, **전기회로의 기본 원리**도 훨씬 잘 이해하게 됩니다.

---

## ✅ 이유

1. **회로 상태에 따라 전하 재분배 방식이 다르기 때문입니다.**

   * 처음에는 **배터리가 연결**되어 있어, 에너지가 공급되며 각 캐패시터가 **배터리 전압에 따라 충전**됩니다.
   * 나중에는 **배터리가 제거**되고 **캐패시터들만 남은 폐회로** 상태가 되기 때문에, **총 전하는 보존**되지만 **에너지는 보존되지 않습니다.**

---

## 🔍 자세한 설명

### ⚡ 초반 상태 (S1 닫힘, S2-a) → 배터리 연결됨

* 배터리가 **전체 24V** 전압을 공급하면서 C1과 C2+C3 조합이 **직렬로 충전**됩니다.
* 따라서 각 캐패시터는 **전압 분배**에 따라 충전되고, **전하 Q도 계산이 가능합니다.**

📌 이때:

* 전체 에너지 = **배터리가 한 일: 1728 µJ**
* 실제 축적된 에너지 = **864 µJ**
* 나머지 864 µJ는 충전 도중 **열 손실 또는 내부 전류 흐름으로 소실**되었다고 해석

---

### 🔁 이후 상태 (S1 열림, S2-b) → 배터리 제거, 폐회로

* 이제는 외부 에너지원 없이 **캐패시터들끼리 전하를 주고받으며 재분배**
* **총 전하(총 양자성량)는 보존되지만**, 각각의 캐패시터 전하와 전압은 변할 수 있음
* 중요한 점은:

  * 폐회로에선 **루프 전압합 = 0**
  * **전하 보존**을 만족하면서 **에너지 최소화 상태로 이동**

👉 이 과정은 **열역학적 비보존 과정**으로, 일부 에너지가 내부 전류 흐름에 의해 소멸됨

---

## ✅ 정리

| 구분                     | 전하 보존 | 에너지 보존        |
| ---------------------- | ----- | ------------- |
| (a) 초기 상태 (배터리 O)      | ❌ X   | ✅ 공급된 에너지 있음  |
| (c) 이후 상태 (배터리 X, 폐회로) | ✅ O   | ❌ 손실됨 (에너지 ↓) |

---

필요하면 실제 회로도와 함께 **정확한 해석 방식**을 순서대로 알려드릴게요.
**전하 보존**, **전압 루프 합 0**, 그리고 **에너지 소멸** 개념만 기억하면 문제에 흔들리지 않습니다.
