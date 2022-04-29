---
layout: music-enhancement
title: "Music Enhancement"
permalink: /music-enhancement/
samples:
  val:
    - 1133
    - 1151
    - 1860
    - 1901
    - 1931
    - 2249
    - 2525
    - 371
    - 432
    - 736
    - 815
    - 826
    - 836
    - 908
    - 92
  test:
    - 1194
    - 3017
    - 3187
    - 4419
    - 5829
real_world_samples:
  - noisy: ../assets/youtube4_aug.wav
    enhanced: ../assets/youtube4_enhanced.wav
    source: https://www.youtube.com/watch?v=7gTYISq4-4E
    source_name: Dance Monkey - Street Musician Karsten Belt (Saxophone)
  - noisy: ../assets/youtube2_aug.wav
    enhanced: ../assets/youtube2_enhanced.wav
    source: https://www.youtube.com/watch?v=liDQRLYu2EM
    source_name: Top 10 Street Piano Performances
  - noisy: ../assets/youtube6_aug.wav
    enhanced: ../assets/youtube6_enhanced.wav
    source: https://www.youtube.com/watch?v=y5fRqPk04Nk
    source_name: People Singing In Front Of Other People In Public Compilation
---
# Music Enhancement via Image Translation and Vocoding
## Nikhil Kandpal, Oriol Nieto, Zeyu Jin
<h3 style="text-align:center;"><a href="">Paper</a> &nbsp; &nbsp; &nbsp; <a href="https://github.com/nkandpa2/music_enhancement">Code</a></h3>
<p style="text-align:center;"><img src="../assets/music_enhancement_figure.jpg" alt="Mel2Mel+Diffwave Model Overview" style="width:90%;"/></p>

### Abstract
Consumer-grade music recordings such as those captured by mobile devices typically contain distortions in the form of background noise, reverb, and microphone-induced EQ. This paper presents a deep learning approach to enhance low-quality music recordings by combining (i) an image-to-image translation model for manipulating audio in its mel-spectrogram representation and (ii) a music vocoding model for mapping synthetically generated mel-spectrograms to perceptually realistic waveforms. We find that this approach to music enhancement outperforms baselines which use classical methods for mel-spectrogram inversion and an end-to-end approach directly mapping noisy waveforms to clean waveforms. Additionally, in evaluating the proposed method with a listening test, we analyze the reliability of common audio enhancement evaluation metrics when used in the music domain.
