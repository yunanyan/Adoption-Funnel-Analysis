# Adoption-Funnel-Analysis

This the collection of SQL codes used in SPOS Adoption Funnel Analysis.
  1. Main Funnel Table is the major table in the analysis. It has 692k rows which represent all the sellers who BoFed in 2022.
     The table has Hit_Time column for every sub-milestone including adoption (2nd transaction, 3rd transaction, 4th transaction,adoption).
     Hit Time is the time between two sub-milestones. It can also be used to compute drop out rate.
     
  2. Segmentation Analysis left joins the main funnel table with different seller segment tables. 

  3. Campaign Investigate left joins the main funnel table with campaign details to determine which campaigns have reached more sellers during their BoF and adoption

  4. Revenue Estimate computes the average revenue per seller for each GPV segment.
