---
layout: archive
title: "Research Projects"
permalink: /projects/
author_profile: true
header:
  og_image: "research/ecdf.png"
---
Fast, Scalable and Geo-Distributed PCA forBig Data Analytics
--------
In our study, we take advantage of the zero-noise-limit Probabilistic PCA model, and introduce a block-division method for it in order to suppress the explosion of intermediate data efficiently. We employ several optimization ideas such as mean propagation for preserving sparsity, dynamic tuning of the number of blocks to automatically adjust to large dimensions, etc. Additionally, in the geo-distributed environment, we propose a communication efficient solution by reducing idle time, passing only the required parameters, and choosing geographically ideal central datacenter for faster accumulation. We refer to our algorithm as TallnWide. Our empirical evaluation with real datasets shows that TallnWide can successfully handle at least $\mathbf{10\times}$ higher dimensional data than existing methods, and offer up to $\mathbf{2.9\times}$ improvement in running time in the geo-distributed environment compared to the conventional approaches.<br/>
- __Supervisor__: [Dr. Muhammad Abdullah Adnan](https://sites.google.com/site/abdullahadnan/)<br/>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;  Associate Professor, Deaprtment of CSE<br/>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;  Bangladesh Universiry of Engineering and Technology (BUET)<br/>
- __Co Authors__: 
    1. [Md. Mehrab Tanjim](https://scholar.google.com/citations?user=IPr2JZYAAAAJ&hl=en), PhD Student, CSE, University of California, San Diego<br/>
- __Status__: Published in [Information System](https://www.sciencedirect.com/journal/information-systems) [[Paper Link](https://www.sciencedirect.com/science/article/abs/pii/S0306437920301526?via%3Dihub)] [Code](https://github.com/tmadnan10/TallnWide)


UACD: A Local Approach for Identifying the Most Influential Spreaders in Twitter in a Distributed Environment
--------
We propose a novel method of identifying the most influential spreaders on Twitter social network by incorporating the user-specific information (extracted from his/her Twitter account) to the topological information. 
We provide a distributed implementation of our proposed algorithm on the Amazon EC2 and observe that the algorithm is scalable and can process a significantly large network. We compare our ranking result with that of the existing methods using widely accepted metrics of ranking comparison and our experimental results indicate that our new method is $\mathbf{12.5\%}$ (average) more accurate and can produce the result in $\mathbf{175\times}$ less time.<br/>
- __Supervisor__: [Dr. Muhammad Abdullah Adnan](https://sites.google.com/site/abdullahadnan/)<br/>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;  Associate Professor, Deaprtment of CSE<br/>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;  Bangladesh Universiry of Engineering and Technology (BUET)<br/>
- __Co Authors__: 
    1. [Md. Saiful Islam](https://saiful1105020.github.io), PhD Student, CSE, University of Rochester
    2.  [Md. Tarikul Islam Papon](https://cs-people.bu.edu/papon/), PhD Researcher, CS, Boston University
- __Status__: Under review at [SNAM](https://www.springer.com/journal/13278)



To Download or Not to Download: A Machine Learning Approach for Detecting Privacy Evasive Mobile Applications on Google Play Store
--------
In our study, we apply unsupervised learning in order to clusterize the mobile apps from Google Play Store based on their description and permissions they seek from the user. After that, we detect the out-layered apps that significantly deviate from the relevant permissions and  label them as unsafe. Finally, we design an LSTM based deep learning model which can provide a rating that best represents the app's behavior regarding user privacy. We evaluate the accuracy of our model using our self-labeled (description and permissions vs safe/unsafe) dataset.<br/>
- __Supervisor__: [Dr. Muhammad Abdullah Adnan](https://sites.google.com/site/abdullahadnan/)<br/>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;  Associate Professor, Deaprtment of CSE<br/>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;  Bangladesh Universiry of Engineering and Technology (BUET)<br/>
- __Co Authors__: 
    1. [Md. Mehrab Tanjim](https://scholar.google.com/citations?user=IPr2JZYAAAAJ&hl=en), PhD Student, CSE, University of California, San Diego
    2. [Md. Touhidul Islam](https://www.linkedin.com/in/md-touhidul-islam-b9aa2688/?originalSubdomain=bd), Graduate RA, CSE, Penn State University
- __Status__: Preprint

Hierarchical Attention for Host Intrusion Detection
--------
The host-based intrusion detection system (HIDS) analyzes auditing data from operating systems, whereas *System-call based HIDS* is about analyzing collected Linux system call traces to detect any malicious activity. The traditional methods of HIDS have been proven to be vulnerable to higher number of false alarms. 
In our work, we propose a novel hierarchical attention based deep learning method of detection intrusion on a host. We evaluate our model on ADFA-LD dataset, which is a collection of a trace data of Linux system calls. We tune our model's hyper parameters to produce the optimum result, and our method successfully outperforms the existing methods in terms of accuracy as well as lower false alarm rate.<br/>
- __Supervisor__: [Dr. Md. Shohrab Hossain](https://scholar.google.com/citations?user=y89HApwAAAAJ&hl=en)<br/>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;  Professor, Deaprtment of CSE<br/>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;  Bangladesh Universiry of Engineering and Technology (BUET)<br/>
- __Co Authors__: 
    1. [Md. Shehab Sarar Ahmed](https://cse.buet.ac.bd/faculty/facdetail.php?id=shehab), Lecturer, CSE, Bangladesh Universiry of Engineering and Technology (BUET)
- __Status__: Preprint

Protein Function Prediction using Multi-Layer CNN
--------
Developing efficient computational approaches for automatic protein function prediction  is of utmost importance to reduce the large gap between the numbers of proteins with known primary sequences and those with experimental annotations. In our work, we have targeted to develop a highly accurate method for predicting protein functions which incorporates a novel hierarchical multi-layer convolutional neural network (CNN) in order to effectively capture the *long-range interactions* among the amino acid residues. We have evaluated our model using CAFA3 and Uniprot dataset.<br/>
- __Supervisor__: [Dr. Md. Shamsuzzoha Bayzid](https://scholar.google.com/citations?user=h2vHz3wAAAAJ&hl=en)<br/>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;  Associate Professor, Deaprtment of CSE<br/>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;  Bangladesh Universiry of Engineering and Technology (BUET)<br/>
- __Co Authors__: 
    1. [Nafis Sadeq](https://www.linkedin.com/in/nafis-sadeq/?originalSubdomain=bd), PhD Student, CSE, University of California, San Diego
    2. [Shafayat Ahmed Piyal](https://www.linkedin.com/in/shafayat-piyal-13b406103/?originalSubdomain=bd), Graduate TA, CSE, Virginia Tech
- __Status__: Preprint