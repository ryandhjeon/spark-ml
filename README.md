# SparkML
__What technical errors did you experience? Please list them explicitly and identify how you corrected them.__

I started off using the physical cluster, hoping that no issues occur this time. For the linear regression part, it was working fine. Slow, but worked. 
When I started the logistic regression notebook, rendering stopped working with the gear icon spinning forever.
I tried stopping and restarting all the kernels, and notebooks for multiple times, but nothing worked. Rather than spending 5 hours trying to fix the issue, the dataset was comparably lot smaller than last reflection, so I decided to use the docker this time. It took a while to process, but I got all the output I wanted at the end. 

__What conceptual difficulties did you experience?__

In PySpark, there were two versions of ml libraries, mllib and ml. According to the documentation, mllib was a bit older version that uses RDD mainly. 
ML in the other hand used Dataframes mainly. The way of using two different libraries were totally different. In the logistic regression, the instructor specifically used `LogisticRegressionWithLBFGS`, so mllib was used. For the KMeans exercise, `ml` was used as I could understand the process better. 
I need to learn the best practice of using PySpark from heavy users.    

__How much time did you spend on each part of the assignment?__

Linear regression: 1 hr

Logistic regression: 3.5 hrs

KMeans: 3 hrs

__Track your time according to the following items: Gitlab & Git, Docker setup/usage, actual reflection work, etc.__

Gitlab & Git: Less than 10 minutes

Docker setup/usage: Less than 15 minutes 

Actual reflection work: About 9 hours including README  

__What was the hardest part of this assignment?__

The hardest part was trying to interpret what the instructor wrote in Scala language, and translate it to Python. 
I realized I cannot literally translate the code into Python, but more of refactoring approach using the Python.

__What was the easiest part of this assignment?__

Nothing is easy. However, since I am currently taking `Data Mining` course by Dr. Sarkar, where I am learning different techniques of regression, clustering in R, I had better understanding of the tasks in this reflection.

__What advice would you give someone doing this assignment in the future?__

There is not only a single way to solve a problem, and that is the beauty of programming. I would try multiple ways when a task is given. In the Spark ML document, you can see that there are so many options you can play with.
Try them out, and see what different results come out.

__What did you actually learn from doing this assignment?__

Every step from loading the data, preparing them, splitting them into training and test data, training for models, and evaluating. All these were possible in one platform, Spark with PySpark. I learned that Spark is the best framework that we can use for any data processing tasks.

__Why does what I learned matter both academically and practically?__

Linear regression, Logistic regression, and KMeans clustering is the ones out of many fundamental algorithms that we need to thoroughly understand, and be able to use it like an expert. 
It was a small dataset, but using PySpark I will be able to utilize it in a much larger dataset in the industry. Learning and experiencing how to utilize ML libraries in PySpark was a whole level upgrade in my skillset.    

## License
[MIT](https://choosealicense.com/licenses/mit/)
