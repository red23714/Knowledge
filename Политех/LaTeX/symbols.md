# Шпаргалка по LaTeX-символам

> Криптография • Высшая математика • Дискретная математика
>
> Формулы: `$...$` — в строке, `$$...$$` — отдельным блоком.
> Внутри таблиц Obsidian символ `|` ломает разметку, поэтому вместо `|` и `\|` используются `\lvert`, `\rvert`, `\lVert`, `\rVert`, `\mid`, `\Vert`. Вне таблиц можно писать как обычно.

## Греческий алфавит

| Буква | Команда | Буква | Команда |
|---|---|---|---|
| $\alpha$ | `\alpha` | $\beta$ | `\beta` |
| $\gamma$ | `\gamma` | $\delta$ | `\delta` |
| $\varepsilon$ | `\varepsilon` | $\epsilon$ | `\epsilon` |
| $\zeta$ | `\zeta` | $\eta$ | `\eta` |
| $\theta$ | `\theta` | $\vartheta$ | `\vartheta` |
| $\iota$ | `\iota` | $\kappa$ | `\kappa` |
| $\lambda$ | `\lambda` | $\mu$ | `\mu` |
| $\nu$ | `\nu` | $\xi$ | `\xi` |
| $\pi$ | `\pi` | $\varpi$ | `\varpi` |
| $\rho$ | `\rho` | $\varrho$ | `\varrho` |
| $\sigma$ | `\sigma` | $\varsigma$ | `\varsigma` |
| $\tau$ | `\tau` | $\upsilon$ | `\upsilon` |
| $\phi$ | `\phi` | $\varphi$ | `\varphi` |
| $\chi$ | `\chi` | $\psi$ | `\psi` |
| $\omega$ | `\omega` | | |
| $\Gamma$ | `\Gamma` | $\Delta$ | `\Delta` |
| $\Theta$ | `\Theta` | $\Lambda$ | `\Lambda` |
| $\Xi$ | `\Xi` | $\Pi$ | `\Pi` |
| $\Sigma$ | `\Sigma` | $\Phi$ | `\Phi` |
| $\Psi$ | `\Psi` | $\Omega$ | `\Omega` |

## Степени, индексы, черты

