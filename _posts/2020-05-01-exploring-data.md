---
published: false
---
## exploratory data analysis

##### 5/01/2020
**https://www.kdnuggets.com/2019/07/10-simple-hacks-speed-data-analysis-python.html

##### 10 hacks to speed up data analysis

Here is a quick summary:

#1 on this ten item list is to use Pandas Profiling to initially explore the dataframe. This package creates a histogram, most frequent values, correlations, quantile statistics, descriptive statistics and essentials: type, unique values, missing values all in a ready made report.

#2 Plotly and cufflinks are for interactive graphs.

#3 Magic commands is a list of commands that run after '%'. For example, the %matplotlib inline is a magic command. It's complement is %matplotlib notebook, which offers more interactivity than the previous by offering more functions like zooming.

#4 %debug is an magic command that can be run after an error has occured to further explore the issue.

#5 pprint is similar to .prettify() for printing out pretty/formatted data.

#6 Make notes stand out by applying colors through classes(class="alert alert-block alert-info").

#7 print out multiple outputs without using print() by running: 

"from IPython.core.interactiveshell import InteractiveShell InteractiveShell.ast_node_interactivity = "all""

and to restore to the original settings: 

"InteractiveShell.ast_node_interactivity = "last_expr""

#8 Running python scripts in the terminal with -i tag. One of the cool benefits of this is that the python shell remains open after the script runs so you can check variables and such. 

#9 Comment out lines of code at a time by pressing cmd/ctrl + /

#10 cmd/ctrl + z undoes delete, now add esc to that and it will undelete the entire cell.

