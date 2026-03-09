# cash-home-buying-analysis
Senior Data Analyst Trial — Scoring methodology for ranking cash home buyer companies by market
This project builds a scoring model that ranks cash home buyer companies within a given market, designed to power "Top 10 Cash Home Buyers articles for homeowners

1. Scoring Methodology & Code: https://colab.research.google.com/drive/15iOSGGZdD2IGGQ-R4JnH__QFNto_hk9u?usp=sharing
2. Ranked Output: https://docs.google.com/spreadsheets/d/13X7P_fQi2P2ye9zKAORUKFRGRBDKoz8_VRkb-bT2aSY/edit?usp=sharing
3. Documentation: https://docs.google.com/document/d/1hD02wQNBGyWwdkJQsUsjTsi1_r7NgefLlPl0jXAuOwU/edit?usp=sharing
4. Write up: https://docs.google.com/document/d/1GnUmMVd6ZlO3RtHqxNVvidgcjExlQ-thFqUfG_2VnSE/edit?usp=sharing

### Approach

- 3-pillar scoring model: Credibility (40%), Customer Experience (35%), Local Activity (25%)
- Sample market: Dallas/Fort Worth, TX 
- Tools: Python, Google Colab, Google Sheets

### Quick Summary

The model scores each company 0-100 on three dimensions mapped to 
homeowner decision-making: trust, satisfaction, and local presence. 
Key design choices include log-scale review counts (to avoid big brand 
dominance), neutral defaults for missing data (to be fair to small 
local operators), and a 1-star review penalty (to catch bad experiences 
hidden behind good averages)
