# Awesome Danish
A curated list of awesome resources for Danish language technology

## Data
### Corpora
* [Danish Gigaword](http://gigaword.dk/) - Collection of Danish corpora (as of May 2020 the corpus is not openly available).
* [OSCAR](https://traces1.inria.fr/oscar/) - Danish corpus derived from the Common Crawl corpus. Described in [Asynchronous Pipeline for Processing Huge Corpora on Medium to Low Resource Infrastructures](https://ids-pub.bsz-bw.de/frontdoor/deliver/index/docId/9021/file/Suarez_Sagot_Romary_Asynchronous_Pipeline_for_Processing_Huge_Corpora_2019.pdf) ([Scholia](https://scholia.toolforge.org/work/Q85398180))
* CLARIN-DK-UCPH
  * [The Danish Parliament Corpus 2009 - 2017, v1](https://repository.clarin.dk/repository/xmlui/handle/20.500.12115/8). The license is Creative Commons - Attribution 4.0 International
  * [Grundtvig's Works Corpus](https://repository.clarin.dk/repository/xmlui/handle/20.500.12115/31). Not for commercial use as the license is Creative Commons - Attribution-NonCommercial 4.0 International.
  * [DK-CLARIN Reference Corpus of General Danish](https://repository.clarin.dk/repository/xmlui/handle/20.500.12115/36) Only for academic use.
* [SemDaX](https://github.com/coastalcph/semdax) - POS-tagged (only adjectives, nouns and verbs), super sense tagged and BIO-tagged sentences. For educational, teaching or research purposes only. 
* [NOMCO](https://cst.ku.dk/projekter/the-danish-nomco-corpus/) - "an annotated multimodal collection of conversational Danish". Apparently not directly available for download. [ [Scholia](https://scholia.toolforge.org/work/Q57730960) ]
* [Danish Propbank](http://catalog.elra.info/en-us/repository/browse/ELRA-W0117/) - commercial resource with 87,000 tokens annotated with morphosyntactic, VerbNet classes and semantic roles. 
* [Danish Dependency Treebank v. 1.0](http://www.buch-kromann.dk/matthias/ddt1.0/) - Matthias Trautner Kromann et al.'s dependency annotation of some texts from PAROLE.
* [Mr. Bean corpus](https://blog.cbs.dk/mrbean-korpus/) - Small Danish-Italian corpus with written and spoken retelling (of Mr Bean episodes) and argumentative text (about smoking). Possibly described in *Tekststrukturering pa italiensk og dansk*
* [Køge Corpus](https://biling.talkbank.org/access/Koge.html) - Danish-Turkish transcribed corpus by Jens Normann Jørgensen.
* [Danske taler](https://dansketaler.dk) - Collection of Danish speeches. API available at https://dansketaler.dk/wp-json/wp/v2/tale
* [DKhate](https://leondz.github.io/hatespeechdata/) - corpus of 3600 hate speech from Twitter and Reddits as well as news comments (to appear in 2020)
* DaNewsroom - Danish summarization dataset. Probably to appear in 2020. Described in DaNewsroom: A Large-scale Danish Summarisation Dataset ([Scholia](https://scholia.toolforge.org/work/Q85509730))

### Parallel corpora
* [Europarl](https://www.statmt.org/europarl/), parallel sentences between Danish and English from the European Parlament. 
* [JW300](http://opus.nlpl.eu/JW300.php) - "a parallel corpus of over 300 languages with around 100 thousand parallel sentences per language pair on average"
* [Tatoeba](https://tatoeba.org/eng/downloads) - Sentences
* [WikiMatrix](https://github.com/facebookresearch/LASER/tree/master/tasks/WikiMatrix), parallel sentences from Wikipedias. 1620 language pairs, including Danish

### Spoken language corpora
* DanPASS - Described in *DanPASS - A Danish Phonetically Annotated Spontaneous Speech corpus* ([Scholia](https://scholia.toolforge.org/work/Q71038312))
* DK-Parole
* LANCHART
* [Common Voice](https://voice.mozilla.org/da) - Crowdsourced multilingual voice dataset. As of 18 December 2019 there is no Danish data. Described in *Common Voice: A Massively-Multilingual Speech Corpus* ([Scholia](https://scholia.toolforge.org/work/Q79020060))
* NST 
  * [NST-speech-22khz](https://www.nb.no/sprakbanken/ressurskatalog/oai-nb-no-sbr-20/) - A 22kHz speech corpus compiled by Nordisk Språkteknologi and made available by the Norwegian Library Service. The speech genre is dictation.
  * [NST-speech-16kHz](https://www.nb.no/sprakbanken/ressurskatalog/oai-nb-no-sbr-19/) - A 16kHz speech corpus compiled by Nordisk Språkteknologi and made available by the Norwegian Library Service. The speech genre is read-aloud and the text is phonetically balanced. Designed for ASR training and testing.
  * [NST-speech-44kHz](https://www.nb.no/sprakbanken/ressurskatalog/oai-nb-no-sbr-21/) - A 44kHz speech corpus compiled by Nordisk Språkteknologi and made available by the Norwegian Library Service. Designed for speech synthesis.


### Dictionaries and ontologies
* [NST-lexical-database](http://www.nb.no/sprakbanken/show?serial=sbr-26) A pronunciation dictionary compiled by Nordisk Språkteknologi and made available by the Norwegian Library Service.
* DanNet [DanNet, Danish Wordnet (v 2.2) - owl format](https://repository.clarin.dk/repository/xmlui/handle/20.500.12115/25) - Danish wordnet with three-clause BSD-like license.
* [Retskrivningsordbogen](https://dsn.dk/retskrivning/om-retskrivningsordbogen/ro-elektronisk-og-som-bog). The official Danish spelling dictionary digitally available under its own special license.
  * [Opslagsord og ordklasser](https://dsn.dk/retskrivning/om-retskrivningsordbogen/RO2012.opslagsord.med.homnr.og.ordklasse.zip) in CSV format.
  * Lexemes, word classes and inflections. [Excerpt](https://dsn.dk/retskrivning/om-retskrivningsordbogen/ro-elektronisk-og-som-bog) in the CSF format available. Full list presumably available upon request.
  * Lexemes, word classes, inflections, grammatical information, hyphenation and usage examples in XML. Full list presumably available upon request.
* [Stavekontrolden](https://stavekontrolden.dk/) - word list with 160132 Danish words. Used, e.g., for spelling suggestion in LibreOffice. Licensed under GPL, LPGL, and MPL.
* [The Concise Danish Dictionary](http://da.speling.org/)/The Comprehensive Danish Dictionary/Den Store Danske Ordliste (DSDO), word list created by Skåne Sjælland Linux User Group and distributed under a GPL license
  * In Debian-based distributions the word list may be installed with `sudo aptitude install aspell-da` and extracted with `spell -d da dump master`.
* [Interactive Terminology for Europe](https://iate.europa.eu) (IATE) - European Union terminology database. October 2020 version contains over 500,000 Danish terms.
* [The Danish FrameNet Lexicon](https://korpus.dsl.dk/e-resources/FrameNet.html), 40,267 lines resource containing 5,300 verbs and 6,490 verbal nouns
* Wikidata lexemes - structured database with metadata about lexemes, their forms and their sense. Over [300,000 lexemes](https://ordia.toolforge.org/statistics/) including [over 6,700 Danish lexemes](https://ordia.toolforge.org/language/) in October 2020.
  * [Overview over Danish lexemes in Ordia](https://ordia.toolforge.org/language/Q9035) - webapp with overview of content of Wikidata lexemes based on SPARQL queries. 
  * [Wikidata lexemes latest lexemes dump in ttl](https://dumps.wikimedia.org/wikidatawiki/entities/latest-lexemes.ttl.bz2) - official dump of lexeme-only part of Wikidata.
 * [NST-ngrams](https://www.nb.no/sprakbanken/ressurskatalog/oai-nb-no-sbr-28/) - A N-gram frequency list compiled by Nordisk Språkteknologi from newspaper text and made available by the Norwegian Library Service. Can be compiled to an n-gram LM with SRILM.
* [AFINN](https://github.com/fnielsen/afinn/tree/master/afinn/data) - Danish lexicons annotated for sentiment.  
* [concreteness-estimates-da](https://github.com/billdthompson/cogsci-auto-norm/blob/master/results/concreteness-estimates-da.csv) - Bill D. Thompson's concreteness estimates for Danish words, as detailed in *[Automatic Estimation of Lexical Concreteness in 77 Languages](http://pubman.mpdl.mpg.de/pubman/item/escidoc:2622741/component/escidoc:2622739/Thompson_Lupyan_2018.pdf)* ([Scholia](https://scholia.toolforge.org/work/Q56219750)).
* [Danish Swadesh List](https://archive.org/details/rosettaproject_dan_swadesh-1) - List of Danish words of basic concepts from The Rosetta Project.
* [Sketch Engine](https://www.sketchengine.eu) - cloud service with wordlists, thesearus, collocations, n-grams etc. Free for academic use in the European Union and paid service for commercial use.

### Word sets
* [Danish-Similarity-Dataset](https://github.com/kuhumcst/Danish-Similarity-Dataset) - Similarity scores for 99 Danish word pairs by Nina Schneidermann and Bolette Sandford Pedersen.
* [Wordsim353-da](https://github.com/fnielsen/dasem/tree/master/dasem/data/wordsim353-da) - Danish translation by Finn Årup Nielsen of the English Wordsim353 English word pair set.
* [Four words](https://github.com/fnielsen/dasem/tree/master/dasem/data) - 100 odd-one-out sets of 4 words or phrases.

### Embeddings 
* [cc.da.300](https://fasttext.cc/docs/en/crawl-vectors.html) ([bin file GB large](https://s3-us-west-1.amazonaws.com/fasttext-vectors/word-vectors-v2/cc.da.300.bin.gz)) - fastText-trained embedding on Danish part of *Common Crawl* and Danish Wikipedia. Read more about the method in *[Learning Word Vectors for 157 Languages](https://arxiv.org/pdf/1802.06893)* ([Scholia](https://scholia.toolforge.org/work/Q49985142)). 
* [wiki.da](https://fasttext.cc/docs/en/pretrained-vectors.html) ([bin+text file](https://s3-us-west-1.amazonaws.com/fasttext-vectors/wiki.da.zip)) - fastText-trained embedding on Danish Wikipedia. Read more about the method in *[Enriching Word Vectors with Subword Information](https://arxiv.org/pdf/1607.04606)* ([Scholia](https://scholia.toolforge.org/work/Q28775150)).
* [Byte-Pair Encoding embedding](https://github.com/bheinzerling/bpemb) - Gensim-based subword embedding. A large number of Danish embeddings are available. They differ in the size of the vocabulary (from 1000 to 200000) and subspace dimensions (from 25 to 300).
* [NLPL word embeddings repository](http://vectors.nlpl.eu/repository/) - NLPL word embeddings repository by Language Technology Group at the University of Oslo. Two Danish embedding models as of November 2020. 
  * [Danish NLPL word embedding](http://vectors.nlpl.eu/repository/20/38.zip) - 100-dimensional word2vec skipgram model trained by Andrey Kutuzov based on the Danish CoNLL17 corpus.
* [Danish DSL and Reddit word2vec word embeddings](https://figshare.com/articles/Danish_DSL_and_Reddit_word2vec_word_embeddings/8099927/1) - 300-dimensional CBOW word2vec word embedding by Emil Middelboe and Anders Lillie trains on Danish DSL corpus and Reddit.

### Neural models
- [Danish BERT](https://github.com/mollerhoj/danish_bert) - Weights for a BERT trained on a large Danish corpora.
- [Danish ELECTRA](https://github.com/sarnikowski/danish_transformers/tree/main/electra) - Danish ELECTRA model. Available in the transformer library.
- [Danish ELMo on OSCAR](https://oscar-corpus.com/files/models/cc/da.zip) - (Link does not work as of December 2020)

## Tools 

### Lemmatization 
- [Lemmy](https://github.com/sorenlind/lemmy) - Lemmatizer for Danish in Python
- [cstlemma](https://github.com/kuhumcst/cstlemma) - lemmatiser

### Named entity recognition
- [spaCy](https://spacy.io) - Python-based named entity extraction 
- [daner](https://github.com/ITUnlp/daner) - Named entity extraction.
- [flair+danlp ner-tagger](https://github.com/alexandrainst/danlp/blob/master/docs/models/ner.md) - Flair NER tagger trained by the Alexandra Institute.
- [Polyglot named entity extraction](https://polyglot.readthedocs.io/en/latest/NamedEntityRecognition.html) - 

### Sentiment analysis
- [afinn](https://github.com/fnielsen/afinn/) - Python package with AFINN Danish lexicon annotated for sentiment, also installable with `pip install afinn`.
- [Sentida](https://github.com/Guscode/Sentida/) - R package With Danish sentiment lexicon and handling of, e.g., negation. Detailed in *[SENTIDA: A New Tool for Sentiment Analysis in Danish](https://tidsskrift.dk/lwo/article/download/115711/163973/)* ([Scholia](https://scholia.toolforge.org/work/Q67272735)).
- [Hisia](https://github.com/Proteusiq/hisia) - Python package with pre-trained machine-learning based Danish sentiment analysis by Prayson Wilfred Daniel.

### Automatic Speech Recognition
* [danspeech](https://github.com/danspeech/danspeech) - DeepSpeech2-based Danish speech recognition in Python
* [kaldi-sprakbanken](https://github.com/kaldi-asr/kaldi/tree/master/egs/sprakbanken/s5) - A recipe for training state-of-the-art(2017) speech recogniser for Danish based on the 16kHz NST database.

### Speech Synthesis (text-to-speech)
* [espeak](http://espeak.sourceforge.net/) - An open-source speech synthesis program for ~56 languages including Danish. eSpeak can also be used as a grapheme-to-phoneme converter and was used to create the Danish Kaldi recipe.
* [ResponsiveVoice](https://responsivevoice.org/) - Commercial Web-based (Javascript-based) text-to-speech synthesis for a number of languages, including Danish. The commercial service is currently free for limited and non-commercial use.
* [Google Cloud Text-to-Speech](https://cloud.google.com/text-to-speech/) - Commercial Web-based text-to-speech synthesis for a number of languages, including Danish.
* [Amazon Polly](https://aws.amazon.com/polly/) - Commercial Web-based text-to-speech synthesis for a number of languages, including Danish. Part of Amazon's commercial AWS services. Female and male voices are available as examples. Limited unregistered free service available at [TTSMP3](https://ttsmp3.com/text-to-speech/Danish/).

### Fundamental processing
- [DaNLP](https://github.com/alexandrainst/danlp/) - "a repository for Natural Language Processing resources for the Danish Language."
- [dapipe](https://github.com/ITUnlp/dapipe) - Danish UD-pipe: tokenisation, lemmatisation, PoS tagging, morphology, dependencies.
- [UDPipe](http://ufal.mff.cuni.cz/udpipe) - Non-language specific version of dapipe. Newer version of the Danish-DDT model than that which is offered by dapipe is available at https://lindat.mff.cuni.cz/repository/xmlui/handle/11234/1-2998
- [DKIE](https://gate.ac.uk/sale/tao/splitch15.html#sec:misc-creole:language-plugins:danish) - GATE pipeline including wrapped Danish models for Stanford CoreNLP.
- [StanfordNLP](https://stanfordnlp.github.io/stanfordnlp/). Python software package for dependency parsing, including tokenization, lemmatization and part-of-speech tagging. A pre-trained model for Danish is available.
 - [bornholmsk](https://github.com/leondz/bornholmsk) - Datasets and embeddings for the Bornholmsk dialect.

## Competitions 
- [ELEXIS Monolingual Word Sense Alignment Task](https://competitions.codalab.org/competitions/22163) - Predicting the relationship between two senses in each of several languages, including Danish.
- [OffensEval 2020 - Danish](https://competitions.codalab.org/competitions/22998) - Offensive Language Identification in Social Media competition. Described in [Offensive Language and Hate Speech Detection for Danish](https://arxiv.org/pdf/1908.04531.pdf) ([Scholia](https://scholia.toolforge.org/work/Q66592400))

## Resources about resources
- [Danish resources](https://people.compute.dtu.dk/faan/ps/Nielsen2016Danish.pdf) - Finn Årup Nielsen's PDF with pointers to Danish resources.
- [Scholia's topic aspect for *Danish*](https://scholia.toolforge.org/topic/Q9035), works (mostly scientific articles) about "Danish" as listed in Wikidata.
- [Language Technology Resources for Danish](https://korpus.dsl.dk/resources.html), list from Det Dansk Sprog- og Litteraturselskab
- [European Language Resources Association (ELRA) list for *Danish*](http://catalog.elra.info/en-us/repository/search/?selected_facets=languageNameFilter_exact%3ADanish), list of various annotated corpora available for purchase with both commercial and non-commercial licenses.
- [sprogteknologi.dk](https://sprogteknologi.dk) - List of Danish language resources. Compiled by the Agency for Digitisation.
