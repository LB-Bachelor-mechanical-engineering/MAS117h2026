# MAS117 – Termodynamikk
## Løsningsforslag - Innlevering 3 / Obligatorisk øving Nr. 3

---

### Oppgave 3.1: Tabell for vann ( $\text{H}_2\text{O}$ )

#### Generelle antagelser og tabellreferanser:
* Tabellene som benyttes er standard damptabeller for vann ($\text{H}_2\text{O}$):
  * **Mettede tilstander (Temperaturtabell / Trykktabell)**: Mettet væske og mettet damp ($T_\text{sat}$, $P_\text{sat}$, $h_f$, $h_g$, $h_{fg}$).
  * **Overopphetet damp**: Tabell for overopphetet vanndamp ($P > P_\text{sat}$ eller $T > T_\text{sat}$).
  * **Underkjølt væske**: Tabell for underkjølt væske eller tilnærming med mettet væske ved gitt temperatur $h \approx h_f(T)$.

---

#### Utregninger per tilstand:

1. **Tilstand 1:** $T = 200^\circ\text{C}$, $x = 0,7$
   * **Beregning:** Siden dampkvaliteten $x = 0,7$ er oppgitt ($0 < x < 1$), befinner stoffet seg i **våt damp-området (to-fase blandingsområde)**.
   * Fra temperaturtabellen for mettet vann ved $T = 200^\circ\text{C}$:
     * $P = P_\text{sat}(200^\circ\text{C}) = 1554,9\text{ kPa} \approx 1555\text{ kPa}$
     * $h_f = 852,26\text{ kJ/kg}$
     * $h_{fg} = 1938,5\text{ kJ/kg}$
   * Spesifikk entalpi:
     $$h = h_f + x \cdot h_{fg} = 852,26 + 0,7 \cdot 1938,5 = 2209,21\text{ kJ/kg}$$
   * **Beskrivelse:** Mettet væske-damp-blanding (Våt damp).

---

2. **Tilstand 2:** $P = 175\text{ kPa}$, $h = 2772,7\text{ kJ/kg}$
   * Fra trykktabellen for mettet vann ved $P = 175\text{ kPa}$:
     * $T_\text{sat} \approx 116,0^\circ\text{C}$
     * $h_f = 486,99\text{ kJ/kg}$
     * $h_g = 2700,2\text{ kJ/kg}$
   * Siden $h = 2772,7\text{ kJ/kg} > h_g$, er tilstanden **overopphetet damp**.
   * Slår opp i tabellen for overopphetet damp ved $P = 0,175\text{ MPa}$ (eller interpolerer):
     * Ved $P = 0,175\text{ MPa}$ og $h = 2772,7\text{ kJ/kg}$ finner vi $T = 150^\circ\text{C}$.
   * **Dampkvalitet $x$:** Ikke definert for overopphetet damp (skrives ofte som `-` eller `N/A`).
   * **Beskrivelse:** Overopphetet damp.

---

3. **Tilstand 3:** $T = 140^\circ\text{C}$, $h = 1800\text{ kJ/kg}$
   * Fra temperaturtabellen ved $T = 140^\circ\text{C}$:
     * $P_\text{sat} = 361,53\text{ kPa}$
     * $h_f = 589,16\text{ kJ/kg}$
     * $h_g = 2733,5\text{ kJ/kg}$
     * $h_{fg} = 2144,3\text{ kJ/kg}$
   * Siden $h_f < h < h_g$ ($589,16 < 1800 < 2733,5$), er stoffet en **væske-damp-blanding**.
   * $P = P_\text{sat} = 361,53\text{ kPa}$
   * Dampkvalitet $x$:
     $$x = \frac{h - h_f}{h_{fg}} = \frac{1800 - 589,16}{2144,3} \approx 0,565$$
   * **Beskrivelse:** Mettet væske-damp-blanding (Våt damp).

---

