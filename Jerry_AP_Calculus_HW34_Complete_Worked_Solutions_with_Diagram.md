# AP Calculus AB — Homework #34

**Textbook:** James Stewart, *Calculus*, 8th Edition  
**Due:** Wednesday, October 21, 2026  
**Assigned:** pp. 192–194: #1–4, 6, 11–27 odd; p. 198: #74, 75, 83(a)  
**Total:** 17 problems

> **Source note:** The problem statements below are paraphrases compiled from our previous homework discussions, not verbatim reproductions of the textbook. Some statements were reconstructed from secondary references and have not been independently verified against photos of Jerry's exact edition; check against the printed exercises. In particular, **#83(a) has the teacher's correction: `3x` inside the cube root, not `x`**. This guide retains the problems and solutions as previously discussed.

## Quick answer index

| Exercise | Final result |
|---|---|
| #1 | $L(x)=16x+23$ |
| #2 | $L(x)=\frac12+\frac{\sqrt3}{2}(x-\frac\pi6)$ |
| #3 | $L(x)=2+\frac14(x-4)=\frac x4+1$ |
| #4 | $L(x)=1-\frac34(x-3)$ |
| #6 | $L(x)=1+\frac x3$; estimates $0.98333$, $1.03333$ |
| #11 | (a) $dy=-\frac{4x}{(x^2-3)^3}dx$; (b) $dy=-\frac{2t^3}{\sqrt{1-t^4}}dt$ |
| #13 | (a) $dy=\frac{\sec^2\sqrt t}{2\sqrt t}dt$; (b) $dy=-\frac{4v}{(1+v^2)^2}dv$ |
| #15 | $dy=\sec^2x\,dx$; at given values $dy=-0.2$ |
| #17 | $dy=\frac{x}{\sqrt{3+x^2}}dx$; at given values $dy=-0.05$ |
| #19 | $\Delta y=1.25$, $dy=1$ |
| #21 | $\Delta y=\sqrt{1.8}-1\approx0.34164$, $dy=0.4$ |
| #23 | $(1.999)^4\approx15.968$ |
| #25 | $\sqrt[3]{1001}\approx10.00333$ |
| #27 | $\tan2^\circ\approx\pi/90\approx0.03491$ |
| #74 | (a) $\partial V/\partial h=\pi r^2/3$; (b) $\partial V/\partial r=2\pi rh/3$ |
| #75 | $\rho(4)=4\text{ kg/m}$ |
| #83(a) | $L(x)=1+x$; $\sqrt[3]{1.03}\approx1.01$ |

---

## Problem 1 — p. 192

**Problem statement (paraphrased).** Find the linearization $L(x)$ of $f(x)=x^3-x^2+3$ at $a=-2$.

**Step-by-step solution**

1. Start with $L(x)=f(a)+f'(a)(x-a)$.
2. Evaluate the function: $f(-2)=(-2)^3-(-2)^2+3=-8-4+3=-9$.
3. Differentiate: $f'(x)=3x^2-2x$.
4. Evaluate the slope: $f'(-2)=3(4)-2(-2)=16$.
5. Substitute: $L(x)=-9+16(x+2)=16x+23$.

**Final answer:** $\boxed{L(x)=16x+23}$, or $\boxed{L(x)+9=16(x+2)}$ in point-slope form.

**Key concept:** Linearization is the tangent line at $x=a$. Its slope is $f'(a)$, and it passes through $(a,f(a))$.

---

## Problem 2 — p. 192

**Problem statement (paraphrased).** Find the linearization $L(x)$ of $f(x)=\sin x$ at $a=\pi/6$.

**Step-by-step solution**

1. Formula: $L(x)=f(a)+f'(a)(x-a)$.
2. Function value: $f(\pi/6)=\sin(\pi/6)=1/2$.
3. Derivative: $f'(x)=\cos x$.
4. Slope: $f'(\pi/6)=\cos(\pi/6)=\sqrt3/2$.
5. Assemble: $L(x)=\frac12+\frac{\sqrt3}{2}\left(x-\frac\pi6\right)$.

**Final answer:** $\boxed{L(x)=\frac12+\frac{\sqrt3}{2}(x-\frac\pi6)}$.

**Key concept:** Use exact unit-circle values and radians when differentiating trigonometric functions.

---

## Problem 3 — p. 192

**Problem statement (paraphrased).** Find the linearization $L(x)$ of $f(x)=\sqrt{x}$ at $a=4$.

**Step-by-step solution**

