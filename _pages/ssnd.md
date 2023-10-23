<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>SSND Demo</title>
    <link rel="stylesheet" href="styles.css"> <!-- Link to your CSS file -->
</head>
<body>
    <header>
        <h1>SSND Demo</h1>
    </header>
    
    <section class="audio-demo">
        <h2>Mixed Audio</h2>
        <audio controls>
            <source src="files/demo1/u1_mix.wav" type="audio/wav">
            Your browser does not support the audio element.
        </audio>
    </section>
    
    <section class="separated-audio">
        <h2>Separated Audio Streams</h2>
        <audio controls>
            <source src="files/demo1/u1_s1.wav" type="audio/wav">
            Your browser does not support the audio element.
        </audio>
        <audio controls>
            <source src="files/demo1/u1_s2.wav" type="audio/wav">
            Your browser does not support the audio element.
        </audio>
    </section>
    
    <section class="spectrograms">
        <h2>Spectrograms</h2>
        <img src="files/demo1/spec_mix.png/spec_mix.png-2.png" alt="Spectrogram Stream 1">
        <img src="files/demo1/spec_mix.png/spec_mix.png-3.png" alt="Spectrogram Stream 2">
    </section>
    
    <footer>
        <p>&copy; 2023 Hassan Taherian</p>
    </footer>
</body>
</html>
