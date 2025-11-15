# Beyond the Hype: Economics of AI, Blockchain and Winner-Takes-Most Platforms

_Working draft – not investment advice._

## 1. Introduction

Over the last decade, three stories have dominated tech:

1. **Blockchain** would “eat the world”.
2. **AI** would become the most profitable technology ever built.
3. “Platform” businesses like **Uber** and **DoorDash** would scale effortlessly with near-zero marginal costs.

Reality is more complicated.

- Blockchain attracted enormous speculative capital – mainly in the form of crypto tokens – but **enterprise blockchain revenues** remain small compared with global IT and cloud spending.
- AI already generates **tens or even hundreds of billions of dollars in revenue**, yet many core players – including OpenAI – run **massive operating losses**.
- Ride-hailing and food-delivery platforms, after a decade of subsidy-driven growth, are just now inching towards profitability, often with very thin margins.

At the same time, “boring” companies in food and FMCG – Nestlé, Unilever, Heineken – continue to deliver **mid-teens to high-teens operating margins** relatively consistently.

This paper uses a small, transparent dataset and a few toy models to explore why.

---

## 2. Markets: blockchain vs AI vs generative AI

The sheet `Markets_overview` in `data/ai_blockchain_platforms_dataset.xlsx` collects approximate market-size estimates for:

- **Blockchain technology** and **Blockchain-as-a-Service (BaaS)**  
- **AI overall** (all segments)  
- **Generative AI** (a subset of AI)

Key patterns:

- The **blockchain technology** market was worth only a few billions of dollars in the early 2020s and is still measured in **single-digit billions** as of 2024, with forecasts reaching tens of billions by 2030.
- **BaaS** follows a similar pattern: from under 2 bn USD in 2019 to a few tens of billions by 2027 in optimistic scenarios.
- The **AI market overall** is already **two orders of magnitude larger** than enterprise blockchain and is forecast to reach several hundred billions by 2030.
- **Generative AI** is a relatively small slice of AI today (tens of billions) but is expected to grow faster than the broader AI market.

The contrast is straightforward:

- **Blockchain**: huge narrative, modest recurring revenues.
- **AI**: already large revenue pool – but the economics behind those revenues are expensive.

---

## 3. Company economics: AI labs, platforms, and “boring” FMCG

### 3.1 AI labs – high revenue, huge losses

OpenAI is a good example of the current AI economics:

- Rapidly growing revenue, reaching multiple billions of USD per year.
- At the same time, **very large operating losses**, driven by:
  - compute and data-centre costs,
  - R&D,
  - sales & marketing,
  - stock-based compensation,
  - revenue-sharing with strategic partners.

In other words: AI proves that **revenue ≠ profit**, especially when the underlying production function is extremely capital-intensive.

### 3.2 Platforms – thin margins in ride-hailing and delivery

Ride-hailing and food-delivery platforms (Uber, Lyft, Grab, DoorDash) illustrate the “winner-takes-most” logic:

- After years of heavy losses, several players now report:
  - positive net income, or
  - positive adjusted EBITDA.
- However, margins remain small:
  - **low single-digit percentages** on gross bookings or revenue.
- Small changes in:
  - subsidies, promotions,
  - driver incentives,
  - competitive intensity,
  can flip the business from profit to loss.

The central tension:

> If you cut discounts and marketing too early to “become profitable”, you may shrink GMV and revenue so much that profitability never appears.

### 3.3 FMCG and beverages – boring but beautiful margins

Food and FMCG giants (Nestlé, Unilever, Heineken) live in a different universe:

- Revenues in the tens of billions of CHF/EUR.
- **Operating margins in the mid- to high-teens**.
- Stable demand, strong brands, and entrenched distribution networks.

They are not “tech” in the VC sense, but they are **excellent at turning revenue into cash**.

---

## 4. A toy model of platform economics

The sheet `Platform_scenarios` builds a simple index-based model of a generic platform with four scenarios:

1. **Baseline_subsidised**  
   - High GMV and revenue, heavy spending on marketing and subsidies.  
   - EBITDA negative (e.g. –10 on a 0–100 index scale).

2. **Attempt_profitability**  
   - Moderate cuts to promotions and marketing.  
   - GMV and revenue shrink; EBITDA improves slightly but may remain negative.

3. **Aggressive_cut**  
   - Deep cuts to subsidies and marketing.  
   - GMV collapses, the platform becomes much smaller.  
   - EBITDA may be closer to zero but the absolute profit is tiny and fragile.

4. **Mature_consolidated**  
   - Competition has thinned out (duopoly/oligopoly).  
   - Higher take-rates, less need for subsidies.  
   - EBITDA finally reaches comfortably positive levels.

The model is deliberately simple, but it captures the intuition:

- In markets with:
  - low switching costs,
  - high price sensitivity,
  - and strong network effects,
- **scale is the precondition for profitability**.  
  Cutting your way to profitability can kill the scale you need.

---

## 5. The cost of AI: energy and infrastructure

The sheet `AI_cost_energy` adds a physical layer:

- Data-centre electricity demand is already a significant chunk of global power use.
- AI-related workloads are expected to greatly increase that demand in the next decade.
- Large AI labs are planning data-centre build-outs on the scale of **entire countries’ electricity consumption**.

This matters because:

- The **unit economics of AI** depend not just on software, but on:
  - hardware (GPUs, accelerators),
  - power prices,
  - cooling and water,
  - long-term infrastructure finance.

AI is not “just code in the cloud”. It is a heavy industrial activity with real-world costs.

---

## 6. Discussion: Tech is not automatically a good business

Putting everything together:

1. **Blockchain** shows that hype + capital do not guarantee revenue.
2. **AI** shows that revenue does not guarantee profits when the cost structure is extreme.
3. **Platforms** show that “just become profitable” can be a dangerous oversimplification.
4. **FMCG and beverages** show that non-tech sectors can have better, more stable economics than many beloved tech narratives.

This does **not** mean that:

- AI is “bad”,
- blockchain is “useless”,
- platforms are doomed.

It means that:

- good technology ≠ good business,
- and good business ≠ necessarily “high tech”.

For founders, operators and investors, the lesson is simple:

> Look at the **full stack of economics** – revenue, margins, capital intensity, energy use, competitive dynamics – not just the sticker label “AI” or “tech”.

---

## 7. Next steps

This working draft suggests a few natural extensions:

- Expand the dataset:
  - add more years and more companies per sector,
  - break out segment-level margins where possible.
- Build proper unit-economics models:
  - cohort-based CAC/LTV,
  - per-ride and per-order cost structures,
  - per-token and per-query AI cost curves.
- Explore scenarios:
  - what happens to AI unit economics if power prices double,
  - or if hardware costs fall faster than expected,
  - or if regulation imposes strict profit or price caps.

Contributions, critiques and alternative datasets are welcome.
