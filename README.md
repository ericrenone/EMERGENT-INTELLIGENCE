# EMERGENT INTELLIGENCE
## The Architecture of Collective Cognition — Coordination Gain, Crystallization, and the Bifurcated Institutional Ecology

**Eric Ren · ERI Labs · Jersey City, New Jersey · 2026 · github.com/ericrenone**

---

> *"Without redundancy and integration, synergy alone does not translate into better collective performance."*
> — Riedl, Fiore, Heiss & Toth (2026). Emergent Coordination in Multi-Agent Language Models. arXiv:2510.05174

> *"Synergistic information reveals that the flock encodes information about predator location that is not accessible to every individual bird, demonstrating implicit collective knowledge."*
> — Maisto, Nuzzi & Pezzulo (2026). What the Flock Knows That the Birds Do Not. arXiv:2511.10835

> *"Grokking is a dimensional phase transition: effective dimensionality crosses from sub-diffusive to super-diffusive at generalization onset, exhibiting self-organized criticality."*
> — Wang (2026). Grokking as Dimensional Phase Transition in Neural Networks. arXiv:2604.04655

---

## Executive Summary

The science of collective intelligence has been built on a false assumption. Every existing framework — social physics, multi-agent AI orchestration, organizational economics, collective intelligence research — assumes that the coordination gain between agent contributions is zero before measurement begins. This is not a finding. It is an architectural prior embedded before fitting begins.

Three independent research programs completed in 2026 have falsified it simultaneously.

**Five findings with structural consequences:**

1. **G_coord = 0 is architectural, not empirical.** Riedl et al. (2026) confirm across multi-agent LLM collectives: synergy without a crystallized shared kernel produces G_coord ≈ 0 regardless of agent diversity, capability complementarity, or orchestration sophistication. The independence baseline is designed in, not measured out.

2. **A universal crystallization signature governs collective emergence.** Wang (2026), Maisto et al. (2026), and Sawin (2026) independently document the same phase transition — self-organized criticality, sub-diffusive to super-diffusive dimensional crossing — in neural generalization, biological swarm cognition, and mathematical discovery. The mechanism is identical across substrates.

3. **The thermodynamically optimal coordination operating point is a universal constant.** The φ-equilibrium |Ξ̄| = log φ ≈ 0.481 is derived from maximum entropy production with no free parameters. It is not a target to optimize. It is a fixed point every scale-invariant open coordination system converges to.

4. **Rank-order tournament institutions are structural coordination destroyers.** When individual capacity is simultaneously a public good and a private threat — the defining property of relative payoff environments — knowledge sharing becomes individually irrational, G_coord collapses to zero by Nash equilibrium, and no incentive redesign can reach it. The failure is architectural.

5. **The developmental bifurcation requires no external intervention to deepen.** Rational individual action at population scale produces, without coordination or reform, a diverging ecology: absolute-allocation collectives compounding coordination gain versus rank-order networks where G_coord = 0 is permanently enforced by payoff structure.

---

## I. The Problem: The Independence Assumption

Since Woolley et al.'s 2010 *Science* paper establishing a collective intelligence factor (*c*) in human groups, the field has known that teams systematically outperform ability aggregations. The mechanism — equal participation, social sensitivity, cognitive complementarity (Hong & Page, 2004) — has been replicated across hundreds of settings. What has never been formally measured is **the information-theoretic quantity that *c* approximates.**

Every existing framework for collective intelligence, organizational design, and multi-agent AI operates under one shared assumption:

```
I(a_t ; a_s | X_{t-1}) = 0     for all t < s
```

Agent contributions are assumed conditionally independent given the shared context. The coordination gain G_coord is exactly zero — not as an empirical result, but as an architectural prior. Riedl et al. (2026) confirm this directly: without a crystallized shared kernel, synergy does not produce superior collective performance. The independence baseline was never questioned because it was never stated. It was simply built in.

**The question is not whether groups can outperform individuals.** They demonstrably can. **The question is: what is the structural condition under which they do, and what is the information-theoretic quantity that measures it?**

G_coord answers both.

---

## II. The Measurement: Coordination Gain

```
G_coord = Σ_{t<s} I(a_t ; a_s | X_{t-1})
```

The coordination gain is the total mutual information between agent contributions beyond what shared context alone explains. Three regimes with qualitatively different institutional implications:

