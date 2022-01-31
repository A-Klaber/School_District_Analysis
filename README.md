# School_District_Analysis
## School_District_Analysis Purpose
A high-level snapshot of the district's key metrics, presented in a table format
An overview of the key metrics for each school, presented in a table format
Tables presenting each of the following metrics:

	- Total School Budget and the Per Student Budget
	- Top 5 and bottom 5 performing schools, based on the overall passing rate
	- The average math score received by students in each grade level at each school
	- The average reading score received by students in each grade level at each school
	- School performance based on the budget per student
	- School performance based on the school size 
	- School performance based on the type of school
	

Look to see if there is any correlation with the budget per student and the passing scores. 
The School board has found evidence of academic dishonesy, we are to remove THS 9th grade scores and compare results.
[Challenge file .ipynb](PyCitySchools_Challenge.ipynb )

### How is the district summary affected?

The distric summary was affected very little.

	- avarage math score -0.1
	- average reading score no change
	- % Passing Math -0.2%
	- % Passing Reading -0.3%
	- % Overall Passing -0.1%

### How is the school summary affected?

The over all passing for Thomas High School had also little change.

	- avarage math score -0.07
	- average reading score +0.05
	- % Passing Math -0.09%
	- % Passing Reading -0.29%
	- % Overall Passing -0.32% 
	
[results](Resources/change.png )

### How does replacing the ninth grade math and reading scores affect Thomas High School’s performance relative to the other schools?

No change was found.

### How does replacing the ninth grade scores affect the following: #Math and reading scores by grade

The only difference in the scores is 9th graders who attended THS show an NaN.

### Scores by school spending

No change was found.

### Scores by school size

No change was found.

### Scores by school type

No change was found.

## Conclusion

After replacing the scores of the 9th grade students, at THS, we learn that very little has changed. 
