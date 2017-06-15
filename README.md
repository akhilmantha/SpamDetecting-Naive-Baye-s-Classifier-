# SpamDetecting-Naive-Baye-s-Classifier-
It is a basic Ml Classifier which can be used to detect spam mails.

Naive Bayes’ Classifier:
We can set A to the probability that the email is spam and B as the contents of the email. If P(A|B) > P(¬A|B) then we can classify the email as spam, otherwise we can’t. Note that since Bayes’ Theorem results in a divisor of P(B) in both cases, we can remove it from the equation for comparison. This leaves: P(A)*P(B|A) > P(¬A)*P(B|¬A). Calculating P(A) and P(¬A) is difficult, they are simply the percentage of your training set which are spam versus not spam.
Laplace Smoothing:
Generally a condition may arise where the word found is not in the training set. To handle this condition, laplace factor can be used.
