# AI, Blockchain and Platform Economics  
### Why Some Hype-Intensive Platforms Struggle to Make Money

*Working paper – draft version*  

---

## Abstract

Over the last decade, investors have poured hundreds of billions of dollars into AI infrastructure, blockchain ecosystems and platform businesses such as ride-hailing and food delivery. Market capitalisations have often moved much faster than profits. By contrast, traditional food and FMCG companies – with modest growth and little hype – frequently post stable operating margins and high cash conversion.

This paper offers a compact, data-informed explanation of this apparent puzzle. Using stylised facts from public financial reports and sector studies, it compares the economics of three groups:

1. **AI hyperscalers and AI-as-a-service providers**;  
2. **Blockchain ecosystems and crypto-asset platforms**;  
3. **Traditional FMCG and food companies**, together with selected platform businesses (ride-hailing, delivery).

The paper argues that three mechanisms jointly explain why hype-intensive platforms may struggle to generate durable, high-quality profits:

- extreme **capital intensity** and long payback periods (especially for AI infrastructure);
- weak or unstable **value capture** in open, token-based ecosystems (blockchain);
- strong **two-sided bargaining power** from users, workers and regulators in gig-and-platform models.

The comparison with “boring” FMCG businesses highlights how moderate growth, lower capital intensity and durable brands can produce more resilient unit economics. The paper concludes with a short checklist for founders and early-stage investors.

All results are **illustrative**: they show what *could* happen under reasonable assumptions, not what *will* necessarily materialise.

---

## 1. Introduction

Over the last years, a large share of technology narratives has been dominated by three themes:

- **AI**, especially foundation models and the data-center infrastructure that powers them;
- **Blockchain and crypto-assets**, promising decentralised finance and programmable money;
- **Platform businesses** – from ride-hailing to food delivery – intermediating fragmented markets at scale.

In financial terms, these sectors combine:

- very high **revenue growth** at times;  
- very volatile **profitability**;  
- substantial **capital expenditure** and customer-acquisition costs.

At the same time, traditional food and fast-moving consumer goods (FMCG) groups, with their slow growth and relatively simple technology, often show operating margins in the mid-teens or higher and strong cash generation.

This paper is a small attempt to give this pattern a simple, transparent explanation using:

- a few stylised profitability and capex metrics across sectors;  
- a lightweight framework based on unit economics and platform economics;  
- qualitative evidence from public sources.

The focus is intentionally pragmatic: what should **founders, operators and early-stage investors** keep in mind when comparing AI / blockchain / platform bets with more “traditional” business models?

---

## 2. Stylised facts across sectors

### 2.1 Capital intensity

AI infrastructure is extremely capital-intensive. Hyperscalers are collectively forecast to spend several hundred billion dollars per year on data-centre infrastructure, with cumulative AI-oriented capex projected in the trillions over the next decade.[^mckinsey][^iot] Even if these investments are concentrated in a few large players, they set the competitive baseline for the sector.

Blockchain ecosystems, by contrast, rely less on physical assets and more on:

- software development,
- token incentives,
- security and compliance.

Capital outlays are lower, but the cost of maintaining security, liquidity and regulatory compliance is non-trivial.

Traditional FMCG and food groups face:

- large but relatively **stable** investments in plants, brands and distribution;
- capex and R&D that tend to be a modest share of sales compared with AI infrastructure.

### 2.2 Profitability patterns

A few empirical regularities emerge from public data (all numbers are indicative ranges rather than point estimates):

- Large consumer-goods companies often report **operating margins** around 15–25% over the cycle.[^fmcg]
- Major platform businesses such as global ride-hailing have only recently moved into positive operating margins, typically in the high single digits to low teens, after years of heavy losses and subsidy-driven growth.[^uber1][^uber2]
- Crypto-asset platforms and exchanges can show very high revenues in boom years, but profitability is extremely cyclical, with some players reporting large losses in downturns despite high trading volumes.[^crypto1][^crypto2]

These patterns suggest that **scale and growth alone** do not guarantee attractive, durable profits. The structure of the business model matters.

---

## 3. A simple framework

The paper uses a deliberately simple framework with three building blocks:

1. **Unit economics** – contribution margin per transaction, user or compute unit;
2. **Capital intensity and payback** – how much irreversible investment is required upfront, and over which time horizon it can be recovered;
3. **Platform value capture** – how the surplus created on the platform is divided among:
   - end users,
   - suppliers or workers,
   - regulators and tax authorities,
   - the platform owner.

### 3.1 Unit economics

Let:

- \( p \) = average price per unit (ride, delivery, compute hour, transaction);
- \( c_v \) = variable cost per unit (driver pay, food cost, variable energy, customer support);
- \( c_f \) = fixed cost per period (platform engineering, compliance, headquarters, marketing);
- \( Q \) = volume.

Then contribution margin per unit is:

\[
m = p - c_v
\]

and operating margin (before capex) is:

\[
\text{OM} = \frac{(p - c_v)Q - c_f}{pQ}.
\]

Platforms with strong competition or regulatory caps may find it hard to increase \( p \) or reduce \( c_v \) without eroding the quality of the service.

### 3.2 Capital intensity and payback

