---
layout: blank
title: "SSND Speech Separation Demo"
permalink: /projects/ssnd/
excerpt: "Demonstration of the SSND Speech Separation Model"
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
    flex: 1;
    text-align: center;
    margin-right: 20px;
  }
  img {
    max-width: 100%;
    height: auto;
    flex: 1;
  }
  footer {
    text-align: center;
    margin-top: 20px;
  }
</style>

<div class="container">
  <h1>SSND Speech Separation Demo</h1>
  <p>Welcome to the SSND demo page. Here, we showcase the capabilities of our state-of-the-art speech separation model.</p>

  <div class="demo-section">
    <h2>Demo Example 1</h2>

<p>This example is from "overlap_ratio_40.0_sil0.1_1.0_session9_actual39.9" recording from 95s to 115s. This example contrains 3-speaker overlap which has not been seen during training. </p>

    <div class="demo">
      <div class="audio">
        <p>Mixed Audio</p>
        <audio controls>
          <source src="/files/demo/example_1/segment_mixch0.wav" type="audio/wav">
          Your browser does not support the audio element.
        </audio>
      </div>
      <img src="/files/demo/example_1/Spec_mix.png" alt="Spectrogram of Mixed Audio">
    </div>
    
    <div class="demo">
      <div class="audio">
        <p>Separated Audio Stream 1</p>
        <audio controls>
          <source src="/files/demo/example_1/segment_0.wav" type="audio/wav">
          Your browser does not support the audio element.
        </audio>
      </div>
      <img src="/files/demo/example_1/Spec_1.png" alt="Spectrogram of Stream 1">
    </div>
    
    <div class="demo">
      <div class="audio">
        <p>Separated Audio Stream 2</p>
        <audio controls>
          <source src="/files/demo/example_1/segment_1.wav" type="audio/wav">
          Your browser does not support the audio element.
        </audio>
      </div>
      <img src="/files/demo/example_1/Spec_2.png" alt="Spectrogram of Stream 2">
    </div>

    <div class="demo">
      <div class="audio">
        <p>Embedding Sequence Indices based on Diarization Estimates </p>
       
      </div>
      <img src="/files/demo/example_1/plot.png" alt="Spectrogram of Stream 1">
    </div>
    
  </div>
</div>

<footer>
  <p>&copy; 2023 Hassan Taherian</p>
</footer>
