# Methodology — Security Forecast 2026–2028

This document describes the methodology used in:

**Part 3. Security Forecast 2026–2028: Same Market, Two Different Maps**

Research cutoff: **28 July 2026**.

The purpose of the study is not to estimate market size or rank vendors. It is to identify where security companies are committing new resources, where the wider industry is directing attention, and where different market signals converge or diverge.

---

## 1. Evidence Model

The study uses four data layers across three types of market signal:

| Evidence type | Data layer | What it represents |
|---|---|---|
| Action | TOP-11 | Closed acquisitions and generally available product launches by 11 large public security vendors |
| Action | Broader Sample | The same events across 66 other security companies |
| Narrative | Forecasts and outlooks | Problems and directions repeatedly identified in descriptions of the market's future |
| Development & Positioning | Patents, conference talks and Expo presence | Technical work, professional attention and commercial positioning |

The layers are deliberately **not combined into a composite score**.

A company may acquire an asset, launch a related product, discuss the same subject in a forecast and promote the category at an industry event. These are different manifestations of one strategy, not four independent votes.

The analysis therefore looks for **convergence and divergence between signals**, rather than attempting to calculate an overall market ranking.

---

## 2. Action Analysis

### 2.1. Observation Window

The Action observation window is:

**28 July 2024 — 28 July 2026**

Action is intended to represent observable commitment of vendor resources.

Two event types qualify:

1. **completed acquisitions;**
2. **products confirmed as generally available (GA).**

An acquisition or GA launch is evidence that resources have been committed. It is not evidence of customer adoption, market maturity, successful integration or commercial success.

---

## 3. Action Samples

### 3.1. TOP-11

The first Action sample consists of:

- Palo Alto Networks
- Fortinet
- Cisco
- CrowdStrike
- Check Point
- Zscaler
- SentinelOne
- Cloudflare
- Tenable
- Rubrik
- Okta

**TOP-11 is a working name, not a ranking.**

Public companies were used partly for continuity with Parts 1 and 2 of the research and partly because acquisitions and product launches are generally easier to verify through public disclosures.

For companies whose businesses extend beyond cybersecurity, only security-related events are included.

Applying the Action filter produced:

- **34 completed acquisitions**
- **33 GA product launches**

during the observation window.

---

### 3.2. Broader Sample

The second Action dataset contains **66 security companies**:

- United States — 18
- Israel — 17
- European Union — 16
- Other regions — 15

The list was fixed before Action events were coded.

The Broader Sample is a **purposive comparison set**, not a statistically representative sample of the global cybersecurity vendor population.

Company selection involved analyst judgement. The purpose of the sample is to test whether patterns observed among large platforms also appear among other vendors, not to estimate the prevalence of those patterns across the entire security industry.

The TOP-11 and Broader Sample are therefore kept separate throughout the analysis.

The full list of companies is provided in the research appendix.

---

## 4. What Counts as Action

### 4.1. Acquisitions

An acquisition qualifies for Action only when the transaction was **completed during the observation window**.

An announced transaction that had not closed by the research cutoff is not counted as a completed Action event.

The acquisition must also be relevant to the cybersecurity business being studied.

Acquisition value is recorded where publicly disclosed, but deal value and company coverage are treated as separate metrics.

A large acquisition therefore does not count more heavily than a small acquisition when measuring the number of companies active in a domain.

---

### 4.2. Product Launches

A product qualifies when there is sufficient public evidence that it reached **general availability** during the observation window.

The following are excluded:

- preview releases;
- beta products;
- roadmap announcements;
- feature updates to an existing product;
- partnerships;
- integrations without a new standalone offering.

The purpose of this filter is to avoid treating announcements and incremental feature changes as equivalent to the launch of a new commercial capability.

---

## 5. Units of Count

The primary Action metric used in the article is:

**number of companies with at least one qualifying event in a domain.**

A company with several acquisitions or product launches in the same domain is therefore counted once when measuring domain breadth.

This prevents highly active vendors from dominating the comparison simply because they produced more announcements.

Additional units are used when examining the internal structure of a domain:

### Company × Direction

Counts whether a company has at least one qualifying event associated with a specific direction.

A company can therefore appear in several directions inside the same domain.

### Event × Direction

Counts mappings between individual qualifying events and directions.

