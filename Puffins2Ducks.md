Readme for Puffins to Ducks CycleGAN and Walt Whitman GPT-2

++PROJECT2++
Alex Mayben and Jeffrey Weekley

GPT-2 Text Generator based on the GPT-2 Playground (https://colab.research.google.com/github/ilopezfr/gpt-2/blob/master/gpt-2-playground_.ipynb)

Walt Whitman corpus was gleaned from Gutenberg.org, primarily from Leaves of Grass (available here: http://www.gutenberg.org/ebooks/1322)

This CycleGAN is based on the example Pix2Pix, available here:

https://www.tensorflow.org/tutorials/generative/pix2pix

The source images are taken from CalTech's dataset CUB_200_2011, available here:

http://www.vision.caltech.edu/visipedia/CUB-200-2011.html

PREPROCESSING THE IMAGES

The images were preprocessed using a Mac OS X Automator Script to scale the images up to 512xN then crop them to 256x256. The images were then concatenated using a simple python script. One set of the images had puffins on the left, the other ducks on the left. The scrip also segmented the images by clamping the colors to 8-bit color space.

The data were then loaded to Google Drive, and available here:

https://drive.google.com/file/d/1b04AAEw3HCow_6j5BDXcjKG06W9iyu4v/view?usp=sharing

It's necessary to mount the Google drive into the notebook before proceeding.
