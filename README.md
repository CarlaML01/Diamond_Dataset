# Diamond Dataset
![diamond dataset](https://media.giphy.com/media/Z06UFnGuY0H9C/giphy.gif)

## Visualization Case Study. 

I will go through the steps of an explanatory data visualization, systematically starting from univariate visualizations, moving through bivariate visualizations, and finally multivariate visualizations.

### Information on the Diamond Dataset
In this notebook, I'll be working with a dataset regarding the prices and attributes of approximately 54,000 round-cut **diamonds**. I'll go through the steps of an explanatory data visualization, systematically starting from ***univariate visualizations***, moving through ***bivariate visualizations***, and finally ***multivariate visualizations***. Finally, I'll work on polishing up selected plots from the analysis so that their main points can be clearly conveyed to others.

The dataset consists of almost 54,000 rows and 10 columns:

- price: Price in dollars. Data were collected in 2008.
- carat: Diamond weight. 1 carat is equal to 0.2 grams.
- cut: Quality of diamond cut, affects its shine. Grades go from (low) Fair, Good, Very Good, Premium, Ideal (best).
- color: Measure of diamond coloration. Increasing grades go from (some color) J, I, H, G, F, E, D (colorless).
- clarity: Measure of diamond inclusions. Increasing grades go from (inclusions) I1, SI2, SI1, VS2, VS1, VVS2, VVS1, IF (internally flawless).
- x, y, z: Diamond length, width, and depth, respectively, in mm.
- table: Ratio of the width of the top face of diamond to its overall width, as a percentage.
- depth: Proportional depth of the diamond, as a percentage. This is computed as 2 * z / (x + y), or the ratio of the depth to the average of length and width.

> For the case study, I will concentrate only on the variables in the top five bullet points: price and the four 'C's of diamond grade. My focus will be on answering the question about the degree of importance that each of these quality measures has on the pricing of a diamond. 
### Follow up steps:
**1) [Univariate Exploration](Univariate_Exploration_Diamonds.ipynb)**

**2) [Bivariate Exploration](Bivariate_Exploration_Diamonds.ipynb)**

**3) [Multivariate Exploration](Multivariate_Exploration_Diamonds.ipynb)**

**4) [Explanatory Polishing](Explanatory_Polishing.ipynb)**

*The End*
