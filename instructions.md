Create a new Jupyter notebook in the current folder to do exploratory data analysis of the data in "heart.csv" using the data dictionary file "HeartCSVDataDictionary.md". Ask me to choose a Python kernel for the notebook. Take a step-wise approach, for example, create the notebook and open it in the editor, then let me select the Python kernel. Then execute the notebook cell-by-cell as it is created and write findings in markdown cells below code cells with output, where needed.

General notebook instructions:
1. Use markdown cells with `#`, `##`, and `###` hashtags for the title, sections, and subsections.
2. Import the required packages in the first section named 'Import Python Packages'.
3. Add the code `%config InlineBackend.figure_format = 'retina'` in the import section to create high resolution plots.
4. The next section should be 'Data Import'. Import the spreadsheet and assign it to the variable `df`
5. The final section should be 'Exploratory Data Analysis'.
6. Add appropriate title and axes labels for plots. Use LaTeX in title and axes labels where appropriate. Always add a grid to plots. Do not use the column headers (variable names) in the "heart.csv" file in reports or plots. The column headers have abbreviations and underscores. Instead, use the information in the "Alternatives column in the data dictionary when creating plots and reports.
7. NEVER use `print` statement. Rather create markdown cells and interpret the results in markdown text. I repeat, do not use the `print` function to create interpretations from results.

Data analysis instructions:
1. Use subsections (in the final section 'Exploratory Data Analysis') for each variable (column in `df`).
2. For each variable calculate summary statistics and data visualization. In the case of a numerical variable, calculate the sample mean, variance, standard deviation, minimum, first quartile, median, third quartile, and the maximum and then create a histogram of the values. Do not use a set number of bins. Rather use specified bin intervals at integer intervals such as (10,15], (15,20), ... , (75.80]. In the case of a categorical variable, calculate the frequency and the relative frequency of each class in the variable and then create a bar plot.