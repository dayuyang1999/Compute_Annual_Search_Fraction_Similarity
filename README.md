# Lee2015
Compute the Annual Search Fraction similarity as described by Lee et al. (2015)

    Lee, C.M.C., et al., Search-based peer firms: Aggregating investor perceptions through internet co-searches. Journal of Financial Economics (2015).
    
Because the calculation can be broken down to the daily level, for the purpose of memory efficiency, we will count unique combinations of `(ip, cik, next cik)` for each day, and then sum the daily counts to the annual level. 
