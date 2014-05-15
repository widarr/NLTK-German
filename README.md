NLTK German
------------------

This is a fork of the NLTK-Contribution package with focus on the german language

NLTK <http://nltk.org/> related code snippets and contributions.

ClassifierBasedGermanTagger
---------------------------

The ClassifierBasedGermanTagger is a part-of-speech tagger extending the nltk's ClassifierBasedTagger with a modified feature_detector. It is designed for tagging German text and achieves an accuracy of 96.09% after being trained on 90% of the German TIGER corpus. 

NegraCorpusReader
-----------------

The NegraCorpusReader is a corpus reader for Negra format corpora like the TIGER corpus. The class extends the ConllCorpusReader from the NLTK.
