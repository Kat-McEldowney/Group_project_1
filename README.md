# **Mortgage Tax Study**
##Columbia Data Analytics BootCamp Group Poject 1
### By Andrea Ceriati, Sarah Demmon, Kat McEldowney, Chantal Thomas

New York imposes a mortgage tax on real estate transactions. This tax rate in NYC is 1.8% on mortgage amounts less than $500,000 and 1.95% on mortgages over $500,000. When buying a home, there is no sales tax, you are only taxed on the mortgage amount. Thre is a mansion Tax of 1% on homes over $1,000,000.

This means that a person buying a $500,000 home for cash pays no tax, a person buying the same home and putting 20% down, (or borrowing $400,000) pays $7,200 in mortgage tax, and a person who only has a 3% down payment on the same purchase must pay $8,730 in additional closing costs to cover this tax.

Upon examining the NY.gov page regarding sales tax collection (https://www.tax.ny.gov/data/stats/taxfacts/sales-miscellaneous-taxes.htm) it was discovered that "New York State offers tax exemptions on food, clothing, residential energy, Internet charges, and cable television, as well as a motor fuel tax cap.' It could be inferred that the reason for the lack of a sales tax on Real Estate puchases is becuase the government sees a home purchase as a necessary purchase that should be untaxed. If this is the case, why are mortgges taxed? Any why aren't purchases of investment properties taxed?
Real Estate is the only industry that we can think of where you can purchase corporate assets and not pay tax on that purchase. A real estate investor who purchases buildings for cash, does not pay any sales tax on this transaction. The US government is attempting to limit corporate control of single family homes with the pending legislation *End Hedge Fund Control of American Homes Act of 2023* that will require any entity with a net value including help assets of over $50 billion to sell off the single family homes they currently own over the next ten years, and prohibit them from aquiring new single family homes. This is an effort to increase the avaialbily of single family homes for individual buyers. There is anohter piece of legislation proposed that would charge a $10,000 per home annual fee for investors owning over 75 homes. (https://www.nytimes.com/2023/12/06/realestate/wall-street-housing-market.html) (https://www.businessinsider.com/housing-market-affordability-investors-hedge-funds-wall-street-democrats-bill-2023-12). In light of this, the ability to purchase a single family home as an invetment without paying sales tax seems like a big oversight. We propose, to assist in this goal of promoting individual ownership of single family homes and apartments, a sales tax of 50% of the current sales tax in NYC, be levied on purchases of single family homes by investors.

We have two hypotheses that we will explore in this project: 
•	We believe that the mMrtgage Tax is a policy that has a disparate impact on people who are already economically disadvantaged. 
•	We also believe that if this tax was lowered and applied across the board to all home purchases, with a higher tax rate applied to investment propery purchases, based on sales price not mortgage amount, the policy would not only be more equitable, but also raise more revenue for the government.

We analyzed the sales data of 15,550 homes sold in Brooklyn, NY in 2022, as well as 2,164 homes sold in 2022 of four of the highest income zip codes and the four lowest income zipcodes in the other boroughs. We used this data to calculate how much mortgage tax was raised and how much would be raised if it were instead a sales tax that was only 1/2 of the current mortgage tax rate and 1/2 the current mansion tax rate on purchases of a proimary residence, and 1/2 the current sales tax rate on investment property purchases. 
We also used census data to examine the differences in demographics of the different zip codes to see if people with lower incomes are paying a larger portion of this tax than people living in zip codes with higher average incomes.

The property sales data came from Property Radar (https://app.propertyradar.com/). We filtered the search to only included sales of condos and single family homes that closed in the 2022 calendar year and market sales that were listed on the open market. This means that the sample does not include short sales, forclosures, or arms length transactions (such as a preson selling to a family member or friend without first listing the home on the open market).




