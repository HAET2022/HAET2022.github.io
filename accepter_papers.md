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


**RevBiFPN The Fully Reversible Bidirectional Feature Pyramid Network**
<br />Vitaliy Chiley; Vithursan Thangarasa; Abhay Gupta; Anshul Samar; Joel T Hestness; Dennis DeCoste<br />
<abstract>This work introduces the RevSilo, the first reversible module for bidirectional multi-scale feature fusion. Like other reversible methods, RevSilo eliminates the need to store hidden activations by recomputing them. Existing reversible methods, however, do not apply to multi-scale feature fusion and are therefore not applicable to a large class of networks. Bidirectional multi-scale feature fusion promotes local and global coherence and has become a de facto design principle for networks targeting spatially sensitive tasks e.g. HRNet and EfficientDet. When paired with high-resolution inputs, these networks achieve state-of-the-art results across various computer vision tasks, but training them requires substantial accelerator memory for saving large, multi-resolution activations. These memory requirements cap network size and limit progress. Using reversible recomputation, the RevSilo alleviates memory issues while still operating across resolution scales. Stacking RevSilos, we create RevBiFPN, a fully reversible bidirectional feature pyramid network. For classification, RevBiFPN is competitive with networks such as EfficientNet while using up to 19.8x lesser training memory. When fine-tuned on COCO, RevBiFPN provides up to a 2.5% boost in AP over HRNet using fewer MACs and a 2.4x reduction in training-time memory.</abstract>