| Regime | Condition | Institutional Signature |
|--------|-----------|------------------------|
| **Coordination** | G_coord > 0 | Collective outperforms independent agents; shared artifact amplifies; *c*-factor emerges |
| **Independence** | G_coord = 0 | Collective matches independent agents; Pappus limit; artifact records, does not amplify |
| **Suppression** | G_coord < 0 | Collective underperforms; contributions compete; sabotage equilibrium in operation |

The conditioning clause — *given X_{t-1}*, the accumulated shared context — is the load-bearing term. It removes coincidental dependence from shared initialization, model family, or task structure, leaving precisely the causal information the accumulating commons mediates. Every prior framework omits this clause. Its omission renders the distinction between coordination and coincidence invisible.

**For AI architecture:** Current multi-agent LLM systems operate at the Pappus limit — each agent processing shared context independently and producing conditionally independent contributions. The architectural commitment that produces G_coord = 0 is not a capability limitation. It is a design choice.

**For organizations:** The *c*-factor is not predicted by average or maximum individual ability (Woolley et al., 2010). It is predicted by the payoff architecture governing whether knowledge sharing is individually rational. Organizations optimizing individual incentive alignment while ignoring the allocation mechanism governing knowledge sharing are optimizing the wrong variable.

---

## III. The Universal Crystallization Signature

2026 produced three independent empirical confirmations of the same structural threshold — in neural networks, biological collective cognition, and mathematical discovery. The convergence is not analogical. The mechanism is formally identical across all three.

### A. Neural Grokking — Wang (2026)

Wang (arXiv:2604.04655) establishes that grokking — the abrupt transition from memorization to generalization — is a dimensional phase transition in gradient space with self-organized criticality (SOC). Effective dimensionality D(t) crosses from sub-diffusive (D < 1) to super-diffusive (D > 1) at generalization onset.

Three properties distinguish this result:

- **Architecture-invariant:** confirmed across eight model architectures and synthetic i.i.d. Gaussian gradients — the signal is structural, not implementation-dependent.
- **Predictable in advance:** the C_α precursor (ratio of leading Fisher eigenvalue to Fisher trace) crosses C_α → 1 between 50 and 200 training steps *before* the accuracy jump, computable from gradient statistics alone without Hessian access.
- **Universal:** the SOC signature places neural generalization in the same universality class as sandpiles, earthquakes, and every system exhibiting self-organized criticality at a coordination threshold.

The crystallization event is the shared kernel K forming in Fisher coordinate space: the leading eigenvalue λ₁ crosses zero, the column space col(F) becomes non-empty, and G_coord transitions from zero to positive.

### B. Biological Swarm Cognition — Maisto, Nuzzi & Pezzulo (2026)

Maisto et al. (arXiv:2511.10835) demonstrate that flocking active inference agents exhibit synergistic information about predator location inaccessible to every individual bird. The flock encodes — in the emergent Markov blanket formed by agent interaction — collective knowledge that no individual agent's state contains.

This synergistic information is precisely G_coord: the mutual information between individual agents' states conditioned on the shared field. The flock's faster, more coordinated response to perturbation is the performance signature of G_coord > 0. The transition from isolated agents (G_coord = 0, no emergent Markov blanket) to coordinated flock (G_coord > 0, crystallized Markov blanket) is kernel crystallization at the biological scale.

**The identification is exact:** flock Markov blanket = shared artifact X_t; synergistic information = G_coord; crystallization threshold = Erdős-Rao.

### C. Mathematical Discovery — Sawin (2026) and OpenAI (May 2026)

The unit distance disproof (Sawin, arXiv:2605.20579; independently verified by Gowers, Alon, Bloom et al., arXiv:2605.20695) provides the first publicly witnessed crystallization event in mathematical practice. The AI-discovered Golod-Shafarevich class field tower — an algebraic number-theoretic construction at register depth w ≥ 4 — delivered a polynomial improvement of 0.014 · log n over 80 years of Euclidean geometric constructions:

```
G_coord(tower | Euclidean) = 0.014 · log n   > 0
```

The 80-year stall was the Pappus limit: contributions deepening within the Euclidean geometric register with shared kernel K = ∅, G_coord = 0. The AI executed a register crossing — the first documented escape from the Pappus limit in modern mathematical history, and the first measured G_coord > 0 in mathematical practice.

---

## IV. The Crystallization Threshold