| Запись | Команда | Смысл |
|---|---|---|
| $x^{2}$, $x_{i}$, $x^{2}_{i}$ | `x^{2}`, `x_{i}` | степень, индекс |
| $x'$, $x''$ | `x'` | штрих |
| $\hat{x}$, $\bar{x}$, $\tilde{x}$ | `\hat{x}`, `\bar{x}`, `\tilde{x}` | крышка, черта, волна |
| $\vec{x}$, $\dot{x}$, $\ddot{x}$ | `\vec{x}`, `\dot{x}` | вектор, производная по времени |
| $\overline{AB}$, $\underline{AB}$ | `\overline{AB}` | черта сверху/снизу |
| $\widehat{AB}$ | `\widehat{AB}` | широкая крышка |
| $\overbrace{\ldots}^{n}$, $\underbrace{\ldots}_{n}$ | `\overbrace{...}^{n}` | фигурная скобка |
| $\overset{a}{=}$, $\underset{a}{=}$ | `\overset{a}{=}` | знак с надписью сверху/снизу |
| $\stackrel{\text{def}}{=}$ | `\stackrel{\text{def}}{=}` | «равно по определению» |
| $f \circ g$ | `f \circ g` | композиция |
| $\dfrac{a}{b}$, $\tfrac{a}{b}$ | `\frac{a}{b}`, `\tfrac{a}{b}` | дробь (крупная/мелкая) |
| $\sqrt{x}$, $\sqrt[n]{x}$ | `\sqrt{x}`, `\sqrt[n]{x}` | корень |

## Скобки

| Запись | Команда | Смысл |
|---|---|---|
| $\left( x \right)$, $\left[ x \right]$ | `\left( x \right)` | автоподбор размера |
| $\left\{ x \right\}$ | `\left\{ x \right\}` | фигурные |
| $\langle x \rangle$ | `\langle x \rangle` | угловые |
| $\lfloor x \rfloor$ | `\lfloor x \rfloor` | пол (целая часть) |
| $\lceil x \rceil$ | `\lceil x \rceil` | потолок |
| $\lvert x \rvert$ | `\lvert x \rvert` | модуль (в таблицах; вне таблиц просто `\|`) |
| $\lVert x \rVert$ | `\lVert x \rVert` | норма (вне таблиц `\|\|`) |
| $\left. \right\vert$ | `\left. \right\vert` | вертикальная черта-разделитель |

## Отношения и сравнения

| Символ | Команда | Символ | Команда |
|---|---|---|---|
| $<$, $>$, $=$ | `<`, `>`, `=` | $\ne$ | `\ne` |
| $\le$, $\ge$ | `\le`, `\ge` | $\ll$, $\gg$ | `\ll`, `\gg` |
| $\sim$ | `\sim` | $\approx$ | `\approx` |
| $\simeq$ | `\simeq` | $\cong$ | `\cong` |
| $\equiv$ | `\equiv` | $\not\equiv$ | `\not\equiv` |
| $\propto$ | `\propto` | $\asymp$ | `\asymp` |
| $\prec$, $\succ$ | `\prec`, `\succ` | $\preceq$, $\succeq$ | `\preceq`, `\succeq` |
| $\perp$ | `\perp` | $\parallel$ | `\parallel` |
| $\angle$ | `\angle` | $\triangle$ | `\triangle` |

## Множества

| Символ | Команда | Смысл |
|---|---|---|
| $x \in A$, $x \notin A$ | `x \in A`, `x \notin A` | принадлежность |
| $A \ni x$ | `A \ni x` | обратная принадлежность |
| $A \subset B$, $A \subseteq B$ | `\subset`, `\subseteq` | подмножество |
| $A \cup B$, $A \cap B$ | `\cup`, `\cap` | объединение, пересечение |
| $A \setminus B$ | `A \setminus B` | разность |
| $\emptyset$, $\varnothing$ | `\emptyset`, `\varnothing` | пустое множество |
| $A \times B$ | `A \times B` | декартово произведение |
| $\bigcup_{i=1}^{n}$, $\bigcap_{i=1}^{n}$ | `\bigcup_{i=1}^{n}` | большие союзы |
| $\mathcal{P}(X)$ | `\mathcal{P}(X)` | булеан |

Числовые множества (в Obsidian макросов `\N`, `\Z` нет — пишите через `\mathbb{}`):

| Запись | Команда | Смысл |
|---|---|---|
| $\mathbb{N}$, $\mathbb{N}_0$ | `\mathbb{N}` | натуральные (с нулём) |
| $\mathbb{Z}$, $\mathbb{Q}$ | `\mathbb{Z}`, `\mathbb{Q}` | целые, рациональные |
| $\mathbb{R}$, $\mathbb{C}$ | `\mathbb{R}`, `\mathbb{C}` | действительные, комплексные |
| $\mathbb{A}$ | `\mathbb{A}` | алгебраические |
| $\mathbb{F}_q$ | `\mathbb{F}_q` | конечное поле |
| $\mathbb{R}[x]$ | `\mathbb{R}[x]` | многочлены |
| $[a, b]$, $(a, b)$ | `[a, b]`, `(a, b)` | отрезок, интервал |
| $\{x : P(x)\}$ | `\{x : P(x)\}` | задание свойством |

## Логика

| Символ | Команда | Смысл |
|---|---|---|
| $\neg x$ | `\neg` | отрицание |
| $x \land y$, $x \lor y$ | `\land`, `\lor` | И, ИЛИ |
| $P \Rightarrow Q$ | `\Rightarrow` | «следовательно» |
| $P \Leftarrow Q$, $P \Leftrightarrow Q$ | `\Leftarrow`, `\Leftrightarrow` | «тогда», «тогда и только тогда» |
| $P \to Q$, $P \leftrightarrow Q$ | `\to`, `\leftrightarrow` | импликация, эквивалентность |
| $\forall x$, $\exists x$ | `\forall`, `\exists` | кванторы |
| $\exists! x$ | `\exists!` | существует единственный |
| $\nexists$ | `\nexists` | не существует |
| $\vdash$, $\models$ | `\vdash`, `\models` | выводимо, общезначимо |
| $\top$, $\bot$ | `\top`, `\bot` | истина, ложь |
| $\therefore$ | `\therefore` | следовательно |

Булева алгебра: отрицание $\overline{x}$ или $\neg x$, конъюнкция $x \land y$,
дизъюнкция $x \lor y$, исключающее ИЛИ $x \oplus y$,
штрих Шеффера $x \uparrow y$, стрелка Пирса $x \downarrow y$,
импликация $x \to y$.

## Стрелки и прочее

| Символ | Команда | Символ | Команда |
|---|---|---|---|
| $\to$, $\gets$ | `\to`, `\gets` | $\mapsto$ | `\mapsto` |
| $\leadsto$ | `\leadsto` | $\iff$ | `\iff` |
| $\Longrightarrow$, $\impliedby$ | `\Longrightarrow`, `\impliedby` | $\Leftrightarrow$ | `\Leftrightarrow` |
| $\uparrow$, $\downarrow$ | `\uparrow`, `\downarrow` | $\nearrow$, $\searrow$ | `\nearrow`, `\searrow` |
| $\infty$ | `\infty` | $\partial$ | `\partial` |
| $\nabla$ | `\nabla` | $\ldots$, $\cdots$ | `\ldots`, `\cdots` |

## Высшая математика

**Пределы, суммы, произведения**

| Запись | Команда |
|---|---|
| $\lim\limits_{x \to a} f(x)$ | `\lim_{x \to a} f(x)` |
| $\lim\limits_{n \to \infty} a_n$ | `\lim_{n \to \infty} a_n` |
| $\sum_{i=1}^{n} a_i$, $\prod_{i=1}^{n} a_i$ | `\sum_{i=1}^{n}`, `\prod_{i=1}^{n}` |
| $\sup$, $\inf$, $\max$, $\min$ | `\sup`, `\inf`, `\max`, `\min` |
| $\arg\max$ | `\arg\max` |

**Производные и интегралы**

| Запись | Команда |
|---|---|
| $f'(x)$, $f^{(n)}(x)$ | `f'(x)`, `f^{(n)}(x)` |
| $\dfrac{dy}{dx}$ | `\frac{dy}{dx}` |
| $\dfrac{\partial f}{\partial x}$ | `\frac{\partial f}{\partial x}` |
| $\dfrac{\partial^2 f}{\partial x \, \partial y}$ | `\frac{\partial^2 f}{\partial x \partial y}` |
| $\nabla f$, $\operatorname{grad} f$ | `\nabla f` |
| $\int_a^b f(x) \, dx$ | `\int_a^b f(x) \, dx` |
| $\iint\limits_{D}$, $\iiint\limits_{V}$ | `\iint_D`, `\iiint_V` |
| $\oint\limits_{\gamma}$ | `\oint_\gamma` |
| $\int\limits_{-\infty}^{+\infty}$ | `\int_{-\infty}^{+\infty}` |

