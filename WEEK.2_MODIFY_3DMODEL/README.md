## Pre-arrange the model


### TOOLS
- Meshmixer
- bilibili

### STEPS

1. export model from Realityscan, in the file of obj
2. save it in whole English path（otherwise the model and its texture will turn red in Meshmixer)
3. import the model in Meshmixer
4. The tutorial on how to use this software. Click on the picture to go to the video page.

<div align="center">
  <a href="https://www.bilibili.com/video/BV1nt4y1z7PS" target="_blank">
    <img src="https://github.com/Red0tt/How-To-Make-Anything-/blob/main/WEEK.2_MODIFY_3DMODEL/video_image/1da3063f2a24bfb6e60eca8b3569d4078461fa04.png" 
         alt="3D扫描演示" 
         style="width: 500px; height: auto; border: 2px solid #f0f0f0;">
  </a>
  <br>
  <strong>Click on the picture to go to the video page(bilibili).</strong>
</div>

<div align="center">
  <a href="https://www.bilibili.com/video/BV1ty4y1i7Y8" target="_blank">
    <img src="https://github.com/Red0tt/How-To-Make-Anything-/blob/main/WEEK.2_MODIFY_3DMODEL/video_image/aedfaec0ffb81385b01f2a98097a0f25eb946250.jpg" 
         alt="3D扫描演示" 
         style="width: 500px; height: auto; border: 2px solid #f0f0f0;">
  </a>
  <br>
  <strong>Click on the picture to go to the video page(bilibili).</strong>
</div>



After gaining a basic understanding from the tutorial, i import a textured model into Meshmixer. 


<img src="https://github.com/Red0tt/How-To-Make-Anything-/blob/main/WEEK.2_MODIFY_3DMODEL/meshmixer/m1.png" width="25%"/>
First, click on this shader to hide the texture. You can see that the model is quite uneven and bumpy, with the bottom slightly connected to a base surface, and it is hollow. There is also a missing section on the head. 

<img src="https://github.com/Red0tt/How-To-Make-Anything-/blob/main/WEEK.2_MODIFY_3DMODEL/meshmixer/m2.png" width="25%"/>
Therefore, i start by using the plane cut tool under the edit menu to extract the necessary part. 

<img src="https://github.com/Red0tt/How-To-Make-Anything-/blob/main/WEEK.2_MODIFY_3DMODEL/meshmixer/m3.png" width="25%"><img src="https://github.com/Red0tt/How-To-Make-Anything-/blob/main/WEEK.2_MODIFY_3DMODEL/meshmixer/m4.png" width="25%"/>

To repair the gap on the head, we use a sphere from the meshmix library, adjust and move it to fill the missing area on the head, and perform a Boolean operation with the original model to make it appear more complete.

<img src="https://github.com/Red0tt/How-To-Make-Anything-/blob/main/WEEK.2_MODIFY_3DMODEL/meshmixer/m5.png" width="25%"/>

As for the base, since I’m not confident in shaping the current form into a proper base, I also used a cylinder placed outside the model. This is because only this way allows adjusting the height of the cylinder. Finally, I moved it beneath the model. At this point, our Kabi model and the cylinder remain separate, and we can later perform a Boolean union.


<img src="https://github.com/Red0tt/How-To-Make-Anything-/blob/main/WEEK.2_MODIFY_3DMODEL/meshmixer/m6.png" width="25%"><img src="https://github.com/Red0tt/How-To-Make-Anything-/blob/main/WEEK.2_MODIFY_3DMODEL/meshmixer/m7.png" width="25%">

For the other uneven and bumpy areas, I tried three repair methods.
First, using the select tool followed by erase & fill. 


<img src="https://github.com/Red0tt/How-To-Make-Anything-/blob/main/WEEK.2_MODIFY_3DMODEL/meshmixer/m8.png" width="25%"/>

Second, selecting and then deleting, followed by repairing with the inspector under the analysis menu. 


