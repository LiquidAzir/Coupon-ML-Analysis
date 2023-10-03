# **Coupon-ML-Analysis**

The "Coupon ML Analysis" was performed to look at how various factors influence the usage of different types of coupons. This was done on the CSV dataset titled "Coupons". 

I started by loading and examining the dataset to understand its structure, columns, and the types of data available.

Basic statistical summaries were generated to provide an overview of the dataset's characteristics and distributions.

I then took a look at two types of coupons ("Bar" and "Restaurant(<$20)") to generate conclusions around what factors have the greatest influence on their usage.

The overall acceptance rate for "Restaurant(<20)" coupons was approximately 70.71%, while the "Bar" coupon acceptance rate was around 68.57%. Both rates indicate a high preference for these coupons.

**Bar Coupon Analysis:**

**Subset Creation:** A subset of the data specific to "Bar" coupons was created to focus on this coupon group.

**Descriptive Analysis:** The acceptance rate for "Bar" coupons was calculated as 68.57%, providing a foundational understanding of the dataset.

**Factor Analysis:**
I analyzed the influence of the frequency of bar visits on acceptance rate.
I explored age factor, comparing drivers under 30 with the rest.
I explored the impact of having children, marital status, occupation, and restaurant visit frequency on coupon acceptance.
Visual aids, like bar plots, were used to represent these distributions and look for patterns.

**Bar Coupon Conculsions**

**Frequency of Bar Visits:** Drivers who visited bars more than once a month had a higher acceptance rate.
**Age Factor:** Drivers under 30 who frequently visited bars were more inclined to accept bar coupons.
**Companion and Marital Status:** Those not accompanied by kids and those who weren't widowed were more receptive to bar coupons.
**Income and Restaurant Visits:** Drivers with lower incomes who frequented cheaper restaurants were more likely to accept bar coupons.
**Occupation:** Excluding certain groups, like those in farming, fishing, or forestry, showed a higher acceptance rate.

**Restaurant (<$20) Coupon Analysis**

**Subset Creation:** Similar to the Bar coupons, a focused dataset for "Restaurant(<20)" coupons was established.

**Descriptive Analysis:** The acceptance rate for "Restaurant(<20)" coupons was computed as 70.71% to set the baseline.

**Factor Analysis:** 
I visualized the acceptance rate based on age, revealing patterns about younger age groups being more receptive.
Further visualizations were conducted on occupation, presence of children, and marital status, using bar plots to help understand patterns and trends.

**Restaurant (<$20) Coupon Conclusions:**

**Age:** Younger age groups, particularly those under the age of 30, tend to accept "Restaurant(<20)" coupons at a higher rate. The acceptance rate gradually decreases with age up to 36, starts to increase up to 46 and finally drops with the group "50plus" having the lowest rate.
**Occupation:** Occupations such as "Architecture & Engineering", "Life Physical Social Science", "COnstruction & Extraction", and "Protective Services" exhibit higher acceptance rates. Certain professions may be more likely to accept restaurant coupons due to their lifestyle or financial considerations.
**Having Children:** Those without children had a slightly higher acceptance rate.
**Marital Status:** "Unmarried partner" individuals were the most receptive, with "Widowed" being the least.

**Overall Conclusion**

Both demographic and socio-economic factors significantly influence the likelihood of coupon acceptance across different types. Younger individuals, specific occupations, marital statuses, and income levels displayed distinct preferences towards certain promotions. Tailoring marketing strategies to these insights can optimize outreach and improve coupon acceptance rates.

