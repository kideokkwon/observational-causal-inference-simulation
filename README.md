# observational-causal-inference-simulation
simulating different (observational) causal inference concepts

The intention is mostly for self-learning - these are some of the methods that I've studied for work-related projects because a lot of people agree that simulating data and playing with the results yourself is an important complement to reading the available literature, and I think this is especially important for observational causal inference projects due to its delicate nature. Posting it publicly of-course helps induce a heightened feeling of accountability (perhaps artificial) as well as inviting feedback, another great way to learn. 

Observational causal inference is delicate because the results can make big claims that product teams would always love to know (causal relationships) but it's also very difficult because all methods rely on untestable assumptions. Therefore, unlike some other data science domains where the results can be more trustable due to the type of available diagnostic methods, in causal inference (not saying that there aren't diagnostic methods in causal inference by the way - there definitely are) you have to prove that your method is academically valid (e.g., is it still best practice in the ever-improving literature?) as well as being able to convince yourself and your audience that the analysis you've performed has minimal human-induced bias (you need to be impartial to the results), and that the untestable assumptions you've invoked on your work is *fair*.

So far the topics covered are:
1. Matching methods
2. Sensitivity Analysis (for cross-sectional data)
3. Panel methods


