---
permalink: /
title: ""
excerpt: "About me"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---


# About
* [Xu Tan](https://www.microsoft.com/en-us/research/people/xuta/) is a Senior Researcher in Machine Learning Group, Microsoft Research Asia ([MSRA](https://www.microsoft.com/en-us/research/lab/microsoft-research-asia/)).
* His research interests cover machine learning, deep learning, and their applications on natural language/speech/music processing, including neural machine translation, pre-training, text to speech, automatic speech recognition, music understanding and generation, talking face generation, etc. 
* He has published [80+ papers](https://scholar.google.com/citations?user=tob-U1oAAAAJ), with citation over 3800+, and designed several popular language/speech/music models and systems, such as [MASS](https://www.microsoft.com/en-us/research/blog/introducing-mass-a-pre-training-method-that-outperforms-bert-and-gpt-in-sequence-to-sequence-language-generation-tasks/), [FastSpeech](https://www.microsoft.com/en-us/research/blog/fastspeech-new-text-to-speech-model-improves-on-speed-accuracy-and-controllability/), and [Muzic](https://github.com/microsoft/muzic).
* He has many technologies (e.g., neural machine translation; pre-training models: [MASS](https://arxiv.org/pdf/1905.02450.pdf); text to speech: [FastSpeech 1](https://www.microsoft.com/en-us/research/blog/fastspeech-new-text-to-speech-model-improves-on-speed-accuracy-and-controllability/)/[2](https://www.microsoft.com/en-us/research/lab/microsoft-research-asia/articles/fastspeech-2-fast-and-high-quality-end-to-end-text-to-speech/), [AdaSpeech](https://arxiv.org/pdf/2103.00993.pdf), [LRSpeech](https://arxiv.org/pdf/2008.03687.pdf); AI music composition: [SongMASS](https://arxiv.org/pdf/2012.05168.pdf), [TeleMelody](https://arxiv.org/pdf/2109.09617.pdf), [HiFiSinger](https://arxiv.org/pdf/2009.01776.pdf); ASR error correction: [FastCorrect 1](https://arxiv.org/pdf/2105.03842.pdf)/[2](https://arxiv.org/pdf/2109.14420.pdf); etc) deployed in Microsoft products (e.g., Bing Search/Ads, Microsoft Translator, Azure TTS, Azure ASR, Microsoft Xiaoice, etc).
* He has several opensource projects on Github, such as [MASS](https://github.com/microsoft/mass), MPNet([Huggingface](https://huggingface.co/transformers/model_doc/mpnet.html)), [Muzic](https://github.com/microsoft/muzic), [NeuralSpeech](https://github.com/microsoft/NeuralSpeech).
* He is an Action Editor of [Transactions on Machine Learning Research (TMLR)](https://www.jmlr.org/tmlr/), an Area Chair of AAAI 2021/2022 and NeurIPS 2021/2022, a member of IEEE, and a member of the standing committee on [Computing Art](https://www.ccf.org.cn/Chapters/CCF_Chapters/CCF_CA/) in China Computer Federation (CCF).


## Featured Projects
### 1. Neural Machine Translation
* Pubish 20+ papers on top conferences, multiple technologies transferred into Microsoft Translator to improve the product experiences.
* We [achieved human parity](https://blogs.microsoft.com/ai/chinese-to-english-translator-milestone/) on Chinese-English machine translation in 2018.
* We won [several champions](https://news.microsoft.com/apac/2019/05/22/microsoft-research-asia-msra-leads-in-2019-wmt-international-machine-translation-competition/) on WMT machine translation competition in 2019. 
* Our [MASS](https://arxiv.org/pdf/1905.02450.pdf) is the first pre-training model for sequence to sequence generation, and is one of the top cited papers in ICML 2019. MASS is deployed in [Microsoft Translator](https://www.bing.com/translator) to enable the translation of 10+ low-resource languages. [[blog]](https://www.microsoft.com/en-us/research/blog/introducing-mass-a-pre-training-method-that-outperforms-bert-and-gpt-in-sequence-to-sequence-language-generation-tasks/) [[code]](https://github.com/microsoft/MASS)

### 2. Text to Speech
* Publish 20+ papers on top conferences, multiple technologies (FastSpeech 1/2, LRSpeech, AdaSpeech 1/2/3, DelightfulTTS) deployed in Microsoft Azure TTS services.  
* Our [FastSpeech 1](https://www.microsoft.com/en-us/research/blog/fastspeech-new-text-to-speech-model-improves-on-speed-accuracy-and-controllability/)/[2](https://www.microsoft.com/en-us/research/lab/microsoft-research-asia/articles/fastspeech-2-fast-and-high-quality-end-to-end-text-to-speech/) are one of the most widely used technologies in TTS in both academia and industry, and are the backbones of many TTS and singing voice synthesis models. Support over 100+ languages in Azure TTS services. Integrated in some popular Github repos, such as ESPNet, Fairseq, NVIDIA Nemo, TensorFlowTTS, Baidu PaddlePaddle Parakeet, etc.
* [DelightfulTTS](https://arxiv.org/pdf/2110.12612.pdf) achieved the best quality in Blizzard Speech Synthesis Challenge 2021.
* [NaturaSpeech](https://arxiv.org/pdf/2205.04421.pdf) achieves human-level quality on text-to-speech synthesis on LJSpeech dataset for the first time. 
* The most comprehensive [TTS Survey](https://arxiv.org/pdf/2106.15561.pdf).
* [TTS Tutorials](https://github.com/tts-tutorial/) at ISCSLP 2021, IJCAI 2021, ICASSP 2022, INTERSPEECH 2022. 
* Speech project demo page: https://speechresearch.github.io/, code opensource page: https://github.com/microsoft/NeuralSpeech.

### 3. AI Music Composition
* Publish 10+ papers on top conferences, multiple techniques (SongMASS, TeleMelody, XiaoiceSing, and HiFiSinger) integrated in Microsoft Azure and Microsoft Xiaoice for AI music composition. 
* Systematic research on songwriting, accompaniment and arrangement, singing voice synthesis, music understanding, etc. Keynote speaker on [AI music composition](https://mp.weixin.qq.com/s/0ef2Xn7oSGYlip7LEzHXog) at GAITC 2021. Tutorial on [AI music composition](https://www.microsoft.com/en-us/research/uploads/prod/2021/10/Tutorial-on-AI-Music-Composition-@ACM-MM-2021.pdf) at ACM MM 2021.   
* Muzic: our research project on AI music, https://github.com/microsoft/muzic. 

### 4. Other Projects
#### &nbsp; 4.1. Pre-training
* Publish 10+ papers on top conferences (MASS, MPNet, Transcormer, NAS-BERT, MP-BERT, SongMASS, MusicBERT, etc)
* [MASS](https://arxiv.org/pdf/1905.02450.pdf) deployed in Bing Ads for Ads content generation, and deployed in Bing Translation for low-resource languages. 
* [MPNet](https://arxiv.org/pdf/2004.09297.pdf) adopted in [Huggingface](https://huggingface.co/transformers/model_doc/mpnet.html).
#### &nbsp; 4.2. Non-Autoregressive Sequence Generation
* Publish 10+ papers (FastSpeech 1/2, AdaSpeech 1/2/3, NaturalSpeech, HiFiSinger, FastCorrect 1/2/3, etc) on non-autoregressive sequence generation on text and speech generation tasks, such as neural machine translation, text error correction, automatic speech recognition, text to speech, singing voice synthesis, etc.
* Give a [tutorial on non-autoregressive sequence generation](https://nar-tutorial.github.io/acl2022/) at ACL 2022. 
#### &nbsp; 4.3. Efficient Machine Learning
* Design efficient models and algorithms to reduce the demands on big data, big model and big computation, with small latency/memory/computation/labeling cost. 
#### &nbsp; 4.4. Multilingual and Low-Resource Scenarios
#### &nbsp; 4.5. Model Structure and Learning Paradigm Design
#### &nbsp; 4.6. Neural Architecture Search 


<br/>
<br/>
For Chinese version, please visit [中文版](https://tan-xu.github.io/Chinese-version/). 


