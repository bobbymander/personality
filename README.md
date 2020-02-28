# personality

Analyzing personality survey data found on Kaggle.

Using python, numpy, pandas, and scikit-learn we will answer the below 4 questions related to this data.

Questions
1.  Can we predict the person's country based on his survey answers?  

Answer is not very well, reaching only 53% accuracy using logistic regression, K nearest neighbors, and decision tree models.

2.  Can we predict a person's time spent on the survey based on his survey answers?

No, not at all based on a rather poor r2 score.

3.  Are the questions in a group correlated with one another more than with other questions in other groups?

Yes, see heatmap pattern.

4.  Can we predict the person's country more accurately if we ignore some survey answers?

No, there was barely a difference in accuracy if we focused on the 20 top correlated columns.


## Installation

You will need a Jupyter notebook installation running a conda python3 kernel.  Once you have this, you will need the below file from GitHub:
	personality_project.ipynb
	
And the below files from Kaggle:
	data-final.csv
	codebook.txt

## Technologies

We used the below technologies in this project:
	python
	numpy
	anaconda
	pandas
	scikit-learn
	matplotlib
	seaborn
	
## References

GitHub Wiki:  https://github.com/bobbymander/personality/wiki/Your-Personality-Makes-You!
GitHub Code:  https://github.com/bobbymander/personality
Kaggle Data:  https://www.kaggle.com/tunguz/big-five-personality-test