# Anomaly-Detection

Suppose you want to develop a model that can detect anomalous connections to your company's server. The server log contains all the information of historical connections; your nice colleague has already helped you to transform the raw log into a collection of feature vectors, where each feature vector characterize a connection in 40 dimensions, e.g., number of failed login attempts, length (number of seconds) of the connection. Here is one example feature vector:


[udp,SF,0,105,146,0,0,0,0,0,0,0,0,0,0,0,0,0,0,0,0,1,1,0.00,0.00,0.00,0.00,1.00,0.00,0.00,255,240,0.94,0.01,0.00,0.00,0.00,0.00,0.00,0.00]
