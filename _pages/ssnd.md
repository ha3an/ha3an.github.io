---
layout: blank
title: "SSND Speech Separation Demo"
permalink: /projects/ssnd/
excerpt: "Demonstration of the SSND Framework"
---

<style>
  body {
    font-family: Arial, sans-serif;
    line-height: 1.6;
    margin: 0;
    padding: 20px;
    background: #f9f9f9;
    color: #333;
  }
  h1, h2 {
    font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
    margin-bottom: 20px;
  }
  .container {
    max-width: 1200px;
    margin: auto;
    padding: 0 20px;
  }
  .demo-section {
    margin-bottom: 40px;
  }
  .demo {
    display: flex;
    align-items: center;
    justify-content: space-between;
    margin-bottom: 20px;
  }
  .audio {
    flex-basis: 30%;
    text-align: center;
  }
  img {
    max-width: 65%;
    height: auto;
  }
  footer {
    text-align: center;
    margin-top: 20px;
    padding-top: 20px;
    border-top: 1px solid #ccc;
  }
</style>

<div class="container">
  <h1>Speaker Separation via Neural Diarization (SSND) Demo</h1>
  <p>We introduce the SSND framework, a novel approach that seamlessly integrates speaker diarization with speaker separation. Our SSND framework achieves state-of-the-art performance for speaker-attributed ASR on LibriCSS dataset. Here, we showcase the capabilities of our state-of-the-art convesational speaker separation framework. <a href="http://web.cse.ohio-state.edu/~wang.77/papers/TPWXW.interspeech23.pdf">Learn More</a> </p>

<footer></footer>



<div class="demo-section">
  <h2>Example 2</h2>
  <p>  This segment is from the "overlap_ratio_0.0_sil0.1_0.5_session4_actual0.0" recording of the LibriCSS dataset, spanning from 320s to 345s, which encompasses speech from seven unique speakers. The entire segment is processed through the SSND framework. Note that the estimated speakers boundaries extend beyond the actual limits of their speech.   </p>

<div class="demo">
    <div class="audio">
      <h4>Reverberant Mixed Audio</h4>
      <audio controls>
        <source src="/files/demo/example_2/segment_mixch0.wav" type="audio/wav">
        Your browser does not support the audio element.
      </audio>
    </div>
    <img src="/files/demo/example_2/Spec_mix.png" alt="Spectrogram of Mixed Audio">
  </div>
  
  <div class="demo">
    <div class="audio">
      <h4>Separated Audio Stream 1</h4>
      <audio controls>
        <source src="/files/demo/example_2/segment_0.wav" type="audio/wav">
        Your browser does not support the audio element.
      </audio>
    </div>
    <img src="/files/demo/example_2/Spec_1.png" alt="Spectrogram of Stream 1">
  </div>
  
  <div class="demo">
    <div class="audio">
      <h4>Separated Audio Stream 2</h4>
      <audio controls>
        <source src="/files/demo/example_2/segment_1.wav" type="audio/wav">
        Your browser does not support the audio element.
      </audio>
    </div>
    <img src="/files/demo/example_2/Spec_2.png" alt="Spectrogram of Stream 2">
  </div>

  <div class="demo">
    <div class="audio">
      <h4>Embedding Sequence Indices based on Diarization Estimates</h4>
    </div>
    <img src="/files/demo/example_2/plot.png" alt="Embedding Sequence Indices">
  </div>
  
</div>

<footer></footer>

<div class="demo-section">
    <h2>Example 3</h2>
    <p>This example, taken from the "overlap_ratio_40.0_sil0.1_1.0_session9_actual39.9" recording of the LibriCSS dataset (from 95s to 115s), presents a challenging scenario with 3-fold speech overlap. Although the SSND model is trained with examples containing only two-speaker overlap, it isolates one speaker in one stream while maintaining the remaining speakers in the other stream. Listen and observe the results below.</p>

 <div class="demo">
      <div class="audio">
        <h4>Reverberant Mixed Audio</h4>
        <audio controls>
          <source src="/files/demo/example_1/segment_mixch0.wav" type="audio/wav">
          Your browser does not support the audio element.
        </audio>
      </div>
      <img src="/files/demo/example_1/Spec_mix.png" alt="Spectrogram of Mixed Audio">
    </div>
    
    <div class="demo">
      <div class="audio">
        <h4>Separated Audio Stream 1</h4>
        <audio controls>
          <source src="/files/demo/example_1/segment_0.wav" type="audio/wav">
          Your browser does not support the audio element.
        </audio>
      </div>
      <img src="/files/demo/example_1/Spec_1.png" alt="Spectrogram of Stream 1">
    </div>
    
    <div class="demo">
      <div class="audio">
        <h4>Separated Audio Stream 2</h4>
        <audio controls>
          <source src="/files/demo/example_1/segment_1.wav" type="audio/wav">
          Your browser does not support the audio element.
        </audio>
      </div>
      <img src="/files/demo/example_1/Spec_2.png" alt="Spectrogram of Stream 2">
    </div>

    <div class="demo">
      <div class="audio">
        <h4>Embedding Sequence Indices based on Diarization Estimates</h4>
      </div>
      <img src="/files/demo/example_1/plot.png" alt="Embedding Sequence Indices">
    </div>
    
  </div>

</div>


<footer>
  <p>&copy; 2023 Hassan Taherian</p>
</footer>
