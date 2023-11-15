---
permalink: /
title: ""
excerpt: ""
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

<style>
    .project-content {
        display: flex;
        flex-direction: column;
        align-items: center;
    }
    .project-content .project-text,
    .project-content .project-image {
        width: 100%;
    }
</style>
<style>
    @media screen and (min-width: 768px) { 
        .project-content {
            flex-direction: row; /* This reverses the order of flex items */
        }
        .project-content .project-text {
            flex: 1;
            padding-right: 20px; /* Adjust padding to the left of the text for separation */
        }
        .project-content .project-image {
            max-width: 300px;
          
        }
    }
           .justified-text {
            text-align: justify;
        }
</style>


I am Hassan Taherian, currently pursuing my PhD in Computer Science at [Ohio&nbsp;State&nbsp;University](https://cse.osu.edu/) since 2017. I have the privilege of conducting my research under the guidance of [Prof.&nbsp;DeLiang&nbsp;Wang](https://web.cse.ohio-state.edu/~wang.77/). My research interests span a variety of domains in the world of sound and speech processing:

<ul class='twocol' style="margin-top: -1%;" markdown='1'>
<li>Speech Separation and Enhancement</li>
<li>Sound Event Detection and Sound Localization</li>
<li>Automatic Speech Recognition</li>
<li>Speaker Recognition and Diarization</li>
<li>Speech Synthesis</li>
<li>Deep Learning in Audio Processing</li>
</ul>

<a id="research_highlights"></a>
## Research Highlights


 ### Conversational Speaker Separation via Neural Diarization


<p class="justified-text"> We introduce a new framework, termed ``speaker separation via neural diarization" (SSND), for multi-channel conversational speaker separation.  This approach employs a deep neural network (DNN) for speaker diarization to demarcate the speech activities of individual speakers. Leveraging the estimated utterance boundaries from neural diarization, we generate a sequence of speaker embeddings. These embeddings, in turn, facilitate the assignment of speakers to two output streams of the separation model. The SSND approach tackles the permutation ambiguity issue of talker-independent separation during the diarization phase, rather than during separation. This distinction permits non-overlapped speakers to be assigned to the same output stream, enabling the processing long recordings missing from standard CSS.  Another advantage of SSND lies in the inherent integration of speaker separation and diarization, enabling sequential grouping of the discontinuous utterances of the same talker.
Our SSND framework achieves state-of-the-art diarization and ASR results, surpassing all existing  methods on the open LibriCSS dataset</p>
<div class="project-content">
    <div class="project-text">
      <a href="/projects/ssnd/">Read More</a>
    </div>
    <div class="project-image">
<img src='/images/diarSEP_diagram-01.png' style='width:300px;' alt='Project 0 Image Description'>
    </div>
</div>  
----
### Location-based Training (LBT)
<div class="project-content">
    <div class="project-text">
 We have proposed two novel training criteria to address the permutation ambiguity problem for multi-channel
talker-independent speaker separation. Different from widely-used permutation invarient trainig (PIT), the new criteria organize DNN outputs on the basis of speaker azimuths and distances relative to a microphone array. 
      <a href="http://web.cse.ohio-state.edu/~wang.77/papers/TTW.taslp22.pdf">Read More</a>
    </div>
    <div class="project-image">
<img src='/images/lbt.png' style='width:300px;' alt='Project 1 Image Description'>
    </div>
</div>
---
### Microphone Array Geometry Agnostic Modeling
<div class="project-content">
    <div class="project-text">
 We utilized spatial features along with speaker embeddings for personalized speech enhancement (PSE) and showed their combination significantly improved the performance for both ASR and signal quality. Furthermore, we proposed a new architecture and introduced the stream pooling layer to perform multi-channel PSE with any number and arrangement of microphones in a way where the output is invariant to the microphone order. Our proposed model consistently outperformed the geometry-dependent models. 
      <a href="https://arxiv.org/pdf/2110.10330.pdf">Read More</a>
    </div>
    <div class="project-image">
<img src='/images/stream_averaging.png' style='width:300px;' alt='Project 1 Image Description'>
    </div>
</div>
---


### Multi-input Multi-output Complex Spectral Mapping
<div class="project-content">
    <div class="project-text">
  Current deep learning based multi-channel speaker separation methods produce a monaural estimate of speaker signals captured by a reference microphone. This work presents a new multi-channel complex spectral mapping approach that simultaneously estimates the real and imaginary spectrograms of all speakers at all microphones. Experimental results show that the proposed MIMO separation model outperforms a multi-input single-output (MISO) speaker separation model with monaural estimates. The proposed approach achieves the state-of-the-art speaker separation on the open LibriCSS dataset.
      <a href="http://web.cse.ohio-state.edu/~wang.77/papers/TPWXW.interspeech23.pdf">Read More</a>
    </div>
    <div class="project-image">
<img src='/images/MIMO.png' style='width:300px;' alt='Project 1 Image Description'>
    </div>
</div>


<a id="Publications"></a>
## Publications
----

0. **Multi-input multi-output complex spectral mapping for speaker separation**, *Interspeech'23* [[pdf](http://web.cse.ohio-state.edu/~wang.77/papers/TPWXW.interspeech23.pdf)]
<br><i>Hassan Taherian</i>, Ashutosh Pandey, Daniel Wong, Buye Xu, and DeLiang Wang
0. **Multi-resolution Location-based training for multi-channel continuous speech separation**, *ICASSP'23* [[pdf](http://web.cse.ohio-state.edu/~wang.77/papers/Taherian-Wang.icassp23.pdf)]
<br><i>Hassan Taherian</i> and DeLiang Wang
0. **Breaking the trade-off in personalized speech enhancement with cross-task knowledge distillation**, *ICASSP'23* [[pdf](https://arxiv.org/pdf/2211.02944.pdf)]
<br><i>Hassan Taherian</i> Sefik Emre Eskimez, and Takuya Yoshioka
0. **Multi-channel talker-independent speaker separation through location-based training**, *IEEE/ACM TASLP'22* [[pdf](http://web.cse.ohio-state.edu/~wang.77/papers/TTW.taslp22.pdf)]
<br><i>Hassan Taherian</i>, Ke Tan, and DeLiang Wang
0. **One model to enhance them all: array geometry agnostic multi-channel personalized speech enhancement**, *ICASSP'22* [[pdf](https://arxiv.org/pdf/2110.10330.pdf)]
<br><i>Hassan Taherian</i>, Sefik Emre Eskimez, Takuya Yoshioka, Huaming Wang, Zhuo Chen, and Xuedong Huang
0. **Location-based training for multi-channel talker-independent speaker separation**, *ICASSP'22* [[pdf](https://web.cse.ohio-state.edu/~wang.77/papers/TTW.icassp22.pdf)]
<br><i>Hassan Taherian</i>, Ke Tan, and DeLiang Wang
0. **A causal and talker-independent speaker separation/dereverberation deep learning algorithm: Cost associated with conversion to real-time capable operation**, *JASA'21* [[pdf](https://web.cse.ohio-state.edu/~wang.77/papers/HTJW.jasa21b.pdf)]
<br>Eric W. Healy, <i>Hassan Taherian</i>, Eric M. Johnson, and DeLiang Wang
0. **Deep learning based speaker separation and dereverberation can generalize across different languages to improve intelligibility**, *JASA'21* [[pdf](https://web.cse.ohio-state.edu/~wang.77/papers/HealyEtAl.jasa21.pdf)]
<br> Eric W. Healy, Eric M. Johnson, Masood Delfarah, Divya S. Krishnagiri, Victoria A. Sevich, <i>Hassan Taherian</i>, and DeLiang Wang
0. **Time-domain loss modulation based on overlap ratio for monaural conversational speaker separation**, *ICASSP'21* [[pdf](https://web.cse.ohio-state.edu/~wang.77/papers/Taherian-Wang.icassp21.pdf)]
<br><i>Hassan Taherian</i> and DeLiang Wang
0. **Robust speaker recognition based on single-channel and multi-channel speech enhancement**, *IEEE/ACM TASLP'20* [[pdf](https://web.cse.ohio-state.edu/~wang.77/papers/TWCW.taslp20.pdf)]
<br><i>Hassan Taherian</i>, Zhong-Qiu Wang, Jorge Chang, and DeLiang Wang
0. **Deep learning based multi-channel speaker recognition in noisy and reverberant environments**, *Interspeech'19* [[pdf](https://web.cse.ohio-state.edu/~wang.77/papers/TWCW.taslp20.pdf)]
<br><i>Hassan Taherian</i>, Zhong-Qiu Wang, and DeLiang Wang
{: reversed="reversed"}


<a id="Patents"></a>
## Patents
----

0. Hassan Taherian, Jonathan Huang and Carlos M. Avendano, <i>Method and System for Detecting Sound Event Liveness Using a Microphone Array</i>, U.S. Patent No. 11,533,577. 20 Dec. 2022. [[Google Patents](https://patents.google.com/patent/US11533577B2/en)]

0. Hassan Taherian, Sefik Emre Eskimez, Takuya Yoshioka, Huaming Wang, Zhuo Chen and Xuedong Huang, <i>Array Geometry Agnostic Multi-channel Personalized Speech Enhancement</i>, U.S. Patent App. No. US20230116052A1, Dec 2021. 
{: reversed="reversed"}

   

<a id="Experience"></a>
## Research Experience
----
###  <img src='/images/osu_small.jpeg' style='width:38px'>  Ohio State University 
<ul class='twocol' markdown='1'>
<li>Research Assistant, Perception and Neurodynamics Laboratory, May 2018 – Present</li>
</ul>
###  <img src='/images/microsoft_small.jpeg' style='width:40px' >  Microsoft Research
<ul class='twocol' markdown='1'>
<li>Research Intern, Azure Cognitive Services, May 2022 – August 2022</li>
<li>Research Intern, Azure Cognitive Services, May 2021 – August 2021</li>
</ul>
### <img src='/images/apple_small.jpeg' style='width:50px'  >  Apple Inc.
<ul class='twocol' markdown='1'>
<li>Research Intern, Interactive Media Group, June 2020 – August 2020</li>
</ul>

Teaching Experience
----
### <img src='/images/osu_small.jpeg' style='width:38px'> Ohio State University
Instructor of CSE 1222 - Programming in C++
Responsible for teaching, grading and holding office hours
Offered in Spring 2018, and Fall 2017 (~40 enrollment)



