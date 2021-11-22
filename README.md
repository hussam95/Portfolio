# SMS Spam Filter Using Naive Bayes Algorithm

In this project, we will use Naive Bayes Theorem to build a spam filter for unwanted text messages (SMS). Naive Bayes theorem is a way to test the validity of a hypothesis against some evidence based on prior knowledge. 

In our case, we will label new SMS either a spam or not spam as a hypothesis. We will then test these two hypotheses using the evidence or prior knowledge availbe in this [dataset](https://archive.ics.uci.edu/ml/datasets/sms+spam+collection). 

Naive Bayes algorithim utilzies the power of probabilities to assign different values to our two hypotheses. The one with greater probability value (spam hypothesis or not spam hypothesis) will decide whether the new message is a spam or not. In other words, we will update our beliefs (spam or not spam) using new evidence. 
