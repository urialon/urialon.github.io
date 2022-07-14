---
permalink: /
title: 
excerpt: "About me"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
 
feature_row1:
  - image_path: c2v_demo.png
    alt: "https://www.code2vec.org"
    title: "code2vec (POPL'2019)"
    url: "https://www.code2vec.org"
    btn_label: "Demo"
    btn_class: "btn--primary"
    url2: "https://github.com/tech-srl/code2vec"
    btn_label2: "Code"
    btn_class: "btn--primary"
    tags: 
        - code2vec
        
feature_row2:
  - image_path: c2s_demo.png
    alt: "https://www.code2seq.org"
    title: "code2seq (ICLR'2019)"
    url: "https://www.code2seq.org"
    btn_label: "Demo"
    btn_class: "btn--primary"
    url2: "https://github.com/tech-srl/code2seq"
    btn_label2: "Code"
    btn_class: "btn--primary"
    tags: 
        - code2seq

feature_row3:
  - image_path: slm_demo.png
    alt: "https://www.AnyCodeGen.org"
    title: "AnyCodeGen (ICML'2020)"
    url: "https://www.AnyCodeGen.org"
    btn_label: "Demo"
    btn_class: "btn--primary"
    url2: "https://github.com/tech-srl/slm-code-generation"
    btn_label2: "Code"
    btn_class: "btn--primary"
    tags: 
        - AnyCodeGen
---