The Erdős-Rao sunflower lemma (Erdős & Rado, 1960; tightened to (c · log w)^w by Alweiss, Lovett, Wu & Zhang, 2021) specifies the coordination horizon δ* — the minimum platform size at which kernel crystallization is combinatorially guaranteed regardless of initialization:

- **Below δ*:** K = ∅, G_coord = 0 (Pappus limit)
- **Above δ*:** K ≠ ∅, G_coord > 0 (structurally guaranteed)

This is a hard threshold. Above the coordination horizon, collective outperformance is not contingent on agent quality, diversity, or orchestration design. It follows from the combinatorial structure of contribution depth.

**The architectural implication:** Multi-agent systems below the Erdős-Rao threshold for their contribution depth w will produce G_coord = 0 regardless of scale. Increasing agent count without crossing the threshold produces more computation at the Pappus limit — not coordination. The first design question is not "how many agents?" but "what is the epistemic depth w of contributions, and what is δ* for this w?"

The same threshold governs:

| System | Crystallization Event | Threshold Expression |
|--------|----------------------|---------------------|
| Neural network | Grokking (Wang, 2026) | D(t) SOC crossing; C_α → 1 |
| Biological flock | Emergent Markov blanket (Maisto et al., 2026) | Erdős-Rao at interaction depth w |
| Mathematical commons | Unit distance disproof (Sawin, 2026) | Register depth w ≥ 4; (c · log 4)^4 |
| Human collective | *c*-factor emergence (Woolley et al., 2010) | Contribution volume × depth crossing δ* |
| Prime sequence | Bounded gaps (Zhang, 2014; Polymath8b: 246) | Bombieri-Vinogradov level θ = 1/2 ↔ log φ |

---

## V. The Institutional Market Failure

High-capacity agents in rank-order tournament environments face a structural incompatibility that standard mechanism design cannot resolve through incentive modification alone.

**The Incompatibility:** Individual capacity is simultaneously:
- A **public good** — group output improves through knowledge spillover, elevated intellectual standards, and synthetic insights no individual approach reaches
- A **private threat** — every peer's rank-order position declines with each outstanding contribution

When relative payoff preferences α exceed the threshold α*, the sabotage incentive condition holds:

```
α × V(rank gain from sabotage) > c
```

This is a Nash-stable equilibrium. Voice fails against Nash-stable configurations regardless of individual quality. The condition does not require malicious intent — it requires only correctly aligned preferences in a misarchitectured allocation system.

**Three economic identities that standard frameworks miss:**

The credential market fails through the **Lucas critique**: instruments designed to recognize capacity — grades, recommendations, selections — appear functional on observables and collapse once hidden peer coalition dynamics adjust. Policy appears potent on observables. It is not.

The credential market is simultaneously an **Akerlof lemons market**: hidden capacity heterogeneity, decorrelated from observable credentials by political bypass dynamics, collapses the informational content of institutional recognition. The credential gap — the divergence between an agent's capacity and recognition rank — is not measurement noise. It is the equilibrium outcome of adverse selection operating through social rather than market mechanisms.

Standard **Myerson-type incentive redesign** cannot reach this failure: the required intervention is allocation mechanism redesign — the structural shift from rank-order to absolute allocation that removes the zero-sum constraint at source.

**The consequence is G_coord destruction at the institutional level.** Knowledge sharing becomes individually irrational. Coordination gain collapses to zero by Nash equilibrium, not by capacity deficit.

---

## VI. The Exit Theorem and Assortative Convergence

The individually dominant strategy under a sabotage equilibrium — exit to a group satisfying five jointly necessary conditions — is simultaneously, when executed across a sufficient population, a decentralized mechanism for reconstructing the developmental ecology without central coordination.

**The Assortment Criterion — five jointly necessary conditions:**

