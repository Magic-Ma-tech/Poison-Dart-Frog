

![image](poison-dart.png)


#Poison Dart Frog Clean-label Backdoor Attack

This is the official implementation of the paper: Poison Dart Frog: A Clean-Label Attack with Low Poisoning Rate and High Attack Success Rate Using Only One Piece of Information


##Requirements
####
- Python >= 3.6
- PyTorch >= 1.10.1
- TorchVisison >= 0.11.2
- OpenCV >= 4.5.3


#Get Started Quickly
Please run the training process for the decoder
```python
python decode_train.py
```

Please run the training process for the encoder

```python
python encode_train.py
```

"Running an Assessment on the Impact of an Attack
```python
python test_exp.py
```