I am a post-doc at the Language Technologies Institute (LTI) of Carnegie Mellon University, working with [Prof. Graham Neubig](https://www.phontron.com/){:target="_blank"}, and a member of [NeuLab](https://www.cs.cmu.edu/~neulab/){:target="_blank"}.

My research interests are broad and include programming language processing (PLP), natural language processing (NLP) and deep learning in general.

I obtained a PhD in the department of Computer Science at the Technion, advised by [Prof. Eran Yahav](https://www.cs.technion.ac.il/~yahave/){:target="_blank"}.

Previously, I served 7 years as an officer onboard a missile ship in the Israeli Navy.
Later, I completed my BSc _summa cum laude_ at the Computer Science Department at the Technion, as an alumnus of The Rothschild-Technion Scholars Program for Excellence. 
Between 2014-2016, I worked at Microsoft R&D center in Haifa, developing data security services for the cloud. 
Between June-September of 2018, I interned at Google New-York, researching neural models for speech recognition.

In addition, I hold a B.A. in Humanities.

I am happily married to Lee and father of Gur 🙂

### News
**_July 2022_** - a new preprint: [`DocCoder`: Generating Code by Retrieving and Reading the Docs](#doccoder)

**_July 2022_** - I released a new HuggingFace 🤗 `transformers` implementation of [RetoMaton](#retomaton) and kNN-language models: [https://github.com/neulab/knn-transformers](https://github.com/neulab/knn-transformers){:target="_blank"}

**_June 2022_** - I was selected for the [ACM SIGPLAN Reynolds Doctoral Dissertation Award](https://www.sigplan.org/Awards/Dissertation/){:target="_blank"} (formerly "SIGPLAN Outstanding Doctoral Dissertation Award")!

**_May 2022_** - our [RetoMaton](#retomaton) paper was accepted to ICML'2022!

**_April 2022_** - our [PolyCoder](#polycoder) paper will appear in ICLR 2022's [DL4Code](https://dl4c.github.io/papers/){:target="_blank"} and PLDI 2022's [MAPS](https://pldi22.sigplan.org/home/maps-2022){:target="_blank"} workshops.

**_March 2022_** - a new preprint: [A Systematic Evaluation of Large Language Models of Code](#polycoder)

**_February 2022_** - a new preprint: [Neuro-Symbolic Language Modeling with Automaton-augmented Retrieval](#retomaton)

**_January 2022_** - our paper [How Attentive are Graph Attention Networks?](#attentive) was accepted to ICLR'2022! 

---
# Publications <a href="https://scholar.google.com/citations?user=QBn7vq8AAAAJ&hl=en&oi=ao" target="_blank"><i class="fas fa-fw fa-graduation-cap"></i></a><a name="publications"></a>

## Preprints
* **`DocCoder`: Generating Code by Retrieving and Reading the Docs** {:id="doccoder"}
    * Shuyan Zhou
, **Uri Alon**, Frank F. Xu, Zhengbao Jiang, Graham Neubig    
    * [[PDF]](https://arxiv.org/pdf/2207.05987.pdf) [[Code (under construction)]](https://github.com/shuyanzhou/doccoder) [[BibTex]](https://github.com/shuyanzhou/doccoder#citation)

## Accepted Papers
* **Neuro-Symbolic Language Modeling with Automaton-augmented Retrieval**{:id="retomaton"} (RetoMaton)
    * **Uri Alon**, Frank F. Xu, Junxian He, Sudipta Sengupta, Dan Roth, Graham Neubig
    * To appear in **_ICML'2022_**
    * [[PDF]](https://arxiv.org/pdf/2201.12431){:target="_blank"} [[Poster]](files/Retomaton_poster_ICML_2022.pdf){:target="_blank"} [[5-min Video]](https://recorder-v3.slideslive.com/?share=69099&s=f862fc4f-577c-4a54-a820-1fbb4786afb9){:target="_blank"} [[1-hour Video]](https://www.youtube.com/watch?v=-Au42BuWTEc){:target="_blank"} [[Slides]](files/retomaton_talk.pdf){:target="_blank"} [[BibTex]](https://pastebin.com/raw/ceVseymz){:target="_blank"}
    * [[Code - `fairseq` implementation]](https://github.com/neulab/retomaton){:target="_blank"} 
    * [[Code - HuggingFace 🤗 `transformers` implementation]](https://github.com/neulab/knn-transformers){:target="_blank"} [[Trained models]](neulab/distilgpt2-finetuned-wikitext103){:target="_blank"} 

* **How Attentive are Graph Attention Networks?**{:id="attentive"}
    * Shaked Brody, **Uri Alon**, Eran Yahav
    * Appeared in **_ICLR'2022_**
    * [[PDF]](https://arxiv.org/pdf/2105.14491.pdf){:target="_blank"} [[Poster]](https://shakedbr.cswp.cs.technion.ac.il/wp-content/uploads/sites/112/2022/03/poster.001.png){:target="_blank"} [[Code]](https://github.com/tech-srl/how_attentive_are_gats){:target="_blank"} [[Video]](https://drive.google.com/file/d/1B2uSH66dfROAgK7RVURjC4WrdSx9tPS_/view){:target="_blank"} [[BibTex]](https://pastebin.com/raw/besiLuqp){:target="_blank"}
    * GATv2 implementations:
      * [[PyTorch Geometric]](https://pytorch-geometric.readthedocs.io/en/latest/modules/nn.html#torch_geometric.nn.conv.GATv2Conv){:target="_blank"}: `from torch_geometric.nn.conv.gatv2_conv import GATv2Conv`
      * [[DGL]](https://docs.dgl.ai/en/latest/api/python/nn.pytorch.html#gatv2conv): &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;`from dgl.nn.pytorch import GATv2Conv`
      * [[TensorFlow GNN]](https://github.com/tensorflow/gnn/blob/main/tensorflow_gnn/docs/api_docs/python/gnn/keras/layers/GATv2.md){:target="_blank"}: &nbsp;&nbsp;&nbsp;`from tensorflow_gnn.keras.layers import GATv2`  

* **On the Bottleneck of Graph Neural Networks and its Practical Implications**
    * **Uri Alon**, Eran Yahav
    * Appeared in **_ICLR'2021_**
    * [[PDF]](https://arxiv.org/pdf/2006.05205){:target="_blank"} [[Poster]](files/bottleneck_poster.pdf){:target="_blank"} [[Slides]](files/bottleneck_slides.pdf){:target="_blank"} [**[Video]**](https://youtu.be/vrLsEwzZTCQ){:target="_blank"} [[Code]](https://github.com/tech-srl/bottleneck/){:target="_blank"} [[BibTex]](https://pastebin.pl/view/raw/f940b575){:target="_blank"}

* **A Structural Model for Contextual Code Changes**
    * Shaked Brody, **Uri Alon**, Eran Yahav
    * Appeared in **_OOPSLA’2020_**
    * [[PDF]](https://arxiv.org/pdf/2005.13209.pdf){:target="_blank"} [[Video]](https://youtu.be/NgY6nx3bU0M){:target="_blank"} [[Code]](https://github.com/tech-srl/c3po){:target="_blank"} [[BibTex]](https://pastebin.pl/view/raw/71d7c823){:target="_blank"}

* **Adversarial Examples for Models of Code**
    * Noam Yefet, **Uri Alon**, Eran Yahav
    * Appeared in **_OOPSLA’2020_**
    * [[PDF]](https://arxiv.org/pdf/1910.07517.pdf){:target="_blank"} [[Video]](https://youtu.be/lOdXDxaUkII){:target="_blank"} [[Code]](https://github.com/tech-srl/adversarial-examples){:target="_blank"} [[BibTex]](https://pastebin.pl/view/raw/3c8512de){:target="_blank"}

* **Neural Reverse Engineering of Stripped Binaries using Augmented Control Flow Graphs**
    * Yaniv David, Uri Alon, Eran Yahav
    * Appeared in **_OOPSLA’2020_**
    * [[PDF]](https://arxiv.org/pdf/1902.09122){:target="_blank"} [[Video]](https://youtu.be/CnCYd9QuiJ0){:target="_blank"} [[Code]](https://github.com/tech-srl/Nero){:target="_blank"} [[BibTex]](https://pastebin.pl/view/raw/d8794bd3){:target="_blank"}

* **Structural Language Models of Code**
    * **Uri Alon**, Roy Sadaka, Omer Levy, Eran Yahav
    * Appeared in **_ICML’2020_**
    * Online demo: [https://www.AnyCodeGen.org](https://www.AnyCodeGen.org){:target="_blank"}
    * [[PDF]](https://arxiv.org/pdf/1910.00577.pdf){:target="_blank"} [[Poster]](files/slm_poster.pdf){:target="_blank"} [[Slides]](files/slm-icml.pdf){:target="_blank"} [[Video]](https://slideslive.com/38927682/structural-language-models-of-code){:target="_blank"} [[Data]](https://github.com/tech-srl/slm-code-generation){:target="_blank"} [[Blog]](https://blog.sigplan.org/2020/05/11/from-programs-to-deep-models-part-3-code-completion/){:target="_blank"} [[BibTex]](https://pastebin.com/raw/8D64vzux){:target="_blank"}

* **Contextual Speech Recognition with Difficult Negative Training Examples**
    * **Uri Alon**, Golan Pundak, Tara N. Sainath
    * Appeared in **_ICASSP’2019_**
    * [[PDF]](https://arxiv.org/pdf/1810.12170){:target="_blank"} [[Poster]](files/icassp2019_poster.pdf){:target="_blank"} [[BibTex]](https://pastebin.com/raw/yfRdBvS1){:target="_blank"}
    
* **code2seq: Generating Sequences from Structured Representations of Code**
    * **Uri Alon**, Shaked Brody, Omer Levy, Eran Yahav
    * Appeared in **_ICLR’2019_**
    * Online demo: [https://code2seq.org](https://code2seq.org){:target="_blank"}
    * [[PDF]](https://arxiv.org/pdf/1808.01400){:target="_blank"} [[Poster]](files/ICLR19_poster_code2seq.pdf){:target="_blank"} [[Blog]](https://blog.sigplan.org/2020/02/12/from-programs-to-deep-models-part-2/){:target="_blank"} [[Code]](https://github.com/tech-srl/code2seq/){:target="_blank"} [[BibTex]](https://pastebin.com/raw/bw548FeG){:target="_blank"}

* **code2vec: Learning Distributed Representations of Code**
    * **Uri Alon**, Meital Zilberstein, Omer Levy, Eran Yahav
    * Appeared in **_POPL’2019_**
    * [**ACM SIGPLAN Research Highlight**](https://www.sigplan.org/Highlights/Papers/){:target="_blank"}
    * Online demo: [https://www.code2vec.org](https://www.code2vec.org){:target="_blank"}
    * [[PDF]](https://arxiv.org/pdf/1803.09473){:target="_blank"} [[Slides (PDF)]](files/code2vec_popl19_slides.pdf){:target="_blank"} [[Slides (PPT)]](files/code2vec_popl19_presentation.pptx){:target="_blank"} [[Video]](https://t.co/fjz2oVoDus){:target="_blank"} [[Blog]](https://blog.sigplan.org/2020/02/12/from-programs-to-deep-models-part-2/){:target="_blank"} [[Code]](https://github.com/tech-srl/code2vec){:target="_blank"} [[BibTex]](https://pastebin.com/raw/ddAkvska){:target="_blank"}

* **A General Path-Based Representation for Predicting Program Properties**
    * **Uri Alon**, Meital Zilberstein, Omer Levy, Eran Yahav
    * Appeared in **_PLDI’2018_**
    * [[PDF]](https://arxiv.org/pdf/1803.09544.pdf){:target="_blank"} [[Slides]](files/pldi18_slides.pdf){:target="_blank"} [[Video]](https://urialon.cswp.cs.technion.ac.il/wp-content/uploads/sites/83/2021/w03/bottleneck_poster.pdf){:target="_blank"} [[Blog]](https://blog.sigplan.org/2019/08/22/from-programs-to-deep-models-part-1/){:target="_blank"} [[Code]](https://github.com/tech-srl/PigeonJS){:target="_blank"} [[BibTex]](https://pastebin.com/raw/5tZQJ0ch){:target="_blank"}

## PhD Thesis
 * **Machine Learning for Programming Language Processing**
     * Computer Science Department, Technion, 2021
     * Awarded the [Reynolds Doctoral Dissertation Award](https://www.sigplan.org/Awards/Dissertation/){:target="_blank"} (formerly "SIGPLAN Outstanding Doctoral Dissertation Award")
     * [[PDF]](https://zenodo.org/record/6730561/files/thesis.pdf){:target="_blank"}

## Technical Reports


* **Lingvo: a Modular and Scalable Framework for Sequence-to-Sequence Modeling**
    * Jonathan Shen, ..., **Uri Alon**, ...
    * [[PDF]](https://arxiv.org/pdf/1902.08295.pdf){:target="_blank"}


## Workshops
* **A Systematic Evaluation of Large Language Models of Code**{:id="polycoder"} (PolyCoder)
    * Frank F. Xu, **Uri Alon**, Graham Neubig, Vincent J. Hellendoorn
    * Appeared in [MAPS'2022](https://pldi22.sigplan.org/details/maps-2022-papers/1/A-Systematic-Evaluation-of-Large-Language-Models-of-Code){:target="_blank"}
    * Appeared in [Deep Learning for Code](https://openreview.net/forum?id=SLcEnoObJZq){:target="_blank"}, ICLR'2022 workshop
    * Press: [[Forbes]](https://www.forbes.com/sites/janakirammsv/2022/03/14/5-ai-tools-that-can-generate-code-to-help-programmers){:target="_blank"} [[ZDNet]](https://www.zdnet.com/article/programming-languages-this-open-source-ai-code-generator-is-very-good-at-writing-in-c/){:target="_blank"} [[VentureBeat]](https://venturebeat.com/2022/03/04/researchers-open-source-code-generating-ai-they-claim-can-beat-openais-codex/){:target="_blank"} [[MarkTechPost]](https://www.marktechpost.com/2022/03/08/cmu-researchers-open-source-polycoder-a-machine-learning-based-code-generator-with-2-7b-parameters/){:target="_blank"}
    * [[PDF]](https://arxiv.org/pdf/2202.13169){:target="_blank"} [[Code]](https://github.com/VHellendoorn/Code-LMs){:target="_blank"} [[BibTex]](https://pastebin.com/raw/ZeNXqKUx){:target="_blank"}

* **Single-Node Attack for Fooling Graph Neural Networks**
    * Ben Finkelshtein, Chaim Baskin, Evgenii Zheltonovzhskii, **Uri Alon**
    * DLG-KDD'2021 [[PDF]](https://arxiv.org/pdf/2011.03574){:target="_blank"} [[Code]](https://github.com/benfinkelshtein/SINGLE){:target="_blank"} [[BibTex]](https://pastebin.pl/view/raw/3f25046a){:target="_blank"}
      

---
# Awards
* 2022 - [Reynolds Doctoral Dissertation Award](https://www.sigplan.org/Awards/Dissertation/){:target="_blank"} (formerly "SIGPLAN Outstanding Doctoral Dissertation Award")
* 2021-2022 – [Rothschild Post-Doctoral Fellowship](https://issuu.com/dleventer/docs/fellows-2021_booklet_corr-4/12){:target="_blank"}
* 2021-2022 – Fulbright Post-Doctoral Fellowship (declined)
* 2020 – [ACM SIGPLAN Research Highlight](https://www.sigplan.org/Highlights/Papers/){:target="_blank"}, "code2vec: Learning Distributed Representations of Code" (POPL’2019)
* 2019 – Jacobs Excellence Scholarship
* 2019 – Department Funding Excellence Scholarship
* 2018 – Department Funding Excellence Scholarship
* 2016 – Excellent Teaching Assistant
* 2016 – Dean’s Excellent Scholarship
* 2016 – Alumnus of the Rothchild-Technion Program for Excellence
* 2015 – SAMBA – CS Excellent Students

---
# Demos

{% include feature_row id="feature_row1" type="left" %}
<a name="code2vec"></a> 

{% include feature_row id="feature_row2" type="left" %}
<a name="code2seq"></a> 

{% include feature_row id="feature_row3" type="left" %}
<a name="AnyCodeGen"></a> 

---
# Service
* Program Committee: MAPS 2022, Deep Learning for Code ICLR'22 workshop, PLDI’2021, NeurIPS’2020 CAP workshop, AIDM’20, AIDM’19
* Reviewer: ICML'2022 (top 10% Best Reviewers), ICLR'2022 (Highlighted Reviewer), AIPLANS NeurIPS 2021 workshop, ICML’2021 (top 10% Best Reviewers), ICLR’2021, NeurIPS’2020, ICLR’2020


