# [ex0525.csv Analysis Summary (click for full report)](ex0525_ANALYSIS.pdf)
- As a data scientist, Duy is requested to query a subset of the incomes of Americans.
- This subset consists of Americans and their distributions of annual incomes in five different education categories (less than 12 years, 12 years, 13-15 years, 16 years, and more than 16 years) with a certain classified condition in 2005.
- It contains 12,000+ rows, each depicting a person with two features, where one feature consists of the five education categories, and the other consists of their income.
- Appropriate assumptions are established in preparation for ANOVA testing by visualizing before and after logarithmic transformation.
- The addressed problem statements are as follows:
  - Test if at least one of the five distributions of educated people is different from the other distributions.
  - Test if people with a Bachelors (16 years of education) have different distributions of income than people with graduate-level education (more than 16 years of education).
  - Test if at least one of the five distributions of educated people is different from the other distributions, but assumes that there is no equal standard deviation for the logged data using Welch's ANOVA test.
  - Determine which pairs of education category distributions differ and by how much money or percentage using the Tukey-Kramer test.
  - 
