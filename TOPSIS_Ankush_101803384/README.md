# TOPSIS Implementation by Ankush Gupta 101803384	
This package will get topsis score for selected csv file.

## Important Details
Input/Output Files:

Simple Python module for Multiple Criteria Decision Making System using TOPSIS.

Input/Output Files:

Input File: Input file contain three or more columns. First column is the object/variable name (e.g. M1, M2, M3, M4…...). The input file from 2nd to last columns contain numeric values only

Output Files: Result file contains all the columns of input file and two additional columns having TOPSIS SCORE and RANK

The parameters for the topsis functions are as follows:
-> The input file name. It must end with .csv. You can give the complete file path if you want to read a file from some specific place

-> The weights string contains weight either in float or numeric form separated by commas.
   Example: "1,1,2,3"

-> The impact string which is separated by commas for each impact and determines if weight at that index is to be taken positive or negative.
   Example: "-,+,+,+"

-> The output file name. It must end with .csv. You can give the complete path along with file name to save the file at specific place. Otherwise, it will save it as default where the package is installed.

The package has two function.. 

Sample Use case:

```
import TOPSIS_Ankush_101803384 
TOPSIS_Ankush_101803384.topsis("input.csv","1,1,1,2","+,+,-,+","output.csv")