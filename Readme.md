# Analysis of association between student participation and academic performance in online education

## This Project is based on the research paper "[Relationship between Student Engagement and Performance in e-Learning Environment Using Association Rules](https://ieeexplore.ieee.org/document/8451005])"

### The Paper uses association rules to find relationship between students engagement and their academic performance. The data is obtained from Learning Management System called *Kalboard 360*. However, they only considered boolean association rules for binary features. So, either a activity or engagment is present or not present at all. There are certain features that aer quantitative, but are converted to categorical variables.

***

### Based on this paper, our aim was to take into considereation the quantitative features which truly shows the engagement of the student and upto what point. Therefore, the dataset used have quantitative features like *Visited Resources* (number of times student Visited the resources), *Raised Hands* (number of times student raised hands), *Anouncement view* (number of times student Viewed announcement), *Discussion*(Number of times Student discussed on the forum).

### High Utility Itemset Mining algorithm _Two-Phase_ was applied instead of Frequent Utility Mining algorithm _Apriori_.

### Positive Relationship between student participation in online education and Academic performance was obtained.