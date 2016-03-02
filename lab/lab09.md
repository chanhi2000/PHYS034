# lab09

## TITLE:
Measuring the Half-life of Radioactive Indium


## EQUIPMENTS:
- Geiger Muller tube and sample holder; Scaler/timer
- Radioactive source of $$^{116}\text{In}$$ made in-house with indium foils via ($$\alpha$$, $$n$$) reactions within our PuBe reactor


## LAB OBJECTIVE
- Learn more about gamma, alpha particle, and neutron radiation physics 
- Learn more about appropriate shielding of particle radiation
- Learn about the statistical nature of radioactive decay
- Measure the half-life of an isotope of radioactive indium ($$^{116}\text{In}^*$$)


## INTRODUCTION AND BACKGROUND:
Every radionuclide has a characteristic half-life, $$\tau_{1/2}$$, defined as the time it takes for one half of the sample to decay according to a specific process. Half-life values range from $$\ll1\:\mu\text{s}$$ to more than a billion years. The half-life of nearly every radionuclide has been determined experimentally, and can be looked-up in standard nuclear data tables. One of the best resources for finding accurate nuclear physics data is "Table of Isotopes", by C.M. Lederer, et. al., John Wiley & Sons, Inc.

Radionuclides decay exponentially with time according to:
$$
N(t)=N_0e^{-\tfrac{t}{\tau}}=N_0e^{-0.693\tfrac{t}{\tau_{1.2}}}
$$

where $$N_0$$ is the number of parent nuclei initially present at time $$t=0$$, $$N(t)$$ is the number of parent nuclei remaining at time $$t$$ and $$\tau$$ is the "lifetime" $$(\tfrac{1}{e})$$ of the parent nucleus via the decay process considered. A more commonly used term is the half-life ¥¥、tauτ1/2, which is the time (on average) it takes for one-half of the parent nuclei to undergo the specific radioactive decay considered. **Use the exponential decay equation given above to explicitly show that** $$\tau_{1/2}=0.693\tau$$.

Although naturally decaying radioisotopes exist for every element on the periodic table, it is also possible to produce radioactive nuclei in the laboratory. Today we will perform such a procedure and then study one of its effects. First, we will expose a small foil of natural In ($$Z=49$$) to a flux of $$\sim1$$-$$10\:\text{MeV}$$ neutrons produced by a $$\text{PuBe}\:(\alpha,n)$$ source. (The $$\text{PuBe}$$ source also emits many $$\gamma$$-rays but we will not study those today.) These neutrons are produced by various nuclear processes occurring within the PuBe source itself. These reactions include $$(\alpha,n)$$ reactions like that shown below, whereby $$\alpha$$-particles emitted by $$\text{Pu}$$ nuclei strike $$^9\text{Be}$$ nuclei (all within the $$\text{PuBe}$$ nuclear reactor core). Each reaction produces an excited $$^{13}\text{C}$$ nucleus that decays into $$^{12}\text{C}$$ (carbon’s most stable isotope) plus an extra neutron, *i.e.*:
$$
\alpha+^{9}\text{Be}\to^{13}\text{C}^*\to^{12}\text{C}+^{1}n.
$$
We will use the resulting neutron flux from our PuBe source to transmute indium into tin! To do this, we will first place indium foils in the PuBe reactor’s neutron flux. This will result in the transmutation of some $$^{115}\text{In}$$ nuclei into $$^{116}\text{In}$$. We will then measure the $$\beta$$-decay of $$^{116}\text{In}$$ into $$^{116}\text{Sn}$$ via the reaction (written here in nuclear physicists’ shorthand notation) $$^{115}\text{In}(n,\beta)^{116}\text{Sn}$$. For reference: $$\tau_{1/2}=54.2\:\text{minutes}$$ for this $$\beta$$-decay process. In equation form, here is the β-decay process we will study in lab:
$$
^{115}\text{In}+n\to^{116}\text{In}^*\to^{116}\text{Sn}+e^-+\bar{\nu}
$$


## SUGGESTED EXPERIMENTAL PROCEDURE:
1. Establish the optimal operating voltage of your Geiger-Muller detector, using the standard technique. Note in your lab book the results of today's calibration. Include an estimate of your uncertainty.

2. Measure the background count rate at the operating voltage you have chosen. Express the count rate in counts per minute. What is your uncertainty in this value? (**HINT**: Think statistics.... $$\sqrt{N}$$)

3. When you are ready to begin the half-life counting experiment, ask the lab instructor to give you a radioactive indium foil from the reactor. Place the (radioactively hot!) foil in the sample holder of your G-M apparatus so that the count rate is moderately high but not “off-scale” for your detector or electronics. For at least one hour, starting as soon as possible after you have your source in place, carefully measure the In-foil $$\beta$$-decay rate at specific time intervals (*e.g.*, record decays/30 sec. every five minutes.) Subtract the background rate from each data point as you go. Be sure to include background-subtracted error estimates (and remember statistics:$$\sqrt{N}$$ ) for each data point!

4. Plot your data in such a way that a straight-line fit is appropriate and carefully determine the half-life of $$^{116}\text{In}$$ via $$\beta$$-decay. Include error bars! (**See hints below**) Does your graph show evidence of two (or more) distinct slopes? If so, why? Does your result for $$\tau_{1/2}$$ (± experimental uncertainty) agree with the expected value? Summarize, and discuss your results.


## HINTS AND SIMPLIFICATIONS FOR ANALYSIS:
1. Assuming $$N_B\ll{N}$$, where $$N$$ is your measured count rate with a source in place and $$N_B$$ is your measured background rate, the statistical uncertainty for each background-corrected measurement $$N$$-$$N_B$$ can be approximated (for simplicity only!) by $$N$$-$$N_B\pm\sim{N}$$ . Of course, this is not statistically correct but the approximation is reasonable for this experiment. (Check some values and you will see it’s true!)

2. You need to include error bars on the grap!h described in experimental step (4) above. When you plot your data in a format that should yield a linear fit, the $$y$$-error bars can be calculated using derivatives....
$$
\ln{(N')}\pm\text{errorbars};\\
$$

$$
\begin{align*}
\text{errorbars}&\sim\frac{d(\ln{(N')}}{dn}\Delta{N}'\\
&=\left(\frac{1}{N'}\right)\Delta{N}'\\
&\sim\frac{\sqrt{N}}{N'}=\frac{\sqrt{N}}{(N-N_B)}
\end{align*}
$$