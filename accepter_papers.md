# Accepted Papers

**Not All Lotteries Are Made Equal**
<br />Surya Kant Sahu; Sai Mitheran J; Somya Suhans Mahapatra<br />
<abstract>The Lottery Ticket Hypothesis (LTH) states that for a reasonably sized neural network, a sub-network within the same network yields no less performance than the dense counterpart when trained from the same initialization. This work investigates the relation between model size and the ease of finding these sparse sub-networks. We show through experiments that, surprisingly, under a finite budget, smaller models benefit more from Ticket Search (TS).</abstract>

[PDF](https://www.dropbox.com/s/fe0f5pfqrq6z3o3/camera_ready.pdf?dl=0) &bull;
[Poster](https://www.dropbox.com/s/zwm371y78l5dbwc/poster.pdf?dl=0) &bull;
[Presentation](https://youtu.be/11y9YWItLe8)



**Revisiting Architecture-aware Knowledge Distillation: Smaller Models and Faster Search**
<br />Taehyeon Aaron Kim; Heesoo Myeong; Se-Young Yun<br />
<abstract>Knowledge Distillation (KD) has recently emerged as a popular method for compressing neural networks. In recent studies, generalized distillation methods that find parameters and architectures of student models at the same time have been proposed. Still, this search method requires a lot of computation to search for architectures and has the disadvantage of considering only convolutional blocks in their search space. This paper introduces a new algorithm, coined as Trust Region Aware architecture search to Distill knowledge Effectively (TRADE), that rapidly finds effective student architectures from several state-of-the-art architectures using trust region Bayesian optimization approach. Experimental results show our proposed TRADE algorithm consistently outperforms both the conventional NAS approach and pre-defined architecture under KD training.</abstract>

[PDF](https://www.dropbox.com/s/rla5xmynatfs40n/paper_with_supplementary.pdf?dl=0) &bull;
[Poster](https://www.dropbox.com/s/8yre3obd3wif2hu/haetworkshop_akd_trade_poster.pdf?dl=0) &bull;
[Presentation](https://youtu.be/uBUPs09Yi80)



**Efficient Fine-Tuning of Compressed Language Models with Learners**
<br />Danilo Vucetic; Mohammadreza Tayaranian; Maryam Ziaeefard; James J. Clark; Brett H Meyer; Warren Gross<br />
<abstract>Fine-tuning BERT-based models is resource-intensive in memory, computation, and time. While many prior works aim to improve inference efficiency via compression techniques, e.g., pruning, these works do not explicitly address the computational challenges of training to downstream tasks. We introduce the Learner module, a novel method for fine-tuning that exploits the overparameterization of pre-trained language models to gain benefits in convergence speed and resource utilization. Learner modules navigate the double bind of 1) training efficiently by fine-tuning a subset of parameters, and 2) training effectively by ensuring quick convergence and high metric scores. Our results on DistilBERT demonstrate that learners perform on par with or surpass the baselines. Learners train 7x fewer parameters than state-of-the-art methods on GLUE. On CoLA, learners fine-tune 20% faster, and have significantly lower resource utilization.</abstract>


**Cut Inner Layers: A Structured Pruning Strategy for Efficient U-Net GANs**
<br />Bo-Kyeong Kim; Shinkook Choi; Hancheol Park<br />
<abstract>Pruning effectively compresses overparameterized models. Despite the success of pruning methods for discriminative models, applying them for generative models has been relatively rarely approached. This study conducts structured pruning on U-Net generators of conditional GANs. A per-layer sensitivity analysis confirms that many unnecessary filters exist in the innermost layers near the bottleneck and can be substantially pruned. Based on this observation, we prune these filters from multiple inner layers or suggest alternative architectures by completely eliminating the layers. We evaluate our approach with Pix2Pix for image-to-image translation and Wav2Lip for speech-driven talking face generation. Our method outperforms global pruning baselines, demonstrating the importance of properly considering where to prune for U-Net generators.</abstract>

[PDF](https://www.dropbox.com/s/1iwwqkj1kepkj89/paper.pdf?dl=0) &bull;
[Poster](https://www.dropbox.com/s/hsuaqarvem9qsgc/poster.pdf?dl=0) &bull;
[Presentation](https://youtu.be/YmNvwBGTeEk)



**A 28nm 8-bit Floating-Point CNN Training Processor with Hardware-Efficient Dynamic Sparsification and 4.7X Training Speedup**
<br />Shreyas Kolala Venkataramanaiah; Jian Meng; Han-Sok Suh; Injune Yeo; Jyotishman Saikia; Sai Kiran Cherupally; Yichi Zhang; Zhiru Zhang; Jae-sun Seo<br />
<abstract>We present an 8-bit floating-point (FP8) training processor which implements (1) highly parallel tensor cores that maintain high utilization throughout forward propagation (FP), backward propagation (BP), and weight update (WU) phases of the training process, (2) hardware-efficient channel gating for dynamic output activation sparsity, (3) dynamic weight sparsity based on group Lasso, and (4) gradient skipping based on FP prediction error. We develop a custom ISA to flexibly support different CNN topologies and training parameters. The 28nm prototype chip demonstrates large improvements in FLOPs reduction (7.3X), energy efficiency (16.4 TFLOPS/W), and overall training latency speedup (4.7X), for both supervised and self-supervised training tasks.</abstract>

[PDF](https://www.dropbox.com/s/bmibx0za2r48u10/HAET_2022_Sparse_Training_paper_final.pdf?dl=0) &bull;
[Poster](https://www.dropbox.com/s/hu6t5qui9ry4qzk/HAET_2022_Sparse_Training_poster.pdf?dl=0) &bull;
[Presentation](https://youtu.be/1CFBOfJsOKA)



**MobileTL: On-device Transfer Learning with Inverted Residual Blocks**
<br />Hung-Yueh Chiang; Natalia Frumkin; Feng Liang; Diana Marculescu<br />
<abstract>We present MobileTL, a memory and computationally efficient on-device transfer learning method for models built with Inverted Residual blocks (IRBs). An IRB splits a full convolution into depthwise and pointwise convolutions, leading to more stacking layers. Though they are efficient for inference, IRBs require additional activation maps stored in memory during back-propagation. To address this issue, MobileTL only updates the bias for internal normalization layers to avoid storing activation maps. Additionally, MobileTL approximates memory-intensive activation layers (e.g., Hard-Swish and ReLU6) as a signed function thereby enabling the use of a binary mask during the backward pass. MobileTL only fine-tunes a few high-level task-specific blocks to reduce the computation cost rather than propagating the gradient through the whole network. Our method reduces training memory usage by 46 % and 53 % for MobileNetV2 and V3 IRBs respectively. For MobileNetV3, we find a 36 % reduction of the floating-point operations when fine-tuning 5 blocks, while only incurring a 0.6 % accuracy reduction in CIFAR10. Extensive experiments on multiple datasets illustrate that our method is Pareto-optimal under given hardware constraints when compared to prior work. Code will be available at: https://github.com/enyac-group.</abstract>

[PDF](https://www.dropbox.com/s/f8f47iydljgjc8t/ICML2022W_HAET_camera_ready.pdf?dl=0) &bull;
[Poster](https://www.dropbox.com/s/5tc98gf4aggqfju/ICML2022_HAET_MobileTL_Poster.pdf?dl=0) &bull;
[Presentation](https://youtu.be/L9Op0RuBmQM)





**Low-Bit DNN Training with Hardware-Efficient Stochastic Rounding Unit Design**
<br />Sung-En Chang; Geng Yuan; Alec Lu; Mengshu Sun; Yanyu Li; Xiaolong Ma; Yanyue Xie; Minghai Qin; Xue Lin; Zhenman Fang; Yanzhi Wang<br />
<abstract>Stochastic rounding is crucial in the training of low-bit deep neural networks (DNNs) to achieve high accuracy. Unfortunately, prior studies require a large number of high-precision stochastic rounding units (SRUs) to guarantee the low-bit DNN accuracy, which involves considerable hardware overhead. In this paper, we propose an automated framework to explore hardware-efficient low-bit SRUs (ESRUs) that can still generate high-quality random numbers to guarantee the accuracy of low-bit DNN training. Experimental results using state-of-the-art DNN models demonstrate that, compared to the prior 24-bit SRU with 24-bit pseudo random number generator (PRNG), our 8-bit ESRU~with 3-bit PRNG reduces the SRU resource usage by $9.75\times$ while achieving a higher accuracy.</abstract>


[Presentation](https://youtu.be/BFjd4z3j-3s)


**Investigating the Not-So-Obvious Effects of Structured Pruning**
<br />Hugo Tessier; Vincent Gripon; Mathieu Léonardon; matthieu Arzel; David Bertrand; Thomas Hannagan<br />
<abstract>Structured pruning is a popular method to reduce the cost of convolutional neural networks. However, depending on the architecture, pruning introduces dimensional discrepancies which prevent the actual reduction of pruned networks and mask their true complexity. Most papers in the literature overlook these issues. We propose a method that systematically solves them and generate an operational network. We show through experiments the gap between the theoretical pruning ratio and the actual complexity revealed by our method.</abstract>

[Poster](https://www.dropbox.com/s/12sashs4hngtfvp/Poster_ICML.pdf?dl=0) &bull;
[Presentation](https://youtu.be/Ru9GtII3kfI)


**OSDP: Optimal Sharded Data Parallel for Distributed Deep Learning**
<br />Youhe Jiang; Xupeng Miao; Xiaonan Nie; Bin Cui<br />
<abstract>Large-scale deep learning models contribute to significant performance improvements on varieties of downstream tasks. Current data and model parallelism approaches utilize model replication and partition techniques to support the distributed training of ultra-large models. However, directly deploying these systems often leads to sub-optimal training efficiency due to the complex model architectures and the strict device memory constraints. In this paper, we propose Optimal Sharded Data Parallel (OSDP), an automated parallel training system that combines the advantages from both data and model parallelism. Given the model description and the device information, OSDP makes trade-offs between the memory consumption and the hardware utilization, thus automatically generates the distributed computation graph and maximizes the overall system throughput. In addition, OSDP introduces operator splitting to further alleviate peak memory footprints during training with negligible overheads, which enables the trainability of larger models as well as the higher throughput. Extensive experimental results of OSDP on multiple different kinds of large-scale models demonstrate that the proposed strategy outperforms the state-of-the-art in multiple regards. Our code is available at https://anonymous.4open.science/r/OptimalShardedDataParallel-751F.</abstract>

[PDF](https://www.dropbox.com/s/07lpaf4pdf7pza0/ICML_Workshop_Camera-ready.pdf?dl=0) &bull;
[Poster](https://www.dropbox.com/s/fydcjezzcflv0zg/ICML_Workshop_Poster_A0.pdf?dl=0) &bull;
[Presentation](https://youtu.be/il66cvILZ2U)


**Studying the impact of magnitude pruning on contrastive learning methods**
<br />Francesco Corti; Rahim Entezari; Sara Hooker; Davide Bacciu; Olga Saukh<br />
<abstract>We study the impact of different versions of magnitude pruning on the representation learned by deep models trained with supervised and supervised contrastive learning methods. We discover that at high sparsity contrastive learning results in a higher number of misclassified examples than if the models are trained with supervised learning. We use the number of PIEs (Hooker et al., 2019), Q Score (Kalibhat et al., 2022), and PD- Score (Baldock et al., 2021) metrics to understand the impact of pruning on the learned representation quality. Our analysis suggests that popular pruning methods are oblivious to representation learning: misclassified examples are largely unique for a combination of learning and pruning methods. The negative impact of sparsity on the quality of the learned representation is the highest early on in the training phase.</abstract>

[PDF](https://www.dropbox.com/s/3omxq9b9kaiigry/Studying%20the%20impact%20of%20magnitude%20pruning%20on%20contrastive%20learning%20methods.pdf?dl=0) &bull;
