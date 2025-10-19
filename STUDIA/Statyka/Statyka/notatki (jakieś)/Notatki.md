# Statyka – Notatki GitHub

---

## 01 – Pojęcia podstawowe

**Punkt materialny**  
Model ciała o pomijalnych wymiarach, traktowany jako punkt geometryczny z przypisaną masą i siłą bezwładności.

**Ciało doskonale sztywne**  
Ciało, którego punkty nie zmieniają wzajemnych odległości. Nie ulega odkształceniom.

**Stopnie swobody**  
Liczba niezależnych parametrów opisujących położenie:
- Punkt na prostej: n = 1
- Punkt na płaszczyźnie: n = 2
- Punkt w przestrzeni: n = 3
- Tarcza/pręt na płaszczyźnie: n = 3
- Bryła w przestrzeni: n = 6

**Więzy**  
Ograniczenia ruchu punktu lub ciała sztywnego.

**Siła**  
Wzajemne oddziaływanie ciał (kontaktowe lub na odległość: grawitacyjne, elektrostatyczne, magnetyczne).  
Jednostka w SI: 1 N = 1 kg·m/s²  
Siła jest wielkością wektorową.

---

## 02 – Zasady (aksjomaty) statyki

**1. Zasada równoległoboku**  
Wypadkowa dwóch sił:  
W = P₁ + P₂

**2. Zasada dwóch sił**  
Siły równoważą się, gdy:  
P = –P′

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
W = P₁ + P₂ + ... + Pₙ = 0  
M₀ = M₁ + M₂ + ... + Mₙ = 0

Równania równowagi:  
ΣP = 0  
ΣM₀ = 0

**Płaski układ sił zbieżnych**  
Warunek równowagi:  
W = p₁ + p₂ + ... + pₙ = Σ(pᵢ) = 0

Przykład:  
Kula o masie m = 100 kg spoczywa na dwóch gładkich powierzchniach pod kątem 30° i 60°. Oblicz reakcje w punktach styku.

---

## 04 – Wypadkowa sił w płaszczyźnie

Układ sił zbieżnych:  
W = P₁ + P₂ + ... + Pₙ = Σ(Pᵢ)

---

## 05 – Moment siły względem punktu

Wektorowo:  
M_O = r_A × P

Skalarowo:  
M_O = r_A · P · sin(α) = P · h

Gdzie:
- r_A – wektor od punktu O do punktu przyłożenia siły  
- P – wartość siły  
- α – kąt między r_A a P  
- h – ramię siły (odległość od punktu O do linii działania siły)

---

## 06 – Podpory płaskie

| Rodzaj podpory               | Reakcje          |
|-----------------------------|------------------|
| Przegubowa nieruchoma       | V, H             |
| Przegubowa przesuwna        | V                |
| Sztywna (ściana, fundament) | V, H, moment     |

---

## 07 – Warunki równowagi w R²

Warunki:  
V = 0  
M₀ = 0

Równania równowagi:  
ΣFₓ = 0  
ΣFᵧ = 0  
ΣM₀ = 0

Wektor siły:  
V = (Vₓ, Vᵧ)  
Vₓ ≤ Rₓ, Vᵧ ≤ Rᵧ

---

## 08 – Wyznaczanie sił w układach

Układ sił zbieżnych: linie działania sił przecinają się w jednym punkcie w płaszczyźnie.

Diagram: punkt O, z którego wychodzą siły F₁, F₂, F₃, F₄.