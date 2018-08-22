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


### Paper [70/100]
In general, papers/project reports are written to describe, in detail, (1) a problem you are attempting to address, (2) how you plan to tackle it, (3) a careful evaluation of your findings, and (4) your final thoughts about the experiments and future work. In your introduction, you do well at highlighting what task you were hoping to automate with the use of machine learning, and to some extent, how you generated data to train your models. However, other portions of the report, such as the detail in your approach to tackling this problem and how you evaluate this approach, you could use some improvement.

In the background section, you cover the concept of CNNs. You could have provided a lot more detail both with respect to CNNs in general, as well as with regards to how they are used in image recognition, and it would have been better to cover them in separate section entirely. Some questions left unanswered, for example, are why you're using CNNs, why the number of layers in the CNN matters, and what kernels, pooling, and fully connected layers are and how they are used. As many people have used CNNs to solve captchas before, it would have been nice to see citations highlighting other work done in that area, as well as a more detailed description about how your approach is different and/or better.

There are also some technically incorrect claims. You state that you define the optimizer "using sigmoid_cross_entry rather than softmax to calculate the loss because sigmoid_cross is used for the case where every class is independent but not mutex while softmax_cross is used for that every class is independent and mutex." The use cases for the softmax and sigmoid are correct. However, the class labels in your problem are neither fully mutually exclusive (mutex) or non-mutex. You have a 144-length label vector (4 digits x 36 values per digit). The values for each digit (i.e., each group of 36 possible number/letter values) are mutually exclusive. For example, if the first digit is a 1, it cannot be a 2. However, the values for different digits are NOT mutually exclusive (i.e., if the first digit is a 1, the second digit can also be a 1). This is a fundamental limitation of the labeling approach you're using, and it's not adequately addressed by using a sigmoid (which assumes all values are not mutually exclusive) or softmax function (which assumes all values are mutually exclusive). You should instead break the problem into 4 separate labels, each of which uses a softmax function.

A substantial portion of your paper just consists of screenshots of your code, a title page, and snapshots of your model training output. I'm certain that the latter could have been presented as a table, and 1/2 page (instead of 3 pages) would have been sufficient to show the results. Code can be shared with your audience separately, as it consumes a large portion of the space you had available for your writing, and because it is somewhat secondary (in importance) to the findings you are describing in your paper. The unfortunate result is that because so much of your report was code and output, we feel that your report did not provide an adequate amount of content.

Your conclusion feels a bit more like a "Results" section. It also doesn't quite address two of the things we had asked students to include to that portion of their reports: (1) How do you think someone could now take your deliverable and use it to their benefit? (2) What would you try/do next if you had the time? There are many additional avenues that could have been explored with the approach taken that would have made for a more interesting conclusion, such as comparing the use of different activation functions, the use of different labeling approaches, the use of SVM as a classification layer, the use of residual units, the exclusion of dropout, etc. It would have also been useful to include comparisons with other models, such as logistic regression or SVM, on this same task. That said, we do hope that this project was fun, stimulating, and served as a good learning experience for you!


### Participation [85/100]


### Final Grade
84.99 (B)
