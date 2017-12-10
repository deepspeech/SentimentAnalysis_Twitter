Goal:
Determine whether a piece of writing is positive, negative or neutral. 
Also known as opinion mining, deriving the opinion or attitude of a speaker.

Marketing:
This Twitter tool will be used by a company to develop their strategies, to understand customers’ feelings towards products or brand, hand see how people respond to their campaigns or product launches. Responses provide insight as to why a product will be purchased or not purchased. 

What you need to install:

Tweepy: tweepy is the python client for the official Twitter API.
Install it using following pip command:
pip install tweepy

TextBlob: textblob is the python library for processing textual data.
Install it using following pip command:
pip install textblob

Also, we need to install some NLTK corpora using following command:

python -m textblob.download_corpora
(Corpora is nothing but a large and structured set of texts.)

Additional actions - Authentication:
Fetch tweets through Twitter API, one needs to register an App through their twitter account. Follow these steps:
Login (https://apps.twitter.com/) and‘Create New App’
Fill the application details. You can leave the callback url field empty.
Once the app is created, you will be redirected to the app page.
Open the ‘Keys and Access Tokens’ tab.
Copy ‘Consumer Key’, ‘Consumer Secret’, ‘Access token’ and ‘Access Token Secret’.

Sample output:

Positive tweets percentage: 30 %
Negative tweets percentage: 20 %

(The rest is neutral)

References:

http://www.ijcaonline.org/research/volume125/number3/dandrea-2015-ijca-905866.pdf
https://textblob.readthedocs.io/en/dev/quickstart.html#sentiment-analysis
textblob.readthedocs.io/en/dev/_modules/textblob/en/sentiments.html
