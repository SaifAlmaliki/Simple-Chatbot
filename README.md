# chatbot by nltk
 We Build a chatbot using deep learning techniques. The chatbot will be trained on the dataset which contains categories (intents), pattern and responses. We use a special recurrent neural network (LSTM) to classify which category the user’s message belongs to and then we will give a random response from the list of responses.
 
There are two basic types of chatbot models based on how they are built; Retrieval based and Generative based models.
 
1. Retrieval based Chatbots

uses predefined input patterns and responses. It then uses some type of heuristic approach to select the appropriate response. It is widely used in the industry to make goal-oriented chatbots where we can customize the tone and flow of the chatbot to drive our customers with the best experience.

2. Generative based Chatbots

Generative models are not based on some predefined responses.
They are based on seq 2 seq neural networks. It is the same idea as machine translation. In machine translation, we translate the source code from one language to another language but here, we are going to transform input into an output. It needs a large amount of data and it is based on Deep Neural networks.


 
# The dataset 
we will be using is ‘intents.json’. This is a JSON file that contains the patterns we need to find and the responses we want to return to the user.

# project files

- Intents.json – The data file which has predefined patterns and responses

- chatbot.ipynb – In this Python file, we wrote a script to build the model and train our chatbot.

- Words.pkl – This is a pickle file in which we store the words Python object that contains a list of our vocabulary.

- Classes.pkl – The classes pickle file contains the list of categories.

- chatbot_model.h5 – This is the trained model that contains information about the model and has weights of the neurons.

- gui.py – This is the Python script in which we implemented GUI for our chatbot. Users can easily interact with the bot.
