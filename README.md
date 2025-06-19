# Reading Between the Lines: Economic Signals and Sentiment from Bank of England (BoE) Speeches
A sentiment analysis of BoE speeches

---

## Table of Contents

- About the Project
- Objective
- Project Highlights
- Methodology
- Key Findings
- Recommendations
- Repository Structure
- Team
- References

---

## About the Project

In this project, as part of LSE's career accelerator course, I worked in a team to produce a sentiment analysis on Bank of England (BoE) speeches and explore how the speech sentiments change over time and their relationship with external and internal events as well as economic indicators within 6 weeks.

---

## Objective 

To assess whether BoE communications reflect, predict, or respond to shifts in macroeconomic conditions — and how these insights can enhance transparency, policy effectiveness, and market guidance.

---

## Project Highlights

### Tools Used
- Jupyter Notebook

---

## Methodology

### Problem Deconstruction with 5 Whys

- Why do Central Banks make public speeches? 
  Speeches discuss the overall state of the economy and add depth and clarity to their monetary policy 
  decisions. Central Banks effectively use speeches as an instrument of monetary policy. 

- Why do they discuss this? 
  They  do  so  to  provide  transparent  information  to  financial  markets  and  the  public  on  economic 
  outlook and monetary policy decisions. 

- Why is this important? 
This  helps  promote  stability  in  markets  (prevent  market  turmoil)  and  reassures  the  public  by 
explaining their activities and economic views.  

- Why is this important? 
  Their insights can influence market expectations of future asset prices and provide further depth into 
  their  reasoning  for  their  economic  views  to  strengthen  public  confidence  and  reduce  economic 
  uncertainty.
  
- Why is this the case? 
  Speeches are closely followed by market participants and policymakers and every word is scrutinised. 
  Speeches  are  analysed  by  not  only  what  has  been  said  but  also  has not been said. They provide 
  forward guidance and given policy-makers and market participants act in a forward looking manner, 
  speeches can influence future expectations of interest rates/inflation can impact the economy.

### Data Sources

- 1,200 BoE speech transcripts (1997–2022)
- Economic indicators (ONS, BoE)
- Market data (Investing.com, UK DMO)

### Models Compared

| Model              | Strengths                          | Suitability |
|-------------------|------------------------------------|-------------|
| TextBlob          | Simple, fast                       | ❌ Generic |
| VADER             | Good for social tone               | ❌ Informal |
| Loughran-McDonald | Tailored for finance               | ⚠️ Limited |
| **FinBERT**       | Deep contextual financial analysis | ✅ Best Fit |

---

## Key Findings

-  **BoE speech sentiment is generally neutral**, even during major events
-  Governor speeches are more volatile and correlated with Gilt movements
-  Staff sentiment showed predictive power for GBP/EUR exchange rate
-  **Sentiment does not predict inflation**, but reflects it reactively
-  No consistent relationship between sentiment and GDP or SONIA

---

## Recommendations

| Action                                       | Priority |
|---------------------------------------------|----------|
| Track speech tone in internal dashboards     | High     |
| Contextualise tone by role and topic         | Medium   |
| Integrate sentiment into scenario planning   | Low      |

---

## Repository Structure

/data/ # Cleaned datasets and source data (e.g., speeches, indicators)
/scripts/ # Python scripts for scraping, cleaning, and sentiment analysis
/visualisations/ # Exported charts and visual summaries (PNG, PDF, etc.)
/images/ # Additional screenshots or README images
README.md # Project overview and documentation
requirements.txt # (Optional) Python dependencies if applicable

---
## Team

- Suleiman Chun Lum Andy Ho  
- Jurgita Cepure  
- Michael Sunner  
- Nanik Nanwani  
- Ng Wen Wen Annora

---

## References

- [FinBERT by yiyanghkust](https://huggingface.co/yiyanghkust/finbert-tone)
- [Bank of England Speeches](https://www.bankofengland.co.uk)
- [Office for National Statistics](https://www.ons.gov.uk)
- [Investing.com](https://www.investing.com)
- [UK Debt Management Office](https://www.dmo.gov.uk)
