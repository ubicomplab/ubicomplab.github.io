---
title: 'Whosecough: In-the-Wild Cougher Verification Using Multitask Learning'
authors: [whitehill, garison, patel]
conference: IEEE International Conference on Acoustics, Speech and Signal Processing (ICASSP), 2020
date: 2020-05-07
pdf: /pdfs/Whosecough.pdf
thumbnail: /images/pubs/whosecough.png
caption: Whosecough uses a patient's unique cough signature to determine when someone who coughs, who is coughing.
citation: |
  Whitehill, Matt, Jake Garrison, and Shwetak Patel. "Whosecough: In-the-Wild Cougher Verification Using Multitask Learning." ICASSP 2020-2020 IEEE International Conference on Acoustics, Speech and Signal Processing (ICASSP). IEEE, 2020.
abstract: |
  Current automatic cough counting systems can determine how many coughs are present in an audio recording. However, they cannot determine who produced the cough. This limits their usefulness as most systems are deployed in locations with multiple people (i.e., a smart home device in a four-person home). Previous models trained solely on speech performed reasonably well on forced coughs [1]. By incorporating coughs into the training data, the model performance should improve. However, since limited natural cough data exists, training on coughs can lead to model overfitting. In this work, we overcome this problem by using multitask learning, where the second task is speaker verification. Our model achieves 82.15% classification accuracy amongst four users on a natural, in-the-wild cough dataset, outperforming human evaluators on average by 9.82%.
bibtex: |
  @INPROCEEDINGS{9053268,
  author={M. {Whitehill} and J. {Garrison} and S. {Patel}},
  booktitle={ICASSP 2020 - 2020 IEEE International Conference on Acoustics, Speech and Signal Processing (ICASSP)}, 
  title={Whosecough: In-the-Wild Cougher Verification Using Multitask Learning}, 
  year={2020},
  volume={},
  number={},
  pages={896-900}
  }
---