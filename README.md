# MACHINE-LEARNING-MODEL-IMPLEMENTATION

COMPANY: CODTECH IT SOLUTIONS

NAME : SANDHYA M

INTERN ID : CT04DG1363

DOMAIN: PYTHON PROGRAMMING

DURATION : 4 WEEKS

MENTOR : NEELA SANTHOSH

  Our inboxes are overflowing with messages in today's digital world, some of which are real and many of which are spam. Spam messages are among the most frequent problems users encounter. These unsolicited, frequently promotional, and occasionally even dangerous messages not only clog inboxes but also present security risks. I decided to use Python, Scikit-learn, and natural language processing (NLP) techniques to create a spam detection system as part of my investigation into practical machine learning applications. I gained practical experience with text classification through this project, which also improved my comprehension of the training and application of machine learning models.
  Building a predictive model that can determine whether a given message is spam or ham (not spam) was the main objective of this project. I used a publicly accessible SMS spam dataset for this. It is made up of thousands of text messages that have been classified as "ham" or "spam." With two columns—the label and the message content—the data was clear and organised.

  Important libraries like Pandas for data handling, Scikit-learn for machine learning, and CountVectorizer for text conversion into a machine-readable format were imported first. To ensure readability and simple debugging, I developed in a Jupyter Notebook within Visual Studio Code.
  I performed fundamental data cleaning operations after loading the dataset, including deleting null values and turning all message data into strings. This was required because raw text cannot be processed by machine learning algorithms; they can only process categorical or numerical data. As a common preprocessing step for classification tasks, I then converted the labels "spam" and "ham" into binary values, 1 and 0 respectively.

  The vectorization step followed. I converted text messages into numerical vectors using Scikit-learn's CountVectorizer. By transforming text into a matrix of token counts, this technique helps the model comprehend how frequently words appear in each message. The model is then trained using this numerical representation of the text data.
  I decided to use the Multinomial Naive Bayes algorithm for the classification model, which is a well-liked option for spam filtering tasks. It is easy to use, effective, and excels at classifying texts. In order to make sure the model learns from most of the data, I divided the dataset into training and testing sets using an 80/20 split. To assess the model's performance, I tested it on unseen messages.

  After training the model, I used the test set to test it and assessed its performance using a classification report and accuracy. With an astounding 97% accuracy rate, the model was able to correctly classify the majority of the messages. It was especially effective at detecting spam messages while reducing false positives, or regular messages that were mistakenly classified as spam.
  I also tested the model on a personalised message such as "You won 1 crore! — and the model accurately identified it as spam. Click this link now to claim. This step demonstrated how well the model generalises to messages that are not part of the training data.

  Through this project, I was able to better understand the entire cycle of a machine learning problem, including data preprocessing, model training, evaluation, and deployment-like testing. It also helped me understand how crucial feature extraction, data quality, and algorithm selection are.
  Overall, creating this spam classifier improved my knowledge of Python and machine learning while also providing me with a tangible illustration of the practical uses of AI. It's a brief but impactful illustration of how machine learning can contribute to safer and less cluttered digital communication.

OUTPUT: ![Image](https://github.com/user-attachments/assets/32ac9b3a-2cbe-4fad-bda8-bbb69154e20d)
