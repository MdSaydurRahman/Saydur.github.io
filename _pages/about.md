---
title: ""
permalink: /
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---
 <h1 style="color:  #0f0e0e;">Bio</h1>
<br>
I am Md Saydur Rahman currently a Ph.D. student in Electrical Engineering at the University of California Riverside (UCR), and I am expected to graduate in 2025. I have completed my Bachelor's from Bangladesh University of Engineering and Technology (BUET). Currently, I am working as a Research Assistant under the supervision of Professor 
<a href="https://intra.ece.ucr.edu/~yhua/" style="color: blue;">Yingbo Hua</a>. My research interest involves Wireless Physical Layer Security, 5g Low-latency Communication, Domain adaptation-based Deep learning, and Federated learning. 
<div class="wordwrap">  
  You can also find my latest articles/publications on  
  <a href="https://scholar.google.com/citations?user=Zbf4zyUAAAAJ&hl=en&authuser=1" style="color: blue;">Google Scholar</a>. </div>
<div class="wordwrap"> My latest <a href="https://drive.google.com/file/d/1g8TKk-dQo5wxPrOqyS6hOfrZyRQPWQ6I/view?usp=sharing" style="color: blue;">CV</a>. </div>

<br>

<h1 style="color: #0f0e0e;">Education</h1>  

- **PhD**: Ongoing at UCR, expected completion by 2025  

- **Master's Degree**: University of California, Riverside (UCR), March 2024  

- **Bachelor's Degree**: Bangladesh University of Engineering and Technology (BUET), 2017
 <br>
 
<br>

<div class="news-section">
  <h1 style="color:  #0f0e0e;">Latest News</h1>

  <li> Oct 2024: Paper presented at the <em>Asilomar </em> in Pacific Grove.</li>
  <li> Sep 2024: Poster presented at <em>Department of Defense NC4</em>.</li>
  <li> Aug 2024: Received the <a href="https://www.linkedin.com/feed/update/urn:li:activity:7231977654407610368/" style="color: red;">Best Paper Award</a>. at the <em>IEEE LANMAN</em>.</li>
  <li> Jul 2024: Paper accepted at the <em>IEEE LANMAN</em>.</li>
  <li> Jun 2024: Paper accepted at the <em>IEEE ICC</em>.</li>
  <li> Apr 2024: Paper accepted at the <em>GPECOM</em>.</li>
  <li> Mar 2024: Got Masters' degree in Electrical Engineering from UC Riverside.</li>
  <li> Feb 2024: Paper accepted at the <em>ICICT</em>.</li>
  <li> Nov 2023: Paper accepted at the <em>IEEE ETFG</em>.</li>
  <li> Oct 2023: Poster presented at <em>Department of Defense NC4</em></li>
  <li> Sep 2023: Passed the PhD Qualifier Exam.</li>
  <li> Jul 2023: Journal Accepted at <em>IEEE Transaction on Signal Processing</em>.</li>
  <li> Sep 2022: Poster presented at <em>Department of Defense NC4</em></li>
  <li> Oct 2020: Started Ph.D at UC Riverside</li>
  <li> Nov 2019: Paper accepted at the <em>IEEE RAAICON</em>.</li>
  
 <br>
  <br>
  <h1 style="color:  #0f0e0e;">Projects</h1>
   <br>

<h4 style="color: #0f0e0e;">Security in Wiretap Channel</h4>  <a href="https://arxiv.org/abs/2403.06438" style="color: blue;">ICC'24</a> 
"STEEP" enables secure message transmission in a MISO fading channel from Alice to Bob, even when Eve's channels are stronger. It unifies principles in wiretap channel transmission and secret key generation, superseding any known models for guaranteed positive secrecy against stronger eavesdroppers. The principle of STEEP consists of two phases of interdependent operations: phases 1 and 2. In phase 1, a node (Alice) sends random probing symbols (also called probes) over a probing channel to another node (Bob). In this phase, Bob obtains some estimates of the probes, which could be noisy. While the estimates of the probes by Eve cannot be noiseless, they are allowed to be less noisy than those by Bob.  
<br><br>

<img src="images/steep1.drawio.png" alt="STEEP Principle Diagram" style="max-width: 60%; height: auto;">  
<br><br>

