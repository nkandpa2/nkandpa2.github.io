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
---
# Music Enhancement via Image Translation and Vocoding
## Nikhil Kandpal, Oriol Nieto, Zeyu Jin

### Abstract
Consumer-grade music recordings such as those captured by mobile devices typically contain distortions in the form of background noise, reverb, and microphone-induced EQ. This paper presents a deep learning approach to enhance low-quality music recordings by combining (i) an image-to-image translation model for manipulating audio in its mel-spectrogram representation and (ii) a music vocoding model for mapping synthetically generated mel-spectrograms to perceptually realistic waveforms. We find that this approach to music enhancement outperforms baselines which use classical methods for mel-spectrogram inversion and an end-to-end approach directly mapping noisy waveforms to clean waveforms. Additionally, in evaluating the proposed method with a listening test, we analyze the reliability of common audio enhancement evaluation metrics when used in the music domain.
