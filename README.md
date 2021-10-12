#### **Overview** 

The main objective of this analysis was to see if Thomas High School has manipulated the data for the ninth graders reading and math scores. There was no evidence that proves there was a manipulation but school board would like to double check since there are state-testing standards to follow and abide to. 

The ask is to replace all the ninth graders reading and math scores with null values and run the analysis again on district and school level. 

#### **Comparisons and Results:

- **How is the district summary affected?**

![dis_summary_old](/Resources/dis_summary_old.PNG)

![dis_summary_new](/Resources/dis_summary_new.PNG)

***New analysis in second picture with black background(after applying NaN's)*

As we can see from the pictures above there's a slight change in decimal points for percentages columns(Passing Math and Passing Reading) and a decimal point difference on Average Math Score. If we round up the decimal point then there won't be any differences between the old and new numbers. 

- **How is the school summary affected?**

![school_summary_old](/Resources/school_summary_old.PNG)

![school_summary_new](/Resources/school_summary_new.PNG)

***New analysis in second picture with black background(after applying NaN's)*

The school summary for every other school remains the same but there's a significant change on the Thomas High School numbers now. In one place the Average Math score was a decimal point higher than the newer number whereas the Average Reading score is untouched. The percentages of Passing Math and Passing Reading is down by 25-29% percent which make sense since all the ninth graders have a null value for their scores. If we change the calculation and use total_new_student_count variable in "School Summary" code instead of per_school_counts our number will be significantly higher.

- **How does replacing the ninth graders’ math and reading scores affect Thomas High School’s performance relative to the other schools?**

  By replacing the ninth grader's math and reading score at Thomas High School, the school ranking dropped from being No. 2 to 8th. The overall Passing percentage dropped from 90% to 65%. 

- How does replacing the ninth-grade scores affect the following:

  - **Math and reading scores by grade**

    - Comparison of Math Scores

      ![math_scores_old](/Resources/math_scores_old.PNG) ![math_scores_new](/Resources/math_scores_new.PNG) 

    ***New analysis in second picture with black background(after applying NaN's)*

    - Comparison of English Scores

      ​	![reading_scores_old](/Resources/reading_scores_old.PNG) ![reading_scores_new](/Resources/reading_scores_new.PNG) 

      ***New analysis in second picture with black background(after applying NaN's)*

      As we can see from the above analysis that changing the math and reading scores to nan didn't affected any other graders(10th-12th) or any other school numbers. 

  

  - **Scores by school spending**

    ![spending_summary_old](/Resources/spending_summary_old.PNG)

    ![spending_summary_new](/Resources/spending_summary_new.PNG)

    ***New analysis in second picture with black background(after applying NaN's)*

    There is no change in numbers as shows above from school spending analysis comparison.

    

  - **Scores by school size**

    ![school_size_old](/Resources/school_size_old.PNG)

    ![school_size_new](/Resources/school_size_new.PNG)

    ​	***New analysis in second picture with black background(after applying NaN's)*

    ​	There is no change in numbers as shown above from school size analysis comparison.

    

  - **Scores by school type**

  ![school_type_old](/Resources/school_type_old.PNG)

  ![school_type_new](/Resources/school_type_new.PNG)

  ​			***New analysis in second picture with black background(after applying NaN's)*

  ​			There is no change in numbers as shows above from school type analysis comparison.

  

#### **Summary:

Overall as we saw on the district level that there wasn't a significant change in the numbers but at the school level dropping the scores had a significant impact. The school ranking dropped from being no. 2nd to no. 8th out of 15 schools. We didn't saw any significant changes in the "School Size", "School Spending" or "School Type". 
