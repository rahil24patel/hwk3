Hello

This is my Homework #3: Attempt #2 submission, by Rahil Patel. I have built all necessary datasets in hwk3_dataset, and answered all questions in hwk3_analysis. Here is a brief summary of the hwk3_dataset:

- Pulled and cleaned MA plan data from 2010–2015 across these four sources: enrollment, service area, penetration, and star ratings
  
- Filtered out SNPs, 800-series plans, PDPs, and US territories

- Built a plan-county-year panel by merging monthly enrollment files with service area and penetration data

- Extracted star ratings by analyzing CMS domain and summary files year by year

- Constructed market share, HMO/Part D indicators, and the Star_Rating variable

- I have four output files for use in the analysis notebook: a full 2010–2015 panel, a 2010-only subset for the RD, contract-level ratings, and plan-year enrollment totals

- Pulled and cleaned MA plan data from 2010–2015 across these four sources: enrollment, service area, penetration, and star ratings

- 
- Filtered out SNPs, 800-series plans, PDPs, and US territories

- 
- Built a plan-county-year panel by merging monthly enrollment files 
  with service area and penetration data

  
- Extracted star ratings from CMS domain and summary files year by year;
  for 2014 and 2015 where the summary file had too few valid scores, 
  star ratings were derived from raw domain scores using CMS rounding rules
- Market share is calculated as avg_enrollment / avg_enrolled at the 
  plan-county level
- Constructed HMO/Part D indicators and the Star_Rating variable
- Four output files are used in the analysis notebook: a full 2010–2015 
  panel, a 2010-only subset for the RD analysis, contract-level ratings, 
  and plan-year enrollment totals
