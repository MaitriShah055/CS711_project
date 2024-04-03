# Analysis of association between student participation and academic performance in online education

## This Project is based on the research paper "[Relationship between Student Engagement and Performance in e-Learning Environment Using Association Rules](https://ieeexplore.ieee.org/document/8451005])"

### The Paper uses association rules to find relationship between students engagement and their academic performance. The data is obtained from Learning Management System called *Kalboard 360*. However, they only considered boolean association rules for binary features. So, either a activity or engagment is present or not present at all. There are certain features that aer quantitative, but are converted to categorical variables. They obtained positive relationship between student engagement and their academic performance

***

### Based on this paper, our aim was to take into consideration the quantitative features which truly shows the engagement of the student and upto what point. Therefore, the dataset used have quantitative features like *Visited Resources* (number of times student Visited the resources), *Raised Hands* (number of times student raised hands), *Anouncement view* (number of times student Viewed announcement), *Discussion*(Number of times Student discussed on the forum).

### High Utility Itemset Mining algorithm [_Two-Phase_](https://link.springer.com/chapter/10.1007/11430919_79) was applied instead of Frequent Utility Mining algorithm _Apriori_.

### The [two-phase source](https://github.com/ZaxR/itemset_mining).


### The output shows association between quantitative variables and the final grade of the student. With more participation in activities, students can improve their academic performance

### Positive Relationship between student participation in online education and Academic performance was obtained.


## How to run the code:

### Download the dataset from the repository and save it to desired folder

### Run the EDA.ipynb to visualize the relationship between features.

### Run the preparation.ipynb to apply Two-phase HUIM algorithm. Change the path of Dataset to your desired location of the dataset.

### Utility Table is defined as per the importance of the feature

### Change the minimum Utility as per the requirement.


## Scope of the project:

### It can be used for Market Basket Analysis mainly. Also, as per our project it can be applied to analyze the performance of the student and thier participation in activities

### Moreover, it can be applied to any dataset with quantitative features. For example, to determine the association between the profit of a Company and the number of sale of the products.

## Output Obtained:

### Final output with true values for high utility itemsets.

![HUI in Student Dataset](https://github.com/MaitriShah055/CS711_project/blob/main/image.png)


## Conclusion:

### It can be concluded that more activities leads to more inclusion of student in the learning and that tends to improve their academic performance.

