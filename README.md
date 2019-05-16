# ngram_language_model
Implementation of a collection of Ngram language models on brown corpus. Randomly divide the dataset into three parts: training, developing and test data.

(a) Write a code that computes unsmoothed unigram and bigram models on the training data of your choice. Report the perplexity of your unigram and bigram models on the training data.

(b) Implement add-Lambda smoothing method. With varying lambda values, try to draw a similar curve to P2-(d). You should measure the perplexity on the developing data.

(c) Pick the best lambda value and train again your unigram and bigram models on training data + developing data. Report new perplexity of your unigram and bigram models on the test data.

(d) Generate random sentences based on the unigram and bigram language models from part(c). Report 5 sentences per model by sampling words from each model continuously until meeting the stop symbol </s>.

(e) Choose at least one additional extension to implement. The available options are trigram, Good-Turing smoothing, interpolation method, and creative handling of unknown words. Verify whether some of your extensions could improve your random sentence generation in part (d).
