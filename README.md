# Federated-Learning-Empowered-Breast-Cancer-Diagnosis

Breast cancer remains one of the most prevalent and lethal diseases affecting women globally. Timely and accurate diagnosis plays a pivotal role in improving patient outcomes and guiding appropriate treatment strategies. In recent years, the convergence of machine learning (ML) and federated learning (FL) techniques has emerged as a promising approach to address the challenges associated with data privacy and security while enhancing the diagnostic accuracy of breast cancer classification models.
Traditional ML models often require centralized access to large volumes of sensitive medical data, posing significant privacy concerns and logistical challenges. Federated learning offers a decentralized alternative by enabling model training across distributed data sources while preserving data privacy at individual institutions or devices. This collaborative approach allows healthcare providers to leverage the collective knowledge embedded in diverse datasets without compromising patient confidentiality.
The primary objective of this study is to develop a hybrid ML model for breast cancer diagnosis, integrating federated learning principles to facilitate collaborative model training across multiple healthcare institutions or devices. By aggregating insights from heterogeneous datasets, the proposed approach aims to enhance the robustness and generalizability of the classification model, ultimately improving diagnostic accuracy and patient care outcomes.
This introduction lays the groundwork for exploring the synergies between federated learning and machine learning in the context of breast cancer diagnosis. Subsequent sections will delve into the methodology, architecture, and implementation of the federated learning-enabled classification model, highlighting its potential to revolutionize collaborative healthcare analytics while safeguarding patient privacy.

# Models used:

## Perceptron 
A single-layer perceptron is the basic unit of a neural network. A perceptron consists of input values, weights and a bias, and a weighted sum.
![image](https://github.com/gap10/Federated-Learning/assets/61880360/c0ff914c-7c1a-4d6b-b2c7-ca5d25c44adb)
We can use the readily available perceptron model implementation of the Scikit learn library. We however, have implemented the model from scratch because accessing weights and bias is easier this way.

## Support Vector Machine (SVM)  
The main objective of the SVM algorithm is to find the optimal hyperplane in an N-dimensional space that can separate the data points in different classes in the feature space. The hyperplane tries that the margin between the closest points of different classes should be as maximum as possible.
![image](https://github.com/gap10/Federated-Learning/assets/61880360/14458c19-7649-4298-a77b-f38ceb0ea10f)
For the SVM model, we can use the already available SVM model in the Scikit learn library. We have used this readily available model directly because it is simpler and the intercept value can also be extracted.

## Multi-Layer Perceptron - 
Multilayer Perceptron falls under the category of feedforward algorithms, because inputs are combined with the initial weights in a weighted sum and subjected to the activation function, just like in the Perceptron. But the difference is that each linear combination is propagated to the next layer.
![image](https://github.com/gap10/Federated-Learning/assets/61880360/5dfe4865-e037-4d00-91c6-a1c3084ddb6b)
In our implementation we have built the multilayer perceptron model from scratch. We used one hidden layer, to keep the model simple. We have used the sigmoid activation function. 

# Comparison of models:
![image](https://github.com/gap10/Federated-Learning/assets/61880360/ecebdc28-f032-492b-8a98-47c144506fc1)
