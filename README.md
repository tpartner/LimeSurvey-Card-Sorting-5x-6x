# Card Sorting for LimeSurvey 5.x
**A custom question theme for "card sorting" in LimeSurvey 5.x**

Compatible with LimeSurvey version 5.x.

![Image Card Sorting](/Card-Sort/survey/questions/answer/multipleshorttext/assets/images/card_sort_5x_4.png)

**Implementation:**

1) - **Manual installation** - Extract the download and upload the *Card-Sort* folder to */pathToLimeSurvey/upload/themes/question/*.
    - **Theme manager** - Extract the download, compress (zip) the *Card-Sort* folder and import via the theme manager.

2) Create a multiple-short-text question, click Save.

3) Set the question setting "Question type" to "Card Sort", click Save.  
![Image Select cardSort](/Card-Sort/survey/questions/answer/multipleshorttext/assets/images/card_sort_5x_1.png)

4) In the question setting "Sorting area names" field, enter a comma-separated list of the names for the sorting "buckets", click Save.  
![Image Enter Bucket names](/Card-Sort/survey/questions/answer/multipleshorttext/assets/images/card_sort_4.x_2.png)

5) Create subquestions as required.

**Notes:**

1) The styles for the theme can be modified in */pathToLimeSurvey/upload/themes/question/Card-Sort/survey/questions/answer/multipleshorttext/assets/css/cardsort.css*.

2) Array filter and array filter exclusion will only work if the filtering question is on a previous page.

3) Demo survey in */Card-Sort/survey/questions/answer/multiplenumeric/assets/demo/*.
    
    
*Custom themes are given without any warranty, implied or otherwise.*
