# Nepali Datasets Collection

*A comprehensive, organized collection of 200+ Nepali datasets across NLP, Computer Vision, Speech, OCR, and more for AI/ML research and development.*

---

## Table of Contents

1. [LLM Development Resources](#llm-development-resources)
2. [Benchmarks and Standards](#benchmarks-and-standards)
3. [Text Corpora](#text-corpora)
4. [NLP Datasets](#nlp-datasets)
5. [Translation and Parallel Data](#translation-and-parallel-data)
6. [Speech and Audio Datasets](#speech-and-audio-datasets)
7. [Computer Vision Datasets](#computer-vision-datasets)
8. [OCR and Handwriting Datasets](#ocr-and-handwriting-datasets)
9. [Lexicons and Linguistic Resources](#lexicons-and-linguistic-resources)
10. [Pre-trained Models and Embeddings](#pre-trained-models-and-embeddings)
11. [Tools and Frameworks](#tools-and-frameworks)
12. [Research Papers](#research-papers)
13. [Open Data and Government Resources](#open-data-and-government-resources)
14. [Additional Resources](#additional-resources)
15. [Dataset Search Guide](#dataset-search-guide)

---

# LLM Development Resources

---

## Pre-training Corpora

### Ultra-Large (Greater Than 1GB)

| Dataset | Size | Source | Link |
|---------|------|--------|------|
| Nepali-Text-Corpus (IRIISNEPAL) | 6.4M articles, 10.1 GB | 99 news websites | [HF](https://huggingface.co/datasets/IRIISNEPAL/nepali-text-corpus) |
| IRIIS-RESEARCH Nepali Text Corpus | 10.1 GB, 6.4M articles | 99 news websites | [HF](https://huggingface.co/datasets/IRIIS-RESEARCH/Nepali-Text-Corpus) |
| OSCAR Corpus Nepali | 3.8 GB, 100M+ sentences | Common Crawl | [Kaggle](https://www.kaggle.com/hsebarp/oscar-corpus-nepali) |
| CC100-Nepali | 200GB uncompressed | Common Crawl 2019 | [MetaText](https://metatext.io/datasets/cc100-nepali) |
| Large Scale Nepali Text Corpus | Large-scale | General | [IEEE Dataport](https://ieee-dataport.org/open-access/large-scale-nepali-text-corpus) |
| Boredoom17 Nepali Corpus | - | General | [HF](https://huggingface.co/datasets/Boredoom17/Nepali-Corpus) |
| Gold Standard Nepali Raw Text Corpus | - | Raw text | [LDCIL](https://data.ldcil.org/a-gold-standard-nepali-raw-text-corpus) |
| Language Resources for Nepal | Multiple datasets | Aggregated collection | [language-resources-nepal.github.io](https://language-resources-nepal.github.io/data) |
| OpenWiseyak-0.1-Pretraining | - | Wiseyak | [HF](https://huggingface.co/datasets/Wiseyak/OpenWiseyak-0.1-Pretraining) |
| Wiseyak-SFT-Mixed-ne-en | - | Wiseyak | [HF](https://huggingface.co/datasets/Wiseyak/Wiseyak-SFT-Mixed-ne-en) |
| Ministry of Finance Nepal Corpus | 2015-2024 (Fiscal Years 2072/73-2080/81) | Government reports | [HF: lilgoose777/mof-nepal-nepali](https://huggingface.co/datasets/lilgoose777/mof-nepal-nepali) |
| Nepali LLM Datasets | - | Aggregated | [HF: Aananda-giri/nepali_llm_datasets](https://huggingface.co/datasets/Aananda-giri/nepali_llm_datasets) |
| NaBI Corpus | - | - | [HF: Utkarsha666/NaBI](https://huggingface.co/datasets/Utkarsha666/NaBI) |

### Large Curated (100MB-1GB)

| Dataset | Size | Description | Link |
|---------|------|-------------|------|
| Nepali News Dataset | 6,800+ articles | With metadata | [Kaggle](https://www.kaggle.com/lotusacharya/nepalinewsdataset) |
| Nepali Wikipedia Articles | 39,000+ articles | Wikipedia dump | [Kaggle](https://www.kaggle.com/disisbig/nepali-wikipedia-articles) |
| np20ng (20 Newsgroup) | 200,000+ documents | 20 categories | [HF](https://huggingface.co/datasets/Suyogyart/np20ng) |
| Nepali News Dataset (Large) | 25,000+ articles | 10+ categories | [Kaggle](https://www.kaggle.com/ashokpant/nepali-news-dataset-large) |
| Ashok Pant Nepali News Dataset | 25,000+ articles | 10+ categories | [Kaggle: ashokpant/nepali-news-dataset-large](https://www.kaggle.com/datasets/ashokpant/nepali-news-dataset-large) |
| Nagarik News Corpus | - | News | [GitHub](https://github.com/ashmitbhattarai/Nepali-Language-Modeling-Using-LSTM/tree/master/Nepali_Corpus/Nagarik) |
| Setopati News Corpus | - | News | [GitHub](https://github.com/ashmitbhattarai/Nepali-Language-Modeling-Using-LSTM/tree/master/Nepali_Corpus/SetoPati) |
| Spandyie Nepali News Dataset | Large collection | Baahrakhari and other sources, cleaned category labels | [HF: spandyie/nepali-news-dataset](https://huggingface.co/datasets/spandyie/nepali-news-dataset) |

### Specialized

| Dataset | Size | Domain | Link |
|---------|------|--------|------|
| Digitized Nepali Textbooks | OCR'd textbooks | Formal register | [HF](https://huggingface.co/datasets/dineshkarki/nepali-textbooks-corpus) |
| Nepali Lyrics Dataset | 5,000+ lyrics | Music domain | [Kaggle](https://www.kaggle.com/datasets/sanjay05kc/nepali-lyrics) |
| 65K Nepali Sentences | 65,000 sentences | General | [GitHub](https://github.com/sanjaalcorps/NepaliDataSets) |
| 350K Nepali Sentences | 350,000 sentences | General | [GitHub](https://github.com/Team-Naya/nlp-doko) |
| Laxmi Prasad Devkota Poems | 119,161 characters | Literary | [GitHub](https://github.com/devkotasawal1/Poem-Generator/blob/master/lspd.txt) |
| Nepali Ukhaan Tukka (Proverbs) | - | Proverbs | [GitHub](https://github.com/theseekersway/Nepali-Ukhaan-Tukka) |
| Nepali Ngram | - | N-grams | [GitHub](https://github.com/virtualanup/nepalingram) |
| Nepali Chat Corpus | - | Chat/conversational | [GitHub](https://github.com/itsmeashutosh43/create-a-Open-Source-Nepali-Chat-corpus) |
| English News Corpus (Nepal) | - | English news about Nepal | [GitHub](https://github.com/sharad461/english-corpus-nepal) |
| Nepal Earthquake Tweets | - | Social media (disaster) | [CrisisNLP](https://crisisnlp.qcri.org/lrec2016/content/2015_nepal_eq.html) |
| Nepali Sentences Corpus | - | General | [Kaggle: sparshrestha/nepali-sentences-corpus](https://www.kaggle.com/datasets/sparshrestha/nepali-sentences-corpus) |
| Nepali Election Results Historical | - | Government | [Kaggle: dimanjung/nepali-election-results-historical](https://www.kaggle.com/datasets/dimanjung/nepali-election-results-historical) |
| Gender Based Violence in Nepal 2019-2026 | - | Social | [Kaggle: aneeshmhj/gender-based-violence-in-nepal-2019-2026](https://www.kaggle.com/datasets/aneeshmhj/gender-based-violence-in-nepal-2019-2026) |
| Nepal Earthquake Seismicity Dataset | 1990-2026 | Geological | [Kaggle: amansinghnp/nepal-earthquake-seismicity-dataset-1990-2026](https://www.kaggle.com/datasets/amansinghnp/nepal-earthquake-seismicity-dataset-1990-2026) |
| Nepal Multi-District Weather Dataset | 2020-2025 | Meteorological | [Kaggle: dipeshthapa1/nepal-multi-district-weather-dataset-2020-2025](https://www.kaggle.com/datasets/dipeshthapa1/nepal-multi-district-weather-dataset-2020-2025) |
| House Price Dataset Nepal | - | Real Estate | [Kaggle: nishanpokh/house-price-dataset-nepal](https://www.kaggle.com/datasets/nishanpokh/house-price-dataset-nepal) |
| Nepal Trekking Dataset | - | Tourism | [Kaggle: bibekrai44/nepal-treking-dataset](https://www.kaggle.com/datasets/bibekrai44/nepal-treking-dataset) |
| Nepali Surname/Caste/Ethnicity Datasets | - | Demographic | [Kaggle: nayansubedi1/nepali-surname-caste-ethnicity-datasets](https://www.kaggle.com/datasets/nayansubedi1/nepali-surname-caste-ethnicity-datasets) |

---

## Fine-tuning Datasets

### Text Classification

| Dataset | Size | Categories | Link |
|---------|------|------------|------|
| 16NepaliNews Corpus | ~14,364 documents | 16 categories | [GitHub](https://github.com/sndsabin/Nepali-News-Classifier) |
| iNLTK Nepali News Dataset | 8,000+ articles | 5 categories | [Kaggle](https://www.kaggle.com/disisbig/nepali-news-dataset) |
| Nepali News Dataset | 6,800+ articles | With metadata | [Kaggle](https://www.kaggle.com/lotusacharya/nepalinewsdataset) |
| Nepali News Classification Dataset | - | - | [Google Drive](https://drive.google.com/drive/folders/1Vm0UJ3FfWP-3guSan3FZsOV4q7rYuJIG) |
| Nepali News Datasets (Small) | 3,000+ articles | - | [Kaggle](https://www.kaggle.com/tejshahi/20nepalinews) |
| Prasta Dataset | - | Question type classification | [Kaggle](https://www.kaggle.com/datasets/sangamthapa/prasta) |
| Nepali Factoid Questions Intent Classified | 500+ samples | Intent detection | [Kaggle](https://www.kaggle.com/datasets/sushiltimilsina/nepali-factoid-questions-intent-classified-dataset) |
| AshokNepal Nepali News Classification | - | News categories | [Kaggle: ashoknepal/nepali-news-classification](https://www.kaggle.com/datasets/ashoknepal/nepali-news-classification) |

### Question Answering

| Dataset | Size | Type | Domain | Link |
|---------|------|------|--------|------|
| Nepali Health Q and A Corpus | 3,000+ Q and A pairs | - | Medical | [Kaggle](https://www.kaggle.com/datasets/thedevastator/nepali-health-q-a-corpus) |
| Pregnancy Related Q and A | 1,500+ pairs | - | Maternal health | [Kaggle](https://www.kaggle.com/datasets/poudelsujan03/pregnancy-related-question-answer-nepali-dataset) |
| Nepali Health Forum Corpus | 2,500+ Q and A | With user interactions | Medical | [Kaggle](https://www.kaggle.com/datasets/rxnach/nepali-health-forum-corpus-questions-and-answers) |
| Nepali QA Dataset (Yunika) | 266 pairs | Extractive | - | [HF](https://huggingface.co/datasets/Yunika/Nepali-QA) |
| Nepali Driving License Test | - | Question Answering | - | [HF: sharad461/nepali-driving-license-test](https://huggingface.co/datasets/sharad461/nepali-driving-license-test) |

### Summarization

| Dataset | Size | Type | Link |
|---------|------|------|------|
| Nepali News Article with Summary | 286,000+ pairs | Headline generation | [Kaggle](https://www.kaggle.com/datasets/adarsh203/nepali-news-article-with-summary) |
| Nepali text summarization | 1,000+ pairs | Abstractive | [Kaggle](https://www.kaggle.com/datasets/imageinfo/nepali-text-summarization) |
| Nepali Abstractive Summarization Corpus | 286k article-title pairs | Abstractive | [Google Drive](https://drive.google.com/file/d/1L56k0zonMk6XpelKAXPm45wCmt-9pS3x/view) |
| Sentence Compression Nepali | 5,000+ pairs | Extractive | [Kaggle](https://www.kaggle.com/datasets/sbastola73/sentence-compression-nepali) |
| Policy Documents and Summaries | 500+ documents | Domain-specific | [Kaggle](https://www.kaggle.com/datasets/greenspaghetti/policy-documents-and-summaries) |
| Sanjeev Bhandari Nepali Summarization | - | Abstractive | [HF: sanjeev-bhandari01/nepali-summarization-dataset](https://huggingface.co/datasets/sanjeev-bhandari01/nepali-summarization-dataset) |

### Named Entity Recognition (NER)

| Dataset | Size | Entity Types | Link |
|---------|------|--------------|------|
| EverestNER | 50,000+ sentences | 8 types | [Kaggle](https://www.kaggle.com/datasets/jeevanchapagain/everestner) |
| DanfeNER | 25,000+ sentences | Geographical and cultural | [Kaggle](https://www.kaggle.com/datasets/jeevanchapagain/danfener) |
| Nepali NER (Ebiquity v2) | - | PER, ORG, LOC | [GitHub](https://github.com/oya163/nepali-ner/tree/master/data/ebiquity_v2) |
| Nepali NER Dataset (dadelani) | - | Multi-token entities | [GitHub](https://github.com/dadelani/nepali-ner) |
| Nepali Offensive Language NER and Sentiment | 5,000+ samples | Dual annotations | [Kaggle](https://www.kaggle.com/datasets/merishnasuwal/offensive-language-ner-and-sentiment-analysis-data) |

### Sentiment Analysis

| Dataset | Size | Type | Domain | Link |
|---------|------|------|--------|------|
| NepaliSentiment | - | With preprocessing and baselines | - | [GitHub](https://github.com/rockerritesh/NepaliSentiment) |
| Nepali Sentiment Analysis | - | Binary classification | - | [Kaggle](https://www.kaggle.com/datasets/aayamoza/nepali-sentiment-analysis) |
| Nepali Language Sentiment Analysis - Movie Reviews | 2,500+ reviews | Star ratings | Film | [Kaggle](https://www.kaggle.com/shikharghimire/nepali-language-sentiment-analysis-movie-reviews) |
| Nepali Luxury Hotel Reviews | 4,000+ reviews | Aspect-based | Hotel | [Kaggle](https://www.kaggle.com/datasets/suprapandey/nepali-luxury-hotel-reviews-2024) |
| XLSum-Nepali | - | Summarization + sentiment | - | [HF](https://huggingface.co/datasets/sanjeev-bhandari01/XLSum-nepali) |
| Nepali Data Set for Sentiment Analysis | - | - | - | [Mahesha](https://mahesha.com.np/nepali-data-set-for-sentiment-analysis/) |
| Sentiment Analysis in Nepali | - | - | - | [GitHub](https://github.com/sarozz/Sentiment_analysis_in_Nepali/blob/master/data.csv) |
| SentimentAnalysis | - | - | - | [GitHub](https://github.com/sagarl123/NepaliNLP-SentimentAnalysis/blob/main/collected_labeled_data.csv) |
| Oya163 Nepali Sentiment Analysis | - | Aspect-based abusive sentiment | Social media | [GitHub: oya163/nepali-sentiment-analysis](https://github.com/oya163/nepali-sentiment-analysis) |
| Nepali Fake News Dataset v1 | 8,838 samples | Binary classification | Synthetic (LLM-generated) | [HF: chhatramani/nepali-fake-news-dataset-v1](https://huggingface.co/datasets/chhatramani/nepali-fake-news-dataset-v1) |

### Hate Speech and Offensive Language

| Dataset | Size | Type | Platform | Link |
|---------|------|------|----------|------|
| Nepali Hate Speech Collection | 5,000+ samples | Annotated | Social media | [Kaggle](https://www.kaggle.com/datasets/mohanbhandari/nepali-hate-speech-collection) |
| Nepali Offensive Language Detection | - | Detection tooling | - | [GitHub](https://github.com/merishnaSuwal/nep-off-langdetect) |
| Nepali Abusive Language NER and Sentiment | - | Multi-task | Abusive text | [Kaggle](https://www.kaggle.com/datasets/merishnasuwal/offensive-language-ner-and-sentiment-analysis-data) |
| NepCov19Tweets | 10,000+ tweets | Emotion labels | Twitter | [Kaggle](https://www.kaggle.com/datasets/mathew11111/nepcov19tweets) |
| Mpox Instagram Sentiment and Hate Analysis | 3,000+ posts | Dual sentiment + hate labels | Instagram | [Kaggle](https://www.kaggle.com/datasets/thakurnirmalya/mpox-instagram-dataset-sentiment-and-hate-analysis) |
| Nepali Financial News Dataset | - | Domain-specific | - | [Kaggle: anujbhattrai/the-nepali-financial-news-dataset](https://www.kaggle.com/datasets/anujbhattrai/the-nepali-financial-news-dataset) |

---

## Translation and Parallel Data

### Large-Scale Parallel Corpora

| Dataset | Size | Language Pair | Link |
|---------|------|---------------|------|
| English-Nepali Parallel Corpus (Kathmandu University) | 1,800,000 pairs | EN-NE | [ELRA W0077](https://catalog.elra.info/en-us/repository/browse/ELRA-W0077/) |
| Kathmandu University English-Nepali Corpus | 1.8M pairs | EN-NE | [AI4Bharat](https://github.com/AI4Bharat/indicnlp_catalog) |
| English-Nepali Translation Instruction Dataset | - | EN-NE | [HF: ashokpoudel/English-Nepali-Translation-Instruction-Dataset](https://huggingface.co/datasets/ashokpoudel/English-Nepali-Translation-Instruction-Dataset) |

### Medium-Scale Corpora

| Dataset | Size | Language Pair | Link |
|---------|------|---------------|------|
| Nepali-English language pair | 40,000+ pairs | EN-NE | [GitHub](https://github.com/sharad461/nepali-translator) |
| Hindi-Nepali Parallel Corpus (Noisy) | 500,000+ pairs | HI-NE | [Kaggle](https://www.kaggle.com/datasets/thenepaliguy/final-hi-ne) |
| Hindi-Nepali Evaluation Corpus (Clean) | 50,000+ pairs | HI-NE | [Kaggle](https://www.kaggle.com/datasets/thenepaliguy/cleanhindinepali) |
| Urdu-Nepali Parallel Corpus | 100,000+ pairs | UR-NE | [Kaggle](https://www.kaggle.com/datasets/rtatman/urdunepali-parallel-corpus) |
| English to Nepali Translation | - | EN-NE | [GitHub](https://github.com/arunism/English-to-Nepali-Language-Translation/tree/master/data) |
| Nepali-English Translation Dataset | - | EN-NE | [GitHub](https://github.com/BISHALTWR/Nepali-English-Translation-Dataset) |
| Nepali Translation Parallel Corpus | - | EN-NE | [Google Drive](https://drive.google.com/file/d/1UThfJKJFvDgTu263DNbz-WPNLqoARZ_0/view) |
| English-Nepali Translated Strings (TDIL) | - | UI/software localization | [TDIL-DC](https://tdil-dc.in/index.php?option=com_download&task=showresourceDetails&toolid=1069&lang=en) |

### Multilingual and Specialized

| Dataset | Size | Languages | Domain | Link |
|---------|------|-----------|--------|------|
| Trilingual Hindi-English-Nepali | 200,000+ triples | HI-EN-NE | - | [Kaggle](https://www.kaggle.com/datasets/sundeepdawadi/cleaned-word2word-en-hi-ne) |
| English-Nepali Translation (HF) | - | EN-NE | Instruction-tuned | [HF](https://huggingface.co/datasets/ashokpoudel/nepali-english-translation-dataset) |
| Bidirectional EN-NE MT (Legal) | 125,000 sentences | EN-NE | Legal | [ACL Paper](https://aclanthology.org/2024.sigul-1.7.pdf) |
| CLE Parallel Corpus | - | EN-NE-UR | - | [AI4Bharat](https://github.com/AI4Bharat/indicnlp_catalog) |

### Historical and Shared Tasks

| Dataset | Event | Link |
|---------|-------|------|
| WMT19 Parallel Corpus | Shared task | [statmt.org](https://www.statmt.org/wmt19/parallel-corpus-filtering.html) |
| FLORES 101 Dataset | Multilingual benchmark | [GitHub](https://github.com/facebookresearch/flores/tree/main/floresv1/data) |

### Instruction Tuning

| Dataset | Languages | Type | Link |
|---------|-----------|------|------|
| Bactrian-X | 50+ languages (includes Nepali) | Instruction tuning | [HF](https://huggingface.co/datasets/MBZUAI/Bactrian-X) |
| Aya Dataset | 101 languages (includes Nepali) | Instruction tuning | [HF](https://huggingface.co/datasets/cohere/aya_dataset) |

---

# Benchmarks and Standards

Comprehensive evaluation frameworks and shared tasks for Nepali NLP.

| Benchmark | Tasks | Link |
|-----------|-------|------|
| NLUE (Nepali Language Understanding Evaluation) | 9 classification + 3 structural prediction tasks (sentiment, hate speech, toxicity, QA, NER) | [arXiv: 2411.19244](https://arxiv.org/abs/2411.19244) |
| Nep-gLUE Benchmark | Official Nepali GLUE-style benchmark (7 NLU tasks) | Limited direct access; see NLUE for comprehensive alternatives |
| FLORES-101 Evaluation Benchmark | Machine translation evaluation across 101 languages including Nepali | [GitHub: facebookresearch/flores](https://github.com/facebookresearch/flores) |
| IndicBench | Benchmark for 11 Indic languages including Nepali (13 tasks) | [New 2025 addition](https://ai4bharat.github.io/indicnlp_catalog/) |
| SemEval 2026 Task 9 | Polarization type classification with Nepali data | [Codabench](https://www.codabench.org/competitions/10669/) |
| Google FLEURS | Multilingual benchmark including Nepali (101 languages) | [HF: google/fleurs](https://huggingface.co/datasets/google/fleurs) |

---

# Text Corpora

---

## Ultra-Large Corpora (Greater Than 1GB)

| Dataset | Size | Source | Link |
|---------|------|--------|------|
| Nepali-Text-Corpus (IRIISNEPAL) | 6.4M articles, 10.1 GB | Largest Nepali corpus from 99 news websites | [HF: IRIISNEPAL/nepali-text-corpus](https://huggingface.co/datasets/IRIISNEPAL/nepali-text-corpus) |
| OSCAR Corpus Nepali | 3.8 GB, 100M+ sentences | Common Crawl | [Kaggle: hsebarp/oscar-corpus-nepali](https://www.kaggle.com/hsebarp/oscar-corpus-nepali) |
| CC100-Nepali | Common Crawl 2019 subset, 200GB uncompressed | Foundation data for multilingual models | [MetaText: cc100-nepali](https://metatext.io/datasets/cc100-nepali) |
| Lamsal (2020) Corpus | 12M+ words | Professionally compiled | Note: Original DOI 404; consider IRIISNEPAL as primary substitute |

---

## Large Curated Collections (100MB-1GB)

| Dataset | Size | Description | Link |
|---------|------|-------------|------|
| Nepali News Dataset | 6,800+ articles with metadata | [Kaggle: lotusacharya/nepalinewsdataset](https://www.kaggle.com/lotusacharya/nepalinewsdataset) | |
| Nepali Wikipedia Articles | 39,000+ articles from Wikipedia dump | [Kaggle: disisbig/nepali-wikipedia-articles](https://www.kaggle.com/disisbig/nepali-wikipedia-articles) | |
| np20ng (20 Newsgroup) | 200,000+ news documents across 20 categories | Adapted from English 20NG | [HF: Suyogyart/np20ng](https://huggingface.co/datasets/Suyogyart/np20ng) |
| Nepali News Dataset (Large) | 25,000+ articles across 10+ categories | [Kaggle: ashokpant/nepali-news-dataset-large](https://www.kaggle.com/ashokpant/nepali-news-dataset-large) | |
| Spandyie Nepali News Dataset | Large collection | News articles scraped from Baahrakhari and other Nepali news sources, with cleaned category labels | [HF: spandyie/nepali-news-dataset](https://huggingface.co/datasets/spandyie/nepali-news-dataset) |

---

## Specialized Text Collections

| Dataset | Size | Domain | Link |
|---------|------|--------|------|
| Nepali Unigrams Cleaned (FineWeb) | 200k+ unique Nepali words with frequency | [Kaggle: thenepaliguy/nepali-unigrams-cleaned](https://www.kaggle.com/datasets/thenepaliguy/nepali-unigrams-cleaned) | |
| Setopati News Dataset | 10,000+ articles from Setopati portal | News domain-specific | [Kaggle: living0world/setopati-news-dataset](https://www.kaggle.com/datasets/living0world/setopati-news-dataset) |
| Nepali Raw Text Data | Raw text batches for preprocessing | [Kaggle: rajanghimire/nepali-raw-text-data-batch1](https://www.kaggle.com/datasets/rajanghimire/nepali-raw-text-data-batch1) | |
| Nepali Lyrics Dataset | 5,000+ song lyrics with metadata | Music domain | [Kaggle: sanjay05kc/nepali-lyrics](https://www.kaggle.com/datasets/sanjay05kc/nepali-lyrics) |
| Digitized Nepali Textbooks | OCR'd school textbooks (formal register) | [HF: dineshkarki/nepali-textbooks-corpus](https://huggingface.co/datasets/dineshkarki/nepali-textbooks-corpus) | |

---

# NLP Datasets

---

## Classification Datasets

News classification, topic modeling, and text categorization.

| Dataset | Size | Description | Link |
|---------|------|-------------|------|
| iNLTK Nepali News Dataset | 8,000+ articles across 5 categories | [Kaggle: disisbig/nepali-news-dataset](https://www.kaggle.com/disisbig/nepali-news-dataset) | |
| 16NepaliNews Corpus | ~14,364 documents across 16 categories | Most comprehensive category coverage | [GitHub: sndsabin/Nepali-News-Classifier](https://github.com/sndsabin/Nepali-News-Classifier) |
| Nepali News Datasets (Small) | 3,000+ articles | Good for quick prototyping | [Kaggle: tejshahi/20nepalinews](https://www.kaggle.com/tejshahi/20nepalinews) |
| Prasta Dataset | Question type classification for QA systems | [Kaggle: sangamthapa/prasta](https://www.kaggle.com/datasets/sangamthapa/prasta) | |
| Nepali Factoid Questions Intent Classified | 500+ samples for intent detection | [Kaggle: sushiltimilsina/nepali-factoid-questions-intent-classified-dataset](https://www.kaggle.com/datasets/sushiltimilsina/nepali-factoid-questions-intent-classified-dataset) | |
| AshokNepal Nepali News Classification | - | News article classification | [Kaggle: ashoknepal/nepali-news-classification](https://www.kaggle.com/datasets/ashoknepal/nepali-news-classification) |

---

## Named Entity Recognition (NER) Datasets

Annotated datasets for entity recognition (person, organization, location, etc.).

| Dataset | Size | Description | Link |
|---------|------|-------------|------|
| EverestNER | 50,000+ annotated sentences, 8 entity types | Largest NER dataset | [Kaggle: jeevanchapagain/everestner](https://www.kaggle.com/datasets/jeevanchapagain/everestner) |
| DanfeNER | 25,000+ sentences covering Nepali geographical and cultural entities | [Kaggle: jeevanchapagain/danfener](https://www.kaggle.com/datasets/jeevanchapagain/danfener) | |
| Nepali NER (Ebiquity v2) | Benchmark dataset with 3 entity types (PER, ORG, LOC) | [GitHub: oya163/nepali-ner/data/ebiquity_v2](https://github.com/oya163/nepali-ner/tree/master/data/ebiquity_v2) | |
| Nepali NER Dataset (dadelani) | Annotated for multi-token entities | [GitHub: dadelani/nepali-ner](https://github.com/dadelani/nepali-ner) | |
| Nepali Offensive Language NER and Sentiment | 5,000+ samples with dual annotations (NER + sentiment) | [Kaggle: merishnasuwal/offensive-language-ner-and-sentiment-analysis-data](https://www.kaggle.com/datasets/merishnasuwal/offensive-language-ner-and-sentiment-analysis-data) | |

---
---
## Sentiment Analysis and Hate Speech Datasets

Social media, news, and online text with sentiment/toxicity annotations.

### Sentiment Analysis

| Dataset | Size | Description | Link |
|---------|------|-------------|------|
| NepaliSentiment | GitHub corpus with preprocessing and baselines | [GitHub: rockerritesh/NepaliSentiment](https://github.com/rockerritesh/NepaliSentiment) | |
| Nepali Sentiment Analysis | Binary classification (positive/negative) | [Kaggle: aayamoza/nepali-sentiment-analysis](https://www.kaggle.com/datasets/aayamoza/nepali-sentiment-analysis) | |
| Nepali Language Sentiment Analysis - Movie Reviews | 2,500+ reviews with star ratings | Domain-specific (film) | [Kaggle: shikharghimire/nepali-language-sentiment-analysis-movie-reviews](https://www.kaggle.com/shikharghimire/nepali-language-sentiment-analysis-movie-reviews) |
| Nepali Luxury Hotel Reviews | 4,000+ reviews with aspect-based sentiment | Hotel domain | [Kaggle: suprapandey/nepali-luxury-hotel-reviews-2024](https://www.kaggle.com/datasets/suprapandey/nepali-luxury-hotel-reviews-2024) |
| XLSum-Nepali | Summarization + sentiment | [HF: sanjeev-bhandari01/XLSum-nepali](https://huggingface.co/datasets/sanjeev-bhandari01/XLSum-nepali) | |
| Nepali Data Set for Sentiment Analysis | - | - | [Mahesha](https://mahesha.com.np/nepali-data-set-for-sentiment-analysis/) |
| Sentiment Analysis in Nepali | - | - | [GitHub](https://github.com/sarozz/Sentiment_analysis_in_Nepali/blob/master/data.csv) |
| SentimentAnalysis | - | - | [GitHub](https://github.com/sagarl123/NepaliNLP-SentimentAnalysis/blob/main/collected_labeled_data.csv) |
| Oya163 Nepali Sentiment Analysis | - | Aspect-based abusive sentiment | [GitHub: oya163/nepali-sentiment-analysis](https://github.com/oya163/nepali-sentiment-analysis) |
| Nepali Fake News Dataset v1 | 8,838 labeled samples | Binary classification (real vs fictional) | [HF: chhatramani/nepali-fake-news-dataset-v1](https://huggingface.co/datasets/chhatramani/nepali-fake-news-dataset-v1) |

### Hate Speech and Offensive Language

| Dataset | Size | Description | Link |
|---------|------|-------------|------|
| Nepali Hate Speech Collection | 5,000+ annotated samples from social media | [Kaggle: mohanbhandari/nepali-hate-speech-collection](https://www.kaggle.com/datasets/mohanbhandari/nepali-hate-speech-collection) |
| Nepali Offensive Language Detection | - | Detection tooling | [GitHub: merishnaSuwal/nep-off-langdetect](https://github.com/merishnaSuwal/nep-off-langdetect) |
| Nepali Abusive Language NER and Sentiment | - | Multi-task (NER + sentiment on abusive text) | [Kaggle: merishnasuwal/offensive-language-ner-and-sentiment-analysis-data](https://www.kaggle.com/datasets/merishnasuwal/offensive-language-ner-and-sentiment-analysis-data) |
| NepCov19Tweets | 10,000+ tweets | Emotion labels | [Kaggle: mathew11111/nepcov19tweets](https://www.kaggle.com/datasets/mathew11111/nepcov19tweets) |
| Mpox Instagram Sentiment and Hate Analysis | 3,000+ posts | Dual sentiment + hate labels | [Kaggle: thakurnirmalya/mpox-instagram-dataset-sentiment-and-hate-analysis](https://www.kaggle.com/datasets/thakurnirmalya/mpox-instagram-dataset-sentiment-and-hate-analysis) |

---

## Question Answering (QA) Datasets

Extractive, generative, and domain-specific QA datasets.

| Dataset | Size | Description | Link |
|---------|------|-------------|------|
| Nepali Health Q and A Corpus | 3,000+ Q and A pairs from health forums | Medical domain | [Kaggle: thedevastator/nepali-health-q-a-corpus](https://www.kaggle.com/datasets/thedevastator/nepali-health-q-a-corpus) |
| Pregnancy Related Question Answer | 1,500+ pairs | Maternal health (specialty medical) | [Kaggle: poudelsujan03/pregnancy-related-question-answer-nepali-dataset](https://www.kaggle.com/datasets/poudelsujan03/pregnancy-related-question-answer-nepali-dataset) |
| Nepali Health Forum Corpus | 2,500+ Q and A from health forums | With user interactions, medical domain | [Kaggle: rxnach/nepali-health-forum-corpus-questions-and-answers](https://www.kaggle.com/datasets/rxnach/nepali-health-forum-corpus-questions-and-answers) |
| Nepali QA Dataset (Yunika) | 266 extractive QA pairs | With passage context, HuggingFace format | [HF: Yunika/Nepali-QA](https://huggingface.co/datasets/Yunika/Nepali-QA) |
| Nepali Driving License Test | - | Question answering | [HF: sharad461/nepali-driving-license-test](https://huggingface.co/datasets/sharad461/nepali-driving-license-test) |

---
---
## Summarization Datasets

Abstractive and extractive summarization, headline generation.

| Dataset | Size | Description | Link |
|---------|------|-------------|------|
| Nepali News Article with Summary | 286,000+ news headlines + articles | Largest summarization resource (headline generation) | [Kaggle: adarsh203/nepali-news-article-with-summary](https://www.kaggle.com/datasets/adarsh203/nepali-news-article-with-summary) |
| Nepali text summarization | 1,000+ document-summary pairs | Abstractive task | [Kaggle: imageinfo/nepali-text-summarization](https://www.kaggle.com/datasets/imageinfo/nepali-text-summarization) |
| Nepali Abstractive Summarization Corpus | 286k article-title pairs | Abstractive | [Google Drive](https://drive.google.com/file/d/1L56k0zonMk6XpelKAXPm45wCmt-9pS3x/view) |
| Sentence Compression Nepali | 5,000+ sentence pairs | Text compression (extractive) | [Kaggle: sbastola73/sentence-compression-nepali](https://www.kaggle.com/datasets/sbastola73/sentence-compression-nepali) |
| Policy Documents and Summaries | 500+ documents | Domain-specific (policy) | [Kaggle: greenspaghetti/policy-documents-and-summaries](https://www.kaggle.com/datasets/greenspaghetti/policy-documents-and-summaries) |
| Sanjeev Bhandari Nepali Summarization | - | Abstractive, fine-tuning dataset | [HF: sanjeev-bhandari01/nepali-summarization-dataset](https://huggingface.co/datasets/sanjeev-bhandari01/nepali-summarization-dataset) |

---

# Translation and Parallel Data

Parallel corpora for machine translation and low-resource language pairs.

---

## Large-Scale Parallel Corpora

| Dataset | Size | Language Pair | Link |
|---------|------|---------------|------|
| English-Nepali Parallel Corpus (Kathmandu University) | 1,800,000 sentence pairs | EN-NE | [ELRA W0077](https://catalog.elra.info/en-us/repository/browse/ELRA-W0077/) |
| Kathmandu University English-Nepali Corpus | 1.8M sentence pairs | EN-NE | [AI4Bharat](https://github.com/AI4Bharat/indicnlp_catalog) |

---

## Medium-Scale Corpora

| Dataset | Size | Language Pair | Link |
|---------|------|---------------|------|
| Nepali-English language pair | 40,000+ parallel sentence pairs | EN-NE | [GitHub: sharad461/nepali-translator](https://github.com/sharad461/nepali-translator) |
| Hindi-Nepali Parallel Corpus (Noisy) | 500,000+ sentence pairs | HI-NE | [Kaggle: thenepaliguy/final-hi-ne](https://www.kaggle.com/datasets/thenepaliguy/final-hi-ne) |
| Hindi-Nepali Evaluation Corpus (Clean) | 50,000+ high-quality sentence pairs | HI-NE | [Kaggle: thenepaliguy/cleanhindinepali](https://www.kaggle.com/datasets/thenepaliguy/cleanhindinepali) |
| Urdu-Nepali Parallel Corpus | 100,000+ sentence pairs | UR-NE | [Kaggle: rtatman/urdunepali-parallel-corpus](https://www.kaggle.com/datasets/rtatman/urdunepali-parallel-corpus) |
| English to Nepali Translation | - | EN-NE | [GitHub: arunism/English-to-Nepali-Language-Translation/tree/master/data](https://github.com/arunism/English-to-Nepali-Language-Translation/tree/master/data) |
| Nepali-English Translation Dataset | - | EN-NE | [GitHub: BISHALTWR/Nepali-English-Translation-Dataset](https://github.com/BISHALTWR/Nepali-English-Translation-Dataset) |
| Nepali Translation Parallel Corpus | - | EN-NE | [Google Drive](https://drive.google.com/file/d/1UThfJKJFvDgTu263DNbz-WPNLqoARZ_0/view) |
| English-Nepali Translated Strings (TDIL) | - | UI/software localization | [TDIL-DC](https://tdil-dc.in/index.php?option=com_download&task=showresourceDetails&toolid=1069&lang=en) |
| English-Nepali Translation Instruction Dataset | - | EN-NE | [HF: ashokpoudel/English-Nepali-Translation-Instruction-Dataset](https://huggingface.co/datasets/ashokpoudel/English-Nepali-Translation-Instruction-Dataset) |

---
---
## Multilingual and Specialized

| Dataset | Size | Languages | Domain | Link |
|---------|------|-----------|--------|------|
| Trilingual Hindi-English-Nepali | 200,000+ aligned triples | HI-EN-NE | - | [Kaggle: sundeepdawadi/cleaned-word2word-en-hi-ne](https://www.kaggle.com/datasets/sundeepdawadi/cleaned-word2word-en-hi-ne) |
| English-Nepali Translation (HF) | - | EN-NE | Instruction-tuned | [HF: ashokpoudel/nepali-english-translation-dataset](https://huggingface.co/datasets/ashokpoudel/nepali-english-translation-dataset) |
| Bidirectional English-Nepali MT for Legal Domain | 125,000 legal sentences | EN-NE | Legal | [ACL Paper](https://aclanthology.org/2024.sigul-1.7.pdf) |
| CLE Parallel Corpus | - | EN-NE-UR | - | [AI4Bharat: indicnlp_catalog](https://github.com/AI4Bharat/indicnlp_catalog) |

---
---
## Historical and Shared Tasks

| Dataset | Event | Link |
|---------|-------|------|
| WMT19 Parallel Corpus | Shared task | [statmt.org/wmt19](https://www.statmt.org/wmt19/parallel-corpus-filtering.html) |
| FLORES 101 Dataset | Multilingual benchmark | [GitHub: facebookresearch/flores](https://github.com/facebookresearch/flores/tree/main/floresv1/data) |

---
---
## Instruction Tuning

| Dataset | Languages | Type | Link |
|---------|-----------|------|------|
| Bactrian-X | 50+ languages (includes Nepali) | Instruction tuning | [HF: MBZUAI/Bactrian-X](https://huggingface.co/datasets/MBZUAI/Bactrian-X) |
| Aya Dataset | 101 languages (includes Nepali) | Instruction tuning | [HF: cohere/aya_dataset](https://huggingface.co/datasets/cohere/aya_dataset) |

---

# Speech and Audio Datasets

Audio data for automatic speech recognition and text-to-speech synthesis.

---

## Large-Scale ASR

| Dataset | Size | Description | Link |
|---------|------|-------------|------|
| OpenSLR-54 (Large Nepali ASR) | 157,000 utterances, 400+ hours | Google-supported, professional quality | [openslr.org/54](https://www.openslr.org/54/) |
| Mozilla Common Voice (Nepali) | Crowdsourced speech, 100k+ clips available | Diverse speakers | [commonvoice.mozilla.org/en/datasets](https://commonvoice.mozilla.org/en/datasets) |
| Nepali Speech to Text Dataset (Parliamentary) | 1,000+ utterances | From Parliament sessions (formal speech) | [Kaggle: ishworsubedii/nepali-speech-to-text-dataset](https://www.kaggle.com/datasets/ishworsubedii/nepali-speech-to-text-dataset) |
| Nepali Automatic Speech Recognition (HF) | Combined ASR dataset | For transcription | [HF: amitpant7/Nepali-Automatic-Speech-Recognition](https://huggingface.co/amitpant7/Nepali-Automatic-Speech-Recognition) |
| ASR Nepali 1 Large | 50,000+ audio files | With transcriptions | [Kaggle: sonismaharjan/asr-nepali-1-large](https://www.kaggle.com/datasets/sonismaharjan/asr-nepali-1-large) |
| Amit Pant Nepali Speech-to-Text | 2,650 rows, 949 MB | Combined from OpenSLR SLR43 and Mozilla Common Voice, cleaned for ASR | [HF: amitpant7/nepali-speech-to-text](https://huggingface.co/datasets/amitpant7/nepali-speech-to-text) |
| Rishi70612 Nepali ASR | 5+ hours, 35 speakers | YouTube-sourced Nepali speech, 30-second chunks | [HF: rishi70612/nepali_asr](https://huggingface.co/datasets/rishi70612/nepali_asr) |
| DarviLab Nepali ASR Community Data | - | Community-contributed ASR data | [HF: darvilab/nepali-asr-community-data](https://huggingface.co/datasets/darvilab/nepali-asr-community-data) |
| Spktsagar OpenSLR Nepali ASR (Cleaned) | - | Cleaned version of OpenSLR Nepali ASR | [HF: spktsagar/openslr-nepali-asr-cleaned](https://huggingface.co/datasets/spktsagar/openslr-nepali-asr-cleaned) |
| IamTangsang OpenSLR54 Nepali ASR | - | OpenSLR54 Nepali ASR dataset | [HF: iamTangsang/OpenSLR54-Nepali-ASR](https://huggingface.co/datasets/iamTangsang/OpenSLR54-Nepali-ASR) |
| Zaxis018 Nepali Speech to Text | - | Speech recognition | [GitHub: Zaxis018/Nepali_speech_to_text](https://github.com/Zaxis018/Nepali_speech_to_text) |

---
---
## TTS and Synthesized Speech

| Dataset | Size | Description | Link |
|---------|------|-------------|------|
| OpenSLR-43 (High quality TTS) | High-quality single-speaker TTS data | Professional recording | [openslr.org/43](https://www.openslr.org/43/) |
| Nepali Singing Voice Data | Audio + lyrics | For singing voice synthesis (music domain) | [Kaggle: pujancozu/nepali-singing-voice-data](https://www.kaggle.com/datasets/pujancozu/nepali-singing-voice-data) |

---
---
## Speech Analysis and Emotion

| Dataset | Size | Description | Link |
|---------|------|-------------|------|
| Nepali Speech Emotion Detection | 3,000+ speech samples | With 6 emotion labels | [Kaggle: ashalupreti/nepali-speech-emotion-detection-dataset](https://www.kaggle.com/datasets/ashalupreti/nepali-speech-emotion-detection-dataset) |
| Newari Music Classification | Audio classification | For Newari (related language) music | [Kaggle: pujancozu/newari-music](https://www.kaggle.com/datasets/pujancozu/newari-music) |

---
---
## Multilingual Benchmarks

| Dataset | Description | Link |
|---------|-------------|------|
| Google FLEURS | Multilingual benchmark including Nepali (101 languages) | [HF: google/fleurs](https://huggingface.co/datasets/google/fleurs) |

---

# Computer Vision Datasets

Datasets for image/video captioning, object detection, and multimodal learning.

---

## Sign Language and Gesture

| Dataset | Size | Description | Link |
|---------|------|-------------|------|
| Nepali Sign Language Character Dataset | 36 characters x 1,000 images = 36,000 total | Sign language recognition | [Kaggle: biratpoudelrocks/nepali-sign-language-character-dataset](https://www.kaggle.com/datasets/biratpoudelrocks/nepali-sign-language-character-dataset) |
| Nepali Sign Language Video Dataset (Zenodo) | 630 professional videos | 1,205 gestures with frame annotations, research-grade | [Zenodo: 10478554](https://zenodo.org/records/10478554) |
| Birat-Poudel Nepali Sign Language Character Dataset | 36 characters x 1,000 images = 36,000 total | Plain and random background versions, organized by character folders | [HF: Birat-Poudel/Nepali-Sign-Language-Character-Dataset](https://huggingface.co/datasets/Birat-Poudel/Nepali-Sign-Language-Character-Dataset) |

---
---
## Image Captioning and Multimodal

| Dataset | Size | Description | Link |
|---------|------|-------------|------|
| Flickr8k Nepali Captioning | 8,000 images x 5 Nepali captions = 40,000 captions | Adapted from Flickr8k English | [GitHub: bipeshrajsubedi/Flickr8k_Nepali_Dataset](https://github.com/bipeshrajsubedi/Flickr8k_Nepali_Dataset) |
| Nepali Video Captioning (MSVD) | 1,500+ videos | With Nepali descriptions | [Kaggle: kabitaparajuli/video-captioning-in-nepali-msvd-dataset](https://www.kaggle.com/datasets/kabitaparajuli/video-captioning-in-nepali-msvd-dataset) |
| MSVD Nepali Dataset | 1,500+ videos | Video captioning | [Kaggle: bipeshrajsubedi/msvd-nepali-dataset](https://www.kaggle.com/datasets/bipeshrajsubedi/msvd-nepali-dataset) |

---
---
## Face Recognition and Emotion

| Dataset | Size | Description | Link |
|---------|------|-------------|------|
| Nepali Celeb Localized Face Dataset | 500+ Nepali celebrities | With face bounding boxes | [GitHub: amitpant7/Nepali-Celeb-Localized-Face-Dataset](https://github.com/amitpant7/Nepali-Celeb-Localized-Face-Dataset) |
| Facial Emotion Detection for Nepali Ethnic Groups | 6,000+ facial images | With 7 emotion labels | [Kaggle: suchanasubedi/facial-emotion-detection-for-nepali-ethnic-groups](https://www.kaggle.com/datasets/suchanasubedi/facial-emotion-detection-for-nepali-ethnic-groups) |

---
---
## Domain-Specific Objects

| Dataset | Size | Description | Link |
|---------|------|-------------|------|
| Nepali Currency Dataset | 5,000+ currency note images | Banknote denomination classification | [Kaggle: uashutoshk/nepali-currency-dataset](https://www.kaggle.com/datasets/uashutoshk/nepali-currency-dataset) |
| Nepali Food Images | 3,000+ images | Of traditional Nepali dishes | [Kaggle: saurabkunwar/nepali-food-images](https://www.kaggle.com/datasets/saurabkunwar/nepali-food-images) |
| Nepali Cultural Dress and Ornaments | 2,000+ images | Of traditional clothing and artifacts | [Kaggle: bimarshakhanal/nepali-cultural-dress-and-ornaments](https://www.kaggle.com/datasets/bimarshakhanal/nepali-cultural-dress-and-ornaments) |
| Nepali Vehicle Dataset | 4,797 images | Two-wheeler and four-wheeler vehicles from Nepal | [Kaggle: sdevkota007/vehicles-nepal-dataset](https://www.kaggle.com/datasets/sdevkota007/vehicles-nepal-dataset) |
| Nepali Vehicle Dataset (Aryal) | - | Nepali vehicle images | [Kaggle: aryalrupesh/nepli-vehicle-dataset](https://www.kaggle.com/datasets/aryalrupesh/nepli-vehicle-dataset) |
| Vehicles Dataset Nepal | - | General vehicle dataset | [Kaggle: ishworsubedii/vehicles-dataset-nepal](https://www.kaggle.com/datasets/ishworsubedii/vehicles-dataset-nepal) |

---
---
## Geospatial and Remote Sensing

| Dataset | Size | Task | Description | Link |
|---------|------|------|-------------|------|
| Nepal Landslide Dataset | 230 GeoTIFF images + PNG masks | Semantic segmentation | Landslide scar detection for U-Net, scars in white, background in black | [Zenodo: 3675410](https://zenodo.org/records/3675410) / [Zenodo: 3688363](https://zenodo.org/records/3688363) |

---

# OCR and Handwriting Datasets

Character recognition, document digitization, and license plate detection.

---

## Handwriting and Character Recognition

| Dataset | Size | Description | Link |
|---------|------|-------------|------|
| Nepali Handwriting Characters | Handwritten character images | For OCR training | [Kaggle: mohanbhandari/nepali-handwriting-characters](https://www.kaggle.com/datasets/mohanbhandari/nepali-handwriting-characters) |
| Handwritten Devanagari Character Dataset | 10,500+ images | Of Devanagari script (applicable to Nepali) | [Kaggle: sa9arr/handwritten-devanagari-character-dataset](https://www.kaggle.com/datasets/sa9arr/handwritten-devanagari-character-dataset) |
| Nepali Handwritten Images for Text Detection | Document-level | Handwritten images for text detection | [Kaggle: sweekardahal/nepali-handwritten-images-for-text-detection](https://www.kaggle.com/datasets/sweekardahal/nepali-handwritten-images-for-text-detection) |
| Dahalsweekar Nepali Handwritten Dataset Major Collection | Comprehensive | Camera-captured images of Nepali handwritten text from various regions | [GitHub: dahalsweekar/Nepali-Handwritten-Dataset-Major-Collection](https://github.com/dahalsweekar/Nepali-Handwritten-Dataset-Major-Collection) |
| Kaushu42 Nepali OCR | - | Handwriting recognition for Nepali characters | [GitHub: kaushu42/nepali-ocr](https://github.com/kaushu42/nepali-ocr) |
| Prasanna1991 DHCD Dataset | - | Dataset of Devanagari (Nepali) handwritten characters | [GitHub: Prasanna1991/DHCD_Dataset](https://github.com/Prasanna1991/DHCD_Dataset) |
| Deejungx NHCR | - | Nepali Handwritten Character Recognition using DHCD dataset | [GitHub: deejungx/nhcr](https://github.com/deejungx/nhcr) |
| Rugz007 Devnagri OCR | - | Optical Character Recognition for Devanagari using TensorFlow 2 (96.63% accuracy) | [GitHub: Rugz007/Devnagri-OCR](https://github.com/Rugz007/Devnagri-OCR) |
| Yashuv Handwritten Devanagari OCR | - | CNN + OpenCV for 46 classes (36 consonants + 10 numerals), 98% accuracy | [GitHub: yashuv/Handwritten-Devnagari-Optical-Character-Recognition](https://github.com/yashuv/Handwritten-Devnagari-Optical-Character-Recognition) |
| Nepali Handwritten Character Recognition (Zenodo) | Research dataset | Detailed annotations for handwritten characters | [Zenodo: 7472398](https://zenodo.org/records/7472398) |
| Improving Tesseract-OCR for Nepali (Zenodo) | 5,000+ images | Preprocessing techniques for OCR improvement | [Zenodo: 4361896](https://zenodo.org/records/4361896) |
| Gauravgiri Nepali OCR Dataset | - | Nepali OCR dataset | [HF: gauravgiri/nepali-ocr-dataset](https://huggingface.co/datasets/gauravgiri/nepali-ocr-dataset) |
| Nahcol Nepali OCR Dataset | - | Nepali OCR dataset | [Kaggle: nahcol/nepali-ocr-dataset](https://www.kaggle.com/datasets/nahcol/nepali-ocr-dataset) |

---
---
## License Plate and Vehicle Recognition

| Dataset | Size | Description | Link |
|---------|------|-------------|------|
| Nepali License Plate (ALPR) V2 | 2,000+ license plate images | For automatic license plate recognition | [Kaggle: ishworsubedii/alpr-v2](https://www.kaggle.com/datasets/ishworsubedii/alpr-v2) |
| Nepali Motorbike Backplate Labeled | 1,500+ motorcycle plate images | With bounding boxes | [Kaggle: saugat111/nepali-moterbike-backplate-lbled](https://www.kaggle.com/datasets/saugat111/nepali-moterbike-backplate-lbled) |

---

# Lexicons and Linguistic Resources

Linguistic resources, dictionaries, and instruction-tuned datasets.

---

## Dictionaries and Word Lists

| Resource | Size | Type | Link |
|----------|------|------|------|
| Sabdabikash Synonym Word List | 50,000+ Nepali words | Thesaurus | [Kaggle: thenepaliguy/sabdabikash-synonym-nepali-word-list](https://www.kaggle.com/datasets/thenepaliguy/sabdabikash-synonym-nepali-word-list) |
| Nepali Dictionary | 25,000+ entries | Definitions and examples | [Kaggle: sangamthapa/nepali-dictionary](https://www.kaggle.com/datasets/sangamthapa/nepali-dictionary) |
| Nepali Stopwords | 400+ words | Filtering | [Kaggle: sangamthapa/nepali-stopwords](https://www.kaggle.com/datasets/sangamthapa/nepali-stopwords) |
| Nepali Brihat Sabdakosh JSON | 122,000 words | Comprehensive dictionary (JSON format) | [GitHub: bikashpadhikari/nepali-brihat-sabdakosh-json](https://github.com/bikashpadhikari/nepali-brihat-sabdakosh-json) |
| Nepali Names | - | Person names | [GitHub: datafiction/oya-nepali-nlp/blob/master/data/names/Nepali.txt](https://github.com/datafiction/oya-nepali-nlp/blob/master/data/names/Nepali.txt) |
| Dummy Nepali People Information | - | Synthetic person data | [GitHub: bibhuticoder/dummydata/blob/master/data.csv](https://github.com/bibhuticoder/dummydata/blob/master/data.csv) |
| Nepali Unigrams Cleaned | 200k+ unique words | Vocabulary with frequency | [Kaggle: thenepaliguy/nepali-unigrams-cleaned](https://www.kaggle.com/datasets/thenepaliguy/nepali-unigrams-cleaned) |
| Nepali Transliteral Dataset | - | Transliteration (Unicode Nepali to Latin script mapping) | [GitHub: SushilShrestha/NepaliTransliteralDataset](https://github.com/SushilShrestha/NepaliTransliteralDataset) |

---
---
## Morphology and Syntax

| Resource | Size | Type | Link |
|----------|------|------|------|
| Nepali POS Data (UPOS Mapped) | 3,000+ tagged sentences | POS tags following Universal Dependencies standard | [Kaggle: thenepaliguy/nepali-pos](https://www.kaggle.com/datasets/thenepaliguy/nepali-pos) |
| Nepali Word-Lemma Gold Data | 5,000+ words | Manual lemmatization annotations | [GitHub: dpakpdl/NepaliLemmatizer/tree/master/Lemmatization/data/manually_annotated_corpus](https://github.com/dpakpdl/NepaliLemmatizer/tree/master/Lemmatization/data/manually_annotated_corpus) |
| Universal Dependencies (UD) Nepali | 17,500+ tokens | Full syntactic dependency annotations (official UD project) | [GitHub: UniversalDependencies/UD_Nepali-NPP](https://github.com/UniversalDependencies/UD_Nepali-NPP) |

---
---
## Instruction Tuning and Multilingual

| Resource | Languages | Type | Link |
|----------|-----------|------|------|
| Bactrian-X (Instruction Tuning) | Nepali included in multilingual instruction-tuning dataset (50+ languages) | [HF: MBZUAI/Bactrian-X](https://huggingface.co/datasets/MBZUAI/Bactrian-X) |
| Aya Dataset (Instruction Tuning) | Nepali included in community-driven instruction dataset (101 languages) | [HF: cohere/aya_dataset](https://huggingface.co/datasets/cohere/aya_dataset) |

---

# Pre-trained Models and Embeddings

Pre-computed word vectors and language models with training datasets.

---

## Large Language Models

| Model | Parameters | Training Data | Link |
|-------|------------|---------------|------|
| IRIISNEPAL RoBERTa | 110M params | 27.5 GB from 99 news sites | [HF: IRIISNEPAL/RoBERTa_Nepali_110M](https://huggingface.co/IRIISNEPAL/RoBERTa_Nepali_110M) |
| NepaliBERT | - | 4.6 GB, 85k+ articles | [HF: Shushant/nepaliBERT](https://huggingface.co/Shushant/nepaliBERT) |
| DistilGPT2-Nepali | - | 13M Nepali sequences (OSCAR + CC100 + Wikipedia) | [HF: Sakonii/distilgpt2-nepali](https://huggingface.co/Sakonii/distilgpt2-nepali) |
| Nepali Text Generation (Transformer) | - | Custom | [GitHub: NirajanBekoju/Transformer-Based-Nepali-Language-Model](https://github.com/NirajanBekoju/Transformer-Based-Nepali-Language-Model) |
| NepBERTa | - | GLUE benchmark baseline | [nepberta.github.io](https://nepberta.github.io/) |
| NepaliGPT | - | - | [arXiv: 2506.16399](https://arxiv.org/abs/2506.16399) |
| Sidskarki Qwen3 ASR Nepali | - | Qwen3 model fine-tuned for Nepali ASR | [HF: sidskarki/Qwen3-ASR-Nepali](https://huggingface.co/sidskarki/Qwen3-ASR-Nepali) |

---
---
## Word Embeddings

| Embedding | Dimensions | Vocabulary | Link |
|-----------|------------|------------|------|
| Nepali Word2Vec from scratch | Custom-trained 300D vectors | With training scripts | [GitHub: R4j4n/Nepali-Word2Vec-from-scratch](https://github.com/R4j4n/Nepali-Word2Vec-from-scratch) |
| 300D Word2Vec Embeddings for Nepali Language | Pre-computed 300D vectors | 20k+ words | [GitHub: rabindralamsal/Word2Vec-Embeddings-for-Nepali-Language](https://github.com/rabindralamsal/Word2Vec-Embeddings-for-Nepali-Language) |
| Nepali FastText Word Vectors | Official FastText vectors | Common Crawl + Wikipedia | [fastText: crawl-vectors](https://github.com/facebookresearch/fastText/blob/master/docs/crawl-vectors.md) |

---
---
## Fine-tuned Models

| Model | Task | Dataset | Link |
|-------|------|---------|------|
| Fine-tuned DistilBERT on 16 Newsgroup | News classification | - | [HF: Suyogyart/nepali-16-newsgroups-classification](https://huggingface.co/Suyogyart/nepali-16-newsgroups-classification) |

---

# Tools and Frameworks

Complete NLP toolkits and utilities for Nepali processing.

| Tool | Description | Link |
|------|-------------|------|
| Nepali Lemmatizer | Rule-based lemmatization with training data | [GitHub: dpakpdl/NepaliLemmatizer/tree/master/Lemmatization/data](https://github.com/dpakpdl/NepaliLemmatizer/tree/master/Lemmatization/data) |
| Nepali Transliteration | Script conversion dataset for transliteration tasks | [Kaggle: saugatkafley/nepali-transliteration](https://www.kaggle.com/datasets/saugatkafley/nepali-transliteration) |
| Audinp (Data Collector) | Tool for collecting speech data (contributed to OpenSLR-54) | [GitHub: SUBOdhar/audinp](https://github.com/SUBOdhar/audinp) |
| BISH-100 (AI Anchor) | Synthetic video dataset with AI-generated Nepali anchor | [Kaggle: bisheshworneupane/bish-100-nepali-text-driven-ai-anchor](https://www.kaggle.com/datasets/bisheshworneupane/bish-100-nepali-text-driven-ai-anchor) |
| Fine-tuned DistilBERT on 16 Newsgroup Dataset | Ready-to-use classifier for news categorization | - | [HF: Suyogyart/nepali-16-newsgroups-classification](https://huggingface.co/Suyogyart/nepali-16-newsgroups-classification) |
| Pemagrg1 Nepali-Datasets | Comprehensive list of Nepali dataset sources | [GitHub: pemagrg1/Nepali-Datasets](https://github.com/pemagrg1/Nepali-Datasets) |
| IOST-ASCOL Nepali Datasets | Curated collection of ML, NLP, audio, images, and geospatial data | [GitHub: IOST-ASCOL/nepali-datasets](https://github.com/IOST-ASCOL/nepali-datasets) |
| CodeforNepal Data | Open data repository for Nepal | [GitHub: CodeforNepal/data](https://github.com/CodeforNepal/data) |
| Sandip BG Nepal Data | Nepal-related datasets | [GitHub: sandipbgt/nepal-data](https://github.com/sandipbgt/nepal-data) |
| Open Knowledge Nepal | Open knowledge resources | [GitHub: openknowledgenp](https://github.com/openknowledgenp) |
| R4j4n Nepali-Dataset | Additional Nepali datasets | [GitHub: R4j4n/Nepali-Dataset](https://github.com/R4j4n/Nepali-Dataset) |
| Madan Baduwal CV Datasets | Computer vision datasets for Nepal | [GitHub: madanbaduwal/cv-datasets](https://github.com/madanbaduwal/cv-datasets) |
| HBVJ99 Nepal-Datasets | Various Nepal datasets | [GitHub: hbvj99/Nepal-Datasets](https://github.com/hbvj99/Nepal-Datasets) |
| Kaushu42 Nepali OCR | Handwriting recognition for Nepali characters | [GitHub: kaushu42/nepali-ocr](https://github.com/kaushu42/nepali-ocr) |
| Prasanna1991 DHCD Dataset | Dataset of Devanagari (Nepali) handwritten characters | [GitHub: Prasanna1991/DHCD_Dataset](https://github.com/Prasanna1991/DHCD_Dataset) |
| Deejungx NHCR | Nepali Handwritten Character Recognition using DHCD dataset | [GitHub: deejungx/nhcr](https://github.com/deejungx/nhcr) |
| Rugz007 Devnagri OCR | Optical Character Recognition for Devanagari using TensorFlow 2 (96.63% accuracy) | [GitHub: Rugz007/Devnagri-OCR](https://github.com/Rugz007/Devnagri-OCR) |
| Yashuv Handwritten Devanagari OCR | CNN + OpenCV for 46 classes (36 consonants + 10 numerals), 98% accuracy | [GitHub: yashuv/Handwritten-Devnagari-Optical-Character-Recognition](https://github.com/yashuv/Handwritten-Devnagari-Optical-Character-Recognition) |

---

# Research Papers

Peer-reviewed publications on Nepali NLP and related work.

---

## Recent and High-Impact (2024-2026)

| Paper | Year | Focus | Link |
|-------|------|-------|------|
| NepaliGPT: A Generative Language Model for the Nepali Language | 2025 | Recent LLM research | [arXiv: 2506.16399](https://arxiv.org/abs/2506.16399) |
| NLUE (Nepali Language Understanding Evaluation) | 2024 | 9 NLU tasks with comprehensive benchmark | [arXiv: 2411.19244](https://arxiv.org/abs/2411.19244) |
| IRIISNEPAL RoBERTa: State-of-the-art Nepali LM | 2024 | 27.5 GB training corpus from 99 news sites | [arXiv: 2411.15734](https://arxiv.org/abs/2411.15734) |
| Code-Mixed Nepali-English Abuse Detection | 2025 | 5k annotated code-mixed dataset | [arXiv: 2504.21026](https://arxiv.org/abs/2504.21026) |
| Nepali Transformers at NLU of Devanagari Script Languages 2025 | 2025 | Transformer architectures for Devanagari | [ACL: 2025.chipsal-1.36](https://aclanthology.org/2025.chipsal-1.36/) |
| Application of Nepali Large Language Models to Improve Sentiment | 2024 | LLM applications | [ACM](https://dl.acm.org/doi/10.1145/3647782.3647804) |
| NepKanun: A RAG-Based Nepali Legal Assistant | 2025 | RAG systems for legal domain | [OpenReview](https://openreview.net/forum?id=LuXTBI6GSh) |
| Exploring NLP Challenges for Nepali | 2024 | Overview of remaining challenges | [Preprints: 202409.1229](https://www.preprints.org/manuscript/202409.1229) |

---
---
## Sentiment Analysis and Classification

| Paper | Focus | Link |
|-------|-------|------|
| Aspect Based Sentiment Analysis of Nepali Text Using SVM and Naive Bayes | Comparative ML approach | [ResearchGate](https://www.researchgate.net/publication/346441002_Aspect_Based_Sentiment_Analysis_of_Nepali_Text_Using_Support_Vector_Machine_and_Naive_Bayes) |
| An Analysis of Classification Algorithms for Nepali News | Benchmark of various classifiers | [ResearchGate](https://www.researchgate.net/publication/343228516_An_Analysis_of_Classification_Algorithms_for_Nepali_News) |
| Nepali Text Document Classification Using Deep Neural Network | Deep learning approaches | [NEPJOL](https://www.nepjol.info/index.php/TUJ/article/view/28677) |

---
---
## NLP Tasks and Applications

| Paper | Task | Link |
|-------|------|------|
| A Machine Learning Approach to Anaphora Resolution in Nepali Language | Pronoun resolution task | [IEEE](https://ieeexplore.ieee.org/document/9200135) |
| Nepali Image Captioning | Vision-language multimodal task | [IEEE: 8947436](https://ieeexplore.ieee.org/abstract/document/8947436) |
| Named-Entity Based Sentiment Analysis of Nepali News Media Texts | NER + sentiment joint modeling | [ACL Anthology](https://aclanthology.org/2020.nlptea-1.16.pdf) |
| Topic Modeling for Nepali Political News | Topic analysis in news domain | [IEEE: 11004776](https://ieeexplore.ieee.org/document/11004776/) |

---
---
## Linguistic and Historical

| Paper | Focus | Link |
|-------|-------|------|
| Natural language processing for Nepali text: a review | Comprehensive NLP review | [Springer](https://link.springer.com/article/10.1007/s10462-021-10093-1) |
| A Descriptive Grammar of Nepali and an Analyzed Corpus | Linguistic grammar reference | [Google Books](https://books.google.com.np/books?id=Z_JoCIRN_xwC) |
| Nepali Spell Checker 1.1 and the Thesaurus | Early spell checking research | [Wayback: NEP05.pdf](https://web.archive.org/web/20131020064957/http://www.panl10n.net/english/final%20reports/pdf%20files/Nepal/NEP05.pdf) |
| Nepali Spell Checker | Earlier spell checking work | [Wayback: NEP04.pdf](https://web.archive.org/web/20150105024511/http://www.panl10n.net/english/final%20reports/pdf%20files/Nepal/NEP04.pdf) |

---
---
## Research Aggregators

| Resource | Description | Link |
|----------|-------------|------|
| List of more Nepali NLP papers | Comprehensive tracker (maintained) | [GitHub: RayGone/Nepali-NLP-Progress](https://github.com/RayGone/Nepali-NLP-Progress) |
| Nepali NLP Progress (divyamani1) | Community-maintained research tracker | [GitHub: divyamani1/Nepali-NLP-Progress](https://github.com/divyamani1/Nepali-NLP-Progress) |
| Curated List of Nepali NLP Resources (Ghimire Sunil) | Comprehensive resource list | [GitHub: ghimiresunil/Curated-List-of-Nepali-NLP-Resources](https://github.com/ghimiresunil/Curated-List-of-Nepali-NLP-Resources) |
| Nepali NLP Resources (rameshhpathak) | Tools and dataset aggregator with descriptions | [GitHub: rameshhpathak/nepali-nlp-resources](https://github.com/rameshhpathak/nepali-nlp-resources) |

---

# Open Data and Government Resources

Official government datasets and open data portals.

| Resource | Description | Link |
|----------|-------------|------|
| Open Data Nepal | Official open data portal with 500+ government datasets (health, education, infrastructure) | [opendatanepal.com](https://opendatanepal.com/) |
| Census Nepal | Official census data from Central Bureau of Statistics (demographic, geographic, economic) | [censusnepal.cbs.gov.np/results](https://censusnepal.cbs.gov.np/results) |
| Nepal Multi-District Weather Dataset (2020-2025) | Meteorological data across districts | [Kaggle: dipeshthapa1/nepal-multi-district-weather-dataset-2020-2025](https://www.kaggle.com/datasets/dipeshthapa1/nepal-multi-district-weather-dataset-2020-2025) |
| Nepal Earthquake Seismicity Dataset (1990-2026) | Historical earthquake data | [Kaggle: amansinghnp/nepal-earthquake-seismicity-dataset-1990-2026](https://www.kaggle.com/datasets/amansinghnp/nepal-earthquake-seismicity-dataset-1990-2026) |
| House Price Dataset Nepal | Real estate pricing | [Kaggle: nishanpokh/house-price-dataset-nepal](https://www.kaggle.com/datasets/nishanpokh/house-price-dataset-nepal) |
| Nepal Trekking Dataset | Tourism routes | [Kaggle: bibekrai44/nepal-treking-dataset](https://www.kaggle.com/datasets/bibekrai44/nepal-treking-dataset) |
| Nepali Election Results Historical | Political data | [Kaggle: dimanjung/nepali-election-results-historical](https://www.kaggle.com/datasets/dimanjung/nepali-election-results-historical) |
| Gender Based Violence in Nepal 2019-2026 | Social data | [Kaggle: aneeshmhj/gender-based-violence-in-nepal-2019-2026](https://www.kaggle.com/datasets/aneeshmhj/gender-based-violence-in-nepal-2019-2026) |

---

# Additional Resources

---

## Specialized Collections and Aggregators

| Resource | Description | Link |
|----------|-------------|------|
| Comprehensive Nepali Datasets (IOST-ASCOL) | Aggregated NLP, speech, image, geospatial datasets | [GitHub: IOST-ASCOL/nepali-datasets](https://github.com/IOST-ASCOL/nepali-datasets) |
| ML Datasets for Nepal | Curated ML resources including Laxmi Prasad Devkota Poems (119k characters) and Brihat Sabdakosh | [GitHub: amitness/ml-datasets](https://github.com/amitness/ml-datasets) |
| IndicNLP Catalog (AI4Bharat) | Official Indic language resources (11 languages including Nepali) | [ai4bharat.github.io/indicnlp_catalog](https://ai4bharat.github.io/indicnlp_catalog/) |

---
---
## Code-Mixed and Multilingual NLP Datasets

| Dataset | Description | Link |
|---------|-------------|------|
| Code-Mixed Nepali-English Abuse Detection | 5,000 Nepali-English code-mixed comments | Social media |
| Nepali-English Code-Switched LID, POS, NER, Sentiment | Complete NLP pipeline for code-mixed data | [GitHub: sagorbrur/codeswitch](https://github.com/sagorbrur/codeswitch) |
| CLE Parallel Corpus (AI4Bharat) | English-Nepali-Urdu parallel data | Multilingual |

---

## **Legal and Government Text Corpora**

### **Constitution and Acts**

| Dataset | Size | Description | Link |
|---------|------|-------------|------|
| **Nepal Constitution Dataset** | - | Complete Nepali Constitution text | [HF: ranjitraut/nepal-constitution-dataset](https://huggingface.co/datasets/ranjitraut/nepal-constitution-dataset) |
| **Nepal Section-wise Act Datasets** | - | Collection of Nepali legal acts organized by sections | [HF: ranjitraut/nepal-section-wise-act-datasets](https://huggingface.co/datasets/ranjitraut/nepal-section-wise-act-datasets) |

---

## **Computer Vision Datasets**

---

### **Domain-Specific Objects**

| Dataset | Size | Description | Link |
|---------|------|-------------|------|
| Nepali Currency Dataset | 5,000+ currency note images | Banknote denomination classification | [Kaggle: uashutoshk/nepali-currency-dataset](https://www.kaggle.com/datasets/uashutoshk/nepali-currency-dataset) |
| **Nepali Currency High-Resolution Image Datasets** | - | High-resolution images of Nepali currency notes | [Kaggle: theranjitraut/nepali-currency-high-resolution-image-datasets](https://www.kaggle.com/datasets/theranjitraut/nepali-currency-high-resolution-image-datasets) |
| Nepali Food Images | 3,000+ images | Of traditional Nepali dishes | [Kaggle: saurabkunwar/nepali-food-images](https://www.kaggle.com/datasets/saurabkunwar/nepali-food-images) |
| Nepali Cultural Dress and Ornaments | 2,000+ images | Of traditional clothing and artifacts | [Kaggle: bimarshakhanal/nepali-cultural-dress-and-ornaments](https://www.kaggle.com/datasets/bimarshakhanal/nepali-cultural-dress-and-ornaments) |
| Nepali Vehicle Dataset | 4,797 images | Two-wheeler and four-wheeler vehicles from Nepal | [Kaggle: sdevkota007/vehicles-nepal-dataset](https://www.kaggle.com/datasets/sdevkota007/vehicles-nepal-dataset) |
| Nepali Vehicle Dataset (Aryal) | - | Nepali vehicle images | [Kaggle: aryalrupesh/nepli-vehicle-dataset](https://www.kaggle.com/datasets/aryalrupesh/nepli-vehicle-dataset) |
| Vehicles Dataset Nepal | - | General vehicle dataset | [Kaggle: ishworsubedii/vehicles-dataset-nepal](https://www.kaggle.com/datasets/ishworsubedii/vehicles-dataset-nepal) |

### **Sports**

| Dataset | Size | Description | Link |
|---------|------|-------------|------|
| **Futvar Football Players Detection Dataset** | - | Football (soccer) players detection for object detection tasks | [Roboflow: ranjit-raut-do9me/futvar-football-players-detection-dataset](https://universe.roboflow.com/ranjit-raut-do9me/futvar-football-players-detection-dataset) |

---

---
## Ethical Considerations

- **Sentiment/Hate Speech Data:** Contains potentially offensive language; bias mitigation recommended for model training
- **Social Media Data (Tweets, Instagram):** May contain personal information; use with GDPR/privacy compliance
- **Copyright:** Wikipedia, news articles sourced responsibly; attribution recommended
- **Multilingual Data:** Code-mixed datasets reflect real-world language use; social biases may be present

---
---
## Quick Links

- **Hugging Face Nepali Datasets**: [huggingface.co/datasets?language=language:ne](https://huggingface.co/datasets?language=language:ne)
- **GitHub Nepali NLP**: [github.com/search?q=nepali+nlp](https://github.com/search?q=nepali+nlp)
- **ACL Anthology (Nepali Papers)**: [aclanthology.org](https://aclanthology.org/)
- **arXiv (Nepali Research)**: [arxiv.org/search/?query=nepali](https://arxiv.org/search/?query=nepali)
- **IndicNLP Catalog**: [ai4bharat.github.io/indicnlp_catalog](https://ai4bharat.github.io/indicnlp_catalog/)

---
---
## Dataset Summary

| Category | Count | Description |
|----------|-------|-------------|
| Text Corpus | 30+ | Ultra-large, large curated, and specialized text collections |
| NLP Datasets | 40+ | Classification, NER, QA, Summarization, Sentiment, Hate Speech |
| Translation Data | 15+ | Parallel corpora for EN-NE, HI-NE, UR-NE, and multilingual |
| Speech and Audio | 15+ | ASR, TTS, emotion detection datasets |
| Computer Vision | 15+ | Sign language, image captioning, face recognition, object detection |
| OCR and Handwriting | 15+ | Character recognition, license plate detection |
| Lexicons | 10+ | Dictionaries, stopwords, POS data, word embeddings |
| Pre-trained Models | 10+ | RoBERTa, BERT, GPT2, word embeddings |
| Benchmarks | 10+ | NLUE, Nep-gLUE, FLORES-101, IndicBench |
| Research Papers | 25+ | Recent publications and historical works |
| Tools and Frameworks | 15+ | NLP toolkits, utilities, dataset aggregators |
| Open Data | 10+ | Government and public datasets |

---
---
## Dataset Search Guide

---

### General Web Search Strategies

---

#### Google Search Operators for Nepali Datasets

| Search Type | Query Template | Example |
|-------------|----------------|---------|
| Basic dataset search | Nepali dataset OR "nepali" dataset OR nepali corpus site:PLATFORM | Nepali NLP dataset site:github.com |
| Recent datasets (2024-2026) | Nepali dataset (2024 OR 2025 OR 2026) site:PLATFORM | Nepali dataset 2025 site:huggingface.co |
| Specific task | Nepali [TASK] dataset OR corpus | Nepali OCR dataset |
| File type filter | Nepali dataset filetype:json OR filetype:csv OR filetype:zip | Nepali NER dataset filetype:json |
| Language code filter | language:ne OR language:nep OR nepali language dataset | language:ne dataset site:huggingface.co |
| Devanagari script | Devanagari dataset OR "Devanagari script" dataset | Devanagari OCR dataset |
| Code-mixed data | Nepali-English code-mixed dataset OR code-switched | Nepali-English code-mixed sentiment dataset |
| Academic sources | Nepali dataset site:arxiv.org OR site:zenodo.org OR site:researchgate.net | Nepali NLP dataset site:zenodo.org |

#### Google Advanced Search Tips
- Use "Nepali" OR "nepali" OR "ne" to catch all variations
- Add site: operator to limit to specific platforms
- Use intitle: to find datasets in titles: intitle:"Nepali dataset"
- Use inurl: to find in URLs: inurl:nepali inurl:dataset
- Filter by date: Click "Tools" -> "Any time" -> "Past year" or custom range
- Use filetype: to find specific formats: filetype:csv Nepali

---

### Hugging Face Datasets Search

---

#### Direct Search Methods

**Web Interface Search**
- Main page: [https://huggingface.co/datasets](https://huggingface.co/datasets)
- Language filter: Click "Language" -> Select "Nepali (ne)" or search language:ne
- Search bar: Type nepali or ne or language:ne

#### Advanced Search Queries

| Query | Result | Link |
|-------|--------|------|
| language:ne | All Nepali language datasets | [HF: datasets?language=ne](https://huggingface.co/datasets?language=ne) |
| nepali | Datasets with "nepali" in name/description | [HF: datasets?q=nepali](https://huggingface.co/datasets?q=nepali) |
| other=nepali | Datasets tagged with Nepali | [HF: datasets?other=nepali](https://huggingface.co/datasets?other=nepali) |
| nepali AND asr | Nepali ASR datasets | [HF: datasets?q=nepali+asr](https://huggingface.co/datasets?q=nepali+asr) |
| nepali AND (ocr OR vision OR image) | Nepali CV datasets | [HF: datasets?q=nepali+(ocr+OR+vision+OR+image)](https://huggingface.co/datasets?q=nepali+(ocr+OR+vision+OR+image)) |
| nepali AND (ner OR sentiment OR classification) | Nepali NLP datasets | [HF: datasets?q=nepali+(ner+OR+sentiment+OR+classification)](https://huggingface.co/datasets?q=nepali+(ner+OR+sentiment+OR+classification)) |
| nepali AND translation | Translation datasets | [HF: datasets?q=nepali+translation](https://huggingface.co/datasets?q=nepali+translation) |
| nepali AND (2024 OR 2025 OR 2026) | Recent datasets | [HF: datasets?q=nepali+(2024+OR+2025+OR+2026)](https://huggingface.co/datasets?q=nepali+(2024+OR+2025+OR+2026)) |

#### Sorting and Filtering
- Sort by: "Most recent", "Most downloads", "Most likes"
- Filter by: Task (text-classification, automatic-speech-recognition, etc.)
- Filter by: License (MIT, Apache, Creative Commons)
- Filter by: Size (Small <1GB, Medium 1-10GB, Large >10GB)

#### Hugging Face API Search
```python
from datasets import load_dataset_builder
from huggingface_hub import HfApi

# Method 1: Using HfApi
api = HfApi()
datasets = api.list_datasets(filter="nepali")
for ds in datasets:
    print(f"{ds.id} - {ds.description}")

# Method 2: Using load_dataset_builder
try:
    dataset = load_dataset_builder("nepali-dataset-name")
    print(dataset.info)
except:
    print("Dataset not found")

# Method 3: Search with language filter
from huggingface_hub import list_datasets
datasets = list_datasets(filter="language:ne")
```

#### Hugging Face CLI
```bash
# Install: pip install huggingface_hub
huggingface-cli scan-cache
huggingface-cli list datasets --filter nepali
huggingface-cli download dataset-name
```

#### Browser Bookmarklets
Create bookmarklets for quick access:

**All Nepali Datasets:**
```javascript
javascript:window.location.href='https://huggingface.co/datasets?language=ne'
```

**Nepali ASR Datasets:**
```javascript
javascript:window.location.href='https://huggingface.co/datasets?q=nepali+automatic-speech-recognition&sort=modified'
```

**Nepali NLP Datasets:**
```javascript
javascript:window.location.href='https://huggingface.co/datasets?q=nepali+(ner+OR+sentiment+OR+classification)&sort=downloads'
```

---

### GitHub Search Strategies

---

#### Direct Search Methods

**GitHub Web Search**
- Main search: [https://github.com/search](https://github.com/search)
- Advanced search: [https://github.com/search/advanced](https://github.com/search/advanced)

#### Search Queries

| Query | Result | Link |
|-------|--------|------|
| nepali dataset | All Nepali dataset repos | [GitHub: nepali dataset](https://github.com/search?q=nepali+dataset) |
| nepali nlp | NLP-related repos | [GitHub: nepali nlp](https://github.com/search?q=nepali+nlp) |
| nepali corpus | Text corpus repos | [GitHub: nepali corpus](https://github.com/search?q=nepali+corpus) |
| nepali ocr | OCR datasets | [GitHub: nepali ocr](https://github.com/search?q=nepali+ocr) |
| nepali speech | Speech/audio datasets | [GitHub: nepali speech](https://github.com/search?q=nepali+speech) |
| nepali computer vision | CV datasets | [GitHub: nepali computer vision](https://github.com/search?q=nepali+computer+vision) |
| nepali handwritten | Handwriting datasets | [GitHub: nepali handwritten](https://github.com/search?q=nepali+handwritten) |
| nepali sign language | Sign language datasets | [GitHub: nepali sign language](https://github.com/search?q=nepali+sign+language) |
| language:nepali | Repos with Nepali as primary language | [GitHub: language:nepali](https://github.com/search?l=nepali) |
| topic:nepali-nlp | NLP topic repos | [GitHub: topic:nepali-nlp](https://github.com/topics/nepali-nlp) |
| topic:nepali-dataset | Dataset topic repos | [GitHub: topic:nepali-dataset](https://github.com/topics/nepali-dataset) |
| topic:nepali-character-recognition | OCR/character recognition | [GitHub: topic:nepali-character-recognition](https://github.com/topics/nepali-character-recognition) |

#### GitHub Advanced Filters
- Sort by: "Recently updated", "Most stars", "Most forks"
- Filter by: Language (Python, Jupyter Notebook, etc.)
- Filter by: License (MIT, Apache, etc.)
- Filter by: Date range (Created/Updated)
- Filter by: Repository type (Public, Sources, Forks)

#### GitHub API Search
```python
import requests
import json

# Search repositories
url = "https://api.github.com/search/repositories"
params = {
    "q": "nepali dataset language:python",
    "sort": "updated",
    "order": "desc",
    "per_page": 100
}
headers = {"Accept": "application/vnd.github.v3+json"}

response = requests.get(url, params=params, headers=headers)
repos = response.json()["items"]
for repo in repos:
    print(f"{repo['name']} - {repo['html_url']} - Stars: {repo['stargazers_count']}")

# Search code
url = "https://api.github.com/search/code"
params = {
    "q": "nepali dataset extension:json OR extension:csv",
    "per_page": 100
}
response = requests.get(url, params=params, headers=headers)
```

#### GitHub CLI (gh)
```bash
# Install: https://cli.github.com/
gh auth login

# Search repos
gh search repos "nepali dataset" --sort updated --order desc
gh search repos "nepali nlp" --language python
gh search repos "topic:nepali-dataset"

# Clone found repos
gh repo clone OWNER/REPO
```

#### GitHub Topics to Follow
- [nepali-nlp](https://github.com/topics/nepali-nlp)
- [nepali-dataset](https://github.com/topics/nepali-dataset)
- [nepali-ocr](https://github.com/topics/nepali-ocr)
- [nepali-character-recognition](https://github.com/topics/nepali-character-recognition)
- [devanagari-character-dataset](https://github.com/topics/devanagari-character-dataset)

---

### Kaggle Search Strategies

---

#### Direct Search Methods

**Kaggle Web Search**
- Main datasets page: [https://www.kaggle.com/datasets](https://www.kaggle.com/datasets)
- Search bar: Type nepali or nepali dataset

#### Search Queries

| Query | Result | Link |
|-------|--------|------|
| nepali | All Nepali datasets | [Kaggle: nepali](https://www.kaggle.com/datasets?search=nepali) |
| nepali nlp | NLP datasets | [Kaggle: nepali nlp](https://www.kaggle.com/datasets?search=nepali+nlp) |
| nepali ocr | OCR datasets | [Kaggle: nepali ocr](https://www.kaggle.com/datasets?search=nepali+ocr) |
| nepali speech | Speech datasets | [Kaggle: nepali speech](https://www.kaggle.com/datasets?search=nepali+speech) |
| nepali computer vision | CV datasets | [Kaggle: nepali computer vision](https://www.kaggle.com/datasets?search=nepali+computer+vision) |
| nepali handwritten | Handwriting datasets | [Kaggle: nepali handwritten](https://www.kaggle.com/datasets?search=nepali+handwritten) |
| nepali sign language | Sign language datasets | [Kaggle: nepali sign language](https://www.kaggle.com/datasets?search=nepali+sign+language) |
| nepali text | Text datasets | [Kaggle: nepali text](https://www.kaggle.com/datasets?search=nepali+text) |
| nepali classification | Classification datasets | [Kaggle: nepali classification](https://www.kaggle.com/datasets?search=nepali+classification) |
| nepali sentiment | Sentiment datasets | [Kaggle: nepali sentiment](https://www.kaggle.com/datasets?search=nepali+sentiment) |

#### Kaggle Tags
- Language tag: [Nepali (16979)](https://www.kaggle.com/datasets?tags=16979-Nepali)
- Task tags: computer-vision, nlp, audio, text-classification, etc.
- Combined: [Computer Vision + Nepali](https://www.kaggle.com/datasets?tags=13207-Computer+Vision,16979-Nepali)

#### Kaggle Advanced Filters
- Sort by: "Most Votes", "Most Recent", "Most Views", "Most Downloads"
- Filter by: License (CC0, CC-BY, Apache, etc.)
- Filter by: Size (Small, Medium, Large)
- Filter by: Usability (Public, Private)

#### Kaggle API Search
```python
from kaggle.api.kaggle_api_extended import KaggleApi

api = KaggleApi()
api.authenticate()

# Search datasets
datasets = api.dataset_list(search="nepali")
for ds in datasets:
    print(f"{ds.ref} - {ds.title}")

# Download dataset
api.dataset_download_files('username/dataset-name', path='./data', unzip=True)

# Search with filters
datasets = api.dataset_list(
    search="nepali",
    tag_ids=["16979"],  # Nepali language tag
    sort_by="votes",
    max_size="1GB"
)
```

#### Kaggle CLI
```bash
# Install: pip install kaggle
kaggle datasets list -s nepali
kaggle datasets list -s "nepali nlp"
kaggle datasets list -s nepali --sort-by votes
kaggle datasets download username/dataset-name
```

---
---
### Roboflow Search Strategies

---

#### Direct Search Methods

**Roboflow Universe Search**
- Main page: [https://universe.roboflow.com/](https://universe.roboflow.com/)
- Search bar: Type nepali or nepali dataset

#### Search Queries

| Query | Result | Link |
|-------|--------|------|
| nepali | All Nepali datasets | [Roboflow: nepali](https://universe.roboflow.com/search?query=nepali) |
| nepali object detection | Object detection datasets | [Roboflow: nepali object detection](https://universe.roboflow.com/search?query=nepali+object+detection) |
| nepali classification | Classification datasets | [Roboflow: nepali classification](https://universe.roboflow.com/search?query=nepali+classification) |
| nepali sign language | Sign language datasets | [Roboflow: nepali sign language](https://universe.roboflow.com/search?query=nepali+sign+language) |
| nepali vehicle | Vehicle detection datasets | [Roboflow: nepali vehicle](https://universe.roboflow.com/search?query=nepali+vehicle) |
| nepali currency | Currency detection | [Roboflow: nepali currency](https://universe.roboflow.com/search?query=nepali+currency) |
| nepali food | Food recognition | [Roboflow: nepali food](https://universe.roboflow.com/search?query=nepali+food) |
| nepali cultural | Cultural heritage | [Roboflow: nepali cultural](https://universe.roboflow.com/search?query=nepali+cultural) |
| devanagari | Devanagari script datasets | [Roboflow: devanagari](https://universe.roboflow.com/search?query=devanagari) |
| nepali character | Character recognition | [Roboflow: nepali character](https://universe.roboflow.com/search?query=nepali+character) |

#### Roboflow Filters
- Task type: Object Detection, Classification, Segmentation, etc.
- License: Public, Private, Commercial
- Image count: Filter by number of images
- Last updated: Filter by recency
- Annotations: Bounding boxes, polygons, etc.

#### Roboflow API Search
```python
import requests

# Search datasets
url = "https://universe.roboflow.com/api/search"
params = {
    "query": "nepali",
    "page": 1,
    "per_page": 20
}
headers = {"Accept": "application/json"}

response = requests.get(url, params=params, headers=headers)
datasets = response.json()["results"]
for ds in datasets:
    print(f"{ds['name']} - {ds['url']} - Images: {ds['image_count']}")

# Get dataset details
dataset_id = "dataset-id"
url = f"https://universe.roboflow.com/api/dataset/{dataset_id}"
response = requests.get(url, headers=headers)
dataset = response.json()
```

#### Roboflow CLI
```bash
# Install: pip install roboflow
from roboflow import Roboflow
rf = Roboflow(api_key="YOUR_API_KEY")

# Search datasets
datasets = rf.search("nepali")
for ds in datasets:
    print(ds)

# Download dataset
project = rf.workspace("workspace-name").project("project-name")
dataset = project.version(1).download("yolov8")
```

---
---
### Zenodo Search Strategies

---

#### Direct Search Methods

**Zenodo Web Search**
- Main page: [https://zenodo.org/](https://zenodo.org/)
- Search bar: Type nepali dataset or nepali

#### Search Queries

| Query | Result | Link |
|-------|--------|------|
| nepali dataset | All Nepali datasets | [Zenodo: nepali dataset](https://zenodo.org/search?page=1&size=20&q=nepali+dataset) |
| nepali nlp | NLP datasets | [Zenodo: nepali nlp](https://zenodo.org/search?q=nepali+nlp) |
| nepali ocr | OCR datasets | [Zenodo: nepali ocr](https://zenodo.org/search?q=nepali+ocr) |
| nepali handwritten | Handwriting datasets | [Zenodo: nepali handwritten](https://zenodo.org/search?q=nepali+handwritten) |
| nepali speech | Speech datasets | [Zenodo: nepali speech](https://zenodo.org/search?q=nepali+speech) |
| nepali computer vision | CV datasets | [Zenodo: nepali computer vision](https://zenodo.org/search?q=nepali+computer+vision) |
| nepal landslide | Landslide datasets | [Zenodo: nepal landslide](https://zenodo.org/search?q=nepal+landslide) |
| nepali sign language | Sign language datasets | [Zenodo: nepali sign language](https://zenodo.org/search?q=nepali+sign+language) |
| devanagari | Devanagari script | [Zenodo: devanagari](https://zenodo.org/search?q=devanagari) |
| subject:"computer vision" nepali | CV datasets | [Zenodo: CV Nepali](https://zenodo.org/search?q=subject%3A%22computer+vision%22+nepali) |

#### Zenodo Advanced Filters
- Type: Dataset, Software, Publication, etc.
- Subject: Computer Science, Linguistics, etc.
- Date range: Filter by publication date
- Access: Open Access, Restricted, etc.
- License: Creative Commons, MIT, etc.

#### Zenodo API Search
```python
import requests

# Search datasets
url = "https://zenodo.org/api/records/"
params = {
    "q": "nepali dataset",
    "type": "dataset",
    "size": 20,
    "page": 1
}
headers = {"Accept": "application/json"}

response = requests.get(url, params=params, headers=headers)
datasets = response.json()["hits"]["hits"]
for ds in datasets:
    print(f"{ds['metadata']['title']} - {ds['links']['html']}")

# Get specific dataset
record_id = "1234567"
url = f"https://zenodo.org/api/records/{record_id}"
response = requests.get(url, headers=headers)
dataset = response.json()
```

#### Popular Nepali Datasets on Zenodo
- [Nepal Landslide Dataset for Semantic Segmentation](https://zenodo.org/records/3675410) (ID: 3675410)
- [Nepal Landslide Dataset](https://zenodo.org/records/3688363) (ID: 3688363)
- [Nepali Handwritten Character Recognition](https://zenodo.org/records/7472398) (ID: 7472398)
- [Improving Tesseract-OCR for Nepali](https://zenodo.org/records/4361896) (ID: 4361896)
- [Nepali Sign Language Video Dataset](https://zenodo.org/records/10478554) (ID: 10478554)

---
---
### Other Dataset Platforms

---

#### Open Data Portals

**Open Data Nepal**
- Website: [https://opendatanepal.com/](https://opendatanepal.com/)
- Search: Use the search bar for "dataset", "nepali", or specific domains
- Categories: Agriculture, Education, Health, Infrastructure, Population, etc.
- API: [https://opendatanepal.com/api/](https://opendatanepal.com/api/)

**Search queries:**
- [https://opendatanepal.com/search?q=nepali](https://opendatanepal.com/search?q=nepali)
- [https://opendatanepal.com/datasets](https://opendatanepal.com/datasets)

**Government of Nepal Data Portal**
- Census Nepal: [https://censusnepal.cbs.gov.np/](https://censusnepal.cbs.gov.np/)
- National Statistics: [https://www.cbs.gov.np/](https://www.cbs.gov.np/)
- Open Government Data: [https://data.gov.np/](https://data.gov.np/)

**World Bank Open Data (Nepal)**
- Website: [https://data.worldbank.org/country/nepal](https://data.worldbank.org/country/nepal)
- API: [https://datahelpdesk.worldbank.org/knowledgebase/articles/898581](https://datahelpdesk.worldbank.org/knowledgebase/articles/898581)

```python
import requests
import pandas as pd

# World Bank API for Nepal data
url = "https://api.worldbank.org/v2/country/NPL/indicator"
params = {
    "format": "json",
    "per_page": 100
}
response = requests.get(url, params=params)
data = response.json()
```

#### Academic Repositories

**IEEE Dataport**
- Website: [https://ieee-dataport.org/](https://ieee-dataport.org/)
- Search: [https://ieee-dataport.org/open-access/large-scale-nepali-text-corpus](https://ieee-dataport.org/open-access/large-scale-nepali-text-corpus)
- Query: nepali dataset or nepali corpus

**Figshare**
- Website: [https://figshare.com/](https://figshare.com/)
- Search: [https://figshare.com/search?q=nepali+dataset](https://figshare.com/search?q=nepali+dataset)

**Dryad**
- Website: [https://datadryad.org/](https://datadryad.org/)
- Search: [https://datadryad.org/search?q=nepali](https://datadryad.org/search?q=nepali)

**Harvard Dataverse**
- Website: [https://dataverse.harvard.edu/](https://dataverse.harvard.edu/)
- Search: [https://dataverse.harvard.edu/search?q=nepali](https://dataverse.harvard.edu/search?q=nepali)

**Mendeley Data**
- Website: [https://data.mendeley.com/](https://data.mendeley.com/)
- Search: [https://data.mendeley.com/datasets?search=nepali](https://data.mendeley.com/datasets?search=nepali)

#### Specialized AI/ML Platforms

**Papers With Code (Datasets)**
- Website: [https://paperswithcode.com/datasets](https://paperswithcode.com/datasets)
- Search: [https://paperswithcode.com/datasets?search=nepali](https://paperswithcode.com/datasets?search=nepali)

**Google Dataset Search**
- Website: [https://datasetsearch.research.google.com/](https://datasetsearch.research.google.com/)
- Search: nepali dataset or nepali corpus
- Query: [https://datasetsearch.research.google.com/search?query=nepali%20dataset](https://datasetsearch.research.google.com/search?query=nepali%20dataset)

**Advanced queries:**
- nepali dataset site:huggingface.co
- nepali corpus site:kaggle.com
- nepali nlp site:github.com

**Data.gov (US) - International Data**
- Website: [https://data.gov/](https://data.gov/)
- Search: [https://catalog.data.gov/dataset?tags=nepal](https://catalog.data.gov/dataset?tags=nepal)

**AWS Open Data Registry**
- Website: [https://registry.opendata.aws/](https://registry.opendata.aws/)
- Search: Nepali or Nepal-related datasets

**Microsoft Research Open Data**
- Website: [https://msropendata.com/](https://msropendata.com/)
- Search: [https://msropendata.com/datasets?search=nepali](https://msropendata.com/datasets?search=nepali)

#### Social Media and Community Platforms

**Reddit**
- Subreddits:
  - r/MachineLearning: [https://www.reddit.com/r/MachineLearning/search/?q=nepali%20dataset](https://www.reddit.com/r/MachineLearning/search/?q=nepali%20dataset)
  - r/datasets: [https://www.reddit.com/r/datasets/search/?q=nepali](https://www.reddit.com/r/datasets/search/?q=nepali)
  - r/Nepal: [https://www.reddit.com/r/Nepal/search/?q=dataset](https://www.reddit.com/r/Nepal/search/?q=dataset)

**Search operators:**
- nepali dataset OR corpus OR collection
- site:reddit.com nepali nlp

**Twitter/X**
- Search: [https://twitter.com/search?q=nepali%20dataset](https://twitter.com/search?q=nepali%20dataset)
- Advanced: nepali dataset lang:en or nepali corpus since:2024-01-01

**LinkedIn**
- Search: [https://www.linkedin.com/search/results/content/?keywords=nepali%20dataset](https://www.linkedin.com/search/results/content/?keywords=nepali%20dataset)

**Discord and Slack Communities**
- Join Nepali NLP, AI4Bharat, Hugging Face Discord servers
- Search for #nepali-datasets or #nepali-nlp channels

#### Niche Platforms

**OpenSLR (Speech and Audio)**
- Website: [https://www.openslr.org/](https://www.openslr.org/)
- Nepali datasets:
  - [SLR43: Nepali TTS](https://www.openslr.org/43/)
  - [SLR54: Nepali ASR](https://www.openslr.org/54/)
  - [SLR80: Multilingual ASR including Nepali](https://www.openslr.org/80/)

**LDC (Linguistic Data Consortium)**
- Website: [https://www.ldc.upenn.edu/](https://www.ldc.upenn.edu/)
- Search: [https://catalog.ldc.upenn.edu/LDC/](https://catalog.ldc.upenn.edu/LDC/)
- Query: nepali or nepali language

**ELRA (European Language Resources Association)**
- Website: [https://catalog.elra.info/](https://catalog.elra.info/)
- Search: [https://catalog.elra.info/en-us/repository/browse/ELRA-W0077/](https://catalog.elra.info/en-us/repository/browse/ELRA-W0077/) (English-Nepali Parallel Corpus)

**Common Voice (Mozilla)**
- Website: [https://commonvoice.mozilla.org/](https://commonvoice.mozilla.org/)
- Nepali: [https://commonvoice.mozilla.org/en/datasets](https://commonvoice.mozilla.org/en/datasets) -> Filter by Nepali

**Flickr (Image Datasets)**
- Website: [https://www.flickr.com/](https://www.flickr.com/)
- Search: [https://www.flickr.com/search/?text=nepali](https://www.flickr.com/search/?text=nepali)
- API: Use Flickr API with tags: nepali, nepal, devanagari

**Wikimedia Commons**
- Website: [https://commons.wikimedia.org/](https://commons.wikimedia.org/)
- Search: [https://commons.wikimedia.org/wiki/Category:Nepal](https://commons.wikimedia.org/wiki/Category:Nepal)
- API: [https://commons.wikimedia.org/w/api.php](https://commons.wikimedia.org/w/api.php)

---
---
### Advanced Search Techniques
---

#### Boolean Search Operators

| Operator | Example | Result |
|----------|---------|--------|
| AND | nepali AND dataset | Both terms must appear |
| OR | nepali OR nepali OR ne | Any term can appear |
| NOT | nepali NOT english | Excludes "english" |
| Quotes | "nepali dataset" | Exact phrase |
| Parentheses | (nepali OR nepali) AND (dataset OR corpus) | Grouped logic |
| Wildcard | nepali* | Matches nepali, nepalis, etc. |
| Site | site:huggingface.co nepali dataset | Only on Hugging Face |
| Filetype | nepali dataset filetype:json | Only JSON files |
| Intitle | intitle:"nepali dataset" | In page title |
| Inurl | inurl:nepali inurl:dataset | In URL |

#### Regular Expression Search

Use regex for more precise matching:

| Pattern | Example | Matches |
|---------|---------|---------|
| nepali[\s-]?dataset | nepali dataset, nepali-dataset | Both variations |
| (nepali\|nepali) | nepali or nepali | Either spelling |
| \bnepali\b | Whole word "nepali" | Not "nepalis" or "nepalese" |
| nepali.*corpus | nepali corpus, nepali text corpus | Any text between |
| dataset.*nepali.*202[4-6] | Recent Nepali datasets | Datasets from 2024-2026 |

#### Semantic Search with LLMs

Use Large Language Models to find datasets:

```python
from langchain_community.vectorstores import Chroma
from langchain_community.embeddings import HuggingFaceEmbeddings
from langchain.text_splitter import CharacterTextSplitter
from langchain_community.document_loaders import WebBaseLoader
from langchain_core.prompts import ChatPromptTemplate
from langchain_core.runnables import RunnablePassthrough
from langchain_core.output_parsers import StrOutputParser

# Method 1: Semantic search on dataset descriptions
model_name = "sentence-transformers/all-mpnet-base-v2"
embeddings = HuggingFaceEmbeddings(model_name=model_name)

# Load dataset metadata
loader = WebBaseLoader(["https://huggingface.co/datasets?language=ne"])
docs = loader.load()
text_splitter = CharacterTextSplitter(chunk_size=1000, chunk_overlap=200)
texts = text_splitter.split_documents(docs)

# Create vector store
db = Chroma.from_documents(texts, embeddings)
retriever = db.as_retriever(search_kwargs={"k": 5})

# Query
query = "Find Nepali OCR datasets with handwritten characters"
docs = retriever.invoke(query)
for doc in docs:
    print(doc.page_content)

# Method 2: LLM-powered search
template = """You are an expert at finding Nepali datasets.
Given the user's query, suggest relevant search terms and platforms.

Query: {query}
Suggestions:"""

prompt = ChatPromptTemplate.from_template(template)
chain = (
    {"query": RunnablePassthrough()}
    | prompt
    | model
    | StrOutputParser()
)

result = chain.invoke("I need Nepali speech recognition datasets")
print(result)
```

---
---
### Mobile and Browser Tools

---

#### Browser Extensions

**Dataset Search Extensions**
- Google Dataset Search Extension: Quick access to Google Dataset Search
- Hugging Face Quick Search: Add HF search to your browser
- GitHub Octotree: Better GitHub repo navigation

**Custom Search Engines (Chrome)**
Create custom search engines in Chrome:

**Hugging Face Nepali Datasets:**
- Name: Hugging Face Nepali
- Keyword: hfnep
- URL: https://huggingface.co/datasets?q=%s+language:ne

**GitHub Nepali:**
- Name: GitHub Nepali
- Keyword: ghnep
- URL: https://github.com/search?q=%s+nepali

**Kaggle Nepali:**
- Name: Kaggle Nepali
- Keyword: knep
- URL: https://www.kaggle.com/datasets?search=%s+nepali

**Usage:** Type hfnep ocr in Chrome address bar -> searches Hugging Face for "ocr language:ne"

#### Mobile Apps

**GitHub Mobile App**
- Search for nepali dataset or nepali nlp
- Save searches for quick access

**Kaggle Mobile**
- Browse datasets by language: Nepali
- Follow Nepali dataset tags

**Hugging Face Mobile**
- Access datasets on mobile browser
- Bookmark Nepali language filter

**Custom Shortcuts (iOS/Android)**
Create shortcuts for frequent searches:

**iOS Shortcut for Nepali Datasets:**
1. Open Shortcuts app
2. Create new shortcut
3. Add "Open URLs" action
4. URL: https://huggingface.co/datasets?language=ne
5. Name: "Nepali Datasets"

**Android Widget:**
Use browser bookmark widgets with pre-saved searches

---
---
### Automated Dataset Discovery

---

#### Python Script for Multi-Platform Search

```python
import requests
import json
from datetime import datetime, timedelta
from typing import List, Dict, Optional

class NepaliDatasetSearcher:
    def __init__(self):
        self.platforms = {
            "huggingface": "https://huggingface.co/api/datasets",
            "github": "https://api.github.com/search/repositories",
            "kaggle": "https://www.kaggle.com/api/v1/datasets/list",
            "zenodo": "https://zenodo.org/api/records/",
            "roboflow": "https://universe.roboflow.com/api/search"
        }
        self.headers = {
            "User-Agent": "NepaliDatasetSearcher/1.0",
            "Accept": "application/json"
        }

    def search_huggingface(self, query: str = "nepali", language: str = "ne",
                          task: Optional[str] = None, limit: int = 20) -> List[Dict]:
        """Search Hugging Face datasets"""
        url = f"{self.platforms['huggingface']}?search={query}"
        if language:
            url += f"&language={language}"
        if task:
            url += f"&task={task}"
        url += f"&limit={limit}"

        response = requests.get(url, headers=self.headers)
        if response.status_code == 200:
            return response.json().get("datasets", [])
        return []

    def search_github(self, query: str = "nepali dataset", language: Optional[str] = None,
                     sort: str = "updated", order: str = "desc", limit: int = 20) -> List[Dict]:
        """Search GitHub repositories"""
        params = {
            "q": query,
            "sort": sort,
            "order": order,
            "per_page": limit
        }
        if language:
            params["q"] += f" language:{language}"

        response = requests.get(self.platforms['github'], params=params, headers=self.headers)
        if response.status_code == 200:
            return response.json().get("items", [])
        return []

    def search_kaggle(self, query: str = "nepali", limit: int = 20) -> List[Dict]:
        """Search Kaggle datasets (requires API key)"""
        from kaggle.api.kaggle_api_extended import KaggleApi
        api = KaggleApi()
        api.authenticate()

        datasets = []
        try:
            results = api.dataset_list(search=query, max_size=limit)
            for r in results:
                datasets.append({
                    "ref": r.ref,
                    "title": r.title,
                    "category": r.category,
                    "voteCount": r.voteCount,
                    "downloadCount": r.downloadCount,
                    "url": f"https://www.kaggle.com/datasets/{r.ref}"
                })
        except Exception as e:
            print(f"Kaggle API error: {e}")
        return datasets

    def search_zenodo(self, query: str = "nepali dataset", limit: int = 20) -> List[Dict]:
        """Search Zenodo records"""
        params = {
            "q": query,
            "type": "dataset",
            "size": limit,
            "page": 1
        }
        response = requests.get(self.platforms['zenodo'], params=params, headers=self.headers)
        if response.status_code == 200:
            hits = response.json().get("hits", {}).get("hits", [])
            return [{"title": h["metadata"]["title"],
                     "url": h["links"]["html"],
                     "date": h["metadata"].get("publication_date"),
                     "description": h["metadata"].get("description")}
                    for h in hits]
        return []

    def search_roboflow(self, query: str = "nepali", limit: int = 20) -> List[Dict]:
        """Search Roboflow Universe"""
        params = {"query": query, "page": 1, "per_page": limit}
        response = requests.get(self.platforms['roboflow'], params=params, headers=self.headers)
        if response.status_code == 200:
            return response.json().get("results", [])
        return []

    def search_all(self, query: str = "nepali", limit: int = 10) -> Dict[str, List[Dict]]:
        """Search all platforms"""
        results = {
            "huggingface": self.search_huggingface(query, limit=limit),
            "github": self.search_github(query, limit=limit),
            "zenodo": self.search_zenodo(query, limit=limit),
            "roboflow": self.search_roboflow(query, limit=limit)
        }

        try:
            results["kaggle"] = self.search_kaggle(query, limit=limit)
        except:
            results["kaggle"] = []

        return results

    def get_recent_datasets(self, days: int = 30, limit: int = 20) -> Dict[str, List[Dict]]:
        """Get datasets updated in last N days"""
        since_date = (datetime.now() - timedelta(days=days)).strftime("%Y-%m-%d")

        results = {
            "huggingface": self.search_huggingface(
                query=f"nepali updated:>{since_date}",
                limit=limit
            ),
            "github": self.search_github(
                query=f"nepali dataset created:>{since_date}",
                sort="updated",
                limit=limit
            ),
            "zenodo": self.search_zenodo(
                query=f"nepali dataset",
                limit=limit
            )
        }
        return results

# Usage
searcher = NepaliDatasetSearcher()

# Search all platforms
all_results = searcher.search_all("nepali ocr", limit=5)
for platform, datasets in all_results.items():
    print(f"\n=== {platform.upper()} ===")
    for ds in datasets[:3]:
        print(f"- {ds.get('title', ds.get('name', ds.get('ref', 'N/A')))}")
        print(f"  {ds.get('url', ds.get('html_url', 'N/A'))}")

# Get recent datasets
recent = searcher.get_recent_datasets(days=7, limit=5)
print("\n=== RECENT DATASETS (Last 7 days) ===")
for platform, datasets in recent.items():
    if datasets:
        print(f"\n{platform}: {len(datasets)} new datasets")
```

#### Scheduled Dataset Monitoring

Set up a cron job or scheduled task to check for new Nepali datasets:

```python
import schedule
import time
from nepali_dataset_searcher import NepaliDatasetSearcher

def check_new_datasets():
    searcher = NepaliDatasetSearcher()
    recent = searcher.get_recent_datasets(days=1, limit=10)

    new_datasets = []
    for platform, datasets in recent.items():
        if datasets:
            new_datasets.append(f"Found {len(datasets)} new datasets on {platform}")

    if new_datasets:
        print("\n".join(new_datasets))
        send_notification("\n".join(new_datasets))

def send_notification(message: str):
    """Send notification via email, Slack, etc."""
    webhook_url = "YOUR_SLACK_WEBHOOK"
    payload = {"text": f"New Nepali Datasets Alert!\n{message}"}
    requests.post(webhook_url, json=payload)

# Schedule daily checks
schedule.every().day.at("09:00").do(check_new_datasets)
schedule.every().day.at("21:00").do(check_new_datasets)

while True:
    schedule.run_pending()
    time.sleep(3600)
```

#### GitHub Actions for Dataset Monitoring

Create a `.github/workflows/monitor-datasets.yml` file:

```yaml
name: Monitor Nepali Datasets
on:
  schedule:
    - cron: '0 9,21 * * *'
  workflow_dispatch:

jobs:
  check-datasets:
    runs-on: ubuntu-latest
    steps:
      - uses: actions/checkout@v4
      - name: Set up Python
        uses: actions/setup-python@v4
        with:
          python-version: '3.10'

      - name: Install dependencies
        run: |
          python -m pip install --upgrade pip
          pip install requests kaggle huggingface_hub

      - name: Run dataset monitor
        env:
          KAGGLE_USERNAME: ${{ secrets.KAGGLE_USERNAME }}
          KAGGLE_KEY: ${{ secrets.KAGGLE_KEY }}
          SLACK_WEBHOOK: ${{ secrets.SLACK_WEBHOOK }}
        run: |
          python scripts/monitor_datasets.py

      - name: Commit updates
        run: |
          git config --global user.name "Dataset Monitor"
          git config --global user.email "monitor@example.com"
          git add data/new_datasets.json
          git commit -m "Update: New Nepali datasets found [$(date +%Y-%m-%d)]"
          git push
```

Create `scripts/monitor_datasets.py`:

```python
import json
import os
from datetime import datetime
from nepali_dataset_searcher import NepaliDatasetSearcher

def load_existing_datasets(filepath: str = "data/known_datasets.json") -> set:
    if os.path.exists(filepath):
        with open(filepath, 'r') as f:
            return set(json.load(f))
    return set()

def save_datasets(datasets: set, filepath: str = "data/known_datasets.json"):
    with open(filepath, 'w') as f:
        json.dump(list(datasets), f, indent=2)

def get_dataset_id(dataset: Dict, platform: str) -> str:
    if platform == "huggingface":
        return f"hf:{dataset.get('id', dataset.get('name', ''))}"
    elif platform == "github":
        return f"gh:{dataset.get('full_name', '')}"
    elif platform == "kaggle":
        return f"kg:{dataset.get('ref', '')}"
    elif platform == "zenodo":
        return f"zd:{dataset.get('id', dataset.get('recid', ''))}"
    elif platform == "roboflow":
        return f"rf:{dataset.get('id', dataset.get('name', ''))}"
    return f"{platform}:{str(dataset)}"

def main():
    searcher = NepaliDatasetSearcher()
    known_datasets = load_existing_datasets()
    new_datasets = []

    all_results = searcher.search_all(limit=50)

    for platform, datasets in all_results.items():
        for ds in datasets:
            ds_id = get_dataset_id(ds, platform)
            if ds_id not in known_datasets:
                known_datasets.add(ds_id)
                new_datasets.append({
                    "id": ds_id,
                    "platform": platform,
                    "name": ds.get('name', ds.get('title', ds.get('ref', 'Unknown'))),
                    "url": ds.get('url', ds.get('html_url', ds.get('links', {}).get('html', '#'))),
                    "date": ds.get('last_modified', ds.get('created_at', ds.get('metadata', {}).get('publication_date', ''))),
                    "description": ds.get('description', '')
                })

    save_datasets(known_datasets)

    if new_datasets:
        message = f"Found {len(new_datasets)} new Nepali datasets!\n\n"
        for ds in new_datasets[:10]:
            message += f"• [{ds['name']}]({ds['url']}) ({ds['platform']})\n"

        with open("data/new_datasets.json", "w") as f:
            json.dump(new_datasets, f, indent=2)

        if os.getenv("SLACK_WEBHOOK"):
            import requests
            payload = {"text": message}
            requests.post(os.getenv("SLACK_WEBHOOK"), json=payload)

        print(message)
    else:
        print("No new datasets found.")

if __name__ == "__main__":
    main()
```

---
---
### Dataset Comparison and Selection Tools

---

#### Dataset Comparison Table Generator

```python
import pandas as pd
from tabulate import tabulate

def compare_datasets(datasets: List[Dict]) -> pd.DataFrame:
    comparison_data = []

    for ds in datasets:
        comparison_data.append({
            "Name": ds.get("name", "N/A"),
            "Platform": ds.get("platform", "N/A"),
            "Size": ds.get("size", "N/A"),
            "Task": ds.get("task", ds.get("category", "N/A")),
            "License": ds.get("license", "N/A"),
            "Last Updated": ds.get("last_modified", ds.get("date", "N/A")),
            "Downloads": ds.get("downloadCount", ds.get("downloads", "N/A")),
            "Stars": ds.get("stargazers_count", "N/A"),
            "URL": ds.get("url", "#")
        })

    df = pd.DataFrame(comparison_data)
    return df

# Example usage
datasets = [
    {
        "name": "IRIIS-RESEARCH Nepali Text Corpus",
        "platform": "Hugging Face",
        "size": "10.1 GB",
        "task": "Text Corpus",
        "license": "MIT",
        "last_modified": "2024-11-15",
        "downloads": "5,000+",
        "url": "https://huggingface.co/datasets/IRIIS-RESEARCH/Nepali-Text-Corpus"
    },
    {
        "name": "Amit Pant Nepali Speech-to-Text",
        "platform": "Hugging Face",
        "size": "949 MB",
        "task": "ASR",
        "license": "Apache 2.0",
        "last_modified": "2025-02-20",
        "downloads": "2,000+",
        "url": "https://huggingface.co/datasets/amitpant7/nepali-speech-to-text"
    }
]

df = compare_datasets(datasets)
print(tabulate(df, headers='keys', tablefmt='grid', showindex=False))
```

#### Dataset Quality Scoring

```python
from datetime import datetime

def score_dataset(dataset: Dict) -> float:
    score = 0.0

    # Platform weight
    platform_weights = {
        "huggingface": 10,
        "github": 8,
        "kaggle": 9,
        "zenodo": 7,
        "roboflow": 8
    }
    score += platform_weights.get(dataset.get("platform", ""), 5)

    # Size weight (logarithmic scale)
    size_str = str(dataset.get("size", "")).lower()
    if "gb" in size_str:
        score += 15
    elif "mb" in size_str:
        score += 10
    elif "kb" in size_str:
        score += 5

    # License weight
    good_licenses = ["mit", "apache", "cc by", "cc0", "bsd", "gpl"]
    license_str = str(dataset.get("license", "")).lower()
    if any(lic in license_str for lic in good_licenses):
        score += 15

    # Recency weight
    date_str = dataset.get("last_modified", dataset.get("date", ""))
    if date_str:
        try:
            date = datetime.strptime(date_str.split("T")[0], "%Y-%m-%d")
            days_old = (datetime.now() - date).days
            if days_old < 30:
                score += 20
            elif days_old < 90:
                score += 15
            elif days_old < 180:
                score += 10
            elif days_old < 365:
                score += 5
        except:
            score += 5

    # Popularity weight
    downloads = dataset.get("downloads", dataset.get("downloadCount", 0))
    if downloads > 1000:
        score += 10
    elif downloads > 500:
        score += 7
    elif downloads > 100:
        score += 5

    stars = dataset.get("stars", dataset.get("stargazers_count", 0))
    if stars > 100:
        score += 10
    elif stars > 50:
        score += 7
    elif stars > 10:
        score += 5

    # Task specificity weight
    task = str(dataset.get("task", "")).lower()
    if task in ["asr", "ocr", "ner", "classification", "translation"]:
        score += 10
    elif task in ["text corpus", "corpus", "general"]:
        score += 5

    # Description quality
    description = dataset.get("description", "")
    if description and len(description) > 100:
        score += 5

    return min(score, 100.0)

# Example
dataset = {
    "name": "IRIIS-RESEARCH Nepali Text Corpus",
    "platform": "huggingface",
    "size": "10.1 GB",
    "task": "Text Corpus",
    "license": "MIT",
    "last_modified": "2024-11-15",
    "downloads": 5000,
    "description": "Largest Nepali corpus from 99 news websites..."
}

quality_score = score_dataset(dataset)
print(f"Quality Score: {quality_score:.1f}/100")
```

---
---
### Learning Resources for Dataset Discovery

---

#### Tutorials and Guides

1. **Hugging Face Datasets Guide**
   - [https://huggingface.co/docs/datasets](https://huggingface.co/docs/datasets)
   - [Finding Datasets Tutorial](https://huggingface.co/docs/datasets/finding_datasets)

2. **Kaggle Datasets Guide**
   - [https://www.kaggle.com/docs/datasets](https://www.kaggle.com/docs/datasets)
   - [Dataset Discovery](https://www.kaggle.com/learn/dataset-discovery)

3. **GitHub Advanced Search**
   - [https://docs.github.com/en/search-github](https://docs.github.com/en/search-github)
   - [Searching on GitHub](https://docs.github.com/en/repositories/working-with-files/using-files/finding-files-on-github)

4. **Roboflow Documentation**
   - [https://docs.roboflow.com/](https://docs.roboflow.com/)
   - [Finding Datasets](https://docs.roboflow.com/datasets)

5. **Zenodo Help**
   - [https://help.zenodo.org/](https://help.zenodo.org/)
   - [Search Syntax](https://help.zenodo.org/#search-syntax)

#### Video Tutorials

| Topic | Video | Channel |
|-------|-------|---------|
| Finding Datasets on Hugging Face | [How to Find Datasets on Hugging Face](https://www.youtube.com/results?search_query=How+to+Find+Datasets+on+Hugging+Face) | Hugging Face |
| Kaggle Dataset Discovery | [Finding Datasets on Kaggle](https://www.youtube.com/results?search_query=Finding+Datasets+on+Kaggle) | Kaggle |
| GitHub Advanced Search | [GitHub Search Tips](https://www.youtube.com/results?search_query=GitHub+Search+Tips) | GitHub |
| Roboflow Dataset Search | [Finding Datasets on Roboflow](https://www.youtube.com/results?search_query=Finding+Datasets+on+Roboflow) | Roboflow |
| Zenodo Dataset Search | [Using Zenodo for Research Data](https://www.youtube.com/results?search_query=Using+Zenodo+for+Research+Data) | Zenodo |

#### Books and Courses

1. **"Natural Language Processing with Python"**
   - Covers dataset discovery for NLP

2. **"Hands-On Machine Learning with Scikit-Learn, Keras, and TensorFlow"**
   - Dataset finding strategies

3. **Fast.ai Practical Deep Learning**
   - [Dataset Downloading](https://course.fast.ai/)

4. **Coursera: Data Science Specialization**
   - [Getting and Cleaning Data](https://www.coursera.org/learn/data-cleaning)

---
---
### Pro Tips for Dataset Discovery

---

#### Best Practices

1. Use multiple platforms: No single platform has all datasets
2. Check dates: Prioritize recent datasets (2024-2026)
3. Verify licenses: Ensure datasets have clear usage rights
4. Check quality: Look for datasets with:
   - Clear documentation
   - Proper labeling/annotation
   - Balanced class distribution
   - Large enough size for your task
5. Join communities: Follow Nepali NLP/Speech/CV communities
6. Set up alerts: Use Google Alerts, GitHub notifications, etc.
7. Contribute back: Share datasets you create with the community
8. Check citations: Look for datasets cited in recent papers
9. Verify sources: Ensure datasets come from reputable sources
10. Test before use: Always validate dataset quality before training

#### Common Pitfalls to Avoid

1. Ignoring license restrictions: Some datasets have strict usage limits
2. Not checking data quality: Datasets may have errors, biases, or poor annotations
3. Overlooking small datasets: Small but high-quality datasets can be valuable
4. Forgetting to cite: Always cite datasets in your research
5. Using outdated datasets: Prioritize recent, well-maintained datasets
6. Not checking for duplicates: Same dataset may appear on multiple platforms
7. Ignoring metadata: Pay attention to dataset descriptions, statistics, and provenance
8. Downloading everything: Be selective to save time and storage
9. Not verifying authenticity: Ensure datasets are from legitimate sources
10. Forgetting preprocessing: Many datasets need cleaning before use

#### Hidden Gems

1. University repositories: Check Nepali university websites (TU, KU, PU, etc.)
2. Government open data: [https://data.gov.np/](https://data.gov.np/)
3. NGO/INGO data: UN, World Bank, ADB, etc. often have Nepal data
4. Local news websites: Some publish datasets (Kantipur, Annapurna Post, etc.)
5. Social media groups: Facebook groups for Nepali AI/ML researchers
6. Academic theses: Nepali university theses often include datasets
7. Conference proceedings: Check local tech conference presentations
8. Hackathon outputs: Datasets created during Nepali hackathons
9. Student projects: GitHub repos from Nepali university students
10. Personal blogs: Nepali researchers often share datasets on their blogs

---
---
### Community and Support

---

#### Discussion Forums

| Platform | Link | Purpose |
|----------|------|---------|
| Hugging Face Discussions | [https://discuss.huggingface.co/](https://discuss.huggingface.co/) | General dataset questions |
| Kaggle Forums | [https://www.kaggle.com/discussion](https://www.kaggle.com/discussion) | Dataset-specific discussions |
| GitHub Discussions | Platform-specific | Repository discussions |
| Reddit r/datasets | [https://www.reddit.com/r/datasets/](https://www.reddit.com/r/datasets/) | Dataset requests |
| Reddit r/MachineLearning | [https://www.reddit.com/r/MachineLearning/](https://www.reddit.com/r/MachineLearning/) | ML dataset discussions |
| Stack Overflow | [https://stackoverflow.com/](https://stackoverflow.com/) | Technical questions |

#### Nepali AI/ML Communities

| Community | Platform | Focus | Link |
|-----------|----------|-------|------|
| Nepali NLP | Discord/Slack | NLP research | Check GitHub orgs |
| AI4Nepal | Facebook/LinkedIn | AI in Nepal | [AI4Nepal](https://www.facebook.com/ai4nepal/) |
| Nepal AI Society | LinkedIn | AI community | [NAIS](https://www.linkedin.com/company/nepal-ai-society) |
| Python Nepal | Facebook | Python and Data Science | [Python Nepal](https://www.facebook.com/pythonnepal/) |
| Data Science Nepal | Facebook | Data Science | [DS Nepal](https://www.facebook.com/groups/datasciencenepal/) |
| Kathmandu AI | Meetup | AI Meetups | [Kathmandu AI](https://www.meetup.com/Kathmandu-AI/) |
| F1Soft Group AI | LinkedIn | Enterprise AI | [F1Soft AI](https://www.linkedin.com/company/f1soft-group/) |

#### Newsletters and Blogs

| Resource | Type | Link |
|----------|------|------|
| Hugging Face Newsletter | Weekly | [Subscribe](https://huggingface.co/newsletter) |
| Kaggle Newsletter | Weekly | [Subscribe](https://www.kaggle.com/newsletter) |
| Towards Data Science | Blog | [Medium](https://towardsdatascience.com/) |
| Analytics Vidhya | Blog | [AV](https://www.analyticsvidhya.com/) |
| Nepali Tech Blogs | Various | Search for "Nepali AI blog" |
| ResearchGate | Academic | [ResearchGate](https://www.researchgate.net/) |
| Academia.edu | Academic | [Academia](https://www.academia.edu/) |

---
---
### Staying Updated

---

#### Notification Methods

1. **Google Alerts**
   - Create alerts for: "Nepali dataset", "Nepali NLP", "Nepali corpus", "Nepali ASR"
   - [https://www.google.com/alerts](https://www.google.com/alerts)

2. **GitHub Notifications**
   - Watch repositories: IOST-ASCOL/nepali-datasets, pemagrg1/Nepali-Datasets
   - Follow topics: nepali-nlp, nepali-dataset

3. **Hugging Face Notifications**
   - Watch datasets: Click "Watch" on Nepali datasets
   - Follow organizations: IRIISNEPAL, etc.

4. **Kaggle Notifications**
   - Follow dataset creators
   - Enable email notifications for new datasets

5. **RSS Feeds**
   - Hugging Face: [https://huggingface.co/datasets?language=ne&format=rss](https://huggingface.co/datasets?language=ne&format=rss)
   - GitHub: Use GitHub RSS for searches

6. **Slack/Discord Bots**
   - Set up bots to monitor new datasets
   - Use webhooks for notifications

7. **IFTTT/Zapier**
   - Create automation: "If new Nepali dataset on HF, then notify me"
   - [IFTTT](https://ifttt.com/) or [Zapier](https://zapier.com/)

#### Dataset Tracking Spreadsheet

Create a spreadsheet to track Nepali datasets:

| Column | Description | Example |
|--------|-------------|---------|
| Name | Dataset name | IRIIS-RESEARCH Nepali Text Corpus |
| Platform | Where it's hosted | Hugging Face |
| URL | Direct link | [HF Link](https://huggingface.co/...) |
| Size | Dataset size | 10.1 GB |
| Task | Primary task | Text Corpus |
| License | Usage license | MIT |
| Last Updated | Last modification date | 2024-11-15 |
| Downloads | Number of downloads | 5,000+ |
| Stars | GitHub stars | 45 |
| Quality Score | Your quality rating | 95/100 |
| Notes | Additional comments | Largest Nepali corpus |
| Status | Your status | Downloaded/To Review/Rejected |
| Date Added | When you found it | 2026-08-08 |

**Template**: Create your own spreadsheet with these columns

---
---
### Quick Start Guide

---

#### For Beginners: Finding Your First Nepali Dataset

1. **Start with Hugging Face**:
   - Go to [https://huggingface.co/datasets?language=ne](https://huggingface.co/datasets?language=ne)
   - Try the **IRIIS-RESEARCH Nepali Text Corpus** for general NLP
   - Try **amitpant7/nepali-speech-to-text** for ASR

2. **Explore Kaggle**:
   - Go to [https://www.kaggle.com/datasets?tags=16979-Nepali](https://www.kaggle.com/datasets?tags=16979-Nepali)
   - Try **Nepali News Dataset** for classification
   - Try **Nepali OCR Dataset** for computer vision

3. **Check GitHub**:
   - Go to [https://github.com/topics/nepali-nlp](https://github.com/topics/nepali-nlp)
   - Try **pemagrg1/Nepali-Datasets** for a curated list
   - Try **IOST-ASCOL/nepali-datasets** for comprehensive collection

4. **Join Communities**:
   - Join Nepali NLP Discord/Slack groups
   - Follow #nepali-datasets on Twitter
   - Subscribe to AI4Nepal newsletters

5. **Start Small**:
   - Begin with a small dataset (1-10MB)
   - Try a simple task (text classification, sentiment analysis)
   - Gradually move to larger, more complex datasets

#### For Researchers: Advanced Discovery

1. Set up automated monitoring using the Python scripts above
2. Create a dataset tracking system (spreadsheet or database)
3. Join academic networks (ResearchGate, Academia.edu)
4. Follow key researchers on GitHub and social media
5. Attend conferences and network with Nepali researchers
6. Collaborate on dataset creation with local institutions
7. Publish your datasets to contribute back to the community

#### For Developers: API Integration

1. Use Hugging Face API for programmatic dataset access
2. Integrate Kaggle API for dataset downloads
3. Use GitHub API to monitor repository updates
4. Create dataset discovery tools for your team
5. Build dataset recommendation systems using embeddings
6. Automate dataset validation and quality checks
7. Create dataset versioning systems for reproducibility

---
---
### Final Checklist for Dataset Discovery

---

#### Weekly Routine

- [ ] Search Hugging Face for new Nepali datasets (language:ne)
- [ ] Check GitHub for new repos (nepali dataset sort:updated)
- [ ] Browse Kaggle for new datasets (nepali)
- [ ] Search Zenodo for academic datasets (nepali dataset type:dataset)
- [ ] Check Roboflow for CV datasets (nepali)
- [ ] Review Reddit/r/datasets for new posts
- [ ] Check Open Data Nepal for government datasets
- [ ] Follow Nepali AI communities on social media
- [ ] Review Google Alerts notifications
- [ ] Update your dataset tracking spreadsheet

#### Monthly Routine

- [ ] Run automated dataset monitor script
- [ ] Check academic repositories (IEEE, Figshare, Dryad)
- [ ] Review recent arXiv papers for new datasets
- [ ] Search conference proceedings (ACL, EMNLP, NeurIPS, etc.)
- [ ] Check NGO/INGO websites for new data releases
- [ ] Update dataset quality scores
- [ ] Share new findings with community
- [ ] Contribute to dataset aggregators
- [ ] Clean up old/unused datasets
- [ ] Backup your dataset collection

#### Quarterly Routine

- [ ] Comprehensive search across all platforms
- [ ] Review and update dataset documentation
- [ ] Verify licenses for all tracked datasets
- [ ] Check for dataset updates/versions
- [ ] Validate data quality of key datasets
- [ ] Update search queries based on new trends
- [ ] Contribute new datasets to community collections
- [ ] Write blog post about new findings
- [ ] Present at local meetups
- [ ] Create tutorial using new datasets

---
---
### Nepali Datasets to Start With

| Rank | Dataset | Platform | Task | Size | Why It's Great | Link |
|------|---------|----------|------|------|----------------|------|
| 1 | IRIIS-RESEARCH Nepali Text Corpus | Hugging Face | Text Corpus | 10.1 GB | Largest Nepali corpus, 6.4M articles | [HF](https://huggingface.co/datasets/IRIIS-RESEARCH/Nepali-Text-Corpus) |
| 2 | Amit Pant Nepali Speech-to-Text | Hugging Face | ASR | 949 MB | Combined OpenSLR + Common Voice, cleaned | [HF](https://huggingface.co/datasets/amitpant7/nepali-speech-to-text) |
| 3 | Nepali Handwritten Dataset Major Collection | GitHub | OCR | 2.5 GB | Comprehensive handwritten text collection | [GitHub](https://github.com/dahalsweekar/Nepali-Handwritten-Dataset-Major-Collection) |
| 4 | Birat-Poudel Nepali Sign Language Dataset | Hugging Face | Sign Language | 36,000 images | Character-level sign language recognition | [HF](https://huggingface.co/datasets/Birat-Poudel/Nepali-Sign-Language-Character-Dataset) |
| 5 | Spandyie Nepali News Dataset | Hugging Face | News Classification | Large | Cleaned category labels from Baahrakhari | [HF](https://huggingface.co/datasets/spandyie/nepali-news-dataset) |
| 6 | Ministry of Finance Nepal Corpus | Hugging Face | Government Text | 2015-2024 | Official government documents, cleaned | [HF](https://huggingface.co/datasets/lilgoose777/mof-nepal-nepali) |
| 7 | Nepali Fake News Dataset v1 | Hugging Face | Fake News Detection | 8,838 samples | Synthetic but well-labeled | [HF](https://huggingface.co/datasets/chhatramani/nepali-fake-news-dataset-v1) |
| 8 | Nepali Vehicle Dataset | Kaggle | Object Detection | 4,797 images | Real-world vehicle images from Nepal | [Kaggle](https://www.kaggle.com/datasets/sdevkota007/vehicles-nepal-dataset) |
| 9 | Nepal Landslide Dataset | Zenodo | Semantic Segmentation | 230 images + masks | Geospatial dataset for disaster response | [Zenodo: 3675410](https://zenodo.org/records/3675410) |
| 10 | Nepali Transliteral Dataset | GitHub | Transliteration | - | Unicode to Latin script mapping | [GitHub](https://github.com/SushilShrestha/NepaliTransliteralDataset) |

---

---

## Dataset Search Guide

### Platform-Specific Search Instructions

---

#### **How to Search Nepali Datasets on Hugging Face**

**Method 1: Using the Web Interface**

1. **Direct Language Filter:**
   - Go to [https://huggingface.co/datasets](https://huggingface.co/datasets)
   - Click on "Language" filter in the left sidebar
   - Select "Nepali (ne)" or type `ne` in the search bar
   - [Direct Link: All Nepali Datasets](https://huggingface.co/datasets?language=ne)

2. **Advanced Search Queries:**
   - Use the search bar at the top
   - Combine terms with AND/OR:
     - `nepali AND asr` - Find ASR datasets
     - `nepali OR ne` - Broader search
     - `language:ne AND task:text-classification` - Classification datasets
     - `nepali AND (ocr OR vision OR image)` - Computer vision datasets
     - `nepali AND (ner OR sentiment OR classification)` - NLP datasets
     - `nepali AND translation` - Translation datasets
     - `nepali updated:>2024-01-01` - Recently updated datasets

3. **Sorting and Filtering:**
   - Sort by: "Most recent", "Most downloads", "Most likes"
   - Filter by: Task type (automatic-speech-recognition, text-classification, etc.)
   - Filter by: License (MIT, Apache, Creative Commons, etc.)
   - Filter by: Size (Small <1GB, Medium 1-10GB, Large >10GB)

4. **Browsing by Task:**
   - Go to [https://huggingface.co/tasks](https://huggingface.co/tasks)
   - Select your task (e.g., Automatic Speech Recognition, Text Classification)
   - Filter by language: Nepali

**Method 2: Using Hugging Face API**

```python
from huggingface_hub import HfApi, list_datasets

# Initialize API
api = HfApi()

# List all Nepali datasets
nepali_datasets = api.list_datasets(filter="language:ne")
for ds in nepali_datasets:
    print(f"Name: {ds.id}")
    print(f"Description: {ds.description}")
    print(f"Downloads: {ds.downloads}")
    print(f"Likes: {ds.likes}")
    print(f"Last Modified: {ds.lastModified}")
    print(f"Link: https://huggingface.co/datasets/{ds.id}\n")

# Search with specific query
datasets = api.list_datasets(filter="nepali asr")
for ds in datasets:
    print(ds.id)

# Get dataset details
from datasets import load_dataset_builder
dataset_builder = load_dataset_builder("dataset-name")
print(dataset_builder.info)
```

**Method 3: Using Hugging Face CLI**

```bash
# Install CLI
pip install huggingface_hub

# Authenticate (optional for public datasets)
huggingface-cli login

# List Nepali datasets
huggingface-cli list datasets --filter nepali

# Search with query
huggingface-cli list datasets --filter "nepali asr"

# Download a dataset
huggingface-cli download ranjitraut/nepal-constitution-dataset
```

**Method 4: Browser Bookmarklets**

Create these bookmarklets for quick access:

1. **All Nepali Datasets:**
   ```javascript
   javascript:window.location.href='https://huggingface.co/datasets?language=ne'
   ```

2. **Nepali ASR Datasets:**
   ```javascript
   javascript:window.location.href='https://huggingface.co/datasets?q=nepali+automatic-speech-recognition&sort=modified'
   ```

3. **Nepali NLP Datasets:**
   ```javascript
   javascript:window.location.href='https://huggingface.co/datasets?q=nepali+(ner+OR+sentiment+OR+classification)&sort=downloads'
   ```

4. **Nepali OCR Datasets:**
   ```javascript
   javascript:window.location.href='https://huggingface.co/datasets?q=nepali+ocr'
   ```

5. **Recently Updated Nepali Datasets:**
   ```javascript
   javascript:window.location.href='https://huggingface.co/datasets?q=nepali+updated:>2024-01-01&sort=modified'
   ```

**Method 5: Using Dataset Cards**

Each dataset on Hugging Face has a dataset card with:
- Description
- Dataset structure
- Usage examples
- Citation information
- License

Example: [IRIIS-RESEARCH Nepali Text Corpus](https://huggingface.co/datasets/IRIIS-RESEARCH/Nepali-Text-Corpus) shows:
- 10.1 GB size
- 6.4M articles
- MIT license
- Usage code snippets

---

#### **How to Search Nepali Datasets on GitHub**

**Method 1: Using GitHub Web Search**

1. **Basic Search:**
   - Go to [https://github.com/search](https://github.com/search)
   - Type: `nepali dataset` or `nepali nlp`
   - [Direct Link: Nepali Dataset Search](https://github.com/search?q=nepali+dataset)

2. **Advanced Search:**
   - Use [GitHub Advanced Search](https://github.com/search/advanced)
   - Fill in:
     - Keywords: `nepali dataset`
     - Language: `Python`, `Jupyter Notebook`, etc.
     - Sort: `Recently updated` or `Most stars`

3. **Search Queries:**

| Query | Purpose | Example Results |
|-------|---------|-----------------|
| `nepali dataset` | All Nepali dataset repositories | Text corpora, OCR datasets, NLP tools |
| `nepali nlp` | NLP-related repositories | Classification, NER, sentiment analysis |
| `nepali corpus` | Text corpus repositories | News datasets, Wikipedia dumps |
| `nepali ocr` | OCR/handwriting recognition | Character datasets, handwritten text |
| `nepali speech` | Speech/audio datasets | ASR datasets, TTS data |
| `nepali computer vision` | CV datasets | Object detection, classification |
| `nepali handwritten` | Handwriting datasets | Character recognition datasets |
| `nepali sign language` | Sign language datasets | Gesture recognition datasets |
| `language:nepali` | Repos with Nepali as primary language | Code written in Nepali |
| `topic:nepali-nlp` | NLP topic repositories | Curated NLP resources |
| `topic:nepali-dataset` | Dataset topic repositories | Dataset collections |
| `topic:nepali-ocr` | OCR topic repositories | Character recognition projects |
| `nepali dataset stars:>10` | Popular repositories | Well-maintained datasets |
| `nepali dataset pushed:>2024-01-01` | Recently created | New datasets from 2024-2026 |
| `nepali dataset in:readme` | Datasets mentioned in README | Well-documented repos |

4. **Using GitHub Topics:**
   - Browse curated topics:
     - [nepali-nlp](https://github.com/topics/nepali-nlp)
     - [nepali-dataset](https://github.com/topics/nepali-dataset)
     - [nepali-ocr](https://github.com/topics/nepali-ocr)
     - [nepali-character-recognition](https://github.com/topics/nepali-character-recognition)
     - [devanagari-character-dataset](https://github.com/topics/devanagari-character-dataset)

**Method 2: Using GitHub API**

```python
import requests
import json

# Search repositories
url = "https://api.github.com/search/repositories"
headers = {"Accept": "application/vnd.github.v3+json"}

# Basic search
params = {
    "q": "nepali dataset",
    "sort": "updated",
    "order": "desc",
    "per_page": 50
}
response = requests.get(url, params=params, headers=headers)
repos = response.json()["items"]

for repo in repos:
    print(f"Repository: {repo['full_name']}")
    print(f"Name: {repo['name']}")
    print(f"Description: {repo['description']}")
    print(f"Stars: {repo['stargazers_count']}")
    print(f"Forks: {repo['forks_count']}")
    print(f"Updated: {repo['updated_at']}")
    print(f"URL: {repo['html_url']}")
    print(f"Language: {repo['language']}")
    print("-" * 80)

# Search with language filter
params = {
    "q": "nepali dataset language:python",
    "sort": "stars",
    "per_page": 30
}
response = requests.get(url, params=params, headers=headers)
python_repos = response.json()["items"]

# Search code files
code_url = "https://api.github.com/search/code"
params = {
    "q": "nepali dataset extension:json OR extension:csv OR extension:txt",
    "per_page": 30
}
response = requests.get(code_url, params=params, headers=headers)
code_results = response.json()["items"]

for result in code_results:
    print(f"File: {result['name']}")
    print(f"Repo: {result['repository']['full_name']}")
    print(f"URL: {result['html_url']}")
    print("-" * 80)
```

**Method 3: Using GitHub CLI (gh)**

```bash
# Install GitHub CLI
# macOS: brew install gh
# Linux: sudo apt install gh
# Windows: winget install --id GitHub.cli

# Authenticate
gh auth login

# Search for repositories
gh search repos "nepali dataset" --sort updated --order desc
gh search repos "nepali nlp" --language python
gh search repos "topic:nepali-dataset"

# View repository details
gh repo view OWNER/REPO

# Clone a repository
gh repo clone ranjitraut/Nepali-Datasets-Collection

# List files in a repository
gh repo view ranjitraut/Nepali-Datasets-Collection --json files

# Search code in repositories
gh search code "nepali dataset" --extension json
gh search code "nepali ocr" --language python
```

**Method 4: Using GitHub Advanced Search Operators**

| Operator | Example | Description |
|----------|---------|-------------|
| `in:name` | `nepali in:name` | Repos with "nepali" in name |
| `in:description` | `dataset in:description nepali` | Repos with "dataset" and "nepali" in description |
| `in:readme` | `nepali in:readme` | Repos with "nepali" in README |
| `language:` | `language:python nepali dataset` | Python repos about Nepali datasets |
| `stars:` | `nepali dataset stars:>50` | Repos with >50 stars |
| `forks:` | `nepali dataset forks:>10` | Repos with >10 forks |
| `pushed:` | `nepali dataset pushed:>2024-01-01` | Repos updated after Jan 1, 2024 |
| `created:` | `nepali dataset created:>2024-01-01` | Repos created after Jan 1, 2024 |
| `user:` | `user:theranjitraut nepali` | Repos by specific user |
| `org:` | `org:IOST-ASCOL nepali` | Repos by specific organization |
| `topic:` | `topic:nepali-nlp topic:dataset` | Repos with specific topics |
| `label:` | `label:nepali label:dataset` | Issues/PRs with specific labels |

**Method 5: GitHub Code Search**

To find actual dataset files (JSON, CSV, etc.):

1. Go to [https://github.com/search](https://github.com/search)
2. Click on "Code" tab
3. Search: `nepali dataset extension:json`
4. Or: `nepali corpus extension:csv`
5. Or: `language:nepali extension:txt`

Example searches:
- [nepali dataset json](https://github.com/search?q=nepali+dataset+extension%3Ajson)
- [nepali corpus csv](https://github.com/search?q=nepali+corpus+extension%3Acsv)
- [nepali nlp txt](https://github.com/search?q=nepali+nlp+extension%3Atxt)

**Method 6: Following Nepali Dataset Repositories**

Watch these key repositories for updates:

1. [pemagrg1/Nepali-Datasets](https://github.com/pemagrg1/Nepali-Datasets) - Comprehensive list
2. [IOST-ASCOL/nepali-datasets](https://github.com/IOST-ASCOL/nepali-datasets) - Curated collection
3. [ghimiresunil/Curated-List-of-Nepali-NLP-Resources](https://github.com/ghimiresunil/Curated-List-of-Nepali-NLP-Resources) - Resource aggregator
4. [rameshhpathak/nepali-nlp-resources](https://github.com/rameshhpathak/nepali-nlp-resources) - Tools and datasets
5. [amitness/ml-datasets](https://github.com/amitness/ml-datasets) - ML datasets for Nepal

To watch a repository:
- Go to the repo page
- Click "Watch" button (top right)
- Select "Watching" to get notifications

**Method 7: GitHub Notifications**

Set up notifications for:
- New repositories matching "nepali dataset"
- Updates to watched repositories
- New issues/PRs in relevant repos

Go to [https://github.com/watching](https://github.com/watching) to manage your watched repositories.

---

### **Quick Reference: Best Search Commands**

| Platform | Command/URL | Purpose |
|----------|-------------|---------|
| **Hugging Face** | `https://huggingface.co/datasets?language=ne` | All Nepali datasets |
| **Hugging Face** | `https://huggingface.co/datasets?q=nepali+asr` | ASR datasets |
| **Hugging Face** | `https://huggingface.co/datasets?q=nepali+ocr` | OCR datasets |
| **Hugging Face** | `https://huggingface.co/datasets?q=nepali+ner` | NER datasets |
| **GitHub** | `https://github.com/search?q=nepali+dataset` | All Nepali dataset repos |
| **GitHub** | `https://github.com/search?q=nepali+nlp` | NLP repos |
| **GitHub** | `https://github.com/topics/nepali-nlp` | NLP topic repos |
| **GitHub** | `https://github.com/topics/nepali-dataset` | Dataset topic repos |
| **Kaggle** | `https://www.kaggle.com/datasets?tags=16979-Nepali` | All Nepali datasets |
| **Kaggle** | `https://www.kaggle.com/datasets?search=nepali+ocr` | OCR datasets |
| **Roboflow** | `https://universe.roboflow.com/search?query=nepali` | All Nepali CV datasets |

---

### **Search Cheat Sheet**

**For NLP Tasks:**
- Hugging Face: `language:ne AND (ner OR sentiment OR classification OR qa OR summarization)`
- GitHub: `nepali AND (nlp OR "natural language" OR corpus OR dataset)`
- Kaggle: `nepali AND (nlp OR text OR classification OR sentiment)`

**For Speech/Audio:**
- Hugging Face: `nepali AND (asr OR "speech-to-text" OR tts OR "text-to-speech")`
- GitHub: `nepali AND (speech OR audio OR asr OR tts)`
- OpenSLR: Search for "Nepali" or "ne"

**For Computer Vision:**
- Hugging Face: `nepali AND (ocr OR vision OR image OR object-detection OR classification)`
- GitHub: `nepali AND (computer-vision OR cv OR ocr OR "object detection")`
- Roboflow: `nepali OR devanagari`
- Kaggle: `nepali AND (image OR vision OR ocr OR detection)`

**For OCR/Handwriting:**
- Hugging Face: `nepali AND (ocr OR handwritten OR "handwriting recognition")`
- GitHub: `nepali AND (ocr OR handwritten OR character OR recognition)`
- Kaggle: `nepali AND (ocr OR handwritten OR character)`

**For Translation:**
- Hugging Face: `nepali AND (translation OR parallel OR "machine translation")`
- GitHub: `nepali AND (translation OR parallel OR corpus)`
- Kaggle: `nepali AND (translation OR parallel)`

**For Legal/Government:**
- Hugging Face: `nepali AND (legal OR constitution OR act OR law OR government)`
- GitHub: `nepali AND (legal OR constitution OR government OR act)`
- Open Data Nepal: Search for specific government datasets

---

*Last Updated: August 8, 2026*
*Maintained by: [theranjitraut](https://github.com/theranjitraut/)*
*Contributions welcome! Submit PR to [Nepali-Datasets-Collection](https://github.com/theranjitraut/Nepali-Datasets-Collection/)*
