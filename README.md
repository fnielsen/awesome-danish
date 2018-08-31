# Awesome Danish
A curated list of awesome resources for Danish language technology

## Corpora

## Sentiment analysis
- [AFINN](https://github.com/fnielsen/afinn/tree/master/afinn/data) - Danish lexicons annotated for sentiment.  
- [afinn](https://github.com/fnielsen/afinn/) - Python package with AFINN Danish lexicon annotated for sentiment, also installable with `pip install afinn`.

## Lexical norms
- [concreteness-estimates-da](https://github.com/billdthompson/cogsci-auto-norm/blob/master/results/concreteness-estimates-da.csv) - Bill D. Thompson's concreteness estimates for Danish words, as detailed in *[Automatic Estimation of Lexical Concreteness in 77 Languages](http://pubman.mpdl.mpg.de/pubman/item/escidoc:2622741/component/escidoc:2622739/Thompson_Lupyan_2018.pdf)* ([Scholia](https://tools.wmflabs.org/scholia/work/Q56219750)).

## Embeddings 
- [cc.da.300](https://fasttext.cc/docs/en/crawl-vectors.html) ([bin file GB large](https://s3-us-west-1.amazonaws.com/fasttext-vectors/word-vectors-v2/cc.da.300.bin.gz)) - fastText-trained embedding on Danish part of *Common Crawl* and Danish Wikipedia. Read more about the method in *[Learning Word Vectors for 157 Languages](https://arxiv.org/pdf/1802.06893)* ([Scholia](https://tools.wmflabs.org/scholia/work/Q49985142)). 
- [wiki.da](https://fasttext.cc/docs/en/pretrained-vectors.html) ([bin+text file](https://s3-us-west-1.amazonaws.com/fasttext-vectors/wiki.da.zip)) - fastText-trained embedding on Danish Wikipedia. Read more about the method in *[Enriching Word Vectors with Subword Information](https://arxiv.org/pdf/1607.04606)* ([Scholia](https://tools.wmflabs.org/scholia/work/Q28775150)).

## Fundamental processing
- [cstlemma](https://github.com/kuhumcst/cstlemma) - lemmatiser
- [daner](https://github.com/ITUnlp/daner) - Named entity extraction.
- [dapipe](https://github.com/ITUnlp/dapipe) - Danish UD-pipe: tokenisation, lemmatisation, PoS tagging, morphology, dependencies.
- [DKIE](https://gate.ac.uk/sale/tao/splitch15.html#sec:misc-creole:language-plugins:danish) - GATE pipeline including wrapped Danish models for Stanford CoreNLP.

## Resources about resources
- [Danish resources](http://www2.imm.dtu.dk/pubdb/views/edoc_download.php/6956/pdf/imm6956.pdf) - Finn Årup Nielsen's PDF with pointers to Danish resources.
- [Scholia's topic aspect for *Danish*](https://tools.wmflabs.org/scholia/topic/Q9035), works (mostly scientific articles) about "Danish" as listed in Wikidata.
