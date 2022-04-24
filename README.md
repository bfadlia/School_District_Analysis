# School_District_Analysis_Challenge
PyCitySchools Project

## Objective
1. Learn about using Jupyter Notebook to open files from local directories.
2. Read external CSV file into a DataFrame.
3. Format, search, groupby, replace columns, merge, filter and slice dataframes.



## Purpose
PyCity school district suspected Thomas High School's 9th grade Reading and Math scores have been falsified to make the school results look better. The district board asked in this project for us to locate and remove this specific data then perform re-apply the analysis of the district-wide data to compare the results beore and after the removal of the wrong data. 


## Results

### How is the district summary affected?
Original Analysis:
-I main difference after replacing Thomas High school 9th grade math and reading results with NaN has been a big drop in their passing rate, dropping from the 90's t0 mid 60s.

# Thomas High school rates
- The original rate for Thomas High School
  - ![IMAGE_DESCRIPTION](/Resources/THS-Original.png)
  
- Their score after replacing the 9th grade scores with Nan
  - ![IMAGE_DESCRIPTION](/Resources/THS-new.png)

- However, when totally disregarding their 9th grade and calculating their rates bases only on their 10th thru 12th grades, the rates come back up to similar high levels like they had originally
  - ![IMAGE_DESCRIPTION](/Resources/THS-adjusted.png)
- Also, Thomas High school rank among the other schools in the district was initially second from the top, then dropped to 8th place after replacing the 9th grade scors, but when ranking only by its 10th thru 12th grade results it returns to its second from the top spot

# District overall rates
- The overall score for the district saw very slight change since Thomas High school few hundred 9th grade students are not significant compared the the 39K students the district has overall

  - The originall district overall numbers looked like this
  - ![IMAGE_DESCRIPTION](/Resources/overall-original.png)
  - their modified overall results looked like this
  - ![IMAGE_DESCRIPTION](/Resources/overall-new.png)

# District rates by grade, spending, size and type
- There is hardly any noticable change across any of these categories since Thomas high school 9th graders are in the hundreds and not significant compared to the district 39k students. The non significant difference is usually only seen in the hundredth of a percintile and only in the bucket where Thomas high school is categorized.

  - Math and reading by grade only has the difference of Thomas High School 9th grade having Nan instead of their numbers. All other grades and schools are not any different
  - Scores by school spending only the $630-$644 range which Thomas High school falls in sees its scores 
     - ![IMAGE_DESCRIPTION](/Resources/spending.png)