1. Formula: $L(x)=f(a)+f'(a)(x-a)$.
2. Function value: $f(4)=\sqrt4=2$.
3. Differentiate: $f(x)=x^{1/2}$, so $f'(x)=\frac12x^{-1/2}=\frac1{2\sqrt{x}}$.
4. Slope: $f'(4)=1/(2\cdot2)=1/4$.
5. Assemble: $L(x)=2+\frac14(x-4)=\frac x4+1$.

**Final answer:** $\boxed{L(x)=2+\frac14(x-4)=\frac x4+1}$.

**Key concept:** Rewrite radicals as fractional powers to differentiate quickly.

---

## Problem 4 — p. 192

**Problem statement (paraphrased).** Find the linearization of $f(x)=\dfrac{2}{\sqrt{x^2-5}}$ at $a=3$.

**Step-by-step solution**

1. Formula: $L(x)=f(a)+f'(a)(x-a)$.
2. Evaluate: $f(3)=\frac2{\sqrt{9-5}}=1$.
3. Rewrite: $f(x)=2(x^2-5)^{-1/2}$.
4. Apply the chain rule: $f'(x)=2(-\frac12)(x^2-5)^{-3/2}(2x)=-\dfrac{2x}{(x^2-5)^{3/2}}$.
5. Slope: $f'(3)=-\frac6{4^{3/2}}=-\frac68=-\frac34$.
6. Assemble: $L(x)=1-\frac34(x-3)=\frac{13}4-\frac{3x}4$.

**Final answer:** $\boxed{L(x)=1-\frac34(x-3)}$.

**Key concept:** Do not forget the inner derivative $\frac{d}{dx}(x^2-5)=2x$. Missing it gives a wrong tangent-line slope.

---

## Problem 6 — p. 192

**Problem statement (paraphrased).** Find the linear approximation of $g(x)=\sqrt[3]{1+x}$ at $a=0$. Estimate $\sqrt[3]{0.95}$ and $\sqrt[3]{1.1}$, and compare the curve with its tangent line.

**Step-by-step solution**

1. Write $g(x)=(1+x)^{1/3}$ and $L(x)=g(0)+g'(0)x$.
2. Function value: $g(0)=1$.
3. Chain rule: $g'(x)=\frac13(1+x)^{-2/3}$, hence $g'(0)=1/3$.
4. Linearization: $L(x)=1+x/3$.
5. For $\sqrt[3]{0.95}$, solve $1+x=0.95$ so $x=-0.05$: $L(-0.05)=1-0.05/3\approx0.98333$.
6. For $\sqrt[3]{1.1}$, take $x=0.1$: $L(0.1)=1+0.1/3\approx1.03333$.
7. To sketch: draw $y=(1+x)^{1/3}$ and the tangent line $y=1+x/3$. They touch at $(0,1)$; near that point the line closely follows the curve.

**Final answers:** $\boxed{L(x)=1+\frac x3}$; $\boxed{\sqrt[3]{0.95}\approx0.98333}$; $\boxed{\sqrt[3]{1.1}\approx1.03333}$.

**Key concept:** A tangent-line estimate is most accurate close to the point of tangency ($x=0$ here).

---

## Problem 11 — p. 193

**Problem statement (paraphrased).** Find the differential $dy$ for (a) $y=(x^2-3)^{-2}$ and (b) $y=\sqrt{1-t^4}$.

### Part (a)

1. Formula: $dy=\frac{dy}{dx}\,dx$.
2. Differentiate with the chain rule: $\frac{dy}{dx}=-2(x^2-3)^{-3}(2x)$.
3. Simplify: $\frac{dy}{dx}=-4x(x^2-3)^{-3}$.
4. Multiply by $dx$: $\boxed{dy=-\frac{4x}{(x^2-3)^3}\,dx}$.

### Part (b)

1. Rewrite: $y=(1-t^4)^{1/2}$.
2. Differentiate: $\frac{dy}{dt}=\frac12(1-t^4)^{-1/2}(-4t^3)$.
3. Simplify: $\frac{dy}{dt}=-\dfrac{2t^3}{\sqrt{1-t^4}}$.
4. Multiply by $dt$: $\boxed{dy=-\frac{2t^3}{\sqrt{1-t^4}}\,dt}$.

**Key concept:** A differential is the derivative *times the differential of the independent variable*. For a function of $t$, the final answer contains $dt$, not $dx$.

---

## Problem 13 — p. 193

**Problem statement (paraphrased).** Find the differential $dy$ for (a) $y=\tan\sqrt{t}$ and (b) $y=\dfrac{1-v^2}{1+v^2}$.

