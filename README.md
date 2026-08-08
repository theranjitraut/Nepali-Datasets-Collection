# Nepali Datasets Collection

*A comprehensive, organized collection of 100+ Nepali datasets across NLP, Computer Vision, Speech, OCR, and more for AI/ML research and development.*

---

## 📋 Table of Contents

1. [🤖 LLM Development Resources](#-llm-development-resources)
2. [📊 Benchmarks &amp; Standards](#-benchmarks--standards)
3. [📚 Text Corpora](#-text-corpora)
4. [🎯 NLP Datasets](#-nlp-datasets)
5. [🔤 Translation &amp; Parallel Data](#-translation--parallel-data)
6. [🎤 Speech &amp; Audio Datasets](#-speech--audio-datasets)
7. [🖼️ Computer Vision Datasets](#-computer-vision-datasets)
8. [📝 Lexicons &amp; Linguistic Resources](#-lexicons--linguistic-resources)
9. [🤖 Pre-trained Models &amp; Embeddings](#-pre-trained-models--embeddings)
10. [🛠️ Tools &amp; Frameworks](#-tools--frameworks)
11. [🔬 Research Papers](#-research-papers)
12. [📂 Open Data &amp; Government Resources](#-open-data--government-resources)
13. [🌐 Additional Resources](#-additional-resources)

---

## 🤖 LLM Development Resources

### Pre-training Corpora

#### Ultra-Large (&gt;1GB)

| Dataset                              | Size                    | Source                | Link                                                                                  |
| ------------------------------------ | ----------------------- | --------------------- | ------------------------------------------------------------------------------------- |
| Nepali-Text-Corpus (IRIISNEPAL)      | 6.4M articles, 10.1 GB  | 99 news websites      | [HF](https://huggingface.co/datasets/IRIISNEPAL/nepali-text-corpus)                   |
| OSCAR Corpus Nepali                  | 3.8 GB, 100M+ sentences | Common Crawl          | [Kaggle](https://www.kaggle.com/hsebarp/oscar-corpus-nepali)                          |
| CC100-Nepali                         | 200GB uncompressed      | Common Crawl 2019     | [MetaText](https://metatext.io/datasets/cc100-nepali)                                 |
| Large Scale Nepali Text Corpus       | Large-scale             | General               | [IEEE Dataport](https://ieee-dataport.org/open-access/large-scale-nepali-text-corpus) |
| Boredoom17 Nepali Corpus             | -                       | General               | [HF](https://huggingface.co/datasets/Boredoom17/Nepali-Corpus)                        |
| Gold Standard Nepali Raw Text Corpus | -                       | Raw text              | [LDCIL](https://data.ldcil.org/a-gold-standard-nepali-raw-text-corpus)                |
| Language Resources for Nepal         | Multiple datasets       | Aggregated collection | [language-resources-nepal.github.io](https://language-resources-nepal.github.io/data) |
| OpenWiseyak-0.1-Pretraining          | -                       | Wiseyak               | [HF](https://huggingface.co/datasets/Wiseyak/OpenWiseyak-0.1-Pretraining)              |
| Wiseyak-SFT-Mixed-ne-en              | -                       | Wiseyak               | [HF](https://huggingface.co/datasets/Wiseyak/Wiseyak-SFT-Mixed-ne-en)                  |

#### Large Curated (100MB-1GB)


| Dataset                     | Size               | Description    | Link                                                                                                                |
| --------------------------- | ------------------ | -------------- | ------------------------------------------------------------------------------------------------------------------- |
| Nepali News Dataset         | 6,800+ articles    | With metadata  | [Kaggle](https://www.kaggle.com/lotusacharya/nepalinewsdataset)                                                     |
| Nepali Wikipedia Articles   | 39,000+ articles   | Wikipedia dump | [Kaggle](https://www.kaggle.com/disisbig/nepali-wikipedia-articles)                                                 |
| np20ng (20 Newsgroup)       | 200,000+ documents | 20 categories  | [HF](https://huggingface.co/datasets/Suyogyart/np20ng)                                                              |
| Nepali News Dataset (Large) | 25,000+ articles   | 10+ categories | [Kaggle](https://www.kaggle.com/ashokpant/nepali-news-dataset-large)                                                |
| Nagarik News Corpus         | -                  | News           | [GitHub](https://github.com/ashmitbhattarai/Nepali-Language-Modeling-Using-LSTM/tree/master/Nepali_Corpus/Nagarik)  |
| Setopati News Corpus        | -                  | News           | [GitHub](https://github.com/ashmitbhattarai/Nepali-Language-Modeling-Using-LSTM/tree/master/Nepali_Corpus/SetoPati) |


#### Specialized


| Dataset                        | Size               | Domain                   | Link                                                                                 |
| ------------------------------ | ------------------ | ------------------------ | ------------------------------------------------------------------------------------ |
| Digitized Nepali Textbooks     | OCR'd textbooks    | Formal register          | [HF](https://huggingface.co/datasets/dineshkarki/nepali-textbooks-corpus)            |
| Nepali Lyrics Dataset          | 5,000+ lyrics      | Music domain             | [Kaggle](https://www.kaggle.com/datasets/sanjay05kc/nepali-lyrics)                   |
| 65K Nepali Sentences           | 65,000 sentences   | General                  | [GitHub](https://github.com/sanjaalcorps/NepaliDataSets)                             |
| 350K Nepali Sentences          | 350,000 sentences  | General                  | [GitHub](https://github.com/Team-Naya/nlp-doko)                                      |
| Laxmi Prasad Devkota Poems     | 119,161 characters | Literary                 | [GitHub](https://github.com/devkotasawal1/Poem-Generator/blob/master/lspd.txt)       |
| Nepali Ukhaan Tukka (Proverbs) | -                  | Proverbs                 | [GitHub](https://github.com/theseekersway/Nepali-Ukhaan-Tukka)                       |
| Nepali Ngram                   | -                  | N-grams                  | [GitHub](https://github.com/virtualanup/nepalingram)                                 |
| Nepali Chat Corpus             | -                  | Chat/conversational      | [GitHub](https://github.com/itsmeashutosh43/create-a-Open-Source-Nepali-Chat-corpus) |
| English News Corpus (Nepal)    | -                  | English news about Nepal | [GitHub](https://github.com/sharad461/english-corpus-nepal)                          |
| Nepal Earthquake Tweets        | -                  | Social media (disaster)  | [CrisisNLP](https://crisisnlp.qcri.org/lrec2016/content/2015_nepal_eq.html)          |


### Fine-tuning Datasets

#### Text Classification


| Dataset                                    | Size               | Categories                   | Link                                                                                                         |
| ------------------------------------------ | ------------------ | ---------------------------- | ------------------------------------------------------------------------------------------------------------ |
| 16NepaliNews Corpus                        | \~14,364 documents | 16 categories                | [GitHub](https://github.com/sndsabin/Nepali-News-Classifier)                                                 |
| iNLTK Nepali News Dataset                  | 8,000+ articles    | 5 categories                 | [Kaggle](https://www.kaggle.com/disisbig/nepali-news-dataset)                                                |
| Nepali News Dataset                        | 6,800+ articles    | With metadata                | [Kaggle](https://www.kaggle.com/lotusacharya/nepalinewsdataset)                                              |
| Nepali News Classification Dataset         | -                  | -                            | [Google Drive](https://drive.google.com/drive/folders/1Vm0UJ3FfWP-3guSan3FZsOV4q7rYuJIG)                     |
| Nepali News Datasets (Small)               | 3,000+ articles    | -                            | [Kaggle](https://www.kaggle.com/tejshahi/20nepalinews)                                                       |
| Prasta Dataset                             | -                  | Question type classification | [Kaggle](https://www.kaggle.com/datasets/sangamthapa/prasta)                                                 |
| Nepali Factoid Questions Intent Classified | 500+ samples       | Intent detection             | [Kaggle](https://www.kaggle.com/datasets/sushiltimilsina/nepali-factoid-questions-intent-classified-dataset) |


#### Question Answering


| Dataset                      | Size                 | Type                   | Domain          | Link                                                                                                     |
| ---------------------------- | -------------------- | ---------------------- | --------------- | -------------------------------------------------------------------------------------------------------- |
| Nepali Health Q&amp;A Corpus | 3,000+ Q&amp;A pairs | -                      | Medical         | [Kaggle](https://www.kaggle.com/datasets/thedevastator/nepali-health-q-a-corpus)                         |
| Pregnancy Related Q&amp;A    | 1,500+ pairs         | -                      | Maternal health | [Kaggle](https://www.kaggle.com/datasets/poudelsujan03/pregnancy-related-question-answer-nepali-dataset) |
| Nepali Health Forum Corpus   | 2,500+ Q&amp;A       | With user interactions | Medical         | [Kaggle](https://www.kaggle.com/datasets/rxnach/nepali-health-forum-corpus-questions-and-answers)        |
| Nepali QA Dataset (Yunika)   | 266 pairs            | Extractive             | -               | [HF](https://huggingface.co/datasets/Yunika/Nepali-QA)                                                   |


#### Summarization


| Dataset                                 | Size                     | Type                | Link                                                                                    |
| --------------------------------------- | ------------------------ | ------------------- | --------------------------------------------------------------------------------------- |
| Nepali News Article with Summary        | 286,000+ pairs           | Headline generation | [Kaggle](https://www.kaggle.com/datasets/adarsh203/nepali-news-article-with-summary)    |
| Nepali text summarization               | 1,000+ pairs             | Abstractive         | [Kaggle](https://www.kaggle.com/datasets/imageinfo/nepali-text-summarization)           |
| Nepali Abstractive Summarization Corpus | 286k article-title pairs | Abstractive         | [Google Drive](https://drive.google.com/file/d/1L56k0zonMk6XpelKAXPm45wCmt-9pS3x/view)  |
| Sentence Compression Nepali             | 5,000+ pairs             | Extractive          | [Kaggle](https://www.kaggle.com/datasets/sbastola73/sentence-compression-nepali)        |
| Policy Documents and Summaries          | 500+ documents           | Domain-specific     | [Kaggle](https://www.kaggle.com/datasets/greenspaghetti/policy-documents-and-summaries) |


#### Named Entity Recognition (NER)


| Dataset                                     | Size              | Entity Types                | Link                                                                                                       |
| ------------------------------------------- | ----------------- | --------------------------- | ---------------------------------------------------------------------------------------------------------- |
| EverestNER                                  | 50,000+ sentences | 8 types                     | [Kaggle](https://www.kaggle.com/datasets/jeevanchapagain/everestner)                                       |
| DanfeNER                                    | 25,000+ sentences | Geographical &amp; cultural | [Kaggle](https://www.kaggle.com/datasets/jeevanchapagain/danfener)                                         |
| Nepali NER (Ebiquity v2)                    | -                 | PER, ORG, LOC               | [GitHub](https://github.com/oya163/nepali-ner/tree/master/data/ebiquity_v2)                                |
| Nepali NER Dataset (dadelani)               | -                 | Multi-token entities        | [GitHub](https://github.com/dadelani/nepali-ner)                                                           |
| Nepali Offensive Language NER and Sentiment | 5,000+ samples    | Dual annotations            | [Kaggle](https://www.kaggle.com/datasets/merishnasuwal/offensive-language-ner-and-sentiment-analysis-data) |


#### Sentiment Analysis


| Dataset                                            | Size           | Type                               | Domain | Link                                                                                                    |
| -------------------------------------------------- | -------------- | ---------------------------------- | ------ | ------------------------------------------------------------------------------------------------------- |
| NepaliSentiment                                    | -              | With preprocessing &amp; baselines | -      | [GitHub](https://github.com/rockerritesh/NepaliSentiment)                                               |
| Nepali Sentiment Analysis                          | -              | Binary classification              | -      | [Kaggle](https://www.kaggle.com/datasets/aayamoza/nepali-sentiment-analysis)                            |
| Nepali Language Sentiment Analysis - Movie Reviews | 2,500+ reviews | Star ratings                       | Film   | [Kaggle](https://www.kaggle.com/shikharghimire/nepali-language-sentiment-analysis-movie-reviews)        |
| Nepali Luxury Hotel Reviews                        | 4,000+ reviews | Aspect-based                       | Hotel  | [Kaggle](https://www.kaggle.com/datasets/suprapandey/nepali-luxury-hotel-reviews-2024)                  |
| XLSum-Nepali                                       | -              | Summarization + sentiment          | -      | [HF](https://huggingface.co/datasets/sanjeev-bhandari01/XLSum-nepali)                                   |
| Nepali Data Set for Sentiment Analysis             | -              | -                                  | -      | [Mahesha](https://mahesha.com.np/nepali-data-set-for-sentiment-analysis/)                               |
| Sentiment Analysis in Nepali                       | -              | -                                  | -      | [GitHub](https://github.com/sarozz/Sentiment_analysis_in_Nepali/blob/master/data.csv)                   |
| SentimentAnalysis                                  | -              | -                                  | -      | [GitHub](https://github.com/sagarl123/NepaliNLP-SentimentAnalysis/blob/main/collected_labeled_data.csv) |


#### Hate Speech &amp; Offensive Language


| Dataset                                    | Size           | Type                         | Platform     | Link                                                                                                        |
| ------------------------------------------ | -------------- | ---------------------------- | ------------ | ----------------------------------------------------------------------------------------------------------- |
| Nepali Hate Speech Collection              | 5,000+ samples | Annotated                    | Social media | [Kaggle](https://www.kaggle.com/datasets/mohanbhandari/nepali-hate-speech-collection)                       |
| Nepali Offensive Language Detection        | -              | Detection tooling            | -            | [GitHub](https://github.com/merishnaSuwal/nep-off-langdetect)                                               |
| Nepali Abusive Language NER and Sentiment  | -              | Multi-task                   | Abusive text | [Kaggle](https://www.kaggle.com/datasets/merishnasuwal/offensive-language-ner-and-sentiment-analysis-data)  |
| NepCov19Tweets                             | 10,000+ tweets | Emotion labels               | Twitter      | [Kaggle](https://www.kaggle.com/datasets/mathew11111/nepcov19tweets)                                        |
| Mpox Instagram Sentiment and Hate Analysis | 3,000+ posts   | Dual sentiment + hate labels | Instagram    | [Kaggle](https://www.kaggle.com/datasets/thakurnirmalya/mpox-instagram-dataset-sentiment-and-hate-analysis) |


### Translation &amp; Parallel Data

#### Large-Scale Parallel Corpora


| Dataset                                               | Size            | Language Pair | Link                                                                        |
| ----------------------------------------------------- | --------------- | ------------- | --------------------------------------------------------------------------- |
| English-Nepali Parallel Corpus (Kathmandu University) | 1,800,000 pairs | EN-NE         | [ELRA W0077](https://catalog.elra.info/en-us/repository/browse/ELRA-W0077/) |
| Kathmandu University English-Nepali Corpus            | 1.8M pairs      | EN-NE         | [AI4Bharat](https://github.com/AI4Bharat/indicnlp_catalog)                  |


#### Medium-Scale Corpora


| Dataset                                  | Size           | Language Pair            | Link                                                                                                     |
| ---------------------------------------- | -------------- | ------------------------ | -------------------------------------------------------------------------------------------------------- |
| Nepali-English language pair             | 40,000+ pairs  | EN-NE                    | [GitHub](https://github.com/sharad461/nepali-translator)                                                 |
| Hindi-Nepali Parallel Corpus (Noisy)     | 500,000+ pairs | HI-NE                    | [Kaggle](https://www.kaggle.com/datasets/thenepaliguy/final-hi-ne)                                       |
| Hindi-Nepali Evaluation Corpus (Clean)   | 50,000+ pairs  | HI-NE                    | [Kaggle](https://www.kaggle.com/datasets/thenepaliguy/cleanhindinepali)                                  |
| Urdu-Nepali Parallel Corpus              | 100,000+ pairs | UR-NE                    | [Kaggle](https://www.kaggle.com/datasets/rtatman/urdunepali-parallel-corpus)                             |
| English to Nepali Translation            | -              | EN-NE                    | [GitHub](https://github.com/arunism/English-to-Nepali-Language-Translation/tree/master/data)             |
| Nepali-English Translation Dataset       | -              | EN-NE                    | [GitHub](https://github.com/BISHALTWR/Nepali-English-Translation-Dataset)                                |
| Nepali Translation Parallel Corpus       | -              | EN-NE                    | [Google Drive](https://drive.google.com/file/d/1UThfJKJFvDgTu263DNbz-WPNLqoARZ_0/view)                   |
| English-Nepali Translated Strings (TDIL) | -              | UI/software localization | [TDIL-DC](https://tdil-dc.in/index.php?option=com_download&task=showresourceDetails&toolid=1069&lang=en) |


#### Multilingual &amp; Specialized


| Dataset                         | Size              | Languages | Domain            | Link                                                                                 |
| ------------------------------- | ----------------- | --------- | ----------------- | ------------------------------------------------------------------------------------ |
| Trilingual Hindi-English-Nepali | 200,000+ triples  | HI-EN-NE  | -                 | [Kaggle](https://www.kaggle.com/datasets/sundeepdawadi/cleaned-word2word-en-hi-ne)   |
| English-Nepali Translation (HF) | -                 | EN-NE     | Instruction-tuned | [HF](https://huggingface.co/datasets/ashokpoudel/nepali-english-translation-dataset) |
| Bidirectional EN-NE MT (Legal)  | 125,000 sentences | EN-NE     | Legal             | [ACL Paper](https://aclanthology.org/2024.sigul-1.7.pdf)                             |
| CLE Parallel Corpus             | -                 | EN-NE-UR  | -                 | [AI4Bharat](https://github.com/AI4Bharat/indicnlp_catalog)                           |


#### Historical &amp; Shared Tasks


| Dataset               | Event                  | Link                                                                         |
| --------------------- | ---------------------- | ---------------------------------------------------------------------------- |
| WMT19 Parallel Corpus | Shared task            | [statmt.org](https://www.statmt.org/wmt19/parallel-corpus-filtering.html)    |
| FLORES 101 Dataset    | Multilingual benchmark | [GitHub](https://github.com/facebookresearch/flores/tree/main/floresv1/data) |


### Instruction Tuning


| Dataset     | Languages                       | Type               | Link                                                     |
| ----------- | ------------------------------- | ------------------ | -------------------------------------------------------- |
| Bactrian-X  | 50+ languages (includes Nepali) | Instruction tuning | [HF](https://huggingface.co/datasets/MBZUAI/Bactrian-X)  |
| Aya Dataset | 101 languages (includes Nepali) | Instruction tuning | [HF](https://huggingface.co/datasets/cohere/aya_dataset) |


### Benchmarks &amp; Evaluation


| Benchmark                                       | Tasks                                                                                  | Link                                                        |
| ----------------------------------------------- | -------------------------------------------------------------------------------------- | ----------------------------------------------------------- |
| NLUE (Nepali Language Understanding Evaluation) | 9 classification + 3 structural prediction (sentiment, hate speech, toxicity, QA, NER) | [arXiv](https://arxiv.org/abs/2411.19244)                   |
| Nep-gLUE Benchmark                              | 7 NLU tasks (GLUE-style)                                                               | Limited access; use NLUE alternative                        |
| FLORES-101                                      | Machine translation evaluation                                                         | [GitHub](https://github.com/facebookresearch/flores)        |
| IndicBench                                      | 13 tasks across Indic languages                                                        | [New 2025](https://ai4bharat.github.io/indicnlp_catalog/)   |
| SemEval 2026 Task 9                             | Polarization type classification                                                       | [Codabench](https://www.codabench.org/competitions/10669/)  |
| Google FLEURS                                   | Multilingual benchmark                                                                 | [HF Dataset](https://huggingface.co/datasets/google/fleurs) |


### Pre-trained Models &amp; Embeddings

#### Large Language Models


| Model                                | Parameters  | Training Data              | Link                                                                               |
| ------------------------------------ | ----------- | -------------------------- | ---------------------------------------------------------------------------------- |
| IRIISNEPAL RoBERTa                   | 110M params | 27.5 GB from 99 news sites | [HF](https://huggingface.co/IRIISNEPAL/RoBERTa_Nepali_110M)                        |
| NepaliBERT                           | -           | 4.6 GB, 85k+ articles      | [HF](https://huggingface.co/Shushant/nepaliBERT)                                   |
| DistilGPT2-Nepali                    | -           | 13M Nepali sequences       | [HF](https://huggingface.co/Sakonii/distilgpt2-nepali)                             |
| Nepali Text Generation (Transformer) | -           | Custom                     | [GitHub](https://github.com/NirajanBekoju/Transformer-Based-Nepali-Language-Model) |
| NepBERTa                             | -           | GLUE benchmark baseline    | [Website](https://nepberta.github.io/)                                             |
| NepaliGPT                            | -           | -                          | [arXiv](https://arxiv.org/abs/2506.16399)                                          |


#### Word Embeddings


| Embedding                    | Dimensions | Vocabulary               | Link                                                                                       |
| ---------------------------- | ---------- | ------------------------ | ------------------------------------------------------------------------------------------ |
| Nepali Word2Vec from scratch | 300D       | Custom                   | [GitHub](https://github.com/R4j4n/Nepali-Word2Vec-from-scratch)                            |
| 300D Word2Vec Embeddings     | 300D       | 20k+ words               | [GitHub](https://github.com/rabindralamsal/Word2Vec-Embeddings-for-Nepali-Language)        |
| Nepali FastText Word Vectors | -          | Common Crawl + Wikipedia | [fastText](https://github.com/facebookresearch/fastText/blob/master/docs/crawl-vectors.md) |


#### Fine-tuned Models


| Model                                 | Task                | Dataset | Link                                                                       |
| ------------------------------------- | ------------------- | ------- | -------------------------------------------------------------------------- |
| Fine-tuned DistilBERT on 16 Newsgroup | News classification | -       | [HF](https://huggingface.co/Suyogyart/nepali-16-newsgroups-classification) |


### Lexicons &amp; Linguistic Resources

#### Dictionaries &amp; Word Lists


| Resource                        | Size               | Type                       | Link                                                                                        |
| ------------------------------- | ------------------ | -------------------------- | ------------------------------------------------------------------------------------------- |
| Sabdabikash Synonym Word List   | 50,000+ words      | Thesaurus                  | [Kaggle](https://www.kaggle.com/datasets/thenepaliguy/sabdabikash-synonym-nepali-word-list) |
| Nepali Dictionary               | 25,000+ entries    | Definitions &amp; examples | [Kaggle](https://www.kaggle.com/datasets/sangamthapa/nepali-dictionary)                     |
| Nepali Stopwords                | 400+ words         | Filtering                  | [Kaggle](https://www.kaggle.com/datasets/sangamthapa/nepali-stopwords)                      |
| Nepali Brihat Sabdakosh JSON    | 122,000 words      | Comprehensive dictionary   | [GitHub](https://github.com/bikashpadhikari/nepali-brihat-sabdakosh-json)                   |
| Nepali Names                    | -                  | Person names               | [GitHub](https://github.com/datafiction/oya-nepali-nlp/blob/master/data/names/Nepali.txt)   |
| Dummy Nepali People Information | -                  | Synthetic person data      | [GitHub](https://github.com/bibhuticoder/dummydata/blob/master/data.csv)                    |
| Nepali Unigrams Cleaned         | 200k+ unique words | Vocabulary with frequency  | [Kaggle](https://www.kaggle.com/datasets/thenepaliguy/nepali-unigrams-cleaned)              |


#### Morphology &amp; Syntax


| Resource                           | Size             | Type                   | Link                                                                                                           |
| ---------------------------------- | ---------------- | ---------------------- | -------------------------------------------------------------------------------------------------------------- |
| Nepali POS Data (UPOS Mapped)      | 3,000+ sentences | POS tags (UD standard) | [Kaggle](https://www.kaggle.com/datasets/thenepaliguy/nepali-pos)                                              |
| Nepali Word-Lemma Gold Data        | 5,000+ words     | Manual lemmatization   | [GitHub](https://github.com/dpakpdl/NepaliLemmatizer/tree/master/Lemmatization/data/manually_annotated_corpus) |
| Universal Dependencies (UD) Nepali | 17,500+ tokens   | Syntactic dependencies | [GitHub](https://github.com/UniversalDependencies/UD_Nepali-NPP)                                               |


---

## 📊 Benchmarks &amp; Standards

Comprehensive evaluation frameworks and shared tasks for Nepali NLP.


| Benchmark                                       | Tasks                                                                                        | Link                                                                          |
| ----------------------------------------------- | -------------------------------------------------------------------------------------------- | ----------------------------------------------------------------------------- |
| NLUE (Nepali Language Understanding Evaluation) | 9 classification + 3 structural prediction tasks (sentiment, hate speech, toxicity, QA, NER) | [arXiv: 2411.19244](https://arxiv.org/abs/2411.19244)                         |
| Nep-gLUE Benchmark                              | Official Nepali GLUE-style benchmark (7 NLU tasks)                                           | Limited direct access; see NLUE for comprehensive alternatives                |
| FLORES-101 Evaluation Benchmark                 | Machine translation evaluation across 101 languages including Nepali                         | [GitHub: facebookresearch/flores](https://github.com/facebookresearch/flores) |
| IndicBench                                      | Benchmark for 11 Indic languages including Nepali (13 tasks)                                 | [New 2025 addition](https://ai4bharat.github.io/indicnlp_catalog/)            |
| SemEval 2026 Task 9                             | Polarization type classification with Nepali data                                            | [Codabench](https://www.codabench.org/competitions/10669/)                    |
| Google FLEURS                                   | Multilingual benchmark including Nepali (101 languages)                                      | [HF: google/fleurs](https://huggingface.co/datasets/google/fleurs)            |


---

## 📚 Text Corpora

### Ultra-Large Corpora (&gt;1GB)


| Dataset                         | Size                                         | Source                                      | Link                                                                                               |
| ------------------------------- | -------------------------------------------- | ------------------------------------------- | -------------------------------------------------------------------------------------------------- |
| Nepali-Text-Corpus (IRIISNEPAL) | 6.4M articles, 10.1 GB                       | Largest Nepali corpus from 99 news websites | [HF: IRIISNEPAL/nepali-text-corpus](https://huggingface.co/datasets/IRIISNEPAL/nepali-text-corpus) |
| OSCAR Corpus Nepali             | 3.8 GB, 100M+ sentences                      | Common Crawl                                | [Kaggle: hsebarp/oscar-corpus-nepali](https://www.kaggle.com/hsebarp/oscar-corpus-nepali)          |
| CC100-Nepali                    | Common Crawl 2019 subset, 200GB uncompressed | Foundation data for multilingual models     | [MetaText: cc100-nepali](https://metatext.io/datasets/cc100-nepali)                                |
| Lamsal (2020) Corpus            | 12M+ words                                   | Professionally compiled                     | *Note: Original DOI 404; consider IRIISNEPAL as primary substitute*                                |


### Large Curated Collections (100MB-1GB)


| Dataset                     | Size                                         | Description                                                                                               | Link                                                                     |
| --------------------------- | -------------------------------------------- | --------------------------------------------------------------------------------------------------------- | ------------------------------------------------------------------------ |
| Nepali News Dataset         | 6,800+ articles with metadata                | [Kaggle: lotusacharya/nepalinewsdataset](https://www.kaggle.com/lotusacharya/nepalinewsdataset)           |                                                                          |
| Nepali Wikipedia Articles   | 39,000+ articles from Wikipedia dump         | [Kaggle: disisbig/nepali-wikipedia-articles](https://www.kaggle.com/disisbig/nepali-wikipedia-articles)   |                                                                          |
| np20ng (20 Newsgroup)       | 200,000+ news documents across 20 categories | Adapted from English 20NG                                                                                 | [HF: Suyogyart/np20ng](https://huggingface.co/datasets/Suyogyart/np20ng) |
| Nepali News Dataset (Large) | 25,000+ articles across 10+ categories       | [Kaggle: ashokpant/nepali-news-dataset-large](https://www.kaggle.com/ashokpant/nepali-news-dataset-large) |                                                                          |


### Specialized Text Collections


| Dataset                           | Size                                     | Domain                                                                                                                       | Link                                                                                                             |
| --------------------------------- | ---------------------------------------- | ---------------------------------------------------------------------------------------------------------------------------- | ---------------------------------------------------------------------------------------------------------------- |
| Nepali Unigrams Cleaned (FineWeb) | 200k+ unique Nepali words with frequency | [Kaggle: thenepaliguy/nepali-unigrams-cleaned](https://www.kaggle.com/datasets/thenepaliguy/nepali-unigrams-cleaned)         |                                                                                                                  |
| Setopati News Dataset             | 10,000+ articles from Setopati portal    | News domain-specific                                                                                                         | [Kaggle: living0world/setopati-news-dataset](https://www.kaggle.com/datasets/living0world/setopati-news-dataset) |
| Nepali Raw Text Data              | Raw text batches for preprocessing       | [Kaggle: rajanghimire/nepali-raw-text-data-batch1](https://www.kaggle.com/datasets/rajanghimire/nepali-raw-text-data-batch1) |                                                                                                                  |
| Nepali Lyrics Dataset             | 5,000+ song lyrics with metadata         | Music domain                                                                                                                 | [Kaggle: sanjay05kc/nepali-lyrics](https://www.kaggle.com/datasets/sanjay05kc/nepali-lyrics)                     |
| Digitized Nepali Textbooks        | OCR'd school textbooks (formal register) | [HF: dineshkarki/nepali-textbooks-corpus](https://huggingface.co/datasets/dineshkarki/nepali-textbooks-corpus)               |                                                                                                                  |


---

## 🎯 NLP Datasets

### Classification Datasets

News classification, topic modeling, and text categorization.


| Dataset                                    | Size                                        | Description                                                                                                                                                                      | Link                                                                                          |
| ------------------------------------------ | ------------------------------------------- | -------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | --------------------------------------------------------------------------------------------- |
| iNLTK Nepali News Dataset                  | 8,000+ articles across 5 categories         | [Kaggle: disisbig/nepali-news-dataset](https://www.kaggle.com/disisbig/nepali-news-dataset)                                                                                      |                                                                                               |
| 16NepaliNews Corpus                        | \~14,364 documents across 16 categories     | Most comprehensive category coverage                                                                                                                                             | [GitHub: sndsabin/Nepali-News-Classifier](https://github.com/sndsabin/Nepali-News-Classifier) |
| Nepali News Datasets (Small)               | 3,000+ articles                             | Good for quick prototyping                                                                                                                                                       | [Kaggle: tejshahi/20nepalinews](https://www.kaggle.com/tejshahi/20nepalinews)                 |
| Prasta Dataset                             | Question type classification for QA systems | [Kaggle: sangamthapa/prasta](https://www.kaggle.com/datasets/sangamthapa/prasta)                                                                                                 |                                                                                               |
| Nepali Factoid Questions Intent Classified | 500+ samples for intent detection           | [Kaggle: sushiltimilsina/nepali-factoid-questions-intent-classified-dataset](https://www.kaggle.com/datasets/sushiltimilsina/nepali-factoid-questions-intent-classified-dataset) |                                                                                               |


### Named Entity Recognition (NER) Datasets

Annotated datasets for entity recognition (person, organization, location, etc.).


| Dataset                                     | Size                                                                   | Description                                                                                                                                                                  | Link                                                                                             |
| ------------------------------------------- | ---------------------------------------------------------------------- | ---------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ------------------------------------------------------------------------------------------------ |
| EverestNER                                  | 50,000+ annotated sentences, 8 entity types                            | Largest NER dataset                                                                                                                                                          | [Kaggle: jeevanchapagain/everestner](https://www.kaggle.com/datasets/jeevanchapagain/everestner) |
| DanfeNER                                    | 25,000+ sentences covering Nepali geographical &amp; cultural entities | [Kaggle: jeevanchapagain/danfener](https://www.kaggle.com/datasets/jeevanchapagain/danfener)                                                                                 |                                                                                                  |
| Nepali NER (Ebiquity v2)                    | Benchmark dataset with 3 entity types (PER, ORG, LOC)                  | [GitHub: oya163/nepali-ner/data/ebiquity\_v2](https://github.com/oya163/nepali-ner/tree/master/data/ebiquity_v2)                                                             |                                                                                                  |
| Nepali NER Dataset (dadelani)               | Annotated for multi-token entities                                     | [GitHub: dadelani/nepali-ner](https://github.com/dadelani/nepali-ner)                                                                                                        |                                                                                                  |
| Nepali Offensive Language NER and Sentiment | 5,000+ samples with dual annotations (NER + sentiment)                 | [Kaggle: merishnasuwal/offensive-language-ner-and-sentiment-analysis-data](https://www.kaggle.com/datasets/merishnasuwal/offensive-language-ner-and-sentiment-analysis-data) |                                                                                                  |


### Sentiment Analysis &amp; Hate Speech Datasets

Social media, news, and online text with sentiment/toxicity annotations.

#### Sentiment Analysis


| Dataset                                            | Size                                             | Description                                                                                                      | Link                                                                                                                                                              |
| -------------------------------------------------- | ------------------------------------------------ | ---------------------------------------------------------------------------------------------------------------- | ----------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| NepaliSentiment                                    | GitHub corpus with preprocessing &amp; baselines | [GitHub: rockerritesh/NepaliSentiment](https://github.com/rockerritesh/NepaliSentiment)                          |                                                                                                                                                                   |
| Nepali Sentiment Analysis                          | Binary classification (positive/negative)        | [Kaggle: aayamoza/nepali-sentiment-analysis](https://www.kaggle.com/datasets/aayamoza/nepali-sentiment-analysis) |                                                                                                                                                                   |
| Nepali Language Sentiment Analysis - Movie Reviews | 2,500+ reviews with star ratings                 | Domain-specific (film)                                                                                           | [Kaggle: shikharghimire/nepali-language-sentiment-analysis-movie-reviews](https://www.kaggle.com/shikharghimire/nepali-language-sentiment-analysis-movie-reviews) |
| Nepali Luxury Hotel Reviews                        | 4,000+ reviews with aspect-based sentiment       | Hotel domain                                                                                                     | [Kaggle: suprapandey/nepali-luxury-hotel-reviews-2024](https://www.kaggle.com/datasets/suprapandey/nepali-luxury-hotel-reviews-2024)                              |
| XLSum-Nepali                                       | Summarization + sentiment                        | [HF: sanjeev-bhandari01/XLSum-nepali](https://huggingface.co/datasets/sanjeev-bhandari01/XLSum-nepali)           |                                                                                                                                                                   |


#### Hate Speech &amp; Offensive Language


| Dataset                                                    | Size                                                     | Description                                                                                                                                                                  | Link                                                                                                                                                                           |
| ---------------------------------------------------------- | -------------------------------------------------------- | ---------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ |
| Nepali Hate Speech Collection                              | 5,000+ annotated samples from social media               | [Kaggle: mohanbhandari/nepali-hate-speech-collection](https://www.kaggle.com/datasets/mohanbhandari/nepali-hate-speech-collection)                                           |                                                                                                                                                                                |
| Nepali Offensive Language Detection and Sentiment Analysis | Offensive language detection tooling                     | [GitHub: merishnaSuwal/nep-off-langdetect](https://github.com/merishnaSuwal/nep-off-langdetect)                                                                              |                                                                                                                                                                                |
| Nepali Abusive Language NER and Sentiment Analysis         | Multi-task dataset (NER + sentiment on abusive text)     | [Kaggle: merishnasuwal/offensive-language-ner-and-sentiment-analysis-data](https://www.kaggle.com/datasets/merishnasuwal/offensive-language-ner-and-sentiment-analysis-data) |                                                                                                                                                                                |
| NepCov19Tweets                                             | 10,000+ COVID-19 tweets with emotion labels              | Social media (Twitter)                                                                                                                                                       | [Kaggle: mathew11111/nepcov19tweets](https://www.kaggle.com/datasets/mathew11111/nepcov19tweets)                                                                               |
| Mpox Instagram Sentiment and Hate Analysis                 | 3,000+ Instagram posts with dual sentiment + hate labels | Health + social media                                                                                                                                                        | [Kaggle: thakurnirmalya/mpox-instagram-dataset-sentiment-and-hate-analysis](https://www.kaggle.com/datasets/thakurnirmalya/mpox-instagram-dataset-sentiment-and-hate-analysis) |


### Question Answering (QA) Datasets

Extractive, generative, and domain-specific QA datasets.


| Dataset                           | Size                                                     | Description                                                                                                                                                              | Link                                                                     |
| --------------------------------- | -------------------------------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------ | ------------------------------------------------------------------------ |
| Nepali Health Q&amp;A Corpus      | 3,000+ Q&amp;A pairs from health forums (medical domain) | [Kaggle: thedevastator/nepali-health-q-a-corpus](https://www.kaggle.com/datasets/thedevastator/nepali-health-q-a-corpus)                                                 |                                                                          |
| Pregnancy Related Question Answer | 1,500+ pairs on maternal health (specialty medical)      | [Kaggle: poudelsujan03/pregnancy-related-question-answer-nepali-dataset](https://www.kaggle.com/datasets/poudelsujan03/pregnancy-related-question-answer-nepali-dataset) |                                                                          |
| Nepali Health Forum Corpus        | 2,500+ Q&amp;A from health forums with user interactions | [Kaggle: rxnach/nepali-health-forum-corpus-questions-and-answers](https://www.kaggle.com/datasets/rxnach/nepali-health-forum-corpus-questions-and-answers)               |                                                                          |
| Nepali QA Dataset (Yunika)        | 266 extractive QA pairs with passage context             | HuggingFace format                                                                                                                                                       | [HF: Yunika/Nepali-QA](https://huggingface.co/datasets/Yunika/Nepali-QA) |


### Summarization Datasets

Abstractive &amp; extractive summarization, headline generation.


| Dataset                          | Size                                                                | Description                                                                                                                            | Link                                                                                                                             |
| -------------------------------- | ------------------------------------------------------------------- | -------------------------------------------------------------------------------------------------------------------------------------- | -------------------------------------------------------------------------------------------------------------------------------- |
| Nepali text summarization        | 1,000+ document-summary pairs                                       | Abstractive task                                                                                                                       | [Kaggle: imageinfo/nepali-text-summarization](https://www.kaggle.com/datasets/imageinfo/nepali-text-summarization)               |
| Nepali News Article with Summary | 286,000+ news headlines + articles                                  | Largest summarization resource (headline generation)                                                                                   | [Kaggle: adarsh203/nepali-news-article-with-summary](https://www.kaggle.com/datasets/adarsh203/nepali-news-article-with-summary) |
| Sentence Compression Nepali      | 5,000+ sentence pairs for text compression (extractive)             | [Kaggle: sbastola73/sentence-compression-nepali](https://www.kaggle.com/datasets/sbastola73/sentence-compression-nepali)               |                                                                                                                                  |
| Policy Documents and Summaries   | 500+ policy documents with professional summaries (domain-specific) | [Kaggle: greenspaghetti/policy-documents-and-summaries](https://www.kaggle.com/datasets/greenspaghetti/policy-documents-and-summaries) |                                                                                                                                  |


---

## 🔤 Translation &amp; Parallel Data

Parallel corpora for machine translation and low-resource language pairs.

### Large-Scale Parallel Corpora


| Dataset                                               | Size                     | Description                | Link                                                                          |
| ----------------------------------------------------- | ------------------------ | -------------------------- | ----------------------------------------------------------------------------- |
| English-Nepali Parallel Corpus (Kathmandu University) | 1,800,000 sentence pairs | Gold standard for EN-NE MT | [ELRA: W0077](https://catalog.elra.info/en-us/repository/browse/ELRA-W0077/)  |
| Kathmandu University English-Nepali Corpus            | 1.8M sentence pairs      | Direct source confirmation | [AI4Bharat: indicnlp\_catalog](https://github.com/AI4Bharat/indicnlp_catalog) |


### Medium-Scale Corpora


| Dataset                                | Size                                                     | Description                                                                                            | Link                                                                                                             |
| -------------------------------------- | -------------------------------------------------------- | ------------------------------------------------------------------------------------------------------ | ---------------------------------------------------------------------------------------------------------------- |
| Nepali-English language pair           | 40,000+ parallel sentence pairs with preprocessing code  | [GitHub: sharad461/nepali-translator](https://github.com/sharad461/nepali-translator)                  |                                                                                                                  |
| Hindi-Nepali Parallel Corpus (Noisy)   | 500,000+ sentence pairs (unfiltered)                     | [Kaggle: thenepaliguy/final-hi-ne](https://www.kaggle.com/datasets/thenepaliguy/final-hi-ne)           |                                                                                                                  |
| Hindi-Nepali Evaluation Corpus (Clean) | 50,000+ high-quality sentence pairs (manually validated) | [Kaggle: thenepaliguy/cleanhindinepali](https://www.kaggle.com/datasets/thenepaliguy/cleanhindinepali) |                                                                                                                  |
| Urdu-Nepali Parallel Corpus            | 100,000+ sentence pairs                                  | Underrepresented language pair                                                                         | [Kaggle: rtatman/urdunepali-parallel-corpus](https://www.kaggle.com/datasets/rtatman/urdunepali-parallel-corpus) |


### Multilingual &amp; Specialized


| Dataset                                          | Size                                         | Description                                                                                                                          | Link                                                                                                                         |
| ------------------------------------------------ | -------------------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------ | ---------------------------------------------------------------------------------------------------------------------------- |
| Trilingual Hindi-English-Nepali                  | 200,000+ aligned triples                     | Multilingual MT resource                                                                                                             | [Kaggle: sundeepdawadi/cleaned-word2word-en-hi-ne](https://www.kaggle.com/datasets/sundeepdawadi/cleaned-word2word-en-hi-ne) |
| English-Nepali Translation (HF)                  | Instruction-tuned format for LLM fine-tuning | [HF: ashokpoudel/nepali-english-translation-dataset](https://huggingface.co/datasets/ashokpoudel/nepali-english-translation-dataset) |                                                                                                                              |
| Bidirectional English-Nepali MT for Legal Domain | 125,000 legal sentences                      | Domain-specific (legal)                                                                                                              | [ACL: 2024.sigul-1.7](https://aclanthology.org/2024.sigul-1.7.pdf)                                                           |
| CLE Parallel Corpus (AI4Bharat)                  | English-Nepali-Urdu triplets                 | Multilingual training                                                                                                                | [GitHub: AI4Bharat/indicnlp\_catalog](https://github.com/AI4Bharat/indicnlp_catalog)                                         |


### Historical &amp; Shared Tasks


| Dataset                             | Description                                 | Link                                                                            |
| ----------------------------------- | ------------------------------------------- | ------------------------------------------------------------------------------- |
| WMT19 Parallel Corpus               | Shared task corpus with filtering challenge | [statmt.org/wmt19](https://www.statmt.org/wmt19/parallel-corpus-filtering.html) |
| English - Nepali translated strings | UI/software localization strings            | *Note: Original link 503; alternative via TDIL-DC not direct—use ELRA above*    |


---

## 🎤 Speech &amp; Audio Datasets

Audio data for automatic speech recognition and text-to-speech synthesis.

### Large-Scale ASR


| Dataset                                       | Size                                                       | Description                                                                                                                        | Link                                                                               |
| --------------------------------------------- | ---------------------------------------------------------- | ---------------------------------------------------------------------------------------------------------------------------------- | ---------------------------------------------------------------------------------- |
| OpenSLR-54 (Large Nepali ASR)                 | 157,000 utterances, 400+ hours                             | Google-supported, professional quality                                                                                             | [openslr.org/54](https://www.openslr.org/54/)                                      |
| Mozilla Common Voice (Nepali)                 | Crowdsourced speech, 100k+ clips available                 | Diverse speakers                                                                                                                   | [commonvoice.mozilla.org/en/datasets](https://commonvoice.mozilla.org/en/datasets) |
| Nepali Speech to Text Dataset (Parliamentary) | 1,000+ utterances from Parliament sessions (formal speech) | [Kaggle: ishworsubedii/nepali-speech-to-text-dataset](https://www.kaggle.com/datasets/ishworsubedii/nepali-speech-to-text-dataset) |                                                                                    |
| Nepali Automatic Speech Recognition (HF)      | Combined ASR dataset for transcription                     | [HF: amitpant7/Nepali-Automatic-Speech-Recognition](https://huggingface.co/amitpant7/Nepali-Automatic-Speech-Recognition)          |                                                                                    |
| ASR Nepali 1 Large                            | 50,000+ audio files with transcriptions                    | [Kaggle: sonismaharjan/asr-nepali-1-large](https://www.kaggle.com/datasets/sonismaharjan/asr-nepali-1-large)                       |                                                                                    |


### TTS &amp; Synthesized Speech


| Dataset                       | Size                                                      | Description                                                                                                        | Link                                          |
| ----------------------------- | --------------------------------------------------------- | ------------------------------------------------------------------------------------------------------------------ | --------------------------------------------- |
| OpenSLR-43 (High quality TTS) | High-quality single-speaker TTS data                      | Professional recording                                                                                             | [openslr.org/43](https://www.openslr.org/43/) |
| Nepali Singing Voice Data     | Audio + lyrics for singing voice synthesis (music domain) | [Kaggle: pujancozu/nepali-singing-voice-data](https://www.kaggle.com/datasets/pujancozu/nepali-singing-voice-data) |                                               |


### Speech Analysis &amp; Emotion


| Dataset                         | Size                                                     | Description                                                                                                                                        | Link |
| ------------------------------- | -------------------------------------------------------- | -------------------------------------------------------------------------------------------------------------------------------------------------- | ---- |
| Nepali Speech Emotion Detection | 3,000+ speech samples with 6 emotion labels              | [Kaggle: ashalupreti/nepali-speech-emotion-detection-dataset](https://www.kaggle.com/datasets/ashalupreti/nepali-speech-emotion-detection-dataset) |      |
| Newari Music Classification     | Audio classification for Newari (related language) music | [Kaggle: pujancozu/newari-music](https://www.kaggle.com/datasets/pujancozu/newari-music)                                                           |      |


### Multilingual Benchmarks


| Dataset       | Description                                             | Link                                                               |
| ------------- | ------------------------------------------------------- | ------------------------------------------------------------------ |
| Google FLEURS | Multilingual benchmark including Nepali (101 languages) | [HF: google/fleurs](https://huggingface.co/datasets/google/fleurs) |


---

## 🖼️ Computer Vision Datasets

Datasets for image/video captioning, object detection, and multimodal learning.

### Sign Language &amp; Gesture


| Dataset                                     | Size                                                            | Description               | Link                                                                                                                                                       |
| ------------------------------------------- | --------------------------------------------------------------- | ------------------------- | ---------------------------------------------------------------------------------------------------------------------------------------------------------- |
| Nepali Sign Language Character Dataset      | 36 characters × 1,000 images = 36,000 total                     | Sign language recognition | [Kaggle: biratpoudelrocks/nepali-sign-language-character-dataset](https://www.kaggle.com/datasets/biratpoudelrocks/nepali-sign-language-character-dataset) |
| Nepali Sign Language Video Dataset (Zenodo) | 630 professional videos (1,205 gestures with frame annotations) | Research-grade            | [Zenodo: 10478554](https://zenodo.org/records/10478554)                                                                                                    |


### Image Captioning &amp; Multimodal


| Dataset                        | Size                                               | Description                   | Link                                                                                                                                                     |
| ------------------------------ | -------------------------------------------------- | ----------------------------- | -------------------------------------------------------------------------------------------------------------------------------------------------------- |
| Flickr8k Nepali Captioning     | 8,000 images × 5 Nepali captions = 40,000 captions | Adapted from Flickr8k English | [GitHub: bipeshrajsubedi/Flickr8k\_Nepali\_Dataset](https://github.com/bipeshrajsubedi/Flickr8k_Nepali_Dataset)                                          |
| Nepali Video Captioning (MSVD) | 1,500+ videos with Nepali descriptions             | Video captioning task         | [Kaggle: kabitaparajuli/video-captioning-in-nepali-msvd-dataset](https://www.kaggle.com/datasets/kabitaparajuli/video-captioning-in-nepali-msvd-dataset) |


### Face Recognition &amp; Emotion


| Dataset                                           | Size                                             | Description                      | Link                                                                                                                                                                       |
| ------------------------------------------------- | ------------------------------------------------ | -------------------------------- | -------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| Nepali Celeb Localized Face Dataset               | 500+ Nepali celebrities with face bounding boxes | Face detection &amp; recognition | [GitHub: amitpant7/Nepali-Celeb-Localized-Face-Dataset](https://github.com/amitpant7/Nepali-Celeb-Localized-Face-Dataset)                                                  |
| Facial Emotion Detection for Nepali Ethnic Groups | 6,000+ facial images with 7 emotion labels       | Culturally-specific dataset      | [Kaggle: suchanasubedi/facial-emotion-detection-for-nepali-ethnic-groups](https://www.kaggle.com/datasets/suchanasubedi/facial-emotion-detection-for-nepali-ethnic-groups) |


### Domain-Specific Objects


| Dataset                             | Size                                                  | Description                          | Link                                                                                                                                             |
| ----------------------------------- | ----------------------------------------------------- | ------------------------------------ | ------------------------------------------------------------------------------------------------------------------------------------------------ |
| Nepali Currency Dataset             | 5,000+ currency note images                           | Banknote denomination classification | [Kaggle: uashutoshk/nepali-currency-dataset](https://www.kaggle.com/datasets/uashutoshk/nepali-currency-dataset)                                 |
| Nepali Food Images                  | 3,000+ images of traditional Nepali dishes            | Food recognition domain              | [Kaggle: saurabkunwar/nepali-food-images](https://www.kaggle.com/datasets/saurabkunwar/nepali-food-images)                                       |
| Nepali Cultural Dress and Ornaments | 2,000+ images of traditional clothing &amp; artifacts | Cultural heritage                    | [Kaggle: bimarshakhanal/nepali-cultural-dress-and-ornaments](https://www.kaggle.com/datasets/bimarshakhanal/nepali-cultural-dress-and-ornaments) |


---

## 📝 Lexicons, Linguistics &amp; Resources

Linguistic resources, dictionaries, and instruction-tuned datasets.

### Dictionaries &amp; Word Lists


| Resource                      | Size                                                             | Description                                                                                                                                    | Link |
| ----------------------------- | ---------------------------------------------------------------- | ---------------------------------------------------------------------------------------------------------------------------------------------- | ---- |
| Sabdabikash Synonym Word List | 50,000+ Nepali words with synonyms (thesaurus)                   | [Kaggle: thenepaliguy/sabdabikash-synonym-nepali-word-list](https://www.kaggle.com/datasets/thenepaliguy/sabdabikash-synonym-nepali-word-list) |      |
| Nepali Dictionary             | 25,000+ entries with definitions &amp; examples                  | [Kaggle: sangamthapa/nepali-dictionary](https://www.kaggle.com/datasets/sangamthapa/nepali-dictionary)                                         |      |
| Nepali Stopwords              | 400+ common words for filtering                                  | [Kaggle: sangamthapa/nepali-stopwords](https://www.kaggle.com/datasets/sangamthapa/nepali-stopwords)                                           |      |
| Nepali Brihat Sabdakosh JSON  | 122,000 words from comprehensive Nepali dictionary (JSON format) | [GitHub: bikashpadhikari/nepali-brihat-sabdakosh-json](https://github.com/bikashpadhikari/nepali-brihat-sabdakosh-json)                        |      |


### Morphology &amp; Syntax


| Resource                           | Size                    | Description                                                 | Link                                                                                                                                     |
| ---------------------------------- | ----------------------- | ----------------------------------------------------------- | ---------------------------------------------------------------------------------------------------------------------------------------- |
| Nepali POS Data (UPOS Mapped)      | 3,000+ tagged sentences | POS tags following Universal Dependencies standard          | [Kaggle: thenepaliguy/nepali-pos](https://www.kaggle.com/datasets/thenepaliguy/nepali-pos)                                               |
| Nepali Word-Lemma Gold Data        | 5,000+ words            | Manual lemmatization annotations                            | [GitHub: dpakpdl/NepaliLemmatizer](https://github.com/dpakpdl/NepaliLemmatizer/tree/master/Lemmatization/data/manually_annotated_corpus) |
| Universal Dependencies (UD) Nepali | 17,500+ tokens          | Full syntactic dependency annotations (official UD project) | [GitHub: UniversalDependencies/UD\_Nepali-NPP](https://github.com/UniversalDependencies/UD_Nepali-NPP)                                   |


### Instruction Tuning &amp; Multilingual


| Resource                         | Languages                                                                  | Description                                                                   | Link |
| -------------------------------- | -------------------------------------------------------------------------- | ----------------------------------------------------------------------------- | ---- |
| Bactrian-X (Instruction Tuning)  | Nepali included in multilingual instruction-tuning dataset (50+ languages) | [HF: MBZUAI/Bactrian-X](https://huggingface.co/datasets/MBZUAI/Bactrian-X)    |      |
| Aya Dataset (Instruction Tuning) | Nepali included in community-driven instruction dataset (101 languages)    | [HF: cohere/aya\_dataset](https://huggingface.co/datasets/cohere/aya_dataset) |      |


---

## 🤖 Pre-trained Models &amp; Embeddings

Pre-computed word vectors and language models with training datasets.

### Word Embeddings


| Resource                                     | Dimensions                                        | Description                         | Link                                                                                                                                        |
| -------------------------------------------- | ------------------------------------------------- | ----------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------- |
| Nepali Word2Vec from scratch                 | Custom-trained 300D vectors with training scripts | Educational resource                | [GitHub: R4j4n/Nepali-Word2Vec-from-scratch](https://github.com/R4j4n/Nepali-Word2Vec-from-scratch)                                         |
| 300D Word2Vec Embeddings for Nepali Language | Pre-computed 300D vectors, 20k+ words             | Ready-to-use                        | [GitHub: rabindralamsal/Word2Vec-Embeddings-for-Nepali-Language](https://github.com/rabindralamsal/Word2Vec-Embeddings-for-Nepali-Language) |
| Nepali FastText Word Vectors                 | Official FastText vectors (Meta/Facebook)         | Trained on Common Crawl + Wikipedia | [fastText: crawl-vectors](https://github.com/facebookresearch/fastText/blob/master/docs/crawl-vectors.md)                                   |


### Large Language Models &amp; Transformers


| Model                                | Parameters  | Training Data                                               | Link                                                                                                                                      |
| ------------------------------------ | ----------- | ----------------------------------------------------------- | ----------------------------------------------------------------------------------------------------------------------------------------- |
| IRIISNEPAL RoBERTa                   | 110M params | 27.5 GB training corpus from 99 news sites                  | [HF: IRIISNEPAL/RoBERTa\_Nepali\_110M](https://huggingface.co/IRIISNEPAL/RoBERTa_Nepali_110M)                                             |
| NepaliBERT                           | -           | 4.6 GB training corpus, 85k+ articles                       | [HF: Shushant/nepaliBERT](https://huggingface.co/Shushant/nepaliBERT)                                                                     |
| DistilGPT2-Nepali                    | -           | 13M Nepali text sequences (OSCAR + CC100 + Wikipedia)       | [HF: Sakonii/distilgpt2-nepali](https://huggingface.co/Sakonii/distilgpt2-nepali)                                                         |
| Nepali Text Generation (Transformer) | -           | Custom transformer for generation &amp; spelling correction | [GitHub: NirajanBekoju/Transformer-Based-Nepali-Language-Model](https://github.com/NirajanBekoju/Transformer-Based-Nepali-Language-Model) |
| NepBERTa                             | -           | Official Nepali BERT baseline for GLUE benchmark            | [nepberta.github.io](https://nepberta.github.io/)                                                                                         |


---

## 🛠️ Tools &amp; NLP Frameworks

Complete NLP toolkits and utilities for Nepali processing.


| Tool                                          | Description                                                 | Link                                                                                                                                                       |
| --------------------------------------------- | ----------------------------------------------------------- | ---------------------------------------------------------------------------------------------------------------------------------------------------------- |
| Nepali Lemmatizer                             | Rule-based lemmatization with training data                 | [GitHub: dpakpdl/NepaliLemmatizer](https://github.com/dpakpdl/NepaliLemmatizer/tree/master/Lemmatization/data)                                             |
| Nepali Transliteration                        | Script conversion dataset for transliteration tasks         | [Kaggle: saugatkafley/nepali-transliteration](https://www.kaggle.com/datasets/saugatkafley/nepali-transliteration)                                         |
| Audinp (Data Collector)                       | Tool for collecting speech data (contributed to OpenSLR-54) | [GitHub: SUBOdhar/audinp](https://github.com/SUBOdhar/audinp)                                                                                              |
| BISH-100 (AI Anchor)                          | Synthetic video dataset with AI-generated Nepali anchor     | [Kaggle: bisheshworneupane/bish-100-nepali-text-driven-ai-anchor](https://www.kaggle.com/datasets/bisheshworneupane/bish-100-nepali-text-driven-ai-anchor) |
| Fine-tuned DistilBERT on 16 Newsgroup Dataset | Ready-to-use classifier for news categorization             | [HF: Suyogyart/nepali-16-newsgroups-classification](https://huggingface.co/Suyogyart/nepali-16-newsgroups-classification)                                  |


---

## 🔬 Research Papers &amp; Benchmarks

Peer-reviewed publications on Nepali NLP and related work.

### Recent &amp; High-Impact (2024-2026)


| Paper                                                            | Year | Focus                                      | Link                                                                       |
| ---------------------------------------------------------------- | ---- | ------------------------------------------ | -------------------------------------------------------------------------- |
| NepaliGPT: A Generative Language Model for the Nepali Language   | 2025 | Recent LLM research                        | [arXiv: 2506.16399](https://arxiv.org/abs/2506.16399)                      |
| NLUE (Nepali Language Understanding Evaluation)                  | 2024 | 9 NLU tasks with comprehensive benchmark   | [arXiv: 2411.19244](https://arxiv.org/abs/2411.19244)                      |
| IRIISNEPAL RoBERTa: State-of-the-art Nepali LM                   | 2024 | 27.5 GB training corpus from 99 news sites | [arXiv: 2411.15734](https://arxiv.org/abs/2411.15734)                      |
| Code-Mixed Nepali-English Abuse Detection                        | 2025 | 5k annotated code-mixed dataset            | [arXiv: 2504.21026](https://arxiv.org/abs/2504.21026)                      |
| Nepali Transformers@NLU of Devanagari Script Languages 2025      | 2025 | Transformer architectures for Devanagari   | [ACL: 2025.chipsal-1.36](https://aclanthology.org/2025.chipsal-1.36/)      |
| Application of Nepali Large Language Models to Improve Sentiment | 2024 | LLM applications                           | [ACM](https://dl.acm.org/doi/10.1145/3647782.3647804)                      |
| NepKanun: A RAG-Based Nepali Legal Assistant                     | 2025 | RAG systems for legal domain               | [OpenReview](https://openreview.net/forum?id=LuXTBI6GSh)                   |
| Exploring NLP Challenges for Nepali                              | 2024 | Overview of remaining challenges           | [Preprints: 202409.1229](https://www.preprints.org/manuscript/202409.1229) |


### Sentiment Analysis &amp; Classification


| Paper                                                                    | Focus                            | Link                                                                                                                                                           |
| ------------------------------------------------------------------------ | -------------------------------- | -------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| Aspect Based Sentiment Analysis of Nepali Text Using SVM and Naive Bayes | Comparative ML approach          | [ResearchGate](https://www.researchgate.net/publication/346441002_Aspect_Based_Sentiment_Analysis_of_Nepali_Text_Using_Support_Vector_Machine_and_Naive_Bayes) |
| An Analysis of Classification Algorithms for Nepali News                 | Benchmark of various classifiers | [ResearchGate](https://www.researchgate.net/publication/343228516_An_Analysis_of_Classification_Algorithms_for_Nepali_News)                                    |
| Nepali Text Document Classification Using Deep Neural Network            | Deep learning approaches         | [NEPJOL](https://www.nepjol.info/index.php/TUJ/article/view/28677)                                                                                             |


### NLP Tasks &amp; Applications


| Paper                                                                 | Task                            | Link                                                                   |
| --------------------------------------------------------------------- | ------------------------------- | ---------------------------------------------------------------------- |
| A Machine Learning Approach to Anaphora Resolution in Nepali Language | Pronoun resolution task         | [IEEE](https://ieeexplore.ieee.org/document/9200135)                   |
| Nepali Image Captioning                                               | Vision-language multimodal task | [IEEE: 8947436](https://ieeexplore.ieee.org/abstract/document/8947436) |
| Named-Entity Based Sentiment Analysis of Nepali News Media Texts      | NER + sentiment joint modeling  | [ACL Anthology](https://aclanthology.org/2020.nlptea-1.16.pdf)         |
| Topic Modeling for Nepali Political News                              | Topic analysis in news domain   | [IEEE: 11004776](https://ieeexplore.ieee.org/document/11004776/)       |


### Linguistic &amp; Historical


| Paper                                                  | Focus                         | Link                                                                                                                                        |
| ------------------------------------------------------ | ----------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------- |
| Natural language processing for Nepali text: a review  | Comprehensive NLP review      | [Springer](https://link.springer.com/article/10.1007/s10462-021-10093-1)                                                                    |
| A Descriptive Grammar of Nepali and an Analyzed Corpus | Linguistic grammar reference  | [Google Books](https://books.google.com.np/books?id=Z_JoCIRN_xwC)                                                                           |
| Nepali Spell Checker 1.1 and the Thesaurus             | Early spell checking research | [Wayback: NEP05.pdf](https://web.archive.org/web/20131020064957/http://www.panl10n.net/english/final%20reports/pdf%20files/Nepal/NEP05.pdf) |
| Nepali Spell Checker                                   | Earlier spell checking work   | [Wayback: NEP04.pdf](https://web.archive.org/web/20150105024511/http://www.panl10n.net/english/final%20reports/pdf%20files/Nepal/NEP04.pdf) |


### Research Aggregators


| Resource                         | Description                           | Link                                                                                        |
| -------------------------------- | ------------------------------------- | ------------------------------------------------------------------------------------------- |
| List of more Nepali NLP papers   | Comprehensive tracker (maintained)    | [GitHub: RayGone/Nepali-NLP-Progress](https://github.com/RayGone/Nepali-NLP-Progress)       |
| Nepali NLP Progress (divyamani1) | Community-maintained research tracker | [GitHub: divyamani1/Nepali-NLP-Progress](https://github.com/divyamani1/Nepali-NLP-Progress) |


---

## 📂 Open Data &amp; Government Resources

Official government datasets and open data portals.


| Resource        | Description                                                                                 | Link                                                                     |
| --------------- | ------------------------------------------------------------------------------------------- | ------------------------------------------------------------------------ |
| Open Data Nepal | Official open data portal with 500+ government datasets (health, education, infrastructure) | [opendatanepal.com](https://opendatanepal.com/)                          |
| Census Nepal    | Official census data from Central Bureau of Statistics (demographic, geographic, economic)  | [censusnepal.cbs.gov.np/results](https://censusnepal.cbs.gov.np/results) |


---

## 🌐 Additional Resources

### Specialized Collections &amp; Aggregators


| Resource                                   | Description                                                                                        | Link                                                                                                                              |
| ------------------------------------------ | -------------------------------------------------------------------------------------------------- | --------------------------------------------------------------------------------------------------------------------------------- |
| Comprehensive Nepali Datasets (IOST-ASCOL) | Aggregated NLP, speech, image, geospatial datasets                                                 | [GitHub: IOST-ASCOL/nepali-datasets](https://github.com/IOST-ASCOL/nepali-datasets)                                               |
| Curated Nepali NLP Resources               | Comprehensive resource list with papers &amp; tools                                                | [GitHub: ghimiresunil/Curated-List-of-Nepali-NLP-Resources](https://github.com/ghimiresunil/Curated-List-of-Nepali-NLP-Resources) |
| Nepali NLP Resources (rameshhpathak)       | Tool &amp; dataset aggregator with descriptions                                                    | [GitHub: rameshhpathak/nepali-nlp-resources](https://github.com/rameshhpathak/nepali-nlp-resources)                               |
| Nepali NLP Progress                        | Research papers &amp; datasets tracker (regularly updated)                                         | [GitHub: divyamani1/Nepali-NLP-Progress](https://github.com/divyamani1/Nepali-NLP-Progress)                                       |
| IndicNLP Catalog (AI4Bharat)               | Official Indic language resources (11 languages including Nepali)                                  | [ai4bharat.github.io/indicnlp\_catalog](https://ai4bharat.github.io/indicnlp_catalog/)                                            |
| ML Datasets for Nepal                      | Curated ML resources including Laxmi Prasad Devkota Poems (119k characters) &amp; Brihat Sabdakosh | [GitHub: amitness/ml-datasets](https://github.com/amitness/ml-datasets)                                                           |


### OCR &amp; Handwriting Datasets

Character recognition, document digitization, and license plate detection.

#### Handwriting &amp; Character Recognition


| Dataset                                      | Description                                                | Link                                                                                                                                                           |
| -------------------------------------------- | ---------------------------------------------------------- | -------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| Nepali Handwriting Characters                | Handwritten character images for OCR training              | [Kaggle: mohanbhandari/nepali-handwriting-characters](https://www.kaggle.com/datasets/mohanbhandari/nepali-handwriting-characters)                             |
| Handwritten Devanagari Character Dataset     | 10,500+ images of Devanagari script (applicable to Nepali) | [Kaggle: sa9arr/handwritten-devanagari-character-dataset](https://www.kaggle.com/datasets/sa9arr/handwritten-devanagari-character-dataset)                     |
| Nepali Handwritten Images for Text Detection | Document-level handwritten images for text detection       | [Kaggle: sweekardahal/nepali-handwritten-images-for-text-detection](https://www.kaggle.com/datasets/sweekardahal/nepali-handwritten-images-for-text-detection) |


#### License Plate &amp; Vehicle Recognition


| Dataset                            | Description                                                         | Link                                                                                                                             |
| ---------------------------------- | ------------------------------------------------------------------- | -------------------------------------------------------------------------------------------------------------------------------- |
| Nepali License Plate (ALPR) V2     | 2,000+ license plate images for automatic license plate recognition | [Kaggle: ishworsubedii/alpr-v2](https://www.kaggle.com/datasets/ishworsubedii/alpr-v2)                                           |
| Nepali Motorbike Backplate Labeled | 1,500+ motorcycle plate images with bounding boxes                  | [Kaggle: saugat111/nepali-moterbike-backplate-lbled](https://www.kaggle.com/datasets/saugat111/nepali-moterbike-backplate-lbled) |


#### Academic OCR Research


| Dataset                                           | Description                                                               | Link                                                  |
| ------------------------------------------------- | ------------------------------------------------------------------------- | ----------------------------------------------------- |
| Nepali Handwritten Character Recognition (Zenodo) | Research dataset with detailed annotations                                | [Zenodo: 7472398](https://zenodo.org/records/7472398) |
| Improving Tesseract-OCR for Nepali (Zenodo)       | 5,000+ images with preprocessing techniques (DOI: 10.5281/zenodo.4361896) | [Zenodo: 4361896](https://zenodo.org/records/4361896) |


### Code-Mixed &amp; Multilingual NLP Datasets


| Dataset                                               | Description                               | Link                                                                    |
| ----------------------------------------------------- | ----------------------------------------- | ----------------------------------------------------------------------- |
| Code-Mixed Nepali-English Abuse Detection             | 5,000 Nepali-English code-mixed comments  | Social media                                                            |
| Nepali-English Code-Switched LID, POS, NER, Sentiment | Complete NLP pipeline for code-mixed data | [GitHub: sagorbrur/codeswitch](https://github.com/sagorbrur/codeswitch) |
| CLE Parallel Corpus (AI4Bharat)                       | English-Nepali-Urdu parallel data         | Multilingual                                                            |


---

## 📜 Ethical Considerations

- **Sentiment/Hate Speech Data:** Contains potentially offensive language; bias mitigation recommended for model training
- **Social Media Data (Tweets, Instagram):** May contain personal information; use with GDPR/privacy compliance
- **Copyright:** Wikipedia, news articles sourced responsibly; attribution recommended
- **Multilingual Data:** Code-mixed datasets reflect real-world language use; social biases may be present

---

## 🚀 Quick Links

- **Hugging Face Nepali Datasets**: [huggingface.co/datasets?language=language:ne](https://huggingface.co/datasets?language=language:ne)
- **GitHub Nepali NLP**: [github.com/search?q=nepali+nlp](https://github.com/search?q=nepali+nlp)
- **ACL Anthology (Nepali Papers)**: [aclanthology.org](https://aclanthology.org/)
- **arXiv (Nepali Research)**: [arxiv.org/search/?query=nepali](https://arxiv.org/search/?query=nepali)
- **IndicNLP Catalog**: [ai4bharat.github.io/indicnlp\_catalog](https://ai4bharat.github.io/indicnlp_catalog/)

---

## 📊 Dataset Summary


| Category                  | Count | Description                                                         |
| ------------------------- | ----- | ------------------------------------------------------------------- |
| **Text Corpus**           | 15+   | Ultra-large, large curated, and specialized text collections        |
| **NLP Datasets**          | 20+   | Classification, NER, QA, Summarization, Sentiment, Hate Speech      |
| **Translation Data**      | 10+   | Parallel corpora for EN-NE, HI-NE, UR-NE, and multilingual          |
| **Speech &amp; Audio**    | 10+   | ASR, TTS, emotion detection datasets                                |
| **Computer Vision**       | 10+   | Sign language, image captioning, face recognition, object detection |
| **OCR &amp; Handwriting** | 8+    | Character recognition, license plate detection                      |
| **Lexicons**              | 8+    | Dictionaries, stopwords, POS data, word embeddings                  |
| **Pre-trained Models**    | 5+    | RoBERTa, BERT, GPT2, word embeddings                                |
| **Benchmarks**            | 5+    | NLUE, Nep-gLUE, FLORES-101, IndicBench                              |
| **Research Papers**       | 15+   | Recent publications and historical works                            |

*Last updated: August 8, 2026*  
*Maintained by: RannWinPro Drive 8*  
*Contributions welcome! Submit PR to [pemagrg1/Nepali-Datasets](https://github.com/pemagrg1/Nepali-Datasets)*
