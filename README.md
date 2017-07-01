# Thai NLP Resource
Collection of Thai NLP libraries, dictionaries, and corpus.
Always welcome for pull requests.

## Thai NLP Libraries

### Thai Character Cluster

Library | Description | Programming Languages | Features | License | Author & Link
--- | --- | --- | --- | --- | ---
JTCC| Thai Character Cluster | Java | | GPL-3.0 | [Wittawat](https://github.com/wittawatj/jtcc)
TCC | Thai Character Cluster | Python | | Apache 2.0 | [Wannaphong](https://github.com/wannaphongcom/pythainlp/blob/pythainlp1.4/pythainlp/tokenize/tcc.py)


### Thai Soundex
Library | Description | Programming Languages | Features | License | Author & Link
--- | --- | --- | --- | --- | ---
LK82 + Udom83 | Thai Soundex | Python | | | [Korakot](https://gist.github.com/korakot/0b772e09340cac2f493868da035597e8)

### Word Segmentation
<table>
<thead>
<tr>
<th>Library</th>
<th>Description</th>
<th>Programming Languages</th>
<th>Features</th>
<th>License</th>
<th>Author &amp; Link</th>
</tr>
</thead>
<tbody>
<tr>
<td>Swath</td>
<td>SWATH (Smart Word Analysis for THai) is a word segmentation for Thai</td>
<td>C</td>
<td>Longest Matching, Maximal Matching and Part-of-Speech Bigram.</td>
<td>GPL</td>
<td><a href="http://www.cs.cmu.edu/%7Epaisarn/software.html">CMU</a></td>
</tr>
<tr>
<td rowspan="3">Lexto</td>
<td rowspan="3">Lexto: Thai Lexeme Tokenizer</td>
<td>Java</td>
<td></td>
<td>LGPL</td>
<td>
<a href="http://www.sansarn.com/lexto/license-lexto.php">NECTEC</a>
</td>
</tr>
<tr>
<td>Python 2</td>
<td></td>
<td>LGPL</td>
<td><a href="https://github.com/Remixman/PythonLexTo">Python2 Wrapper</a></td>
</tr>
<tr>
<td>Python 3</td>
<td></td>
<td>LGPL</td>
<td><a href="https://github.com/c4n/PythonLexTo">Python3 Wrapper</a></td>
</tr>
<tr>
<td>Wordcut</td>
<td>Thai word breaker for Node.js</td>
<td>JavaScript, Node.JS</td>
<td></td>
<td>LGPL-3.0</td>
<td><a href="https://github.com/veer66/wordcut">veer66, github</a></td>
</tr>
<tr>
<td>wordcutpy</td>
<td>A simple Thai word tokenizer written in 1 Python file</td>
<td>Python 3</td>
<td></td>
<td>LGPL-3.0</td>
<td><a href="https://github.com/veer66/wordcutpy">veer66, github</a></td>
</tr>
<tr>
<td>CutKum</td>
<td>Thai Word-Segmentation with Deep Learning in Tensorflow. RNN.</td>
<td>Python</td>
<td>0.93 F-measure.</td>
<td>MIT</td>
<td><a href="https://github.com/pucktada/cutkum">Pucktada, github</a></td>
</tr>
<tr>
<td>DeepCut</td>
<td>A Thai word tokenization library using Deep Neural Network. CNN.</td>
<td>Python</td>
<td>0.988 F-measure.</td>
<td>MIT</td>
<td><a href="https://github.com/rkcosmos/deepcut">rkcosmos, github</a></td>
</tr>
<tr>
<td>SynThai</td>
<td>Thai Word Segmentation and Part-of-Speech Tagging with Deep Learning. RNN. LSTM.</td>
<td>Python</td>
<td>0.992 F-measure.</td>
<td>MIT</td>
<td><a href="https://github.com/KenjiroAI/SynThai">KenjiroAI, github</a></td>
</tr>
</tbody>
</table>

### Part of Speech Tagging (POS Tagging)
Library | Description | Programming Languages | Features | License | Author & Link
--- | --- | --- | --- | --- | ---
Jitar+NAiST | A simple Trigram HMM part-of-speech tagger | Java |  |  | [Ver66](https://veer66.wordpress.com/2012/03/20/part-of-speech-tagger-%E0%B8%AA%E0%B8%B3%E0%B8%AB%E0%B8%A3%E0%B8%B1%E0%B8%9A%E0%B8%A0%E0%B8%B2%E0%B8%A9%E0%B8%B2%E0%B9%84%E0%B8%97%E0%B8%A2/), [Jitar](https://github.com/danieldk/jitar) + [NAiST, 1](http://naist.cpe.ku.ac.th/pkg/jitar_model_large.zip) + [NAiST, 2](http://naist.cpe.ku.ac.th/pkg/jitar-20100224.zip)
SynThai| Thai Word Segmentation and Part-of-Speech Tagging with Deep Learning. RNN. LSTM. | Python | 0.9163 F-measure. RNN. LSTM | MIT | [KenjiroAI, github](https://github.com/KenjiroAI/SynThai)


### Name Entity Recognition

Library | Description | Programming Languages | Features | License | Author & Link
--- | --- | --- | --- | --- | ---
Thai-NEST | Thai Named Entity tagging Specification and Tools |  |  | GPL | [KINDML, SIIT](http://saki.siit.tu.ac.th/kindml/thainest/)  


### Syntactic Parsing & Tools

Library | Description | Programming Languages | Features | License | Author & Link
--- | --- | --- | --- | --- | ---
Chart-parser | Extract Syntactic Structure from POS Tagged Sentence. | C |  | All rights reserved | Thanaruk T. (thanaruk@siit.tu.ac.th)
Grammar Processing | Labelled Buckets -> Context Free Grammer (CFG) | Python | Transform and compute probability | |  [Thodsaporn C.](https://github.com/tchayintr/nlp-python/tree/master/grammar_processing)  


## Dictionaries / Translation Pairs
Library | Description | Size | Features | License | Link
--- | --- | --- | --- | --- | ---
Transliteration Corpus |  | 31K pairs | Thai-Eng Translation Pair | CC BY-NC-SA 3.0 TH | [NECTEC](https://www.nectec.or.th/corpus/index.php?league=pm)
Lexitron | Opensource Thai-English Dictionary | | TH->EN, EN->TH | LGPL | [NECTEC](http://www.sansarn.com/lexto/license-lexitron.php)

## Downloadable Text Corpus

Library | Description | Size | Features | License | Link
--- | --- | --- | --- | --- | ---
ORCHID | | 30K sent. | Word Seg., POS Tagged. | CC BY-NC-SA 3.0 TH | [NECTEC](https://www.nectec.or.th/corpus/index.php?league=pm)
InterBEST 2009/2010 | | 5M words | Word Seg. | CC BY-NC-SA 3.0 TH | [NECTEC](https://www.nectec.or.th/corpus/index.php?league=pm)
Thai Wikipedia | Formal Articles | 1.49GB (~213.1 MB compressed) | XML | GFDL | [WIKIPEDIA](https://dumps.wikimedia.org/thwiki/latest/thwiki-latest-pages-articles.xml.bz2)
TNC Top-5000 Words | Word frequency | 5,000 words | Frequency of Thai words in various genres, EXCEL |  All rights reserved  | [CHULA](http://www.arts.chula.ac.th/~ling/TNC/category.php?id=58&)
Click Bait Sentences | Thai Click Bait Sentence | 330 sent. (90.7KB) | | MIT | [Wannaphongcom](https://github.com/wannaphongcom/lexicon-thai/blob/master/clickbait/1.txt)
Thai Sentimental Word List | Thai Sentimental Words List | 52KB | Seperated Words as Adj, V | MIT | [Wannaphongcom](https://github.com/wannaphongcom/lexicon-thai/tree/master/sentiment)
Prime Minister 29 | Prime Minister 29's Speech Sentences | 338KB | Word segged, Name Entity Tagged | MIT | [Wannaphongcom](https://github.com/wannaphongcom/lexicon-thai/tree/master/thai-corpus/Prime%20Minister%2029)


## Web Query Text Corpus
Library | Description | Size | Features | License | Link
--- | --- | --- | --- | --- | ---
Thai National Corpus 2 | | 32M words. | Query text by genre, domain |  All rights reserved  | [CHULA](http://www.arts.chula.ac.th/~ling/TNCII/)
Thai Medical Document | | 3,594 docs | Document and dynamic keyword map |  All rights reserved  | [KINDML, SIIT](http://md.knowdd.com/)  

## Pre-trained Word Vectors
Pre-trained Model | Description | Size | Dimensions | License | Link
--- | --- | --- | --- | --- | ---
fastText | Skip-Gram model trained on Wikipedia using fastText | | 300 | CC BY-SA 3.0 | [Facebook](https://github.com/facebookresearch/fastText/blob/master/pretrained-vectors.md) + [Bin & Text](https://s3-us-west-1.amazonaws.com/fasttext-vectors/wiki.th.zip) + [Text Only](https://s3-us-west-1.amazonaws.com/fasttext-vectors/wiki.th.vec)

# Acknowledgements
* Arthit (https://www.facebook.com/arthit) - For suggestions on license words.
* C4N (https://github.com/kobkrit/nlp_thai_resources/commits/master/README.md?author=c4n)
* Ver66 (https://github.com/kobkrit/nlp_thai_resources/commits/master/README.md?author=veer66)
* Bi89 (https://github.com/kobkrit/nlp_thai_resources/commits/master/README.md?author=bi89)
