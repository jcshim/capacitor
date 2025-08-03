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

### 회로 정리 및 등가 정전용량 계산

1. C2와 C3는 **병렬 연결**되어 있으므로, 등가 정전용량:
   $$
   C_{23} = C_2 + C_3 = 2.0\,\mu F + 4.0\,\mu F = 6.0\,\mu F
   $$

2. C1과 (C2+C3)는 **직렬 연결**:
   $$
   C_{\text{total}} = \left(\frac{1}{C_1} + \frac{1}{C_{23}}\right)^{-1}
   $$
   $$
   = \left(\frac{1}{6.0\,\mu F} + \frac{1}{6.0\,\mu F}\right)^{-1}
   = (2 \times \frac{1}{6.0\,\mu F})^{-1}
   = ( \frac{1}{3.0\,\mu F} )^{-1}
   = 3.0\,\mu F 
   $$

### 전체 회로에 흐르는 전하 Q 구하기

전지의 전위차(ΔVB)로 충전될 전체 전하는:
$$
Q_{\text{total}} = C_{\text{total}} \cdot \Delta V_B = 3.0\,\mu F \times 24\,V = 72\,\mu C
$$

### 각 커패시터에 흐르는 전하 구하기

- **직렬 연결 시 동일 전하**를 갖는다: Q1 = Q23 = 72 μC

#### ① C1:

$$
Q_{C1} = Q_{\text{total}} = 72\,\mu C
$$

#### ② C2, C3: (병렬 연결, 전압 동일)

C2, C3에 걸리는 전압:
$$
V_{23} = \frac{Q_{23}}{C_{23}} = \frac{72\,\mu C}{6.0\,\mu F} = 12\,V
$$

따라서,
- C2: $$ Q_2 = C_2 \cdot V_{23} = 2.0\,\mu F \times 12\,V = 24\,\mu C $$
- C3: $$ Q_3 = C_3 \cdot V_{23} = 4.0\,\mu F \times 12\,V = 48\,\mu C $$

### 최종 정리 (답)

| 커패시터 | 전하 (μC) |
|----------|---------|
| C1       | 72      |
| C2       | 24      |
| C3       | 48      |