In AI infrastructure, a large share of costs takes the form of:

- long-lived investments in data centres, chips and power;
- long training cycles for foundation models.

Let \( K \) denote cumulative capex and \( CF_t \) the free cash flow in year \( t \). Simple discounted-cash-flow calculations show that high \( K \) requires either:

- very high future \( CF_t \), or
- long horizons with low discount rates.

If competition and regulation prevent very high margins, the result is a long and uncertain payback period.

### 3.3 Value capture in open ecosystems

Blockchain ecosystems add further complexity:

- networks often issue **tokens** that dilute value capture;
- the protocol community, validators and users all expect to share in the surplus;
- open-source competition can erode any single project’s ability to charge for services.

This makes it hard for one entity to accumulate the kind of stable, compounding profits seen in concentrated FMCG markets.

---

## 4. Three mechanisms behind the profitability gap

### 4.1 AI: heavy capex, delayed economics

AI infrastructure is a classic case of **front-loaded investment**:

- massive capex on data centres, GPUs and power contracts;
- uncertain long-term demand and pricing for AI services.

Even if the long-run economics are attractive, in the short-to-medium term:

- depreciation and financing costs depress accounting profits;
- competition among hyperscalers can compress prices for AI compute;
- demand is highly sensitive to macro cycles and to the success of specific AI applications.

The result is a period where revenue growth is impressive, but **economic profit** (after the cost of capital) may be modest or negative.

### 4.2 Blockchain: weak value capture and high fragility

In blockchain ecosystems, the main risks are:

1. **Value leakage to tokens and speculators.**  
   Token-based incentives mean a large share of value accrues to early token holders and intermediaries, not to the protocol team itself.

2. **Regulatory and trust overhang.**  
   Crypto-asset markets have experienced repeated boom-and-bust cycles, with regulatory scrutiny increasing after each shock. This raises the cost of compliance and limits the ability to scale certain revenue streams.

3. **Open-source competition.**  
   Protocol code can often be forked, making it difficult to sustain high take-rates without losing liquidity or users.

The combination of these forces means that even large, systemically important platforms may struggle to maintain high, stable operating margins over long horizons.

### 4.3 Ride-hailing and delivery: intense competition for surplus

Ride-hailing and food-delivery platforms illustrate another variant of the same problem:

- users expect low prices and high convenience;
- drivers and couriers demand adequate pay and flexibility;
- regulators pay increasing attention to labour conditions and market power.

In such an environment, the platform is forced to **share most of the surplus** it creates in order to keep both sides on board. Margins can improve over time, but the equilibrium is often a thin-margin, high-volume business rather than a high-margin monopoly.

---

## 5. Why “boring” FMCG can be attractive

Traditional food and FMCG businesses start from a different configuration:

- demand is stable and recurring;
- physical products and brands create **differentiation** that is harder to copy than software alone;
- distribution networks and shelf space act as barriers to entry.

Operating margins in the mid-teens or higher are not unusual, and capital intensity is moderate compared with AI infrastructure. Free cash flow tends to be more predictable, allowing companies to:

- pay regular dividends,
- reinvest in brands and process innovation,
- deleverage when needed.

For an investor focused on **risk-adjusted** returns, this profile can be more attractive than a highly uncertain AI or crypto bet, even if the latter offers explosive upside in optimistic scenarios.

---

## 6. Implications for founders and investors

For founders considering AI, blockchain or platform business models, this paper suggests a few questions to ask early:

1. **Unit economics:**  
   - After realistic assumptions on pricing and variable costs, is contribution margin per unit clearly positive?  
   - How sensitive is it to competition and regulation?

2. **Capital intensity:**  
   - How much irreversible capex is required before the model stabilises?  
   - Over how many years does it realistically pay back?

3. **Value capture:**  
   - Who ultimately captures the surplus – users, workers, token holders, or the company?  
   - Is there a credible path to durable margins without relying purely on market power?

4. **Comparison benchmark:**  
   - Is this business actually superior, on a risk-adjusted basis, to a well-run “boring” business with clear, simple economics?

For early-stage investors, the main takeaway is to **discount hype narratives** and focus on:

- economics per unit,
- the scale of irreversible investment,
- the credibility of the value-capture mechanism.

---

## 7. Limitations and directions for further work

This working paper is deliberately simple. Key limitations include:

- Reliance on **high-level, aggregated numbers** rather than a full panel dataset.
- Focus on a small number of representative sectors and firms.
- Absence of formal econometric modelling: all scenarios are back-of-the-envelope.

Future versions could:

- build a proper dataset of listed AI, blockchain, platform and FMCG firms;
- estimate more rigorous relationships between capex intensity, network-effect strength and profitability;
- explore case studies of specific companies that transitioned from hyper-growth to sustainable profitability (or failed to do so).

---

## References (illustrative)

- Industry reports and financial statements of major AI hyperscalers and cloud providers.  
- Sector studies on data-centre capex and AI infrastructure.  
- Public financial data for listed FMCG and consumer-goods companies.  
- Research and policy papers on crypto-asset markets and financial stability.  
- Academic and practitioner work on platform economics, network effects and gig-economy labour markets.
