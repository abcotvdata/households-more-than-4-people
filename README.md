# Households with more than 4 people documentation

### Background 

This month, the federal government launched a program offering free at-home COVID-19 tests. Every household is eligible for four tests. But, data from the U.S. Census estimates that nearly 12 million households have more than 4 people – and, poorer neighborhoods or neighborhoods of color tend to have more households with more than 4 people. 

### Sourcing & Language 

This data comes from the U.S. Census Bureau’s 2019 5-year American Community Survey. Included are datasets by county and census tract. It’s important to note that **the data we compiled has two distinct categories.** The race/ethnicity data is on an ***individual*** level, meaning it’s counting the number of people of a certain race/ethnicity. The income and number-of-people-in-a-home data are on a ***household*** level, meaning that data is counting the number of ***households*** in a certain category or reporting the median income of a whole household. 

With that in mind, it’s important to be specific when talking about the intersection of race and households. You wouldn’t want to say: “households of color tend to have a more than four people,” because the race/ethnicity data is on an individual level. Instead, it would be correct to say: “Neighborhoods of color tend to have a higher percentage of households with more than four people.”  

However, it WOULD be correct to say: “Poorer households tend to have higher rates of homes with more than four people,” because the income data is at the household level. 

### Fields 

Below are fields and descriptions for the datasets: 

- **GEOID:** Census ID for the geography 
- **NAME:** Spelled out name of the geography (for census tracts, includes the name of the county) 
- **Total_pop:** total estimated population 
- **Median_household_income:** the median (or “typical” income of a household in the geography – Note: this is NOT the average) 
- **White, black, ai_an, asian, hi_pi, hisp_lat:** the number of people estimated to be non-Hispanic white, non-Hispanic Black, non-Hispanic American Indian/Alaska Native, non-Hispanic asian, non-Hispanic Native Hawaiian/Pacific Islander, or Hispanic/Latino, respectively, in a particular geography. 
- **Pct_white, pct_black, pct_ai_an, pct_asian, pct_hi_pi, pct_hisp_lat, pct_poc:** the percentage of people estimated to be non-Hispanic white, non-Hispanic Black, non-Hispanic American Indian/Alaska Native, non-Hispanic asian, non-Hispanic Native Hawaiian/Pacific Islander, or Hispanic/Latino, or people of color (AKA: non-white), respectively, in a particular geography. 
- **Total_hh:** the total number of households in a particular geography 
- **Total_hh_owner:** the total number of owned households in a particular geography 
- **Total_hh_renter:** the total number of rented households in a particular geography 
- **Pct_owners:** the percentage households that are owned in a particular geography (out of all households) 
- **Pct_renters:** the percentage households that are rented in a particular geography (out of all households) 
- **Total_owner_more_than_4:** the number of owned households that have more than 4 people 
- **Total_owner_less_than_4:** the number of owned households that have less than 4 people 
- **Total_renter_more_than_4:** the number of rented households that have more than 4 people 
- **Total_renter_less_than_4:** the number of rented households that have less than 4 people 
- **Total_hh_more_than_4:** the number of total households that have more than 4 people 
- **Total_hh_less_than_4:** the number of total households that have less than 4 people 
- **Pct_owner_more_than_4:** the percentage of owned households that have more than 4 people 
- **Pct_renter_more_than_4:** the percentage of rented households that have more than 4 people 
- **Pct_total_hh_more_than_4:** the percentage of total households that have more than 4 people 
- **Poc_bin:** whether the geography has less than 25%, 25-50%, 50-75% or more than 75% people of color 
- **Income_bin:** whether the geography’s median household income is less than the 25th percentile, between the 25th and 50th percentile, between the 50th and 75th percentile, or more than the 75th percentile. (***NOTE:** The percentiles rounded to the nearest thousand and are based on all the geographies in the particular data sheet. Therefore, they will vary depending on the data sheet you’re looking at.*) 