### Part (a)

1. Start with $dy=(dy/dt)dt$.
2. Set $u=\sqrt t$, so $u'=1/(2\sqrt t)$.
3. Apply the chain rule to $\tan u$: $dy/dt=\sec^2(\sqrt t)\cdot1/(2\sqrt t)$.
4. Final: $\boxed{dy=\frac{\sec^2(\sqrt t)}{2\sqrt t}\,dt}$.

### Part (b)

1. Let $N=1-v^2$ and $D=1+v^2$. Then $N'=-2v$ and $D'=2v$.
2. Quotient rule: $dy/dv=\frac{N'D-ND'}{D^2}=\frac{(-2v)(1+v^2)-(1-v^2)(2v)}{(1+v^2)^2}$.
3. Expand: numerator $=-2v-2v^3-2v+2v^3=-4v$.
4. Final: $\boxed{dy=-\frac{4v}{(1+v^2)^2}\,dv}$.

**Key concept:** Part (a) requires the chain rule and part (b) the quotient rule. Always include the matching differential ($dt$ or $dv$).

---

## Problem 15 — p. 193

**Problem statement (paraphrased).** For $y=\tan x$, (a) find $dy$ and (b) evaluate it when $x=\pi/4$ and $dx=-0.1$.

**Step-by-step solution**

1. $dy=y'\,dx$.
2. Since $y'=\sec^2x$, **(a)** $\boxed{dy=\sec^2x\,dx}$.
3. At $x=\pi/4$, $\sec^2(\pi/4)=2$.
4. With $dx=-0.1$, $dy=2(-0.1)=-0.2$.

**Final answer (b):** $\boxed{dy=-0.2}$.

**Key concept:** $dy$ estimates the change in $y$. A negative $dx$ produces a negative $dy$ when the local slope is positive.

---

## Problem 17 — p. 193

**Problem statement (paraphrased).** For $y=\sqrt{3+x^2}$, (a) find $dy$ and (b) evaluate it at $x=1$, $dx=-0.1$.

**Step-by-step solution**

1. Rewrite: $y=(3+x^2)^{1/2}$.
2. Chain rule: $y'=\frac12(3+x^2)^{-1/2}(2x)=\frac{x}{\sqrt{3+x^2}}$.
3. **(a)** $\boxed{dy=\frac{x}{\sqrt{3+x^2}}\,dx}$.
4. At $x=1$, $y'=1/\sqrt4=1/2$.
5. Multiply by $dx=-0.1$: **(b)** $\boxed{dy=-0.05}$.

**Key concept:** The differential $dy=f'(x)dx$ gives a local *estimate*, not necessarily the exact change $\Delta y$.

---

## Problem 19 — p. 193

**Problem statement (paraphrased).** For $y=x^2-4x$, $x=3$, and $dx=\Delta x=0.5$, calculate $\Delta y$ and $dy$. Sketch $dx$, $dy$, and $\Delta y$.

**Step-by-step solution**

