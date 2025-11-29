### Why AI Looks Likely to Stay

---

## Abstract

This paper argues that artificial intelligence (AI) is highly likely to
remain a **persistent general-purpose technology**, not a transient
speculative bubble. The argument is threefold:

1. **Scale and persistence of investment.**  
   Global data-centre equipment and infrastructure spending exceeded
   roughly USD 290 billion in 2024, with the top hyperscalers
   accounting for more than half of that, largely driven by AI-related
   workloads. Forward-looking estimates put cumulative AI-capable
   data-centre capex in the trillions of dollars towards 2030.

2. **Breadth of enterprise adoption.**  
   Recent global surveys report that around 80–90% of large
   organisations use AI in at least one business function, and that a
   rising minority report measurable EBIT or productivity gains.

3. **Micro-level productivity evidence.**  
   Experimental and firm-level studies find sizeable productivity
   effects—often in the range of 5–30%—for tasks such as coding,
   customer support, document drafting, analysis and translation.

Using simple economics of capital intensity, unit economics and
general-purpose technologies, the paper concludes that AI is more akin
to electricity or cloud computing—costly to build, unevenly deployed,
but structurally embedded—than to a purely speculative fad.

All magnitudes are **stylised**; they illustrate what could happen under
reasonable assumptions, not precise forecasts.

---

## 1. Introduction

Artificial intelligence combines several features that make it a strong
candidate for a **general-purpose technology**:

- it can be applied across many sectors and tasks;
- it is continually improving thanks to data and model scale;
- it requires complementary investments in skills, data and
  organisational change.

At the same time, the current wave—centred on large language models and
generative AI—has triggered concerns about over-investment and hype. The
central question of this paper is:

> Are we witnessing a speculative overshoot or the durable build-out of
> a new layer of digital infrastructure?

To answer, the paper assembles stylised facts on investment, adoption
and productivity, and links them through simple economic relationships.

---

## 2. Investment scale and capital intensity

### 2.1 Global AI-relevant capex

Recent market-research estimates indicate that:

- global data-centre equipment and infrastructure spending reached
  roughly **USD 290 billion in 2024**, supported by rapid growth in
  AI-capable hardware;
- the **top 10 hyperscalers** (large cloud and internet platforms)
  accounted for more than half of total data-centre capex;
- projections for 2030 suggest an aggregate requirement on the order of
  **USD 6–7 trillion** in data-centre investment, of which about
  **USD 5 trillion** dedicated to AI workloads.

These numbers imply an annual AI-related capex flow of several hundred
billion dollars for an extended period. The only historical analogues at
this scale are large network infrastructures (electricity grids,
telecoms, broadband and mobile).

### 2.2 AI infrastructure as a capital stock

Let:

- $K$ = stock of AI-relevant capital (data centres, chips, networking);
- $I$ = annual AI-relevant investment;
- $\delta$ = depreciation rate (including technological obsolescence).

In a simple perpetual-inventory model:

$$
K_{t+1} = (1 - \delta)K_t + I_t.
$$

With $I_t$ of the order of USD 300–400 billion per year and
$\delta \approx 10\%$–$15\%$, the steady-state capital stock $K$ implied
by sustained flows is:

$$
K^\* \approx \frac{I}{\delta},
$$

which easily reaches the multi-trillion-dollar range.  
It is economically implausible that such an asset base would be built
and then abandoned quickly: the more realistic risk is **lower-than-hoped
returns**, not complete disappearance.

---

## 3. Enterprise adoption

### 3.1 Breadth vs depth

Recent global surveys of executives report that:

- around **80–90% of organisations** use some form of AI or analytics in
  at least one business function;
- a much smaller share (around one-third) report **significant,
  enterprise-wide impact** on EBIT or productivity.

This pattern—high adoption, lower maturity—is typical for new general-
purpose technologies: firms experiment broadly before redesigning
processes around the technology.

### 3.2 Where AI is actually used

Across surveys and case studies, several use-case clusters recur:

- **Customer interaction**: chatbots, support triage, summarising
  interactions, drafting responses.
- **Software and IT**: code generation, test automation, log analysis.
- **Knowledge work**: drafting and editing documents, research memos,
  contracts and reports.
- **Data analysis**: forecasting demand, detecting anomalies, fraud or
  outliers.
- **Translation and localisation**: internal documentation, product
  support, marketing copy.

The key fact is that these are **core cost centres** in modern
organisations. Even moderate efficiency gains—say 10–20% reductions in
labour time—translate into meaningful economic value.

---

## 4. Micro-level productivity evidence

### 4.1 Experimental studies

Randomised-control trials in customer support, programming, consulting
and writing tasks typically find:

