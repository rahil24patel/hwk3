Hello

This is my Homework #3 submission, by Rahil Patel. I have built all necessary datasets in hwk3_dataset, and answered all questions in hwk3_analysis. Here is a brief summary of the hwk3_dataset:

- Pulled and cleaned MA plan data from 2010–2015 across four raw sources: enrollment, service area, penetration, and star ratings
  
- Filtered out SNPs, 800-series plans, PDPs, and US territories to match CMS standards

  
- Built a plan-county-year panel by merging monthly enrollment files with service area and penetration data


- Extracted star ratings by parsing CMS domain and summary files year by year, using a continuous raw score as a fallback where the official rating was missing

- Constructed market share, HMO/Part D indicators, and the Star_Rating variable

- I have four output files for use in the analysis notebook: a full 2010–2015 panel, a 2010-only subset for the RD, contract-level ratings, and plan-year enrollment totals
