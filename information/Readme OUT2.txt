OUT2
----

The Out2 test data has been drawn from wikipedia. This dataset was used in the first Jigsaw competition on Kaggle, in which teams had to classify different types of (non-)toxic posts. More information on the challenge and the dataset can be found here:

https://www.kaggle.com/competitions/jigsaw-toxic-comment-classification-challenge/data

I sampled and reformatted the original test data to make it more in line with the other datasets: I only preserved the labels for "toxic" and "severe_toxic" posts and got rid of the others. I then randomly selected 600 non-toxic posts, 300 moderately offensive ones and 300 severely offensive posts for you to test your models on. The distinction between the moderately and the severely offensive posts has not been preserved in the labels: "NOT" means not toxic, "OFF" means either offensive or severely offensive.