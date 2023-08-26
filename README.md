# Signal Creator
## Description:
A very well utilized app that allows you to generate images from sounds and generate sounds from images. There are two modes, one is generating images from sound files (.wav) and the other is generating sounds from image files (.png). You can toggle between these two modes, each mode has its own set of configurations that you can edit and modify to your liking. 

### Features:
Some features include the sound playback buttons, export single/all files, import single/all files, a config file to save all of your settings, file clearer, and an image displayer to display the file that is being selected or used.

## How to use:
To start you will begin by setting which ever mode you'd like from the file menu tab, from there you will be brought up with all of the mode's UI. Each mode usually has the option to clear files which simply means to clear them from the listbox. And using the file menu tab you can toggle between the 2 modes.

### Sound to Image Mode:
For Sound to Image Mode, you can import either one file or a whole directory of them (.wav files only as any other format are not supported), from there you can select the sound files inside the listbox to view the preview or result of the image generation.
![VOTV Signal Creator 8_26_2023 3_05_24 AM](https://github.com/SquareZeb/Signal-Creator/assets/136224084/ca8e217c-5baa-4497-9415-df3aa233c005)

#### Changing Image Resolutions:
You also have the option to set the custom resolution of the output image when its exported, under file menu tab it will open up a small popup which will prompt you to enter in the custom values for the X and Y sizes of the output image. After hitting save, you will want to hit the Refresh button and reselect the file in the listbox to update its new custom resolution. Now do note that when setting higher resolution counts it will eat up more resources and will have to process a lot more, meaning the software will run significantly slower on higher resolution counts.
‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎ ‎ ‎ ‎‎‎ ‎ ‎ ‎‎‎ ‎ ‎ ‎‎‎ ‎ ‎ ‎‎‎ ‎ ‎ ‎‎‎ ‎ ‎ ‎‎‎ ‎ ‎ ‎‎‎ ‎ ‎ ‎‎‎ ‎ ‎ ‎‎‎ ‎ ‎ ‎‎‎ ‎ ‎ ‎‎‎ ‎ ‎ ‎‎‎ ‎ ‎ ‎‎‎ ‎ ‎ ‎‎‎ ‎ ‎ ‎‎‎ ‎ ‎ ‎‎‎ ‎ ‎ ‎‎‎ ‎ ‎ ‎‎‎ ‎ ‎ ‎‎‎ ‎ ‎ ‎‎‎ ‎ ‎ ‎‎‎ ‎ ‎ ‎‎‎ ‎ ‎ ‎‎‎ ‎ ‎ ‎‎‎ ‎ ‎ ‎‎‎ ‎ ‎ ‎‎‎ ‎ ‎ ‎‎‎ ‎ ‎ ‎‎‎ ‎ ‎ ‎‎‎ ‎ ‎ ‎‎‎ ‎ ‎ ‎‎‎ ‎ ‎ ‎‎‎ ‎ ‎ ‎‎‎ ‎ ‎ ‎‎‎ ‎ ‎ ‎‎‎ ‎ ‎ ‎‎‎ ‎ ‎ ‎‎‎ ‎ ‎ ‎‎‎ ‎ ‎ ‎‎‎ ‎ ‎ ‎‎‎ ‎ ‎ ‎‎‎ ‎ ‎ ‎‎‎ ‎ ‎ ‎‎‎ ‎ ‎ ‎‎ ‎ ‎ ‎‎‎ ‎ ‎ ‎‎‎ ‎ ‎‎ ‎ ‎ ‎‎‎ ‎ ‎ ‎‎‎ ‎ ‎ ‎‎‎ ‎ ‎ ‎‎‎ ‎ ‎ ‎‎‎ ‎ ‎ ‎‎‎ ‎ ‎ ‎‎‎ ‎ ‎ ‎‎‎ ‎ ‎ ‎‎‎ ‎ ‎ ‎‎‎ ‎ ‎ ‎‎‎ ‎ ‎ ‎‎‎ ‎ ‎ ‎‎‎ ‎ ‎ ‎‎‎ ‎ ‎ ‎‎‎ ‎ ‎ ‎‎‎ ‎ ‎ 
![Change Output Image Resolution 8_26_2023 3_05_50 AM](https://github.com/SquareZeb/Signal-Creator/assets/136224084/2edd75b9-33e5-4d7f-9afb-954fa99fb9bb)

### Image to Sound Mode:
For Image to Sound Mode, you first must set the different values for frequency range, pixel range, pitch range, and audio stretch factor, this is required for generating and importing the image files. After you've set the values to your liking, you can import either one file or a whole directory of them: (.png files, they must be in a square shape because if in any other shape will cause the generation of the sound file to become corrupted, and it must have a resolution lower than 200x200 pixels as anything higher than this will cause the software to crash and become frozen).
![VOTV Signal Creator 8_26_2023 3_07_11 AM](https://github.com/SquareZeb/Signal-Creator/assets/136224084/cd2fe18d-9b03-4eff-baa2-a732123dcdfd)

#### Changing Sound Factor Ranges:
You also have the option to change the ranges or values of the sliders to better fit your customizations, like changing the resolution under the file tab, once clicked will bring up a small popup prompting you to enter in all the details. After saving said details you will then hit refresh to update the sliders.‎‎‎‎‎‎
‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎‎ ‎ ‎ ‎‎‎ ‎ ‎ ‎‎‎ ‎ ‎ ‎‎‎ ‎ ‎ ‎‎‎ ‎ ‎ ‎‎‎ ‎ ‎ ‎‎‎ ‎ ‎ ‎‎‎ ‎ ‎ ‎‎‎ ‎ ‎ ‎‎‎ ‎ ‎ ‎‎‎ ‎ ‎ ‎‎‎ ‎ ‎ ‎‎‎ ‎ ‎ ‎‎‎ ‎ ‎ ‎‎‎ ‎ ‎ ‎‎‎ ‎ ‎ ‎‎‎ ‎ ‎ ‎‎‎ ‎ ‎ ‎‎‎ ‎ ‎ ‎‎‎ ‎ ‎ ‎‎‎ ‎ ‎ ‎‎‎ ‎ ‎ ‎‎‎ ‎ ‎ ‎‎‎ ‎ ‎ ‎‎‎ ‎ ‎ ‎‎‎ ‎ ‎ ‎‎‎ ‎ ‎ ‎‎‎ ‎ ‎ ‎‎‎ ‎ ‎ ‎‎‎ ‎ ‎ ‎‎‎ ‎ ‎ ‎‎‎ ‎ ‎ ‎‎‎ ‎ ‎ ‎‎‎ ‎ ‎ ‎‎‎ ‎ ‎ ‎‎‎ ‎ ‎ ‎‎‎ ‎ ‎ ‎‎‎ ‎ ‎ ‎‎‎ ‎ ‎ ‎‎‎ ‎ ‎ ‎‎‎ ‎ ‎ ‎‎‎ ‎ ‎ ‎‎‎ ‎ ‎ ‎‎‎ ‎ ‎ ‎‎ ‎ ‎ ‎‎‎ ‎ ‎ ‎‎‎ ‎ ‎‎ ‎ ‎ ‎‎‎ ‎ ‎ ‎‎‎ ‎ ‎ ‎‎‎ ‎ ‎ ‎‎‎ ‎ ‎ ‎‎‎ ‎ ‎ ‎‎‎ ‎ ‎ ‎‎‎ ‎ ‎ ‎‎‎ ‎ ‎ ‎‎‎ ‎ ‎ ‎‎‎ ‎ ‎ ‎‎‎ ‎ ‎ ‎‎‎ ‎ ‎ ‎‎‎ ‎ ‎ ‎‎‎ ‎ ‎ ‎‎‎ ‎ ‎ ‎‎‎ ‎ ‎ ‎‎‎ ‎ ‎ ‎‎‎ ‎ ‎ ‎‎‎ 
![Change Sound Factor Ranges 8_26_2023 3_07_42 AM](https://github.com/SquareZeb/Signal-Creator/assets/136224084/55b3335e-ed6a-4bf1-988a-1bd0cb06017c)

## Download Link:
Download from the releases tab from the very right --------------------------------------------------------------------------------------------------->
If you can't get to it, use this link to download the latest:
https://github.com/SquareZeb/Signal-Creator/releases/tag/2.0



