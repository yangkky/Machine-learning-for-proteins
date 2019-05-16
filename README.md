## Papers on machine learning for proteins

### Background

We recently released a [review](https://arxiv.org/abs/1811.10775) of machine learning methods in protein engineering, but the field changes so fast and there are so many new papers that any static document will inevitably be missing important work. We hope that this will be a useful resource for people interested in the field. 

To the best of our knowledge, this is the first public, collaborative list of machine learning papers on protein applications. We try to classify papers based on a combination of their applications and model type. If you have suggestions for other papers or categories, please make a pull request or issue!

### Format

Within each category, papers are listed in reverse chronological order (newest first). Where possible, a link should be provided. 

### Categories

[Reviews](#reviews)  
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

**Machine learning-guided directed evolution for protein engineering.**  
Kevin K. Yang, Zachary Wu, Frances H. Arnold.   
*Preprint, April 2019.*   
[[arxiv](https://arxiv.org/abs/1811.10775)]

### Machine-learning guided directed evolution

**Batched Stochastic Bayesian Optimization via Combinatorial Constraints Design**.   
Kevin K. Yang, Yuxin Chen, Alycia Lee, Yisong Yue.   
*International Conference on Artificial Intelligence and Statistics (AISTATS), April 2019.*  
[[arxiv](https://arxiv.org/abs/1904.08102)] [[PMLR](http://proceedings.mlr.press/v89/yang19c.html)]

**Machine learning-assisted directed protein evolution with combinatorial libraries.**  
Zachary Wu, S. B. Jennifer Kan, Russell D. Lewis, Bruce J. Wittmann, Frances H. Arnold.  
*PNAS, April 2019.*  
[[10.1073/pnas.1901979116](https://doi.org/10.1073/pnas.1901979116)]

**Machine learning-guided channelrhodopsin engineering enables minimally-invasive optogenetics.**  
Claire N. Bedbrook, Kevin K. Yang, J. Elliott Robinson, Viviana Gradinaru, Frances H .Arnold.  
*Preprint, March 2019.*  
[[10.1101/565606](https://doi.org/10.1101/565606)] [[bioRxiv](https://www.biorxiv.org/content/10.1101/565606v1)]

**Machine-Learning-Guided Mutagenesis for Directed Evolution of Fluorescent Proteins.**  
Yutaka Saito, Misaki Oikawa, Hikaru Nakazawa, Teppei Niide, Tomoshi Kameda, Koji Tsuda, and Mitsuo Umetsu.  
*ACS Synthetic Biology, August 2018.*  
[[10.1021/acssynbio.8b00155](https://doi.org/10.1021/acssynbio.8b00155)]

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

**Leveraging implicit knowledge in neural networks for functional dissection and engineering of proteins.**  
Julius Upmeier zu Belzen, Thore Bürgel, Stefan Holderbach, Felix Bubeck, Lukas Adam, Catharina Gandor, Marita Klein, Jan Mathony, Pauline Pfuderer, Lukas Platz, Moritz Przybilla, Max Schwendemann, Daniel Heid, Mareike Daniela Hoffmann, Michael Jendrusch, Carolin Schmelas, Max Waldhauer, Irina Lehmann, Dominik Niopek, Roland Eils.  
*Nature Machine Intelligence, May 2019.*  
[[Nature Machine Intelligence](https://www.nature.com/articles/s42256-019-0049-9)]

**Predicting Protein Binding Affinity With Word Embeddings and Recurrent Neural Networks.**  
Carlo Mazzaferro.  
*Preprint, April 2017.*  
[[10.1101/128223](https://doi.org/10.1101/128223)] [[bioRxiv](https://www.biorxiv.org/node/37703.abstract)]

**ProFET: Feature engineering captures high-level protein functions.**. 
Dan Ofer, Michal Linial.  
*Bioinformatics, June 2015.*  
[[10.1093/bioinformatics/btv345](https://doi.org/10.1093/bioinformatics/btv345)]

**AAindex: amino acid index database, progress report 2008.**  
Shuichi Kawashima, Piotr Pokarowski, Maria Pokarowska, Andrzej Kolinski, Toshiaki Katayama, Minoru Kanehisa.  
*Nucleic Acids Research, January 2008.*  
[[10.1093/nar/gkm998](https://doi.org/10.1093/nar/gkm998)]

### Unsupervised variant prediction

### Generative models

### Predicting stability

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

**Protein Secondary Structure Prediction with Long Short Term Memory Networks.**. 
Søren Kaae Sønderby, Ole Winther.
*Preprint, December 2014.*  
[[arxiv](https://arxiv.org/abs/1412.7828)]

### Predicting sequence from structure

### Classification and annotation

**DeepGO: predicting protein functions from sequence and interactions using a deep ontology-aware classifier.**  
Maxat Kulmanov, Mohammed Asif Khan, Robert Hoehndorf.  
*Bioinformatics, February 2018.*  
[[Bioinformatics](https://doi.org/10.1093/bioinformatics/btx624)]

**Near perfect protein multi-label classification with deep neural networks.**  Balázs Szalkaia, Vince Grolmuszab.  
*Methods, January 2018.*  
[[10.1016/j.ymeth.2017.06.034](https://doi.org/10.1016/j.ymeth.2017.06.034)]

**ProLanGO: Protein Function Prediction Using Neural Machine Translation Based on a Recurrent Neural Network.**  
Renzhi Cao, Colton Freitas, Leong Chan, Miao Sun, Haiqing Jiang, Zhangxin Chen.  
*Molecules, October 2017.*. 
[[10.3390/molecules22101732](https://doi.org/10.3390/molecules22101732)]

**The spectrum kernel: A string kernel for SVM protein classification.**  
Christina S Leslie, Eleazar Eskin, William Stafford Noble.  
*Pacific Symposium on Biocomputing, January 2002.*  
[[pdf](http://psb.stanford.edu/psb-online/proceedings/psb02/leslie.pdf)]

### Predicting interactions with other molecules

**Simple tricks of convolutional neural network architectures improve DNA–protein binding prediction.**  
Zhen Cao, Shihua Zhang.  
*Bioinformatics, October 2018.*  
[[10.1093/bioinformatics/bty893](https://doi.org/10.1093/bioinformatics/bty893)

**MHCflurry: Open-Source Class I MHC Binding Affinity Prediction.** . 
Timothy J. O'Donnell, Alex Rubinsteyn, Maria Bonsack, Angelika B. Riemer, Uri Laserson, Jeff Hammerbacher.  
*Cell Systems, June 2018.*  
[[10.1016/j.cels.2018.05.014](https://doi.org/10.1016/j.cels.2018.05.014)]

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

### Other supervised learning

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

**DeepLoc: prediction of protein subcellular localization using deep learning.**  
Jose Juan Almagro Armenteros, Casper Kaae Sønderby, Søren Kaae Sønderby, Henrik Nielsen, Ole Winther.  
*Bioinformatics, September 2017.*  
[[10.1093/bioinformatics/btx548](https://doi.org/10.1093/bioinformatics/btx548)]

**Semisupervised Gaussian Process for Automated Enzyme Search.**  
Joseph Mellor, Ioana Grigoras, Pablo Carbonell, and Jean-Loup Faulon.  
*ACS Synthetic Biology, March 2016.*  
[[10.1021/acssynbio.5b00294](https://doi.org/10.1021/acssynbio.5b00294)]