4. **Tilstand 4:** $T = 950^\circ\text{C}$, $x = 0,0$
   * **Beregning:** $x = 0,0$ betyr at stoffet er i tilstanden **mettet væske**.
   * Ved ekstremt høy temperatur ($T = 950^\circ\text{C}$) ligger tilstanden langt over den kritiske temperaturen for vann ($T_c = 373,95^\circ\text{C}$).
   * *Merk:* Dersom $x=0,0$ menes for en mettet tilstand eller om $T=95,0^\circ\text{C}$ var ment på trykkleif:
     * Dersom $T = 95,0^\circ\text{C}$ og $x = 0,0$:
       * $P = P_\text{sat}(95^\circ\text{C}) = 84,61\text{ kPa}$
       * $h = h_f(95^\circ\text{C}) = 398,0\text{ kJ/kg}$
       * **Beskrivelse:** Mettet væske.
     * Dersom $T = 950^\circ\text{C}$ tolkes som et superkritisk/overopphetet gasspunkt (uten fasedeling), er $x$ udefinert.
   *(Tabellen fylles ut med $T = 95^\circ\text{C}$ som antatt rettet oppgaveverdi, eller $T=950^\circ\text{C}$ spesifisert)*.

---

5. **Tilstand 5:** $T = 80^\circ\text{C}$, $h = 500\text{ kJ/kg}$
   * Fra temperaturtabell ved $T = 80^\circ\text{C}$:
     * $h_f = 335,02\text{ kJ/kg}$
     * $h_g = 2643,3\text{ kJ/kg}$
   * Siden $h_f < h < h_g$, er stoffet i to-faseområdet.
   * $P = P_\text{sat}(80^\circ\text{C}) = 47,416\text{ kPa}$
   * Dampkvalitet $x$:
     $$x = \frac{500 - 335,02}{2307,4} \approx 0,0715$$
   * **Beskrivelse:** Mettet væske-damp-blanding.

---

6. **Tilstand 6:** $T = 800^\circ\text{C}$, $h = 3162,2\text{ kJ/kg}$
   * Siden temperaturen $T = 800^\circ\text{C}$ er svært høy (godt over kritisk temp.), befinner vannet seg i området for **overopphetet damp**.
   * Slår opp i tabell for overopphetet damp ved $T = 800^\circ\text{C}$ og $h = 3162,2\text{ kJ/kg}$:
     * Dette tilsvarer et trykk $P = 3000\text{ kPa} = 3,0\text{ MPa}$.
   * **Dampkvalitet $x$:** Udefinert (`-`).
   * **Beskrivelse:** Overopphetet damp.

---

#### Utfylt tabell:

| Tilstand | $T$, $^\circ\text{C}$ | $P$, $\text{kPa}$ | $h$, $\text{kJ/kg}$ | $x$ | Beskrivelse av tilstanden |
| :--- | :--- | :--- | :--- | :--- | :--- |
| **1** | 200 | **1554,9** | **2209,2** | 0,7 | Mettet væske-damp-blanding |
| **2** | **150** | 175 | 2772,7 | **-** | Overopphetet damp |
| **3** | 140 | **361,5** | 1800 | **0,565** | Mettet væske-damp-blanding |
| **4** | 95 *(eller 950)* | **84,6** | **398,0** | 0,0 | Mettet væske |
| **5** | 80 | **47,4** | 500 | **0,0715** | Mettet væske-damp-blanding |
| **6** | 800 | **3000** | 3162,2 | **-** | Overopphetet damp |

---

### Oppgave 3.2: Stempel-sylinder med stoppere

#### Gitte data:
* **Tilstand 1:** $P_1 = 200\text{ kPa}$, $T_1 = 300^\circ\text{C}$
* **Prosess 1 $\rightarrow$ 2:** Avkjøling ved konstant trykk ($P_2 = P_1 = 200\text{ kPa}$) inntil alt vann er mettet damp og stempelet treffer stopperne.
* **Mellomtilstand 2:** Mettet damp ved $P_2 = 200\text{ kPa}$ ($x_2 = 1,0$).
* **Prosess 2 $\rightarrow$ 3:** Videre avkjøling ved konstant volum ($v_3 = v_2$) inntil $P_3 = 100\text{ kPa}$.

---

#### a) Skisse av prosessene i et $T-v$-diagram

```
    T (°C)
      ^
      |          (1) Isobar P1 = 200 kPa
  300 |----------*
      |           \
      |            \   
T_sat2|-------------* (2) Mettet damp (x = 1)
      |            |
  T_3 |------------* (3)
      |            |  Isochor v2 = v3
      +---------------------------------> v (m^3/kg)
                    v_2 = v_3
```

