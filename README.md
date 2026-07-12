## LLM-based translation evaluation: Georgian and Bulgarian to English

### Project Overview

- #### Georgian, Bulgarian and Russian Texts ...

- #### Evaluated Translation Systems
   - GPT _(current model="gpt-5.4-mini")_
   - Gemini _(current model="gemini-3-flash-preview")_
   - Google Translate _(2026)_
   - Human Expert Translation 

### Dataset directory layout 
```
translation-Europeanlanguages/
├── Data/
|   ├── Bulgarian/
│       ├── BaiGanyo/				# Literary work   
│           ├── en/      					   # English translations by human experts
│           ├── gem/        				   # Gemini translations
│           ├── ggl/               		   # Google Translate translations
│           ├── gpt/               		   # GPT translations
│           ├── orig/						   # Original text               
│       ├── BulgarianNews/			# News acticles
│           ├── en/
│           ├── gem/
│           ├── ggl/               
│           ├── gpt/               
│           ├── orig/
│   ├── Georgian/
│       ├── GeorgianNews/			# News acticles
│           ├── en/      
│           ├── gem/        
│           ├── ggl/               
│           ├── gpt/               
│           ├── orig/ 
│       ├── Vazha_ThreePoems/		# Literary work 
│           ├── en/      
│           ├── gem/        
│           ├── ggl/               
│           ├── gpt/               
│           ├── orig/

|
├── ...
├── ...
└── README.md
```

### (version 2) Dataset directory layout 
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