**Векторы, матрицы**

| Запись | Команда | Смысл |
|---|---|---|
| $\vec{a} \cdot \vec{b}$ | `\vec{a} \cdot \vec{b}` | скалярное произведение |
| $\vec{a} \times \vec{b}$, $[\vec{a}, \vec{b}]$ | `\times`, `[\vec{a}, \vec{b}]` | векторное произведение |
| $(\vec{a}, \vec{b})$ | `(\vec{a}, \vec{b})` | скалярное произведение |
| $\det A$, $A^{T}$, $A^{-1}$, $A^{*}$ | `\det A`, `A^{T}` | определитель, транспонирование |
| $\operatorname{rank} A$, $\operatorname{tr} A$ | `\operatorname{rank}` | ранг, след |
| $E$ | `E` | единичная матрица |
| $\lVert x \rVert_2$, $\lVert x \rVert_\infty$ | `\lVert x \rVert_2` | нормы |

$$
A = \begin{pmatrix} a_{11} & a_{12} \\ a_{21} & a_{22} \end{pmatrix}
\qquad
\begin{vmatrix} a & b \\ c & d \end{vmatrix}
\qquad
\begin{bmatrix} 1 & 0 \\ 0 & 1 \end{bmatrix}
$$

Окружения: `pmatrix` (круглые), `bmatrix` (квадратные), `vmatrix` (определитель), `matrix` (без скобок), `cases` (система), `aligned` (выкладки).

