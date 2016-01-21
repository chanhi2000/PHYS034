# **week03**

## REALTIVISTICI MASS
$$
    \begin{align*}
    m&=\gamma\:m_0,&\left<m_0:\:\text{mass at rest}\right>
    \end{align*}
$$
#### in NON-RELATIVISTIC frame (PHYS031)
$$
    \begin{align*}
    E&=W=\int{\vec{F}\cdot{d}\vec{x}}=\int{\left(m\vec{a}\right)\cdot{d}\vec{x}}\\
    &=\int{m\left(\frac{d\vec{v}}{dt}\right)\cdot\vec{x}}=\int{m\left(\frac{d\vec{x}}{dt}\right)d\vec{v}}\\
    &=\int{m(v)(dv)}=m\left(\frac{v^2}{2}\right)=\frac{1}{2}mv^2;
    \end{align*}
$$


#### in RELATIVISTIC frame
$$
    \begin{align*}
    E&=W=\int{\vec{F}\cdot{d}\vec{x}}=\int{\left(\frac{dp}{dt}\right)dx},&&\left<F=\frac{dp}{dt}\right>\\
    &=\int{\frac{d}{dt}(p)dx}=\int{\frac{d}{dt}\left(\gamma{m_0}v\right)}\\
    &=\int{m_0\left(\gamma\frac{dv}{dt}+v\frac{d\gamma}{dt}\right)}\\
    &=\cdots
    \end{align*}
$$

$$
    \left\{
    \begin{align*}
    \gamma&=\left(1-\frac{v^2}{c^2}\right)^{-\frac{1}{2}};\\
    \frac{d\gamma}{dt}&=\frac{d}{dt}\left(\gamma\right)=\frac{d}{dt}\left(1-\frac{v^2}{c^2}\right)^{-\frac{1}{2}}\\
    &=\left(-\frac{1}{2}\right)\left(1-\frac{v^2}{c^2}\right)^{-\frac{3}{2}}\left[\left(-\frac{2v}{c^2}\right)\left(\frac{dv}{dt}\right)\right]\\
    &=\frac{v}{c^2}\gamma^3\frac{dv}{dt}
    \end{align*}
    \right\}
$$

$$
    \begin{align*}
    E&=\int{m_0\left(\gamma\frac{dv}{dt}+v\left(\frac{v}{c^2}\gamma^3\frac{dv}{dt}\right)\right)dx}\\&=\int{m_0\left(\gamma{dv}+\frac{v^2}{c^2}\gamma^3dv\right)\frac{dx}{dt}}=\int{m_0\gamma{dv}\left(1+\frac{v^2}{c^2}\gamma^2\right)\frac{dx}{dt}}
    \end{align*}
$$

$$
    \left\{
    \begin{align*}
    1+\frac{v^2}{c^2}\gamma^2&=1+\left(\frac{v^2}{c^2}\right)\left(\frac{c^2}{c^2-v^2}\right)=1+\frac{v^2}{c^2-v^2}\\
    &=\left(\frac{v^2}{c^2-v^2}\right)+\left(\frac{c^2-v^2}{c^2-v^2}\right)=\frac{c^2}{c^2-v^2}=\gamma^2
    \end{align*}
    \right\}
$$
$$
    \begin{align*}
    E&=\int{m_0\gamma(\gamma^2)dv(v)}=\int{m_0\gamma^3v\:dv},\\
    &\left<\frac{d\gamma}{dt}=\frac{v}{c^2}\gamma^3\frac{dv}{dt};\:\:\:\:d\gamma=\frac{v}{c^2}\gamma^3dv\right>\\
    &=\int{m_0(c^2)d\gamma}=m_0c^2\int{d\gamma}=\gamma{m_0}c^2;
    \end{align*}
$$

$$
    \begin{align*}
    \therefore{E}&=\gamma{m_0}c^2
    \end{align*}
$$
Give the lower and upper bounds for this integral
$$
    \begin{align*}
    E&=m_0c^2\left.\left(1-\frac{v^2}{c^2}\right)^{-\frac{1}{2}}\right|_{0}^v\\
    &=m_0c^2\left(1-\frac{(v)^2}{c^2}\right)^{-\frac{1}{2}}-m_0c^2\left(1-\frac{(0)^2}{c^2}\right)^{-\frac{1}{2}}\\
    &=m_0c^2\gamma-m_0c^2=(\gamma-1)m_0c^2;
    \end{align*}
$$

given velocity "close" to speed of light, the kinetic energy is denoted,
$$
    \begin{align*}
    K&=\gamma{m_0}c^2-m_0c^2=E_{\text{total}}-E_{\text{rest}}\\
    &=(\gamma-1)m_0c^2
    \end{align*}
$$
to see if this equation holds true in classical physics.
$$
    \left\{
    \begin{align*}
    v\ll{c},&\underset{\text{Binomial Expansion}}{\gamma\approx1+\frac{1}{2}\frac{v^2}{c^2}}
    \end{align*}\right\}
$$
$$
    \begin{align*}
    K\approx\left[\left(1+\frac{1}{2}\frac{v^2}{c^2}\right)-1\right]m_0c^2=\frac{1}{2}m_0v^2
    \end{align*}
$$
###### ENERGY RELATION ($$E_{\text{total}} vs. E_{\text{rest}}$$)
$$
    \begin{align*}
    m&=\gamma{m_0};\\
    m^2&=\gamma^2m_0^2=\left(\frac{c^2}{c^2-v^2}\right)m_0^2;\\
    m_0^2c^2&=m^2(c^2-v^2)=m^2c^2-m^2v^2;\\
    (m_0^2c^2)(c^2)&=(c^2)(m^2c^2-m^2v^2);\\
    (m_0c^2)^2&=(mc^2)^2-m^2c^2v^2;\\
    (mc^2)^2&=m^2c^2v^2+(m_0c^2)^2;\\
    &\left<E=m_0c^2\right>\:\:\:\:\left<p=mv\right>\\
    (E_{\text{total}})^2&=(pc)^2+(E_{\text{rest}})^2
    \end{align*}
$$

### DIREC'S DISCOVERY
- Basically he proposed that in special relativity, electrons can have both a **positive** charge and **negative** energy.
> **Q**: how is it possible to have an electron with energy that is **positively charged**?
