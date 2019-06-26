# Awesome Danish
A curated list of awesome resources for Danish language technology

## Corpora
* NST
  * [NST-ngrams](http://www.nb.no/sprakbanken/show?serial=sbr-28) - A N-gram frequency list compiled by Nordisk Språkteknologi from newspaper text and made available by the Norwegian Library Service. Can be compiled to an n-gram LM with SRILM.
  * [NST-speech-22khz](http://www.nb.no/sprakbanken/show?serial=sbr-20) - A 22kHz speech corpus compiled by Nordisk Språkteknologi and made available by the Norwegian Library Service. The speech genre is dictation.
  * [NST-speech-16kHz](http://www.nb.no/sprakbanken/show?serial=sbr-19) - A 16kHz speech corpus compiled by Nordisk Språkteknologi and made available by the Norwegian Library Service. The speech genre is read-aloud and the text is phonetically balanced. Designed for ASR training and testing.
  * [NST-speech-44kHz](http://www.nb.no/sprakbanken/show?serial=sbr-21) - A 44kHz speech corpus compiled by Nordisk Språkteknologi and made available by the Norwegian Library Service. Designed for speech synthesis.
* CLARIN-DK-UCPH
  * [The Danish Parliament Corpus 2009 - 2017, v1](https://repository.clarin.dk/repository/xmlui/handle/20.500.12115/8). The license is Creative Commons - Attribution 4.0 International
  * [Grundtvig's Works Corpus](https://repository.clarin.dk/repository/xmlui/handle/20.500.12115/31). Not for commercial use as the license is Creative Commons - Attribution-NonCommercial 4.0 International.
  * [DK-CLARIN Reference Corpus of General Danish](https://repository.clarin.dk/repository/xmlui/handle/20.500.12115/36) Only for academic use.
* [SemDaX](https://github.com/coastalcph/semdax) For educational, teaching or research purposes only. POS-tagged (only adjectives, nouns and verbs), super sense tagged and BIO-tagged sentences
* [NOMCO](https://cst.ku.dk/projekter/the-danish-nomco-corpus/) is "an annotated multimodal collection of conversational Danish". Apparently not directly available for download. [ [Scholia](https://tools.wmflabs.org/scholia/work/Q57730960) ]
* [Danish Propbank](http://catalog.elra.info/en-us/repository/browse/ELRA-W0117/), commercial resource with 87,000 tokens annotated with morphosyntactic, VerbNet classes and semantic roles. 
* [DKhate](https://leondz.github.io/hatespeechdata/), corpus of 3600 hate speech from Twitter and Reddits as well as news comments (to appear in 2019)

## Dictionaries and ontologies
* [NST-lexical-database](http://www.nb.no/sprakbanken/show?serial=sbr-26) A pronunciation dictionary compiled by Nordisk Språkteknologi and made available by the Norwegian Library Service.
* DanNet [DanNet, Danish Wordnet (v 2.2) - owl format](https://repository.clarin.dk/repository/xmlui/handle/20.500.12115/25) - Danish wordnet with three-clause BSD-like license.
* [Retskrivningsordbogen](https://dsn.dk/retskrivning/om-retskrivningsordbogen/ro-elektronisk-og-som-bog). The official Danish spelling dictionary digitally avaiable under its own special license.
  * [Opslagsord og ordklasser](https://dsn.dk/retskrivning/om-retskrivningsordbogen/RO2012.opslagsord.med.homnr.og.ordklasse.zip) in CSV format.
  * Lexemes, word classes and inflections. [Excerpt](https://dsn.dk/retskrivning/om-retskrivningsordbogen/ro-elektronisk-og-som-bog) in the CSF format available. Full list presumably available upon request.
  * Lexemes, word classes, inflections, grammatical information, hyphenation and usage examples in XML. Full list presumably available upon request.
* The Comprehensive Danish Dictionary/Den Store Danske Ordliste (DSDO), word list created by Skåne Sjælland Linux User Group and distributed under a GPL license
  * Primary distribution site at http://da.speling.org/ seems no longer available 
  * In Debian-based distributions the word list may be installed with `sudo aptitude install aspell-da` and extracted with `spell -d da dump master`.
* [The Danish FrameNet Lexicon](https://korpus.dsl.dk/e-resources/FrameNet.html), 40,267 lines resource containing 5,300 verbs and 6,490 verbal nouns
* Wikidata lexemes, structured database with metadata bout lexemes, their forms and their sense. Over 50.000 lexemes including 1.800 Danish in June 2019
  * [Overview over Danish lexemes in Ordia](https://tools.wmflabs.org/ordia/language/Q9035)
  * [Latest lexemes dump in ttl](https://dumps.wikimedia.org/wikidatawiki/entities/latest-lexemes.ttl.bz2)

## Automatic Speech Recognition
* [kaldi-sprakbanken](https://github.com/kaldi-asr/kaldi/tree/master/egs/sprakbanken/s5) - A recipe for training state-of-the-art(2017) speech recogniser for Danish based on the 16kHz NST database.

## Speech Synthesis (text-to-speech)
* [espeak](http://espeak.sourceforge.net/) - An open-source speech synthesis program for ~56 languages including Danish. eSpeak can also be used as a grapheme-to-phoneme converter and was used to create the Danish Kaldi recipe.
* [ResponsiveVoice](https://responsivevoice.org/) - Web-based (Javascript-based) text-to-speech synthesis for a number of languages, including Danish. The commercial service is currently free for limited and non-commercial use.

## Sentiment analysis
- [AFINN](https://github.com/fnielsen/afinn/tree/master/afinn/data) - Danish lexicons annotated for sentiment.  
- [afinn](https://github.com/fnielsen/afinn/) - Python package with AFINN Danish lexicon annotated for sentiment, also installable with `pip install afinn`.

## Lexical norms
- [concreteness-estimates-da](https://github.com/billdthompson/cogsci-auto-norm/blob/master/results/concreteness-estimates-da.csv) - Bill D. Thompson's concreteness estimates for Danish words, as detailed in *[Automatic Estimation of Lexical Concreteness in 77 Languages](http://pubman.mpdl.mpg.de/pubman/item/escidoc:2622741/component/escidoc:2622739/Thompson_Lupyan_2018.pdf)* ([Scholia](https://tools.wmflabs.org/scholia/work/Q56219750)).

## Embeddings 
- [cc.da.300](https://fasttext.cc/docs/en/crawl-vectors.html) ([bin file GB large](https://s3-us-west-1.amazonaws.com/fasttext-vectors/word-vectors-v2/cc.da.300.bin.gz)) - fastText-trained embedding on Danish part of *Common Crawl* and Danish Wikipedia. Read more about the method in *[Learning Word Vectors for 157 Languages](https://arxiv.org/pdf/1802.06893)* ([Scholia](https://tools.wmflabs.org/scholia/work/Q49985142)). 
- [wiki.da](https://fasttext.cc/docs/en/pretrained-vectors.html) ([bin+text file](https://s3-us-west-1.amazonaws.com/fasttext-vectors/wiki.da.zip)) - fastText-trained embedding on Danish Wikipedia. Read more about the method in *[Enriching Word Vectors with Subword Information](https://arxiv.org/pdf/1607.04606)* ([Scholia](https://tools.wmflabs.org/scholia/work/Q28775150)).
- [Byte-Pair Encoding embedding](https://github.com/bheinzerling/bpemb) - Gensim-based subword embedding. A large number of Danish embeddings are available. They differ in the size of the vocabulary (from 1000 to 200000) and subspace dimensions (from 25 to 300).

## Fundamental processing
- [cstlemma](https://github.com/kuhumcst/cstlemma) - lemmatiser
- [Lemmy](https://github.com/sorenlind/lemmy) - Lemmatizer for Danish in Python
- [daner](https://github.com/ITUnlp/daner) - Named entity extraction.
- [dapipe](https://github.com/ITUnlp/dapipe) - Danish UD-pipe: tokenisation, lemmatisation, PoS tagging, morphology, dependencies.
- [DKIE](https://gate.ac.uk/sale/tao/splitch15.html#sec:misc-creole:language-plugins:danish) - GATE pipeline including wrapped Danish models for Stanford CoreNLP.
- [StanfordNLP](https://stanfordnlp.github.io/stanfordnlp/). Python software package for dependency parsing, including tokenization, lemmatization and part-of-speech tagging. A pre-trained model for Danish is available.
 - [bornholmsk](https://github.com/leondz/bornholmsk) - Datasets and embeddings for the Bornholmsk dialect.

## Resources about resources
- [Danish resources](http://www2.imm.dtu.dk/pubdb/views/edoc_download.php/6956/pdf/imm6956.pdf) - Finn Årup Nielsen's PDF with pointers to Danish resources.
- [Scholia's topic aspect for *Danish*](https://tools.wmflabs.org/scholia/topic/Q9035), works (mostly scientific articles) about "Danish" as listed in Wikidata.
- [Language Technology Resources for Danish](https://korpus.dsl.dk/resources.html), list from Det Dansk Sprog- og Litteraturselskab
- [European Language Resources Association (ELRA) list for *Danish*](http://catalog.elra.info/en-us/repository/search/?selected_facets=languageNameFilter_exact%3ADanish), list of various annotated corpora available for purchase with both commercial and non-commercial licenses.