**Функции**

| Запись | Команда |
|---|---|
| $\sin x$, $\cos x$, $\tan x$, $\cot x$ | `\sin`, `\cos`, `\tan`, `\cot` |
| $\arcsin x$, $\arccos x$, $\arctan x$ | `\arcsin`, `\arccos`, `\arctan` |
| $\ln x$, $\log_a x$, $\log_2 x$, $\lg x$ | `\ln`, `\log_a`, `\lg` |
| $\exp x$, $e^x$ | `\exp x`, `e^x` |
| $\sinh x$, $\cosh x$ | `\sinh`, `\cosh` |
| $\operatorname{sgn} x$, $\operatorname{rot} \vec{a}$ | `\operatorname{sgn}` |

## Дискретная математика

**Комбинаторика**

| Запись | Команда | Смысл |
|---|---|---|
| $n!$ | `n!` | факториал |
| $P_n = n!$ | `P_n = n!` | перестановки |
| $A_n^k$ | `A_n^k` | размещения |
| $C_n^k = \binom{n}{k}$ | `C_n^k`, `\binom{n}{k}` | сочетания |
| $\bar{C}_n^k$ | `\bar{C}_n^k` | сочетания с повторениями |
| $\binom{n+k-1}{k}$ | `\binom{n+k-1}{k}` | то же через формулу |

**Целочисленное деление:** $a = bq + r$; $q = a \operatorname{div} b$,
$r = a \bmod b$ (команда `\bmod`, без скобок просто `mod`),
$a \equiv b \pmod n$, $n \mid a$ — «$n$ делит $a$» (`\mid`, отрицание `\nmid`).

**Графы**

| Запись | Команда | Смысл |
|---|---|---|
| $G = (V, E)$ | `G = (V, E)` | граф: вершины и рёбра |
| $\lvert V \rvert = n$, $\lvert E \rvert = m$ | `\lvert V \rvert` | число вершин/рёбер |
| $v \sim w$ | `v \sim w` | смежные вершины |
| $e = \{u, v\}$, $(u, v)$ | `e = \{u, v\}` | ребро/дуга |
| $\deg v$, $\deg^{+} v$ | `\deg v` | степень, полустепень исхода |
| $\delta(G)$, $\Delta(G)$ | `\delta(G)`, `\Delta(G)` | min/max степень |
| $N(v)$ | `N(v)` | окрестность вершины |
| $G - v$, $G - e$ | `G - v` | удаление вершины/ребра |
| $G \cong H$ | `G \cong H` | изоморфизм |
| $K_n$, $K_{m,n}$ | `K_n`, `K_{m,n}` | полный, двудольный |
| $C_n$, $P_n$ | `C_n`, `P_n` | цикл, путь |
| $\chi(G)$ | `\chi(G)` | хроматическое число |
| $\omega(G)$ | `\omega(G)` | кликовое число |
| $d(v, w)$, $\operatorname{diam} G$ | `d(v, w)` | расстояние, диаметр |
| $\kappa(G)$ | `\kappa(G)` | вершинная связность |

