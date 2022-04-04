
# Speakers

- [Jian Tang](#jian-tang)

- [Damien Querlioz](#damien-querlioz)

- [Alexander Keller](#alexander-keller)

- [Melika Payvand](#melika-payvand)

- [Fabien Cardinaux](#fabien-cardinaux)

- [Tien-Ju Yang](#tien-ju-yang)

## Jian Tang

| <img src="/speakers_pictures/Jian.jpg" alt="Jian Tang" height="250px" /> |
| **Geometric Deep Learning for Drug Discovery** |
| Drug discovery is a very long and expensive process, taking on average more than 10 years and costing 2.5B to develop a new drug. Artificial intelligence has the potential to significantly accelerate the process of drug discovery by extracting evidence from a huge amount of biomedical data and hence revolutionizes the entire pharmaceutical industry. In particular, graph representation learning and geometric deep learning--a fast growing topic in the machine learning and data mining community focusing on deep learning for graph-structured and 3D data---has seen great opportunities for drug discovery as many data in the domain are represented as graphs or 3D structures (e.g. molecules, proteins, biomedical knowledge graphs). In this talk, I will introduce our recent progress on geometric deep learning for drug discovery and also a newly released open-source machine learning platform for drug discovery, called TorchDrug. |

| **Affiliation** | [MILA](https://jian-tang.com/) |
| **Biography** | Jian Tang is currently an assistant professor at Mila-Quebec AI Institute and also at the Computer Science Department and Business School of University of Montreal.  He is a Canada CIFAR AI Research Chair. His main research interests are graph representation learning, graph neural networks, geometric deep learning, deep generative models, knowledge graphs and drug discovery. During his PhD, he was awarded with the best paper in ICML2014; in 2016, he was nominated for the best paper award in the top data mining conference World Wide Web (WWW); in 2020, he is awarded with Amazon and Tencent Faculty Research Award. He is one of the most representative researchers in the growing field of graph representation learning and has published a set of representative works in this field such as LINE and RotatE. His work LINE on node representation learning has been widely recognized and is the most cited paper at the WWW conference between 2015 and 2019.  Recently, his group just released an open-source machine learning package, called TorchDrug, aiming at  making AI drug discovery software and libraries freely available to the research community. He is an area chair of ICML and NeurIPS. | 


## Damien Querlioz

| <img src="/speakers_pictures/Damien.jpg" alt="Damien Querlioz" height="250px" /> |
| **Memory-Centric Machine Learning** |
| When performing machine learning tasks, central and graphics processing units consume considerably more energy for moving data between logic and memory units than for doing actual arithmetic. Brains, by contrast, achieve superior energy efficiency by fusing logic and memory entirely, performing a form of “in-memory” computing. Until now such an integration between logic and memory was impossible at a large scale using CMOS technology. However, companies such as Intel, Samsung, or TSMC, have recently reached production status on new memory devices such as (mem)resistive, phase change, and magnetic memories, which give us an opportunity to achieve an extremely tight integration between logic and memory. Unfortunately, these new devices also come with important challenges due to their unreliable nature. In this talk, we will look at neuroscience inspiration to extract lessons on the design of in-memory computing systems with unreliable devices. We will first study the reliance of brains on approximate memory strategies, which can be reproduced for machine learning. We will give the example of a hardware binarized neural network relying on resistive memory. Based on measurements on a hybrid CMOS and resistive hafnium oxide memory chip exploiting a differential approach, we will see that such systems can exploit the properties of emerging memories without the need for error-correcting codes, and achieve extremely high energy efficiency. Then, we will present a second approach where the probabilistic nature of emerging memories, instead of being mitigated, can be fully exploited to implement a type of probabilistic learning. We show that the inherent variability in hafnium oxide memristors can naturally implement the sampling step in the Metropolis-Hastings Markov Chain Monte Carlo algorithm, and train experimentally an array of 16,384 memristors to recognize images of cancerous tissues using this technique. Finally, we will present prospects concerning the implementation of different learning algorithms with emerging memories. |

| **Affiliation** | [CNRS](https://sites.google.com/site/damienquerlioz/) |
| **Biography** | Damien Querlioz is a CNRS Researcher at the Centre de Nano-sciences et de Nanotechnologies of Université Paris-Saclay. His research focuses on novel usages of emerging non-volatile memory and other nanodevices, in particular relying on inspirations from biology and machine learning. He received his predoctoral education at Ecole Normale Supérieure, Paris and his PhD from Université Paris-Sud in 2009. Before his appointment at CNRS, he was a Postdoctoral Scholar at Stanford University and at the Commissariat a l'Energie Atomique. Damien Querlioz is the coordinator of the interdisciplinary INTEGNANO research group, with colleagues working on all aspects of nanodevice physics and technology, from materials to systems. He is a member of the bureau of the French Biocomp research network. He has co-authored one book, nine book chapters, more than 100 journal articles, and conference proceedings, and given more than 50 invited talks at national and international workshops and conferences. In 2016, he was the recipient of an ERC Starting Grant to develop the concept of natively intelligent memory. In 2017, he received the CNRS Bronze medal. He has also been a co-recipient of the 2017 IEEE Guillemin-Cauer Best Paper Award and of the 2018 IEEE Biomedical Circuits and Systems Best Paper Award. | 

## Alexander Keller

| <img src="/speakers_pictures/Alexander.jpeg" alt="Alexander Keller" height="250px" /> |
| **1x1-Convolutions by Random Ternary Matrices** |
| We demonstrate that 1x1-convolutions in deep neural networks, which are equivalent to fully connected layers, may be replaced by constant, random ternary matrices with weights in {-1,0,+1}. Such matrices may be generated on the chip during computation and therefore require neither memory access for weights nor training. In addition, such layers do not perform any multiplications. We reduce model size significantly while preserving accuracy.|

| **Affiliation** | [NVIDIA](https://research.nvidia.com/person/alex-keller) |
| **Biography** | Alexander Keller is a director of research at NVIDIA, leading advanced rendering research. Before, he had been the Chief Scientist of mental images, where he had been responsible for research and the conception of future products and strategies including the design of the iray renderer. Prior to industry, he worked as a full professor for computer graphics and scientific computing at Ulm University, where he co-founded the UZWR (Ulmer Zentrum für wissenschaftliches Rechnen) and received an award for excellence in teaching. Alexander Keller holds a Ph.D. in computer science, authored more than 25 granted patents, and published more than 50 papers mainly in the area of quasi-Monte Carlo methods, photorealistic image synthesis using ray tracing, and machine learning.|



## Melika Payvand

| <img src="/speakers_pictures/Melika.jpg" alt="Melika Payvand" height="250px" /> |
| **Closing the Gap Between Devices, Circuits and Algorithms Towards Low-Power On-Chip Online Learning** |
| Tur digital society is shifting to an era of pervasive specialized edge-computing systems for a wide variety of tasks.Artificial Intelligence (AI) is fueling this revolution to achieve remarkable results for both pattern recognition and generation. However, the current technology used to run AI algorithms is not optimally suited for the low-power and real-time requirements of edge-computing devices. While multiple efforts have been launched to develop low power processing technologies to overcome this problem, training these algorithms for continuous learning and adaptation at the edge remains a challenge. Neuromorphic technologies with adaptive properties have the potential to overcome this problem through learning continuously from streaming data in an always-on and low power fashion. Moreover, there has been lots of advancements in emerging memory technologies which present a great opportunity for online learning through their multi-state properties and internal dynamics. Furthermore, there have been many recent new neuroscientific discoveries and machine learning insights which makes this problem very timely. |

| **Affiliation** | [University of Zurich](https://services.ini.uzh.ch/people/melika) |
| **Biography** |  Melika Payvand is a research scientist at the Institute of Neuroinformatics, University of Zurich and ETH Zurich. She received her M.S. and Ph.D degree in electrical and computer engineering from the University of California Santa Barbara in 2012 and 2016 respectively. Her research activities and interest is in exploiting the physics of the computational substrate for online learning and sensory processing on the edge. In particular, she is interested in following a co-design approach between devices, circuits, algorithms and application for a holistic approach towards low power learning and processing at the edge. She is co-coordinating the European NEUROTECH project, is in the scientific committee of the Capocaccia workshop, and chairs the neuromorphic engineering track at the IEEE flagship conference International Conference in Circuits and Systems (ISCAS). She served as the co-chair of the 2021 International Conference on Neuromorphic Systems (ICONS 2021) and is a guest editor of Frontiers in Neuroscience and and is the winner of the best neuromorph award of the 2019 Telluride neuromorphic workshop. |




## Tien-Ju Yang

| <img src="/speakers_pictures/Tien-Ju Yang" alt="Tien-Ju Yang" height="250px" /> |
| **NetAdaptV2: Efficient Neural Architecture Search with Fast Super-Network Training and Architecture Optimization** |
| Neural architecture search (NAS) typically consists of three main steps: training a super-network, training and evaluating sampled deep neural networks (DNNs), and training the discovered DNN. Most of the existing efforts speed up some steps at the cost of a significant slowdown of other steps or sacrificing the support of non-differentiable search metrics. The unbalanced reduction in the time spent per step limits the total search time reduction, and the inability to support non-differentiable search metrics limits the performance of discovered DNNs. We present NetAdaptV2 with three innovations to better balance the time spent for each step while supporting non-differentiable search metrics. First, we propose channel-level bypass connections that merge network depth and layer width into a single search dimension to reduce the time for training and evaluating sampled DNNs. Second, ordered dropout is proposed to train multiple DNNs in a single forward-backward pass to decrease the time for training a super-network. Third, we propose the multi-layer coordinate descent optimizer that considers the interplay of multiple layers in each iteration of optimization to improve the performance of discovered DNNs while supporting non-differentiable search metrics. With these innovations, NetAdaptV2 reduces the total search time by up to 5.8$\times$ on ImageNet and 2.4X on NYU Depth V2, respectively, and discovers DNNs with better accuracy-latency/accuracy-MAC trade-offs than state-of-the-art NAS works. Moreover, the discovered DNN outperforms NAS-discovered MobileNetV3 by 1.8\% higher top-1 accuracy with the same latency. |

| **Affiliation** | [Google](https://ieeexplore.ieee.org/author/37086227631) |
| **Biography** | Tien-Ju Yang received the B.S. and M.S. degrees in Electrical Engineering and Electronic Engineering from National Taiwan University (NTU), Taipei, Taiwan, in 2010 and 2012, respectively, and the M.S. and Ph.D. degrees in Electrical Engineering and Computer Science from Massachusetts Institute of Technology, Cambridge, MA, in 2018 and 2020, respectively. His research interest spans the area of deep learning, computer vision, machine learning, image/video processing, and VLSI system design. He is currently a Research Scientist at Google focusing on efficient large-scale on-device training and federated learning. He won ﬁrst place in the 2011 NTU Innovation Contest. He also co-taught a tutorial on ``Efficient Image Processing with Deep Neural Networks'' at IEEE International Conference on Image Processing 2019. |


## Fabien Cardinaux

| <img src="/speakers_pictures/Fabien.jpeg" alt="Fabien Cardinaux" height="250px" /> |
| **DNN Quantization with Mixed Precision and Trained Lookup Tables.** |
| Efficient deep neural network (DNN) inference on mobile or embedded devices typically involves quantization of the network parameters and activations. In this talk we will see how we can parametrize the quantizers efficiently to learn the optimal bitwidth for each layer.  We show that a parametrization of the quantizer with step size and dynamic range is the key to achieve a stable training and a good final performance. The bitwidth can then be inferred from them. In a second part we will introduce
look-up table quantization, LUT-Q, which learns a dictionary and assigns each weight to one of the dictionary’s values. We show that this method is very flexible and that many other techniques can be seen as special cases of LUT-Q. For example, we can constrain the dictionary trained with LUT-Q to generate networks with pruned weight matrices or restrict the dictionary to powers-of-two to avoid the need for multiplications. |

| **Affiliation** | [Sony]() |
| **Biography** | Fabien Cardinaux is leading a R\&D team at the Sony R\&D Center Europe in Stuttgart (Germany). Prior to joining Sony in 2011, he has worked as a Postdoc at the University of the Sheffield (UK). In 2005, he obtained a PhD from EPFL (Switzerland) for his work on machine learning methods applied to face authentication. His current research interests lie in deep neural network footprint reduction, neural architecture search and audio content representation. |
