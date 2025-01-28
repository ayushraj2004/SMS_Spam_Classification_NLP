Problem Statement:
Mobile message is a way of communication among the people, and billions of mobile device users exchange numerous messages. However, such type of communication is insecure due to lack of proper message filtering mechanisms. One cause of such insecurity is spam and The spam detection is a big issue in mobile message communication due to which mobile message communication is insecure. In order to tackle this problem, an accurate and precise method is needed to detect the spam in mobile message communication. Our job is to create a model which predicts whether a given SMS is spam or ham.

Installation
Use the package manager pip to install foobar.

pip install foobar
``

## Usage

```python
import foobar

# returns 'words'
foobar.pluralize('word')

# returns 'geese'
foobar.pluralize('goose')

# returns 'phenomenon'
foobar.singularize('phenomena')
Project Flow:
Problem Statement Data Gathering Data Preprocessing : Here we perform some operation on data A. Tokenization B. Lower Case C. Stopwords D. Lemmatization / Stemming Vectorization (Convert Text data into the Vector): A. Bag Of Words (CountVectorizer) B. TF-IDF Model Building : A. Model Object Initialization B. Train and Test Model Model Evaluation : A. Accuracy Score B. Confusition Matrix C. Classification Report Model Deployment Prediction on Client Data

Please make sure to update tests as appropriate.

Tech Stack Used
Python NLP Machine Learning Algorithms