Путь: $v_0 e_1 v_1 \ldots e_k v_k$; матрица смежности $A(G)$.
Симметрическая разность: $A \triangle B$ (`\triangle`).

**Отношения и функции**

| Запись | Команда | Смысл |
|---|---|---|
| $R \subseteq A \times A$, $x R y$ | `R \subseteq A \times A` | отношение |
| $R^{-1}$, $R \circ S$ | `R^{-1}`, `R \circ S` | обращение, композиция |
| $id_A$ | `id_A` | тождественное отношение |
| $f : A \to B$, $f : a \mapsto b$ | `f : A \to B`, `a \mapsto b` | отображение |
| $f(A)$, $f^{-1}(B)$ | `f(A)`, `f^{-1}(B)` | образ, прообраз |
| $f\vert_X$ | `f\vert_X` | ограничение |
| $\ker \varphi$ | `\ker \varphi` | ядро |
| $\operatorname{Im} f$, $\operatorname{Dom} f$ | `\operatorname{Im}` | образ, область определения |

## Криптография

**Теория чисел**

| Запись | Команда | Смысл |
|---|---|---|
| $a \equiv b \pmod n$ | `a \equiv b \pmod n` | сравнение по модулю |
| $\mathbb{Z}_n$, $\mathbb{Z}_n^{*}$ | `\mathbb{Z}_n` | кольцо вычетов, обратимые элементы |
| $\gcd(a, b)$, $\operatorname{lcm}(a, b)$ | `\gcd(a, b)` | НОД, НОК |
| $a \perp b$ | `a \perp b` | взаимно просты |
| $\varphi(n)$ | `\varphi(n)` | функция Эйлера |
| $\lambda(n)$ | `\lambda(n)` | функция Кармайкла |
| $\mu(n)$ | `\mu(n)` | функция Мёбиуса |
| $\left( \dfrac{a}{p} \right)$ | `\left( \frac{a}{p} \right)` | символ Лежандра/Якоби |
| $\operatorname{ord}_n(a)$ | `\operatorname{ord}_n(a)` | порядок элемента |
| $\log_g h$ | `\log_g h` | дискретный логарифм |
| $g^x \bmod p$ | `g^x \bmod p` | возведение в степень по модулю |
| $\lfloor \log_2 n \rfloor + 1$ | `\lfloor \log_2 n \rfloor + 1` | битовая длина числа |

**Операции**

| Запись | Команда | Смысл |
|---|---|---|
| $a \oplus b$ | `a \oplus b` | XOR |
| $a \odot b$, $a \otimes b$ | `\odot`, `\otimes` | круговые умножения |
| $a \Vert b$ | `a \Vert b` | конкатенация (вне таблиц `\|\|`) |
| $a \wedge b$, $a \vee b$ | `\wedge`, `\vee` | побитовые И, ИЛИ |
| $x \ll k$, $x \gg k$ | `x \ll k`, `x \gg k` | битовые сдвиги |
| $[P]$ | `[P]` | индикатор: 1, если $P$ истинно |

**Схемы и протоколы**

| Запись | Команда | Смысл |
|---|---|---|
| $\operatorname{Gen}(1^{n})$ | `\operatorname{Gen}(1^n)` | генерация ключа |
| $\operatorname{Enc}_k(m)$, $\operatorname{Dec}_k(c)$ | `\operatorname{Enc}_k` | шифрование/расшифрование |
| $(pk, sk)$ | `(pk, sk)` | открытый/секретный ключ |
| $c = m^{e} \bmod n$ | `c = m^{e} \bmod n` | RSA-шифрование |
| $m = c^{d} \bmod n$ | `m = c^{d} \bmod n` | RSA-расшифрование |
| $H : \{0,1\}^{*} \to \{0,1\}^{n}$ | `H : \{0,1\}^{*} \to \{0,1\}^{n}` | хэш-функция |
| $h = H(m \Vert r)$ | `H(m \Vert r)` | хэш с солью |
| $\{m\}_k$ | `\{m\}_k` | шифртекст на ключе $k$ |
| $A \to B : m$ | `A \to B : m` | шаг протокола |
| $\mathcal{A}$ | `\mathcal{A}` | противник (adversary) |

