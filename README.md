# Project 1 Generative Text

Ebben Blake, eblake3@huskers.unl.edu

## Abstract

I plan to create text generated images using GPT-2. Creating a database of typed images (examples shown below) I plan to create other images. I have found a website that converts images into text, by colecting a range of photos I hope that I will be able to produce a handful of text that creates some sort of an image. Each peice will have a title and statment behind it that will be gerneated. Since these images will serve as a "art series" an artist statment will be needed. I will organize a set of artist statemnts so that the text generator can create some sort of personality for the artist as well as the "process" or materials used to make the art. For the final deliverable, I want to create photos that document "the gallerty" either by creating a space in unreal engine or therough adobe demisions. Using these photos of the gallery, I could make a fake page that belongs to the artist.

The first two images are set to a high resolution and the last one is set to a medium resolution

![image](https://user-images.githubusercontent.com/83600906/152912412-b9de9ab8-8f6a-4718-aee2-1a8479eb974e.png)

![image](https://user-images.githubusercontent.com/83600906/152912516-21a4713f-fd5e-40d5-a705-3aa85f1e3d29.png)




## Model/Data

  Orignally I used images found online and then converted them all of the photos to be 240 pixels wide and then ran all the fitted images into an ascii converter (http://www.springfrog.com/converter/ascii-text-art/index.php). The photos did not offere a lot of contrast or values for the progam to better understand, so creating images that could be intreptred as an image became diffcult. When first running through the generative text model, I used the 355M model as well as 124M due to technical problmes that arose. 

## Code

Your code for generating your project:
- training_code.py or training_code.ipynb - your training code
- generative_code.py or generative_code.ipynb - your generation code

## Results

  After converting the inital work, the recycled images, the outcome was an assortmetn of links, license, and verious repating text with a jumble of Ascii wokr that could slightly repersent soemthing. Knowing that the use of images that were so dense, while lacking a variety of value I know I had to change the taining data. I collectied a range of offical Ascii art that were listed on https://www.asciiart.eu/. I tried to collect a vareity of large and small typed images allowing for variety. I created a new database for the offical Ascii art and ran the code. I still encountered various links, football conmentary and random dialogue, but I did get a better outcome compared to my first datatbase.

## Technical Notes

Any implementation details or notes we need to repeat your work. 
- Does this code require other pip packages, software, etc?
- Does it run on some other (non-datahub) platform? (CoLab, etc.)

## Reference

References to any papers, techniques, repositories you used:
- Papers
  - [This is a paper](this_is_the_link.pdf)
- Repositories
- Blog posts
