# SiamVGG
SiamVGG: Visual Tracking with Deeper Siamese Networks

Won 4th place in [VOT2018 Realtime Challenge](http://www.votchallenge.net/vot2018/)

We will soon release our training code and testing code.

The VOT2018 submision file is available. Feel free to try it! Download the pretrained data from [Google Drive](https://drive.google.com/file/d/13rx9kMJ1lwpics1Qr9_uKjloqLHfMaoU/view?usp=sharing) and follow the instruction to set up the test. (Partial of the code are modified from [SiamFC-pytorch](https://github.com/huanglianghua/siamfc-pytorch), thanks to Lianghua!)

[Demo](https://www.youtube.com/watch?v=cvP64cmiAmY)

 🔴Currently, I'm trying to combine the RPN module into it. After that, I'll release the training part and the SiamVGGRPN code.

The [zip file](https://drive.google.com/open?id=13aC_2stCEU0VoiIpp6wgudenUSVye74b) includes three json files: ilsvrc_vid.txt, youtube_final.txt, vot2018.txt. In our training process, we use ilsvrc_vid.txt and youtube_final.txt to train and vot2018.txt to verify the model.

If you find our project useful, please cite our technical report:

@inproceedings{Li2019SiamVGGVT,
  title={SiamVGG: Visual Tracking using Deeper Siamese Networks},
  author={Yuhong Li and Xiaofan Zhang},
  year={2019}
}

[arxiv version](https://arxiv.org/abs/1902.02804)
