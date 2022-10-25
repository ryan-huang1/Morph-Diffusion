# Morph Diffusion

### Novel video generation with user prompts + automated tensor image morphing
Morph Diffusion is a workflow that can create a seamless video based on a number of user inputs and prompts describing the envisioned video. It is called "Morph Diffusion" as it is using the v1.5 Stable Diffusion ckpt to generate images, then morphing between them to create a video output. It is required to use the premium teirs to run the notebook as it is extremely compute intenssive. 

---

## Results

https://user-images.githubusercontent.com/59319094/197673297-af666d1d-53c2-449a-8940-4411e5885e9b.mp4

https://user-images.githubusercontent.com/59319094/197673388-7aa06cf3-ff14-478f-96b3-b65a453bb9c3.mp4

---

## Usage

[Google Colab Notebook](https://colab.research.google.com/github/ryan-huang1/morph-diffusion/blob/main/morph-diffusion.ipynb) Note: A HuggingFace account + a valid write toekn is required for use of this notebook

It should be simple as going code block by block executing each one after another, some may take up to 2 hours to execute :)

---

## Assigmemt Questions

**Paste 3 screenshots that illustrate what your program does:**

**Describe the overall purpose of the program and briefly explain what the screenshots illustrate.**

**Describe the input and output of the program.**

The input of this program is the amount of photos and the content of said photos, hardcoded it takes the additional inputs of a background image + a image mask. The output of this program is a seamless video of the photos being morphed.

**Selection determines which parts of an algorithm are executed based on a condition being true or false. Paste a screenshot of selection(if) being used in your program:**

<img width="470" alt="Screen Shot 2022-10-24 at 11 23 30 PM" src="https://user-images.githubusercontent.com/59319094/197675015-066805d2-fce3-4092-a338-14c92093fd94.png">

**Describe the code segment related to selection and how it relates to the function of the program.** 

This code segment will take the user's input, then check if the number which was given is under 25. This repersents the number of frames, it rejects any over 25 as that many images would be prohibivly compute intesive.

**Capture and paste program code segments you developed for the program that contains a list being used to manage complexity in your program.**

Paste the first segment which shows how data have been stored in the list:

Paste the second segment which shows data in the list being used to fulfill the program’s purpose:

Identify the name of the list being used.

Describe what the data contained in the list represents in your program.

Explain how the selected list manages complexity in your program code by explaining why your program code could not be written, or how it would be written differently, if you did not use the list. 