* **Prosess 1–2 (Isobar prosess):** Horisontal bevegelse nedover langs isobaren $P = 200\text{ kPa}$ fra overopphetet damp til metningskurven for damp ($x_2 = 1,0$).
* **Prosess 2–3 (Isokor prosess):** Vertikal linje rett nedover (konstant spesifikt volum $v_3 = v_2$) ned til trykket $P_3 = 100\text{ kPa}$ i to-faseområdet.

---

#### b) Endring i spesifikk entalpi ($\Delta h$) fra starttilstand (1) til sluttilstand (3)

1. **Tilstand 1 ($P_1 = 200\text{ kPa} = 0,2\text{ MPa}$, $T_1 = 300^\circ\text{C}$):**
   * Fra tabell for overopphetet damp:
     $$h_1 = 3077,2\text{ kJ/kg}$$
     $$v_1 = 1,31623\text{ m}^3/\text{kg}$$

2. **Tilstand 2 (Mettet damp ved $P_2 = 200\text{ kPa}$):**
   * Fra trykktabell for mettet vann ved $P = 200\text{ kPa}$:
     $$v_2 = v_g(200\text{ kPa}) = 0,88578\text{ m}^3/\text{kg}$$

3. **Tilstand 3 ($P_3 = 100\text{ kPa}$, $v_3 = v_2 = 0,88578\text{ m}^3/\text{kg}$):**
   * Fra trykktabell for mettet vann ved $P_3 = 100\text{ kPa}$:
     * $v_f = 0,001043\text{ m}^3/\text{kg}$
     * $v_g = 1,6940\text{ m}^3/\text{kg}$
     * $h_f = 417,46\text{ kJ/kg}$
     * $h_{fg} = 2258,0\text{ kJ/kg}$
   * Finn dampkvalitet $x_3$:
     $$x_3 = \frac{v_3 - v_f}{v_g - v_f} = \frac{0,88578 - 0,001043}{1,6940 - 0,001043} = \frac{0,884737}{1,692957} \approx 0,5226$$
   * Beregn $h_3$:
     $$h_3 = h_f + x_3 \cdot h_{fg} = 417,46 + 0,5226 \cdot 2258,0 = 1597,49\text{ kJ/kg}$$

4. **Endring i spesifikk entalpi $\Delta h_{1-3}$:**
   $$\Delta h = h_3 - h_1 = 1597,49 - 3077,2 = -1479,71\text{ kJ/kg}$$

   * **Svar:** Endringen i spesifikk entalpi er **$-1480\text{ kJ/kg}$** (entalpien reduseres med $1480\text{ kJ/kg}$).

---

### Oppgave 3.3: Fast tank med kuldemiddel R-134a

#### Gitte data:
* Volum $V = 60\text{ L} = 0,060\text{ m}^3$
* Masse $m = 0,5\text{ kg}$
* **Tilstand 1:** $P_1 = 140\text{ kPa}$
* **Tilstand 2:** $P_2 = 180\text{ kPa}$

---

#### a) Dampkvalitet $x_1$ i starten

Spesifikt volum for prosessen (konstant volum):
$$v = \frac{V}{m} = \frac{0,060\text{ m}^3}{0,5\text{ kg}} = 0,12\text{ m}^3/\text{kg}$$

Fra metningstabell for R-134a ved $P_1 = 140\text{ kPa}$:
* $v_f = 0,0007381\text{ m}^3/\text{kg}$
* $v_g = 0,14014\text{ m}^3/\text{kg}$

Siden $v_f < v < v_g$, beregnes $x_1$:
$$x_1 = \frac{v - v_f}{v_g - v_f} = \frac{0,12 - 0,0007381}{0,14014 - 0,0007381} = \frac{0,1192619}{0,1394019} \approx 0,8555$$

* **Svar:** Dampkvaliteten i starten er **$x_1 \approx 0,856$ (eller $85,6\%$)**.

---

#### b) Temperatur i sluttilstanden ($T_2$)

I sluttilstanden har vi $P_2 = 180\text{ kPa}$ og $v_2 = 0,12\text{ m}^3/\text{kg}$.
Fra metningstabell for R-134a ved $P_2 = 180\text{ kPa}$:
* $v_g = 0,10983\text{ m}^3/\text{kg}$