**Вероятностная запись**

| Запись | Команда | Смысл |
|---|---|---|
| $\Pr[A]$, $\Pr[A \mid B]$ | `\Pr[A]`, `\Pr[A \mid B]` | вероятность, условная |
| $x \leftarrow S$ | `x \leftarrow S` | детерминированный выбор из $S$ |
| $x \xleftarrow{\$} S$ | `x \xleftarrow{\$} S` | равновероятный выбор из $S$ |
| $\mathcal{D}$, $\operatorname{Supp}(\mathcal{D})$ | `\mathcal{D}` | распределение, носитель |
| $E[X]$, $\operatorname{Var}[X]$ | `E[X]` | матожидание, дисперсия |
| $\operatorname{negl}(n)$ | `\operatorname{negl}(n)` | пренебрежимая величина |
| $\operatorname{poly}(n)$ | `\operatorname{poly}(n)` | полиномиальная |
| $f = O(g)$, $f = \Theta(g)$, $f = o(g)$ | `f = O(g)` | асимптотика |
| $\stackrel{c}{\approx}$ | `\stackrel{c}{\approx}` | вычислительная неразличимость |
| $\mathbb{P}$, $\mathbb{E}$ | `\mathbb{P}`, `\mathbb{E}` | вероятность, матожидание |

**Группы, кольца, поля**

| Запись | Команда | Смысл |
|---|---|---|
| $(G, \cdot)$, $\mathbb{G}$ | `(G, \cdot)` | группа |
| $\lvert G \rvert$ | `\lvert G \rvert` | порядок группы |
| $\langle g \rangle$ | `\langle g \rangle` | циклическая группа, порождённая $g$ |
| $g^{x}$, $g^{a} h^{b}$ | `g^{x}` | степени элементов |
| $\mathbb{F}_p$, $\operatorname{GF}(q)$ | `\mathbb{F}_p` | конечное поле |
| $\mathbb{F}_{p^{k}}^{*}$ | `\mathbb{F}_{p^{k}}^{*}` | мультипликативная группа поля |
| $\mathbb{Z}[x]$, $\mathbb{F}_p[x]/(f)$ | `\mathbb{F}_p[x]/(f)` | кольца многочленов |
| $\varphi : G \to H$ | `\varphi : G \to H` | гомоморфизм |
| $aH$ | `aH` | смежный класс |
| $E(\mathbb{F}_p)$ | `E(\mathbb{F}_p)` | эллиптическая кривая |
| $P + Q$, $[k]P$ | `[k]P` | операции на кривой |

## Полезные приёмы

Свои операторы: `\operatorname{Enc}`, `\operatorname{ord}` — если команды нет в MathJax, `\operatorname` всегда выручит.

Многострочные выкладки — `aligned`:

$$
\begin{aligned}
c &= m^{e} \bmod n \\
m &= c^{d} \bmod n
\end{aligned}
$$

Система сравнений — `cases`:

$$
\begin{cases}
x \equiv a \pmod n \\
y \equiv b \pmod n
\end{cases}
$$

Вычисления по модулю: $a \cdot b \equiv (a \bmod n)(b \bmod n) \pmod n$.

Малая теорема Ферма: $a^{p-1} \equiv 1 \pmod p$; теорема Эйлера: $a^{\varphi(n)} \equiv 1 \pmod n$.

> **Нюансы Obsidian:** макросы `\N`, `\Z`, `\Q`, `\R`, `\C` MathJax не знает — используйте `\mathbb{...}`. Доллар в тексте экранируется как `\$`. Внутри таблиц избегайте символа `|` даже внутри формул — используйте `\vert`, `\Vert`, `\mid`.
