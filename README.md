Hi, I am from Mechanical Engineering, and this is my first proper ML/DL project.
I started everything from scratch — Python, NumPy, ML basics, PyTorch, CNNs — while doing my core mechanical work in parallel.
It was honestly a big learning curve for me, but I gave my best to understand the concepts step-by-step.

I wasn't able to complete the RNN assignment earlier, but I am improving and really want a chance to be part of this project. I will definitely prove myself with consistent effort.

I did use ChatGPT for guidance, but I did not blindly copy.
I went through every line, understood what each part does, and learned things slowly in my own way.
This README is written honestly, and reflects my actual understanding# Roshith_DrawAi_task_1

For Part 1, I built a very simple CNN using PyTorch video :

 Steps I did:

Loaded CIFAR-10 dataset

Converted images to tensors

Made a simple CNN with two convolution layers

Wrote a basic training loop (forward → loss → backward → optimizer step)

Evaluated test accuracy


What a dataset is (images + labels)

Training vs testing

What a model does (predicts classes)

What loss means (how wrong the model is)

How gradient descent updates weights

Basic CNN structure: conv → relu → pooling → flatten → fully connected

For Part 2, I made small improvements to the baseline model.
I kept things simple because I am still learning everything from scratch, but I wanted to show clear improvement and understanding.
 What I improved:
1️ Data Augmentation

I added:

RandomHorizontalFlip()

RandomCrop()

This makes the model see slightly different images each epoch, which reduces overfitting and improves generalization.

 Added ONE extra convolution layer

I expanded my CNN from 2 conv layers → 3 conv layers.
More conv layers help the model learn better patterns (edges → shapes → higher-level features).

Augmentation prevents memorization

Deeper CNN learns richer features

Both help increase test accuracy

I am from Mechanical Engineering, and I am learning ML/DL from zero while managing my core subjects. It has been challenging but I genuinely enjoyed doing this assignment because I finally understood how a CNN works internally.

I know I couldn't complete the RNN task earlier, but I am improving and really want an opportunity to work with the team. I promise that if I get the chance, I will put consistent effort, learn properly, and contribute my best.

Thank you for reviewing my work.
It really means a lot.

🙏 If any mistakes are there, I am ready to correct them. I want to grow and learn.
