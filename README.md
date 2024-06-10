#  Instrumental Sounds and Speech Perception: Playing Around with Sound

LIGN 168 Final Project

This is a final project for LIGN 168:Computational Speech Processing at UCSD. This tool works to replace an input text stream with instrumental audio which is roughly correlated to specific speech sounds.

The main software my project involved was the forced aligner charsiu. I used the textless pretrained model and ran it through google’s Colab. I used python to build my tool and used the following libraries: librosa, pydub, torch torchvision torchaudio, datasets transformers, praatio librosa, g2p_en g2pM, sounddevice, wavio, scipy, libsndfile1, os, sys, and itertools. 

To run this project you will need to install the textless forced aligner from charsiu. This step is included in the py file.

You will also need a folder of the instrumental sounds used to create the instrumental audio or the speech sounds for the speech sounds version. You can download the 'sounds' folder from github or use this link. 

https://drive.google.com/drive/folders/1q64gynZQsHGRACCGduampWhV9WTJrx_4?usp=sharing

Note that you will need to change the path to the audio files to have the code access the right file. 


