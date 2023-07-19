# AI4Bio-Reading-List

This is an AI for Biology reading list maintained by the MBZUAI AI4Bio Group.

**Contents:**
- [1. Protein Level](#1-protein-level)
  * [1.1 Protein Structure Prediction](#11-protein-structure-prediction)
  * [1.2 Protein Function Prediction](#12-protein-function-prediction)
  * [1.3 Protein Design](#13-protein-design)
- [2. Protein Interaction Level](#2-protein-interaction-level)
- [3. Cell Level](#3-cell-level)
  * [3.1 Cell Type Annotation](#31-cell-type-annotation)
  * [3.2 Perturbation Modeling](#32-perturbation-modeling)
- [4. Others](#4-others)

Note: For applications of diffusion methods in protein science, check [Diffusion reading list](https://github.com/MBZUAI/AI4Bio-Reading-List/blob/main/Diffusion%20reading%20list.md).


## 1. Protein Level


### 1.1 Protein Structure Prediction

* **Highly accurate protein structure prediction with AlphaFold.** Nature. 2021. Jumper, J., Evans, R., Pritzel, A., Green, T., Figurnov, M., Ronneberger, O., ... & Hassabis, D. [[Paper](https://www.nature.com/articles/s41586-021-03819-2)] 
[[Slides](https://github.com/MBZUAI/AI4Bio-Reading-List/blob/main/Presentation%20slides/20221117%20Pre%20-%20Highly%20accurate%20protein%20structure%20prediction%20with%20AlphaFold.pdf)]

* **Accurate prediction of protein structures and interactions using a three-track neural network.** Science. 2021. Baek, M., DiMaio, F., Anishchenko, I., Dauparas, J., Ovchinnikov, S., Lee, G. R., ... & Baker, D. [[Paper](https://www.science.org/doi/abs/10.1126/science.abj8754)]

* **ColabFold: making protein folding accessible to all].** *Nature Methods*. 2022. Mirdita, M., Schütze, K., Moriwaki, Y., Heo, L., Ovchinnikov, S., & Steinegger, M. [[Paper](https://www.nature.com/articles/s41592-022-01488-1)]

* **Language models of protein sequences at the scale of evolution enable accurate structure prediction.** BioRxiv. 2022. Lin, Z., Akin, H., Rao, R., Hie, B., Zhu, Z., Lu, W., ... & Rives, A. [[Paper](https://www.biorxiv.org/content/10.1101/2022.07.20.500902v1.full.pdf)] [[Slides](https://github.com/MBZUAI/AI4Bio-Reading-List/blob/main/Presentation%20slides/20221201%20Pre%20-%20Language%20models%20of%20protein%20sequences%20at%20the%20scale%20of%20evolution%20enable%20accurate%20structure%20prediction.pdf)]

* **High-resolution de novo structure prediction from primary sequence.** BioRxiv. 2022. Wu, R., Ding, F., Wang, R., Shen, R., Zhang, X., Luo, S., ... & Peng, J. [[Paper](https://www.biorxiv.org/content/10.1101/2022.07.21.500999v1.full.pdf)] [[Slides](https://github.com/MBZUAI/AI4Bio-Reading-List/blob/main/Presentation%20slides/20221208%20Pre%20-%20HelixFold_OmegaFold_ESMFold.pdf)]

* **Helixfold-single: Msa-free protein structure prediction by using protein language model as an alternative.** ArXiv. 2022. Fang, X., Wang, F., Liu, L., He, J., Lin, D., Xiang, Y., ... & Song, L. [[Paper](https://arxiv.org/pdf/2207.13921.pdf)] [[Slides](https://github.com/MBZUAI/AI4Bio-Reading-List/blob/main/Presentation%20slides/20221208%20Pre%20-%20HelixFold_OmegaFold_ESMFold.pdf)]

[//]: <* [AmoebaContact and GDFold: a new pipeline for rapid prediction of protein structures](https://arxiv.org/pdf/1905.11640.pdf). *arXiv preprint arXiv:1905.11640*. Mao, W., Ding, W., & Gong, H. (2019).>

[//]: <* [Improved fragment sampling for ab initio protein structure prediction using deep neural networks](https://www.nature.com/articles/s42256-019-0075-7). *Nature Machine Intelligence*. Wang, T., Qiao, Y., Ding, W., Mao, W., Zhou, Y., & Gong, H. (2019).>

[//]: <* [Improved protein structure prediction by deep learning irrespective of co-evolution information](https://www.nature.com/articles/s42256-021-00348-5). *Nature Machine Intelligence*. Xu, J., Mcpartlon, M., & Li, J. (2021).>



### 1.2 Protein Function Prediction

* **Biological structure and function emerge from scaling unsupervised learning to 250 million protein sequences.** PNAS. 2021. Rives, A., Meier, J., Sercu, T., Goyal, S., Lin, Z., Liu, J., ... & Fergus, R. [[Paper](https://www.pnas.org/doi/epdf/10.1073/pnas.2016239118)]

* **Leveraging implicit knowledge in neural networks for functional dissection and engineering of proteins.** Nature Machine Intelligence. 2019. Upmeier zu Belzen, J., Bürgel, T., Holderbach, S., Bubeck, F., Adam, L., Gandor, C., ... & Eils, R. [[Paper](https://www.nature.com/articles/s42256-019-0049-9)]

* **Protein function prediction is improved by creating synthetic feature samples with generative adversarial networks.** Nature Machine Intelligence. 2020. Wan, C., & Jones, D. T. [[Paper](https://www.nature.com/articles/s42256-020-0222-1)]

* **Protein function prediction for newly sequenced organisms.** Nature Machine Intelligence. 2021. Torres, M., Yang, H., Romero, A. E., & Paccanaro, A.   [[Paper](https://www.nature.com/articles/s42256-021-00419-7)]

* **Enzyme function prediction using contrastive learning.** Science. 2023. Yu, T., Cui, H., Li, J. C., Luo, Y., Jiang, G., & Zhao, H.    [[Paper](https://www.science.org/doi/10.1126/science.adf2465)] [[Slides](https://github.com/MBZUAI/AI4Bio-Reading-List/blob/main/Presentation%20slides/20230713%20Pre%20-%20Enzyme%20function%20prediction%20using%20contrastive%20learning.pdf
)]




### 1.3 Protein Design

* **Expanding functional protein sequence spaces using generative adversarial networks.** Nature Machine Intelligence. 2021. Repecka, D., Jauniskis, V., Karpus, L., Rembeza, E., Rokaitis, I., Zrimec, J., ... & Zelezniak, A. [[Paper](https://www.nature.com/articles/s42256-021-00310-5)]

* **Transformer-based protein generation with regularized latent space optimization.** Nature Machine Intelligence. 2022. Castro, E., Godavarthi, A., Rubinfien, J., Givechian, K., Bhaskar, D., & Krishnaswamy, S. [[Paper](https://www.nature.com/articles/s42256-022-00532-1)]

* **A high-level programming language for generative protein design.** bioRxiv. 2022-12. Hie, B., Candido, S., Lin, Z., Kabeli, O., Rao, R., Smetanin, N., ... & Rives, A. [[Paper](https://www.biorxiv.org/content/10.1101/2022.12.21.521526v1.abstract)] [[Slides](https://github.com/MBZUAI/AI4Bio-Reading-List/blob/main/Presentation%20slides/20230112%20Pre%20-%20A%20high-level%20programming%20language%20for%20generative%20protein%20design.pdf)]

* **A universal deep-learning model for zinc finger design enables transcription factor reprogramming.** Nature Biotechnology. 2023. Ichikawa, D. M., Abdin, O., Alerasool, N., Kogenaru, M., Mueller, A. L., Wen, H., ... & Noyes, M. B. [[Paper](https://www.nature.com/articles/s41587-022-01624-4)] [[Slides](https://github.com/MBZUAI/AI4Bio-Reading-List/blob/main/Presentation%20slides/20230316%20Pre%20-%20A%20universal%20deep-learning%20model%20for%20zinc%20finger%20design%20enables%20transcription%20factor%20reprogramming.pdf)]





## 2. Protein Interaction Level

* **Predicting drug–protein interaction using quasi-visual question answering system.** Nature Machine Intelligence. 2020. Zheng, S., Li, Y., Chen, S., Xu, J., & Yang, Y. (2020). [[Paper](https://www.nature.com/articles/s42256-020-0152-y)]

* **A topology-based network tree for the prediction of protein–protein binding affinity changes following mutation.** Nature Machine Intelligence. 2020. Wang, M., Cang, Z., & Wei, G. W. [[Paper](https://www.nature.com/articles/s42256-020-0149-6)]

* **Computed structures of core eukaryotic protein complexes.** Science. 2021. Humphreys, I. R., Pei, J., Baek, M., Krishnakumar, A., Anishchenko, I., Ovchinnikov, S., ... & Baker, D. [[Paper](https://www.science.org/doi/full/10.1126/science.abm4805)]

* **Harnessing protein folding neural networks for peptide–protein docking.** Nature communications. 2022. Tsaban, T., Varga, J. K., Avraham, O., Ben-Aharon, Z., Khramushin, A., & Schueler-Furman, O. [[Paper](https://www.nature.com/articles/s41467-021-27838-9)]

* **Protein complex prediction with AlphaFold-Multimer.** BioRxiv. 2022. Evans, R., O’Neill, M., Pritzel, A., Antropova, N., Senior, A., Green, T., ... & Hassabis, D. [[Paper](https://www.biorxiv.org/content/10.1101/2021.10.04.463034v2.full.pdf)]

* **Improved prediction of protein-protein interactions using AlphaFold2.** Nature communications. 2022. Bryant, P., Pozzati, G., & Elofsson, A. [[Paper](https://www.nature.com/articles/s41467-022-28865-w)]

* **AF2Complex predicts direct physical interactions in multimeric proteins with deep learning.** Nature communications. 2022. Gao, M., Nakajima An, D., Parks, J. M., & Skolnick, J. [[Paper](https://www.nature.com/articles/s41467-022-29394-2)]

* **Uni-Fold Symmetry: harnessing symmetry in folding large protein complexes.** bioRxiv. 2022. Li, Z., Yang, S., Liu, X., Chen, W., Wen, H., Shen, F., ... & Zhang, L. [[Paper](https://www.biorxiv.org/content/10.1101/2022.08.30.505833v1.abstract)]

* **Predicting the structure of large protein complexes using AlphaFold and Monte Carlo tree search.** Nature Communications. 2022. Bryant, P., Pozzati, G., Zhu, W., Shenoy, A., Kundrotas, P., & Elofsson, A. [[Paper](https://www.nature.com/articles/s41467-022-33729-4)]

* **Improve the Protein Complex Prediction with Protein Language Models.** bioRxiv. 2022. Chen, B., Xie, Z., Xu, J., Qiu, J., Ye, Z., & Tang, J. [[Paper](https://www.biorxiv.org/content/10.1101/2022.09.15.508065v2.abstract)]





## 3. Cell Level

### 3.1 Cell Type Annotation


* **Clustering single-cell RNA-seq data with a model-based deep learning approach.** Nature Machine Intelligence. 2019. Tian, T., Wan, J., Song, Q., & Wei, Z. [[Paper](https://www.nature.com/articles/s42256-019-0037-0)]

* **An interpretable deep-learning architecture of capsule networks for identifying cell-type gene expression programs from single-cell RNA-sequencing data.** Nature Machine Intelligence. 2020. Wang, L., Nie, R., Yu, Z., Xin, R., Zheng, C., Zhang, Z., ... & Cai, J. [[Paper](https://www.nature.com/articles/s42256-020-00244-4)]

* **Iterative transfer learning with neural network for clustering and cell type classification in single-cell RNA-seq analysis.** Nature Machine Intelligence. 2020. Hu, J., Li, X., Hu, G., Lyu, Y., Susztak, K., & Li, M. [[Paper](https://www.nature.com/articles/s42256-020-00233-7)]

* **Simultaneous deep generative modelling and clustering of single-cell genomic data.** Nature Machine Intelligence. 2021. Liu, Q., Chen, S., Jiang, R., & Wong, W. H. (2021). [[Paper](https://www.nature.com/articles/s42256-021-00333-y)]

* **scBERT as a large-scale pretrained deep language model for cell type annotation of single-cell RNA-seq data**. Nature Machine Intelligence. 2022. Yang, F., Wang, W., Wang, F., Fang, Y., Tang, D., Huang, J., ... & Yao, J. [[Paper](https://www.nature.com/articles/s42256-022-00534-z#Sec2)] [[Slides](https://github.com/MBZUAI/AI4Bio-Reading-List/blob/main/Presentation%20slides/20221215%20Pre%20-%20scBERT%20as%20a%20large-scale%20pretrained%20deep%20language%20model%20for%20cell%20type%20annotation%20of%20single-cell%20RNA-seq%20data.pdf)]

* **A multi-use deep learning method for CITE-seq and single-cell RNA-seq data integration with cell surface protein prediction and imputation.** Nature Machine Intelligence. 2022. Lakkis, J., Schroeder, A., Su, K., Lee, M. Y., Bashore, A. C., Reilly, M. P., & Li, M. [[Paper](https://www.nature.com/articles/s42256-022-00545-w)]

* **Contrastive learning enables rapid mapping to multimodal single-cell atlas of multimillion scale.** Nature Machine Intelligence. 2022. Yang, M., Yang, Y., Xie, C., Ni, M., Liu, J., Yang, H., ... & Wang, J. [[Paper](https://www.nature.com/articles/s42256-022-00518-z)]

* **Interpreting the B-cell receptor repertoire with single-cell gene expression using Benisse.** Nature Machine Intelligence. 2022. Zhang, Z., Chang, W. Y., Wang, K., Yang, Y., Wang, X., Yao, C., ... & Wang, T. [[Paper](https://www.nature.com/articles/s42256-022-00492-6)]

* **Simultaneous dimensionality reduction and integration for single-cell ATAC-seq data using deep learning.** Nature Machine Intelligence. 2022. Kopp, W., Akalin, A., & Ohler, U. [[Paper](https://www.nature.com/articles/s42256-022-00443-1)]

* **Cell type annotation of single-cell chromatin accessibility data via supervised Bayesian embedding.** Nature Machine Intelligence. 2022. Chen, X., Chen, S., Song, S., Gao, Z., Hou, L., Zhang, X., ... & Jiang, R. [[Paper](https://www.nature.com/articles/s42256-021-00432-w)]

* **Deep learning of cross-species single-cell landscapes identifies conserved regulatory programs underlying cell types.** Nature Genetics. 2022. Li, Jiaqi, Jingjing Wang, Peijing Zhang, Renying Wang, Yuqing Mei, Zhongyi Sun, Lijiang Fei et al. [[Paper](https://www.nature.com/articles/s41588-022-01197-7)]


### 3.2 Perturbation Modeling

#### 3.2.1 Methods

* **GEARS: Predicting transcriptional outcomes of novel multi-gene perturbations.** BioRxiv. 2022. Roohani, Y., Huang, K., & Leskovec, J. [[Paper](https://www.biorxiv.org/content/10.1101/2022.07.12.499735v2)] [[Slides](https://github.com/MBZUAI/AI4Bio-Reading-List/blob/main/Presentation%20slides/20221215%20Pre%20-%20scBERT%20as%20a%20large-scale%20pretrained%20deep%20language%20model%20for%20cell%20type%20annotation%20of%20single-cell%20RNA-seq%20data.pdf)]

* **Effective gene expression prediction from sequence by integrating long-range interactions.** Nature methods. 2021. Avsec, Ž., Agarwal, V., Visentin, D., Ledsam, J. R., Grabska-Barwinska, A., Taylor, K. R., ... & Kelley, D. R. [[Paper](https://www.nature.com/articles/s41592-021-01252-x)] [[Slides](https://github.com/MBZUAI/AI4Bio-Reading-List/blob/main/Presentation%20slides/20230126%20Pre%20-%20Effective%20gene%20expression%20prediction%20from%20sequence%20by%20integrating%20long-range%20interactions.pdf)]

* **Compositional perturbation autoencoder for single-cell response modeling.** BioRxiv. 2021. Lotfollahi, M., Susmelj, A. K., Donno, C. D., Ji, Y., Ibarra, I. L., Wolf, F. A., Yakubova, N., Theis, F. J., & Lopez-Paz, D. [[Paper](https://www.biorxiv.org/content/10.1101/2021.04.14.439903v1)]

* **Predicting Cellular Responses to Novel Drug Perturbations at a Single-Cell Resolution.** ArXiv. 2022. Hetzel, L., Böhm, S., Kilbertus, N., Günnemann, S., Lotfollahi, M., & Theis, F. [[Paper](https://doi.org/10.48550/arXiv.2204.13545)]

* **MultiCPA: Multimodal Compositional Perturbation Autoencoder.** BioRxiv. 2022. Inecik, K., Uhlmann, A., Lotfollahi, M., & Theis, F. [[Paper](https://doi.org/10.1101/2022.07.08.499049)]

* **Machine learning for perturbational single-cell omics. Cell Systems.** Cell Systems. 2021. Ji, Y., Lotfollahi, M., Wolf, F. A., & Theis, F. J. [[Paper](https://doi.org/10.1016/j.cels.2021.05.016)]

* **Learning Single-Cell Perturbation Responses using Neural Optimal Transport.** BioRxiv. 2021. Bunne, C., Stark, S. G., Gut, G., Castillo, J. S. del, Lehmann, K.-V., Pelkmans, L., Krause, A., & Rätsch, G. [[Paper](https://doi.org/10.1101/2021.12.15.472775)]


#### 3.2.2 Data
* **scPerturb: Harmonized Single-Cell Perturbation Data.** bioRxiv. 2023. Peidli, S., Green, T. D., Shen, C., Gross, T., Min, J., Garda, S., Yuan, B., Schumacher, L. J., Taylor-King, J. P., Marks, D. S., Luna, A., Blüthgen, N., & Sander, C. [[Paper](https://doi.org/10.1101/2022.08.20.504663 )]

* **SERGIO: A Single-Cell Expression Simulator Guided by Gene Regulatory Networks.** 2020. Cell Systems. Dibaeinia, P., & Sinha, S. [[Paper](https://doi.org/10.1016/j.cels.2020.08.003)]



## 4. Others

* [Predicting disease-associated mutation of metal-binding sites in proteins using a deep learning approach](https://www.nature.com/articles/s42256-019-0119-z). *Nature Machine Intelligence*. Koohi-Moghadam, M., Wang, H., Wang, Y., Yang, X., Li, H., Wang, J., & Sun, H. (2019). 

* [Evaluation of deep learning in non-coding RNA classification](https://www.nature.com/articles/s42256-019-0051-2). *Nature Machine Intelligence*. Amin, N., McGrath, A., & Chen, Y. P. P. (2019).

* [Feedback GAN for DNA optimizes protein functions](https://www.nature.com/articles/s42256-019-0017-4). *Nature Machine Intelligence*. Gupta, A., & Zou, J. (2019). 

* [Gene set inference from single-cell sequencing data using a hybrid of matrix factorization and variational autoencoders](https://www.nature.com/articles/s42256-020-00269-9). *Nature Machine Intelligence*. Lukassen, S., Ten, F. W., Adam, L., Eils, R., & Conrad, C. (2020). 

* [Elucidation of DNA methylation on N6-adenine with deep learning](https://www.nature.com/articles/s42256-020-0211-4). *Nature Machine Intelligence*. Tan, F., Tian, T., Hou, X., Yu, X., Gu, L., Mafra, F., ... & Hakonarson, H. (2020).

* [Deep learning decodes the principles of differential gene expression](https://www.nature.com/articles/s42256-020-0201-6). *Nature Machine Intelligence*.Tasaki, S., Gaiteri, C., Mostafavi, S., & Wang, Y. (2020). 

* [Gaussian embedding for large-scale gene set analysis](https://www.nature.com/articles/s42256-020-0193-2). *Nature Machine Intelligence*. Wang, S., Flynn, E. R., & Altman, R. B. (2020).

* [Deep learning incorporating biologically inspired neural dynamics and in-memory computing](https://www.nature.com/articles/s42256-020-0187-0) *Nature Machine Intelligence*. Woźniak, S., Pantazi, A., Bohnstingl, T., & Eleftheriou, E. (2020). 

* [A novel machine learning framework for automated biomedical relation extraction from large-scale literature repositories](https://www.nature.com/articles/s42256-020-0189-y). *Nature Machine Intelligence*. Hong, L., Lin, J., Li, S., Wan, F., Yang, H., Jiang, T., ... & Zeng, J. (2020). 

* [A deep learning method for recovering missing signals in transcriptome-wide RNA structure profiles from probing experiments](https://www.nature.com/articles/s42256-021-00412-0). *Nature Machine Intelligence*. Gong, J., Xu, K., Ma, Z., Lu, Z. J., & Zhang, Q. C. (2021). 

* [Integration of multiomics data with graph convolutional networks to identify new cancer genes and their associated molecular mechanisms](https://www.nature.com/articles/s42256-021-00325-y). *Nature Machine Intelligence*. Schulte-Sasse, R., Budach, S., Hnisz, D., & Marsico, A. (2021).

* [An automated framework for efficiently designing deep convolutional neural networks in genomics](https://www.nature.com/articles/s42256-021-00316-z). *Nature Machine Intelligence*. Zhang, Z., Park, C. Y., Theesfeld, C. L., & Troyanskaya, O. G. (2021). 

* [Improving representations of genomic sequence motifs in convolutional networks with exponential activations](https://www.nature.com/articles/s42256-020-00291-x). *Nature Machine Intelligence*. Repecka, D., Jauniskis, V., Karpus, L., Rembeza, E., Rokaitis, I., Zrimec, J., ... & Zelezniak, A. (2021). 

* [Deep neural networks identify sequence context features predictive of transcription factor binding](https://www.nature.com/articles/s42256-020-00282-y). *Nature Machine Intelligence*. Zheng, A., Lamkin, M., Zhao, H., Wu, C., Su, H., & Gymrek, M. (2021).

* [Deep neural networks with controlled variable selection for the identification of putative causal genetic variants](https://www.nature.com/articles/s42256-022-00525-0). *Nature Machine Intelligence*. Kassani, P. H., Lu, F., Le Guen, Y., Belloy, M. E., & He, Z. (2022). 

* [Molecular convolutional neural networks with DNA regulatory circuits](https://www.nature.com/articles/s42256-022-00502-7). *Nature Machine Intelligence*. Xiong, X., Zhu, T., Zhu, Y., Cao, M., Xiao, J., Li, L., ... & Pei, H. (2022). 

* [Interpreting neural networks for biological sequences by learning stochastic masks](https://www.nature.com/articles/s42256-021-00428-6).*Nature Machine Intelligence*. Linder, J., La Fleur, A., Chen, Z., Ljubetič, A., Baker, D., Kannan, S., & Seelig, G. (2022).

* [Hierarchical deep reinforcement learning reveals a modular mechanism of cell movement](https://www.nature.com/articles/s42256-021-00431-x). *Nature Machine Intelligence*. Wang, Z., Xu, Y., Wang, D., Yang, J., & Bao, Z. (2022). 

* [Structure-guided isoform identification for the human transcriptome](https://doi.org/10.7554/eLife.82556). *ELife*. Sommer, M. J., Cha, S., Varabyou, A., Rincon, N., Park, S., Minkin, I., Pertea, M., Steinegger, M., & Salzberg, S. L. (2022). 


