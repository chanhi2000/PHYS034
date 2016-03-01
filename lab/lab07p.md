# lab07p

## TITLE:
USEFUL INFORMATION FOR RADIOACTIVITY EXPERIMENTS


## 1. RANDOM NATURE OF NUCLEAR DECAY
The decay of a single radioactive nucleus is a random event and cannot be predicted with absolute accuracy.  If we take a large collection of similar radioactive nuclei, however, we can apply basic statistics to predict how many nuclei will spontaneously decay during a specified time interval.  The probability for "$$n$$" decays during a known time interval is given by the Poisson distribution:
$$
P(n)=\frac{[<n>^n\cdot{e}^{-<n>}]}{n!}
$$

where $$<n>$$ is the average number of decays in the interval.  For small $$<n>$$, $$P(n)$$ vs. $$n$$ is a lopsided distribution.  As $$<n>$$ increases, the Poisson distribution approaches the symmetric Gaussian distribution.  Suppose we have a sample of radioactive nuclei, and we carry out a large number "$$M$$" of identical, independent measurements of the count rate (counts / unit time).  The average count rate $$<n>$$ and the standard deviation $$\sigma$$ are defined to be:
$$
<n>=\left(\frac{1}{M}\right)\sum_{i=1}^{M}{n_i}
$$

and
$$
\sigma=\left[\frac{1}{(M-1)}\sum_{i=1}^{M}{\left(n_i-<n>\right)^2}\right]^{\frac{1}{2}}
$$

For a Poisson distribution, it can be shown that $$\sigma=<n>^{\tfrac{1}{2}}$$.  Assuming, for example, that $$<n>$$ is $$100\:\tfrac{\text{counts}}{\text{min}}$$, then $$\sigma=10$$.  Approximately $$68\:\%$$ of the observed count rates fall in the range $$(<n>\pm\sigma)$$, and approximately $$95\:\%$$ will fall in the range $$(<n>\pm2\sigma)$$.  For any single measurement "$$n$$", $$68\:\%$$ of the time "$$n$$" will be within $$\pm\sigma$$ of the average $$<n>$$.  If the single measurement is $$n\:\left[\tfrac{\text{counts}}{\text{time}}\right]$$ then the approximate uncertainty in "$$n$$" is $$n^{\tfrac{1}{2}}$$.

## 2. RADIOACTIVE "HALF-LIFE"
Every radionuclide has a characteristic half-life, which is defined as the time it takes for one-half of the sample to decay. Half-lives range from incredibly short $$(<1\mu\text{s})$$ to incredibly long (billions of years).  The half-life of nearly every radionuclide has been determined experimentally, and can be looked-up in standard nuclear data tables.  (One of the best resources for finding accurate nuclear physics data is "Table of Isotopes", by C.M. Lederer, et. al., John Wiley & Sons, Inc., N.Y.) All radionuclides decay exponentially with time, as given by:
$$
N(t)=N_0e^{\tfrac{-t}{\tau}}=N_0e^{-0.693\tfrac{t}{\tau_{1/2}}}
$$

where $$N_0$$ is the number of parent nuclei present at time $$t=0$$, $$N(t)$$ is the number present at time "$$t$$", and $$\tau$$ is the "lifetime" of the particular nuclear species measured.  $$\tau_{\tfrac{1}{2}}$$ is called the "half-life" of the radionuclide, which is the time (on average) that it takes for one-half of a sample to undergo a specific radioactive decay.

## 3. UNIT
- $$1\:\text{Ci}=3.7\times10^{10}\:\tfrac{\text{decays}}{\text{s}}$$ (Curie)

- $$1\:\text{rad}=100\:\tfrac{\text{ergs}}{\text{g}}=6.25\times10^7\:\tfrac{\text{MeV}}{\text{g}}$$
