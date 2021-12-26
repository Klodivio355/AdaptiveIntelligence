# AdaptiveIntelligence
Implementation of the COM3240 assignments

# Assignment 1 Feedback

Results and discussion : 56.5

Q1 &Q2 : The student should say clearly that backpropagation is derived through minimisation of an error function. The updating equations are incorrect, and the symbols adopted are not clearly explained.

Q3 : Clear plot with point of convergence clearly observable. No comment on when convergence has occured.

Q4 : Good accuracy achieved and basic comparison made. Reasons for better performance not explored or explained.

Q5 : Farily descriptive derivation, correct implementation in code.

Q6 : great work!

Q7 : nice job!

Q8 : Error bars must be given. Fair but limited discussion on the certain way performance changes shown in the figure. Some comparison to the linear model performance in the EMNIST paper should be made for full marks.

Report, code documentation and originality : 20
Well-structured report and clear figures. Well done!

# Assignment 2 Feedback

Results and discussion : 49
Q1 : Well done
Q2 : Fair description of exploitation vs exploration tradeoff, graphs clearly show effect of increasing epsilon and this is commented on in the text. Comparison between purely greedy and e-greedy might have been more clear but explanation still effective.
Q3 : Graphs are clear, but no error bars used which would have been useful for comparing stochastic experiments. In places parameter search too coarse to pick up on characteristics we'd expect to see in performance wrt parameter graphs (small improvement when a nominally small 0 Q4 : good work and intuition but no comparison between Sarsa(lambda) and Sarsa algorithms, which is converging faster and why? if there is any difference. 
Q5 : right intutition and fair attempt to the answer, but you didn't show a heatmap, say averaged over many runs with random initial locations (trials), of the directions or the arrows that the robot will be most probably take at each state in the grid to get to the homing location, using a quiever plot maybe. 
Q6 & Q7 : The solution to the problem of high dimensional space is correct, but should have been described in more detail. The student should have considered how to change the representation of the environment to adopt value function approximation. The graph reporting the preferred directions learnt by the agent is unclear...there are 5 colours with 4 possible directions.

Report, code documentation and originality : 17
Well-structured report and clear figures. References and figure captions should be added. For full marks it should be of journal standard.
