# **hw01c**

## 1.20.2
Use the binomial expansion to derive the following results for values of $$v\ll{c}$$ and use when applicable in the problems that follow in this section.
$$
    \frac{1}{\gamma}\approx1-\frac{1}{2}\frac{v^2}{c^2}
$$

#### 1.20.2
$$
    \frac{1}{\gamma}=\sqrt{1-\left(\frac{\mathbf{V}}{c}\right)^2};
$$
######BINOMIAL EXPENSION:
$$
    \begin{align*}
    f(\epsilon)&=f(0)+\frac{f'(0)\epsilon^1}{1!}+\frac{f''(0)\epsilon^2}{2!}+\cdots\\
    &\left<\frac{1}{\gamma}=f(\epsilon)=\left[1-\epsilon\right]^{\frac{1}{2}},\right>\\
    &\left<\epsilon=\frac{\mathbf{V}^2}{c^2},\:\:\:\:\epsilon'\approx\epsilon''\approx\epsilon\right>\\
    \end{align*}
    
$$
$$
    \left\{\begin{align*}
    f(0)&=\left[1-(0)\right]^{\frac{1}{2}}=1;\\
    f'(\epsilon)&=\left(\frac{1}{2}\right)\left(1-(\epsilon)\right)^{-\frac{1}{2}}(-1);&f'(0)&=\left(\frac{1}{2}\right)(-1)=-\frac{1}{2};\\
    f''(\epsilon)&=\left(\frac{1}{2}\right)\left(-\frac{1}{2}\right)\left(1-(\epsilon)\right)^{-\frac{3}{2}}(-1);&f''(0)&=\left(-\frac{1}{4}\right)(-1)=\frac{1}{4};\\
    \vdots&
    \end{align*}\right\}
$$
$$
    \begin{align*}
    \gamma&\approx1+\frac{\left(-\frac{1}{2}\right)}{1!}\epsilon+\frac{\left(\frac{1}{4}\right)}{2!}\epsilon^2+\cdots+\\
    &=1-\frac{1}{2}\epsilon+\frac{1}{8}\epsilon^2+\cdots,&\left<\epsilon=\frac{\mathbf{V}^2}{c^2}\right>\\
    &=1-\frac{1}{2}\left(\frac{\mathbf{V}^2}{c^2}\right)
    +\frac{1}{8}\left(\frac{\mathbf{V}^2}{c^2}\right)^2+\cdots\\
    &\approx1-\frac{1}{2}\left(\frac{\mathbf{V}^2}{c^2}\right)
    \end{align*}
$$