One event may map to several directions where the underlying source explicitly supports several independent capabilities.

These secondary counts are used to understand the structure of activity. They are not treated as additional independent companies.

---

## 6. Action Taxonomy

Action events are classified using a fixed two-level model:

**Domain → Direction**

The taxonomy contains:

- **10 domains**
- **57 directions**

The complete taxonomy is available in the research appendix.

An event may receive more than one Direction mapping where public evidence supports several distinct capabilities.

Two classification boundaries are particularly important.

---

### 6.1. Data Security Analytics — DSA

**DSA is an analytical cluster, not a conventional purchasing category.**

It combines directions including:

- SIEM
- XDR/MDR
- SOAR
- Threat Intelligence
- Risk Engine
- Policy Engine
- Big Data Analytics
- Observability
- NDR
- adjacent security analytics capabilities

The cluster exists because the research is interested in convergence between security data, detection, context and decision-support capabilities.

Its breadth should therefore **not** be interpreted as a like-for-like estimate of market size against narrower product domains.

---

### 6.2. AI Security

**AI Security means securing AI, not using AI.**

A security product does not enter the AI Security domain merely because it uses:

- machine learning;
- generative AI;
- an LLM;
- AI-assisted investigation;
- AI-generated detections;
- AI-based automation.

The Action category covers capabilities intended to protect AI systems themselves, including areas such as:

- models;
- prompts;
- agents;
- inference;
- AI applications;
- AI supply chains;
- AI-related data flows.

This distinction prevents the rapid spread of AI functionality across conventional security products from being counted as equivalent to the emergence of AI Security products.

---

## 7. Narrative Analysis

Narrative examines how organizations describe the future of cybersecurity.

The dataset contains:

- **31 forecast and outlook documents**
- published by **19 organizations**

The organizations consist of:

- eight analyst or consulting organizations;
- the eleven vendors in TOP-11.

Narrative is measured in two ways.

### Document-level count

Each document is treated as an observation.

An organization publishing four relevant reports may therefore contribute four observations.

### Organization-level count

Each organization contributes at most one observation to a theme, regardless of how many documents it published.

The two counts are **not averaged**.

Their purpose is to determine whether a theme remains prominent after removing the effect of organizations that publish more material than others.

Narrative is not treated as evidence of future demand. It shows which problems have become important enough to recur in the industry's description of its own future.

---

## 8. Narrative Verification

Quantitative claims used from forecast and outlook material were checked against the original report, press release or publication of the source organization where available.

Claims were assessed in context rather than using numbers reproduced by secondary sources alone.

This is important because a number may be technically correct while being presented outside the conditions under which it was originally measured.

For example, a survey result may apply only to large enterprises, one geography or one observation period and should not automatically be interpreted as a global market value.

Another limitation is source bias.

Eleven of the nineteen organizations in the Narrative dataset are security vendors. Their forecasts may therefore reflect both genuine expectations and their own strategic or commercial positioning.

For that reason, Narrative is evaluated as a separate signal and is not combined numerically with Action.

---

## 9. Development & Positioning

This layer contains three different datasets:

- patents;
- conference talks;
- Expo / commercial positioning.

They are not treated as equivalent measurements.

---

### 9.1. Patents

Patent material is used **qualitatively**.

Its purpose is to identify technical problems and areas of development that sit behind broader market categories.

Patent counts are not used to rank companies because comparisons are affected by:

- different patent strategies;
- different jurisdictions;
- differences in corporate structure;
- publication delays;
- differences in filing practice.

The principal patent sources used in the research include:

- USPTO
- WIPO
- EPO Espacenet
- Google Patents

Patent activity therefore supports interpretation but is not used as a direct measure of market momentum.

---

### 9.2. Conference Talks

The conference dataset contains:

**3,075 presentations across 20 security conferences in 2024 and 2025.**

Conference talks are used as a proxy for **professional and research attention**.

They do not measure:

- product adoption;
- vendor revenue;
- commercial demand.

The analysis focuses primarily on changes in the relative attention given to selected themes between 2024 and 2025.

The full conference list is provided in the research appendix.

---

### 9.3. Expo / Positioning

Expo data is based on vendor presence in:

- exhibitor lists;
- solution-provider lists;
- sponsor lists

for major security industry events.

