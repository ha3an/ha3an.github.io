---
layout: blank
title: "SSND Speech Separation Demo"
permalink: /projects/ssnd/
excerpt: "Demonstration of the SSND Speech Separation Model"
---

Welcome to the SSND demo page. Here, we showcase the capabilities of our state-of-the-art speech separation model.

## Demo Example 1

<div style="display: flex; flex-wrap: wrap; gap: 20px; justify-content: space-between; align-items: center;">

  <div style="flex: 1; min-width: 300px;">
    <p>Mixed Audio</p>
    <audio controls>
      <source src="/files/demo1/u1_mix.wav" type="audio/wav">
      Your browser does not support the audio element.
    </audio>
  </div>
  
  <img src="/files/demo1/spec_mix.png/spec_mix.png-1.png" alt="Spectrogram of Mixed Audio" style="width: 30%; min-width: 200px;">
  
  <div style="flex: 1; min-width: 300px;">
    <p>Separated Audio Stream 1</p>
    <audio controls>
      <source src="/files/demo1/u1_s1.wav" type="audio/wav">
      Your browser does not support the audio element.
    </audio>
  </div>
  
  <img src="/files/demo1/spec_mix.png/spec_mix.png-2.png" alt="Spectrogram of Stream 1" style="width: 30%; min-width: 200px;">
  
  <div style="flex: 1; min-width: 300px;">
    <p>Separated Audio Stream 2</p>
    <audio controls>
      <source src="/files/demo1/u1_s2.wav" type="audio/wav">
      Your browser does not support the audio element.
    </audio>
  </div>
  
  <img src="/files/demo1/spec_mix.png/spec_mix.png-3.png" alt="Spectrogram of Stream 2" style="width: 30%; min-width: 200px;">
  
</div>

<footer>
    <p>&copy; 2023 Hassan Taherian</p>
</footer>
