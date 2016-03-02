# lab01

##TITLE:
MEASURING THE SPEED OF LIGHT

##EQUIPMENTS:
- Function Generator (FG) $$f\leq500\:\text{kHz}$$ is sufficient
- Oscilloscope; Calipers; Meter Stick
- LCR Circuit – long cylindrical capacitor, long coil, R provided by internal resistance of FG

##OVERVIEW[^1]:
Today you’ll use your Physics 33 knowledge to measure the speed of light! You’ll use a resonant LC-circuit with a cylindrical capacitor, a coil (inductor), and a variable-frequency function generator acting as the power source (see diagram below). The physics we’re dealing with today is rich and I encourage you to read more about electromagnetic waves in general. Have a look at Maxwell’s Equations for Electromagnetism - you should recognize all four equations from your work last quarter in Physics 33.$$V$$ by :
$$
I=kV^{\tfrac{3}{2}}
$$

##PRE-LAB HOMEWORK
1. Show that the capacitance (in Farads) of an ideal cylindrical capacitor of length “$$x$$” and relevant radii (think aboutit!) “$$a$$” and “$$b$$”is: $$C=2\pi\epsilon_0\frac{x}{\ln\left(\tfrac{b}{a}\right)}$$. (**HINT**: Use Gauss’s Law, $$\Delta{V}=-\int{E\cdot{d}l}$$ and $$Q=CV_c$$)

2. Show that the self-inductance (in Henries) of an ideal solenoid of length "$$z$$", cross sectional area "$$A$$", and number of turns "$$N$$"is: $$L=\frac{\mu_0N^2A}{z}$$.

3. Measure and rec!ord in your lab notebook the relevant geometric values (± uncertainties) for your capacitor and inductor. You will need to measure the various relevant diameters and lengths, the number of turns and diameter of the wire, etc. Include a clear sketches of your capacitor and inductor. Then use the expressions provided above in steps (1) and (2) to compute the capacitance and inductance of your circuit elements.

4. Use your values for $$C$$ and $$L$$ to predict the resonant frequency, $$f_0$$, of your LC(R) circuit, using the standard results for an LC oscillator that you learned in Physics 33. Record this in your lab notebook, making it clear it is your predicted value. (**HINT**: Recall that for a LCR circuit, $$f_0=\frac{1}{[2\pi(LC)^{\tfrac{1}{2}}]}$$ is the resonant frequency when $$R\ll{X}_L$$ and $$R\ll{X}_C$$. ($$X_L=\omega{L}$$ and $$X_C=\tfrac{1}{\omega{C}}$$.)

5. Now measure the resonant frequency of your LC(R) circuit using an oscilloscope and function generator. Make it clear in your lab notebook that this is your measured value for $$f_0$$. Compare your measured and predicted values of $$f_0$$ (± uncertainties). As always, comment on any discrepancy between the values. Calculate $$X_L$$ and $$X_C$$ for your circuit using your measured $$f_0$$. Then confirm that $$R\ll\omega{L}$$ and $$R\ll\tfrac{1}{\omega{C}}$$ (as we assumed).

6. Maxwell related the speed of light in vacuum (~ air at STP) to the constants[^2] $$\epsilon_0$$ and $$\mu_0$$ by $$c=\tfrac{1}{\sqrt{\epsilon_0\mu_0}}$$. Use the pre-lab expressions for $$L$$ and $$C$$ plus any suitable approximations to show that $$c$$ can be written:
$$
c\approx\pi^2f_0(D-d)N\left(\frac{2x}{z[\ln\left(\tfrac{b}{a}\right)]}\right)^{\tfrac{1}{2}},
$$
where "$$D$$" is the outer diameter of the inductor, "$$d$$" is the diameter of the inductor wire and all other terms are defined as before. Using all measured values, determine the speed of light, $$c$$. Compare your result to the accepted value of $$3.0\times10^8\:\tfrac{\text{m}}{\text{s}}$$. Comment on any discrepancy, clearly describing sources of experimental error. Comment on ways you might have done the experiment differently to achieve more accurate (and/or more precise) results.

[^1]: Experiment based on: George W. Clark, "An electrical measurement of the speed of light", *Amer. J. Phys.* **69** (2), February (2001).
[^2]: Recall that $$\epsilon_0=8.85\times10^{-12}\:\tfrac{\text{C}^2}{\text{N-m}^2}$$ and $$\mu_0=4\pi\times10^{-7}\:\tfrac{\text{T-m}}{\text{A}}$$
