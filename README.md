## LLM-based translation evaluation: Georgian and Bulgarian to English

### Project Overview

- #### Georgian Texts ...

- #### Bulgarian Texts ...

- #### Evaluated Translation Systems
   - GPT _(specify the model)_
   - Gemini _(specify the model)_
   - Google Translate _(more details)_
   - Human Expert Translation 

### (Current) Structure of dataset directory 
```
translation-Europeanlanguages/
├── Data/
|   ├── Bulgarian/
│       ├── BaiGanyo/                       
│           ├── bul_original_baiganyo/      
│           ├── eng_expert_baiganyo/        
│           ├── gem_baiganyo/               
│           ├── ggl_baiganyo/               
│           ├── gpt_baiganyo/               
│       ├── BulgarianNews/
│           ├── bul_origianl_BTA_news/
│           ├── eng_expert_BTA_news/
│           ├── gem_BTA_news/               
│           ├── ggl_BTA_news/               
│           ├── gpt_BTA_news/
│   ├── Georgian/
│       ├── GeorgianNews/
│           ├── eng_expert_IPN_news/      
│           ├── ge_original_IPN_news/        
│           ├── gem_IPN_news/               
│           ├── ggl_IPN_news/               
│           ├── gpt_IPN_news/ 
│       ├── Vazha_ThreePoems/
│           ├── eng_expert_vazha/      
│           ├── ge_original_vazha/        
│           ├── gem_vazha/               
│           ├── ggl_vazha/               
│           ├── gpt_vazha/ 
|
├── ...
├── ...
└── README.md
```

### (version 2) Structure of dataset directory 
```
translation-Europeanlanguages/
├── Data/
|   ├── original/                      # Original texts
│       ├── bul/                            # Bulgarian
│          ├── BaiGanyo/                        # Literary work
│          └── BTA_News/                        # News acticles 
│       ├── ge/                             # Georgian
│          ├── Vazha_ThreePoems/                # Literary work
│          └── IPN_News/                        # News acticles 
|   ├── en/                             # English translations by human experts 
│       ├── BaiGanyo/
│       ├── BTA_News/
│       ├── Vazha/
│       └── IPN_News/
|   ├── gem/                             # Gemini translations
│       ├── BaiGanyo/
│       ├── BTA_News/
│       ├── Vazha/
│       └── IPN_News/
|   ├── ggl/                            # Google Translate translations
│       ├── BaiGanyo/
│       ├── BTA_News/
│       ├── Vazha/
│       └── IPN_News/
|   ├── gpt/                            # GPT translations
│       ├── BaiGanyo/
│       ├── BTA_News/
│       ├── Vazha/
│       └── IPN_News/
|
├── ...
├── ...
└── README.md
```
