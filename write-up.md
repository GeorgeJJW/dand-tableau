# Create a Tableau Story: Survival on the Titanic

Student: George J. J. Wu

Date: April 20, 2018

[Dataset](https://www.kaggle.com/c/titanic/data) (Udacity [subset](https://d17h27t6h515a5.cloudfront.net/topher/2017/October/59d54e6d_titanic-data/titanic-data.csv))

[Initial Draft](https://public.tableau.com/profile/george.wu5551#!/vizhome/dand_titanic/Titanic?publish=yes)

[Final Draft](https://public.tableau.com/profile/george.wu5551#!/vizhome/dand_titanic_final/Titanic?publish=yes)

## Summary

The sinking of the RMS Titanic in 1912 was one of the deadliest shipwrecks in history, killing many of the passengers onboard. Passengers who did survive the ordeal were predominantly women and children from the upper and middle social classes.

## Design

### Initial Decisions

- Used length and position exclusively for visual encodings, as the use of color and shape was not deemed to be necessary for the current visualizations.

- Used a dashboard of bar charts to visualize various bivariate comparisons.

- Used interactive bar charts with filters to visualize various multivariate comparisons, enabling readers to focus on a particular comparison as they saw fit.

- Oriented bar charts to horizontal for better viewing on a web page.

- Excluded 177 entries for missing age values using data source filter.

- Categorized age values into 3 groups: minor(under 18), adult(18-59), and senior(60 and above).

- Conceptualized passenger survival of each demographic group as a survival rate, which was obtained by dividing the number of survivors in each demographic group by the total number of passengers in each demographic group (number of survivors in each group / number of people in each group).

### Changes Made

- Added annotations of how age groups were categorized.

- Added group size for each demographic group in tooltip.

## Feedback

* "What do you think is the main takeaway from this visualization?"

> Joshua: First thing obviously visible is that women and children were dramatically more likely to survive the disaster.

> Matias: Men are considered much more expendable, unless they are under age. The difference between the rich and the poor can be seen, even in emergency situations where no money is involved. This is particularly noticeable in the adult population. Children of both sexes were protected, but children of the poor were more likely to die. This increases my suspicion that the poor were located lower in deck, and so had less time to get out.

* "What relationships do you notice?"

> Joshua: There seemed to be a direct correlation between social standing and probability of surviving the disaster.

> Matias: Among the adult population, gender privilege (as far as being considered valuable) overtakes economic privilege by such a strong margin that we only see a difference between priority given to higher income individuals among males. Females in these two groups were likely all pushed first. Among the children, the poor were clearly at a disadvantage, but the middle class children did not seem to be advantaged as compared to the rich. The highest survival male adult group was equal to the lowest female adult group.

* "Is there something you don’t understand in the graphics?"

> Joshua: Only thing that's not entirely clear is what the ages are for each group, i.e. minor being ages 1-18, seniors being 55+, etc.

> Matias: No.

* "Any additional feedback?"

> Joshua: I mean it probably doesn't matter but I like to see numbers on each one to see exactly how many of each group there are. Like if for whatever reason there's like 10 middle class female kids, so having 100% survival rate kinda means less, versus like 80% of 400 adult women.

> Matias: This was very interesting to look at, especially because I once spoke to someone about the issue of men being considered expendable, and how this is a problem in our society, and they argued strongly that this was just in the media, but in real emergency situations men don't let women and children out of the ship first. That it's not a problem at all, and it's a misconception.

## Resources

- [Difference between extract filters and data source filters](https://community.tableau.com/docs/DOC-8721)

- [Arrange filter values in tableau](https://stackoverflow.com/questions/32042025/arrange-filter-values-in-tableau)

- [Customizing tooltips for each measure value in multiple measures](https://community.tableau.com/thread/145845)