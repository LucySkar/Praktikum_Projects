# Creditworthiness Analysis

**Goal**: preprocess data and analyze if different factors (family_status, children and purpose) can influence bank credit users' depts.

### Results and Findings
1. Not all data were suitable for analysis, and some rows and columns had to be excluded. It is necessary to clarify where the errors come from in order to correct them and expand the subsets.
2. The influence of various factors on credit debts was analysed:
- Credit debt is affected not only by the presence of children, but also by their number, and families with many children turned out to be somewhat more disciplined than people with 1-2 children. Least of all debts on loans from childless borrowers.
- Marital status affects male borrowers more than women. Among women, the most diligent category of payers are widows, and the largest percentage of debtors is among those who live in a civil partnership. For single, married and divorced women, the percentage of debtors is almost the same. Among men, unmarried and, possibly, widowers are the least responsible for paying off loans, and married people are the most disciplined category of male borrowers. 
- The categories of borrowers with the highest and lowest incomes are the least likely to have loan debts, and most often the debtors are representatives of the category of low ("above poverty") and middle income.
- According to the purpose of the loan, the smallest percentage of debtors is among those who took a loan for real estate transactions, and the largest - for a car and education.
3. The conclusions made in this analysis can be used further for credit scoring calculation. Also, a possible way forward for the work may be to consider the influence of other combinations of factors, especially after the revision of the dataset.
