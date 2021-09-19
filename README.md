# Brain-Computer-Interface

Matlab-designed algorithm implemented with Machine Learning methods. The purpose was to use collected signal information to discriminate between right-lobe, left-lobe,
and passive acitivity. Research provided a few algorithms to choose from but due to a combination of time, simplicity, & resources it was decided to use LDA, Naive
Bayes, & Gaussian with Kernal algorithms. Initial stages found a low accuracy probability ranging from 27 - 53 % with an average of about 34. After retooling, Naive
Bayes found the best range with an average of 77%, & a range of 62 - 87 %. All other possibilities saw increases after retooling. 

Lessons Learned: All 13 sensors were used however a proper selection method could have increased probabilities by eliminating inconsequential signals. Due to a 
combination of issues, a proper method was not found as initial sensor selection found some higher accuracies but also lows and a very skewed average. Initially,
it was believed that the "zeroes" were inconsequential sensors however testing found reduced scores across the board. Investigation into this would've been grand
if time availed itself. 
