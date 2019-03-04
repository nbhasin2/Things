# Things
Simple bash / mobile / etc. related things that one uses and forgets. 

## iOS
### 1. Transform 3D
- https://guides.codepath.com/ios/Using-Perspective-Transforms#step-4-animating-the-transform 
- http://radar.oreilly.com/2013/07/rotating-a-uiview-in-3d.html
- https://stackoverflow.com/questions/5833488/how-to-disable-calayer-implicit-animations
- https://stackoverflow.com/questions/34438889/how-to-do-transforms-on-a-calayer
- https://stackoverflow.com/questions/29879314/how-to-create-custom-flip-animation-using-uiview
- https://stackoverflow.com/questions/9656071/how-to-flip-a-uiview-around-the-x-axis-while-simultaneously-switching-subviews
- https://stackoverflow.com/questions/6531332/how-to-rotate-an-uiimageview-with-catransform3drotate-make-an-effect-like-door-o

## ANDROID
### 1. Setting up adb path
In case your don't have bash profile 
```
touch .bash_profile
```
If you already have bash profile 
```
echo 'source ~/.bashrc' >> ~/.bash_profile
echo 'PATH=$PATH:$HOME/[PATH TO YOUR platform-tools]' >> ~/.bashrc
echo 'ANDROID_HOME=$HOME/[[PATH TO YOUR Android SDK]]' >> ~/.bashrc
```
