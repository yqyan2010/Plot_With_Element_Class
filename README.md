# Plot_With_Element_Class
### I created a class in python named "Element". This class works with ICP-MS data.

### Explanation of Elment class and how to use it
- Element class loads a dataset called "sample.xlsx"
- "sample.xlsx" has 29 columns, each named as an element such as "Be","Mg","Fe","Ca","Hg","Pb" etc.
- Operation: iron=Element('Fe'), takes all data of Fe element
- Or operation: calcium=Element('Ca'), takes all data of Ca element
- Then you can use some simple functions to find out statistics of element data
  - iron.scatter: generate scatter plot of iron element
  - iron.histogram: generate histogram plot of iron element
  - iron.total: count the total datapoint of iron element
  - etc.

### Open Jupyte notebook "plot_with_element_class.ipynb" file and you will see examples
