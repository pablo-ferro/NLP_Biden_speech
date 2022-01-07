# NLP Biden speech
President Joe Biden Inauguration speech. Sentiments analyzed with NLP
Every quote has been analyzed by two definitions: 
- Polarity (going from +1 to -1)
- Subjectivity (from 0 to 1).
- An extra analysis using Naive Bayes method, that returns 3 values: pos or neg, pos value and neg value.

To use the Naive Bayes analyzer, we need TextBlob and NLTK:
```
from textblob.sentiments import NaiveBayesAnalyzer
import nltk
nltk.download('movie_reviews')
nltk.download('punkt')
```

Also, trying to create some visualizations about the words, a visual analysis simple for users.
