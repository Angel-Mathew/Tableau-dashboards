# Tableau-dashboards
Dashboards built with Tableau: UAE GDP vs oil price and bank loan approval.
# Tableau Dashboards

Dashboards I built using Tableau.

## 1. UAE GDP vs Oil Price



A Tableau dashboard that compares the UAE's nominal GDP with the Brent crude oil price from 1987 to 2024.

### The problem
The UAE is an oil-producing country, so the question is how closely its economy follows the oil price. I wanted to test that with data instead of assuming it.

### What you can explore
- A line chart of GDP against Brent price over time
- Bars of yearly GDP growth with the oil price change laid over them
- A scatter plot of GDP growth against oil price change, with trend lines for before and after 2005
- A year slider

### What I found
- GDP and oil price move together over the long run. Both rise strongly from the early 2000s, and Brent peaks around 2011 to 2012.
- Falls in the oil price line up with weak growth. In 2009 and 2015, oil dropped sharply and GDP growth turned negative.
- Rises line up with strong growth. In 2000 and 2021, oil jumped by roughly 60 to 70 percent and GDP growth was around 18 to 24 percent.
- The trend lines slope upward in both periods, which shows a positive link between oil price change and GDP growth.

## 2. Bank Loan Approval



A Tableau dashboard about 614 loan applicants, built from a loan dataset (loan_train.csv).

### The problem
Banks need to understand what separates approved from rejected applications. I wanted to check which applicant details matter most.

### What you can explore
- Approval rate (68.73 percent) and total applicants (614)
- Approved (Y) versus rejected (N) by education level
- Approved versus rejected by credit history

### What I found
- Credit history is the strongest factor. Applicants with a good credit history (1) are mostly approved, roughly 380 approved against 95 rejected. Applicants without it (0) are mostly rejected, with only a handful approved.
- Education has a smaller effect. Graduates are approved more often (roughly 71 percent) than non-graduates (roughly 61 percent).
