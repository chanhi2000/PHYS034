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