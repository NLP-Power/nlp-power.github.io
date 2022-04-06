## About the workshop

Benchmarks have played a crucial role in accelerating progress in the field of NLP, covering a wide range of research directions: natural language understanding (GLUE, SuperGLUE), natural language generation (GEM), cross-lingual knowledge transfer (XGLUE, XTREME), probing, and interpretation (LINSPECTOR, SentEval), hate speech and bias (HateCheck, StereoSet, HONEST) and robustness to adversarial attacks (RobustnessGym,  AdvGLUE).  Despite the fact that the concept of benchmarking has become a standard practice for evaluating upcoming models against one another and human solvers, there are still a number of unresolved issues and methodological concerns.

<img src="./pic2.jpg" alt="hi" class="inline" height="400"/>

The main objectives of this workshop are to (1) create a space for critical reflection on current benchmarks and evaluation tools, (2) encourage the development of improved or new benchmarks and evaluation tools that resolve current challenges, (3) develop better approaches to model ranking, (4) rethink benchmarking strategies that best account for computational costs, energy and ethical considerations, out-of-domain language capabilities and meeting the end-user preferences. We welcome submissions on ongoing and finished research and hope to provide an opportunity for participants to present their work and exchange ideas. Particular topics of interest include, but are not limited to:
 - Computational efficiency and energy considerations in NLP benchmarks;
 - New practices in measuring linguistic competence in mono- and multilingual benchmarks;
 - Critical analysis of existing benchmark evaluation and construction designs;
 - Guidelines for reproducibility and reliability of the benchmark results;
 - Construction of zero-shot and few-shot mono- and multilingual benchmarks;
 - Novel approaches to benchmark evaluation considering task complexity, model architecture, number of parameters and result aggregation;
 - Applications of utility theory, voting theory and microeconomics to benchmark evaluation;
 - User and application-specific model evaluation;
 - New metrics and tasks for computationally lean comparison between models and measuring interpretability;
 - Benchmarks and other evaluation methods to analyse ethical or social aspects of NLP tools;
 - Analysis of human and model evaluation strategies in natural language understanding, text generation, knowledge transfer;
 - Human evaluation protocols, specifically in the multilingual setting;
 - Tracing biases and ethical issues in benchmark datasets and models.


**Computational race & carbon footprints** A recent trend on scaling the  number of parameters in pretrained language models to hundreds of billions (Brown et al., 2020) has facilitated novel state-of-the-art results on NLU benchmarks at the cost of millions of dollars and large carbon footprint (Strubell  et  al.,  2019;  Lottick et  al., 2019; Bender et al., 2021). This often results in insignificant improvements, e.g. the difference in the overall score of current top-3  models on the SuperGLUE leaderboard is of maximum  0.3%. The trend also leads to the problem of unequal access to computational resources (Couldry and Mejias, 2020) and difficulties of using such models in academic and industrial fields (Schick  and  Schütze, 2021).

**Linguistic competence** Modern  models  struggle to learn rare phenomena from data, even when increasing the size of pre-training corpora (Zhang et  al.,  2020). The  linguistic  phenomena  generally  follow  Zipf  distribution,  meaning  that  most of them are harder to learn because of their rare presence in natural language data (Rogers, 2021). 

**Reproducibility crisis** Recent   studies   report that  reproducibility  of  the  stated  results  in  NLP is  hard  to  achieve  w.r.t. neural  models  (Belz et  al.,  2021a;  Bianchi  and  Hovy,  2021)  and  human solvers (Belz et al., 2021b), a scientific problem that has received the term of “reproducibility crisis” (Baker, 2016).  Systematic reviews of this kind raise doubts on the reliability of model ranking on canonical leaderboards, specifically against human baselines which are widely regarded as the standard form of tracing progress in the field. 

**Model and human evaluation design** The NLP field has not yet reached a consensus about benchmark methodological guidelines on model and human  evaluation  (Bowman  and  Dahl, 2021; Rodriguez et al., 2021). Many works detail cognitive biases in human evaluation (Schoch et al., 2020), critique unreliability of human baselines through crowd-sourcing (Nangia and Bowman, 2019), reinforce the need of independent evaluation in multiple languages (Linzen, 2020),  highlight the necessity  of  measuring  contribution  of  a  particular task to the resulting score (Choudhury and Deshpande,  2021),  and  evaluating  inference  time  and memory  consumption  (Kiela  et  al., 2021) along with  the  user  preferences  (Ethayarajh  and  Jurafsky, 2020).

**Application to real-word scenarios** Recent studies reveal that even those models, which gain highest scores in existing benchmarks, can  be fooled  be  carefully crafted adversarial  examples (Nie et al., 2020). This justifies the need for systematic evaluation of model robustness in form of adversarial attacks and other transformations, applied to test data (Wang et al., 2021; Goel et al., 2021).

**Data collection & leakage** Benchmark datasets076are traditionally collected from publicly available resources that may contain malicious and ethically inappropriate data (Liang et al., 2020). Moreover, recent  works  reveal  data  leakages  between  train and test sets (Elangovan et al., 2021; Lewis et al., 2021), rising questions whether the models indeed demonstrate their generalization abilities or simply learn statistical artefacts in the pre-training and downstream data. This has stimulated design of zero- and few-shot scenarios that assess generalization capacity of the models (Hou et al., 2020; Alex et al., 2021).



## Ethics policy

Authors are required to honour the ethical code set out in the ACL Code of
Ethics, and comply with the ethics guidelines for ARR submissions.

## Anti-Harassment Policy
NLP Power 2022 adheres to the [ACL Anti-Harassment Policy](https://www.aclweb.org/adminwiki/sphp?title=Anti-Harassment_Policy).

## Demographic Diversity
The open exchange of ideas, the freedom of thought and expression, and respectful scientific debate are central to our workshop. First, we will make sure that the ACL Anti-Harassment Policy is respected during the organization and execution of the event. Second, our approach to the selection of invited speakers / PC takes into consideration the need for demographic diversity. Third, our organizing team includes individuals from diverse genders and sociodemographic backgrounds.
