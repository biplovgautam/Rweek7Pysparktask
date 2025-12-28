## PySpark Analysis of Flying Etiquette Survey Data

[Dataset:](flying.csv) containing passengers' survey responses on airplane etiquette.

[Solution(ipynb):](PySpark_Analysis_of_Flying_Etiquette.ipynb) jupyter notebook file solution

[Solution(pdf):](PySpark_Analysis_of_Flying_Etiquette.pdf) pdf file solution
### Part a) Frequency of Air Travel
#### Write PySpark code to:

-  Load the "flying.csv" dataset using PySpark

- Construct a horizontal bar chart of the frequency variable (answers to "How often do you travel by plane?")

- Include a suitable title and proper axis labels

- Display the counts in descending order


### Requirements:

- Include your PySpark code

- Include the resulting bar chart

- Briefly describe the distribution of travel frequency among respondents
---
### Part b) Children and Attitudes Toward Babies on Planes

#### Consider the variables:

- children_under_18 (answers to "Do you have any children under 18?")
- baby (answers to "In general, is it rude to bring a baby on a plane?")

### Write PySpark code to:

- Remove any rows where either of these two variables is null
- Construct an appropriate graphical plot showing the relationship between the two variables (e.g., grouped bar chart, stacked bar chart, or cross-tabulation visualization)
- Include your PySpark code, graphical plot, and a written conclusion

### Questions to address in your conclusion:

- What is the relationship between having children under 18 and attitudes toward babies on planes?
- Do parents and non-parents have significantly different views?
- What patterns or trends do you observe?
---
### Part c) Age Groups and Reclining Seats Behavior
#### Consider the variables:

- age (respondent's age group)
- recline (answers to "Is it rude to recline your seat on a plane?")

#### Write PySpark code to:

- Filter out any rows with null values in either variable
- Create a contingency table showing the relationship between age groups and opinions on reclining seats
- Calculate the percentage of respondents in each age group who think it is rude to recline
- Create a grouped or faceted bar chart displaying these percentages by age group
- Interpret your findings: Which age groups are most likely to consider seat reclining rude? Is there a clear trend?

**Include in your answer:** PySpark code, contingency table, percentage calculations, visualization, and interpretation.

---
### Part d) Alcohol Consumption and General Rudeness Perceptions
#### Consider the variables:

- alcohol (answers to "Do you drink alcohol while flying?")
- rude (overall perception - answers to "How often do you observe rude behavior on planes?")
#### Write PySpark code to:

- Remove rows with null values in either variable
- Calculate summary statistics (count, proportions) for each combination of alcohol consumption and perceived rudeness
- Create an appropriate visualization (e.g., mosaic plot equivalent or heat map) showing the relationship
- Write a brief analysis: Does alcohol consumption appear to be related to how often passengers observe rude behavior? Is there a pattern?

**Include in your answer:** PySpark code, summary statistics, visualization, and interpretation.

---
### General Requirements for All Parts:
- Use PySpark DataFrames (not RDDs) for all data manipulation

- Use appropriate PySpark methods for filtering, grouping, and aggregation

- Use Python libraries (Matplotlib, Seaborn, or Plotly) for visualizations

- Include comments in your code explaining each step

- Ensure all visualizations have clear titles, axis labels, and legends where appropriate

- Write clear, concise interpretations of your findings

- For each analysis, state any assumptions you're making about the data