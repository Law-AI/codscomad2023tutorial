# AI & Law: Formative Developments, State-of-the-Art Approaches, Challenges & Opportunities
This repository contains all detailed information and resources for this upcoming tutorial at CODS-COMAD 2023, due to be held at IIT Bombay, 3rd January 2023.

# Abstract
Artificial Intelligence (AI), Machine Learning (ML), and Natural Language Processing (NLP) are  transforming the way legal professionals and law firms approach their work. The significant potential for the application of AI to Law, for instance, by creating computational solutions for legal tasks, has intrigued researchers for decades. This appeal has only been amplified with the advent of Deep Learning (DL). In particular, research in AI \& Law can be extremely beneficial in countries like India with an overburdened legal system.
    
In this tutorial, we will give an overview of the various aspects of applying AI to legal textual data. 
We will start with a history of AI \& Law, and then discuss the current state of AI \& Law research including the techniques that have produced the biggest impact. We will also take a deep dive into the software processes required to implement and sustain such AI solutions.

# Task-specific Resources
This section contains resources for different automation tasks in the legal domain

## Legal Named Entity Recognition

This task aims to identify different entities in legal documents. Entities may be classified into different groups that have different legal meanings, such as the parties (appellants, respondents), lawyers, judges and so on.

+ <a href="https://github.com/elenanereiss/Legal-Entity-Recognition"> A Dataset of German Legal Documents for Named Entity Recognition </a> (<a href="https://aclanthology.org/2020.lrec-1.551.pdf">Lietner et al., 2020</a>)
+ <a href="https://github.com/Legal-NLP-EkStep/legal_NER"> Named Entity Recognition in Indian court judgments </a> (<a href="https://arxiv.org/pdf/2211.03442.pdf">Kalamkar et al., 2022</a>)

## Legal Judgment Prediction

Broadly speaking, this task aims to determine the outcomes of court cases. In many settings, this may be composed of several sub-tasks, which are addressed in the forthcoming sections.

+ <a href="https://github.com/koc-lab/law-turk"> Natural language processing in law: Prediction of outcomes in the higher courts of Turkey </a> (<a href="https://www.sciencedirect.com/science/article/pii/S0306457321001692?via%3Dihub">Mumcuoglu et al., 2021</a>)
+ <a href="https://pub.cl.uzh.ch/wiki/public/pacoco/swiss_legislation_corpus"> Building corpora for the philological study of Swiss legal texts </a> (<a href="https://www.zora.uzh.ch/id/eprint/54761/">Hofler et al., 2011</a>)
+ <a href="https://github.com/Exploration-Lab/CJPE"> ILDC for CJPE: Indian Legal Documents Corpus for Court Judgment Prediction and Explanation </a> (<a href="https://aclanthology.org/2021.acl-long.313.pdf">Malik et al., 2021</a>)
+ <a href="https://github.com/masha-medvedeva/ECtHR_crystal_ball"> Judicial Decisions of the European Court of Human Rights: Looking into the Crystal Ball </a> (<a href="http://martijnwieling.nl/files/Medvedeva-submitted.pdf">Medvedeva et al., 2018</a>)
+ <a href="https://github.com/thunlp/CAIL"> CAIL2018: A Large-Scale Legal Dataset for Judgment Prediction </a> (<a href="https://arxiv.org/pdf/1807.02478.pdf">Xiao et al., 2018</a>)

## Identifying Legal Articles and Charges

Often considered a sub-task of Legal Judgment Prediction, this task aims to identify the relevant legal articles and charges given the facts of a case.

+ <a href="https://github.com/Law-AI/LeSICiN"> LeSICiN: A Heterogeneous Graph-based Approach for Automatic Legal Statute Identification from Indian Legal Documents </a> (<a href="https://ojs.aaai.org/index.php/AAAI/article/view/21363">Paul et al., 2022</a>)
+ <a href="https://github.com/IntelligentLaw/HMN"> Hierarchical Matching Network for Crime Classification </a> (<a href="https://dl.acm.org/doi/pdf/10.1145/3331184.3331223">Wang et al., 2019</a>)
+ <a href="https://github.com/Law-AI/automatic-charge-identification"> Automatic Charge Identification from Facts: A Few Sentence-Level Charge Annotations is All You Need </a> (<a href="https://aclanthology.org/2020.coling-main.88.pdf">Paul et al., 2020</a>)
+ <a href="https://github.com/nlp208/legal_attention"> Charge Prediction with Legal Attention </a> (<a href="https://link.springer.com/chapter/10.1007/978-3-030-32233-5_35">Bao et al., 2019</a>)

## Semantic Segmentation / Rhetorical Role Labeling

Court case documents are composed of several functional parts such as Facts, Arguments, Ruling, etc. which may not be clearly demarcated. This task aims to automate the process of segmenting a court case document into these parts.

+ <a href="https://github.com/Law-AI/semantic-segmentation"> Identification of Rhetorical Roles of Sentences in Indian Legal Judgments </a> (<a href="https://arxiv.org/pdf/1911.05405.pdf">Bhattacharya et al., 2019</a>)
+ <a href="https://datasets.doctrine.fr/"> The French Court Decision Structure dataset — FCD12K </a>

