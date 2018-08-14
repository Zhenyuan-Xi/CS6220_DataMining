"# ZhenyuanXi-assignments"   

https://github.com/Zhenyuan-Xi/ZhenyuanXi-assignments

### Assignment 0 [100/100]  
Well done!

### Assignment 1 [96/100]
1. 10/10
2. 10/10
3. 10/10
4. 20/20
5. 30/30
6. 16/20 &nbsp;[The description about what you have observed from the results is not enough]

Comments: Good job!

### Assignment 2 [70/100]
1. 35/35
2. 35/35
3. 0/30 &nbsp; [Missing]

Comments: May be more careful with questions next time :)

### Assignment 3 [100/100]
#### 1.1
1. 10/10
2. 10/10 
3. 10/10

#### 1.2
1. 15/15
2. 15/15

#### 1.3
1. 15/15
2. 15/15
3. 10/10

### Assignment 4[100/100]
#### 1.1
1. 10/10
2. 10/10
3. 5/5
4. 5/5

#### 1.2
1. 10/10
2. 10/10

#### 1.3
1. 15/15 [You can use matplotlib.pylab here]
2. 15/15

#### 1.4
1. 20/20

Comments: Good job.

### Assignment 5 [100/100]
#### Parrt one
1. 10/10
2. 20/20 &nbsp; [You should generate all the 12 plots here.]
3. 20/20

#### Part two
1. 25/25
2. 25/25

Comments: Great!


### Midterm [94/100]
1. 10/10
2. 2/10 [PCA ignores the labels of the data. Here, the direction with greatest variance (and first principal component) is the vertical direction; the second component will be in the horizontal direction.]
3. 10/10
4. 10/10
5. 10/10 
6. 10/10 
7. 8/10 [You did a good job defining both cohesion and separation metrics (as well as the silhouette coefficient). I would have liked to see a more clear description of why certain values for cohesion/separation indicate good/bad clusters, or perhaps why negative silhouette coefficient values are undesirable.]
8. 10/10 [Well done!]
9. 10/10 
10. 10/10 
11. Extra Credit. 4/10 [The use of association rules is not a bad idea. However, it is still probably not the best method to apply of those we have discussed. In particular, association rules are not personalized; they are not based on user histories, but rather itemset histories. They do not account for similarities between users, only the co-occurrence of items (e.g., diseases) in the data.]


### Quiz 1 [7/7]
1. 1/1
2. 2/2
3. 1/1
4. 1/1
5. 2/2


### Proposal [100/100]

### Quiz 2 [7/10]
1. 0/2 [the answer should be voting and stacking -- There are two approaches for combining models: voting and stacking (page 45 in lecture 11 slide)]
2. 2/2 [By manipulating the training set;<br> By manipulating the input features; <br>By manipulating the class labels into a binary class problem；<br>By manipulating the learning algorithm (answer comes from Everaldo and Reid)]
3. 2/2 [good answer]
4. 2/2 
5. 1/2 [Your answer is not completed. The important thing shoud be the words frequency and weighting. You should give more details in "text information". Here's the reference answer--<br>TF-IDF captures information about how frequent certain words are across all documents, and it uses that to weight the value assigned to those terms. This allows words that are very common across the entire dataset (e.g., “the”, “in”, “at”, etc.) to have their importance reduced, which is often very helpful.(answer comes form Everaldo and Reid)]

Comments: It seems like you have gained a good grasp of the content in last course.


### Final [85/100]
1. 3/10 [Not necessarily. You're completely correct about the properties of PCA. But we can have high-dimensional data with unrelated features. In many cases, PCA will actually make classes less well-separated and classification more challenging.]
2. 8/10 [3 out of 4 correct; 1 partially correct]
3. 4/10 [The conditional independence assumption actually helps avoid the Curse of Dimensionality, which is more of a problem when considering features together rather than separately. Due to the "naive" independence assumption, naive Bayes only considers one dimension at a time, avoiding some of the problems with a large number of dimensions.]
4. 8/10 [We would typically expect Everaldo's estimate to be better, because while the relative percentages of instances sampled are the same, Everaldo would have sampled more instances in absolute number. It follows that his estimate is then more likely to be accurate.]
5. 10/10 [Good! The use of Lapacian smoothing is typically a little different (simply applied to the feature in question), but you clearly understand how multinomial naive Bayes works!]
6. 10/10
7. 10/10
8. 10/10
9. 10/10 [Great explanations!]
10. 7/10 [a.) While family A initially achieves a higher TPR, the screening test must prevent false negative outcomes as much as possible, even at the cost of additional false positive outcomes. So the best choice for the screening test is a classification model that maximizes the TPR even at relatively high FPR. As family B achieves a higher maximum TPR than A, family B is the best choice for the screening test.]
11. Extra Credit. 5/10 [You're correct that the perceptron will perform poorly and random forest will perform well. Also, naive Bayes may perform well, but it depends on the type of naive Bayes model. 5NN and a decision tree should perform relatively well.]