<img src="https://github.com/Red0tt/How-To-Make-Anything-/blob/main/WEEK.2_MODIFY_3DMODEL/meshmixer/m9.png" width="25%"/>

Third, using the sculpt tool, which is more suitable when the first two methods fail to achieve the desired shape.


<img src="https://github.com/Red0tt/How-To-Make-Anything-/blob/main/WEEK.2_MODIFY_3DMODEL/meshmixer/m10.png" width="25%"/>


The final repaired model is shown in the figure below.

<img src="https://github.com/Red0tt/How-To-Make-Anything-/blob/main/WEEK.2_MODIFY_3DMODEL/modified.png" width="25%" alt="unkabi"><img src="https://github.com/Red0tt/How-To-Make-Anything-/blob/main/WEEK.2_MODIFY_3DMODEL/meshmixer/m11.png" width="25%">


## 3D PRINT

**TOOLS**
- software Ultimaker
- IUP3D 3D printer

**STEPS**

Import the OBJ model into Ultimaker, adjust the model's orientation and size, ensuring there are no angles smaller than 45 degrees, and do not use support (I tried it once; the support was extremely difficult to remove and left marks). 

<img src="https://github.com/Red0tt/How-To-Make-Anything-/blob/main/WEEK.2_MODIFY_3DMODEL/3dprint/u%20(1).png" width="25%"><img src="https://github.com/Red0tt/How-To-Make-Anything-/blob/main/WEEK.2_MODIFY_3DMODEL/3dprint/u%20(2).png" width="25%">


Set up the printer and check the preview. (choose non ultimaker printer)


<img src="https://github.com/Red0tt/How-To-Make-Anything-/blob/main/WEEK.2_MODIFY_3DMODEL/3dprint/u%20(4).png" width="40%"><img src="https://github.com/Red0tt/How-To-Make-Anything-/blob/main/WEEK.2_MODIFY_3DMODEL/3dprint/u%20(5).png" width="25%"><img src="https://github.com/Red0tt/How-To-Make-Anything-/blob/main/WEEK.2_MODIFY_3DMODEL/3dprint/u%20(6).png" width="25%"><img src="https://github.com/Red0tt/How-To-Make-Anything-/blob/main/WEEK.2_MODIFY_3DMODEL/3dprint/u%20(3).png" width="25%">

Import the G-code file to the SD card, insert it into the printer, and start printing. At the beginning, pay attention to the distance between the nozzle tip and the build plate to see if it is too close. I thought it was somewhat too close, so I stopped and adjusted the distance.

Here is the process photos.


<img src="https://github.com/Red0tt/How-To-Make-Anything-/blob/main/WEEK.2_MODIFY_3DMODEL/3dprint/3d0.jpg" width="25%">
<img src="https://github.com/Red0tt/How-To-Make-Anything-/blob/main/WEEK.2_MODIFY_3DMODEL/22c9bf079cb4452e07fda1ab26ad31d1.jpeg" width="25%" alt="3dp1"><img src="https://github.com/Red0tt/How-To-Make-Anything-/blob/main/WEEK.2_MODIFY_3DMODEL/bd70603910664863ba7252fc64bc6e77.jpeg" width="25%" alt="3dp2">



**PROBLEMS AND SOLUTIONS**
1. Curling
<img src="https://github.com/Red0tt/How-To-Make-Anything-/blob/main/WEEK.2_MODIFY_3DMODEL/3d1.jpg" width="25%" alt="3dp1">


**Solution**: Because of overheating.
[curling or rough corners - simplify3d](https://www.simplify3d.com/resources/print-quality-troubleshooting/curling-or-rough-corners/)

2. Stringing or Oozing
 <img src="https://github.com/Red0tt/How-To-Make-Anything-/blob/main/WEEK.2_MODIFY_3DMODEL/3d2.jpg" width="25%" alt="3dp2">

 
 **Solution**: speed and distance is ok. Can try "retraction" setting.
[Stringing or Oozing - simplify3d](https://www.simplify3d.com/resources/print-quality-troubleshooting/stringing-or-oozing/)
   
