# OSU-MCM
A data science project made for the OSU MCM Competition. Analyzes regular season records of NCAA Men's basketball teams to quantify the amount of luck inherently present in collegiate basketball. Uses an elo system, bootstrapping, MSE and gradient descent.

## File guide (Unimportant files omitted)
- AI Use Report.tex - describes how AI was used in this project
- Basketball_dataset.xlsx - original data set
- Basketball_dataset_clean_seth.xlsx - the cleaned data set
- Bootstrapped dist.png - graph of the upset proportions in the bootstrapped samples
- ELO vs MLE.png - graph comparing two methods of upset probability estimations
- Elos.txt - text file containing the final calculated elos
- K histogram - graph showing the elo differences in each game played with at least one top team
- MSE vs K - graph showing mean squared error between predicted and actual upset proportions
- Sources.txt - DEPRECATED, see bibliography for all sources.
- bibliography.bib - bibliography containing sources for the project
- data_analysis.ipynb - Jupyter Notebook file containing the python code for the elo calculation and related analysis
- seth_data_procesing.ipynb - Code used to clean the data set (not all of the changes were generated via code)
- writeup.pdf - the final writeup of the project
- writeup.tex - source LaTeX for the writeup
- writeup.* - other files used to generate the writeup
