## LLM-based translation evaluation: Georgian, Bulgarian, Russian

#### Project Overview
This repository contains datasets, notebooks, and analysis results for evaluating machine and large language model translations of selected texts into English. The materials include literary and news texts, human expert translations, and translations produced by GPT, Gemini, and Google Translate. 

#### Repository structure

```text
translation-Europeanlanguages/
├── Data/                                   # Source texts and translation data
│   ├── Bulgarian/
│   │   ├── BaiGanyo/                       # Literary work
│   │   └── BulgarianNews/                  # News texts
│   ├── Georgian/
│   │   ├── GeorgianNews/                   # News texts
│   │   └── Vazha_ThreePoems/               # Literary work
│   ├── Russian/
│   │   └── Stalker/
│   ├── combined_translations_bul/
│   ├── combined_translations_ge/
│   ├── combined_en.csv
│   ├── combined_gem.csv
│   ├── combined_ggl.csv
│   └── combined_gpt.csv
├── Fine-tuning/                            # Fine-tuning materials
├── original_text_and_expert_translations/  # Original texts and expert translations
├── results/                                # Analysis outputs
├── ekman_mapping.json                      # Emotion-label mapping
├── goemotions_sentiment_analysis.ipynb      # GoEmotions sentiment analysis
├── semantic_analysis.ipynb                 # Semantic analysis
├── translations.ipynb                      # Translation workflow and analysis
├── uncertainty_analysis.ipynb               # Translation uncertainty analysis
└── README.md
```

- #### Georgian, Bulgarian and Russian Texts ...

- #### Evaluated Translation Systems
   - Human Experts _(reference English translations)_
   - GPT _(current model="gpt-5.4-mini")_
   - Gemini _(current model="gemini-3-flash-preview")_
   - Google Translate _(2026)_
  

- #### Dataset directory layout

The language and text-type folders organise the original texts. Translation data are also provided in language-specific combined folders and in combined CSV files.

```text
Data/
├── Bulgarian/
│   ├── BaiGanyo/                           # Literary work
│           ├── en/      					            # English translations by human experts
│           ├── gem/      					            # Gemini translations
│           ├── ggl/      					            # Google Translate translations
│           ├── gpt/      					            # GPT translations
│           ├── orig/      					             # Original text   
│   └── BulgarianNews/                      # News texts
│           ├── en/
│           ├── gem/
│           ├── ggl/               
│           ├── gpt/               
│           ├── orig/
├── Georgian/
│   ├── GeorgianNews/                       # News texts
│   └── Vazha_ThreePoems/                   # Literary work
├── Russian/
│   └── Stalker/
├── combined_translations_bul/
├── combined_translations_ge/
├── combined_en.csv                         # English translation data
├── combined_gem.csv                        # Gemini translation data
├── combined_ggl.csv                        # Google Translate data
└── combined_gpt.csv                        # GPT translation data
```
