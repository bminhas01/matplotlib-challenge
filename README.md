# Matplotlib-challenge

This is an analysis of the most recent study of potential treatments for squamous cell carcinoma (SCC) conducted by Pymaceuticals Inc. The study comprised of treating 249 mice identified with SCC tumor growth with a variety of drug regimens. The goal is to determine whether Pymaceuticals' drug of interest, Capomulin, is demonstrably more or as effective as other regimens. 

Steps for Analysis:
* Detemine data does not include any duplicates or errors; if so, remove any data associated with that Mouse ID

* Create a summary statistics table consisting of the mean, median, variance, standard deviation, and SEM of the tumor volume for each drug regimen

* Generate a bar plot to display total number of measurements taken for each treatment regimen (use both Pandas's `DataFrame.plot()` and Matplotlib's `pyplot)

* Generate a pie plot that shows the number of male vs. female mice in the study (use both Pandas's `DataFrame.plot()` and Matplotlib's `pyplot)

* Isolate the data for mice receiving the four most promising treatments: Capomulin, Ramicane, Infubinol, and Ceftamin, and determine the final tumor volume for each mouse. Identify any potential outliers by calculating the quartiles and IQR.

* Generate a box and whisker plot of the final tumor volumes for the four regimens and highlight any potential outliers

* Randomly select a mouse from the Capomulin sample and generate a line plot of tumor volume vs. time point

* Using the Capomulin sample again, generate a scatter plot of mouse weight vs. average tumor volume

* Include at least three observations or inferences made from the data provided at the top of the notebook. 