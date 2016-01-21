# **hw01b**

## 1.13
Suppose that an event occurs in inertial frame $$S$$ with coordinates $$x=75\:m$$, $$y=18\:m$$, $$z=4.0\:m$$ at $$t=2.0\times10^{-5}\:s$$.  The inertial frame $$S’$$ moves in the $$+x$$ direction with $$v=0.85c$$.  The origins of $$S$$ and $$S'$$ coincided at $$t=t'=0$$.  
1. What are the coordinates of the event in $$S’$$?  
2. Use the inverse transformation on the results of (1) to obtain the original coordinates.

#### 1.13.1
$$
    \begin{align*}
    \underset{\text{Lorentz Transformation}}{
    \begin{cases}
    x'=\gamma(x-\mathbf{V}t);\\
    y'=y;\\
    z'=z;\\
    t'=\gamma\left(t-\frac{\mathbf{V}}{c^2}x\right)
    \end{cases}
    }
    ,&&\left<\gamma=\frac{1}{\sqrt{1-\left(\frac{\mathbf{V}}{c}\right)^2}}=\frac{1}{\sqrt{1-\left(\frac{0.85c}{c}\right)^2}}=1.8983;\right>
    \end{align*}
$$
$$
    \begin{align*}
    x'&=\gamma(x-\mathbf{V}t)\\
    &=(1.8983)\left((75)-(0.85)\left(3.0\times10^8\right)\left(2.0\times10^{-5}\right)\right)\\
    &=-9.538\times10^3\:\text{m}\\
    y'&=y=18\:\text{m}\\
    z'&=z=4\:\text{m}\\
    t'&=\gamma\left(t-\frac{\mathbf{V}}{c^2}x\right)\\
    &=(1.8983)\left((2.0\times10^{-5})-\left(\frac{0.85c}{c^2}\right)(75)\right)\\
    &=3.756\times10^{-5}\:\text{s}\\\\
    \end{align*}
$$
$$
    \therefore
    \begin{cases}
    x'=-9.538\times10^{3}\:\text{m};\\
    y'=18\:\text{m};\\
    z'=4\:\text{m};\\
    t'=3.756\times10^{-5}\:\text{s}
    \end{cases}
$$

#### 1.13.2
$$
    \begin{align*}
    \underset{\text{Inverse Lorentz Transformation}}{
    \begin{cases}
    x=\gamma(x'+\mathbf{V}t);\\
    y=y';\\
    z=z';\\
    t=\gamma\left(t'+\frac{\mathbf{V}}{c^2}x'\right)
    \end{cases}
    }
    ,&&\left<\gamma=\frac{1}{\sqrt{1-\left(\frac{\mathbf{V}}{c}\right)^2}}=\frac{1}{\sqrt{1-\left(\frac{0.85c}{c}\right)^2}}=1.8983;\right>
    \end{align*}
$$
$$
    \begin{align*}
    x&=\gamma(x'-\mathbf{V}t')\\
    &=(1.8983)\left((-9.538\times10^3)-(0.85)\left(3.0\times10^8\right)\left(3.756\times10^{-5}\right)\right)\\&=75.8\:\text{m}\\
    y'&=y=18\:\text{m}\\
    z'&=z=4\:\text{m}\\
    t&=\gamma\left(t'+\frac{\mathbf{V}}{c^2}x'\right)\\
    &=(1.8983)\left((3.756\times10^{-5})-\left(\frac{0.85c}{c^2}\right)(-9.538\times10^3)\right)\\&=2.0\times10^{-5}\:\text{s}\\\\
    \end{align*}
$$
$$
    \therefore
    \begin{cases}
    x=75.8\:\text{m};\\
    y=18\:\text{m};\\
    z=4\:\text{m};\\
    t=2.0\times10^{-5}\:\text{s}
    \end{cases}
$$