Expo presence is interpreted as evidence of **commercial positioning**.

It does not demonstrate:

- customer purchases;
- product deployment;
- revenue;
- market share.

A rise in Expo presence means that more vendors are positioning themselves around a category, not necessarily that customer demand has increased by the same amount.

Talk and Expo datasets are therefore compared mainly through changes over time rather than through their absolute numbers.

---

## 10. Different Datasets, Different Time Windows

The four analysis layers rest on five underlying datasets because Development & Positioning combines patents, conference talks and Expo data.

They do not operate on the same clock.

- **Action** uses a fixed two-year observation window from 28 July 2024 to 28 July 2026.
- **Narrative** includes forecasts and outlooks that may look several years into the future.
- **Patents** may become public significantly later than the R&D activity that produced them.
- **Conference talks** are compared primarily between 2024 and 2025.
- **Expo positioning** is also observed through changes in industry-event presence over time.

For this reason, the research does **not** assume a sequence such as:

**patent → conference talk → Expo → product → acquisition**

Real markets do not necessarily develop in that order.

A product can emerge before analysts establish a category name. Commercial positioning can expand before broad adoption. An acquisition can precede a new product by months or years. Research activity can remain invisible until a patent is published.

The analysis therefore compares the **direction and content of signals**, rather than assuming a fixed lead/lag relationship between them.

---

## 11. Scope of the Study

The study measures publicly observable evidence of what security vendors are:

- building;
- acquiring;
- discussing;
- researching;
- positioning.

It does **not** directly measure:

- customer adoption;
- product renewals;
- revenue attributable to individual capabilities;
- production deployment;
- operational effectiveness;
- market share;
- customer spending.

This distinction is important throughout the analysis.

A large number of qualifying Action events means that many vendors have committed resources to a direction. It does not mean that the direction has already achieved equivalent customer adoption.

---

## 12. Principal Limitations

### 12.1. Sample Selection

The Broader Sample was manually constructed and is not statistically representative of the worldwide security market.

Its results should therefore be interpreted as a comparison with TOP-11 rather than an estimate of global vendor prevalence.

---

### 12.2. Disclosure Bias

The analysis depends on publicly available disclosures.

Companies differ substantially in how consistently they announce:

- GA releases;
- acquisitions;
- product changes;
- technical developments.

This may create regional and company-level differences in observable activity that do not perfectly reflect differences in actual activity.

Within the Broader Sample, qualifying Action events were identified for:

- 83% of US companies;
- 71% of Israeli companies;
- 69% of EU companies;
- 60% of companies in other regions.

Part of this gradient may reflect differences in public disclosure and availability of English-language material rather than underlying security-market activity alone.

---

### 12.3. Narrative Bias

A substantial part of the Narrative dataset comes from vendors whose publications also form part of their strategic positioning.

Narrative should therefore be understood as evidence of what the industry repeatedly says will matter, not as an independent forecast of future demand.

---

### 12.4. Observation Period

The Action window covers two years.

This is sufficient to identify a period of concentrated activity but not to establish a long-term structural trend by itself.

The findings should therefore be interpreted as a snapshot of market movement during the observed period.

---

## 13. Interpretation Rule

The study deliberately gives Action more evidentiary weight than Narrative, conference attention or commercial positioning because an acquisition or GA launch demonstrates that resources have already been committed.

However, even Action remains a **supply-side signal**.

The strongest conclusions are therefore drawn where several structurally different datasets point in the same direction.

Equally, divergence between datasets is treated as a finding rather than as noise.

Examples include a direction where:

- specialist product development is broad but large-platform M&A remains limited;
- Expo positioning rises faster than observable Action;
- conference attention increases before a broad commercial product wave;
- large platforms and smaller vendors pursue the same domain through different mechanisms.

The central purpose of the methodology is to preserve these differences rather than collapse them into a single market score.

---

## 14. Reproducibility

The research appendix provides the supporting material required to understand and, where the underlying public sources permit, reproduce the analysis:

- composition of the TOP-11 and Broader Sample;
- Action taxonomy;
- Domain → Direction classification;
- Narrative source set;
- conference source set;
- Expo source description;
- patent source description.

The research cutoff for this version is **28 July 2026**.

Future market developments should be evaluated separately rather than retrospectively added to the dataset used for the published analysis.