## Pre-trained Language Models for the Legal Domain

Recently there have been many efforts to pre-train large, transformer-based language models for the legal domain, which have been adapted to many down-stream end tasks with spectacular efficiency.

+ <a href="https://huggingface.co/nlpaueb/legal-bert-base-uncased"> LEGAL-BERT: The Muppets straight out of Law School </a> (<a href="https://aclanthology.org/2020.findings-emnlp.261.pdf">Chalkidis et al., 2020</a>)
+ <a href="https://huggingface.co/zlucia/legalbert"> When Does Pretraining Help? Assessing Self-Supervised Learning for Law and the CaseHOLD Dataset of 53,000+ Legal Holdings </a> (<a href="https://arxiv.org/pdf/2104.08671v3.pdf">Zheng et al., 2021</a>)
+ <a href="https://huggingface.co/pile-of-law/legalbert-large-1.7M-1"> Pile of Law: Learning Responsible Data Filtering from the Law and a 256GB Open-Source Legal Dataset </a> (<a href="https://arxiv.org/pdf/2207.00220.pdf">Henderson et al., 2022</a>)
+ <a href="https://huggingface.co/law-ai/InLegalBERT"> Pre-training Transformers on Indian Legal Text </a> (<a href="https://arxiv.org/pdf/2209.06049.pdf">Paul et al., 2022</a>)

# Presenters

+ **Jack G. Conrad**, *Director of Applied Research and Lead Research Scientist, TR Labs at Thomson Reuters, Minneapolis, MN  USA*
    + Jack Conrad is Director of Applied Research at Thomson Reuters TR Labs where he  focuses on a broad range of technical application areas involving AI, machine learning and textual data processing.  He also fosters cross-team collaboration and communication in the process of implementing and deploying technology to meet business needs. For over two decades, he has  delivered critical artifacts and infrastructure for research and business directed projects across a diverse spectrum of domains that have included legal, tax and news.  Jack has published more than 50 peer reviewed research papers and has eight patents. He is passionate about the power of AI transformation in enterprise environments.
    Jack is past president of the International Association for Artificial Intelligence and Law (IAAIL.org) and has served on the IAAIL Executive Committee for 8 years. Jack’s areas of expertise include research in the fields of  information retrieval (search), question answering, NLP, machine learning, data mining, and system evaluation.
    
+ **Shirsha Ray Chaudhuri**, *Director of Engineering, TR Labs at Thomson Reuters, Bangalore, Karnataka, India*
    + Shirsha Ray Chaudhuri is the Director of Engineering at Thomson Reuters Labs, Bangalore. TR Labs is TR's applied research division, focused on delivering solutions with AI and emerging tech to TR's platforms and products and customer Proof of Concepts (PoCs). TR’s editorial workflows power its best-in-class product like Westlaw. The TR Labs team in Bangalore contributes to leveraging AI in these editorial workflows. Her earlier work includes strategic architecture and prototyping for Daimler's EvoBus team to help route planning software solutions for electric buses, predictive maintenance solutions for Daimler's DTNA service centres, and use of AI for rapid field ops in Daimler's Japan-based FUSO trucks. Besides providing point-in-time solutions for a single use case, she implemented generic modifications of such AI services which could be replicated across geographies and operators.   

+ **Shounak Paul**, *Senior Research Fellow, Deptt. of Computer Science \&, Engineering, IIT Kharagpur, West Bengal, India*
    + Shounak Paul is a Senior Research Fellow at the Department of CSE, IIT Kharagpur. His research interests mainly include legal data analytics and applications of NLP in the legal domain. His works on AI & Law for Indian applications have been published in premier conferences and journals such as: semantic segmentation (JURIX 2019, best paper award; AI & Law Journal 2021), charge identification (COLING 2020) and legal statute identification using citation networks (AAAI 2022).

+ **Saptarshi Ghosh**, *Assistant Professor, Deptt. of Computer Science \&, Engineering, IIT Kharagpur, West Bengal, India* 
    + Saptarshi Ghosh is an Assistant Professor at the Department of CSE, IIT Kharagpur. His research interests include Legal analytics, Social media analytics, and Algorithmic bias and fairness (on which he presently leads a Max Planck Partner Group at IIT Kharagpur). His works on AI \& Law have been published at premier conferences including SIGIR, AAAI, CIKM, ECIR, COLING, and have been awarded at top AI & Law conferences, including the Best Paper Award at the International Conference on Legal Knowledge and Information Systems (JURIX) 2019, and the Best Student Paper Award at the International Conference on Artificial Intelligence and Law (ICAIL) 2021. He is presently the Section Editor on Legal Information Retrieval for the journal Artificial Intelligence and Law, the premier journal in AI & Law. He has been awarded with several prestigious awards, including the Institution of Engineers (India) Young Engineer Award 2017-18 in Computer Engineering discipline. 
