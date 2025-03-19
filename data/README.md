# data

Place data file(s) in this folder.

Drunk_high_at_school <- read_xlsx("../data/How many times in the past year (12 months) have you been drunk or high at school? (hn126) Percentage of students who answered at least 1 time.xlsx")

- `Drunk_high_at_school`: A file containing data of the percentage of students who said they were drunk or high at school at least one time. 

family_support_data <- read.csv ("/cloud/project/data/love_support_family.csv")

- `family_support_data`: A file containing data of the percentage of students who said that they generally have the support of their parents at home. 

Growth_vs_family <- full_join(Drunk_high_at_school, family_support_data, by = "Grade")

- `Growth_vs_family`: A variable that joins the family_support_data and Drunk_high_at_school data. This makes it easier to compare the percentage of students that say that they've been drunk or high at school by the percentage of students who say they have their parents' support.  





