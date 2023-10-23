---
layout: single
title: "SSND Speech Separation Demo"
permalink: /projects/ssnd/
excerpt: "Demonstration of the SSND Speech Separation Model"
---

<style>
  .demo-container {
    display: flex;
    flex-wrap: wrap;
    gap: 20px;
    justify-content: space-between;
    align-items: center;
  }
  .audio-container {
    flex: 1;
    min-width: 300px;
    text-align: center;
  }
  .spectrogram {
    width: 100%;
    max-width: 500px;
  }
  footer {
    width: 100%;
    text-align: center;
    margin-top: 20px;
  }
</style>

Welcome to the SSND demo page. Here, we showcase the capabilities of our state-of-the-art speech separation model.

## Demo Example 1

<div class="demo-container">

  <div class="audio-container">
    <p>Mixed Audio</p>
    <audio controls>
      <source src="/files/demo1/u1_mix.wav" type="audio/wav">
      Your browser does not support the audio element.
    </audio>
  </div>
  
  <img class="spectrogram" src="/files/demo1/spec_mix.png/spec_mix.png-1.png" alt="Spectrogram of Mixed Audio">
  
  <div class="audio-container">
    <p>Separated Audio Stream 1</p>
    <audio controls>
      <source src="/files/demo1/u1_s1.wav" type="audio/wav">
      Your browser does not support the audio element.
    </audio>
  </div>
  
  <img class="spectrogram" src="/files/demo1/spec_mix.png/spec_mix.png-2.png" alt="Spectrogram of Stream 1">
  
  <div class="audio-container">
    <p>Separated Audio Stream 2</p>
    <audio controls>
      <source src="/files/demo1/u1_s2.wav" type="audio/wav">
      Your browser does not support the audio element.
    </audio>
  </div>
  
  <img class="spectrogram" src="/files/demo1/spec_mix.png/spec_mix.png-3.png" alt="Spectrogram of Stream 2">
  
</div>

<footer>
  <p>&copy; 2023 Hassan Taherian</p>
</footer>
