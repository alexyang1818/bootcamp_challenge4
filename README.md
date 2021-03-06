# Boot Camp Challenge 4: PyCitySchools

## **Overview of the school district analysis:**

This report compared analysis results after the math and reading scores for the 9th grade at Thomas High School have been replaced with NaNs.

## **Results:**

After the math and reading scores of the 461 ninth graders at Thomas High School have been replaced with NaNs, the following analysis results were affected.

### District Summary 
*District Summary before Correction*

![District Summary before Correction](./Resources/district_summary_before_correction.png)

*District Summary after Correction*

![District Summary after Correction](./Resources/district_summary_after_correction.png)

Both the math and reading scores have dropped based on the average scores and the passing percentages.

### School Summary

*School Summary before Correction*

![School Summary before Correction](./Resources/school_summary_before_correction.png)

*School Summary after Correction*

![School Summary after Correction](./Resources/school_summary_after_correction.png)

For the school summary, obviously only Thomas High School is affected by the correction. Its average math score decreased by 0.07 but its average reading score increased by 0.05. The passing percentages decreased by 0.1-0.3%.

### Thomas High School’s performance relative to the other schools

*Top 5 Schools before Correction*

![Top 5 Schools before Correction](./Resources/top_5_before_correction.PNG)

*Top 5 Schools after Correction*

![Top 5 Schools after Correction](./Resources/top_5_after_correction.PNG)

Thomas High School remained as the second best performance based on the overall passing percentage no matter of a slight decrease in the overall passing percentage.

### How does replacing the ninth-grade scores affect the following:
- Math and reading scores by grade

*Math Score by Grade before Correction*

![Math Score by Grade before Correction](./Resources/score_by_school_math_before_correction.PNG)

*Math Score by Grade after Correction*

![Math Score by Grade after Correction](./Resources/score_by_school_math_after_correction.PNG)

*Reading Score by Grade before Correction*

![Reading Score by Grade before Correction](./Resources/score_by_school_reading_before_correction.PNG)

*Reading Score by Grade after Correction*

![Reading Score by Grade after Correction](./Resources/score_by_school_reading_after_correction.PNG)

The math and reading scores by grade did not change, except for the ninth grade of Thomas High School, which were replaced by "NaN"s.

- Scores by school spending

*Scores by school spending before correction*

![Scores by school spending before correction](./Resources/scores_by_school_spending_before_correction.PNG)

*Scores by school spending after correction*

![Scores by school spending after correction](./Resources/scores_by_school_spending_after_correction.PNG)

The scores by school spending on every student is not affected upon the updated analysis.

- Scores by school size

*Scores by school size before correction*

![Scores by school size before correction](./Resources/scores_by_school_size_before_correction.PNG)

*Scores by school size after correction*

![Scores by school size after correction](./Resources/scores_by_school_size_after_correction.PNG)

The scores by school size is not affected upon the updated analysis.

- Scores by school type

*Scores by school type before correction*

![Scores by school type before correction](./Resources/scores_by_school_type_before_correction.PNG)

*Scores by school type after correction*

![Scores by school type after correction](./Resources/scores_by_school_type_after_correction.PNG)

The scores by school type is not affected upon the updated analysis.

## **Summary:**

Replacing the ninth grade at Thomas High School does not change the results of this analysis. The math and reading scores analyzed against capita spending, school size, and school type remain the same upon the correction. The only change is that the score for the ninth grade at Thomas High School is "NaN", which is expected.