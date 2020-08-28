# Credit-Classification-Using-Deep-Learning
Predicting Loan Repayment Possibility of the Borrowers of P2P Online Lending Business Using Deep Learning Architecture

Online lending platforms, popularly known as peer to peer (P2P), attract large number of users and generate huge loan transaction data. The availability of these data helps to make prediction of repayment by the borrowers, but there are limitations in extracting features because of the complex nature of information. Artificial Intelligence (AI) can automatically extract useful features from large P2P lending data. This project proposes a deep neural networks (NN) for default prediction in Lending Club data to automatically extract features and improve the performance. We capture the complex features of lending data with this architecture and reuse loan information to predict the repayment of the borrower. Experimental results show that the proposed method automatically extracts useful features from Lending Club data and is effective in default prediction with 89% accuracy. This model was compared with some other machine learning methods, the proposed method has achieved the highest performance.

Data Source: https://www.kaggle.com/wordsforthewise/lending-club

Python Packages Used: TensorFlow, Keras, Pandas, Matplotlib, Seaborn, sci-kit-learn

Model / Architecture:
● Data preprocessing through dealing with missing data, converting to categorical data, exploratory data analysis.
● Model building using TensorFlow and Keras layers.
● Compiling the model, fitting / training with training data and predict loan classification.
● Evaluating model performance using the classification reports, confusion matrices and accuracy scores.
● Comparing the deep learning result with other machine learning classifiers such as the Logistic Regression, Decision Tree, Gaussian NB classifier as well as with the ensemble of these classifiers.
