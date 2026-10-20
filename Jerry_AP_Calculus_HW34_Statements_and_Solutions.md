# AP Calculus AB — Homework #34

**Textbook:** James Stewart, *Calculus*, 8th ed.  
**Due:** Wednesday, October 21, 2026  
**Assigned:** pp. 192–194: #1–4, 6, 11–27 odd; p. 198: #74, #75, #83(a). **17 problems total.**

> **Accuracy note:** The statements below are *paraphrases*, reconstructed from our earlier homework discussion and previous guide—not verbatim textbook text. Except for #6, they have **not been checked against photographs of the assigned edition's pages**. In particular, #19 and #21 are unknown; their solutions cannot be determined reliably without the textbook. Verify the other problem data against the book. Problem #83(a) uses **3x** inside the root, as specified in the assignment.

## p. 192 — #1

**Problem (unverified paraphrase):** Find the linearization of $f(x)=x^3-x^2+3$ at $a=-2$.

**Solution.** The linearization formula is $L(x)=f(a)+f'(a)(x-a)$.

$$f(-2)=-8-4+3=-9,\qquad f'(x)=3x^2-2x,\qquad f'(-2)=16.$$

$$\boxed{L(x)=-9+16(x+2)=16x+23}$$

## p. 192 — #2

**Problem (unverified paraphrase):** Find the linearization of $f(x)=\sin x$ at $a=\pi/6$.

**Solution.** $f'(x)=\cos x$, $f(\pi/6)=1/2$, and $f'(\pi/6)=\sqrt3/2$.

$$\boxed{L(x)=\frac12+\frac{\sqrt3}{2}\left(x-\frac{\pi}{6}\right)}$$

## p. 192 — #3

**Problem (unverified paraphrase):** Find the linearization of $f(x)=\sqrt x$ at $a=4$.

**Solution.** $f'(x)=1/(2\sqrt x)$, so $f(4)=2$ and $f'(4)=1/4$.

$$\boxed{L(x)=2+\frac14(x-4)=\frac x4+1}$$

## p. 192 — #4

**Problem (unverified paraphrase):** Find the linearization of $f(x)=\dfrac{2}{\sqrt{x^2-5}}$ at $a=3$.

**Solution.** Write $f(x)=2(x^2-5)^{-1/2}$. By the chain rule,

$$f'(x)=2\left(-\frac12\right)(x^2-5)^{-3/2}(2x)=-\frac{2x}{(x^2-5)^{3/2}}.$$

At $x=3$: $f(3)=2/2=1$ and $f'(3)=-6/8=-3/4$.

$$\boxed{L(x)=1-\frac34(x-3)}$$

*Verify the printed function; an earlier third-party answer was inconsistent with the numerator 2.*

## p. 192 — #6

**Problem (paraphrased from our earlier verified discussion):** For $g(x)=\sqrt[3]{1+x}$ at $a=0$, find the linear approximation and use it to estimate $\sqrt[3]{0.95}$ and $\sqrt[3]{1.1}$. Sketch the curve and tangent line.

**Solution.** Write $g(x)=(1+x)^{1/3}$. Then

$$g'(x)=\frac13(1+x)^{-2/3},\qquad g(0)=1,\qquad g'(0)=\frac13.$$

The tangent line at $(0,1)$ is

$$\boxed{L(x)=1+\frac{x}{3}}.$$

For $\sqrt[3]{0.95}$, take $x=-0.05$:

$$\boxed{\sqrt[3]{0.95}\approx L(-0.05)=1-\frac{0.05}{3}\approx0.98333.}$$

For $\sqrt[3]{1.1}$, take $x=0.1$:

$$\boxed{\sqrt[3]{1.1}\approx L(0.1)=1+\frac{0.1}{3}\approx1.03333.}$$

**Graph instruction:** Plot $y=\sqrt[3]{1+x}$ and its tangent $y=1+x/3$ on the same axes. They meet at $(0,1)$ and are close near $x=0$.

## p. 193 — #11

**Problem (unverified paraphrase):** Find the differentials for (a) $y=(x^2-3)^{-2}$ and (b) $y=\sqrt{1-t^4}$.

**Solution (a).** Chain rule:

$$y'=-2(x^2-3)^{-3}(2x)=-\frac{4x}{(x^2-3)^3}.$$

$$\boxed{dy=-\frac{4x}{(x^2-3)^3}\,dx}$$

**Solution (b).**

$$\frac{dy}{dt}=\frac12(1-t^4)^{-1/2}(-4t^3)=-\frac{2t^3}{\sqrt{1-t^4}}.$$

$$\boxed{dy=-\frac{2t^3}{\sqrt{1-t^4}}\,dt}$$

## p. 193 — #13

**Problem (unverified paraphrase):** Find the differentials for (a) $y=\tan(\sqrt t)$ and (b) $y=\dfrac{1-v^2}{1+v^2}$.

**Solution (a).** By the chain rule,

$$\frac{dy}{dt}=\sec^2(\sqrt t)\cdot\frac{1}{2\sqrt t},\qquad\boxed{dy=\frac{\sec^2(\sqrt t)}{2\sqrt t}\,dt}.$$

**Solution (b).** By the quotient rule,

$$\frac{dy}{dv}=\frac{(-2v)(1+v^2)-(1-v^2)(2v)}{(1+v^2)^2}=-\frac{4v}{(1+v^2)^2}.$$

