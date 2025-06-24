# Collaboration Strategies
 Experiment on human machine collaboration strategies. 
 The study was developed by me and my collegue Alessia Papale in our lab, MUDI, of the Milano-Bicocca University starting from the inspiration to some previous work https://link.springer.com/article/10.1007/s13755-021-00138-8.

## Data Collection
The data have been collected in Gaetano Pini Hospital thanks to the collaboration of doctor Gallazzi.

## Data Preparation
Data preparation procedures are all reported in Kasparov_ALL notebook.

## Coordination Protocols 

1. Simple Majority: The first and second observer provide their judgments. The third observer is involved if and only if the first two observers disagree. The final decision is the majority choice of the three observers in the team. 
2. Accuracy-Oriented: he three observers provide their judgments. If they agree, their decision is taken as final. If they disagree, the decision is made by comparing the average accuracy of the two agreeing observers with the accuracy of the dissenting one. If the average of the pair is higher, their shared decision is chosen; otherwise, the dissenting opinion prevails.
3. Confidence-Oriented: he three observers provide their judgments. If they agree, their decision is taken as final. If they disagree, the decision is made by comparing the average confidence of the two agreeing observers with the confidence of the dissenting one. If the average of the pair is higher, their shared decision is chosen; otherwise, the dissenting opinion prevails.
4. Specificity-oriented: he first observer provides their judgment and the second observer is involved if and only if the first observer deemed the case abnormal. If the first two observers disagree, then the third observer is also involved. The final decision is made by comparing the average speci x confi, where specificity also accounts for how confident the observer is in this particular case, of the two agreeing observers with the same product computed for the dissenting one. If the average of the pair is higher, their shared decision is chosen; otherwise, the dissenting opinion prevails.
5. Sensitivity-oriented: he first observer provides their judgment and the second observer is involved if and only if the first observer deemed the case normal. If the first two observers disagree, then the third observer is also involved. The final decision is made by comparing the average sensi x confi, where sensitivity also accounts for how confident the observer is in this particular case, of the two agreeing observers with the same product computed for the dissenting one. If the average of the pair is higher, their shared decision is chosen; otherwise, the dissenting opinion prevails.
6. Cautious Protocol: The first two observers provide their judgments, accuracy, and subjective confidences. If they agree in their judgment, the team accepts the decision only if both have accuracy and confidence above a defined threshold α_acc and α_conf (acc_i ≥ α_acc and conf_i ≥ α_conf), both equal to the quantile 0.25 of human's accuracy and confidences respectively in the considered case. Otherwise, if the two observers disagree or if at least one of them has accuracy or confidence below the threshold α, the third observer is involved. The final decision is made by comparing the average acc_i x conf_i, where accuracy also accounts for how confident the observer is in this particular case, of the two agreeing observers with the same product computed for the dissenting one. If the average of the pair is higher, their shared decision is chosen; otherwise, the dissenting opinion prevails.
7. Presumptuous Protocol: The first two observers provide their judgments, accuracy, and subjective confidences. If both of them have accuracy above a defined threshold α_acc (acc_i ≥ α_acc), equal to the quantile 0.25 of the human accuracies in the considered case, the team’s decision is the same as the one provided by the observer with greater confidence. If at least one observer has accuracy below the threshold α_acc, the team follows the observer with the highest accuracy.
8. AND Rule: The first observer provides their judgment. The second observer is involved if and only if the interpretation of the first observer is abnormal and, in that case, the decision of the team is the same as the second observer’s.
9. OR Rule: The first observer provides their judgment. The second observer is involved if and only if the interpretation of the first observer is normal and, in that case, the decision of the team is the same as the second observer’s.


We are looking forward to hear your opinion about this project. Feel free to contact us for a comparison: g.lopiano1@campus.unimib.it, a.papale@campus.unimib.it