[PDF](https://www.dropbox.com/s/wrp8n9f8j2okrfv/RevBiFPN.pdf?dl=0) &bull;
[Poster](https://www.dropbox.com/s/5yxvnok33gl3x9w/3-revbifpn_heat_icml2022_poster.pdf?dl=0) &bull;
[Presentation](https://youtu.be/b_SQrw_dR6k)


**Rethinking Pareto Frontier for Performance Evaluation of Deep Neural Networks**
<br />Vahid Partovi Nia; Alireza Ghaffari; Mahdi Zolnouri; Yvon Savaria<br />
<abstract>Performance optimization of deep learning models is conducted either manually or through automatic architecture search, or a combination of both. On the other hand, their performance strongly depends on the target hardware and how successfully the models were trained. We propose to use a multi-dimensional Pareto frontier to re-define the efficiency measure of candidate deep learning models, where several variables such as training cost, inference latency, and accuracy play a relative role in defining a dominant model. Furthermore, a random version of the multi-dimensional Pareto frontier is introduced to mitigate the uncertainty of accuracy, latency, and throughput of deep learning models in different experimental setups. These two complementary methods can be combined to perform objective benchmarking of deep learning models. Our proposed method is applied to a wide range of deep image classification models trained on ImageNet data. Our method combines competing variables with stochastic nature in a single relative efficiency measure. This allows ranking deep learning models that run efficiently on different hardware, and combining inference efficiency with training efficiency objectively.</abstract>

[PDF](https://www.dropbox.com/s/a416og118p38m9l/Pareto_final-paper.pdf?dl=0) &bull;
[Poster](https://www.dropbox.com/s/2f1fl6hvvsufpc4/ICMLW_Pareto_poster.pdf?dl=0) &bull;


**GroupBERT: Enhanced Transformer Architecture with Efficient GroupedStructures**
<br />Ivan Chelombiev; Daniel Justus; Douglas Orr; Anastasia Dietrich; Frithjof Gressmann; Alexandros Koliousis; Carlo Luschi<br />
<abstract>Attention based language models have high computational requirements, due to large parameter count, dense operations and large volumes of data. We modify the structure of a Transformer layer by introducing grouped transformations to dense feed-forward layers and add a grouped convolution module. The resulting architecture shows superior computational and task performance compared to BERT model family, that translate to time and energy savings for model training.</abstract>


**Principal Component Networks: Parameter Reduction Early in Training**
<br />Roger Waleffe; Theodoros Rekatsinas<br />
<abstract>In this paper, we show that hidden layer activations in overparameterized neural networks for image classification exist primarily in subspaces smaller than the actual model width. We further show that these subspaces can be identified early in training. Based on these observations, we show how to efficiently find small networks that exhibit similar accuracy to their overparameterized counterparts after only a few training epochs. We term these network architectures Principal Component Networks (PCNs). We evaluate PCNs on CIFAR-10 and ImageNet for VGG and ResNet style architectures and find that PCNs consistently reduce parameter counts with little accuracy loss, thus providing the potential to reduce the computational costs of deep neural network training.</abstract>

[PDF](https://www.dropbox.com/s/75vocnn5r4833qe/PCNs_ICML_2022.pdf?dl=0) &bull;
[Poster](https://www.dropbox.com/s/7p3uhpyound22st/pcn_poster.pdf?dl=0) &bull;
[Presentation](https://youtu.be/BQ6mKBzbfms)


**TT-PINN: A Tensor-Compressed Neural PDE Solver for Edge Computing**
<br />Ziyue Liu; Xinling Yu; Zheng Zhang<br />
<abstract>Physics-informed neural networks (PINNs) have been increasingly employed due to their capability of modeling complex physics systems. To achieve better expressiveness, increasingly larger network sizes are required in many problems. This has caused challenges when we need to train PINNs on edge devices with limited memory, computing and energy resources. To enable training PINNs on edge devices, this paper proposes an end-to-end compressed PINN based on Tensor-Train decomposition. In solving a Helmholtz equation, our proposed model significantly outperforms the original PINNs with few parameters and achieves satisfactory prediction with up to 15x overall parameter reduction.</abstract>

[PDF](https://www.dropbox.com/s/zrwwfnm5u5uqsf9/paper_TT-PINN.pdf?dl=0) &bull;
[Poster](https://www.dropbox.com/s/arzcltb0r0zl9tb/poster_TT-PINN.pdf?dl=0) &bull;
[Presentation](https://youtu.be/-Ic244hvX4Q)


**Get the Random Number on the fly: A Low-Precision DNN Training Framework using Stochastic Rounding without the Random Number Generator**
<br />Geng Yuan; Sung-En Chang; Alec Lu; Jun Liu; Qing Jin; Yanyu Li; Yushu Wu; Zhenglun Kong; Yanyue Xie; Peiyan Dong; Minghai Qin; Xiaolong Ma; Zhenman Fang; Yanzhi Wang<br />
<abstract>Stochastic rounding is a critical technique used in low-precision deep neural networks (DNNs) training to ensure good model accuracy. <br/>However, it requires a large number of random numbers generated on the fly. <br/>This is not a trivial task on the hardware platforms such as FPGA and ASIC.<br/>The widely used solution is to introduce random number generators with extra hardware costs. In this paper, we innovatively propose to employ the stochastic property of DNN training process itself and directly extract random numbers from DNNs in a self-sufficient manner. We propose different methods to obtain random numbers from different sources in neural networks and a generator-free framework is proposed for low-precision DNN training on a variety of deep learning tasks. Moreover, we evaluate the quality of the extracted random numbers and find that high-quality random numbers widely exist in DNNs, while their quality can even pass the NIST test suite.</abstract>

[PDF](https://www.dropbox.com/s/ueafpq0h03suy6r/HAET22_Gen_Free_Camera_Ready.pdf?dl=0) &bull;
[Poster](https://www.dropbox.com/s/k6a8mzcjr9nfwtf/HAET2022_Poster_Gen_Free.pdf?dl=0) &bull;
[Presentation](https://youtu.be/CKFeT0L4-8Y)


**Efficient Training of Deep Equilibrium Models**
<br />Bac Nguyen; Lukas Mauch<br />
<abstract>Deep equilibrium models (DEQs) have proven to be very powerful for learning data representations. The idea is to replace traditional (explicit) feedforward neural networks with an implicit fixed-point equation, which allows to decouple the forward and backward passes. In particular, training DEQ layers becomes very memory-efficient via the implicit function theorem. However, backpropagation through DEQ layers still requires solving an expensive Jacobian-based equation. In this paper, we introduce a simple but effective strategy to avoid this computational burden. Our method relies on the Jacobian approximation of Broyden’s method after the forward pass to compute the gradients during the backward pass. Experiments show that simply re-using this approximation can<br/>significantly speed up the training while not causing any performance degradation.</abstract>

[PDF](https://www.dropbox.com/s/ck35l4iofjnm3u0/icml_gdeq.pdf?dl=0) &bull;
[Poster](https://www.dropbox.com/s/b6l8s7zvpuvzors/GDEQ_poster.pdf?dl=0) &bull;
[Presentation](https://youtu.be/Sf067JbODUM)


**Locally Supervised Learning with Periodic Global Guidance**
<br />Hasnain Irshad Bhatti; Jaekyun Moon<br />
<abstract>Locally supervised learning aims to train a neural network based on a local estimation of the global loss function at each decoupled module of the network. Auxiliary networks are typically appended to the modules to approximate the gradient updates based on the greedy local losses. Despite being advantageous in terms of parallelism and reduced memory consumption, this paradigm of training severely degrades the generalization performance of neural networks. In this paper, we propose Periodically Guided local Learning (PGL), which reinstates the global objective repetitively into the local-loss based training of neural networks primarily to enhance the model's generalization capability. We show that a simple periodic guidance scheme begets significant performance gains while having a low memory footprint. We conduct extensive experiments on various datasets and networks to demonstrate the effectiveness of PGL, especially in the configuration with numerous decoupled modules.</abstract>

[PDF](https://www.dropbox.com/s/d3i0ky9z96tnabe/camera-ready.pdf?dl=0) &bull;
[Poster](https://www.dropbox.com/s/xbki931ec46q4v4/poster.pdf?dl=0) &bull;
[Presentation](https://youtu.be/o7g5X0CyMfM)


**Energy-aware Network Operator Search in Deep Neural Networks**
<br />Shamma Nasrin<br />
<abstract>This work proposes a novel Energy-aware Network Operator Search (ENOS) approach to address the energy-accuracy trade-offs of a deep neural network (DNN) accelerator. The proposed ENOS framework allows an optimal layer-wise integration of inference operators with optimal precision to maintain high prediction accuracy along with high energy efficiency. The search is formulated as a continuous optimization problem, solvable using gradient descent methods, thereby minimally increasing the training cost when learning both layer-wise inference operators and weights. We discuss multiply-accumulate (MAC) cores for digital spatial architectures that can be reconfigured to different operators and varying computing precision. ENOS training methods with single and bi-level optimization objectives are discussed and compared. We also discuss a sequential operator assignment strategy and a stochastic mode of ENOS. ENOS, characterized on ShuffleNet and SqueezeNet using CIFAR10 and CIFAR100, improves accuracy by 10--20% compared to the conventional uni-operator approaches and by 3-5% compared to mixed-precision uni-operator implementations for the same energy budget.</abstract>



**TrimBERT: Tailoring BERT for Trade-offs**
<br />Sharath Nittur Sridhar; Anthony Sarah; Sairam Sundaresan<br />
<abstract>Models based on BERT have been extremely successful in solving a variety of natural language processing (NLP) tasks. Unfortunately, many of these large models require a great deal of computational resources and/or time for pre-training and fine-tuning which limits wider adoptability. While self-attention layers have been well-studied, a strong justification for inclusion of the intermediate layers which follow them remains missing in the literature. In this work, we show that reducing the number of intermediate layers in BERT-Base results in minimal fine-tuning accuracy loss of downstream tasks while significantly decreasing model size and training time. We further mitigate two key bottlenecks, by replacing softmax operations in the self-attention layers with a computationally simpler alternative and removing half of all layernorm operations. This further increases the throughput while maintaining a high level of fine-tuning accuracy.</abstract>

[PDF](https://www.dropbox.com/s/xxo51pa9z35wk1h/TrimBERT_ICML_2022_Workshop_HAETCameraReady.pdf?dl=0) &bull;
[Poster](https://www.dropbox.com/s/87dmk9qtttgntil/ICML-HAET-Poster36x48.pdf?dl=0) &bull;
[Presentation](https://youtu.be/9s24p8LTbZU)


**QReg: On Regularization Effects of Quantization**
<br />MohammadHossein AskariHemmat; Reyhane Askari Hemmat; Alexander Hoffman; Ivan Lazarevich; Ehsan Saboori; Olivier Mastropietro; Sudhakar Sah; Yvon Savaria; Jean-Pierre David<br />
<abstract>In this paper we study the effects of quantization in DNN training. We hypothesize that weight quantization is a form of regularization and the amount of regularization is correlated with the quantization level (precision). We confirm our hypothesis by providing analytical study and empirical results. By modeling weight quantization<br/>as a form of additive noise to weights, we explore how this noise propagates through the network at training time. We then show that the magnitude of this noise is correlated with the level of quantization. To confirm our analytical study, we performed an extensive list of experiments summarized in this paper in which we show that the regularization effects of quantization can be seen in various vision tasks and models, over various datasets. Based on our study, we propose that<br/>8-bit quantization provides a reliable form of regularization in different vision tasks and models.</abstract>

[PDF](https://www.dropbox.com/s/nqdiwi8h5vk3lqq/On%20Regularization%20Effects%20of%20Quantization.pdf?dl=0) &bull;
[Poster](https://www.dropbox.com/s/f31ufo2gmcli79g/Qreg_Poster.pdf?dl=0) &bull;
[Presentation](https://youtu.be/x7BX781P3QY)



**MCTensor: A High-Precision Deep Learning Library with Multi-Component Floating-Point**
<br />Tao Yu; Wentao Guo; Canal Li; Tiancheng Yuan; Christopher De Sa<br />
<abstract>In this paper, we introduce MCTensor, a library based on PyTorch for providing general-purpose and high-precision arithmetic for DL training. MCTensor is used in the same way as PyTorch Tensor: we implement multiple basic, matrix-level computation operators and NN modules for MCTensor with identical PyTorch interface. Our algorithms achieve high precision computation and also benefits from heavily-optimized PyTorch floating-point arithmetic. We evaluate MCTensor arithmetic against PyTorch native arithmetic for a series of tasks, where models using MCTensor in float16 would match or outperform the PyTorch model with float32 or float64 precision.</abstract>

[PDF](https://www.dropbox.com/s/wb6qitawtxn4h4l/MCFLibrary_camera_ready.pdf?dl=0) &bull;
[Poster](https://www.dropbox.com/s/29uj3o2mtvgnc2b/Icml22_poster_mcf.pdf?dl=0) &bull;
[Presentation](https://youtu.be/uHc4l35z0Vk)


**Finding Structured Winning Tickets with Early Pruning**
<br />Udbhav Bamba; Devin Kwok; Gintare Karolina Dziugaite; David Rolnick<br />
<abstract>Early in the training of a neural network, there exist sparse subnetworks (“winning lottery tickets”) that can be trained in isolation to match the accuracy of full, dense training (Frankle &amp; Carbin, 2019; Frankle et al., 2020a). While this behavior was first observed for unstructured pruning, it is less clear if such subnetworks also appear in different structured pruning regimes, which have the advantage of being more computationally efficient than unstructured pruning. In this work, we show that a simple method of kernel pruning by mean magnitude, which outperforms the better-studied method of filter pruning, can also identify structured winning tickets, much like filter pruning or unstructured pruning. Moreover, we demonstrate that applying mean magnitude kernel pruning to networks early in training can achieve a higher accuracy-to-FLOPs ratio than training dense networks, filter pruning networks, or pruning networks at initialization.</abstract>

[PDF](https://www.dropbox.com/s/kg5a9r8h1ga9laj/Paper.pdf?dl=0) &bull;
[Poster](https://www.dropbox.com/s/ipf8k8enanpujf7/Poster.pdf?dl=0) &bull;
[Presentation](https://youtu.be/H5PC3bkdzr4)


**FlashAttention: Fast and Memory-Efficient Exact Attention with IO-Awareness**
<br />Tri Dao; Daniel Y Fu; Stefano Ermon; Atri Rudra; Christopher Re<br />
<abstract>Transformers are slow and memory-hungry on long sequences, since the time and memory complexity of self-attention are quadratic in sequence length. Approximate attention methods have attempted to address this problem by trading off model quality to reduce the compute complexity, but often do not achieve wall-clock speedup. We argue that a missing principle is making attention algorithms IO-aware -- accounting for reads and writes between levels of GPU memory. We propose FlashAttention, an IO-aware exact attention algorithm that uses tiling to reduce the number of memory reads/writes between GPU high bandwidth memory (HBM) and GPU on-chip SRAM. We analyze the IO complexity of FlashAttention, showing that it requires fewer HBM accesses than standard attention, and is optimal for a range of SRAM sizes. We also extend FlashAttention to block-sparse attention, yielding an approximate attention algorithm that is faster than any existing approximate attention method. FlashAttention trains Transformers faster than existing baselines: 15% end-to-end wall-clock speedup on BERT-large (seq. length 512) compared to the MLPerf 1.1 training speed record, 3× speedup on GPT-2 (seq. length 1K), and 2.4× speedup on long-range arena (seq. length 1K-4K). FlashAttention and block-sparse FlashAttention enable longer context in Transformers, yielding higher quality models (0.7 better perplexity on GPT-2 and 6.4 points of lift on long-document classification) and entirely new capabilities: the first Transformers to achieve better-than-chance performance on the Path-X challenge (seq. length 16K, 61.4% accuracy) and Path-256 (seq. length 64K, 63.1% accuracy).</abstract>
