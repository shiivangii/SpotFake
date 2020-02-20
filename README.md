# SpotFake
This repository contains the code for the paper titled: SpotFake: A multimodal framework for fake news detection published in IEEE BigMM 2019 (Best Poster Award). 

The propose architecture aims to detect whether a given news article is real or fake. It does not take into account any
other sub-task in the detection process.

The prime novelty of SpotFake is to incorporate the power of language models, i.e. Bidirectional Encoder Representations from Transformers (BERT) to incorporate contextual information. 

The image features are learned from VGG-19 pre-trained on ImageNet dataset.

##
[Link to Paper](http://precog.iiitd.edu.in/pubs/SpotFake-IEEE_BigMM.pdf)

[Link to Presentation](https://docs.google.com/presentation/d/1sFtwYI2Lnpl1XtYtaFpUcj-D9o6JJP5DS8zyL_2w3Fs/edit?usp=sharing)

[Link to Poster]( https://drive.google.com/open?id=12UUWQ-L18qdATligfPh7DEQw2ktOC0u0)



## Dataset:
1. Twitter MediaEval 2016 (media eval 2016)
2. Weibo (WeiboRumorSet)
All the necessary libraries used in implementation is listed in 'environment.yml' file.

# Citation
If this code or dataset is useful for your research, please cite our paper:


     @inproceedings{SpotFake,
      author ={Singhal, Shivangi and Shah, Rajiv and Chakraborty, Tanmoy and Kumaraguru, Ponnurangam and Shin'ichi Satoh},
      title = {SpotFake: A Multimodal Framework for Fake News Detection},
      booktitle = {IEEE BigMM},
     year={2019},
     location={Singapore},
     url={http://precog.iiitd.edu.in/pubs/SpotFake-IEEE_BigMM.pdf},
     keywords={Multimodal Fake News Detection, Machine Learning, Deep Learning}
     }

### Note
We also created [SpotFake+]( https://github.com/shiivangii/SpotFakePlus ), an advanced version of SpotFake that deals with long (full) length articles. The paper got accepted as a short paper in AAAI 2020.

