## Papers on machine learning for proteins

### Background

We recently released a [review](https://arxiv.org/abs/1811.10775) of machine learning methods in protein engineering, but the field changes so fast and there are so many new papers that any static document will inevitably be missing important work. This format also allows us to broaden the scope beyond engineering-specific applications. We hope that this will be a useful resource for people interested in the field.

To the best of our knowledge, this is the first public, collaborative list of machine learning papers on protein applications. We try to classify papers based on a combination of their applications and model type. If you have suggestions for other papers or categories, please make a pull request or issue!

### Format

Within each category, papers are listed in reverse chronological order (newest first). Where possible, a link should be provided.

### Categories

[Reviews](#reviews)  
[Tools](#tools)  
[Machine-learning guided directed evolution](#machine-learning-guided-directed-evolution)  
[Representation learning](#representation-learning)  
[Unsupervised variant prediction](#unsupervised-variant-prediction)  
[Generative models](#generative-models)  
[Predicting stability](#predicting-stability)  
[Predicting structure from sequence](#predicting-structure-from-sequence)  
[Predicting sequence from structure](#predicting-sequence-from-structure)  
[Classification and annotation](#classification-and-annotation)  
[Predicting interactions with other molecules](#predicting-interactions-with-other-molecules)  
[Other supervised learning](#other-supervised-learning)

### Reviews

**Machine learning and AI-based approaches for bioactive ligand discovery and GPCR-ligand recognition.**  
Sebastian Raschka, Benjamin Kaufman.  
*Preprint, January 2020.*  
[[arXiv](https://arxiv.org/abs/2001.06545v2)]

**Machine Learning in Enzyme Engineering.**   
Stanislav Mazurenko, Zbynek Prokop, Jiri Damborsky.   
*ACS Catalysis, December 2019.*   
[[doi.org/10.1021/acscatal.9b04321](https://doi.org/10.1021/acscatal.9b04321)]  

**Machine learning-guided directed evolution for protein engineering.**  
Kevin K. Yang, Zachary Wu, Frances H. Arnold.   
*Nature Methods, July 2019.*   
[[doi.org/10.1038/s41592-019-0496-6](https://doi.org/10.1038/s41592-019-0496-6)]  
Preprint available on [arxiv](https://arxiv.org/abs/1811.10775). 

**Evaluating Protein Transfer Learning with TAPE.**   
Roshan Rao, Nicholas Bhattacharya, Neil Thomas, Yan Duan, Xi Chen, John Canny, Pieter Abbeel, Yun S. Song.   
*Preprint, June 2019.*   
[[arxiv](https://arxiv.org/abs/1906.08230)]

**Can Machine Learning Revolutionize Directed Evolution of Selective Enzymes?**  
Guangyue Li, Yijie Dong, Manfred T. Reetz.  
*Advanced Synthesis & Catalysis, March 2019.*  
[[10.1002/adsc.201900149](https://doi.org/10.1002/adsc.201900149)]

### Tools

**Selene: a PyTorch-based deep learning library for sequence data.**  
Kathleen M. Chen, Evan M. Cofer, Jian Zhou, Olga G. Troyanskaya.  
*Nature Methods, March 2019.*  
[[doi.org/10.1038/s41592-019-0360-8](https://doi.org/10.1038/s41592-019-0360-8)]

### Machine-learning guided directed evolution

**A Deep Dive into Machine Learning Models for Protein Engineering.**  
Yuting Xu, Deeptak Verma, Robert P Sheridan, Andy Liaw, Junshui Ma, Nicholas
Marshall, John McIntosh, Edward C. Sherer, Vladimir Svetnik, Jennifer Johnston.  
*Journal of Chemical Information and Modeling, April 2020.*  
[[10.1021/acs.jcim.0c00073](https://doi.org/10.1021/acs.jcim.0c00073)]

**Evolutionary context-integrated deep sequence modeling for protein engineering.**  
Yunan Luo, Lam Vo, Hantian Ding, Yufeng Su, Yang Liu, Wesley Wei Qian, Huimin Zhao, Jian Peng.  
*Preprint, January 2020.*  
[[10.1101/2020.01.16.908509](https://doi.org/10.1101/2020.01.16.908509)]

**Biological Sequence Design using Batched Bayesian Optimization.**  
David Belanger, Suhani Vora, Zelda Mariet, Ramya Deshpande, David Dohan, Christof Angermueller, Kevin Murphy, Olivier Chapelle, Lucy Colwell.  
*NeurIPS Workshop on Machine Learning and the Physical Sciences, December 2019.*  
[[ML4PS](https://ml4physicalsciences.github.io/files/NeurIPS_ML4PS_2019_141.pdf)]

**Model Inversion Networks for Model-Based Optimization.**  
Aviral Kumar, Sergey Levine
*Preprint, December 2019.*  
[[arxiv](https://arxiv.org/abs/1912.13464v1)]

**Interpreting mutational effects predictions, one substitution at a time.**  
C. K. Sruthi, Meher K. Prakash.  
*bioRxiv, December 2019*  
[[doi.org/10.1101/867812](https://doi.org/10.1101/867812)]

**A structure-based deep learning framework for protein engineering.**  
Raghav Shroff, Austin W. Cole, Barrett R. Morrow, Daniel J. Diaz, Isaac Donnell, Jimmy Gollihar, Andrew D. Ellington, Ross Thyer.  
*Preprint, November 2019.*  
[[10.1101/833905](https://doi.org/10.1101/833905)]

**Comprehensive AAV capsid fitness landscape reveals a viral gene and enables machine-guided design.**  
Pierce J. Ogden, Eric D. Kelsic, Sam Sinai, George M. Church.  
*Science, November 2019.*  
[[10.1126/science.aaw2900](https://doi.org/10.1126/science.aaw2900)]

**Machine learning-guided channelrhodopsin engineering enables minimally-invasive optogenetics.**  
Claire N. Bedbrook, Kevin K. Yang, J. Elliott Robinson, Viviana Gradinaru, Frances H Arnold.    
*Nature Methods, October 2019.*  
[[10.1038/s41592-019-0583-8](https://doi.org/10.1038/s41592-019-0583-8)]   
Preprint available on [[bioRxiv](https://www.biorxiv.org/content/10.1101/565606v1)]

**Batched Stochastic Bayesian Optimization via Combinatorial Constraints Design**.   
Kevin K. Yang, Yuxin Chen, Alycia Lee, Yisong Yue.   
*International Conference on Artificial Intelligence and Statistics (AISTATS), April 2019.*  
[[arxiv](https://arxiv.org/abs/1904.08102)] [[PMLR](http://proceedings.mlr.press/v89/yang19c.html)]

**Machine learning-assisted directed protein evolution with combinatorial libraries.**  
Zachary Wu, S. B. Jennifer Kan, Russell D. Lewis, Bruce J. Wittmann, Frances H. Arnold.  
*PNAS, April 2019.*  
[[10.1073/pnas.1901979116](https://doi.org/10.1073/pnas.1901979116)]

**Conditioning by adaptive sampling for robust design.**  
David H. Brookes, Hahnbeom Park, Jennifer Listgarten.  
*Preprint, January 2019.*  
[[arxiv](https://arxiv.org/abs/1901.10060)]

**A machine learning approach for reliable prediction of amino acid interactions and its application in the directed evolution of enantioselective enzymes.**  
Frédéric Cadet, Nicolas Fontaine, Guangyue Li, Joaquin Sanchis, Matthieu Ng Fuk Chong, Rudy Pandjaitan, Iyanar Vetrivel, Bernard Offmann, Manfred T. Reetz.  
*Scientific Reports, November 2018.*  
[[10.1038/s41598-018-35033-y](https://doi.org/10.1038/s41598-018-35033-y)]

**Design by adaptive sampling.**  
David H. Brookes, Jennifer Listgarten.  
*Preprint, October 2018.*  
[[arxiv](https://arxiv.org/abs/1810.03714)]

**Machine-Learning-Guided Mutagenesis for Directed Evolution of Fluorescent Proteins.**  
Yutaka Saito, Misaki Oikawa, Hikaru Nakazawa, Teppei Niide, Tomoshi Kameda, Koji Tsuda, and Mitsuo Umetsu.  
*ACS Synthetic Biology, August 2018.*  
[[10.1021/acssynbio.8b00155](https://doi.org/10.1021/acssynbio.8b00155)]

**Toward machine-guided design of proteins.**  
Surojit Biswas,  Gleb Kuznetsov, Pierce J. Ogden, Nicholas J. Conway, Ryan P. Adams, George M. Church.  
*Preprint, June 2018.*  
[[10.1101/337154](https://doi.org/10.1101/337154)] [[bioRxiv](https://www.biorxiv.org/content/10.1101/337154v1)]

**Feedback GAN (FBGAN) for DNA: a Novel Feedback-Loop Architecture for Optimizing Protein Functions.**  
Anvita Gupta, James Zou.  
*Preprint, April 2018.*  
[[arxiv](https://arxiv.org/abs/1804.01694)]

**Machine learning to design integral membrane channelrhodopsins for efficient eukaryotic expression and plasma membrane localization.**  
Claire N. Bedbrook, Kevin K. Yang, Austin J. Rice, Viviana Gradinaru, Frances H. Arnold.  
*PLOS Computational Biology, October 2017.*  
[[10.1371/journal.pcbi.1005786](https://doi.org/10.1371/journal.pcbi.1005786)]

**Exploring sequence-function space of a poplar glutathione transferase using designed information-rich gene variants.**  
Yaman Musdal, Sridhar Govindarajan, Bengt Mannervik.  
*Protein Engineering, Design, and Selection, August 2017.*  
[[10.1093%2Fprotein%2Fgzx045](https://dx.doi.org/10.1093%2Fprotein%2Fgzx045)]

**Navigating the protein fitness landscape with Gaussian processes.**  
Philip A. Romero, Andreas Krause, Frances H. Arnold.  
*PNAS, January 2013.*  
[[10.1073/pnas.1215251110](https://doi.org/10.1073/pnas.1215251110)]

**Engineering proteinase K using machine learning and synthetic genes.**  
Jun Liao, Manfred K. Warmuth, Sridhar Govindarajan, Jon E. Ness, Rebecca P Wang, Claes Gustafsson, Jeremy Minshull.  
*BMC Biotechnology, March 2007.*  
[[10.1186/1472-6750-7-16](https://doi.org/10.1186/1472-6750-7-16)]

**Improving catalytic function by ProSAR-driven enzyme evolution.**  
Richard J. Fox, S. Christopher Davis, Emily C. Mundorff, Lisa M. Newman, Vesna Gavrilovic, Steven K. Ma, Loleta M. Chung, Charlene Ching, Sarena Tam, Sheela Muley, John Grate, John Gruber, John C. Whitman, Roger A. Sheldon, Gjalt W. Huisman.  
*Nature Biotechnology, February 2007.*  
[[Nature Biotechnology](https://www.nature.com/articles/nbt1286)]

### Representation learning

**Unsupervised protein embeddings outperform hand-crafted sequence and structure features at predicting molecular function.**  
Amelia Villegas-Morcillo, Stavros Makrodimitris, Roeland van Ham, Angel M. Gomez, Victoria Sanchez, Marcel Reinders.  
*Preprint, April 2020.*  
[[10.1101/2020.04.07.028373](https://doi.org/10.1101/2020.04.07.028373)]

**Site2Vec: a reference frame invariant algorithm for vector embedding of protein-ligand binding sites.**  
Arnab Bhadra, Kalidas Y.  
*Preprint, March 2020.*  
[[arxiv](https://arxiv.org/abs/2003.08149v1)]

**Evolutionary context-integrated deep sequence modeling for protein engineering.**  
Yunan Luo, Lam Vo, Hantian Ding, Yufeng Su, Yang Liu, Wesley Wei Qian, Huimin Zhao, Jian Peng.  
*Preprint, January 2020.*  
[[10.1101/2020.01.16.908509](https://doi.org/10.1101/2020.01.16.908509)]

**Sequence representations and their utility for predicting protein-protein interactions.**  
Dhananjay Kimothi, Pravesh Biyani, James M Hogan.  
*Preprint, December 2019.*  
[[10.1101/2019.12.31.890699](https://doi.org/10.1101/2019.12.31.890699)]

**Language modelling for biological sequences – curated datasets and baselines.**  
Jose Juan Almagro Armenteros, Alexander Rosenberg Johansen, Ole Winther, Henrik Nielsen.  
*Preprint, December 2019*.  
[[alrojo.github.io](https://alrojo.github.io/media/publications/LMProteins/preprint.pdf)]

**Deciphering protein evolution and fitness landscapes with latent space models**  
Xinqiang Ding, Zhengting Zou, Charles L. Brooks III.  
*Nature Communications, December 2019.*  
[[doi.org/10.1038/s41467-019-13633-0](https://doi.org/10.1038/s41467-019-13633-0)]

**End-to-end multitask learning, from protein language to protein features without alignments.**  
Ahmed Elnaggar, Michael Heinzinger, Christian Dallago, Burkhard Rost.  
*Preprint, December 2019.*  
[[10.1101/864405](https://doi.org/10.1101/864405)]

**Unified rational protein engineering with sequence-only deep representation learning.**  
Ethan C. Alley, Grigory Khimulya, Surojit Biswas, Mohammed AlQuraishi, George M. Church.  
*Nature Methods, October 2019*  
[[10.1038/s41592-019-0598-1](https://doi.org/10.1038/s41592-019-0598-1)]

**Structure-Based Function Prediction using Graph Convolutional Networks.**  
Vladimir Gligorijevic, P. Douglas Renfrew, Tomasz Kosciolek, Julia Koehler Leman, Kunghyun Cho, Tommi Vatanen, Daniel Berenberg, Bryn Taylor, Ian M. Fisk, Ramnik J. Xavier, Rob Knight, Richard Bonneau.  
*Preprint, October 2019*.  
[[0.1101/786236](https://doi.org/10.1101/786236)]

**Modeling the language of life – Deep Learning Protein Sequences.**  
Michael Heinzinger, Ahmed Elnaggar, Yu Wang, Christian Dallago, Dmitrii Nechaev, Florian Matthes, Burkhard Rost.  
*Preprint, September 2019.*  
[[10.1101/614313](https://doi.org/10.1101/614313)]

**Augmenting Protein Network Embeddings with Sequence Information.**  
Hassan Kane, Mohamed K. Coulibali, Pelkins Ajanoh, Ali Abdallah.  
*Preprint, August 2019.*  
[[10.1101/730481](https://doi.org/10.1101/730481)]

**Universal Deep Sequence Models for Protein Classification.**  
Nils Strodthoff, Patrick Wagner, Markus Wenzel, Wojciech Samek.  
*Preprint, July 2019.*  
[[10.1101/704874](https://doi.org/10.1101/704874)]

**DeepPrime2Sec: Deep Learning for Protein Secondary Structure Prediction from the Primary Sequences.**  
Ehsaneddin Asgari, Nina Poerner, Alice C. McHardy,  Mohammad R.K. Mofrad.  
*Preprint, July 2019.*  
[[10.1101/705426](https://doi.org/10.1101/705426)]

**A Self-Consistent Sonification Method to Translate Amino Acid Sequences into Musical Compositions and Application in Protein Design Using Artificial Intelligence.**  
Chi-Hua Yu, Zhao Qin, Francisco J. Martin-Martinez, Markus J. Buehler.  
*ACS Nano, June 2019.*  
[[10.1021/acsnano.9b02180](https://doi.org/10.1021/acsnano.9b02180)]

**Evaluating Protein Transfer Learning with TAPE.**  
Roshan Rao, Nicholas Bhattacharya, Neil Thomas, Yan Duan, Xi Chen, John Canny, Pieter Abbeel, Yun S. Song.  
*Preprint, June 2019.*  
[[arxiv](https://arxiv.org/abs/1906.08230)]

**Leveraging implicit knowledge in neural networks for functional dissection and engineering of proteins.**  
Julius Upmeier zu Belzen, Thore Bürgel, Stefan Holderbach, Felix Bubeck, Lukas Adam, Catharina Gandor, Marita Klein, Jan Mathony, Pauline Pfuderer, Lukas Platz, Moritz Przybilla, Max Schwendemann, Daniel Heid, Mareike Daniela Hoffmann, Michael Jendrusch, Carolin Schmelas, Max Waldhauer, Irina Lehmann, Dominik Niopek, Roland Eils.  
*Nature Machine Intelligence, May 2019.*  
[[Nature Machine Intelligence](https://www.nature.com/articles/s42256-019-0049-9)]

**Modeling the Language of Life – Deep Learning Protein Sequences.**   
Michael Heinzinger, Ahmed Elnaggar, Yu Wang, Christian Dallago, Dmitrii Nechaev, Florian Matthes, Burkhard Rost.  
*Preprint, May 2019.*  
[[10.1101/614313](https://doi.org/10.1101/614313)] [[bioRxiv](https://www.biorxiv.org/content/10.1101/614313v2)]

**Biological Structure and Function Emerge from Scaling Unsupervised Learning to 250 Million Protein Sequences.**  
Alexander Rives, Siddharth Goyal, Joshua Meier, Demi Guo, Myle Ott, C. Lawrence Zitnick, Jerry Ma, Rob Fergus.  
*Preprint, April 2019.*  
[[10.1101/622803](https://doi.org/10.1101/622803)] [[bioRxiv](https://www.biorxiv.org/content/10.1101/622803v1)]

**Learning protein constitutive motifs from sequence data.**  
Jérôme Tubiana, Simona Cocco, Rémi Monasson.  
*eLife, March 2019.*  
[[10.7554/eLife.39397](https://doi.org/10.7554/eLife.39397)]

**Learning protein sequence embeddings using information from structure.**  
Tristan Bepler, Bonnie Berger.  
*International Conference on Learning Representations, February 2019.*  
[[ICLR](https://arxiv.org/abs/1902.08661)] 

**Application of fourier transform and proteochemometrics principles to protein engineering.**  
Frédéric Cadet, Nicolas Fontaine, Iyanar Vetrivel, Matthieu Ng Fuk Chong, Olivier Savriama, Xavier Cadet, Philippe Charton.  
*BMC Bioinformatics, October 2018.*  
[[10.1186/s12859-018-2407-8](https://doi.org/10.1186/s12859-018-2407-8)]

**Learned protein embeddings for machine learning.**  
Kevin K Yang, Zachary Wu, Claire N Bedbrook, Frances H Arnold  
*Bioinformatics, August 2018*  
[[10.1093/bioinformatics/bty178](https://doi.org/10.1093/bioinformatics/bty178)] 

**Deep Semantic Protein Representation for Annotation, Discovery, and Engineering.**  
Ariel S Schwartz, Gregory J Hannum, Zach R Dwiel, Michael E Smoot, Ana R Grant, Jason M Knight, Scott A Becker, Jonathan R Eads, Matthew C LaFave, Harini Eavani, Yinyin Liu, Arjun K Bansal, Toby H Richardson   
*Preprint, July 2018*   
[[10.1101/365965](https://doi.org/10.1101/365965)]  

**Improved Descriptors for the Quantitative Structure–Activity Relationship Modeling of Peptides and Proteins.**  
Mark H. Barley, Nicholas J. Turner, Royston Goodacre.  
*Journal of Chemical Information and Modeling, January 2018.*  
[[10.1021/acs.jcim.7b00488](https://doi.org/10.1021/acs.jcim.7b00488)]

**Variational auto-encoding of protein sequences.**  
Sam Sinai, Eric Kelsic, George M. Church, Martin A. Nowak  
*Preprint, December 2017*  
[[arxiv](https://arxiv.org/abs/1712.03346)]

**Predicting Protein Binding Affinity With Word Embeddings and Recurrent Neural Networks.**  
Carlo Mazzaferro.  
*Preprint, April 2017.*  
[[10.1101/128223](https://doi.org/10.1101/128223)] [[bioRxiv](https://www.biorxiv.org/node/37703.abstract)]

**dna2vec: Consistent vector representations of variable-length k-mers.**  
Patrick Ng  
*Preprint, January 2017*  
[[arxiv](https://arxiv.org/abs/1701.06279)]  

**Distributed Representations for Biological Sequence Analysis.**  
Dhananjay Kimothi, Akshay Soni, Pravesh Biyani, James M. Hogan  
*Preprint, August 2016*  
[[arxiv](https://arxiv.org/abs/1608.05949)]  

**ProFET: Feature engineering captures high-level protein functions.**  
Dan Ofer, Michal Linial.  
*Bioinformatics, June 2015.*  
[[10.1093/bioinformatics/btv345](https://doi.org/10.1093/bioinformatics/btv345)]

**AAindex: amino acid index database, progress report 2008.**  
Shuichi Kawashima, Piotr Pokarowski, Maria Pokarowska, Andrzej Kolinski, Toshiaki Katayama, Minoru Kanehisa.  
*Nucleic Acids Research, January 2008.*  
[[10.1093/nar/gkm998](https://doi.org/10.1093/nar/gkm998)] 

### Unsupervised variant prediction

**Unsupervised inference of protein fitness landscape from deep mutational scan.**  
Jorge Fernandez-de-Cossio-Diaz, Guido Uguzzoni, Andrea Pagnani.  
*Preprint, March 2020.*  
[[10.1101/2020.03.18.996595](https://doi.org/10.1101/2020.03.18.996595)]


**Deep generative models of genetic variation capture the effects of mutations.**  
Adam J. Riesselman, John B. Ingraham, Debora S. Marks   
*Nature Methods, September 2018*  
[[10.1038/s41592-018-0138-4](https://doi.org/10.1038/s41592-018-0138-4)] 

**Variational auto-encoding of protein sequences.**  
Sam Sinai, Eric Kelsic, George M. Church, Martin A. Nowak  
*Preprint, December 2017*  
[[arxiv](https://arxiv.org/abs/1712.03346)] 

### Generative models

**Designing Feature-Controlled Humanoid Antibody Discovery Libraries Using Generative Adversarial Networks.**  
Tileli Amimeur, Jeremy M. Shaver, Randal R. Ketchem, J. Alex Taylor, Rutilio H. Clark, Josh Smith, Danielle Van Citters, Christine C. Siska, Pauline Smidt, Megan Sprague, Bruce A. Kerwin, Dean Pettit.
*Preprint, April 2020.*
[[10.1101/2020.04.12.024844](https://doi.org/10.1101/2020.04.12.024844)]

**ProGen: Language Modeling for Protein Generation.**  
Ali Madani, Bryan McCann, Nikhil Naik, Nitish Shirish Keskar, Namrata Anand, Raphael R. Eguchi, Po-Ssu Huang, Richard Socher.  
*Preprint, March 2020.*  
[[10.1101/2020.03.07.982272](https://doi.org/10.1101/2020.03.07.982272)]


**Expanding functional protein sequence space using generative adversarial networks.**  
Donatas Repecka, Vykintas Jauniskis, Laurynas Karpus, Elzbieta Rembeza, Jan Zrimec, Simona Poviloniene, Irmantas Rokaitis, Audrius Laurynenas, Wissam Abuajwa, Otto Savolainen, Rolandas Meskys, Martin K. M. Engqvist, Aleksej Zelezniak.  
*Preprint, October 2019.*  
[[10.1101/789719](https://doi.org/10.1101/789719)]

**De Novo Protein Design for Novel Folds using Guided Conditional Wasserstein Generative Adversarial Networks (gcWGAN).**  
Mostafa Karimi, Shaowen Zhu, Yue Cao, Yang Shen.  
*Preprint, September 2019.*  
[[10.1101/769919](https://doi.org/10.1101/769919)]

**Reconstructing continuous distributions of 3D protein structure from cryo-EM images.**  
Ellen D. Zhong, Tristan Bepler, Joseph H. Davis, Bonnie Berger.  
*Preprint, September 2019.*
[[arXiv](https://arxiv.org/abs/1909.05215)]

**Accelerating Protein Design Using Autoregressive Generative Models.**  
Adam Riesselman, Jung-Eun Shin, Kollasch, Conor McMahon, Elana Simon, Chris Sander, Aashish Manglik, Andrew Kruse,  Debora Marks.  
*Preprint, September 2019.*  
[[10.1101/757252](https://doi.org/10.1101/757252)]

**Deep generative models for T cell receptor protein sequences.**  
Kristian Davidsen, Branden J. Olson, William S. DeWitt III, Jean Feng, Elias Harkins, Philip Bradley, Frederick A. Matsen IV.  
*eLife, September 2019*.  
[[10.7554/eLife.46935.001](https://doi.org/10.7554/eLife.46935.001)]

**Generative Models for Graph-Based Protein Design.**  
John Ingraham, Vikas K. Garg, Regina Barzilay, Tommi Jaakkola.  
*ICLR workshop on Deep Generative Models for Highly Structured Data, May 2019.*  
[[OpenReview](https://openreview.net/pdf?id=SJgxrLLKOE)]

**How to Hallucinate Functional Proteins.**  
Zak Costello, Hector Garcia Martin  
*Preprint, March 2019*  
[[arxiv](https://arxiv.org/abs/1903.00458)]  

**Conditioning by adaptive sampling for robust design.**  
David H. Brookes, Hahnbeom Park, Jennifer Listgarten.  
*Preprint, January 2019.*  
[[arxiv](https://arxiv.org/abs/1901.10060)]

**Generative modeling for protein structures.**  
Namrata Anand, Po-Ssu Huang.  
*NeurIPS, December 2018.*  
[[NeurIPS](https://papers.nips.cc/paper/7978-generative-modeling-for-protein-structures.pdf)]

**Design of metalloproteins and novel protein folds using variational autoencoders.**  
Joe G. Greener, Lewis Moffat, David T Jones.  
*Scientific Reports, November 2018.*  
[[10.1038/s41598-018-34533-1](https://doi.org/10.1038/s41598-018-34533-1)]

**Design by adaptive sampling.**  
David H. Brookes, Jennifer Listgarten.  
*Preprint, October 2018.*  
[[arxiv](https://arxiv.org/abs/1810.03714)]

**Deep generative models of genetic variation capture the effects of mutations.**  
Adam J Riesselman, John B Ingraham, Debora S. Marks   
*Nature Methods, September 2018*  
[[10.1038/s41592-018-0138-4](https://doi.org/10.1038/s41592-018-0138-4)] 

**Feedback GAN (FBGAN) for DNA: a Novel Feedback-Loop Architecture for Optimizing Protein Functions.**  
Anvita Gupta, James Zou.  
*Preprint, April 2018.*  
[[arxiv](https://arxiv.org/abs/1804.01694)]

**Recurrent Neural Network Model for Constructive Peptide Design.**  
Alex T. Müller, Jan A. Hiss, and Gisbert Schneider.  
*Journal of Chemical Information and Modeling, January 2018*  
[[10.1021/acs.jcim.7b00414](https://doi.org/10.1021/acs.jcim.7b00414)]

**Variational auto-encoding of protein sequences.**  
Sam Sinai, Eric Kelsic, George M. Church, Martin A. Nowak  
*Preprint, December 2017*  
[[arxiv](https://arxiv.org/abs/1712.03346)]

### Predicting stability

**Predicting changes in protein thermostability upon point mutation with deep 3D convolutional neural networks.**  
Bian Li, Yucheng T. Yang, John A. Capra, Mark B. Gerstein.  
*Preprint, February 2020.*  
[[10.1101/2020.02.28.959874](https://doi.org/10.1101/2020.02.28.959874)]

**Machine Learning for Prioritization of Thermostabilizing Mutations for G-protein Coupled Receptors.**  
S. Muk, S. Ghosh, S. Achuthan, X. Chen, X. Yao, M. Sandhu, M. C. Griffor, K. F. Fennell, Y. Che, V. Shanmugasundaram, X. Qiu, C. G. Tate, N. Vaidehi.  
*Preprint, July 2019.*  
[[10.1101/715375](https://doi.org/10.1101/715375)]

**mGPfusion: predicting protein stability changes with Gaussian process kernel learning and data fusion.**
Emmi Jokinen, Markus Heinonen, Harri Lähdesmäki.  
*Bioinformatics, July 2018.*  
[[10.1093/bioinformatics/bty238](https://doi.org/10.1093/bioinformatics/bty238)]

**Structure Based Thermostability Prediction Models for Protein Single Point Mutations with Machine Learning Tools.**  
Lei Jia , Ramya Yarlagadda, Charles C. Reed.  
*PLOS One, September 2015.*  
[[10.1371/journal.pone.0138022](https://doi.org/10.1371/journal.pone.0138022)]

**NeEMO: a method using residue interaction networks to improve prediction of protein stability upon mutation.**  
Manuel Giollo, Alberto J. M. Martin†, Ian Walsh, Carlo Ferrari, Silvio C. E. Tosatto.  
*BMC Genomics, May 2014.*  
[[10.1186/1471-2164-15-S4-S7](https://doi.org/10.1186/1471-2164-15-S4-S7)]

**mCSM: predicting the effects of mutations in proteins using graph-based signatures.**  
Douglas E. V. Pires, David B. Ascher, Tom L. Blundell.  
*Bioinformatics, February 2014.*  
[[10.1093/bioinformatics/btt691](https://doi.org/10.1093/bioinformatics/btt691)]

**PROTS-RF: A Robust Model for Predicting Mutation-Induced Protein Stability Changes.**  
Yunqi Li, Jianwen Fang.  
*PLOS One, October 2012.*  
[[10.1371/journal.pone.0047247](https://doi.org/10.1371/journal.pone.0047247)]

**Predicting changes in protein thermostability brought about by single- or multi-site mutations.**  
Jian Tian, Ningfeng Wu, Xiaoyu Chu, Yunliu Fan.  
*BMC Bioinformatics, July 2010.*  
[[10.1186/1471-2105-11-370](https://doi.org/10.1186/1471-2105-11-370)]

**Fast and accurate predictions of protein stability changes upon mutations using statistical potentials and neural networks: PoPMuSiC-2.0.**  
Yves Dehouck, Aline Grosfils, Benjamin Folch, Dimitri Gilis, Philippe Bogaerts, Marianne Rooman.  
*Bioinformatics, October 2009.*  
[[10.1093/bioinformatics/btp445](https://doi.org/10.1093/bioinformatics/btp445)]

**Prediction of protein stability changes for single‐site mutations using support vector machines.**  
Jianlin Cheng, Arlo Randall, Pierre Baldi.  
*Proteins, December 2005*.  
[[10.1002/prot.20810](https://doi.org/10.1002/prot.20810)]

**Predicting protein stability changes from sequences using support vector machines.**  
Emidio Capriotti, Piero Fariselli, Remo Calabrese, Rita Casadio.  
*Bioinformatics, September 2005.*  
[[10.1093/bioinformatics/bti1109](https://doi.org/10.1093/bioinformatics/bti1109)]

**I-Mutant2.0: predicting stability changes upon mutation from the protein sequence or structure.**  
Emidio Capriotti, Piero Fariselli, Rita Casadio.  
*Nucleic Acids Research, July 2005.*  
[[10.1093/nar/gki375](https://doi.org/10.1093/nar/gki375)]

**A neural-network-based method for predicting protein stability changes upon single point mutations.**  
Emidio Capriotti, Piero Fariselli, Rita Casadio.  
*Bioinformatics, August 2004.*  
[[10.1093/bioinformatics/bth928](https://doi.org/10.1093/bioinformatics/bth928)]

**Mismatch string kernels for discriminative protein classification.**  
Christina S. Leslie, Eleazar Eskin, Adiel Cohen, Jason Weston, William Stafford Noble.  
*Bioinformatics, March 2004.*  
[[10.1093/bioinformatics/btg431](https://doi.org/10.1093/bioinformatics/btg431)]

### Predicting structure from sequence

**Energy-based models for atomic-resolution protein conformations.**  
Yilun Du, Joshua Meier, Jerry Ma, Rob Fergus, Alexander Rives.  
*ICLR, April 2020.*  
[[arXiv](https://arxiv.org/abs/2004.13167)]

**A fully open-source framework for deep learning protein real-valued distances.**  
Badri Adhikari.  
*Preprint, April 2020.*  
[[10.1101/2020.04.26.061820]( https://doi.org/10.1101/2020.04.26.061820)]

**PhANNs, a fast and accurate tool and web server to classify phage structural proteins.**  
Victor Seguritan, Jackson Redfield, David Salamon, Robert A. Edwards, Anca M. Segall.  
*Preprint, April 2020.*  
[[10.1101/2020.04.03.023523]( https://doi.org/10.1101/2020.04.03.023523)]

**Improved protein structure prediction using predicted inter-residue orientations.**  
Jianyi Yang, Ivan Anishchenko, Hahnbeom Park, Zhenling Peng, Sergey Ovchinnikov, David Baker.  
*PNAS, January 2020.*  
[[10.1073/pnas.1914677117]( https://doi.org/10.1073/pnas.1914677117)]

**Improved protein structure prediction using potentials from deep learning.**  
Andrew W. Senior, Richard Evans, John Jumper, James Kirkpatrick, Laurent Sifre, Tim Green, Chongli Qin, Augustin Žídek, Alexander W. R. Nelson, Alex Bridgland, Hugo Penedones, Stig Petersen, Karen Simonyan, Steve Crossan, Pushmeet Kohli, David T. Jones, David Silver, Koray Kavukcuoglu, Demis Hassabis.  
*Nature, January 2020.*  
[[10.1038/s41586-019-1923-7](https://doi.org/10.1038/s41586-019-1923-7)]

**Deep learning extends de novo protein modelling coverage of genomes using iteratively predicted structural constraints.**  
Joe G. Greener, Shaun M. Kandathil, David T. Jones.  
*Nature Communications, September 2019.*  
[[10.1038/s41467-019-11994-0](https://doi.org/10.1038/s41467-019-11994-0)]

**DeepPrime2Sec: Deep Learning for Protein Secondary Structure Prediction from the Primary Sequences.**  
Ehsaneddin Asgari, Nina Poerner, Alice C. McHardy,  Mohammad R.K. Mofrad.  
*Preprint, July 2019.*  
[[10.1101/705426](https://doi.org/10.1101/705426)]

**End-to-End Differentiable Learning of Protein Structure.**  
Mohammed AlQuraishi.  
*Cell Systems, April 2019.*  
[[10.1016/j.cels.2019.03.006](https://doi.org/10.1016/j.cels.2019.03.006)]

**DESTINI: A deep-learning approach to contact-driven protein structure prediction.**  
Mu Gao, Hongyi Zhou, Jeffrey Skolnick.  
*Scientific Reports, March 2019.*  
[[10.1038/s41598-019-40314-1](https://doi.org/10.1038/s41598-019-40314-1)]


**Learning protein sequence embeddings using information from structure.**  
Tristan Bepler, Bonnier Berger.  
*International Conference on Learning Representations, February 2019.*  
[[ICLR](https://arxiv.org/abs/1902.08661)] 

**Generative modeling for protein structures.**  
Namrata Anand, Po-Ssu Huang.  
*NeurIPS, December 2018.*  
[[NeurIPS](https://papers.nips.cc/paper/7978-generative-modeling-for-protein-structures.pdf)]

**Distance-based Protein Folding Powered by Deep Learning.**  
Jinbo Xu.  
*Preprint, November 2018.*  
[[arxiv](https://arxiv.org/abs/1811.03481)]

**Porter 5: fast, state-of-the-art ab initio prediction of protein secondary structure in 3 and 8 classes.**  
Mirko Torrisi, Manaz Kaleel, Gianluca Pollastri.  
*Preprint, October 2018.*  
[[10.1101/289033](https://doi.org/10.1101/289033)] [[bioRxiv](https://www.biorxiv.org/content/10.1101/289033v4)]

**Protein Secondary Structure Prediction Based on Data Partition and Semi-Random Subspace Method.**  
Yuming Ma, Yihui Liu, Jinyong Cheng.  
*Scientific Reports, June 2018.*  
[[10.1038/s41598-018-28084-8](https://doi.org/10.1038/s41598-018-28084-8)]


**Protein Secondary Structure Prediction with Long Short Term Memory Networks.**  
Søren Kaae Sønderby, Ole Winther.
*Preprint, December 2014.*  
[[arxiv](https://arxiv.org/abs/1412.7828)] 

**Deep Supervised and Convolutional Generative Stochastic Network for Protein Secondary Structure Prediction.**  
Jian Zhou, Olga G. Troyanskaya.  
*Preprint, March 2014.*  
[[arxiv](https://arxiv.org/abs/1403.1347)]

### Predicting sequence from structure

**Protein Sequence Design with a Learned Potential.**  
Namrata Anand, Raphael R. Eguchi, Alexander Derry, Russ B. Altman, Po-Ssu Huang.  
*Preprint, January 2020.*  
[[10.1101/2020.01.06.895466](https://doi.org/10.1101/2020.01.06.895466)]

**Designing real novel proteins using deep graph neural networks.**  
Alexey Strokach, David Becerra, Carles Corbi, Albert Perez-Riba, Philip M. Kim.  
*Preprint, December 2019.*  
[[10.1101/868935](https://doi.org/10.1101/868935)] [[bioRxiv](https://www.biorxiv.org/content/10.1101/868935v1)]

**ProDCoNN: Protein design using a convolutional neural network.**  
Yuan Zhang, Yang Chen, Chenran Wang, Chun‐Chao Lo, Xiuwen Liu, Wei Wu, Jinfeng Zhang.  
*Proteins: Structure, Function, Bioinformatics, December 2019.*  
[[10.1002/prot.25868]( https://doi.org/10.1002/prot.25868)]

**RamaNet: Computational De Novo Protein Design using a Long Short-Term Memory Generative Adversarial Neural Network.**  
Sari Sabban, Mikhail Markovsky.  
*Preprint, June 2019.*  
[[10.1101/671552](https://doi.org/10.1101/671552)] [[bioRxiv](https://www.biorxiv.org/content/10.1101/671552v1)]

**Generative Models for Graph-Based Protein Design.**  
John Ingraham, Vikas K. Garg, Regina Barzilay, Tommi Jaakkola.  
*ICLR workshop on Deep Generative Models for Highly Structured Data, May 2019.*  
[[OpenReview](https://openreview.net/pdf?id=SJgxrLLKOE)]

**SPIN2: Predicting sequence profiles from protein structures using deep neural networks.**  
James O'Connell, Zhixiu Li, Jack Hansonm, Rhys Heffernan, James Lyons, Kuldip Paliwal, Abdollah Dehzangi, Yuedong Yang, Yaoqi Zhou.  
*Proteins, March 2018.*  
[[10.1002/prot.25489](https://doi.org/10.1002/prot.25489)]

### Classification and annotation

**Unsupervised protein embeddings outperform hand-crafted sequence and structure features at predicting molecular function.**  
Amelia Villegas-Morcillo, Stavros Makrodimitris, Roeland van Ham, Angel M. Gomez, Victoria Sanchez, Marcel Reinders.  
*Preprint, April 2020.*  
[[10.1101/2020.04.07.028373](https://doi.org/10.1101/2020.04.07.028373)]

**Machine Learning Predicts New Anti-CRISPR Proteins.**  
Gavin J. Knott, Jennifer A. Doudna, Fayyaz ul Amir Afsar Minhas.  
*Preprint, November 2019.*  
[[10.1101/854950](https://doi.org/10.1101/854950)]

**Improving protein function prediction with synthetic feature samples created by generative adversarial networks.**  
Cen Wan, David T. Jones.  
*Preprint, August 2019.*  
[[10.1101/730143](https://doi.org/10.1101/730143)]

**Universal Deep Sequence Models for Protein Classification.**  
Nils Strodthoff, Patrick Wagner, Markus Wenzel, Wojciech Samek.  
*Preprint, July 2019.*  
[[10.1101/704874](https://doi.org/10.1101/704874)]

**Critiquing Protein Family Classification Models Using Sufficient Input Subsets.**  
Brandon Carter, Maxwell L. Bileschi, Jamie Smith, Theo Sanderson, Drew Bryant, David Belanger, Lucy J. Colwell.  
*Preprint, June 2019.*  
[[10.1101/674119](https://doi.org/10.1101/674119)] [[bioRxiv](https://www.biorxiv.org/content/10.1101/674119v1)]

**A Brief History of Protein Sorting Prediction.**  
Henrik Nielsen, Konstantinos D. Tsirigos, Søren Brunak, Gunnar von Heijne.  
*The Protein Journal, May 2019.*  
[[10.1007/s10930-019-09838-3](https://doi.org/10.1007/s10930-019-09838-3)]

**DEEPred: Automated Protein Function Prediction with Multi-task Feed-forward Deep Neural Networks.**  
Ahmet Sureyya Rifaioglu, Tunca Dogan, Maria Jesus Martin, Rengul Cetin-Atalay, Volkan Atalay.  
*Scientific Reports, May 2019.*  
[[10.1038/s41598-019-43708-3](https://doi.org/10.1038/s41598-019-43708-3)]

**Using Deep Learning to Annotate the Protein Universe.**  
Maxwell L. Bileschi, David Belanger, Drew Bryant, Theo Sanderson, Brandon Carter, D. Sculley, Mark A. DePristo, Lucy J. Colwell.  
*Preprint, May 2019.*  
[[10.1101/626507](https://doi.org/10.1101/626507)] [[bioRxiv](https://www.biorxiv.org/content/10.1101/626507v3)]

**ECPred: a tool for the prediction of the enzymatic functions of protein sequences based on the EC nomenclature.**  
Alperen Dalkiran, Ahmet Sureyya Rifaioglu, Maria Jesus Martin, Rengul Cetin-Atalay, Volkan Atalay, Tunca Dogan.  
*BMC Bioinformatics, September 2018.*  
[[10.1186/s12859-018-2368-y](https://doi.org/10.1186/s12859-018-2368-y)]

**DeepGO: predicting protein functions from sequence and interactions using a deep ontology-aware classifier.**  
Maxat Kulmanov, Mohammed Asif Khan, Robert Hoehndorf.  
*Bioinformatics, February 2018.*  
[[10.1093/bioinformatics/btx624](https://doi.org/10.1093/bioinformatics/btx624)]

**Near perfect protein multi-label classification with deep neural networks.**  
Balázs Szalkaia, Vince Grolmuszab.  
*Methods, January 2018.*  
[[10.1016/j.ymeth.2017.06.034](https://doi.org/10.1016/j.ymeth.2017.06.034)]

**Large‐scale automated function prediction of protein sequences and an experimental case study validation on PTEN transcript variants.**  
Ahmet Sureyya Rifaioglu, Tunca Dogan, Omer Sinan Sarac, Tulin Ersahin, Rabie Saidi, Mehmet Volkan Atalay, Maria Jesus Martin, Rengul Cetin‐Atalay.  
*Proteins, November 2017.*  
[[10.1002/prot.25416](https://doi.org/10.1002/prot.25416)]

**ProLanGO: Protein Function Prediction Using Neural Machine Translation Based on a Recurrent Neural Network.**  
Renzhi Cao, Colton Freitas, Leong Chan, Miao Sun, Haiqing Jiang, Zhangxin Chen.  
*Molecules, October 2017.*  
[[10.3390/molecules22101732](https://doi.org/10.3390/molecules22101732)]

**Continuous Distributed Representation of Biological Sequences for Deep Proteomics and Genomics.**  
Ehsaneddin Asgari, Mohammad R. K. Mofrad  
*PLOS One, November 2015.*  
[[10.1371/journal.pone.0141287](https://doi.org/10.1371/journal.pone.0141287)]

**A structural alignment kernel for protein structures.**  
Jian Qiu, Martial Hue, Asa Ben-Hur, Jean-Philippe Vert, William Stafford Noble  
*Bioinformatics, January 2007.*  
[[10.1093/bioinformatics/btl642](https://doi.org/10.1093/bioinformatics/btl642)]  

**The spectrum kernel: A string kernel for SVM protein classification.**  
Christina S Leslie, Eleazar Eskin, William Stafford Noble.  
*Pacific Symposium on Biocomputing, January 2002.*  
[[pdf](http://psb.stanford.edu/psb-online/proceedings/psb02/leslie.pdf)]

### Predicting interactions with other molecules

**Site2Vec: a reference frame invariant algorithm for vector embedding of protein-ligand binding sites.**  
Arnab Bhadra, Kalidas Y.  
*Preprint, March 2020.*  
[[arxiv](https://arxiv.org/abs/2003.08149v1)]

**Mutation effect estimation on protein-protein interactions using deep contextualized representation learning**  
Guangyu Zhou, Muhao Chen, Chelsea J.-T. Ju, Zheng Wang, Jyun-Yu Jiang, Wei Wang.  
*NAR Genomics and Bioinformatics, March 2020*  
[[10.1093/nargab/lqaa015](https://doi.org/10.1093/nargab/lqaa015)]  

**Biophysical prediction of protein–peptide interactions and signaling networks using machine learning.**  
Joseph M. Cunningham, Grigoriy Koytiger, Peter K. Sorger & Mohammed AlQuraishi.  
*Nature Methods, January 2020.*  
[[10.1038/s41592-019-0687-1](https://doi.org/10.1038/s41592-019-0687-1)]

**Functions of olfactory receptors are decoded from their sequence.**  
Xiaojing Cong, Wenwen Ren, Jody Pacalon, Claire A. de March, Lun Xu, Hiroaki Matsunami, Yiqun Yu, Jérôme Golebiowski.  
*Preprint, January 2020.*  
[[10.1101/2020.01.06.895540](https://doi.org/10.1101/2020.01.06.895540)]

**Explainable Deep Relational Networks for Predicting Compound-Protein Affinities and Contacts.**  
Mostafa Karimi, Di Wu, Zhangyang Wang, Yang Shen.  
*Preprint, December 2019.*  
[[arxiv](https://arxiv.org/abs/1912.12553v1)]

**Using Single Protein/Ligand Binding Models to Predict Active Ligands for Previously Unseen Proteins**.  
Vikram Sundar, Lucy Colwell.  
*NeurIPS Workshop on Machine Learning and the Physical Sciences, December 2019.*  
[[ML4PS](https://ml4physicalsciences.github.io/files/NeurIPS_ML4PS_2019_66.pdf)]

**Deciphering interaction fingerprints from protein molecular surfaces using geometric deep learning.**  
P. Gainza, F. Sverrisson, F. Monti, E. Rodolà, D. Boscaini, M. M. Bronstein, B. E. Correia.  
*Nature Methods, December 2019.*  
[[10.1038/s41592-019-0666-6](https://doi.org/10.1038/s41592-019-0666-6)]

**End-to-End Learning on 3D Protein Structure for Interface Prediction**  
Raphael J. L. Townshend, Rishi Bedi, Patricia A. Suriana, Ron O. Dror.  
*NeurIPS, December 2019.*  
[[arxiv](https://arxiv.org/abs/1807.01297)]

**USMPep: Universal Sequence Models for Major Histocompatibility Complex Binding Affinity Prediction.**  
Johanna Vielhaben, Markus Wenzel, Wojciech Samek, Nils Strodthoff.  
*Preprint, October 2019.* 
[[10.1101/816546](https://doi.org/10.1101/816546)]

**DeepCLIP: Predicting the effect of mutations on protein-RNA binding with Deep Learning.**  
Alexander Gulliver Bjørnholt Grønning, Thomas Koed Doktor, Simon Jonas Larsen, Ulrika Simone Spangsberg Petersen, Lise Lolle Holm, Gitte Hoffmann Bruun, Michael Birkerod Hansen, Anne-Mette Hartung, Jan Baumbach, Brage Storstein Andresen.  
*Preprint, September 2019.*  
[[10.1101/757062](https://doi.org/10.1101/757062)] 

**Multifaceted protein–protein interaction prediction based on Siamese residual RCNN**  
Muhao Chen, Chelsea J.-T. Ju, Guangyu Zhou, Xuelu Chen, Tianran Zhang, Kai-Wei Chang, Carlo Zaniolo, Wei Wang.  
*Bioinformatics, July 2019. (Procs. ISMB/ECCB-2019)*  
[[10.1093/bioinformatics/btz328](https://doi.org/10.1093/bioinformatics/btz328)]  

**DeepConv-DTI: Prediction of drug-target interactions via deep learning with convolution on protein sequences.**  
Ingoo Lee, Jongsoo Keum, Hojung Nam.  
*PLOS Computational Biology, June 2019.*  
[[10.1371/journal.pcbi.1007129](https://doi.org/10.1371/journal.pcbi.1007129)]

**Leveraging binding-site structure for drug discovery with point-cloud methods.**  
Vincent Mallet, Carlos G. Oliver, Nicolas Moitessier, Jerome Waldispuhl.  
*Preprint, May 2019.*  
[[arXiV]](https://arxiv.org/abs/1905.12033)]

**Repertoires of G protein-coupled receptors for Ciona-specific neuropeptides.**  
Akira Shiraishi, Toshimi Okuda, Natsuko Miyasaka, Tomohiro Osugi, Yasushi Okuno, Jun Inoue, and Honoo Satake.  
*PNAS, March 2019.*  
[[10.1073/pnas.1816640116]( https://doi.org/10.1073/pnas.1816640116)]

**Simple tricks of convolutional neural network architectures improve DNA–protein binding prediction.**  
Zhen Cao, Shihua Zhang.  
*Bioinformatics, October 2018.*  
[[10.1093/bioinformatics/bty893](https://doi.org/10.1093/bioinformatics/bty893)

**MHCflurry: Open-Source Class I MHC Binding Affinity Prediction.**  
Timothy J. O'Donnell, Alex Rubinsteyn, Maria Bonsack, Angelika B. Riemer, Uri Laserson, Jeff Hammerbacher.  
*Cell Systems, June 2018.*  
[[10.1016/j.cels.2018.05.014](https://doi.org/10.1016/j.cels.2018.05.014)]

**P2Rank: machine learning based tool for rapid and accurate prediction of ligand binding sites from protein structure.**    
Radoslav Krivak, David Hoksza.  
*Journal of Cheminformatics, August 2018*.  
[[10.1186/s13321-018-0285-8](https://doi.org/10.1186/s13321-018-0285-8)]  

**DeepMHC: Deep Convolutional Neural Networks for High-performance peptide-MHC Binding Affinity Prediction.**  
Jianjun Hu, Zhonghao Liu.  
*Preprint, December 2017.*  
[[10.1101/239236](https://doi.org/10.1101/239236)] [[bioRxiv](https://www.biorxiv.org/content/10.1101/239236v1)]

**DeepSite: protein-binding site predictor using 3D-convolutional neural networks.**  
J, Jiménez. S. Doerr, G. Martínez-Rosell, A. S. Rose, G. De Fabritiis.  
*Bioinformatics, October 2017.*  
[[10.1093/bioinformatics/btx350](https://doi.org/10.1093/bioinformatics/btx350)]

**Predicting Protein Binding Affinity With Word Embeddings and Recurrent Neural Networks.**  
Carlo Mazzaferro.  
*Preprint, April 2017.*    
[[10.1101/128223](https://doi.org/10.1101/128223)] [[bioRxiv](https://www.biorxiv.org/node/37703.abstract)]

**Atomic Convolutional Networks for Predicting Protein-Ligand Binding Affinity.**  
Joseph Gomes, Bharath Ramsundar, Evan N. Feinberg, Vijay S. Pande.  
*Preprint, March 2017.*  
[[arxiv](https://arxiv.org/abs/1703.10603)]

**Convolutional neural network architectures for predicting DNA–protein binding.**  
Haoyang Zeng, Matthew D. Edwards. Ge Liu, David K. Gifford.  
*Bioinformatics, 15 June 2016.*  
[[10.1093/bioinformatics/btw255](https://doi.org/10.1093/bioinformatics/btw255)]

**A deep learning framework for modeling structural features of RNA-binding protein targets.**  
Sai Zhang, Jingtian Zhou, Hailin Hu, Haipeng Gong, Ligong Chen, Chao Cheng, Jianyang Zeng.  
*Nucleic Acids Research, October 2015.*  
[[10.1093/nar/gkv1025](https://doi.org/10.1093/nar/gkv1025)]

**Predicting the sequence specificities of DNA- and RNA-binding proteins by deep learning.**  
Babak Alipanahi, Andrew Delong, Matthew T. Weirauch, Brendan J. Frey.  
*Nature Biotechnology, July 2015.*  
[[10.1038/nbt.3300](https://doi.org/10.1038/nbt.3300)]

**Protein-protein docking using learned three-dimensional representations.**  
Georgy Derevyanko, Guillaume Lamoureux.  
*Preprint, March 2017.*  
[[10.1101/738690](https://doi.org/10.1101/738690)][[bioRxiv](https://www.biorxiv.org/content/10.1101/738690v2)]


### Other supervised learning

**ProtTox: Toxin identification from Protein Sequences.**  
Sathappan Muthiah, Debanjan Datta, Mohammad Raihanul Islam, Patrick Butler, Andrew Warren, Naren Ramakrishnan.  
*Preprint, April 2020.*  
[[10.1101/2020.04.18.048439](https://doi.org/10.1101/2020.04.18.048439)]

**Predicting the Viability of Beta-Lactamase: How Folding and Binding Free Energies Correlate with Beta-Lactamase Fitness.**  
Jordan Yang, Nandita Naik, Jagdish Suresh Patel, Christopher S. Wylie, Wenze Gu, Jessie Huang, Marty Ytreberg, Mandar T. Naik, Daniel M. Weinreich, Brenda M. Rubenstein.  
*Preprint, April 2020.*  
[[10.1101/2020.04.15.043661](https://doi.org/10.1101/2020.04.15.043661)]

**Classifying protein structures into folds by convolutional neural networks, distance maps, and persistent homology.**  
Yechan Hong, Yongyu Deng, Haofan Cui, Jan Segert, Jianlin Cheng.  
*Preprint, April 2020.*  
[[10.1101/2020.04.15.042739](https://doi.org/10.1101/2020.04.15.042739)]

**Minimum epistasis interpolation for sequence-function relationships.**  
Juannan Zhou, David M. McCandlish.  
*Nature Communications, April 2020.*  
[[10.7554/eLife.16965.024](https://doi.org/10.7554/eLife.16965.024)]

**Machine Learning to Identify Flexibility Signatures of Class A GPCR Inhibition.**  
Joseph Bemister-Buffington, Alex J. Wolf, Sebastian Raschka, Leslie A. Kuhn.  
*Biomolecules, March 2020.*  
[[10.3390/biom10030454](https://doi.org/10.3390/biom10030454)]

**Extraction of Protein Dynamics Information Hidden in Cryo-EM Map Using Deep Learning.**  
Shigeyuki Matsumoto, Shoichi Ishida, Mitsugu Araki, Takayuki Kato, Kei Terayama, Yasushi Okuno.  
*Preprint, February 2020.*  
[[10.1101/2020.02.17.951863](https://doi.org/10.1101/2020.02.17.951863)]

**Transformer neural network for protein specific de novo drug generation as machine translation problem.**  
Daria Grechishnikova.  
*Preprint, December 2019.*  
[[10.1101/863415](https://doi.org/10.1101/863415)]

**Iterative Peptide Modeling With Active Learning And Meta-Learning.**  
Rainier Barrett, Andrew D. White.  
*Preprint, November 2019.*  
[[arxiv](https://arxiv.org/abs/1911.09103)]

**Deep convolutional neural network and attention mechanism based pan-specific model for interpretable MHC-I peptide binding prediction.**  
Jing Jin, Zhonghao Liu, Alireza Nasiri, Yuxin Cui, Stephen Louis, Ansi Zhang, Yong Zhao, Jianjun Hu.  
*Preprint, November 2019.*  
[[10.1101/830737](https://doi.org/10.1101/830737)]

**BCrystal: an interpretable sequence-based protein crystallization predictor.**  
Abdurrahman Elbasir, Raghvendra Mall, Khalid Kunji, Reda Rawi, Zeyaul Islam, Gwo-Yu Chuang, Prasanna R Kolatkar, Halima Bensmail. 
*Bioinformatics, October 2019.*  
[[10.1093/bioinformatics/btz762](https://doi.org/10.1093/bioinformatics/btz762)]

**Deep learning regression model for antimicrobial peptide design.**  
Jacob Witten, Zack Witten.  
*Preprint, July 2019.*  
[[doi.org/10.1101/692681](https://doi.org/10.1101/692681)] [[bioRxiv](https://www.biorxiv.org/content/10.1101/692681v1)]

**Using machine learning to predict organismal growth temperatures from protein primary sequences.**  
David B. Sauer, Da-Neng Wang.  
*Preprint, June 2019.*  
[[10.1101/677328](https://doi.org/10.1101/677328)] [[bioRxiv](https://www.biorxiv.org/content/10.1101/677328v1?rss=1)]

**SolXplain: An Explainable Sequence-Based Protein Solubility Predictor.**  
Raghvendra Mall.  
*Preprint, May 2019.*  
[[10.1101/651067](https://doi.org/10.1101/651067)] [[bioRxiv](https://www.biorxiv.org/content/10.1101/651067v1)]

**High precision protein functional site detection using 3D convolutional neural networks.**  
Wen Torng, Russ B Altman.  
*Bioinformatics, May 2019.*  
[[10.1093/bioinformatics/bty813](https://doi.org/10.1093/bioinformatics/bty813)]

**Develop machine learning-based regression predictive models for engineering protein solubility.**  
Xi Han, Xiaonan Wang, Kang Zhou.  
*Bioinformatics, April 2019.*  
[[10.1093/bioinformatics/btz294](https://doi.org/10.1093/bioinformatics/btz294)]

**DeepCrystal: a deep learning framework for sequence-based protein crystallization prediction.**  
Abdurrahman Elbasir, Balasubramanian Moovarkumudalvan, Khalid Kunji, Prasanna R Kolatkar, Raghvendra Mall, Halima Bensmail.  
*Bioinformatics, November 2018.*  
[[10.1093/bioinformatics/bty953](https://doi.org/10.1093/bioinformatics/bty953)]

**DeepSol: a deep learning framework for sequence-based protein solubility prediction.**  
Sameer Khurana, Reda Rawi, Khalid Kunji, Gwo-Yu Chuang, Halima Bensmail, Raghvendra Mall.  
*Bioinformatics, March 2018.*   
[[10.1093/bioinformatics/bty166](https://doi.org/10.1093/bioinformatics/bty166)]

**A statistical model for improved membrane protein expression using sequence-derived features.**  
Shyam M. Saladi, Nauman Javed, Axel Müller, William M. Clemons, Jr.  
*Journal of Biological Chemistry, March 2018.*  
[[10.1074/jbc.RA117.001052](https://doi.org/10.1074/jbc.RA117.001052)]

**Learning epistatic interactions from sequence-activity data to predict enantioselectivity.**  
Julian Zaugg, Yosephine Gumulya, Alpeshkumar K. Malde, Mikael Bodén.  
*Journal of Computer Aided Molecular Design, December 2017.*  
[[10.1007/s10822-017-0090-x](https://doi.org/10.1007/s10822-017-0090-x)]

**Quantitative Missense Variant Effect Prediction Using Large-Scale Mutagenesis Data.**  
Vanessa E. Gray, Ronald J. Hause, Jens Luebeck, Jay Shendure, Douglas M. Fowler.  
*Cell Systems, December 2017.*  
[[10.1016/j.cels.2017.11.003](https://doi.org/10.1016/j.cels.2017.11.003)]

**DeepLoc: prediction of protein subcellular localization using deep learning.**  
Jose Juan Almagro Armenteros, Casper Kaae Sønderby, Søren Kaae Sønderby, Henrik Nielsen, Ole Winther.  
*Bioinformatics, September 2017.*  
[[10.1093/bioinformatics/btx548](https://doi.org/10.1093/bioinformatics/btx548)]

**Semisupervised Gaussian Process for Automated Enzyme Search.**  
Joseph Mellor, Ioana Grigoras, Pablo Carbonell, and Jean-Loup Faulon.  
*ACS Synthetic Biology, March 2016.*  
[[10.1021/acssynbio.5b00294](https://doi.org/10.1021/acssynbio.5b00294)]

**High Precision Prediction of Functional Sites in Protein Structures.**  
Ljubomir Buturovic, Mike Wong, Grace W. Tang, Russ B. Altman, Dragutin Petkovic.  
*PLOS One, March 2014.*  
[[10.1371/journal.pone.0091240](https://doi.org/10.1371/journal.pone.0091240)]

**Sequence Motifs in MADS Transcription Factors Responsible for Specificity and Diversification of Protein-Protein Interaction.**   
Aalt D. J. van Dijk, Giuseppa Morabito, Martijn Fiers, Roeland C. H. J. van Ham, Gerco C. Angenent, Richard G. H. Immink.  
*PLOS Computational Biology, November 2010.*  
[[10.1371/journal.pcbi.1001017](https://doi.org/10.1371/journal.pcbi.1001017)]

**Predicting and understanding transcription factor interactions based on sequence level determinants of combinatorial control.**  
A.D.J. van Dijk, C.J.F. ter Braak, R.G. Immink, G.C. Angenent, R.C.H.J. van Ham.  
*Bioinformatics, January 2008.*  
[[10.1093/bioinformatics/btm539](https://doi.org/10.1093/bioinformatics/btm539)]

**Deep convolutional networks for quality assessment of protein folds.**   
Georgy Derevyanko, Sergei Grudinin, Yoshua Bengio, Guillaume Lamoureux.   
*Bioinformatics, December 2018.*   
[[10.1093/bioinformatics/bty494](https://doi.org/10.1093/bioinformatics/bty494)][[ArXiv](https://arxiv.org/abs/1801.06252)]
