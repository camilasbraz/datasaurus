# Importance of Visualizing and Analyzing Data Instead of Solely Relying on Indicators

Do you have the habit of merely analyzing indicators or the results of an analysis without looking at how the data is distributed? If so, you might be overlooking the power of visualization!

In 1973, the statistician Francis Anscombe expressed his concern about this phenomenon by presenting Anscombe's Quartet, a set of four graphs that challenged the prevailing idea at the time that data calculations and indicators should take precedence over visualizing this information in data analysis.

All the data sets in the Quartet share the same statistical properties, such as mean and standard deviation, and therefore yield identical indicators. However, when you plot the graphs and visualize the results, you'll notice that each data set has a distinct profile. Analyzing them solely based on the result of regression or other models does not generate the necessary information to effectively understand the problem, identify what's happening, and propose effective solutions.

To illustrate this situation, let's consider a scenario where you want to investigate the relationship between the amount of advertising for a product and its sales, for example. After conducting research, you find that the mean and standard deviation of the advertising quantity are 54.26 and 19.76, and for sales, they are 47.83 and 26.93. Additionally, the correlation between these two variables is -0.06. The four graphs presented in this post have these statistical properties, and considering only these calculated pieces of information can lead to incorrect conclusions about the behavior and relationship between these variables.

In Anscombe's words: "Do both calculations and graphs. Both types of results should be studied; each will contribute to understanding."

If you want to learn more about this topic, I recommend reading the article "Same Stats, Different Graphs: Generating Datasets with Varied Appearance and Identical Statistics through Simulated Annealing," available at [this link](https://dl.acm.org/doi/10.1145/3025453.3025912). And if you'd like to reproduce these graphs locally to investigate this phenomenon, you can fork this repo.
