# **week01**

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

