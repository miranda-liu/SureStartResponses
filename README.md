# SureStartResponses

# RESPONSES!
2/8/21: I hope to learn how to actually implement machine learning algorithms and things like neural networks, instead of just knowing a brief concept of what they are. Also very excited to learn how to apply machine learning to different things!

2/9/21: 

   1. What is the difference between supervised and unsupervised learning?

Supervised machine learning is when the program is trained on a predefined set of training examples, allowing it to reach an accurate conclusion with any new data given. Unsupervised machine learning is when the program needs to find patterns and relationships on a given dataset.

   2. Describe why the following statement is FALSE: Scikit-Learn has the power to visualize data without a Graphviz, Pandas, or other data analysis libraries.
   
Scikit-Learn doesn't have the power to visualize data without the data analysis libraries because it is responsible for data modeling, but not the loading, handling, manipulating, and visualising of data which is what the other libraries are responsible for.


2/10/21: 
   1. What are “Tensors” and what are they used for in Machine Learning?

Tensors are the mathematical representation of a physical thing that can be described through magnitude and many directions. In machine learning, tensors can represent multi-dimensional data.

   2. What did you notice about the computations that you ran in the TensorFlow programs (i.e. interactive models) in the tutorial?

The computations in the TensorFlow programs involved mainly vectors/tensors represented as arrays. They noted that TensorFlow has a "lazy evaluation" because if you did result = tf.multiply(x1, x2) it wouldn't actually calculate the result, only defines the model. **When I tried to implement it in TensorFlow 2.0, I think that the newer version is now using "eager execution."?

2/11/21: 
    -Problem: predict potential wildfire locations across the U.S. based on precipitation, air temperatures, land surface temperatures, and heat wave dates
    -Datasets: https://wonder.cdc.gov/controller/datarequest/D104;jsessionid=2E289443248F94E5F580EC2080EB, https://wonder.cdc.gov/nasa-nldas.html, https://wonder.cdc.gov/nasa-lst.html, https://wonder.cdc.gov/nasa-precipitation.html
    -Approach/algorithm: Long Short Term Memory Network (LSTM) because I saw that they can retain info over time, which means that it is able to recall older info to make better predictions.


2/12/21: Action item will be posted to the projects repo

2/13/21-2/14/21: catch-up days

2/15/21: Action item will be posted to the projects repo

2/16/21: 
   1. How do you think Machine Learning or AI concepts were utilized in the design of this game?

The game used the applicants' CVs and the selected company's (I chose Google) as data to train an ML algorithm, which learned from the way I chose to accept or reject people. Apparently I had a tendency to choose more "orange" people, so the algorithm learned to favor them as well. The orange people also tended to be more qualified when I was choosing, so it unintentionally became biased. 

   2. Can you give a real-world example of a biased machine learning model, and share your ideas on how you make this model more fair, inclusive, and equitable? Please reflect on why you selected this specific biased model.

I've read some news articles in the past year about how facial recognition machine learning models are often biased, which leads to harsher punishments for the group it's biased against (POC, certain locations, etc). I think that to make this model more fair, inclusive, and equitable, the people making it should include cautionary warnings about possible discrimination to make the users aware (model cards?), examining the data collected for training for bias, and paying more attention to the groups with the worst accuracy/performance. I chose this specific biased model because the context seems particular relevant when looking at the past year.

2/17/21:

Fully Connected Neural Network
1. Architecture: series of fully connected layers that connect every neuron in one layer to every neuron in the next layer
2. No assumptions made about what the input is
3. Applications: used for deep learning

Convolutional Neural Network
1. Architecture: input image -> convolution layer -> pooling layer -> fully connected layer
2. Each neuron is only connected to a few nearby neurons
3. Assume input is an image?
4. Applications: image classification through identifying features in input images

Description of layers and roles:
1. Convolutional layer -> passes a filter over the image, then scans a few pixels at a time and creates a feature map predicting the class that each feature belongs to
2. Pooling layer -> the downsampling; reduces amount of info in each feature coming from convolution and keeps only the most important info
3. Fully Connected input layer -> flattens the outputs from earlier layers forming a single vector (becomes input later)
4. Fully Connected layer -> takes inputs from feature analysis and applies weights to predict the correct label
5. Fully Connected output layer -> gives you the final probabilities for each label (identifying the image)


2/23/21:
1. Advantages of the Rectified Linear activation function include: avoiding and fixing the problem of the vanishing gradient, and also requires less computational power than tanh and sigmoid because it has simpler mathematical operations.
3. One use case for the ReLU is in the hidden layers of a neural network.


2/25/21:
Changing the loss to regression based functions (both mean squared error and mean absolute error) on the housing prices model from yesterday made them more accurate.
