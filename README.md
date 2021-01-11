# School_District_Analysis

## Overview of the school district analysis:
* Initally I was tasked with doing a complete analysis for the school district regarding the test scores of 15 high schools. Once that analysis was completed, it was brought to my attention that there was some possible academic dishonesty and it would need to investigated. I removed the math and reading scores of the ninth grade students of Thomas High Shool. The analysis was then rerun and this output will display which metrics changed, if any.

****! This report is discuss the changes that occured from the initial analysis and the subsequent analysis.  !****

## Results

### The Differences

#### The District Summary - includes each student at each school and their respective math and reading scores.
* The removal of 9th grade scores affected every category. As you can there were drops in every category except for the average reading score, which remained at 81.9. Even the student count dropped, meaning they will no longer be accounted for in the new calculations.

![Original District Summary](Resources/course.district_summary.png)
Original
![Challenge District Summary](Resources/challenge_district_summary.png)
Challenge

#### The School Summary
* The other Thomas High metrics saw very subtle increases as well.
* Only the Thomas High data was modified, all other fields remain the same.

![Original_school_summary](Path)
![Challenge_school_summary]()

#### THS performance vs the other schools (with the ninth grade scores were removed)
* reading average and % passing increased

#### How did replacing the ninth grad scores affect the following:

* Math and reading scores by grade no difference
  - With these metrics there was no change at all except for the 9th grade category at Thomas High where there is now a NaN in place for the reading and math scores.

Original![Original](Resources/ori.bygrade.png)

Challenge![challenge](Resources/chal.bygrade.png)

* Scores by school spending
  - Thomas was in the $630-644 per student group, therefore that was the only category that had a change. All metrics had a very slight decrease.

Original![Original](Resources/ori.spending.png)

Challenge![challenge](Resources/chal.spending.png)

* Scores by school size
  - Thomas High was a medium sized school. All metrics decreased across the board.
Original![original](Resources/ori.schoolsize.png)

Challenge![challenge](Resources/chal.size.png)

* Scores by school type  
  - Since Thomas High is a Charter school, that was the category that was modifed by the deletion of the scores. The whole numbers were unchanged in either dataset, but the slight change is seenin the trailing decimal numbers.

Original![Original](Resources/ori.schooltype.png)

Challenge![challenge](Resources/chal.type.png)

#### Summary - (Summarize four major changes in the updated school district analysis after reading and math scores for the ninth grade at Thomas High School have been replaced with NaNs.)
- When the scores for tthomas were removed, it benefited the shool itself all metrics increased, when compared againstt other schools
- But when comparing on any other metric, spending, 
