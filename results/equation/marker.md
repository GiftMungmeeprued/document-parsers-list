## 2.2 Regge trajectories and anomalous dimensions

Let us list some families of local operators that will be important in this work. The lowest twist families are "double-twist" operators built from two scalars ϕ i . These can be grouped into O(N) singlets, antisymmetric tensors, and symmetric tensors as follows:

$$
[(\phi^i \phi^j)_s]_J \sim \phi^i \partial_{\mu_1} \cdots \partial_{\mu_J} \phi^i + \cdots, \qquad \tau = d - 2 + O(1/N),
$$
  
\n
$$
[(\phi^i \phi^j)_{\text{sym}}]_J \sim \phi^{(i} \partial_{\mu_1} \cdots \partial_{\mu_J} \phi^j) + \cdots, \qquad \tau = d - 2 + O(1/N),
$$
  
\n
$$
[(\phi^i \phi^j)_{\text{asym}}]_J \sim \phi^{[i} \partial_{\mu_1} \cdots \partial_{\mu_J} \phi^{j]} + \cdots, \qquad \tau = d - 2 + O(1/N).
$$
 (2.5)

Here ". . . " represents combinations of derivatives needed to ensure that the operator is primary. By analogy with QCD, we will sometimes refer to these leading twist operators as DGLAP-type [2, 69, 70]. In the limit N → ∞, these operators become higher-spin conserved currents with scaling dimensions ∆ = J + d − 2. At finite N, the higher-spin symmetries are slightly broken and these operators acquire anomalous dimensions, except for the spin-2 singlet current, which is the stress tensor [(ϕ iϕ i )s]<sup>2</sup> = Tµν. The leading anomalous dimensions are [71, 72]

$$
\gamma_{\text{sym},J} = \gamma_{\text{asym},J} = \frac{1}{N} \frac{16(J-1)(d+J-2)\sin\left(\frac{\pi d}{2}\right)\Gamma(d-2)}{\pi(d+2J-4)(d+2J-2)\Gamma\left(\frac{d}{2}-2\right)\Gamma\left(\frac{d}{2}+1\right)},
$$
  

$$
\gamma_{s,J} = \gamma_{\text{(a)sym},J} - \frac{1}{N} \frac{8\sin\left(\frac{\pi d}{2}\right)\Gamma(d-2)\Gamma(d+1)\Gamma(J+1)}{\pi(d-1)(d+2J-4)(d+2J-2)\Gamma\left(\frac{d}{2}-2\right)\Gamma\left(\frac{d}{2}+1\right)\Gamma(d+J-3)}.
$$
(2.6)

Some example higher-twist families are

$$
[\sigma\phi^{i}]_{J} \sim \sigma \partial_{\mu_{1}} \cdots \partial_{\mu_{J}} \phi^{i},
$$
  
\n
$$
[\sigma(\phi^{i}\phi^{j})_{\rho}]_{J} \sim \sigma(\phi^{i}\partial_{\mu_{1}} \cdots \partial_{\mu_{J}} \phi^{i})_{\rho},
$$
  
\n
$$
[\sigma\sigma]_{J} \sim \sigma \partial_{\mu_{1}} \cdots \partial_{\mu_{J}} \sigma,
$$
  
\n
$$
\tau = d + O(1/N),
$$
  
\n
$$
\tau = 4 + O(1/N).
$$
  
\n(2.7)

Here and below, we use the notation that ρ stands for an O(N) representation that can be either "s", "sym", or "asym". The equation of motion implies that □ϕ ∼ σϕ. Thus, [σ(ϕ iϕ j )ρ]<sup>J</sup> plays the role of a subleading double-twist family for ϕ. Each additional insertion of σ or ϕ generates additional subleading trajectories. Thus, even in the infinite-N limit, the theory contains a rich set of families that become dense in τ at large τ (for generic d).

## 2.3 A first look at the Chew-Frautschi plot

A Regge trajectory is a family of light-ray operators depending continuously on spin J. Nonvanishing light-ray operators with nonnegative integer J become light-transforms of local operators L[O] (or their shadow transforms). We can visualize Regge trajectories using a Chew-Frautschi plot. The coordinates of the Chew-Frautschi plot are conventionally chosen to be ∆− d 2 and J, where (∆, J) = (1−JL, 1−∆L), where (∆L, JL) are the quantum numbers