# AI-generated text Detection in Russian. 
This repo contains code and data associated with the MA thesis on AI-generated text Detection in Russian. 

# Abstract
In recent years, concerns have grown over the use of generative AI for malicious purposes, such as creating fake online content or misuse in academic settings. This undermines public trust in online content and makes it difficult to ensure the authenticity of written material, especially as AI-generated text becomes increasingly indistinguishable from human-written text with each new generation of models. In this study, we investigate how reliable current baseline systems—both classical and neural—are against evasion strategies designed to conceal machine authorship. We focus specifically on Russian, an underrepresented language in AI-generated text (AIGT) detection research, and design three adversarial strategies: (1) human editing of AIGTs, (2) the use of AI humanizer tools, and (3) targeted manipulation of class-indicative unigrams. To achieve this, we introduce RuMix, a dataset consisting of 1,500 human-written and AI-generated texts across three distinct genres: news articles, social media posts, and poems. It includes two additional test sets that contain both manually crafted and automatically generated manipulations of news articles. We find that neither the classical nor neural models are significantly affected by these attacks; while classical models experience a slight drop in some performance metrics, neural models perform consistently across all test sets. These findings suggest that current detection models are largely robust to straightforward evasion strategies, but also highlight the need for future research to better understand how these systems work and where their vulnerabilities lie. Finally, we discuss the limitations of our evasion strategies and dataset, and open-source our contributions to support future research in AI-generated text detection for the Russian language.

# Contents
Elizaveta_Cheremisina_DTA_thesis.pdf: MA thesis paper

data folder:
RuMix dataset used in experiements: training split and three test splits. 
Original human data and AI-generated texts can be found in the following Googdle Drive folder: https://drive.google.com/drive/folders/1byzb_c85kd0nE1m-htFfuEG861KigOVZ?usp=sharing

code folder:
Code files used in this study.

plots folder: Contains all the plots/visualisations presented in the study.
# Contributions
Our main contributions include: (1) an extensive overview of AI humanizer tools for Russian; (2) the design and implementation of a suite of adversarial evasion strategies; and (3) the creation and open-source publication of RuMix.

# Citing

```bibtex
@mastersthesis{cheremisina2025rumix,
  author    = {Elizaveta Cheremisina and Walter Daelemans and Jens Lemmens},
  title     = {AI-generated Text Detection in Russian: Exploring Limitations of Evasion Strategies},
  school    = {University of Antwerp},
  year      = {2025},
  month     = {May},
  address   = {Antwerp, Belgium},
  type      = {Master's thesis}
}
