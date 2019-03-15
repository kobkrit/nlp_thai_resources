# Thai Natural Language Processing (Thai NLP) Resource
Collection of Thai Natural Language Processing (NLP) software libraries, dictionaries, and corpus.
Always welcome for pull requests.

## Thai NLP Libraries/Services

### Thai Character Cluster

Library | Description | Programming Languages | Features | License | Author & Link
--- | --- | --- | --- | --- | ---
JTCC| Thai Character Cluster | Java | | GPL-3.0 | [Wittawat](https://github.com/wittawatj/jtcc)
TCC | Thai Character Cluster | Python | | Apache 2.0 | [Wannaphong](https://github.com/wannaphongcom/pythainlp/blob/pythainlp1.4/pythainlp/tokenize/tcc.py)

### Thai Sentiment Analysis
Library | Description | Programming Languages | Features | License | Author & Link
--- | --- | --- | --- | --- | ---
sentiment_analysis_thai | | | || [JagerV3](https://github.com/JagerV3/sentiment_analysis_thai)

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
<td>93% F-measure.</td>
<td>MIT</td>
<td><a href="https://github.com/pucktada/cutkum">Pucktada, github</a></td>
</tr>
 <tr>
<td>Thai Language Toolkit (tltk)</td>
<td> Based on a paper by Wirote Aroonmanakun in 2002. Word segmentation is based on a maximum collocation approach. Syllable segmentation is based on 3grams statistics. (Dataset is included)</td>
<td>Python</td>
<td>97.86% F-measure. (It was tested on a different testset; it is not fair to compare it with other models.)</td>
<td>GPLv3</td>
<td><a href="https://pypi.python.org/pypi/tltk/"> awirote, the Python Package Index</a></td>
 </tr>
<tr>
<td>DeepCut</td>
<td>A Thai word tokenization library using Deep Neural Network. CNN.</td>
<td>Python</td>
<td>98.8% F-measure.</td>
<td>MIT</td>
<td><a href="https://github.com/rkcosmos/deepcut">rkcosmos, github</a></td>
</tr>
<tr>
<td>SynThai</td>
<td>Thai Word Segmentation and Part-of-Speech Tagging with Deep Learning. RNN. LSTM.</td>
<td>Python</td>
<td>99.2% F-measure</td>
<td>MIT</td>
<td><a href="https://github.com/KenjiroAI/SynThai">KenjiroAI, github</a></td>
</tr>
<tr>
<td>CutThai</td>
<td>Thai word segmentation written in coffee-script Edit</td>
<td>Coffee-script</td>
<td></td>
<td>MIT</td>
 <td><a href="https://github.com/pureexe/cutthai">Pureexe/cutthai Github</a></td>
</tr>
<tr>
 <td>Multi-Candidate-Word-Segmentation</td>
 <td>Multi Candidate Word Segmentation for Thai language</td>
 <td>Python, RNN, LSTM</td>
 <td>97.0% F-measure (Word Level), 98.95% F-measure (Boundary Level)</td>
 <td>MIT</td>
 <td><a href="https://goo.gl/hdhbiR">Paper</a>, <a href="https://github.com/earthy123/Multi-Candidate-Word-Segmentation">earthy123/Multi-Candidate-Word-Segmentation</a><br></td>
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
Named Entity Tagging (Thai NEST) | Thai Named Entity tagging Specification and Tools | | | GPL | [KINDML, SIIT](http://saki.siit.tu.ac.th/kindml/thainest/), [AIAT](http://aiat.in.th/resources/index.php/tools/48-1-0-named-entity-tagging-program-version-1-0)
ThaiNER | Thai Named Entity Recognition for PyThaiNLP | Python | | Apache 2.0 (code) & CC BY 3.0 (Dataset) | [ThaiNER](https://github.com/wannaphongcom/thai-ner)

### News Structure Tagging

Library | Description | Programming Languages | Features | License | Author & Link
--- | --- | --- | --- | --- | ---
News Structure Tagging Program | Thai News Structure Tagging Program | | Metadata tagging, Structure tagging, Automatic News Title Generation | GPL | [AIAT](http://aiat.in.th/resources/index.php/tools/47-1-0-news-structure-tagging-program-version-1-0)

### Syntactic Parsing & Tools

Library | Description | Programming Languages | Features | License | Author & Link
--- | --- | --- | --- | --- | ---
Chart-parser | Extract Syntactic Structure from POS Tagged Sentence. | C |  | All rights reserved | Thanaruk T. (thanaruk@siit.tu.ac.th)
Grammar Processing | Labelled Brackets -> Context Free Grammars (CFGs) | Python | Transform and compute probability | |  [Thodsaporn C.](https://github.com/tchayintr/nlp-python/tree/master/grammar_processing)  

### Thai Word Embedding
Library | Description | Programming Languages | Features | License | Author & Link
--- | --- | --- | --- | --- | ---
kobkrit-word-embedding | Tensorflow implementation of Thai word embedding | Python | Source code, Example, Word distance graph | LGPL | [Kobkrit V.](https://github.com/kobkrit/tf-nlp-thai-word-embedding)

### Thai Question Answering (Machine Comprehension)
Service | Description | License | Author & Link
--- | --- | --- | --- 
Thai Machine Comprehension (ThaiMC) | Bidirectional Attention Flow | Copyright (As the service) | [iApp-AI](http://ai.iapp.co.th)

### Thai Emojification
Service | Description | License | Author & Link
--- | --- | --- | --- 
Thai Emotification | LSTM | GNU General Public License v3.0 | [Demo at iApp-AI](http://ai.iapp.co.th/emojify) and [Source, Github](https://github.com/kobkrit/thai-emojification)

## Dictionaries / Translation Pairs
Library | Description | Size | Features | License | Link
--- | --- | --- | --- | --- | ---
Transliteration Corpus |  | 31K pairs | Thai-Eng Translation Pair | CC BY-NC-SA 3.0 TH | [NECTEC](https://www.nectec.or.th/corpus/index.php?league=pm)
LEXiTRON | Thai<->English Dictionary | | TH->EN, EN->TH | LEXiTRON License | [NECTEC](http://www.sansarn.com/lexto/license-lexitron.php)
Yaitron | LEXiTRON in machine readable format (XML) | | TH->EN, EN->TH | LEXiTRON License | Veer66 [Schema](http://th.lug.wikia.com/wiki/YAiTRON_%28English-Thai_dictionary%29), [Data & Conversion Code](https://github.com/veer66/Yaitron)


## Downloadable Text Corpus

Library | Description | Size | Features | License | Link
--- | --- | --- | --- | --- | ---
ORCHID | | 30K sent. | Word Seg., POS Tagged. | CC BY-NC-SA 3.0 TH | [NECTEC](https://www.nectec.or.th/corpus/index.php?league=pm)
THAI-NEST | Thai-NEST: Thai Named Entity tagging Specification and Tools | 45K+ Name Entity Token | Name Entity Tagged | GNU Lesser General Public 2.1 | [KINDML](https://saki.siit.tu.ac.th/kindml/thainest/index.php/download)
InterBEST 2009/2010 | | 5M words | Word Seg. | CC BY-NC-SA 3.0 TH | [NECTEC](https://www.nectec.or.th/corpus/index.php?league=pm)
Thai Wikipedia | Formal Articles | 1.49GB (~213.1 MB compressed) | XML | GFDL | [WIKIPEDIA](https://dumps.wikimedia.org/thwiki/latest/thwiki-latest-pages-articles.xml.bz2)
TNC Top-5000 Words | Word frequency | 5,000 words | Frequency of Thai words in various genres, EXCEL |  All rights reserved  | [CHULA](http://www.arts.chula.ac.th/~ling/TNC/category.php?id=58&)
Click Bait Sentences | Thai Click Bait Sentence | 330 sent. (90.7KB) | | MIT | [Wannaphongcom](https://github.com/wannaphongcom/lexicon-thai/blob/master/clickbait/1.txt)
Thai Sentimental Word List | Thai Sentimental Words List | 52KB | Seperated Words as Adj, V | MIT | [Wannaphongcom](https://github.com/wannaphongcom/lexicon-thai/tree/master/sentiment)
Prime Minister 29 | Prime Minister 29's Speech Sentences | 338KB | Word segged, Name Entity Tagged | MIT | [Wannaphongcom](https://github.com/wannaphongcom/lexicon-thai/tree/master/thai-corpus/Prime%20Minister%2029)
Thai named entity corpora | named entity corpora by Wirote Aroonmanakun's students | 266KB-1.5MB | syllable seg., word seg., Named Entity tagged | GPLv3(not sure, but tltk is using this license) | [นัชชา ถิระสาโรช Data](http://pioneer.chula.ac.th/~awirote/Data-Nutcha.zip)<br /> [ศศิวิมล กาลันสีมา Data](http://pioneer.chula.ac.th/~awirote/Data-Sasiwimon.zip)<br /> [ณัฐดาพร เลิศชีวะ Data](http://pioneer.chula.ac.th/~awirote/Data-Nattadaporn.zip) 
Thai WordNet | [THE CONSTRUCTION OF THAI WORDNET OF 1ST ORDER ENTITY COMMON BASE CONCEPTS USING A BI-DIRECTIONAL TRANSLATION METHOD AND WITH DICTIONARIES OF DIFFERENT COMPILATIONAL APPROACHES(ธนนท์ หลีน้อย)](http://www.arts.chula.ac.th/~ling/thesis/2551MA-DHANON.pdf) <br /> <br /> [THE CONSTRUCTION OF THAI WORDNET OF 2ND ORDER ENTITY COMMON BASE CONCEPTS USING A BI-DIRECTIONAL TRANSLATION METHOD : A STUDY OF THE DIVERSITY OF MEANINGS AFFECTING TRANSLATIONAL ACCURACY (ปริศนา อัครพุทธิพร)](http://cuir.car.chula.ac.th/handle/123456789/14274)||WordNet|N/A| [ธนนท์ หลีน้อย 2008](http://pioneer.chula.ac.th/~awirote/Data-Dhannon.rar)<br />[ปริศนา อัครพุทธิพร Data 2008](http://pioneer.chula.ac.th/~awirote/Data-Prisana.rar) 
Toxicity in Thai Tweet Corpus |Tokyo Metropolitan University Natural Language Processing Group | | Each tweet is labeled as toxic or non-toxic |CC BY-NC 4.0 | [tmu-nlp](https://github.com/tmu-nlp/ThaiToxicityTweetCorpus)

## Web Query Text Corpus
Library | Description | Size | Features | License | Link
--- | --- | --- | --- | --- | ---
Thai National Corpus 2 | | 32M words | Query text by genre, domain |  All rights reserved  | [CHULA](http://www.arts.chula.ac.th/~ling/TNCII/)
Thai Medical Document | | 3,594 docs | Document and dynamic keyword map |  All rights reserved  | [KINDML, SIIT](http://md.knowdd.com/) 
Southeast Asian Languages Library | Thai News, Web Text, Pop Music, Literature, Toponyms | 20M chars | Phase around a search text | | [SEALang](http://sealang.net/thai/corpus.htm)
HSE Thai Corpus | Modern texts written in Thai language (mostly news websites) | 50M tokens | Query by word form, lexeme, translation, grammatical attributes, lexical attributees | |  [HSE School of Linguistics](http://web-corpora.net/ThaiCorpus/search/)

## Parallel Corpus 
Library | Description | Size | Features | License | Link
--- | --- | --- | --- | --- | ---
TALPCo | TUFS Asian Language Parallel Corpus  | 1327 sent | open parallel corpus consisting of Japanese sentences and their translations into Burmese (Myanmar; the official language of the Republic of the Union of Myanmar), Malay (the national language of Malaysia, Singapore and Brunei), Indonesian, Thai, Vietnamese and English | CC BY 4.0 | [TALPCo](https://github.com/matbahasa/TALPCo)

## Pre-trained Word Vectors 
Pre-trained Model | Description | Size | Dimensions | License | Link
--- | --- | --- | --- | --- | ---
fastText | Skip-Gram model trained on Wikipedia using fastText | | 300 | CC BY-SA 3.0 | [Facebook](https://github.com/facebookresearch/fastText/blob/master/pretrained-vectors.md) + [Bin & Text](https://s3-us-west-1.amazonaws.com/fasttext-vectors/wiki.th.zip) + [Text Only](https://s3-us-west-1.amazonaws.com/fasttext-vectors/wiki.th.vec)
thai2fit | ULMFit on Wikipedia. Perplexity of 46.80959 with 60,002 embeddings. | 70MB | 300 | MIT | [thai2vec](https://github.com/cstorm125/thai2fit) / [pyThaiNLP](https://github.com/PyThaiNLP/)

## [Thai Text Classification Benchmarks](https://www.github.com/pythainlp/classification-benchmarks)

### [wongnai-corpus](https://github.com/wongnai/wongnai-corpus)

| model     | micro_f1_public | micro_f1_private | 
|-----------|-----------------|------------------|
| [**ULMFit**](https://github.com/cstorm125/thai2fit) | **0.59313**          | **0.60322**           |
| fastText | 0.5145          | 0.5109           |
| LinearSVC | 0.5022          | 0.4976           |
| [Kaggle Score](https://www.kaggle.com/c/wongnai-challenge-review-rating-prediction/leaderboard) | 0.59139      | 0.58139          |
| [BERT](https://github.com/ThAIKeras/bert) | 0.56612 | 0.57057 |

### [prachathai-67k](https://github.com/PyThaiNLP/prachathai-67k): body_text

| Model     | Macro-accuracy | Macro-F1 |
|-----------|----------------|----------|
| fastText  | 0.9302         | 0.5529   |
| LinearSVC | 0.513277       | 0.552801 |
| **ULMFit**    | **0.948737**       | **0.744875**	 |

## [wisesight-sentiment](https://github.com/PyThaiNLP/wisesight-sentiment)

| Model               | Public Accuracy | Private Accuracy |
|---------------------|-----------------|------------------|
| Logistic Regression | 0.72781         | 0.7499           |
| FastText            | 0.63144         | 0.6131           |
| ULMFit              | 0.71259         | 0.74194          |
| ULMFit Semi-supervised    | 0.73119     | 0.75859      |
| **[ULMFit Semi-supervised Repeated One Time](https://github.com/PyThaiNLP/wisesight-sentiment/blob/master/competition.ipynb)**    | **0.73372**     | **0.75968**      |

## [truevoice-intent](https://github.com/PyThaiNLP/truevoice-intent): destination

| model     | accuracy | micro-F1 |
|-----------|----------|----------|
| fastText  | 0.384116 | 0.384116 |
| LinearSVC | 0.807876 | 0.327565 |
| **ULMFit**    | **0.834981**  | **0.834981** |

## Not found? Try to look at another Thai NLP Awesome List/Resource (Like this one)
https://resources.aiat.or.th/

# Acknowledgements
* [Arthit](https://www.facebook.com/arthit) - For suggestions on license words.
* [C4N](https://github.com/kobkrit/nlp_thai_resources/commits/master/README.md?author=c4n)
* [Veer66](https://github.com/kobkrit/nlp_thai_resources/commits/master/README.md?author=veer66)
* [Bi89](https://github.com/kobkrit/nlp_thai_resources/commits/master/README.md?author=bi89)
* [Tchayintr](https://github.com/kobkrit/nlp_thai_resources/commits/master/README.md?author=tchayintr)
* [PureEXE](https://github.com/kobkrit/nlp_thai_resources/commits/master/README.md?author=pureexe)
* [Cstorm125](https://github.com/kobkrit/nlp_thai_resources/commits/master/README.md?author=cstorm125)
* [Wannaphongcom](https://github.com/kobkrit/nlp_thai_resources/commits/master/README.md?author=wannaphongcom)
* [Ekapolc](https://github.com/kobkrit/nlp_thai_resources/commits/master/README.md?author=ekapolc)