$$\boxed{dy=-\frac{4v}{(1+v^2)^2}\,dv}$$

## p. 193 — #15

**Problem (unverified paraphrase):** Find $dy$ for $y=\tan x$, then evaluate when $x=\pi/4$ and $dx=-0.1$.

**Solution.** $dy=\sec^2x\,dx$. Since $\sec^2(\pi/4)=2$,

$$\boxed{dy=2(-0.1)=-0.2}$$

## p. 193 — #17

**Problem (unverified paraphrase):** Find $dy$ for $y=\sqrt{3+x^2}$, then evaluate when $x=1$ and $dx=-0.1$.

**Solution.**

$$dy=\frac12(3+x^2)^{-1/2}(2x)\,dx=\frac{x}{\sqrt{3+x^2}}\,dx.$$

At $x=1$, $dy=(1/2)(-0.1)$, so

$$\boxed{dy=-0.05}$$

## p. 193 — #19

**Problem statement:** **Not yet verified.** The function and specified values were absent from the earlier source.

**Solution method only (not a numerical answer):** If it asks for actual change and differential change, calculate

$$\boxed{\Delta y=f(x+\Delta x)-f(x)}\qquad\text{and}\qquad\boxed{dy=f'(x)\,\Delta x}.$$

The exact answer requires the printed question.

## p. 193 — #21

**Problem statement:** **Not yet verified.** The function or approximation target was absent from the earlier source.

**Solution method only (not a numerical answer):** Choose a convenient nearby $a$ and use

$$\boxed{f(x)\approx f(a)+f'(a)(x-a)}.$$

The exact answer requires the printed question.

## p. 193 — #23

**Problem (unverified paraphrase):** Estimate $(1.999)^4$ using a linear approximation.

**Solution.** Set $f(x)=x^4$, $a=2$, $dx=-0.001$. Then $f(2)=16$, $f'(x)=4x^3$, and $f'(2)=32$.

$$f(1.999)\approx16+32(-0.001)=\boxed{15.968}.$$

## p. 193 — #25

**Problem (unverified paraphrase):** Approximate $\sqrt[3]{1001}$ by linearization near $1000$.

**Solution.** Take $f(x)=x^{1/3}$, $a=1000$, $dx=1$.

$$f(1000)=10,\qquad f'(x)=\frac{1}{3x^{2/3}},\qquad f'(1000)=\frac1{300}.$$

$$\boxed{\sqrt[3]{1001}\approx10+\frac1{300}\approx10.00333}$$

## p. 193 — #27

**Problem (unverified paraphrase):** Use linear approximation to estimate $\tan(2^\circ)$.

**Solution.** Near $x=0$ radians, $f(x)=\tan x$ has $f(0)=0$, $f'(0)=\sec^2(0)=1$. Thus $\tan x\approx x$ for small $x$ in radians. Convert $2^\circ$ to $\pi/90$ radians:

$$\boxed{\tan(2^\circ)\approx\frac\pi{90}\approx0.03491}$$

## p. 198 — #74

**Problem (unverified paraphrase):** For the cone-volume formula $V=\dfrac\pi3r^2h$, determine sensitivity to height (fixed radius) and radius (fixed height).

**Solution.** Treat the other quantity as a constant in each derivative:

$$\boxed{\frac{dV}{dh}=\frac\pi3r^2\quad (r\text{ fixed})}$$

$$\boxed{\frac{dV}{dr}=\frac{2\pi}{3}rh\quad (h\text{ fixed})}$$

*The original question's actual subparts may differ; check page 198.*

## p. 198 — #75

**Problem (unverified paraphrase):** A rod's mass up to distance $x$ is $m(x)=x(1+\sqrt x)$. Find the linear density at $x=4$.

**Solution.** Expand $m(x)=x+x^{3/2}$ and differentiate:

$$\rho(x)=m'(x)=1+\frac32\sqrt x.$$

At $x=4$,

$$\boxed{\rho(4)=1+\frac32(2)=4}$$

Units are mass per unit length (e.g. kg/m if mass is in kg and distance in m).

## p. 198 — #83(a)

**Problem (unverified paraphrase incorporating the teacher's correction):** Linearize $f(x)=\sqrt[3]{1+3x}$ at $x=0$ and approximate $\sqrt[3]{1.03}$. **The radicand contains $3x$, not $x$.**

**Solution.**

$$f'(x)=\frac13(1+3x)^{-2/3}\cdot3=(1+3x)^{-2/3}.$$

Since $f(0)=1$ and $f'(0)=1$,

$$\boxed{L(x)=1+x}.$$

For $\sqrt[3]{1.03}$, solve $1+3x=1.03$, giving $x=0.01$. Hence

$$\boxed{\sqrt[3]{1.03}\approx L(0.01)=1.01}.$$

---

## Formula reminder

- **Linearization:** $L(x)=f(a)+f'(a)(x-a)$.
- **Differential:** $dy=f'(x)\,dx$.
- **Actual change:** $\Delta y=f(x+\Delta x)-f(x)$.
- **Small-change approximation:** $\Delta y\approx dy$.

**Verification still needed:** Compare all reconstructed statements to the assigned textbook pages, especially #4, #11–27, #74–75 and #83(a). Complete #19 and #21 only after seeing their original statements.
