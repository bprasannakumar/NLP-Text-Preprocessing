# Text-Preprocessing
Text preprocessing is the initial step of any NLP related program. After text is preprocessed, then the output can be fed into the next NLP pipeline for further semantic analysis.
This repo contains files related to text preprocessing such as tokenization, stemming and lemmatization, and removing stop words and punctuations.

# Tokenization:
The process of splitting an input document into meaningful chunks is called Tokenization and that chunk is called as a token. We can think of a token as a useful unit for further semantic processing. It can be a word, a sentence, a paragraph, or anything else. Let’s look at a few examples.

There various popular libraries available to do it like NLTK and Spacy.  Let’s use NLTK and look at a few examples.

WhitespaceTokenizer: Uses white space to split a document
TreebankWordTokenizer: Uses language semantics to split a document
WordPunctTokenizer: Uses punctuations to split a document
RegexpTokenizer: Uses custom regular expression to split a document

# Stemming:
Stemming is the process of reducing inflected or derived words to their base form or root form, called as stem, by chopping off or replacing the suffixes of the words. The resulting stem may not be identical to the morphological root of the word.

# Lemmatization:
Lemmatization is the process of reducing inflected or derived words to their base form or root form, which is similar to dictionary form (called as lemma), using morphological analysis. The lemma is usually identical to the morphological root of the word, which is used in dictionary.

If we apply stemming/lemmatization on a document corpus, it will convert many inflected/derived form of a word into its root word and all those derived words will be treated as a single word when we construct the vocabulary from the given corpus. Hence, it will considerably decrease the size of the vocabulary.

# Removing stop words, punctuations, and special characters
Since in some cases stop words, punctuations, special characters do not add any additional meaning to the text corpus, we should think of removing those. If we remove those, this will help our text preprocessing and will help reduce vocabulary size. 
