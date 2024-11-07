$$p(x)=a(x-h)^n+k$$
$$p'(x)=n*a(x-h)^{n-1}$$
ONLY for $x^n$
p'(x) gives slope of p(x) at any point



$$
\frac{d}{dx}ax^n=a*nx^{n-1}
$$




sin
cos
-sin
-cos







---
reference material:
When you find the derivative, you're really finding the instantaneous slope of the original function. 
Or in other words, you're finding the slope of the *tangent* line at a point on the original graph.

You can first approximate the tangent using two secant lines, making $a$ smaller and smaller.
$$
AROC=\frac{f(a+h)-f(a)}{(a+h)-a}
$$
This finds the slope of a secant line, representing the **average rate of change** over the interval $[a,a+h]$.

The **instantaneous rate of change** for $f$ at $a$ where $h$ represents the change from $a$ to $a+h$ is:
$$
f'=IROC=\lim_{h \to 0}\frac{f(x+h)-f(a)}{h}
$$

---
The Derivative of the function OR The Derivative of the point

Derivative is the SLOPE of the tangent line, NOT the tangent line
Derivate is the Limit of the slope equation 



---
$$\lim_{x\to c}\frac{f(x)-f(c)}{x-c}$$

$\Delta x$ form
$$\lim_{x\to \Delta x}\frac{f(x+\Delta x)-f(x)}{\Delta x}$$
$h$ form
**forward difference** quotient
$$\lim_{h\to 0}\frac{f(x+h)-f(x)}{h}$$
**backward difference** quotient
$$\lim_{h\to 0}\frac{f(x)-f(x-h)}{h}$$
**symmetric difference** quotient
$$\lim_{h\to 0}\frac{f(x+h)-f(x-h)}{2h}$$
