# Statyka – Notatki Obsidian

---

## 01 – Pojęcia podstawowe

**Punkt materialny**  
Model ciała o pomijalnych wymiarach, traktowany jako punkt geometryczny z przypisaną masą i siłą bezwładności.

**Ciało doskonale sztywne**  
Ciało, którego punkty nie zmieniają wzajemnych odległości. Nie ulega odkształceniom.

**Stopnie swobody**  
Liczba niezależnych parametrów opisujących położenie:
- Punkt na prostej: $n = 1$
- Punkt na płaszczyźnie: $n = 2$
- Punkt w przestrzeni: $n = 3$
- Tarcza/pręt na płaszczyźnie: $n = 3$
- Bryła w przestrzeni: $n = 6$

**Więzy**  
Ograniczenia ruchu punktu lub ciała sztywnego.

**Siła**  
Wzajemne oddziaływanie ciał (kontaktowe lub na odległość: grawitacyjne, elektrostatyczne, magnetyczne).  
Jednostka w SI: $1\,\text{N} = 1\,\text{kg} \cdot \text{m/s}^2$  
Siła jest wielkością wektorową.

---

## 02 – Zasady (aksjomaty) statyki

**1. Zasada równoległoboku**  
Wypadkowa dwóch sił:  
$$
\vec{W} = \vec{P}_1 + \vec{P}_2
$$

**2. Zasada dwóch sił**  
Siły równoważą się, gdy:  
$$
\vec{P} = -\vec{P}'
$$

**3. Zasada dodania układu zerowego**  
Dodanie lub odjęcie układu sił równoważących się nie zmienia działania układu sił.

**4. Zasada zesztywnienia**  
Zesztywnienie ciała odkształcalnego nie narusza jego równowagi.

**5. Zasada uwolnienia od więzów**  
Ciało nieswobodne można myślowo uwolnić od więzów, zastępując je siłami reakcji.

---

## 03 – Równowaga układów sił

**Płaski układ sił skończonych**  
Warunki równowagi:  
$$
\vec{W} = \vec{P}_1 + \vec{P}_2 + \ldots + \vec{P}_n = 0
$$
$$
M_0 = M_1 + M_2 + \ldots + M_n = 0
$$

Równania równowagi:  
$$
\sum \vec{P} = 0
$$
$$
\sum M_0 = 0
$$

**Płaski układ sił zbieżnych**  
Warunek równowagi:  
$$
\vec{W} = \vec{p}_1 + \vec{p}_2 + \ldots + \vec{p}_n = \sum_{i=1}^{n} \vec{p}_i = 0
$$

Przykład:  
Kula o masie $m = 100\,\text{kg}$ spoczywa na dwóch gładkich powierzchniach pod kątem $30^\circ$ i $60^\circ$. Oblicz reakcje w punktach styku.

---

## 04 – Wypadkowa sił w płaszczyźnie

Układ sił zbieżnych:  
$$
\vec{W} = \vec{P}_1 + \vec{P}_2 + \ldots + \vec{P}_n = \sum_{i=1}^{n} \vec{P}_i
$$

---

## 05 – Moment siły względem punktu

Wektorowo:  
$$
\vec{M}_O = \vec{r}_A \times \vec{P}
$$

Skalarowo:  
$$
M_O = r_A \cdot P \cdot \sin \alpha = P \cdot h
$$

Gdzie:  
- $\vec{r}_A$ – wektor od punktu O do punktu przyłożenia siły  
- $P$ – wartość siły  
- $\alpha$ – kąt między $\vec{r}_A$ a $\vec{P}$  
- $h$ – ramię siły (odległość od punktu O do linii działania siły)

---

## 06 – Podpory płaskie

| Rodzaj podpory               | Reakcje              |
|-----------------------------|----------------------|
| Przegubowa nieruchoma       | $V$, $H$             |
| Przegubowa przesuwna        | $V$                  |
| Sztywna (ściana, fundament) | $V$, $H$, moment     |

---

## 07 – Warunki równowagi w $\mathbb{R}^2$

Warunki:  
$$
\vec{V} = 0
$$
$$
M_0 = 0
$$

Równania równowagi:  
$$
\sum F_x = 0
$$
$$
\sum F_y = 0
$$
$$
\sum M_0 = 0
$$

Wektor siły:  
$$
\vec{V} = (V_x, V_y)
$$
$$
V_x \leq R_x,\quad V_y \leq R_y
$$

---

## 08 – Wyznaczanie sił w układach

Układ sił zbieżnych: linie działania sił przecinają się w jednym punkcie w płaszczyźnie.

Diagram: punkt $O$, z którego wychodzą siły $\vec{F}_1$, $\vec{F}_2$, $\vec{F}_3$, $\vec{F}_4$.