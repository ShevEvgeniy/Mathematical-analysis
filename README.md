# Введение в математический анализ

## Тема 1. Знакомство с математическим анализом

### Введение в математический анализ
1. Как относятся друг к другу множество и последовательность? (в ответе использовать слова типа: часть, целое, общее, частное, родитель, дочерний субъект и т.д.)

2. Прочитать высказывания математической логики, построить их отрицания и *установить истинность*

$$\forall y \in [0; 1] : sgn(y)=1$$

$$\forall n\in \mathbb{N}>2 :\exists x, y, z\in \mathbb{N} : x^n = y^n + z^n$$ 

$$\forall x\in \mathbb{R}\exists X\in \mathbb{R} : X > x$$

$$\forall x\in \mathbb{C}\forall y\in \mathbb{C} : x > y || x < y$$  

$$\forall y\in[0; \frac\pi2]\exists \varepsilon > 0 : sin(y)< sin(y + \varepsilon)$$

$$\forall y\in[0; \pi)\exists\varepsilon > 0 : cos(y) > \cos(y + \varepsilon)$$ 

$$\exists x : x\notin \{ \mathbb {N, Z, Q, R, C } \}$$

### Множество
 1. Даны три множества a,b и с. Необходимо выполнить все изученные виды бинарных операций
над всеми комбинациями множеств.
 2. *Выполнить задание 1 на языке Python

 ### Последоватльность
 1. Даны 4 последовательности. Необходимо:

a. исследовать их на монотонность;

b. исследовать на ограниченность;

c. найти пятый по счету член.

a: 2 ** n - n

n = 1, +oo

последовательность ограничена снизу числом 1


b: 1 / (n - 1)

n = 2, +oo

последовательность ограничена сверху числом 1


b: -1 ** n + sqrt(2 * n)

n = 1, +oo

последовательность ограничена снизу числом -1


b: (-1) ** (2 * n) + 1 / (n ** 2)

n = 1, +oo

последовательность ограничена сверху числом 2

2. a1 = 128, a(n+1) - a(n) = 6, найти 12-й член заданной неявно последовательности

3. На языке Python предложить алгоритм вычисляющий численно предел с точностью e=10^(-7)**

6. Предложить оптимизацию алгоритма,полученного в задании 3, ускоряющую его сходимость.