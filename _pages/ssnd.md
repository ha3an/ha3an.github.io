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
  }
  h1, h2 {
    font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
  }
  .container {
    max-width: 1200px;
    margin: auto;
    overflow: auto;
    padding: 0 20px;
  }
  .demo {
    display: flex;
    flex-wrap: wrap;
    gap: 20px;
    justify-content: space-between;
    align-items: center;
  }
  .audio {
    flex: 1;
    min-width: 250px;
    text-align: center;
  }
  img {
    max-width: 100%;
    height: auto;
  }
  footer {
    text-align: center;
    margin-top: 20px;
  }
</style>

<div class="container">
  <h1>SSND Speech Separation Demo</h1>
  <p>Welcome to the SSND demo page. Here, we showcase the capabilities of our state-of-the-art speech separation model.</p>

  <h2>Demo Example 1</h2>

  <div class="demo">
    <div class="audio">
      <p>Mixed Audio</p>
      <audio controls>
        <source src="/files/demo1/u1_mix.wav" type="audio/wav">
        Your browser does not support the audio element.
      </audio>
    </div>
    <img src="/files/demo1/spec_mix.png/spec_mix.png-1.png" alt="Spectrogram of Mixed Audio">
    
    <div class="audio">
      <p>Separated Audio Stream 1</p>
      <audio controls>
        <source src="/files/demo1/u1_s1.wav" type="audio/wav">
        Your browser does not support the audio element.
      </audio>
    </div>
    <img src="/files/demo1/spec_mix.png/spec_mix.png-2.png" alt="Spectrogram of Stream 1">
    
    <div class="audio">
      <p>Separated Audio Stream 2</p>
      <audio controls>
        <source src="/files/demo1/u1_s2.wav" type="audio/wav">
        Your browser does not support the audio element.
      </audio>
    </div>
    <img src="/files/demo1/spec_mix.png/spec_mix.png-3.png" alt="Spectrogram of Stream 2">
  </div>
</div>

<footer>
  <p>&copy; 2023 Hassan Taherian</p>
</footer>
