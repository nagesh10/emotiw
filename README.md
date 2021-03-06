# EmotiW - emotion recognition from video

| | | | | | |
| :-------------: |:-------------:|:-------------:|:-------------:|:-------------:|:-------------:|
| <figure> <img src="2017/examples/angry.png" height="128"><figcaption>Angry</figcaption></figure> | <figure> <img src="2017/examples/fear.png" height="128"><figcaption>Fear</figcaption></figure> | <figure> <img src="2017/examples/happy.png" height="128"><figcaption>Happy</figcaption></figure> | <figure> <img src="2017/examples/neutral.png" height="128"><figcaption>Neutral</figcaption></figure> | <figure> <img src="2017/examples/sad.png" height="128"><figcaption>Sad</figcaption></figure> | <figure> <img src="2017/examples/surprise.png" height="128"><figcaption>Surprise</figcaption></figure> |


Code for Emotion Recognition in the Wild (EmotiW) challenge.

For EmotiW 2017 code please see folder [2017](https://github.com/bknyaz/emotiw/tree/master/2017).

## Description

cd to folder 2017, then run the code as: ```python3 submission5.py```

The code will download all necessary features precomputed using our models, train emotion classification models and predict emotions on the test set.

Test accuracy is 60.03% (second place).

### Requirements
- Python3 (necessary to load features saved in python3)

### Test environment
- Ubuntu 14.04 LTS

## References

[Challenge website](https://sites.google.com/site/emotiwchallenge/home)

Paper:
[`Convolutional neural networks pretrained on large face recognition datasets for emotion classification from video`](https://arxiv.org/abs/1711.04598) accepted to the 1st	Workshop on Large-scale	Emotion
Recognition	and	Analysis. IEEE	International	Conference	on	Automatic	Face	and	Gesture
Recognition	2018, Xi'an, China

If you use our code or features in your work, please cite our paper as following:
```
@inproceedings{knyazev2018leveraging,
  title={Leveraging large face recognition data for emotion classification},
  author={Knyazev, Boris and Shvetsov, Roman and Efremova, Natalia and Kuharenko, Artem},
  booktitle={Automatic Face \& Gesture Recognition (FG 2018), 2018 13th IEEE International Conference on},
  pages={692--696},
  year={2018},
  organization={IEEE}
}
```
