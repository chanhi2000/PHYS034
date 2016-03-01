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

where $$N_0$$ is the number of parent nuclei initially present at time $$t=0$$, $$N(t)$$ is the number of parent nuclei remaining at time $$t$$ and $$\tau$$ is the "lifetime" $$(\tfrac{1}{e})$$ of the parent nucleus via the decay process considered. A more commonly used term is the half-life ¥¥、tauτ1/2, which is the time (on average) it takes for one-half of the parent nuclei to undergo the specific radioactive decay considered. Use the exponential decay equation given above to explicitly show that τ1/2 = 0.693τ .
Although naturally decaying radioisotopes exist for every element on the periodic table, it is also possible to produce radioactive nuclei in the laboratory. Today we will perform such a procedure and then study one of its effects. First, we will expose a small foil of natural In (Z=49) to a flux of ~1-10 MeV neutrons produced by a PuBe (α,n) source. (The PuBe source also emits many γ-rays but we will not study those today.) These neutrons are produced by various nuclear processes occurring within the PuBe source itself. These reactions include (α,n) reactions like that shown below, whereby α-particles emitted by Pu nuclei strike 9Be nuclei (all within the PuBe nuclear reactor core). Each reaction produces an excited 13C nucleus that decays into 12C (carbon’s most stable isotope) plus an extra neutron, i.e:
α+9Be → 13C* →12C+1n.
We will use the resulting neutron flux from our PuBe source to transmute indium into tin! To do this, we will first place indium foils in the PuBe reactor’s neutron flux. This will result in the transmutation of some 115In nuclei into 116In. We will then measure the β-decay of 116In into 116Sn via the reaction (written here in nuclear physicists’ shorthand notation) 115In(n,ß)116Sn. For reference: τ1/2=54.2 minutes for this β- decay process. In equation form, here is the β-decay process we will study in lab:
115In+n → 116In* →116Sn+e- + "e !