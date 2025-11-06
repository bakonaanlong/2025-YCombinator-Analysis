# Y Combinator 2025 Analysis Dashboard  
 

---

## 1. Background and Overview  

This dashboard presents a comprehensive analysis of companies accepted into the Y Combinator (YC) accelerator program in 2025. Drawing from publicly available data on YC’s official announcements, company profiles, and batch disclosures up to the Summer 2025 cohort, the study examines **474 companies** across three batches: **Spring 2025**, **Winter 2025**, and **Summer 2025**.  

The primary objective is to identify **emerging trends, geographic concentration, industry composition, and the prevalence of AI-driven innovation** within the YC ecosystem. By visualizing key metrics—location, industry, AI involvement, and batch distribution—this dashboard enables investors, founders, policymakers, and researchers to understand the evolving priorities of one of the world’s leading startup accelerators.  

**Key Scope**:  
- Covers **all 474 companies** in the 2025 YC cohorts (S25, W25, S25).  
- Excludes B2B-focused companies from certain industry breakdowns where specified.  
- Defines **AI-related** companies based on explicit use of AI/ML in core product, infrastructure, or business model.  

---

## 2. Data Structure Overview  

| **Field**                  | **Description**                                                                 | **Data Type** | **Source**                     |
|----------------------------|---------------------------------------------------------------------------------|---------------|--------------------------------|
| `company_name`             | Official registered name of the startup                                          | String        | YC Bookface / Website          |
| `batch`                    | YC batch identifier (e.g., S25, W25, SS25)                                       | Categorical   | YC Official Announcements      |
| `location_hq`              | Headquarters city (primary operating base)                                       | String        | Company website / Crunchbase   |
| `industry_primary`         | Main industry vertical (Healthcare, Fintech, Education, etc.)                    | Categorical   | YC directory + manual tagging  |
| `is_b2b`                   | Boolean flag indicating B2B business model                                       | Boolean       | Product analysis               |
| `is_ai_related`            | Boolean flag if AI/ML is core to product or operations                           | Boolean       | Technical description review   |
| `founding_year`            | Year company was founded                                                         | Integer       | Company records                |
| `team_size_at_yc`          | Number of founders/team members at time of YC application                        | Integer       | YC application data            |

**Total Records**: **474**  
**Batches Analyzed**:  
- Spring 2025 (S25)  
- Winter 2025 (W25)  
- Summer 2025 (SS25)  

*Note: Data is aggregated and anonymized where required. Industry classifications follow YC’s internal taxonomy with minor harmonization for consistency.*

---

## 3. Executive Summary  

- **Geographic Dominance**: **San Francisco** remains the epicenter, hosting **40% (190/474)** of 2025 YC companies.  
- **AI Supremacy**: **62% (294/474)** of all companies are **AI-related**—the highest proportion in YC history.  
- **B2B Leadership**: **310 companies (65%)** operate in B2B, with **202 (65% of B2B)** leveraging AI.  
- **Industry Concentration**: **Healthcare, Consumer, and Fintech** dominate non-B2B segments; **Industrials** lead when B2B is excluded from industry charts.  
- **Batch Growth**: **Summer 2025** was the largest batch with **~180+ companies**, followed by Winter and Spring.  

> **Key Takeaway**: YC 2025 marks the **"AI Batch Era"**—with AI not just prevalent but structurally embedded across industries and business models.

---

## 4. Insights Deep Dive  

### 4.1 Location Concentration  
- **San Francisco** hosts **40%** of all companies, reinforcing its role as the default global startup hub.  
- **New York, London, Boston, and Toronto** follow, but combined represent less than **15%**.  
- **Remote-first** companies account for **~8%**, indicating a partial post-pandemic normalization toward physical HQs.  

### 4.2 AI Penetration  
- **294 companies (62%)** are AI-related—the highest ever recorded in a single YC year.  
- Among **B2B companies**, **65% integrate AI**, suggesting enterprise adoption is driving AI startup formation.  
- **Non-AI companies (38%)** are increasingly niche or infrastructure-adjacent (e.g., climate, defense, education hardware).  

### 4.3 Industry Dynamics  
- When **excluding B2B**, **Healthcare** leads, followed by **Consumer** and **Fintech**.  
- **Industrials** dominate when B2B is isolated—likely due to supply chain, robotics, and manufacturing AI tools.  
- **Government and Real Estate** remain marginal (<5% combined).  

### 4.4 Batch Trends  
- **Summer 2025** cohort is the largest and most AI-heavy (~68% AI-related).  
- **Winter 2025** shows higher remote and international founder representation.  
- Batch size correlates positively with AI focus—suggesting YC prioritizes scalable AI models in larger cohorts.  

---

## 5. Recommendations  

### For Founders  
1. **Relocate strategically**: San Francisco offers network density; consider **NY or Boston** for sector-specific ecosystems (fintech, biotech).  
2. **Integrate AI early**: Even non-tech products benefit from AI in operations, marketing, or personalization.  
3. **Target B2B + AI intersection**: Highest YC acceptance and funding correlation in 2025.  

### For Investors  
1. **Overweight SF-based AI/B2B plays**: Highest density of high-signal opportunities.  
2. **Monitor non-obvious AI**: Consumer and healthcare AI startups may be undervalued relative to infrastructure.  
3. **Track batch momentum**: Summer cohorts increasingly set the annual tone—prioritize demo day attendance.  

### For Policymakers & Ecosystem Builders  
1. **Bridge the location gap**: Incentives in emerging hubs (Africa, Southeast Asia) could diversify YC’s global footprint.  
2. **Support AI ethics & governance training**: With 62% AI penetration, responsible innovation must scale with volume.  

### For YC & Accelerator Programs  
1. **Expand industry-specific tracks**: Healthcare and Consumer AI need dedicated mentorship pipelines.  
2. **Publish AI transparency metrics**: Help founders signal responsible AI practices to LPs and regulators.  

---

**Dashboard Navigation**:  
- **Overview Tab**: High-level KPIs and filters  
- **Dashboard Tab**: Interactive charts and batch comparisons  
- **Dataset Tab**: Raw data export (CSV) and schema  



---  
*© 2025 Bako Naanlong. All rights reserved. Data sourced ethically from public YC records.*