1. Actual change: $\Delta y=f(x+\Delta x)-f(x)$.
2. Calculate $f(3)=9-12=-3$.
3. Calculate $f(3.5)=3.5^2-4(3.5)=12.25-14=-1.75$.
4. Thus $\boxed{\Delta y=-1.75-(-3)=1.25}$.
5. Differential: $f'(x)=2x-4$, so $f'(3)=2$.
6. Thus $\boxed{dy=f'(3)dx=2(0.5)=1}$.
7. Sketch: from $x=3$ move horizontally by $dx=0.5$. The tangent line rises by $dy=1$; the actual curve rises by $\Delta y=1.25$.

**Final answers:** $\boxed{\Delta y=1.25,\quad dy=1}$.

**Key concept:** The upward-curving graph (concave up) lies above its tangent line nearby, so $dy$ underestimates $\Delta y$ in this example.

---

## Problem 21 — p. 193

**Problem statement (paraphrased).** For $y=\sqrt{x-2}$, $x=3$, and $dx=\Delta x=0.8$, calculate $\Delta y$ and $dy$. Sketch the changes.

**Step-by-step solution**

1. Actual change: $\Delta y=f(3.8)-f(3)$.
2. $f(3)=\sqrt{1}=1$ and $f(3.8)=\sqrt{1.8}$.
3. Thus $\boxed{\Delta y=\sqrt{1.8}-1\approx0.34164}$.
4. Differentiate: $f'(x)=\frac1{2\sqrt{x-2}}$.
5. At $x=3$, $f'(3)=1/2$.
6. Differential: $\boxed{dy=\frac12(0.8)=0.4}$.
7. Sketch: from $x=3$ move horizontally by $0.8$. The curve rises by about $0.34164$, but its tangent line rises by $0.4$.

**Diagram for Problem 21**

```svg
<svg viewBox="0 0 340 235" width="100%" xmlns="http://www.w3.org/2000/svg">
  <line x1="28" y1="208" x2="323" y2="208" stroke="currentColor" opacity=".5" />
  <line x1="28" y1="208" x2="28" y2="15" stroke="currentColor" opacity=".5" />
  <path d="M36 190 Q78 151 130 121 Q203 91 307 75" stroke="#2563eb" fill="none" stroke-width="2.8" />
  <line x1="76" y1="151" x2="307" y2="38" stroke="#d97706" stroke-width="2.4" />
  <circle cx="130" cy="121" r="4" fill="#2563eb" />
  <line x1="130" y1="121" x2="264" y2="121" stroke="currentColor" opacity=".4" stroke-dasharray="4 4" />
  <line x1="130" y1="121" x2="130" y2="208" stroke="currentColor" opacity=".4" stroke-dasharray="4 4" />
  <line x1="264" y1="121" x2="264" y2="208" stroke="currentColor" opacity=".4" stroke-dasharray="4 4" />
  <line x1="264" y1="121" x2="264" y2="56" stroke="#d97706" stroke-width="3" />
  <line x1="277" y1="121" x2="277" y2="82" stroke="#2563eb" stroke-width="3" />
  <line x1="130" y1="190" x2="264" y2="190" stroke="#64748b" stroke-width="2" />
  <text x="185" y="184" font-size="11" fill="currentColor">dx = 0.8</text>
  <text x="130" y="222" text-anchor="middle" font-size="11" fill="currentColor">3</text>
  <text x="264" y="222" text-anchor="middle" font-size="11" fill="currentColor">3.8</text>
  <text x="269" y="47" font-size="11" fill="#d97706">dy</text>
  <text x="282" y="79" font-size="11" fill="#2563eb">Δy</text>
  <text x="47" y="29" font-size="11" fill="#2563eb">Function</text>
  <text x="47" y="44" font-size="11" fill="#d97706">Tangent line</text>
</svg>
```

**Final answers:** $\boxed{\Delta y\approx0.34164,\quad dy=0.4}$.

**Key concept:** $\sqrt{x-2}$ is concave down for $x>2$, so its tangent line lies above the nearby curve and overestimates the rise.

---

## Problem 23 — p. 193

**Problem statement (paraphrased).** Estimate $(1.999)^4$ using linear approximation or differentials.

**Step-by-step solution**

1. Choose $f(x)=x^4$ and nearby convenient $a=2$.
2. Evaluate $f(2)=16$.
3. Differentiate: $f'(x)=4x^3$, so $f'(2)=32$.
4. Linearization: $L(x)=16+32(x-2)$.
5. Substitute $x=1.999$: $L(1.999)=16+32(-0.001)=15.968$.

**Final answer:** $\boxed{(1.999)^4\approx15.968}$.

**Key concept:** Choose a nearby value with easy arithmetic (here, $2^4$), then adjust using the derivative times the small change.

---

## Problem 25 — p. 193

**Problem statement (paraphrased).** Estimate $\sqrt[3]{1001}$ using linear approximation or differentials.

**Step-by-step solution**

1. Choose $f(x)=x^{1/3}$ and $a=1000$ (a perfect cube).
2. $f(1000)=10$.
3. Differentiate: $f'(x)=\frac13x^{-2/3}=1/(3x^{2/3})$.
4. At $a=1000$, $f'(1000)=1/(3\cdot100)=1/300$.
5. Linearization: $L(x)=10+\frac{x-1000}{300}$.
6. Evaluate: $L(1001)=10+1/300\approx10.00333$.

**Final answer:** $\boxed{\sqrt[3]{1001}\approx10.00333}$.

**Key concept:** Recognizing a nearby perfect cube makes the base value and derivative easy to compute.

---

## Problem 27 — p. 193

**Problem statement (paraphrased).** Estimate $\tan 2^\circ$ using linear approximation or differentials.

**Step-by-step solution**

1. Choose $f(x)=\tan x$ and $a=0$.
2. Convert degrees to radians: $2^\circ=2\pi/180=\pi/90$.
3. Compute $f(0)=0$.
4. Derivative: $f'(x)=\sec^2x$, so $f'(0)=1$.
5. Linearization: $L(x)=0+1(x-0)=x$.
6. Approximation: $\tan2^\circ\approx L(\pi/90)=\pi/90\approx0.03491$.

**Final answer:** $\boxed{\tan2^\circ\approx\pi/90\approx0.03491}$.

**Key concept:** The small-angle rule $\tan x\approx x$ requires **radians**, not degrees.

---

## Problem 74 — p. 198

**Problem statement (paraphrased from our earlier discussion; verify in the printed text).** For a right circular cone with volume $V=\frac13\pi r^2h$, (a) differentiate with respect to height $h$, holding radius $r$ constant, and (b) differentiate with respect to radius $r$, holding $h$ constant.

**Step-by-step solution**

**(a) With respect to $h$:**

1. Write $V=(\pi r^2/3)h$.
2. Hold $r$ constant, so $\pi r^2/3$ is a constant coefficient.
3. Differentiate: $\boxed{\frac{\partial V}{\partial h}=\frac13\pi r^2}$.

**(b) With respect to $r$:**

1. Write $V=(\pi h/3)r^2$.
2. Hold $h$ constant.
3. Power rule: $\frac{\partial V}{\partial r}=\frac{\pi h}{3}(2r)$.
4. Simplify: $\boxed{\frac{\partial V}{\partial r}=\frac23\pi rh}$.

**Key concept:** Differentiate with respect to the requested variable while treating the other independent variable as constant. The partial derivative symbol $\partial$ expresses that explicitly.

---

## Problem 75 — p. 198

**Problem statement (paraphrased).** A rod's mass in kilograms as a function of its length $x$ in meters is $m=x(1+\sqrt x)$. Find its linear density at $x=4$ m.

**Step-by-step solution**

1. Linear density is the rate of change of mass with length: $\rho(x)=dm/dx$.
2. Expand the function: $m=x+x^{3/2}$.
3. Differentiate: $\frac{dm}{dx}=1+\frac32x^{1/2}=1+\frac32\sqrt x$.
4. Evaluate at $x=4$: $\rho(4)=1+\frac32(2)=4$.

**Final answer:** $\boxed{\rho(4)=4\text{ kg/m}}$.

**Key concept:** A derivative can represent a physical rate (kilograms per meter here). Density at a point is *not* the total mass of the rod.

---

## Problem 83(a) — p. 198 — teacher-corrected expression

**Problem statement (paraphrased; teacher's correction applied).** Find the linear approximation of $f(x)=\sqrt[3]{1+3x}$ at $a=0$ and use it to estimate $\sqrt[3]{1.03}$.

> **Correction:** The radicand is **$1+3x$**, not $1+x$.

**Step-by-step solution**

1. Rewrite $f(x)=(1+3x)^{1/3}$ and use $L(x)=f(0)+f'(0)x$.
2. Compute $f(0)=1$.
3. Chain rule: $f'(x)=\frac13(1+3x)^{-2/3}\cdot3=(1+3x)^{-2/3}$.
4. Compute $f'(0)=1$.
5. Linearization: $\boxed{L(x)=1+x}$.
6. To estimate $\sqrt[3]{1.03}$, solve $1+3x=1.03$, obtaining $x=0.01$.
7. Evaluate $L(0.01)=1.01$.

**Final answers:** $\boxed{L(x)=1+x}$ and $\boxed{\sqrt[3]{1.03}\approx1.01}$.

**Key concept:** The derivative of the inside, $3$, cancels the $1/3$ from the power rule. The input shift for $1.03$ is **$x=0.01$**, not $0.03$.

---

## Essential formulas to review

1. **Linearization:** $L(x)=f(a)+f'(a)(x-a)$.
2. **Differential:** $dy=f'(x)\,dx$ (or $dy=f'(t)\,dt$, etc.).
3. **Exact change:** $\Delta y=f(x+\Delta x)-f(x)$.
4. **Approximation:** $\Delta y\approx dy$ for small $\Delta x=dx$.
5. **Chain rule:** $\frac{d}{dx}[u(x)]^n=n[u(x)]^{n-1}u'(x)$.
6. **Quotient rule:** $(u/v)'=(u'v-uv')/v^2$.
7. **Useful trig derivatives:** $(\tan x)'=\sec^2x$ and $(\sin x)'=\cos x$ (in radians).
8. **Concavity and tangent-line error:** locally, a concave-up graph lies above its tangent line; a concave-down graph lies below it.

