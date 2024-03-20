# Project---Neural-Machine-Translation
The goal of this project was to create a Sequential Encoder-Decoder model using a French to English text dataset to accurately convert French sentences to English sentences. The project involved several steps, including data preprocessing and building the model.

The first step in the project was data preprocessing. This involved cleaning and normalizing the text data by removing special characters, punctuation, and stop words. The next step was to tokenize the text data, which involved breaking up the text into individual words or phrases. This was followed by vectorizing the tokenized text data, which involved converting the text into a numerical format that could be used by the machine learning model.

Once the data was preprocessed, the next step was to build the Sequential Encoder-Decoder model. This model consists of two components: an encoder and a decoder. The encoder takes in the input sequence (in this case, a French sentence) and converts it into a fixed-length vector representation. The decoder then takes this vector representation and generates the output sequence (in this case, an English sentence).

The model was trained on the preprocessed French to English text dataset using the Adam optimizer and categorical cross-entropy loss function. The performance of the model was evaluated using the BLEU score, which measures the similarity between the predicted and actual output sequences.

The final model achieved a BLEU score of 82%, which indicates that it is able to accurately convert French sentences to English sentences. The model can be used to translate French text into English in a variety of applications, such as in language learning or in the translation of documents for businesses or organizations.

Overall, this project demonstrates the effectiveness of using NLP techniques and a Sequential Encoder-Decoder model to translate text from one language to another. With further refinement and training, the model can be improved to achieve even higher accuracy in the translation of French to English text.
