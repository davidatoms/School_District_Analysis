# School District Analysis

###### Written by: David Adams
###### Written on: January 22, 2021
###### Python, Pandas, Jupyter Notebook

### Overview of the School District Analysis project
- [X] Deliverable 1: Replace ninth-grade reading and math scores for Thomas High School
- [X] Deliverable 2: Repeat the school district analysis
- [X] Compare the PyCitySchools Module to the PyCitySchools Challenge Code

The purpose of this project was to frame and group student data from specific schools based on multiple categorizes such as school type, school size, school budgets in a certain district. By framing this data, it is easier to list out and understand the student scores for reading and math within those certain categories.

The data in jupyter notebook pieces together the data of this school district.
 
### Process of Analysis
1. Followed the instructions and coded through the module.
2. Followed instructions on the Challenge Starter document.
3. Compared the outputs.
4. Provided further testing possibilities.

### Results from updating the School District Analysis to match Deliverable 1

In the first PyCitySchools python file, the ninth-grade reading and math scores for Thomas High School have not been changed. The data in that file remains as it was inputted. For the data in the PyCitySchool Challenge file, the ninth-grade reading and math scores for Thomas High School have been changed to 'NaN'. 

* How is the district summary affected?

*The code:*
```
# Create a District Summary DataFrame
district_summary_df = pd.DataFrame(
          [{"Total Schools": school_count, 
          "Total Students": student_count, 
          "Total Budget": total_budget,
          "Average Math Score": average_math_score, 
          "Average Reading Score": average_reading_score,
          "% Passing Math": passing_math_percentage,
         "% Passing Reading": passing_reading_percentage,
        "% Overall Passing": overall_passing_percentage}])
```   
*Output PyCityModules:*

![PyCitySchools](/Desktop/Education/columbia/Coding/Data_Science_Bootcamp/Columbia_Module_4/School_District_Analysis/Resources/PyCitySchools.png)

*Output PyCityChallenge:*

![PyCityChallenge](/Desktop/Education/columbia/Coding/Data_Science_Bootcamp/Columbia_Module_4/School_District_Analysis/Resources/PyCityChallenge.png)
       
The overall percentage of passing students decreased in the PyCityChallenge file. Thomas High School ninth-graders didn't score as well as the rest of the district in reading or math. I only compared the test scores because it was the only aspect of the data changed from the PyCity Modules and the Challenge.

* How is the school summary affected?
* How does replacing the ninth graders math and reading scores affect Thomas High School performance relative to the other schools?
* How does replacing the ninth-grade scores affect the following:
    * Math and reading scores by grade
      * Before
      
      * After
      
    * Scores by school spending
      * Before
      
      * After
      
    * Scores by school size
      * Before
      
      * After
      
    * Scores by school type
      * Before
      
      * After
      
### Conclusions


### Further Testing
    
