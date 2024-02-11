Intel-Hackaton RVCE 
Team Name: Yash Saraogi

Team Members:
Yash Saraogi: yashsaraogi.cs23@rvce.edu.in
Charan RK: charanrk2003@gmail.com
Nishasri R: nishakumbar6104@gmail.com
Vatsal Mehta: vatsalmehta163@gmail.com

Problem Statement:
Stock Market Prediction: Leveraging AI Analytics Toolkit for predicting stocks using company data (microsoft) in intel oneAPI AI analytics toolkit Hackathon Trained models

Intel One API AI Analytic Toolkit:

We have utilised the toolkits provided by Intel in this project, providing us with amazing performances and effiiciency in our project. We have used few toolkits from the given to name a few: Modin, ITEX, Skikit learn.

Dataset: msft-daily-max

Tech Stack:
	1. Intel® Extension for Scikit-learn*
	2. Modin: Drop-in replacement for Pandas
	3. Intel® Optimization for TensorFlow     

Scikit-learn for Traditional Machine Learning:
Scikit-learn is a powerful library for traditional machine learning algorithms. We have used multiple regression models like Support Vector Machine (SVM), Decision Tree, Random Forest and Linear Regression. They were all imported from the extensive library of scikit learn. 

Modin for Pandas Parallelization:
Modin is designed to accelerate data manipulation tasks using the Pandas library. It can efficiently parallelize Pandas operations, which is beneficial for handling large datasets in stock market analysis. Utilize Modin to speed up data preprocessing and exploration tasks, enabling quicker insights into your financial data.

Intel oneAPI for Heterogeneous Parallel Computing:
Complement scikit-learn and Modin with Intel oneAPI to harness the power of heterogeneous parallel computing. Use oneAPI's Data Parallel C++ to parallelize your machine learning algorithms, optimizing their performance across different hardware architectures. This is particularly useful for speeding up computations on CPUs, GPUs, and FPGAs.

Combined Approach for Enhanced Performance:
Consider combining the strengths of scikit-learn, Modin, and Intel oneAPI for a holistic approach to stock market prediction. Utilize scikit-learn for traditional machine learning algorithms, Modin for efficient data manipulation, and oneAPI for parallelization across diverse hardware. This integrated approach can lead to improved performance and faster model development and evaluation.

The model that gave us the best accuracy on the dataset was LSTM, it ia a long short-term memory networks that use (ANN) artificial neural networks in the field of artificial intelligence (AI) and deep learning. In contrast to normal feed-forward neural networks, also known as recurrent neural networks, these networks feature feedback connections.

Future Scopes

The future scope of stock market prediction using tools like scikit-learn, Modin, Intel oneAPI, and cloud platforms is promising and likely to witness advancements on multiple fronts. Firstly, the integration of artificial intelligence (AI) and machine learning (ML) techniques is expected to play a pivotal role. As technology continues to evolve, more sophisticated algorithms, including deep learning models such as recurrent neural networks (RNNs) and transformers, may become prevalent in stock market analysis. This shift towards more complex models has the potential to capture intricate patterns within financial data, providing more accurate predictions and aiding in more informed investment decisions.

Secondly, the incorporation of real-time data and advanced data sources could significantly enhance the predictive capabilities of stock market models. With the rise of big data technologies and improved data accessibility, financial analysts may integrate a diverse range of data, including social media sentiments, news articles, and global economic indicators, into their predictive models. This holistic approach could offer a more comprehensive understanding of market dynamics and contribute to more robust predictions. Moreover, the ongoing development of quantum computing technologies might introduce new paradigms for processing vast amounts of financial data, potentially revolutionizing the efficiency and speed of stock market prediction models. Overall, the future scope encompasses not only the refinement of existing methodologies but also the exploration of cutting-edge technologies to push the boundaries of stock market forecasting.
