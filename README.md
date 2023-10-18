# TMHINT-QI VoiceMOS2023

This repository aims to publically share the training and test data of TMHINT-QI version II, which was used as one of the tracks in VoiceMOS Challenge 2023. 

## TMHINT-QI version II 
The TMHINT-QI version II  is the updated version of the original <a href="https://drive.google.com/file/d/1TMDiz6dnS76hxyeAcCQxeSqqEOH4UDN0/view?usp=sharing" target="_blank">TMHINT-QI</a> dataset. The version I dataset has no unseen scenarios for the evaluation set. Therefore, the version II dataset aims to accommodate such concerns by modifying the training set and providing the unseen systems for the evaluation set. 

### Training Set
The training set consists of four scene environments: clean, babble, white, and pink noises. It also consists of noisy, clean, and enhanced utterances from four systems, including Minimum-mean Square Error (MMSE), Deep Denoising Autoencoder (DDAE), Fully Convolutional Network (FCN), and Transformer. The training set consists of 11053 utterances with corresponding quality (0-5) and intelligibility (0-10) scores.

Please refer to the following <a href="https://www.dropbox.com/s/yc6yhpjb92xa5yy/VOICEMOS2023_DISTRO.tar.gz?dl=0" target="_blank">link</a> for the updated split for the training set, and please download the corresponding utterances in the following <a href="https://drive.google.com/file/d/1TMDiz6dnS76hxyeAcCQxeSqqEOH4UDN0/view?usp=sharing" target="_blank">link</a>. 

### Test Set
The TMHINT-QI version II test set consists of five scene environments: clean, babble, white, and pink noises, and street noise for the unseen environment. It also consists of noisy, clean, and enhanced utterances consisting of three seen enhanced systems (FCN, MMSE, and Tranformer) and two unseen enhanced systems (Conformer-based Metric Generative Adversarial Network (CMGAN) and DEMUCS). In total, the test set of TMHINT-QI version II consists 1960 utterances.

The corresponding test set of TMHINT-QI version II can be downloaded at the following <a href="https://drive.google.com/drive/u/2/folders/1d8-LBrJieL0YCaqXGoBegYWIu2b0CwNz" target="_blank">link</a>. In addition, the corresponding utterances can be downloaded 
<a href="https://drive.google.com/file/d/10_1JbEsxKPYZJLDXMeMkcjLHkbDQt84w/view" target="_blank">here</a>. 

### Current benchmark score
![Capture](https://github.com/dhimasryan/TMHINT-QI_VoiceMOS2023/assets/2504723/becdb7e7-87c0-42cd-9c91-5fbd915942df)

From the VoiceMOS Challenge 2023, our system (T02), which is based on the improved version of <a href="https://github.com/dhimasryan/MOSA-Net-Cross-Domain" target="_blank">MOSA-Net</a> achieved the top performer among the other systems. The detail explanation regarding our systems can be found in the following <a href="https://arxiv.org/pdf/2309.12766.pdf" target="_blank">link</a>  

### Citation ###

Please kindly cite our <a href="https://arxiv.org/pdf/2309.12766.pdf" target="_blank">paper</a>, if you use the dataset in your research.
```js
@misc{zezario2023study,
      title={A Study on Incorporating Whisper for Robust Speech Assessment}, 
      author={Ryandhimas E. Zezario and Yu-Wen Chen and Szu-Wei Fu and Yu Tsao and Hsin-Min Wang and Chiou-Shann Fuh},
      year={2023},
      eprint={2309.12766},
      archivePrefix={arXiv},
      primaryClass={eess.AS}
}
```
### Acknowledgment
<a href="https://bio-asplab.citi.sinica.edu.tw/index.html" target="_blank">BioASP Lab, Academia Sinica</a>

<a href="https://voicemos-challenge-2023.github.io/" target="_blank">VoiceMOS Challenge Organizers 2023</a>
