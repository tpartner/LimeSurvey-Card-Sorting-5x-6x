# Card Sorting for LimeSurvey 4.x
**A custom question theme for "card sorting" in LimeSurvey 4.x**

![Image Card Sorting](/cardSort/survey/questions/answer/multipleshorttext/assets/images/card_sort_4.x_3.png)

**Implementation:**

1) Extract the download and upload the **cardSort** folder to */pathToLimeSurvey/upload/themes/question/*.

2) Create a multiple-short-text question, click Save.

3) Set the question setting "Question theme" to "cardSort", click Save.  
![Image Select cardSort](/cardSort/survey/questions/answer/multipleshorttext/assets/images/card_sort_4.x_1.png)

4) In the question setting "Sorting area names" field, enter a comma-separated list of the names for the sorting "buckets", click Save.  
![Image Enter Bucket names](/cardSort/survey/questions/answer/multipleshorttext/assets/images/card_sort_4.x_2.png)

5) Create subquestions as required.

**Notes:**

1) The styles for the theme can be modified in */pathToLimeSurvey/upload/themes/question/cardSort/survey/questions/answer/multipleshorttext/assets/css/cardsort.css*.

2) Array filter and array filter exclusion will only work if the filtering question is on a previous page.

3) Demo survey in */cardSort/survey/questions/answer/multiplenumeric/assets/demo/*.
    
    
*Custom themes are given without any warranty, implied or otherwise.*
