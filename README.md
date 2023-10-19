The method (George) we'd like you to implement has a 3 step pipeline:
1. Train a model using ERM
2. Cluster inputs based on the output they produce for ERM
3. Retrain using "Group-Balancing" to ensure each you sample batches s.t. each group appears equally.
