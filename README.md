# Thai NLP Resource
Collection of Thai NLP libraries, dictionaries, and corpus.

## Thai NLP Libraries

### Thai Character Cluster
Library | Description | Support Languages | Features | License | Author & Link
--- | --- | --- | --- | --- | ---
TCC| Thai Character Cluster | C | | | Thanaruk et.al. 


### Word Segmentation

Library | Description | Programming Languages | Features | License | Author & Link
--- | --- | --- | --- | --- | ---
Swath | SWATH (Smart Word Analysis for THai) is a word segmentation for Thai | C | Longest Matching, Maximal Matching and Part-of-Speech Bigram. | GPL | [CMU](http://www.cs.cmu.edu/~paisarn/software.html)
Lexto | Lexto: Thai Lexeme Tokenizer | Java, Python | | LGPL | [NECTEC](http://www.sansarn.com/lexto/license-lexto.php) + [Python2 Wrapper](https://github.com/Remixman/PythonLexTo) + [Python3 Wrapper](https://github.com/c4n/PythonLexTo)
Wordcut | Thai word breaker for Node.js | JavaScript, Node.JS | | LGPL-3.0 | [Veer66, github](https://github.com/veer66/wordcut)
CutKum | Thai Word-Segmentation with Deep Learning in Tensorflow | Python | 0.93 recall, 0.92 precision, 0.93 F-measure. | MIT | [Pucktada, github](https://github.com/pucktada/cutkum)



### Part of Speech Tagging (POS Tagging)
Library | Description | Programming Languages | Features | License | Author & Link
--- | --- | --- | --- | --- | ---
Jitar+NAiST | A simple Trigram HMM part-of-speech tagger | Java |  |  | [Ver66](https://veer66.wordpress.com/2012/03/20/part-of-speech-tagger-%E0%B8%AA%E0%B8%B3%E0%B8%AB%E0%B8%A3%E0%B8%B1%E0%B8%9A%E0%B8%A0%E0%B8%B2%E0%B8%A9%E0%B8%B2%E0%B9%84%E0%B8%97%E0%B8%A2/), [Jitar](https://github.com/danieldk/jitar) + [NAiST, 1](http://naist.cpe.ku.ac.th/pkg/jitar_model_large.zip) + [NAiST, 2](http://naist.cpe.ku.ac.th/pkg/jitar-20100224.zip)

### Name Entity Recognition


### Syntactic Parsing & Tools 

Library | Description | Programming Languages | Features | License | Author & Link
--- | --- | --- | --- | --- | ---
Chart-parser | Extract Syntactic Structure from POS Tagged Sentence. | C |  | Copyright | Thanaruk T. (thanaruk@siit.tu.ac.th)
Grammar Processing | Labelled Buckets -> Context Free Grammer (CFG) | Python | Transform and compute probability | |  [Thodsaporn C.](https://github.com/tchayintr/nlp-python/tree/master/grammar_processing)  


## Dictionaries / Translation Pairs
Library | Description | Size | Features | License | Link
--- | --- | --- | --- | --- | ---
Transliteration Corpus |  | 31K pairs | Thai-Eng Translation Pair | CC BY-NC-SA 3.0 TH | [NECTEC](https://www.nectec.or.th/corpus/index.php?league=pm)
Lexitron | Opensource Thai-English Dictionary | | TH->EN, EN->TH | LGPL | [NECTEC](http://www.sansarn.com/lexto/license-lexitron.php)

## Text Corpus

Library | Description | Size | Features | License | Link
--- | --- | --- | --- | --- | ---
ORCHID | | 30K sent. | Word Seg., POS Tagged. | CC BY-NC-SA 3.0 TH | [NECTEC](https://www.nectec.or.th/corpus/index.php?league=pm)
InterBEST 2009/2010 | | 5M words | Word Seg. | CC BY-NC-SA 3.0 TH | [NECTEC](https://www.nectec.or.th/corpus/index.php?league=pm)
Thai Wikipedia | Formal Articles | 1.49GB (~213.1 MB compressed) | XML | GFDL | [WIKIPEDIA](https://dumps.wikimedia.org/thwiki/latest/thwiki-latest-pages-articles.xml.bz2)


