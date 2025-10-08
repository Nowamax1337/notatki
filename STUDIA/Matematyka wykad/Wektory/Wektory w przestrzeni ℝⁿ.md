## Literatura
- M. Gewert, Z. Skoczylas – *Algebra liniowa 1. Definicje, twierdzenia, wzory. Przykłady, zadania. Kolokwia, egzaminy.*  
- M. Gewert, Z. Skoczylas – *Analiza matematyczna 1. Definicje, twierdzenia, wzory. Przykłady i zadania. Kolokwia i egzaminy.*  
- W. Krysicki, L. Włodarski – *Analiza matematyczna w zadaniach, cz. 1*, PWN  

---

## Definicje przestrzeni
- $$\mathbb{R}^n = \{(x_1, x_2, \dots, x_n) : x_i \in \mathbb{R}\}$$  

**Przykłady:**  
- $$\mathbb{R}^2 = \{(x,y): x,y \in \mathbb{R}\}$$  
- $$\mathbb{R}^3 = \{(x,y,z): x,y,z \in \mathbb{R}\}$$  

### Odległość
Dla punktów $$A=(x_1,\dots,x_n), B=(y_1,\dots,y_n)$$:  
$$d(A,B) = \sqrt{(y_1-x_1)^2 + \dots + (y_n-x_n)^2}$$  

**Przykład:**  
$$A=(5,2,1), B=(7,3,-1) \implies d(A,B)=\sqrt{19}$$  

---

## Wektory
- **Wektor związany**: $$\overrightarrow{AB}$$ – początek w $$A$$, koniec w $$B$$.  
- **Wektor wodzący**: $$\overrightarrow{OP} = [x_1,\dots,x_n]$$ dla $$P=(x_1,\dots,x_n)$$.  
- **Wektor swobodny**: $$\overrightarrow{AB} = [y_1-x_1, \dots, y_n-x_n]$$.  

**Przykład:**  
$$A=(-4,1,5,2), B=(5,2,3,-1) \implies \overrightarrow{AB}=[9,1,-2,-3]$$  

---

## Operacje na wektorach
- **Dodawanie**:  
  $$[v_1,\dots,v_n] + [w_1,\dots,w_n] = [v_1+w_1,\dots,v_n+w_n]$$  
- **Mnożenie przez skalar**:  
  $$c[v_1,\dots,v_n] = [cv_1,\dots,cv_n]$$  
- **Kombinacja liniowa**:  
  $$x_1a_1 + x_2a_2 + \dots + x_m a_m$$  

**Przykład:**  
$$2[5,1,-2] - 3[2,-3,4] + 4[-1,2,7] = [0,19,12]$$  

---

## Długość i wersory
- $$|v| = \sqrt{v_1^2 + \dots + v_n^2}$$  
- Wektor jednostkowy (wersor): $$|v|=1$$  
- Dwa wektory mają **ten sam kierunek** ⇔ $$v = c w$$ dla $$c \in \mathbb{R}$$.  

---

## Iloczyn skalarny
- **Definicje:**  
  1. $$v \cdot w = v_1w_1 + \dots + v_nw_n$$  
  2. $$v \cdot w = |v||w|\cos\alpha$$  

**Własności:**  
- $$v \cdot w = w \cdot v$$ (symetria)  
- $$u \cdot (v+w) = u \cdot v + u \cdot w$$ (rozdzielność)  
- $$(cv)\cdot w = c(v \cdot w)$$ (homogeniczność)  
- $$v \neq 0 \implies v \cdot v > 0$$ (dodatnia określoność)  
- $$|v| = \sqrt{v \cdot v}$$  
- $$|v+w| \leq |v|+|w|$$ (nierówność trójkąta)  
- $$v \perp w \iff v \cdot w = 0$$  

---

## Twierdzenie Pitagorasa
$$|v+w|^2 = |v|^2 + |w|^2 \quad \iff \quad v \perp w$$  

---

## Liniowa niezależność
- Układ $$a_1,\dots,a_k$$ jest **liniowo zależny**, jeśli jeden wektor jest kombinacją pozostałych.  
- Układ **liniowo niezależny**, jeśli żaden nie jest kombinacją innych.  

**Fakty:**  
- Układ zawierający wektor zerowy → liniowo zależny.  
- Układ zawierający dwa wektory równoległe → liniowo zależny.  