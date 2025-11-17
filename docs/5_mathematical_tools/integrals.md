# ⚡ Integrals

---

## 📜 The Story Behind Integrals

Long before modern calculus existed, ancient mathematicians were already trying to measure the **area of curved shapes**, the **length of arcs**, and the **volume of irregular solids**.
The Greeks used geometric tricks, but the breakthrough came in the 17th century when two brilliant minds — **Isaac Newton** and **Gottfried Wilhelm Leibniz** — independently discovered the formal method we now call **integration**.

Their idea was revolutionary:
Instead of fighting the complexity of curves, **slice them into infinitely many tiny pieces**, measure each one, and add them up.

This concept became one of the pillars of calculus, allowing us to connect **motion**, **accumulation**, **growth**, and **area** through a single elegant operation.

Today, integrals appear everywhere — physics, engineering, probability, geometry, and any system where something **accumulates** continuously.

---

## 🧠 What Is an Integral?

An **integral** measures the **accumulation** of a quantity.

There are two main ideas:

### **1. Indefinite Integral (Antiderivative)**

It gives a **family of functions** whose derivative is the original function:

$$
\int f(x), dx = F(x) + C
$$

Here:

* (F'(x) = f(x))
* (C) is the constant of integration

### **2. Definite Integral (Area Under the Curve)**

$$
\int_a^b f(x), dx
$$

This represents:

* The **net area** between the curve and the x-axis
* The **total accumulated change** from (x=a) to (x=b)

By the **Fundamental Theorem of Calculus**:

$$
\int_a^b f(x), dx = F(b) - F(a)
$$

Integrals let us compute:

* Area
* Volume
* Work
* Probability
* Charge, mass, energy
* Anything continuous that **adds up** over a region

---

## 💡 Why Integrals Matter

Integrals are essential in:

* Physics (motion, forces, fields, energy)
* Engineering (signals, materials, stress)
* Probability (distributions and expectations)
* Geometry (areas, lengths, volumes)
* Economics (cost, revenue, growth)

They turn **continuous problems** into **mathematical expressions we can compute** — the superhero tool for anything involving accumulation.

---

## 🧒 “Explain It Like I’m 3 Years Old”

Imagine you have a **giant jar** of candy 🍬.
Instead of counting each candy one by one, you **pour a super-thin stream** of candy dust into the jar.

An integral does this:

> It counts all the tiny pieces until you get the total amount.

A curve is like a candy machine:

* Every tiny slice of the curve gives a tiny piece of candy
* Add all slices together = the integral

That’s how we “measure” shapes, movement, and everything that builds up continuously.

---

## ⚙️ Essential Symbols & Formulas for Integrals

| Symbol          | Meaning                                 |
| --------------- | --------------------------------------- |
| **∫**           | Integral sign                           |
| **a, b**        | Lower and upper limits                  |
| **dx**          | Infinitesimally small change in (x)     |
| **F(x)**        | Antiderivative of (f(x))                |
| **C**           | Constant of integration                 |
| **∫ f(x) dx**   | Indefinite integral                     |
| **∫ₐᵇ f(x) dx** | Definite integral from (a) to (b)       |
| **FTC**         | Fundamental Theorem of Calculus         |
| **Area**        | Computed via definite integrals         |
| **Volume**      | Often computed via rotational integrals |

---

### ✅ Core Formulas (GitHub-safe)

#### **Indefinite Integrals**

* Power rule:
  $$
  \int x^n dx = \frac{x^{n+1}}{n+1} + C \quad (n \ne -1)
  $$

* Exponential:
  $$
  \int e^x dx = e^x + C
  $$

* Logarithm:
  $$
  \int \frac{1}{x} dx = \ln |x| + C
  $$

* Trigonometric:
  $$
  \int \sin x, dx = -\cos x + C
  $$
  $$
  \int \cos x, dx = \sin x + C
  $$

* Rational function (basic):
  $$
  \int \frac{1}{x^2} dx = -\frac{1}{x} + C
  $$

---

### **Definite Integrals**

* Fundamental Theorem of Calculus:
  $$
  \int_a^b f(x) dx = F(b) - F(a)
  $$

* Area under a positive function:
  $$
  A = \int_a^b f(x), dx
  $$

* Average value of a function:
  $$
  f_{\text{avg}} = \frac{1}{b-a} \int_a^b f(x), dx
  $$

---

## 📘 Fundamental Techniques & Methods

### ⚡ Integration Methods

* **Substitution** (reverse chain rule):
  $$
  \int f(g(x))g'(x), dx = \int f(u), du
  $$

* **Integration by parts**:
  $$
  \int u, dv = uv - \int v, du
  $$

* **Partial fractions**:
  Break rational functions into simpler pieces.

* **Trigonometric identities**:
  Turn trig products into integrable forms.

* **Improper integrals**:
  Limits used for infinite intervals or vertical asymptotes.

---

## 📐 Useful Geometric Integrals

* Area under a curve:
  $$
  A = \int_a^b f(x), dx
  $$

* Arc length:
  $$
  L = \int_a^b \sqrt{1 + \left(f'(x)\right)^2}, dx
  $$

* Volume by rotation (disk method):
  $$
  V = \pi \int_a^b \left(f(x)\right)^2 dx
  $$

* Volume by washers:
  $$
  V = \pi \int_a^b \left(R(x)^2 - r(x)^2\right) dx
  $$

* Volume by cylindrical shells:
  $$
  V = 2\pi \int_a^b x f(x), dx
  $$

---

### 🧠 Quick Notes

* **Area** is positive even if the function dips below the axis (but integrals give *net* area).
* **Definite integrals never have +C**.
* **Indefinite integrals always include +C**.
* Many integrals rely on spotting patterns or choosing the right method.
* Think of every integral as **adding up infinitely many tiny contributions**.

---

✨ **In short:**
Integrals let us measure **total change**, **area**, **volume**, and anything that accumulates — one infinitesimal piece at a time.

---

# 📘 Ultimate Derivatives & Integrals Table (Must-Know)

Below is your *core toolbox* — the essential formulas every warrior of calculus should master.

---

# 🔥 1. Power Functions

| Function ( f(x) )                 | Derivative ( f'(x) )      | Antiderivative ( F(x) )     |   |       |
| --------------------------------- | ------------------------- | --------------------------- | - | ----- |
| ( x^n )                           | ( nx^{n-1} )              | ( \frac{x^{n+1}}{n+1} + C ) |   |       |
| ( x^{-1} = \frac{1}{x} )          | ( -\frac{1}{x^2} )        | ( \ln                       | x | + C ) |
| ( \sqrt{x} = x^{1/2} )            | ( \frac{1}{2\sqrt{x}} )   | ( \frac{2}{3} x^{3/2} + C ) |   |       |
| ( \frac{1}{\sqrt{x}} = x^{-1/2} ) | ( -\frac{1}{2} x^{-3/2} ) | ( 2\sqrt{x} + C )           |   |       |

---

# 🔥 2. Exponential Functions

| Function  | Derivative      | Antiderivative             |
| --------- | --------------- | -------------------------- |
| ( e^x )   | ( e^x )         | ( e^x + C )                |
| ( a^x )   | ( a^x \ln(a) )  | ( \frac{a^x}{\ln(a)} + C ) |
| ( \ln x ) | ( \frac{1}{x} ) | ( x \ln x - x + C )        |

---

# 🔥 3. Trigonometric Functions

| Function   | Derivative         | Antiderivative  |                 |       |
| ---------- | ------------------ | --------------- | --------------- | ----- |
| ( \sin x ) | ( \cos x )         | ( -\cos x + C ) |                 |       |
| ( \cos x ) | ( -\sin x )        | ( \sin x + C )  |                 |       |
| ( \tan x ) | ( \sec^2 x )       | ( -\ln          | \cos x          | + C ) |
| ( \cot x ) | ( -\csc^2 x )      | ( \ln           | \sin x          | + C ) |
| ( \sec x ) | ( \sec x \tan x )  | ( \ln           | \sec x + \tan x | + C ) |
| ( \csc x ) | ( -\csc x \cot x ) | ( -\ln          | \csc x + \cot x | + C ) |

---

# 🔥 4. Inverse Trigonometric Functions

| Function      | Derivative                  | Antiderivative                         |
| ------------- | --------------------------- | -------------------------------------- |
| ( \arcsin x ) | ( \frac{1}{\sqrt{1-x^2}} )  | ( x\arcsin x + \sqrt{1-x^2} + C )      |
| ( \arccos x ) | ( -\frac{1}{\sqrt{1-x^2}} ) | ( x\arccos x - \sqrt{1-x^2} + C )      |
| ( \arctan x ) | ( \frac{1}{1+x^2} )         | ( x\arctan x - \frac12\ln(1+x^2) + C ) |

---

# 🔥 5. Hyperbolic Functions

| Function    | Derivative          | Antiderivative       |
| ----------- | ------------------- | -------------------- |
| ( \sinh x ) | ( \cosh x )         | ( \cosh x + C )      |
| ( \cosh x ) | ( \sinh x )         | ( \sinh x + C )      |
| ( \tanh x ) | ( \text{sech}^2 x ) | ( \ln(\cosh x) + C ) |

---

# 🔥 6. Logarithmic & Rational Forms

| Form                       | Derivative             | Antiderivative    |                  |       |
| -------------------------- | ---------------------- | ----------------- | ---------------- | ----- |
| ( \ln                      | u                      | )                 | ( \frac{u'}{u} ) | —     |
| ( \frac{1}{ax+b} )         | ( \frac{a}{(ax+b)^2} ) | ( \frac{1}{a}\ln  | ax+b             | + C ) |
| ( \frac{1}{1+x^2} )        | —                      | ( \arctan x + C ) |                  |       |
| ( \frac{1}{\sqrt{1-x^2}} ) | —                      | ( \arcsin x + C ) |                  |       |

---

# 🔥 7. Product & Chain Rule Patterns

(*Must recognize instantly.*)

| Pattern     | Derivative       | Antiderivative              |
| ----------- | ---------------- | --------------------------- |
| ( u^n )     | ( n u^{n-1} u' ) | ( \frac{u^{n+1}}{n+1} + C ) |
| ( e^{u} )   | ( e^{u}u' )      | ( e^{u} + C )               |
| ( \sin(u) ) | ( \cos(u)u' )    | ( -\cos(u) + C )            |
| ( \cos(u) ) | ( -\sin(u)u' )   | ( \sin(u) + C )             |

---

# 🔥 8. Special Must-Know “By Heart” Pairs

Here are *the pairs you absolutely must recall instantly*, Bruce — the mental batarangs.

| Derivative                                     | Primitive                                    |   |       |
| ---------------------------------------------- | -------------------------------------------- | - | ----- |
| ( (x^2)' = 2x )                                | ( \int 2x, dx = x^2 + C )                    |   |       |
| ( (x^3)' = 3x^2 )                              | ( \int 3x^2 dx = x^3 + C )                   |   |       |
| ( (\ln x)' = \frac{1}{x} )                     | ( \int \frac{1}{x} dx = \ln                  | x | + C ) |
| ( (x\ln x - x)' = \ln x )                      | ( \int \ln x, dx = x \ln x - x + C )         |   |       |
| ( (e^x)' = e^x )                               | ( \int e^x dx = e^x + C )                    |   |       |
| ( (\sin x)' = \cos x )                         | ( \int \cos x dx = \sin x + C )              |   |       |
| ( (\cos x)' = -\sin x )                        | ( \int \sin x dx = -\cos x + C )             |   |       |
| ( \left(-\frac{1}{x}\right)' = \frac{1}{x^2} ) | ( \int \frac{1}{x^2} dx = -\frac{1}{x} + C ) |   |       |

---

# 🔥 9. The Top 10 Integrals Everyone Must Know

If you remember nothing else… *remember these*:

1. ( \int x^n dx = \frac{x^{n+1}}{n+1} + C )
2. ( \int e^x dx = e^x + C )
3. ( \int \frac{1}{x} dx = \ln|x| + C )
4. ( \int \sin x dx = -\cos x + C )
5. ( \int \cos x dx = \sin x + C )
6. ( \int \frac{1}{1+x^2} dx = \arctan x + C )
7. ( \int \frac{1}{\sqrt{1-x^2}} dx = \arcsin x + C )
8. ( \int a^x dx = \frac{a^x}{\ln a} + C )
9. ( \int u' \cdot f(u), dx = \int f(u), du ) (substitution key)
10. ( \int u, dv = uv - \int v, du ) (integration by parts)

---
