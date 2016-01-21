# **lect01**

## NEWTON'S LAW
$$
    \sum{\vec{F}}=m\vec{a};
$$
- **vector** statement
- **sum of force** statement
- does not make distinction between
    - **object at rest** and
    - **object moving at constant velocity**.

$$
    \begin{matrix}
    V=0&\equiv&V=\text{const}
    \end{matrix}
$$


## FRAME OF REFERENCE
- inertial frame
- e.g.
    - $$S: xy\text{-frame}$$

> **Q1**: In the classroom, fixed to the surface of the earth, are we on an inertial frame?

- **A1**: No. Because the earth is spinning.


> **Q2**: Do we see something spinning, because the earth is spinning?

- **A2**: No. (except [coriolis effect](https://en.m.wikipedia.org/wiki/Coriolis_effect))

###### EXAMPLE#1: FRAME OF REFERENCE

###### EXAMPLE#2: FRAME OF REFERENCE


#### IN GENERAL
$$
    \begin{align*}
    v'&=v-\mathbf{V},&&\begin{cases} v_1=v_1'+\mathbf{V};\\ v_2=v_2'-\mathbf{V};
    \end{cases}
    \end{align*}
$$
#### CONSERVATION OF MOMENTUM
$$
    \begin{align*}
    m_1v_1+m_2v_2&=(m_1+m_2)v_f;&&\left<v=v'+\mathbf{V}\right>\\
    m_1(v_1'+\mathbf{V})+m_2(v_2'+\mathbf{V})&=(m_1+m_2)(v_f'+\mathbf{V});\\
    m_1v_1'+m_2v_2'+(m_1+m_2)\mathbf{V}&=(m_1+m_2)(v_f')+(m_1+m_2)\mathbf{V});\\
    m_1v_1'+m_2v_2'&=(m_1+m_2)v_f'
    \end{align*}
    
$$

$$
    \underset{\text{conservation of momentum}}{\therefore{S'}: m_1v_1'+m_2v_2'=(m_1+m_2)v_f'}
$$

## GALILEAN TRANSFORMATION
- #### DERIVATION
$$
    \begin{align*}
    v'&=v-\mathbf{V};\\
    \frac{dx'}{dt'}&=\frac{dx}{dt}-\mathbf{V};&&\left<dt'=dt\right>\\
    dx'&=dx-\mathbf{V}dt;\\
    x'&=x-\mathbf{V}dt;
    \end{align*}
$$
- #### GENERAL FORM (for Newtonian Relativity)    
$$
    \begin{cases}
    x'=x-\mathbf{V}t;\\
    y'=y;\\
    z'=z;\\
    t'=t;\\
    \end{cases}
$$

## SPEED OF LIGHT
- #### list of important equations
    - [Gauss's Law](https://en.m.wikipedia.org/wiki/Gauss%27s_law)
$$
    \begin{align*}
    \oint{\vec{E}\cdot{d}\vec{S}}&=\frac{Q_{\text{enc}}}{\epsilon_0},&&\left<\underset{\text{permittivity of free space}}{\epsilon_0=\frac{10^{-9}}{36\pi}\approx8.85\times10^{-12}}\right>
    \end{align*}
$$
    - [Faraday's Law (of induction)](https://en.m.wikipedia.org/wiki/Faraday%27s_law_of_induction)
$$
    \begin{align*}
    \oint{\vec{E}\cdot{d}\vec{S}}&=-\frac{d\Phi_{B}}{dt},&&&&\left<\underset{\text{magnetic flux}}{\phi_B=\oint{\vec{B}\cdot{d}\vec{S}}}\right>
    \end{align*}
$$
    - [Ampere's Law](https://en.m.wikipedia.org/wiki/Amp%C3%A8re%27s_circuital_law)
$$
    \begin{align*}
    \oint{\vec{B}\cdot{d}\vec{S}}&=\mu_0i_{\text{through}},&&\left<\begin{matrix}B:\text{magnetic flux density}\\ \underset{\text{permeability of free space}}{\mu_0=4\pi\times10^{-7}=12.6\times10^{-7}}\end{matrix}\right>
    \end{align*}
$$
    - [Maxwell's Equation](https://en.m.wikipedia.org/wiki/Maxwell%27s_equations)
$$
    \begin{align*}
    \oint{\vec{B}\cdot{d}\vec{S}}&=\mu_0\left[i_{\text{through}}+\epsilon_0\frac{d\Phi_E}{dt}\right],&\text{where}\\
    \end{align*}
$$
$$
    \left<
    \begin{align*}
    \phi_E&=\oint{\vec{E}\cdot{d}\vec{S}}
    =\oint{E\:dA\:\cos{\theta}}\\&=E\:A=\left[\frac{q}{\epsilon_0A}\right]A
    \end{align*}
    \right>
$$

- #### DERIVATION
$$
    \begin{align*}
    \oint{\vec{E}\cdot{d}\vec{S}}
    &=E(x+\Delta{x},t)h+0-E(x,t)h+0;&&\left<E(x+\Delta{x})=E(x)+\frac{dE}{dx}\Delta{x}\right>\\
    &=\left[E(x)+\frac{dE}{dx}\Delta{x}\right]h-E(x,t)h;\\
    &=\underline{\frac{dE}{dx}\Delta{x}\:h;}
    \end{align*}
$$
$$
    \begin{align*}
    \oint{\vec{E}\cdot{d}\vec{S}}
    &=-\frac{d\Phi_B}{dt}=-\frac{d}{dt}\left(\oint{\vec{B}\cdot{d}\vec{A}}\right)=-\frac{d}{dt}\left(B\:A\:\cos{\theta}\right)\\
    &=-\frac{d}{dt}\left(B\:\Delta{x}\:h\right)=\underline{-\frac{dB}{dt}\Delta{x}\:h;}\\\\
    \end{align*}
$$
$$
    \begin{align*}
    \frac{dE}{dx}\Delta{x}\:h&=-\frac{dB}{dt}\Delta{x}\:h\\
    \therefore\frac{dE}{dx}&=-\frac{dB}{dt}
    \end{align*}
$$
$$  
    \begin{align*}
    \oint{\vec{B}\cdot{d}\vec{S}}&=-B(x+\Delta{x})h+0+B(x,t)h+0,&&\left<B(x+\Delta{x})=B(x)+\frac{dB}{dx}\Delta{x}\right>\\
    &=-\left[B(x,t)+\frac{dB}{dx}\Delta{x}\right]h+B(x,t)h\\
    &=\underline{-\frac{dB}{dx}\Delta{x}\:h;}
    \end{align*}
$$
$$
    \begin{align*}
    \oint{\vec{B}\cdot{d}\vec{S}}&=\mu_0\left[i_{\text{through}}+\epsilon_0\frac{d\Phi_E}{dt}\right],&&\left<i_{\text{through}}=0\right>\\
    &=\epsilon_0\mu_0\frac{d\Phi_{E}}{dt}=\epsilon_0\mu_0\frac{d}{dt}\oint{\vec{E}\cdot{d}\vec{S}}\\&=\underline{\epsilon_0\mu_0\frac{dE}{dt}\Delta{x}\:h};\\\\
    \end{align*}
$$
$$
    \begin{align*}
    -\frac{dB}{dx}\Delta{x}\:h&=\epsilon_0\mu_0\frac{dE}{dt}\Delta{x}\:h\\
    \therefore-\frac{dB}{dx}&=\epsilon_0\mu_0\frac{dE}{dt}
    \end{align*}
$$
Use these two equations to come up with something new
$$
    \left\{
    \begin{align*}
    \frac{dE}{dx}&=-\frac{dB}{dt}\\\\
    -\frac{dB}{dx}&=\epsilon_0\mu_0\frac{dE}{dt}
    \end{align*}
    \right.
$$
$$
    \begin{align*}
    \left(\frac{d}{dx}\right)\frac{dE}{dx}&=-\left(\frac{d}{dx}\right)\frac{dB}{dt}\\
    \frac{d^2E}{dx^2}&=\frac{d}{dt}\left(-\frac{dB}{dx}\right),&&\left<-\frac{dB}{dx}=\epsilon_0\mu_0\frac{dE}{dt}\right>\\
    &=\frac{d}{dt}\left(\epsilon_0\mu_0\frac{dE}{dt}\right)\\
    &=\epsilon_0\mu_0\frac{d^2E}{dt^2}
    \end{align*}
$$
**Reminder**: wave equation (PHYS032)
$$  
    \begin{align*}
    \frac{d^2y}{dx^2}&=\frac{1}{v^2}\frac{d^2y}{dt^2}\\
    \end{align*}
$$
So we use this relation to make sense of our derived equation
$$
    \left\{
    \begin{align*}
    \frac{d^2y}{dx^2}&=\left(\frac{1}{v^2}\right)\frac{d^2y}{dt^2}\\\\
    \frac{d^2E}{dx^2}&=\left(\epsilon_0\mu_0\right)\frac{d^2E}{dt^2}
    \end{align*}
    \right.
$$
#### SPEED OF THE WAVE (LIGHT)
$$
    \begin{align*}
    \frac{1}{v^2}&=\epsilon_0\mu_0;\\
    v&=\frac{1}{\sqrt{\epsilon_0\mu_0}}=\frac{1}{\sqrt{\left(\frac{10^{-9}}{36\pi}\right)\left(4\pi\times10^{7}\right)}}\\
    &=3.0\times10^{8}
    \end{align*}
$$
#### CONCLUSION
 - **Light** is no different from **EM wave** (i.e. microwave, radio wave, x-ray, etc.)

## LORENTZ TRANSFORMATION
from GALILEAN TRANSFORMATION
#### Gamma
$$
    x'=x-\mathbf{V}t;
$$
Lorentz Transformation says that, in special relativity,
$$
    x'=\gamma\left(x-\mathbf{V}t\right)
$$
- Einstein's Postulate says if we consider the distance to be
$$d=rt$$
$$
    \left\{\begin{align*}
    S'&:x'=ct';\\
    S&: x=ct;
    \end{align*}\right.
$$
back to our Lorentz Transformation
$$
    \begin{matrix}
    \underset{\text{Lorentz TF form}}{\underline{\begin{align*}
    x'&=\gamma\left(x-\mathbf{V}t\right)\\
    (ct')&=\gamma\left((ct)-\mathbf{V}t\right)\\
    ct'&=\gamma\left(c-\mathbf{V}\right)t
    \end{align*}}}&&
    \underset{\text{Inverse Lorentz TF form}}{\underline{\begin{align*}
    x&=\gamma\left(x'+\mathbf{V}t'\right)\\
    (ct)&=\gamma\left((ct')+\mathbf{V}t'\right)\\
    ct&=\gamma\left(c+\mathbf{V}\right)t'
    \end{align*}}}\end{matrix}
$$
Use this relation to derive Gamma
$$
    \begin{align*}
    1&=1;\\
    \left(\frac{ct'}{\gamma\left(c-\mathbf{V}\right)t}\right)&=\left(\frac{\gamma\left(c+\mathbf{V}\right)t'}{ct}\right);\\
    \frac{c}{\gamma\left(c-\mathbf{V}\right)}&=\frac{\gamma\left(c+\mathbf{V}\right)}{c}\\
    c^2&=(\gamma)^2(c-\mathbf{V})(c+\mathbf{V})\\
    &=\gamma^2\left(c^2-\mathbf{V}^2\right);\\\\
    \gamma^2&=\frac{c^2}{c^2-\mathbf{V}}=\frac{1}{\frac{c^2-\mathbf{V}}{c^2}}=\frac{1}{1-\frac{\mathbf{V}^2}{c^2}};\\
    \gamma&=\sqrt{\left(\frac{1}{1-\frac{\mathbf{V}^2}{c^2}}\right)}=\frac{1}{\sqrt{1-\left(\frac{\mathbf{V}}{c}\right)^2}}\\
    &=\frac{1}{\sqrt{1-\left(\beta\right)^2}},
    \end{align*}
$$
where
$$
    \begin{matrix}
    \begin{align*}
    \beta=\frac{\mathbf{V}}{c}
    \end{align*}&
    \begin{cases}
    \beta\to0&\mathbf{V}\ll{c}\\
    \beta\to1&\mathbf{V}\approx{c}
    \end{cases}
    \end{matrix}
$$

#### TIME FOR LORENTZ TRANSFORMATION

- An observer from frame $$S$$ can see the person's time in the other frame $$S'$$ is **dilated** when the frame $$S'$$ is moving at a speed **close to speed of light**. On that note, we need to know how to get the proper time, $$t'$$ measured by the observer from $$S$$ frame.
###### $$t$$ and $$t'$$
$$  
    \begin{align*}
    x&=\gamma(x'+\mathbf{V}t')
    \end{align*}
$$