Siden $v_2 = 0,12\text{ m}^3/\text{kg} > v_g = 0,10983\text{ m}^3/\text{kg}$, befinner sluttilstanden seg i **overopphetet damp-området**.

Fra tabell for overopphetet R-134a ved $P = 0,18\text{ MPa}$:
* Ved $T = 10^\circ\text{C}$: $v = 0,11938\text{ m}^3/\text{kg}$
* Ved $T = 20^\circ\text{C}$: $v = 0,12482\text{ m}^3/\text{kg}$

Lineær interpolasjon for $v = 0,120\text{ m}^3/\text{kg}$:
$$T_2 = 10 + (20 - 10) \cdot \frac{0,120 - 0,11938}{0,12482 - 0,11938} = 10 + 10 \cdot \frac{0,00062}{0,00544} \approx 11,14^\circ\text{C}$$

* **Svar:** Temperaturen i sluttilstanden er **$T_2 \approx 11,1^\circ\text{C}$**.

---

#### c) $P-v$-diagram for prosessen

```
   P (kPa)
     ^
     |         /--- Overopphetet damp
     |        /
 180 |-------* (2)  [v = 0.12 m^3/kg]
     |      /|
 140 |-----*-+------ (1) [v = 0.12 m^3/kg]
     |    /  |
     |   /   |      (Vertikal rett linje = isokor prosess)
     +--+----+-----------------------------> v (m^3/kg)
       v_f  v_1=v_2
```

---

### Oppgave 3.4: Lufttanker koblet sammen

#### Gitte data og antagelser:
* Gasskonstant for luft: $R = 0,287\text{ kJ/(kg}\cdot\text{K)}$
* **Tank A:** $m_A = 10\text{ kg}$, $T_A = 15^\circ\text{C} = 288,15\text{ K}$, $P_A = 400\text{ kPa}$
* **Tank B:** $V_B = 4\text{ m}^3$, $T_B = 40^\circ\text{C} = 313,15\text{ K}$, $P_B = 200\text{ kPa}$
* **Sluttilstand (Lokal likevekt):** $T_2 = 21^\circ\text{C} = 294,15\text{ K}$
* **Antagelse:** Luft oppfører seg som en ideell gass.

---

#### a) Beregn volumet av tank A ($V_A$)

Bruker tilstandsligningen for ideell gass ($P \cdot V = m \cdot R \cdot T$):
$$V_A = \frac{m_A \cdot R \cdot T_A}{P_A}$$

$$V_A = \frac{10\text{ kg} \cdot 0,287\text{ kPa}\cdot\text{m}^3/(\text{kg}\cdot\text{K}) \cdot 288,15\text{ K}}{400\text{ kPa}} = \frac{826,9905}{400} \approx 2,0675\text{ m}^3$$

* **Svar:** Volumet av tank A er **$V_A \approx 2,07\text{ m}^3$**.

---

#### b) Beregn slutttrykket i systemet ($P_2$)

1. **Finn massen av luft i tank B ($m_B$):**
   $$m_B = \frac{P_B \cdot V_B}{R \cdot T_B} = \frac{200\text{ kPa} \cdot 4\text{ m}^3}{0,287\text{ kJ/(kg}\cdot\text{K)} \cdot 313,15\text{ K}} = \frac{800}{89,87405} \approx 8,9013\text{ kg}$$

2. **Finn total masse ($m_\text{tot}$) og totalt volum ($V_\text{tot}$):**
   $$m_\text{tot} = m_A + m_B = 10\text{ kg} + 8,9013\text{ kg} = 18,9013\text{ kg}$$
   $$V_\text{tot} = V_A + V_B = 2,0675\text{ m}^3 + 4,0\text{ m}^3 = 6,0675\text{ m}^3$$

3. **Beregn slutttrykk $P_2$ ved $T_2 = 294,15\text{ K}$:**
   $$P_2 = \frac{m_\text{tot} \cdot R \cdot T_2}{V_\text{tot}}$$
   $$P_2 = \frac{18,9013\text{ kg} \cdot 0,287\text{ kJ/(kg}\cdot\text{K)} \cdot 294,15\text{ K}}{6,0675\text{ m}^3} = \frac{1595,683}{6,0675} \approx 262,99\text{ kPa}$$

* **Svar:** Slutttrykket i systemet er **$P_2 \approx 263\text{ kPa}$**.
```

eof