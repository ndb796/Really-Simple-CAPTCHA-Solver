## Really Simple CAPTCHA Solver

### Setup
```
# Python 3이 설치되어 있지 않다면 설치합니다.
# pip3를 설치합니다.
sudo apt-get install python3-pip
# CAPTCHA Solver를 위한 라이브러리를 설치합니다.
sudo pip3 install opencv-python
sudo pip3 install numpy
sudo pip3 install imutils
sudo pip3 install sklearn
sudo pip3 install tensorflow
sudo pip3 install keras
```

### Extract single letters from CAPTCHA images
```
python3 extract_single_letters_from_captchas.py
```

### Train the neural network to recognize single letters
```
python3 train_model.py
```

### Use the model to solve CAPTCHA images
```
python3 solve_captchas_with_model.py
```

### References
* https://github.com/BenjaminWegener/CaptchaSolver
* https://medium.com/@ageitgey/how-to-break-a-captcha-system-in-15-minutes-with-machine-learning-dbebb035a710
