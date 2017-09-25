## Spam-Classifier
<br>
Naive Bayesian probability based spam classifier.<br> 
Created it as python implementation for the taugh octave spam classifier in Machine Learning Course by Andrew Ng.<br>

<br>

**Working**<br>

                
                Probability that a message containing a given word is spam
                                 P(W|S) * P(S)<br>
                 P(S|W) = ----------------------------- <br>
                          P(W|S) * P(S) + P(W|H) * P(H)<br>
                          
                          <br>
                          <br>
               
                   Probability that a given message is spam
                                           p1 p2 ... pN
                       p = ------------------------------------------------------
                                p1 p2 ... pN + (1 - p1)(1 - p2) ... (1 - pN)
                                
                                
<br>
**The classifier takes a body of known spam and ham (non-spam) emails to evaluate.(Just Like training)** <br>
Then, it evaluates each email in a test body of emails as spam or ham, with the difference between ham and spam only known to the classifier for the purpose of calculating the success rate.<br>

Several parameters can be changed to optimize the effectiveness of the classifier. By tweaking these parameters, rates in the upper 90% range for both spam and ham classification can be reached.<br>

**Usage** <br>
- Updating soon.......
