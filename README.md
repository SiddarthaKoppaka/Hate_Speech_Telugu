# Unmasking Hate: Telugu Language Hate Speech Recognition
##Abstract
In the digital era, the spread of abusive language and hate speech on social media is alarming, especially for low-resource languages like Telugu. Our project, "Unmasking Hate," aims to combat abusive language in Telugu by collecting a comprehensive dataset from Twitter and training Transformer models. Our goal is to contribute towards a safer online environment by leveraging advanced natural language processing techniques.

##Introduction
Hate speech, targeting individuals or groups based on characteristics such as race, religion, or gender, has grown with social media's rise. For Telugu, a language spoken by millions yet underrepresented in research, we've taken a step forward by creating datasets and developing hate speech recognition models to address this issue head-on.

##Related Work
Our work draws inspiration from advancements in hate speech detection in languages like Hindi and Marathi, utilizing CNNs, LSTMs, and Transformer models like BERT and RoBERTa. We extend these methodologies to Telugu, a language with distinct linguistic and cultural nuances.

##Data Collection and Preprocessing
Gathering and Preparing the Tweet Dataset
We collected ~50,000 tweets using snscrape, focusing on keywords related to abusive language in Telugu. Post-collection, we embarked on rigorous data cleaning and manual annotation to ensure the dataset's quality for model training.

###Data Cleaning & Preprocessing
Through regular expressions, we removed mentions, user IDs, emojis, and irrelevant English words, aiming for a balanced dataset of positive and negative labels to train our models effectively.

##Training the Model
Model Description
We explored a variety of models, from RNNs and LSTMs to state-of-the-art Transformers, aiming to identify the most effective architecture for hate speech detection in Telugu.

###Training Approaches
RNN & LSTM: Utilized for their capability to capture sequential patterns and long-term dependencies within text data.
Transformers: Implemented models like mBERT, DistilBERT, Indic-BERT, NLLB, and MuRIL, leveraging their self-attention mechanisms and pre-trained knowledge for better performance in language understanding and hate speech detection.
Evaluation and Metrics
We evaluated the models using F1 score, recall, precision, and accuracy. Our results show significant promise, with most Transformer models achieving over 95% accuracy, and mBERT leading at 98.2%.

##Conclusion
Our research presents a significant step towards detecting hate speech in Telugu. Through the creation of a custom dataset and the application of Transformer models, we demonstrated the effectiveness of these approaches in addressing hate speech, with mBERT showcasing outstanding performance.

##How to Use
(Provide details on how to set up the environment, install dependencies, and run the models, including code snippets.)

bash
Copy code
# Example setup code
git clone <repository-url>
cd <repository-name>
pip install -r requirements.txt

##Contributors
(List of project contributors and their roles)

##Acknowledgments
(Any acknowledgments to data sources, financial support, etc.)

##References
(Complete list of referenced works as cited throughout the document.)