- productivity gains (more tasks completed or higher quality) in the
  range of **5–35%**;
- larger gains for **less experienced workers**;
- mixed effects on quality depending on task complexity.

Denote:

- $y_0$ = baseline output per worker hour;
- $g$ = proportional productivity gain from AI support;
- $w$ = wage per hour;
- $c_{\text{AI}}$ = effective AI cost per worker hour (licence + infra).

Then unit labour cost without AI is:

$$
ULC_0 = \frac{w}{y_0},
$$

while with AI it becomes:

$$
ULC_1 = \frac{w + c_{\text{AI}}}{(1 + g)y_0}.
$$

AI is cost-reducing if $ULC_1 < ULC_0$, that is:

$$
\frac{w + c_{\text{AI}}}{1 + g} < w
\quad \Rightarrow \quad
c_{\text{AI}} < gw.
$$

With $g = 20\%$ and a wage of, say, USD 40/hour, AI support can cost up
to **USD 8/hour** and still reduce unit labour costs. For many SaaS
pricing models, this inequality holds comfortably.

### 4.2 Firm-level evidence

Firm case studies in accounting, legal, marketing and software
development show that:

- AI-assisted teams often complete certain document or coding tasks in
  **half the time**;
- error rates may fall when AI is used as a second pair of eyes;
- value materialises only when workflows, training and governance are
  adapted.

This is consistent with the view that AI is already **embedded in
production processes**, not just in speculative trading.

---

## 5. Economics of AI infrastructure

### 5.1 Return on compute

Consider a simplified AI-infrastructure provider that invests a capital
stock $K$ and sells compute services.

Let:

- $p$ = average price per compute unit;
- $c_v$ = variable cost per compute unit (energy, operations);
- $U$ = compute units sold per year;
- $c_f$ = fixed operating cost per year (staff, R&D, software);
- $r$ = required rate of return (cost of capital).

Contribution per compute unit is:

$$
m = p - c_v.
$$

Operating cash flow before capex is:

$$
CF_{\text{op}} = mU - c_f.
$$

Define a **return on compute**:

$$
\text{ROC} = \frac{CF_{\text{op}}}{K}.
$$

If $K = \$50$ billion and $CF_{\text{op}} = \$5$ billion, then
$\text{ROC} = 10\%$. If the cost of capital is in the 8–12% range, this
is borderline acceptable.

Scenarios:

- **High-demand case**: strong utilisation and pricing yield
  $CF_{\text{op}} = \$10$–12 billion, so ROC is 20–24% and payback under
  5 years.
- **Central case**: $CF_{\text{op}} = \$5$ billion, ROC ≈ 10%.
- **Low-demand case**: $CF_{\text{op}} = \$2$ billion, ROC ≈ 4%, below
  cost of capital.

The existence of these scenarios does not determine which one will
occur, but it shows that **plausible parameter ranges** yield acceptable
returns; combined with the irreversible nature of $K$, this makes an
abrupt exit unlikely.

---

## 6. Risks and frictions

AI’s durability as a technology does not mean smooth economics. Key
risks include:

- **Over-investment**: if too many players build overlapping capacity,
  ROC can be depressed for years.
- **Governance and safety**: poor risk management may trigger regulation
  that raises costs or restricts business models.
- **Organisational inertia**: many firms will fail to redesign processes
  and thus will not capture the potential productivity gains.
- **Distributional effects**: labour-market adjustment costs and
  concentration of market power could create political pushback.

These risks affect **who** captures value and **how much**, but they do
not by themselves imply that AI as a technology will disappear.  
Instead, they shape the equilibrium between AI providers, complementors
and regulators.

---

## 7. Conclusion

The economic case for AI as a durable, embedded technology rests on:

- trillions of dollars in planned and ongoing infrastructure investment;
- broad but uneven enterprise adoption across sectors;
- consistent micro-evidence of productivity gains in concrete tasks.

Unlike many crypto-asset narratives, AI’s value proposition does not rely
primarily on price appreciation of a token. It is rooted in **cost
savings and quality improvements** in everyday production processes:
fraud checks completed in hours instead of weeks, code written or
reviewed faster, documents drafted more efficiently.

From an investor or founder perspective, the key question is **where**
in the AI value chain returns will concentrate (infrastructure vs
applications vs integration), not whether AI itself will vanish. Subsequent
papers in this series compare this trajectory with blockchain, platforms
and FMCG businesses.

---

## References (indicative)

This paper draws on:

- market-research reports on global data-centre infrastructure and AI-related capex;
- surveys of enterprise AI adoption and value capture by global consulting firms;
- OECD and central-bank studies on AI and productivity;
- experimental and firm-level papers on generative-AI productivity effects.