In phase 2, Bob echoes back his estimated probes encrypted by a secret message meant for Alice via a return channel. Since Alice knows the exact probes, the effective wiretap channel system from Bob to Alice and Eve, relative to the secret message from Bob, is such that the effective return channel from Bob to Alice is stronger than that from Bob to Eve, subject to a sufficient amount of power from Bob.
 
<br>


<h4 style="color: #0f0e0e;">UAV Against Jamming</h4>  
In this UAV communication against jamming, we first consider a network as illustrated in Fig. Here Alice and Eve are ground stations with \( n_A \) and \( n_E \) antennas respectively. Eve is capable of jamming and receiving in full-duplex. Bob is the UAV with a single antenna. Unmanned Aerial Vehicle (UAV) assisted wireless communication has emerged as a highly promising element in the landscape of future wireless networks. This work investigates the application of “Secret-message Transmission by Echoing Encrypted Probes (STEEP)” to secure UAV communications between a ground station (Alice) and a UAV (Bob). Even with the presence of strong jamming from a full-duplex eavesdropper (Eve), STEEP shows resilience and maintains a strong positive secrecy rate in bits per channel use in every channel coherence period as long as Eve’s observations during the probing phase of STEEP are not noiseless.

<img src="images/uav.drawio.png" alt="STEEP with UAV against Jamming" style="max-width: 60%; height: auto;">  
<br><br>
The novel scheme "STEEP" maintains a strong positive secrecy rate in bits per channel use during each channel coherence period. Theoretical and numerical results demonstrate secure aerial communication even against a stronger ground jammer.  
<a href="#" style="color: blue;">Asilomar'24</a>  




<h4 style="color: #0f0e0e;">Low-Latency Multi-Access (MA) STEEP</h4>  <a href="https://ieeexplore.ieee.org/abstract/document/10621876" style="color: blue;">LANMAN'24</a>  
"MA-STEEP" between User Equipment (UEs) and an Access Point (AP) allows all UEs to utilize a common sequence of probes broadcast by the AP. This low-latency method demonstrates positive secrecy with high probability, and the total secrecy capacity increases with the number of UEs, unlike methods using a common nonce.  

<br>


<h4 style="color: #0f0e0e;">SDoF Using Collaborative Pilots</h4>  <a href="https://ieeexplore.ieee.org/abstract/document/10235266" style="color: blue;">TSP'23</a>  
The Secure Degree of Freedom (SDoF) of a multi-user, multi-antenna, full-duplex wireless network with secret information transmission is analyzed using multi-user, multi-antenna ANECE against multi-antenna Eve. Novel results on SDoF are shown by analyzing the secret-key capacity of each pair of nodes in a network of multiple collaborative nodes per channel coherence period.  

<br>


<h4 style="color: #0f0e0e;">Domain Adaptation</h4>  <a href="https://ieeexplore.ieee.org/abstract/document/10407265" style="color: blue;">ETFG'23</a> | <a href="https://ieeexplore.ieee.org/abstract/document/10582569" style="color: blue;">GPECOM'24</a>  
Evaluating source-free domain adaptation models in location-based adaptive learning for weather forecasting, building load, and solar/wind power prediction. A pre-trained model from the source domain is utilized for prediction tasks, assuming no source data during target domain prediction. The weights of only the last few layers of the DNN model are updated, making the model faster compared to traditional approaches.  

<br>


<h4 style="color: #0f0e0e;">Gait Phase Classification</h4>  <a href="https://link.springer.com/chapter/10.1007/978-981-97-3562-4_29" style="color: blue;">ICICT'24</a>  
A novel deep learning model incorporating Bi-GRU and transformer encoders with a gating mechanism efficiently regulates the flow of information between encoders. Achieving better accuracy in most cases, the model includes several locomotion modes, surpassing prior research focused solely on simple level-ground conditions.  

<br>


<h4 style="color: #0f0e0e;">Document Image Classification</h4>  <a href="https://www.techrxiv.org/doi/full/10.36227/techrxiv.172254255.56093481" style="color: blue;">CITDS'24</a>  
The ConvNext V2 model, which incorporates elements of self-attention from transformers, significantly improves document image classification performance on the Tobacco-3482 dataset, achieving a 92.25% accuracy with fast convergence. This suggests that pre-training on ImageNet alone can be highly effective without additional domain-specific training.  

<br>


