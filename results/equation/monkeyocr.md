# 2.2 Regge trajectories and anomalous dimensions  

Let us list some families of local operators that will be important in this work. The lowest twist families are "double-twist" operators built from two scalars $\phi^{i}$. These can be grouped into $O(N)$ singlets, antisymmetric tensors, and symmetric tensors as follows:  

$$
$\begin{array} { l l } { { \left[ ( \phi ^ { i } \phi ^ { j } ) _ { s } \right] _ { J } \sim \phi ^ { i } \partial _ { \mu _ { 1 } } \cdots \partial _ { \mu _ { J } } \phi ^ { i } + \cdots \, , } } & { { \tau = d - 2 + O ( 1 / N ) \, , } } \\ { { \left[ ( \phi ^ { i } \phi ^ { j } ) _ { \mathrm { s y m } } \right] _ { J } \sim \phi ^ { ( i } \partial _ { \mu _ { 1 } } \cdots \partial _ { \mu _ { J } } \phi ^ { j ) } + \cdots \, , } } & { { \tau = d - 2 + O ( 1 / N ) \, , } } \\ { { \left[ ( \phi ^ { i } \phi ^ { j } ) _ { \mathrm { a s y m } } \right] _ { J } \sim \phi ^ { [ i } \partial _ { \mu _ { 1 } } \cdots \partial _ { \mu _ { J } } \phi ^ { j ] } + \cdots \, , } } & { { \tau = d - 2 + O ( 1 / N ) \, . } } \end{array}$
$$  

Here “$\ldots$” represents combinations of derivatives needed to ensure that the operator is primary. By analogy with QCD, we will sometimes refer to these leading twist operators as DGLAP-type [2, 69, 70]. In the limit $N \to \infty$, these operators become higher-spin conserved currents with scaling dimensions $\Delta = J + d - 2$. At finite $N$, the higher-spin symmetries are slightly broken and these operators acquire anomalous dimensions, except for the spin-2 singlet current, which is the stress tensor $[(\phi^i \phi^i)_s]_2 = T_{\mu\nu}$. The leading anomalous dimensions are [71, 72]  

$$
$\begin{array} { r l } & { \gamma _ { \mathrm { s y m } , J } = \gamma _ { \mathrm { a s y m } , J } = \frac { 1 } { N } \frac { 1 6 ( J - 1 ) ( d + J - 2 ) \sin \left( \frac { \pi d } { 2 } \right) \Gamma ( d - 2 ) } { \pi ( d + 2 J - 4 ) ( d + 2 J - 2 ) \Gamma \left( \frac { d } { 2 } - 2 \right) \Gamma \left( \frac { d } { 2 } + 1 \right) } , } \\ & { \gamma _ { s , J } = \gamma _ { ( \mathrm { a } ) \mathrm { s y m } , J } - \frac { 1 } { N } \frac { 8 \sin \left( \frac { \pi d } { 2 } \right) \Gamma ( d - 2 ) \Gamma ( d + 1 ) \Gamma ( J + 1 ) } { \pi ( d - 1 ) ( d + 2 J - 4 ) ( d + 2 J - 2 ) \Gamma \left( \frac { d } { 2 } - 2 \right) \Gamma \left( \frac { d } { 2 } + 1 \right) \Gamma ( d + J - 3 ) } . } \end{array}$
$$  

Some example higher-twist families are  

$$
$\begin{array} { l l } { { \left[ \sigma \phi ^ { i } \right] _ { J } \sim \sigma \partial _ { \mu _ { 1 } } \cdots \partial _ { \mu _ { J } } \phi ^ { i } \, , } } & { { \tau = \frac { d + 2 } { 2 } + O ( 1 / N ) \, , } } \\ { { \left[ \sigma ( \phi ^ { i } \phi ^ { j } ) _ { \rho } \right] _ { J } \sim \sigma ( \phi ^ { i } \partial _ { \mu _ { 1 } } \cdots \partial _ { \mu _ { J } } \phi ^ { i } ) _ { \rho } \, , } } & { { \tau = d + O ( 1 / N ) \, , } } \\ { { \left[ \sigma \sigma \right] _ { J } \sim \sigma \partial _ { \mu _ { 1 } } \cdots \partial _ { \mu _ { J } } \sigma \, , } } & { { \tau = 4 + O ( 1 / N ) \, . } } \end{array}$
$$  

Here and below, we use the notation that $\rho$ stands for an $O(N)$ representation that can be either "s", "sym", or "asym". The equation of motion implies that $\Box\phi\sim\sigma\phi$. Thus, $[\sigma(\phi^i\phi^j)_\rho]_J$ plays the role of a subleading double-twist family for $\phi$. Each additional insertion of $\sigma$ or $\phi$ generates additional subleading trajectories. Thus, even in the infinite-$N$ limit, the theory contains a rich set of families that become dense in $\tau$ at large $\tau$ (for generic $d$).  

# 2.3 A first look at the Chew-Frautschi plot  

A Regge trajectory is a family of light-ray operators depending continuously on spin $J$. Nonvanishing light-ray operators with nonnegative integer $J$ become light-transforms of local operators $\mathbf{L}[\mathcal{O}]$ (or their shadow transforms). We can visualize Regge trajectories using a Chew-Frautschi plot. The coordinates of the Chew-Frautschi plot are conventionally chosen to be $\Delta-\frac{d}{2}$ and $J$, where $(\Delta,J)=(1-J_L,1-\Delta_L)$, where $(\Delta_L,J_L)$ are the quantum numbers  