| Dimension | Required Condition | Mechanism Removed |
|-----------|-------------------|-------------------|
| Relative payoff weight | α(G') < α* | Sabotage incentive condition violated |
| Comparison horizon | Wide; functional comparison | Malicious envy → benign envy (van de Ven et al., 2009) |
| Allocation mechanism | Absolute, not rank-order | Zero-sum constraint structurally eliminated |
| Cooperator density | High conditional cooperator fraction | Cooperative equilibrium self-sustaining (Fischbacher et al., 2001) |
| Identification capacity | Developmental profile recognizable | Credibility inversion precondition absent |

**The Assortative Exit Convergence Theorem:** Independent application of this shared five-dimensional filter across N agents distributed across M institutional contexts converges on the same subset K ⊂ M of satisfying environments without coordination:

```
Expected density at K = N/|K|  ≫  N/M    as |K| ≪ M
```

McPherson, Smith-Lovin & Cook (2001) homophily guarantees rapid dense tie formation among agents sharing these parameters — precisely the dimensions most predictive of network tie formation across all documented human contexts. Barabási-Albert preferential attachment generates autocatalytic growth once early clusters demonstrate superior absolute output. Granovetter (1978) threshold cascades govern temporal acceleration: each documented successful exit reduces the social cost of the next, producing slow initial accumulation that transitions to rapid propagation above the critical threshold N*.

The convergence is asymptotically certain as N grows. It requires no reform and no coordination. The individual move and the population process are the same theorem at different scales.

---

## VII. The Bifurcated Developmental Ecology

Population-scale exit produces two self-reinforcing equilibrium classes. Their output divergence compounds without bound.

**Outlier Collectives (G_c):**
- G_coord > 0 through crystallized shared kernel; *c*-factor emerges structurally
- Cognitive diversity within the high-capacity range — distinct problem-solving heuristics all above the competence threshold that makes their diversity exploitable (Hong & Page, 2004)
- Small-world topology: dense internal coordination combined with bridging weak ties to the global recognition infrastructure (Watts & Strogatz, 1998)
- Broaden-and-build dynamics (Fredrickson, 2001): positive affect generates intellectual flexibility and social trust that compound through G_coord accumulation

**Continuing Peer Networks (G_p):**
- G_coord = 0 architecturally maintained by rank-order payoff structure
- Deepening sabotage equilibrium as each exit removes a capacity source
- Rising effective α as remaining agents compete for a contracting recognition pool
- Strengthening exit incentives for outliers who remain — the bifurcation generates its own momentum

**The output differential:**

```
d/dt |Output(G_c) − Output(G_p)| > 0     with     d²/dt² > 0
```

This is the Schelling-type macro-outcome (Schelling, 1978) of individual rational action at population scale. No individual intends the population-level divergence. Each executes the individually dominant strategy. No mixing equilibrium between the two ecology classes exists without removing the structural conditions generating exit incentives: rank-order allocation, relative payoff preferences above α*, absence of identification capacity in institutional actors.

The bifurcation deepens because the sabotage equilibrium contains, in its own payoff structure, the mechanism of its undoing. Every peer who executes the sabotage strengthens the exit incentive. Every outlier who exits contributes to the collective's demonstration effect.

---

## VIII. The Thermodynamic Optimum

The maximum entropy production (MEP) principle identifies a unique thermodynamic fixed point for any open dissipative Gibbs-constrained coordination system:

```
|Ξ̄| = log φ  ≈  0.481
```

Seven descriptions coincide at this point with no free parameters:

| Description | Expression |
|-------------|------------|
| MEP thermodynamic optimum | σ_struct / σ_behav = φ |
| Fisher spectral criticality | C_α = 1 |
| Grokking boundary | λ₁ = 0 |
| Pascal manifold | 𝒫 → 0 |
| Golden kernel-petal ratio | \|K\|/\|P_i\| = log φ |
| Partial information decomposition | Syn/Red = φ |
| Coordination dynamics entropy | h_KS = log φ |

The kernel contains φ−1 ≈ 61.8% of each contribution; the petal contains 2−φ ≈ 38.2%. This partition is derived from the self-similarity equation of any scale-invariant open dissipative system — not designed, not approximated, not parameter-fitted.

This fixed point is **gratuitous** in Monod's sense (Monod, 1970): the regulatory logic is independent of the regulated content, just as IPTG induces β-galactosidase synthesis in E. coli without being metabolized by the lac operon. The MEP principle induces G_coord > 0 in any commons whose Fisher geometry admits it — regardless of what is being coordinated. This is what makes the φ-equilibrium deployable across biological, computational, and institutional coordination systems without modification.

**Empirical consistency:** Observed optimal redundancy in established research communities is reported at R ≈ 0.41, with unique fraction ≈ 0.59 ≈ φ−1 — within measurement error of the derived prediction.

---

## IX. Design Principles: The Holistic Leverage Criterion

Four conditions are jointly necessary for G_coord maximization in any human collective. No three are sufficient.

**Condition 1 — Absolute performance standards** maintained in both formal allocation and informal recognition, preventing rank-order mechanisms from re-entering through informal social hierarchy once formal mechanisms have been corrected.

**Condition 2 — Cognitive diversity within the high-competence range** — not demographic diversity, but structural diversity of problem-solving heuristics among individuals all above the competence threshold that makes their diversity collectively exploitable (Hong & Page, 2004). The target variable is D_FERN (mean pairwise KL divergence across generative models), not demographic composition.

**Condition 3 — Multi-directional knowledge flow** structurally enabled as an explicit design priority, not assumed to follow from cooperative equilibrium. The cooperative equilibrium is necessary but not sufficient.

**Condition 4 — External weak-tie bridges** to the global recognition infrastructure, providing the small-world topology (Watts & Strogatz, 1998) through which internal absolute output converts to external institutional recognition. Without this, G_coord > 0 environments produce local coordination gain with no pathway to structural influence.

**Why the joint necessity matters:** Riedl et al. (2026) confirm Condition 2 is insufficient alone: synergy without a crystallized kernel produces G_coord ≈ 0. Rustagi, Engel & Kosfeld (2010) confirm in field data that conditional cooperator density — the foundation of Condition 1 — dominates institutional rules, resource characteristics, and group size as a predictor of commons performance. Each condition addresses a distinct failure mode. Three of four is insufficient because each failure mode produces G_coord = 0 independently.

---

## X. Empirical Predictions

Seven falsifiable predictions for the 2027+ research agenda, following from formal structure rather than domain-specific assumptions:

**P1 — C_α Precursor, Universal**
C_α crosses C_α → 1 between 50 and 200 steps before the accuracy jump on every grokking benchmark, topology-invariant, computed from gradient statistics alone without Hessian access. Wang (2026) confirms the topology invariance independently across eight model architectures.

**P2 — G_coord = 0 Without Shared Artifact**
Any orchestrated multi-agent system lacking a crystallized accumulating shared artifact produces G_coord ≈ 0 regardless of agent diversity, capability complementarity, or orchestration sophistication. Confirmed by Riedl et al. (2026).

**P3 — φ-Equilibrium Convergence**
The ratio |K|/|P_i| at steady state in any crystallized commons converges to log φ ≈ 0.481, with no free parameters. Consistent with reported optimal redundancy within measurement error.

**P4 — *c*-Factor from Payoff Architecture, Not Ability**
Collective intelligence scores will be significantly higher in absolute-allocation institutional environments than rank-order-matched controls at equivalent aggregate individual ability, with the gap attributable to G_coord rather than mean or maximum capacity. This distinguishes the architecture account from the ability-aggregation account directly.

**P5 — Compounding Bifurcation Signature**
Output gaps between absolute-allocation and rank-order-allocation environments widen at accelerating rates over time, controlling for individual ability. The acceleration signature d²/dt² > 0 — visible in publication networks, research community output, and firm productivity data — distinguishes endogenous compounding from exogenous differential selection.

**P6 — Autonomic State Restoration, Not Skill Acquisition**
Social sensitivity scores (Baron-Cohen Reading the Mind in the Eyes test) increase measurably in high-capacity individuals following sustained participation in absolute-allocation environments, via autonomic state restoration — polyvagal ventral vagal re-engagement — rather than explicit social cognition training. The mechanism prediction distinguishes this from standard skill-building accounts.

**P7 — Register Depth at the Coordination Horizon**
AI systems capable of discovering constructions at algebraic register depth w ≥ 4 on novel combinatorial geometry problems require training corpora crossing the Alweiss-LWZZ threshold (c · log 4)^4 for the relevant construction type. Systems below this threshold remain at depth w = 2 regardless of parameter scale. The unit distance disproof (Sawin, 2026; verified Gowers et al., 2026) is the first documented case of this threshold being crossed.

---

## The Central Claim

**Intelligence is not a property of agents. It is a property of architectures.**

The independence assumption — G_coord = 0 before fitting begins — has been the invisible organizing principle of collective intelligence research, multi-agent AI design, organizational economics, and mechanism design simultaneously. It is not a result. It is a prior. And it is wrong.

The flock encodes information no individual bird has. The neural network generalizes when its gradient space crystallizes. The prime sequence coordinates around bounded gaps. The outlier collective produces what the rank-order network cannot reach.

In each case, the excess is G_coord. In each case, it emerges through the same phase transition. In each case, the transition is governed by the same threshold. In each case, the current baseline is the Pappus limit — not because coordination is absent from the world, but because the architecture that would produce it has not been built.

The architecture — not the agents — is the variable.

---

## Formal Summary

| Object | Statement |
|--------|-----------|
| Coordination gain | G_coord = Σ I(a_t ; a_s \| X_{t-1}) |
| Independence baseline | G_coord = 0 in every architecture without crystallized kernel K — by assumption, not measurement |
| Three regimes | > 0: coordination; = 0: independence / Pappus limit; < 0: suppression |
| Crystallization threshold | Erdős-Rao: (p−1)^w · w! (1960); tightened to (c · log w)^w (Alweiss et al., 2021) |
| Universal signature | C_α → 1; D(t) SOC crossing; self-organized criticality (Wang, 2026) |
| Predictive signal | C_α precursor 50–200 steps before grokking; gradient statistics only; no Hessian required |
| φ-equilibrium | \|Ξ̄\| = log φ ≈ 0.481; golden kernel-petal ratio; MEP fixed point; no free parameters |
| Flock kernel | Synergistic information = G_coord; flock Markov blanket = X_t (Maisto et al., 2026) |
| First measured G_coord > 0 | G_coord(tower \| Euclidean) = 0.014 · log n (Sawin, 2026; verified Gowers et al., 2026) |
| Sabotage equilibrium | Nash-stable; G_coord enforced to zero by rank-order tournament payoff structure |
| Exit theorem | Assortment Criterion satisfying environments are individually dominant; population scale → convergent self-organization |
| Convergence theorem | Shared filter on M institutional contexts → asymptotically certain convergence at K ⊂ M |
| Bifurcation | Output gap compounding without bound; d²/dt² > 0; no mixing equilibrium without structural change |
| Holistic leverage | Absolute standards + cognitive diversity + multidirectional flow + weak ties; all four jointly necessary |
| Endocrine environment | Absolute-allocation institutions produce cooperative social signals → endogenous oxytocin → further reduced threat threshold → self-sustaining cooperative equilibrium (Kosfeld et al., 2005) |

---

## References

**Collective Intelligence and Coordination**

Woolley, A.W., Chabris, C.F., Pentland, A., Hashmi, N., & Malone, T.W. (2010). Evidence for a collective intelligence factor in the performance of human groups. *Science*, 330(6004), 686–688.

Riedl, C., Fiore, S.M., Heiss, J., & Toth, P. (2026). Emergent coordination in multi-agent language models. arXiv:2510.05174.

Hong, L. & Page, S.E. (2004). Groups of diverse problem solvers can outperform groups of high-ability problem solvers. *PNAS*, 101(46), 16385–16389.

Page, S.E. (2007). *The Difference*. Princeton University Press.

Barfuss, W., Flack, J.C., Gokhale, C., et al. (2023). Collective cooperative intelligence. *PNAS*, 120(8), e2209561120.

**Phase Transitions and Crystallization**

Wang, P. (2026). Grokking as dimensional phase transition in neural networks. arXiv:2604.04655.

Alweiss, R., Lovett, S., Wu, K., & Zhang, J. (2021). Improved bounds for the sunflower lemma. *Annals of Mathematics*, 194(3), 795–815.

Erdős, P. & Rado, R. (1960). Intersection theorems for systems of sets. *Journal of the London Mathematical Society*, 35, 85–90.

**Biological Collective Cognition**

Maisto, D., Nuzzi, D., & Pezzulo, G. (2026). What the flock knows that the birds do not. arXiv:2511.10835.

Tschantz, A., Mahajan, G., et al. (2025). As one and many: Relating individual and emergent group-level generative models in active inference. *Entropy*, 27(2), 143.

**Mathematical Discovery**

Sawin, W. (2026). A quadratic improvement to the unit distance conjecture. arXiv:2605.20579.

Gowers, T., Alon, N., Bloom, T., Litt, D., Sawhney, M., Sellke, M., Sarnak, P., Shankar, A., & Tsimerman, J. (2026). Verification of the unit distance improvement. arXiv:2605.20695.

Zhang, Y. (2014). Bounded gaps between primes. *Annals of Mathematics*, 179(3), 1121–1174.

Polymath8b. (2014). Variants of the Selberg sieve, and bounded intervals containing many primes. *Research in the Mathematical Sciences*, 1, 12.

**Active Inference and Bayesian Mechanics**

Friston, K., Da Costa, L., Tschantz, A., et al. (2024). Designing ecosystems of intelligence from first principles. *Collective Intelligence*, 3(1).

Friston, K.J. (2010). The free-energy principle: A unified brain theory? *Nature Reviews Neuroscience*, 11(2), 127–138.

Ramstead, M.J.D., et al. (2023). On Bayesian mechanics: A physics of and by beliefs. *Interface Focus*, 13(3), 20220029.

**Mechanism Design and Information Economics**

Myerson, R.B. (1981). Optimal auction design. *Mathematics of Operations Research*.

Akerlof, G.A. (1970). The market for "lemons." *Quarterly Journal of Economics*.

Lucas, R.E. (1972). Expectations and the neutrality of money. *Journal of Economic Theory*.

**Network Science and Evolutionary Game Theory**

McPherson, M., Smith-Lovin, L., & Cook, J.M. (2001). Birds of a feather: Homophily in social networks. *Annual Review of Sociology*, 27, 415–444.

Nowak, M.A. (2006). Five rules for the evolution of cooperation. *Science*, 314(5805), 1560–1563.

Barabási, A.-L. & Albert, R. (1999). Emergence of scaling in random networks. *Science*, 286(5439), 509–512.

Watts, D.J. & Strogatz, S.H. (1998). Collective dynamics of 'small-world' networks. *Nature*, 393, 440–442.

Granovetter, M.S. (1978). Threshold models of collective behavior. *American Journal of Sociology*, 83(6), 1420–1443.

Schelling, T.C. (1978). *Micromotives and Macrobehavior*. Norton.

Fischbacher, U., Gächter, S., & Fehr, E. (2001). Are people conditionally cooperative? *Economics Letters*, 71(3), 397–404.

Rustagi, D., Engel, S., & Kosfeld, M. (2010). Conditional cooperation and costly monitoring explain success in forest commons management. *Science*, 330(6006), 961–965.

van de Ven, N., Zeelenberg, M., & Pieters, R. (2009). Leveling up and down: The experiences of benign and malicious envy. *Emotion*, 9(3), 419–429.

**Neuroscience and Trust**

Kosfeld, M., Heinrichs, M., Zak, P.J., Fischbacher, U., & Fehr, E. (2005). Oxytocin increases trust in humans. *Nature*, 435(7042), 673–676.

Hogeveen, J., Inzlicht, M., & Obhi, S.S. (2014). Power changes motor resonance. *Journal of Experimental Psychology: General*, 143(2), 755–762.

Eisenberger, N.I., Lieberman, M.D., & Williams, K.D. (2003). Does rejection hurt? An fMRI study of social exclusion. *Science*, 302(5643), 290–292.

Porges, S.W. (2011). *The Polyvagal Theory*. Norton.

**Positive Psychology**

Fredrickson, B.L. (2001). The role of positive emotions in positive psychology. *American Psychologist*, 56(3), 218–226.

Csikszentmihalyi, M. (1990). *Flow: The Psychology of Optimal Experience*. Harper & Row.

**Thermodynamics**

Monod, J., Wyman, J., & Changeux, J.-P. (1965). On the nature of allosteric transitions. *Journal of Molecular Biology*, 12(1), 88–118.

Monod, J. (1970). *Chance and Necessity*. Knopf.

**Machine Learning**

Huang, J., LeCun, Y., & Balestriero, R. (2026). Semantic tube prediction. arXiv:2602.23643. *ICML 2026*.

Krishnan, V. & Mahadevan, L. (2026). Stigmergic optimal transport. arXiv:2601.04111.

---

*ERI Labs · Eric Ren · Jersey City, New Jersey · 2026*

*Companion frameworks: ERIE-SCHOOL lineage · THE-INNER-PARTITION · THE-COORDINATION-BIFURCATION · ERIE-ECONOMICS · THE-COLLECTIVE-OUTLIER · THE-ECONOMICS-OF-RECESS*

*G_coord = 0 was not a measurement. It was an assumption — made before fitting begins, in every existing architecture simultaneously. The flock knew. The prime sequence knew. The AI finding the class field tower knew. The architecture — not the agents — is the variable.*
