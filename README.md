# Code sample for CU Earth Lab Data Scientist Position  <a name="top"></a>
By: Chilisa Shorten (cmshorten@gmail.com)<br /> 
May 31, 2021

**This work represents provisional interpretations, please do not distribute.**

**Code Context:**<br />
This code represents a type of data I work with (ICP-MS data from mudstone samples) and statistical/machine learning methods which I commonly use. The script contains documentation within the function and markdown cells, which explain the processes so that others can understand and reproduce the same results. This script is capable of being applied to other datasets if the user structures the input file like the example (i.e. "Unit" column and three elements of interest) and provides <span style="color:red;font-weight:bold">!!! INPUT !!!</span> when prompted.

**Data Context:**<br />
The dataset in this example is from one study area with samples from two different units, the Mordecai and Rigby units (names changed to Regular Show cartoon characters due to the provisional nature of the data). The data are elemental amounts of potassium (K %), uranium (U ppm), and thorium (Th pmm) in mudstone samples. Samples were collected, ground, and analyzed for elements using ICP-MS. We are interested in determining if there are clusters within each unit – which may explain the variation of the unit across the study area – and examining how the three elements relate to each other.
