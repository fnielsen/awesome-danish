# Awesome Danish
A curated list of awesome resources for Danish language technology

## Data
### Corpora
* [Danish Gigaword](http://gigaword.dk/) - Collection of 10^12 words of Danish text. Described in *[The Danish Gigaword Corpus](http://www.ep.liu.se/ecp/178/046/ecp2021178046.pdf)* ([Scholia](https://scholia.toolforge.org/work/Q107060118)) 
* [Danish review dataset](https://github.com/AlessandroGianfelici/danish_reviews_dataset) - Trustpilot-crawled dataset by Alessandro Gianfelici with  44,085 reviews .
* [OSCAR](https://traces1.inria.fr/oscar/) - Danish corpus derived from the Common Crawl corpus. Described in *[Asynchronous Pipeline for Processing Huge Corpora on Medium to Low Resource Infrastructures](https://ids-pub.bsz-bw.de/frontdoor/deliver/index/docId/9021/file/Suarez_Sagot_Romary_Asynchronous_Pipeline_for_Processing_Huge_Corpora_2019.pdf)* ([Scholia](https://scholia.toolforge.org/work/Q85398180))
* CLARIN-DK-UCPH
  * [The Danish Parliament Corpus 2009 - 2017, v1](https://repository.clarin.dk/repository/xmlui/handle/20.500.12115/8). The license is Creative Commons - Attribution 4.0 International
  * [Grundtvig's Works Corpus](https://repository.clarin.dk/repository/xmlui/handle/20.500.12115/31). Not for commercial use as the license is Creative Commons - Attribution-NonCommercial 4.0 International.
  * [DK-CLARIN Reference Corpus of General Danish](https://repository.clarin.dk/repository/xmlui/handle/20.500.12115/36) Only for academic use.
* [DanFEVER](https://figshare.com/articles/dataset/DanFEVER_claim_verification_dataset_for_Danish/14380970) - Danish text corpus with over 6'400 claims and support. Described in *[DanFEVER: claim verification dataset for Danish](http://www.ep.liu.se/ecp/178/047/ecp2021178047.pdf)* ([Scholia](https://scholia.toolforge.org/work/Q107060524))
* [DanNet](https://cst.ku.dk/projekter/dannet/) - wordnet with usage examples. The usage examples have been used for word sense disambiguation, see [XL-WSD: An Extra-Large and Cross-Lingual Evaluation Frameworkfor Word Sense Disambiguation](http://wwwusers.di.uniroma1.it/~navigli/pubs/AAAI_2021_Pasinietal.pdf)
* [SemDaX](https://github.com/coastalcph/semdax) - POS-tagged (only adjectives, nouns and verbs), super sense tagged and BIO-tagged sentences. For educational, teaching or research purposes only. 
* [NOMCO](https://cst.ku.dk/projekter/the-danish-nomco-corpus/) - "an annotated multimodal collection of conversational Danish". Apparently not directly available for download. [ [Scholia](https://scholia.toolforge.org/work/Q57730960) ]
* [Danish Propbank](http://catalog.elra.info/en-us/repository/browse/ELRA-W0117/) - commercial resource with 87,000 tokens annotated with morphosyntactic, VerbNet classes and semantic roles. 
* [Danish Dependency Treebank v. 1.0](http://www.buch-kromann.dk/matthias/ddt1.0/) - Matthias Trautner Kromann et al.'s dependency annotation of some texts from PAROLE.
* [Mr. Bean corpus](https://blog.cbs.dk/mrbean-korpus/) - Small Danish-Italian corpus with written and spoken retelling (of Mr Bean episodes) and argumentative text (about smoking). Possibly described in *Tekststrukturering pa italiensk og dansk*
* [Køge Corpus](https://biling.talkbank.org/access/Koge.html) - Danish-Turkish transcribed corpus by Jens Normann Jørgensen.
* [Danske taler](https://dansketaler.dk) - Collection of Danish speeches. API available at https://dansketaler.dk/wp-json/wp/v2/tale
* [DKhate](https://sites.google.com/site/offensevalsharedtask/home) - corpus of 3600 hate speech from Twitter and Reddits as well as news comments. Described in *[Offensive Language and Hate Speech Detection for Danish](https://www.aclweb.org/anthology/2020.lrec-1.430)* ([Scholia](https://scholia.toolforge.org/work/Q66592400))
* DaNewsroom - Danish summarization dataset. Probably to appear in 2020. Described in *[DaNewsroom: A Large-scale Danish Summarisation Dataset](https://www.aclweb.org/anthology/2020.lrec-1.831.pdf)* ([Scholia](https://scholia.toolforge.org/work/Q85509730))
* Wikipedia
  * [wiki40b/da](https://www.tensorflow.org/datasets/catalog/wiki40b#wiki40bda) - Clean-up text from Danish Wikipedia. Described in *[Wiki-40B: Multilingual Language Model Dataset](https://www.aclweb.org/anthology/2020.lrec-1.297/)*. ([Scholia](https://scholia.toolforge.org/work/Q105430726))
* [XED](https://github.com/Helsinki-NLP/XED) - emotion annotated movie subtitles. Described in *[XED: A Multilingual Dataset for Sentiment Analysis and Emotion Detection](https://www.aclweb.org/anthology/2020.coling-main.575.pdf)* ([Scholia](https://scholia.toolforge.org/work/Q105978198)).
* [DaN+](https://github.com/bplank/DaNplus) - annotated for nested named entities on top of the entire Danish Universal Dependencies (UD_Danish-DDT) and 3 new web domains and includes lexical normalization. Described in *[DaN+: Danish Nested Named Entities and Lexical Normalization](https://www.aclweb.org/anthology/2020.coling-main.583/)* 
* [WikiANN](https://drive.google.com/file/d/11onAGOLkkqrIwM784siWlg-cewa5WKm8/view?usp=sharing) - Named entity annotated corpus. Described in *[Cross-lingual Name Tagging and Linking for 282 Languages](https://www.aclweb.org/anthology/P17-1178.pdf)* ([Scholia](https://scholia.toolforge.org/work/Q54488065))
* [Corona Dataset](https://github.com/certainlyio/corona_dataset) - Question dataset from Certainly annotated for domain and intent.

### Parallel corpora
* [Europarl](https://www.statmt.org/europarl/) - parallel sentences between Danish and English from the European Parlament. 
* [ITU Faroese Pairs Dataset](https://huggingface.co/datasets/strombergnlp/itu_faroese_danish) - Faroese-Danish parallel text. Described in *[The ITU Faroese Pairs Dataset](https://arxiv.org/pdf/2206.08727.pdf)* ([Scholia](https://scholia.toolforge.org/work/Q112673011))
* [JW300](http://opus.nlpl.eu/JW300.php) - "a parallel corpus of over 300 languages with around 100 thousand parallel sentences per language pair on average"
* [OpenSubtitles2018](http://opus.nlpl.eu/OpenSubtitles-v2018.php) - Parallel corpus from movie and tv subtitles. Described in *[OpenSubtitles2016: Extracting Large Parallel Corpora from Movie and TV Subtitles](http://www.lrec-conf.org/proceedings/lrec2016/pdf/947_Paper.pdf)*.
* [Tatoeba](https://tatoeba.org/eng/downloads) - Sentences
* [WikiMatrix](https://github.com/facebookresearch/LASER/tree/master/tasks/WikiMatrix), parallel sentences from Wikipedias. 1620 language pairs, including Danish

### Spoken language corpora
* [DanPASS](https://www.danpass.hum.ku.dk/) - Described in *DanPASS - A Danish Phonetically Annotated Spontaneous Speech corpus* ([Scholia](https://scholia.toolforge.org/work/Q71038312))
* [LANCHART](https://lanchart.hum.ku.dk/) - Centre for Language Change In Real Time. Various audio recordings. Whether the data is available is not immediately apparent. Described in, e.g., *[The data and design of the LANCHART study](https://www.tandfonline.com/doi/pdf/10.1080/03740460903364003)* ([Scholia](https://scholia.toolforge.org/work/Q97756317)).
* [Common Voice](https://commonvoice.mozilla.org/da/datasets) - Crowdsourced multilingual annotated speech dataset. As of April 2022, seven hours of validated speech are distributed. Sentence can be entered collaboratively at https://commonvoice.mozilla.org/sentence-collector. Common Voice is described in *Common Voice: A Massively-Multilingual Speech Corpus* ([Scholia](https://scholia.toolforge.org/work/Q79020060)).
* [FT Speech](https://ftspeech.github.io/) - Described in *FT SPEECH : Danish Parliament Speech Corpus* ([Scholia](https://scholia.toolforge.org/work/Q98841513)).
* NST 
  * [NST-speech-22khz](https://www.nb.no/sprakbanken/ressurskatalog/oai-nb-no-sbr-20/) - A 22kHz speech corpus compiled by Nordisk Språkteknologi and made available by the Norwegian Library Service. The speech genre is dictation.
  * [NST-speech-16kHz](https://www.nb.no/sprakbanken/ressurskatalog/oai-nb-no-sbr-19/) - A 16kHz speech corpus compiled by Nordisk Språkteknologi and made available by the Norwegian Library Service. The speech genre is read-aloud and the text is phonetically balanced. Designed for ASR training and testing.
  * [NST-speech-44kHz](https://www.nb.no/sprakbanken/ressurskatalog/oai-nb-no-sbr-21/) - A 44kHz speech corpus compiled by Nordisk Språkteknologi and made available by the Norwegian Library Service. Designed for speech synthesis.
* [VoxLingua107](http://bark.phon.ioc.ee/voxlingua107/) - 28 hours audio with unannotated Danish speech sampled from YouTube videos. Described in *[VoxLingua107: a Dataset for Spoken Language Recognition](https://arxiv.org/pdf/2011.12998.pdf)* ([Scholia](https://scholia.toolforge.org/work/Q110042720))
* [VoxPopuli](https://github.com/facebookresearch/voxpopuli) - Speech from the European Parliament including 13'600 hours of unannotated Danish. Described in *[VoxPopuli: A Large-Scale Multilingual Speech Corpus for Representation Learning, Semi-Supervised Learning and Interpretation](https://aclanthology.org/2021.acl-long.80.pdf)* ([Scholia](https://scholia.toolforge.org/work/Q109631220))
* [Wikimedia Commons Audio files of Danish language](https://commons.wikimedia.org/wiki/Category:Audio_files_of_Danish_language) - Recordings of readings of articles from the Danish Wikipedia, Danish words and a few Danish literary works.

### Dictionaries and ontologies
* [Det Centrale Ordregister](https://ordregister.dk/) - identifier for words and their inflections with 516,017 forms (COR).
* [The Danish Sentiment Lexicon](https://github.com/dsldk/danish-sentiment-lexicon) - Det Danske Sentimentleksikon (DDS) 13,859 headwords assigned with polarity values.
* [NST-lexical-database](http://www.nb.no/sprakbanken/show?serial=sbr-26) A pronunciation dictionary compiled by Nordisk Språkteknologi and made available by the Norwegian Library Service.
* DanNet [DanNet, Danish Wordnet (v 2.2) - owl format](https://repository.clarin.dk/repository/xmlui/handle/20.500.12115/25) - Danish wordnet with three-clause BSD-like license.
* [Retskrivningsordbogen](https://dsn.dk/retskrivning/om-retskrivningsordbogen/ro-elektronisk-og-som-bog). The official Danish spelling dictionary digitally available under its own special license.
  * [Opslagsord og ordklasser](https://dsn.dk/retskrivning/om-retskrivningsordbogen/RO2012.opslagsord.med.homnr.og.ordklasse.zip) in CSV format.
  * Lexemes, word classes and inflections. [Excerpt](https://dsn.dk/retskrivning/om-retskrivningsordbogen/ro-elektronisk-og-som-bog) in the CSF format available. Full list presumably available upon request.
  * Lexemes, word classes, inflections, grammatical information, hyphenation and usage examples in XML. Full list presumably available upon request.
* [Stavekontrolden](https://stavekontrolden.dk/) - word list with 160,132 Danish words. Used, e.g., for spelling suggestion in LibreOffice. Licensed under GPL, LPGL, and MPL.
* [The Concise Danish Dictionary](http://da.speling.org/)/The Comprehensive Danish Dictionary/Den Store Danske Ordliste (DSDO), word list created by Skåne Sjælland Linux User Group and distributed under a GPL license
  * In Debian-based distributions the word list may be installed with `sudo aptitude install aspell-da` and extracted with `spell -d da dump master`.
* [Interactive Terminology for Europe](https://iate.europa.eu) (IATE) - European Union terminology database. October 2020 version contains over 500,000 Danish terms.
* [The Danish FrameNet Lexicon](https://korpus.dsl.dk/resources/details/framenet.html), 40,267 lines resource containing 5,300 verbs and 6,490 verbal nouns
* Wikidata lexemes - structured database with metadata about lexemes, their forms and their sense. Over [575,000 lexemes](https://ordia.toolforge.org/statistics/) including [over 11,000 Danish lexemes](https://ordia.toolforge.org/language/) in September 2021.
  * [Overview over Danish lexemes in Ordia](https://ordia.toolforge.org/language/Q9035) - webapp with overview of content of Wikidata lexemes based on SPARQL queries. 
  * [Wikidata lexemes latest lexemes dump in ttl](https://dumps.wikimedia.org/wikidatawiki/entities/latest-lexemes.ttl.bz2) - official dump of lexeme-only part of Wikidata.
 * [NST-ngrams](https://www.nb.no/sprakbanken/ressurskatalog/oai-nb-no-sbr-28/) - A N-gram frequency list compiled by Nordisk Språkteknologi from newspaper text and made available by the Norwegian Library Service. Can be compiled to an n-gram LM with SRILM.
* [AFINN](https://github.com/fnielsen/afinn/tree/master/afinn/data) - Danish lexicons annotated for sentiment.  
* [concreteness-estimates-da](https://github.com/billdthompson/cogsci-auto-norm/blob/master/results/concreteness-estimates-da.csv) - Bill D. Thompson's concreteness estimates for Danish words, as detailed in *[Automatic Estimation of Lexical Concreteness in 77 Languages](http://pubman.mpdl.mpg.de/pubman/item/escidoc:2622741/component/escidoc:2622739/Thompson_Lupyan_2018.pdf)* ([Scholia](https://scholia.toolforge.org/work/Q56219750)).
* [SAM lexicon](https://github.com/steffan267/Sentiment-Analysis-on-Danish-Social-Media/tree/master/Lexicon) - sentiment analysis word list extended from AFINN to 4275 lines. Described in *[Sentiment Analysis Multitool, SAM](https://raw.githubusercontent.com/lucaspuvis/SAM/master/Thesis.pdf)*.
* [Danish Swadesh List](https://archive.org/details/rosettaproject_dan_swadesh-1) - List of Danish words of basic concepts from The Rosetta Project.
* [Sketch Engine](https://www.sketchengine.eu) - cloud service with wordlists, thesearus, collocations, n-grams etc. Free for academic use in the European Union and paid service for commercial use.

### Word sets
* [Danish-Similarity-Dataset](https://github.com/kuhumcst/Danish-Similarity-Dataset) - Similarity scores for 99 Danish word pairs by Nina Schneidermann and Bolette Sandford Pedersen. Also available in [danlp](https://github.com/alexandrainst/danlp/blob/master/docs/docs/datasets.md#danish-similarity-dataset).
* [Wordsim353-da](https://github.com/fnielsen/dasem/tree/master/dasem/data/wordsim353-da) - Danish translation by Finn Årup Nielsen of the English Wordsim353 English word pair set. Also available in [danlp](https://github.com/alexandrainst/danlp/blob/master/docs/docs/datasets.md#wordsim-353).
* [Four words](https://github.com/fnielsen/dasem/tree/master/dasem/data) - 100 odd-one-out sets of 4 words or phrases.

### Embeddings 
* [cc.da.300](https://fasttext.cc/docs/en/crawl-vectors.html) ([bin file GB large](https://s3-us-west-1.amazonaws.com/fasttext-vectors/word-vectors-v2/cc.da.300.bin.gz)) - fastText-trained embedding on Danish part of *Common Crawl* and Danish Wikipedia. Read more about the method in *[Learning Word Vectors for 157 Languages](https://arxiv.org/pdf/1802.06893)* ([Scholia](https://scholia.toolforge.org/work/Q49985142)). 
* [wiki.da](https://fasttext.cc/docs/en/pretrained-vectors.html) ([bin+text file](https://s3-us-west-1.amazonaws.com/fasttext-vectors/wiki.da.zip)) - fastText-trained embedding on Danish Wikipedia. Read more about the method in *[Enriching Word Vectors with Subword Information](https://arxiv.org/pdf/1607.04606)* ([Scholia](https://scholia.toolforge.org/work/Q28775150)).
* [Byte-Pair Encoding embedding](https://github.com/bheinzerling/bpemb) - Gensim-based subword embedding. A large number of Danish embeddings are available. They differ in the size of the vocabulary (from 1000 to 200000) and subspace dimensions (from 25 to 300).
* [NLPL word embeddings repository](http://vectors.nlpl.eu/repository/) - NLPL word embeddings repository by Language Technology Group at the University of Oslo. Two Danish embedding models as of November 2020. 
  * [Danish NLPL word embedding](http://vectors.nlpl.eu/repository/20/38.zip) - 100-dimensional word2vec skipgram model trained by Andrey Kutuzov based on the Danish CoNLL17 corpus.
* [Danish DSL and Reddit word2vec word embeddings](https://figshare.com/articles/Danish_DSL_and_Reddit_word2vec_word_embeddings/8099927/1) - 300-dimensional CBOW word2vec word embedding by Emil Middelboe and Anders Lillie trained on Danish DSL corpus and Reddit.

### Neural text models
- [A-ttack](https://github.com/ogtal/A-ttack) - Ælæctra-based model for detection of "textual attacks" developed by [Analyse & Tal](https://ogtal.dk/). Related to the Ha-te model.
- [Danish BERT](https://github.com/mollerhoj/danish_bert) - Certainly's (Botxo/Møllerhøj) Weights for a BERT trained on a large Danish corpora.
- [Danish ELECTRA](https://github.com/sarnikowski/danish_transformers/tree/main/electra) - Philip Tamimi-Sarnikowski's Danish ELECTRA model. Available in the transformer library.
- [daT5-summariser](https://huggingface.co/sarakolding/daT5-summariser) - Danish abstractive summarisation of news articles based on mT5-base.
- [ConvBERT](https://github.com/sarnikowski/danish_transformers/blob/main/convbert/README.md) - Philip Tamimi-Sarnikowski's model
- [Danish ELMo on OSCAR](https://oscar-corpus.com/files/models/cc/da.zip) - (Link does not work as of December 2020)
- [Ha-te](https://github.com/ogtal/Ha-te) - Hate speech detection based on Ælæctra developed by [Analyse & Tal](https://ogtal.dk/). Related to the A-ttack model.
- [Ælæctra](https://huggingface.co/Maltehb/-l-ctra-danish-electra-small-uncased) - Malte Højmark-Bertelsen's Danish Gigaword-trained Electra-based model
- [Multilingual sentence transformers](https://www.sbert.net/docs/pretrained_models.html) - Pre-trained multilingual sentence transformers,
- [wiki40b-lm-da](https://tfhub.dev/google/wiki40b-lm-da/1) - language model trained on Danish from Wiki40B dataset
- [WikiBERT](https://github.com/turkunlp/wikibert) - BERT model for many languages, including Danish. Described in *[WikiBERT models: deep transfer learning for many languages ](https://ep.liu.se/ecp/178/001/ecp2021178001.pdf)* ([Scholia](https://scholia.toolforge.org/work/Q107059867))

### Neural speech models
* [Alvenir Wav2vec2](https://huggingface.co/Alvenir/wav2vec2-base-da) - Pretrained Danish neural model.
* [Whisper](https://openai.com/blog/whisper/) - Multilingual neural model from OpenAI.
* [xls-r-300m-danish-nst-cv9](https://huggingface.co/chcaa/xls-r-300m-danish-nst-cv9) - Pretrained Danish neural model.

## Tools 

### Lemmatization 
- [Lemmy](https://github.com/sorenlind/lemmy) - Lemmatizer for Danish in Python.
- [cstlemma](https://github.com/kuhumcst/cstlemma) - lemmatiser.
- [spaCy](https://spacy.io) - Python-based package with lemmatization.

### Punctuation 
- [punctfix](https://github.com/danspeech/punctfix) - "Adds punctuation and capitalization for a given text."

### Named entity recognition
- [ScandiNER](https://huggingface.co/saattrupdan/nbailab-base-ner-scandi) - Scandinavian named entity recognition, achieving state-of-the-art performance in Danish, Norwegian (both Bokmål and Nynorsk), Swedish, Icelandic and Faroese.
- [DaLUKE](https://github.com/peleiden/daLUKE) - Danish named entity recognition based on LUKE. Described in *[DaLUKE: The Entity-aware,Danish Language Model](https://peleiden.github.io/bug-free-guacamole/main.pdf)*.
- [spaCy](https://spacy.io) - Python-based named entity extraction 
- [daner](https://github.com/ITUnlp/daner) - Named entity extraction from ITU NLP. Described in *[DKIE: Open Source Information Extraction for Danish](https://aclanthology.org/E14-2016.pdf)* ([Scholia](https://scholia.toolforge.org/work/Q28609956)).
- [flair+danlp ner-tagger](https://github.com/alexandrainst/danlp/blob/master/docs/docs/tasks/ner.md) - Flair NER tagger trained by the Alexandra Institute.
- [Polyglot named entity extraction](https://polyglot.readthedocs.io/en/latest/NamedEntityRecognition.html) - 

### Entity linking
- [Babelfy](http://babelfy.org/) - Web app and service for linking words and entities.
- [DBpedia Spotlight](https://www.dbpedia-spotlight.org/) - DBpedia-based entity linker. Described in *Improving Efficiency and Accuracy in Multilingual Entity Extraction* ([Scholia](https://scholia.toolforge.org/work/Q106526263))

### Sentiment analysis
- [afinn](https://github.com/fnielsen/afinn/) - Python package with AFINN Danish lexicon annotated for sentiment, also installable with `pip install afinn`.
- [Hisia](https://github.com/Proteusiq/hisia) - Python package with pre-trained machine-learning based Danish sentiment analysis by Prayson Wilfred Daniel.
- [senda](https://github.com/ebanalyse/senda) - Python package with transformer-based sentiment analysis from Ekstra Bladet Analyse with as of 2021 [state-of-the-art performance](https://danlp-alexandra.readthedocs.io/en/latest/docs/tasks/sentiment_analysis.html#benchmark-of-polarity-classification) on one dataset.
- [Sentida](https://github.com/Guscode/Sentida/) - R package With Danish sentiment lexicon and handling of, e.g., negation. Detailed in *[SENTIDA: A New Tool for Sentiment Analysis in Danish](https://tidsskrift.dk/lwo/article/download/115711/163973/)* ([Scholia](https://scholia.toolforge.org/work/Q67272735)).

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
- [spaCy](https://spacy.io/) - Python-based natural language processing package
- [dacy](https://github.com/KennethEnevoldsen/DaCy) - Danish spaCy pipeline.

## Competitions 
- [ELEXIS Monolingual Word Sense Alignment Task](https://competitions.codalab.org/competitions/22163) - Predicting the relationship between two senses in each of several languages, including Danish.
- [OffensEval 2020 - Danish](https://competitions.codalab.org/competitions/22998) - Offensive Language Identification in Social Media competition. Described in [Offensive Language and Hate Speech Detection for Danish](https://arxiv.org/pdf/1908.04531.pdf) ([Scholia](https://scholia.toolforge.org/work/Q66592400))

## Resources about resources
- [Danish resources](https://people.compute.dtu.dk/faan/ps/Nielsen2016Danish.pdf) - Finn Årup Nielsen's PDF with pointers to Danish resources.
- [Scholia's topic aspect for *Danish*](https://scholia.toolforge.org/topic/Q9035), works (mostly scientific articles) about "Danish" as listed in Wikidata.
- [DaNLP](https://github.com/alexandrainst/danlp) - Alexandra Institute's list of Danish resources
- [Language Technology Resources for Danish](https://korpus.dsl.dk/resources.html), list from Det Dansk Sprog- og Litteraturselskab
- [European Language Resources Association (ELRA) list for *Danish*](http://catalog.elra.info/en-us/repository/search/?selected_facets=languageNameFilter_exact%3ADanish), list of various annotated corpora available for purchase with both commercial and non-commercial licenses.
- [sprogteknologi.dk](https://sprogteknologi.dk) - List of Danish language resources. Compiled by the Agency for Digitisation.
