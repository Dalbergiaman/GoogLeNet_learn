# GoogLeNet_learn
尝试调整GoogLeNet
![image](https://github.com/user-attachments/assets/1c709e1b-4732-4e4c-86c9-4a9285b121cd)
框架由inception和auxclassifer共同组成
* 在尝试搭建的过程中，将第一层7*7卷积替换成了两个3*3卷积，识别效率提升的较快。
* 后续在调整学习率时发现，0.001的学习率可以快速提高效果。
* 在auxclassifer的全连接层前添加dropout效果不好
