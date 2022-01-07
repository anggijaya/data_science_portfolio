# satria_portfolio
Data Science Portfolio

# Project 1: Anomaly Detection using Isolation Forest
One of the proven anomaly detection algorithms is the Isolation Forest. As the name implies - this is an ensemble of trees, which are built independently of each other. But in this case, the principle of building a tree is different from what is used in regression or classification problems - minimizing the splitting criterion at each step. The trees are also binary, but at each node the feature is chosen randomly, the feature values for splitting are also chosen randomly from the range (min, max) that the feature accepts. The tree is built to the maximum possible depth - when there is only one object in each leaf. With this approach, it appears that the anomalies will get to the final leaf much earlier than normal objects. This is the principle of detecting anomalies which Isolation Forest uses, this algorithm "isolates" anomalies by normal objects at early steps.
