# NLP Power!

The First Workshop on Efficient Benchmarking in NLP. The workshop programme will be available [here](https://nlp-power.github.io/program.html).

## Important dates

 - TBA

## Workshop description

Benchmarks have played a crucial role in accelerating progress in the field of NLP, covering a widerange of research directions: 
natural language understanding  (Wang  et  al.,  2019a,b),  natural  language generation (Gehrmann et al., 2021), cross-lingual knowledge transfer (Hu et al., 2020), prob-ing and interpretation (Conneau and Kiela, 2018;Conneau  et  al.,  2018),  ethical  biases  (Röttgeret al., 2020) and robustness to adversarial attacks (Morris  et  al.,  2020). Despite  that  the  concept of benchmarking has become a standard practicefor  evaluating  upcoming  models  against  one  another  and  human  solvers,  there  is  still  a  number of unresolved issues and methodological concerns (Rogers, 2019; Dehghani et al., 2021).

The main objectives of this workshop are: (1) encouraging the development of optimal model ranking and evaluation approaches for NLP benchmarks, (2) rethinking benchmarking strategies that best account for computational costs, energy and ethical considerations, out-of-domain language capabilities and meet the end user preferences. We welcome submissions on the ongoing and finished research and hope to provide an opportunity to present their work and exchange ideas. Particular topics of interest include, but are not limited to:

 - Computational efficiency and energy considerations;
 - New practices in measuring linguistic competence in mono- and multilingual benchmarks;
 - Critical analysis of existing benchmark evaluation and construction designs;
 - Guidelines for reproducibility and reliability of the benchmark results;
 - Construction of zero-shot and few-shot mono- and multilingual benchmarks;
 - Novel approaches to benchmark evaluation considering task complexity, model architecture, number of parameters and result aggregation;
 - Applications of utility theory, voting theory and microeconomics  to benchmark evaluation;
 - User and application-specific model evaluation;
 - New metrics and tasks for computationally lean comparison between models and measuring interpretability;
 - Analysis of human and model evaluation strategies in natural language understanding, text generation, knowledge transfer;
 - Human evaluation protocols, specifically in the multilingual setting;
 - Tracing biases and ethical issues in benchmark datasets and models.


The official call for papers is available [here](cfp.txt).

**Computational race & carbon footprints** A recent trend on scaling the  number of parameters in pretrained language models to hundreds of billions (Brown et al., 2020) has facilitated novel state-of-the-art results on NLU benchmarks at the cost of millions of dollars and large carbon footprint (Strubell  et  al.,  2019;  Lottick et  al., 2019; Bender et al., 2021). This often results in insignificant improvements, e.g. the difference in the overall score of current top-3  models on the SuperGLUE leaderboard is of maximum  0.3%. The trend also leads to the problem of unequal access to computational resources (Couldry and Mejias, 2020) and difficulties of using such models in academic and industrial fields (Schick  and  Schütze, 2021).

**Linguistic competence** Modern  models  struggle to learn rare phenomena from data, even when increasing the size of pre-training corpora (Zhang et  al.,  2020). The  linguistic  phenomena  generally  follow  Zipf  distribution,  meaning  that  most of them are harder to learn because of their rare presence in natural language data (Rogers, 2021). 

**Reproducibility crisis** Recent   studies   report that  reproducibility  of  the  stated  results  in  NLP is  hard  to  achieve  w.r.t. neural  models  (Belz et  al.,  2021a;  Bianchi  and  Hovy,  2021)  and  human solvers (Belz et al., 2021b), a scientific problem that has received the term of “reproducibility crisis” (Baker, 2016).  Systematic reviews of this kind raise doubts on the reliability of model ranking on canonical leaderboards, specifically against human baselines which are widely regarded as the standard form of tracing progress in the field. 

**Model and human evaluation design** The NLP field has not yet reached a consensus about benchmark methodological guidelines on model and human  evaluation  (Bowman  and  Dahl, 2021; Rodriguez et al., 2021). Many works detail cognitive biases in human evaluation (Schoch et al., 2020), critique unreliability of human baselines through crowd-sourcing (Nangia and Bowman, 2019), reinforce the need of independent evaluation in multiple languages (Linzen, 2020),  highlight the necessity  of  measuring  contribution  of  a  particular task to the resulting score (Choudhury and Deshpande,  2021),  and  evaluating  inference  time  and memory  consumption  (Kiela  et  al., 2021) along with  the  user  preferences  (Ethayarajh  and  Jurafsky, 2020).

**Application to real-word scenarios** Recent studies reveal that even those models, which gain highest scores in existing benchmarks, can  be fooled  be  carefully crafted adversarial  examples (Nie et al., 2020). This justifies the need for systematic evaluation of model robustness in form of adversarial attacks and other transformations, applied to test data (Wang et al., 2021; Goel et al., 2021).

**Data collection & leakage** Benchmark datasets076are traditionally collected from publicly available resources that may contain malicious and ethically inappropriate data (Liang et al., 2020). Moreover, recent  works  reveal  data  leakages  between  train and test sets (Elangovan et al., 2021; Lewis et al., 2021), rising questions whether the models indeed demonstrate their generalization abilities or simply learn statistical artefacts in the pre-training and downstream data. This has stimulated design of zero- and few-shot scenarios that assess generalization capacity of the models (Hou et al., 2020; Alex et al., 2021).

## Invited speakers

### Ulises A. Mejias [(SUNY Oswego)](https://blog.ulisesmejias.com/)
<img src="https://github.com/NLP-Power/nlp-power.github.io/blob/main/ulises_mejias.jpg?raw=true" width="100px" align="right">
Ulises A. Mejias is Professor of Communication Studies and director of the Institute for Global Engagement at SUNY Oswego. From 2021 to 2025, a Fulbright Specialist fellow. Ulises A. Mejias is co-founder of the Non-Aligned Technologies Movement and the network Tierra Común and also serves on the Board of Directors of Humanities New York, a National Endowment for the Humanities affiliate. Research interests include critical internet studies, network theory and science, philosophy of technology, sociology of communication, and political economy of digital media.

### Anna Rumshisky [(UMASS, Amazon)](https://www.uml.edu/sciences/computer-science/faculty/rumshisky-anna.aspx) 
<img src="https://github.com/NLP-Power/nlp-power.github.io/blob/main/rumshisky-anna.jpg?raw=true" width="100px" align="right">
Anna Rumshisky is an Associate Professor of Computer Science at the University of Massachusetts Lowell, where she heads the Text Machine Lab for NLP. Her primary research area is machine learning for natural language processing, with a focus on deep learning techniques. 


## Program Committee
 - Jürgen Schmidhuber (Swiss AI Lab IDSIA, USI, SUPSI, AIRI) 
 - Leonid Zhukov (AIRI)
 - Mikhail Burtsev (AIRI)
 - Anastasia Bonch-Osmolovskaya (HSE University)
 - Andrey Kravchenko (Oxford University)
 - Daniel Karabekyan (HSE University)
 - Preslav Nakov (QCRI) 
 - Suresh Manandhar (Wiseyak, USA)
 - Olga Lyashevskaya (Vinogradov IRL RAS, HSE University)

## Organizers

 - **Tatiana Shavrina** (AIRI, SberDevices) is a Research Project Manager in NLP at AI Research Institute, Moscow, Russia. Tatiana also works as a Chief Technology Expert in the Department of Experimental ML at SberDevices. Her research focus is on the evaluation and interpretation of the pretrained language models (LMs) training results.
 - **Valentin Malykh** (Huawei) has written his PhD thesis at Moscow Institute of Physics and Technology and defended it at the Institute for Systems Programming, Russian Academy of Sciences in 2019. Dr Malykh has more than 20 papers in the NLP field, including publications on such conferences as NeurIPS, ACL, WSDM. Now Valentin is employed as a senior research scientist at Huawei Noah's Ark laboratory.
 - **Ekaterina Artemova** (HSE University, Huawei) holds a PostDoc position at CS Faculty, HSE and advises Noah Ark's NLP team on advanced research topics. Ekaterina focuses on NLU tasks, ranging from ToD systems to IE, and creating new datasets. 
 - **Vladislav Mikhailov** (SberDevices, HSE University) is an R\&D NLP Engineer in the Department of Experimental ML at SberDevices and works as an invited lecturer in Big Data and IR School (HSE). 
 - **Oleg Serikov** (AIRI, HSE University) is a pro-active NLP Researcher at AIR Institute. Oleg now writes his PhD thesis at HSE University, his main points of interest are transfer learning, multilingual language modelling and benchmarking.
 - **Vitaly Protasov** (AIRI) works as an NLP Researcher at AIR Institute. Vitaly has a rich history of research collaborations in NLP with SkolTech, MIPT and Huawei, his main topics of interest now being transfer learning methods in benchmarking. 


## Workshop programme 

TBD

## Paper submission 

Papers and abstracts should follow the official __ 2022 style guidelines and should be submitted via ACL Rolling Review

Accepted submissions will be presented at the workshop: most as posters, some as oral presentations (determined by the program committee).

## Dual submissions and preprints 
Dual submissions with the main conference are allowed, but authors must declare dual submission by entering the paper's main conference submission id.
The reviews for the submission for the main conference will be automatically forwarded to the workshop and taken into consideration when your paper is evaluated.
Authors of dual-submission papers accepted to the main conference should retract them from the workshop by September 20.

Papers posted to preprint servers such as arxiv can be submitted
without any restrictions on when they were posted.

## Camera-ready information
Authors of accepted archival papers should upload the final version of their paper to the submission system by the camera-ready deadline. Authors may use one extra page to address reviewer comments, for a total of nine pages. 


## Anti-Harassment Policy
NLP Power 2022 adheres to the [ACL Anti-Harassment Policy](https://www.aclweb.org/adminwiki/sphp?title=Anti-Harassment_Policy).

## Demographic Diversity
The open exchange of ideas, the freedom of thought and expression, and respectful scientific debate are central to our workshop. First, we will make sure that the ACL Anti-Harassment Policy is respected during the organization and execution of the event. Second, our approach to the selection of invited speakers / PC takes into consideration the need for demographic diversity. Third, our organizing team includes individuals from diverse genders and sociodemographic backgrounds.
