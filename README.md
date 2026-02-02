# Ancient Greek-English word alignment
Data and code for Ancient Greek-English word alignment, as discussed in Keersmaekers forthcoming, *Lexically-oriented word alignment for Ancient Greek: a learning-to-rank approach*.

The experiments described in the paper can be reproduced from the Jupyter notebook provided here. For this you need to have glaux-nlp installed (https://github.com/alekkeersmaekers/glaux-nlp), as well as WordNet from the nltk (*import nltk; nltk.download('wordnet')*) and the spaCy en_core_web_trf model (*python -m spacy download en_core_web_trf*).

There is no command line version for WordAligner yet: I will provide this in the future and make it possible to align your own texts with WordAligner.

## How to cite

Please refer to the following publication if you make use of the code and/or datasets:

> Keersmaekers, Alek. Accepted. Lexically-oriented word alignment for Ancient Greek: a learning-to-rank approach. In *Daidalos: KI in der Klassischen Philologie - Historical Languages and AI*. Propylaeum.

You can freely use all the data, but please also refer to the original datasets if you make use of one of the external datasets (Ugarit, New Testament) that I have modified. You can find their references and the description of how I have modified them in the paper cited above.
