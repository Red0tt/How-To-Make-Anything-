# CONCEPT
The future I envision is one with severe noise pollution, and the product is headphones that allow selective hearing of specific sound segments, so they can block out specific sounds. The box I made is the engine on the headphone (The actual position is on the outside of the ear cups). 

# DESIGN
I came across a pair of headphones online—so cool, exactly what I've been looking for. The oval-shaped part on them is just the right spot to house the noise-processing engine. I think future headphones might not have headbands or the usual earcups, so I designed an engine instead. Because of the product will be worn on a person's head, so it should be as portable as possible.


# MAKE 3D MODEL
First, I looked for 3D models on the official Arduino website but found only drawings. So, I went to printables.com to download 3D models. During this process, I learned how the creators designed assemblable Arduino boxes. I thought the idea in the diagram was great—it could secure the Arduino and assemble the box without screws (since I didn't have screws prepared at the time), so I learned this method. 

<img width="50%" alt="屏幕截图 2025-10-14 091627" src="https://github.com/user-attachments/assets/b0561555-01af-4c93-a2d3-66ae6478d509" />

I recorded the steps in Rhino in pictures.

<img width="50%" alt="屏幕截图 2025-10-11 101541" src="https://github.com/user-attachments/assets/555b6159-aa0b-4fd3-ae43-f32c62a180d6" />

<img width="50%" height="1368" alt="屏幕截图 2025-10-11 110226" src="https://github.com/user-attachments/assets/948d8afa-e053-446b-9504-d199b4b1dd0f" />

<img width="50%" height="1368" alt="屏幕截图 2025-10-11 115610" src="https://github.com/user-attachments/assets/40e363cf-0433-4fd5-811f-b08701f7b4bc" />

<img width="50%" height="1368" alt="屏幕截图 2025-10-11 121202" src="https://github.com/user-attachments/assets/bfc1ca07-0c33-444d-88fa-8a0f7d81aed4" />

<img width="50%" height="1368" alt="屏幕截图 2025-10-11 130317" src="https://github.com/user-attachments/assets/880b5855-b23b-4124-b3b8-30e1202b0fe2" />

<img width="50%" height="1368" alt="屏幕截图 2025-10-11 130350" src="https://github.com/user-attachments/assets/559099d7-2d2a-408c-abd8-cbfb8e08cec4" />

<img width="50%" height="1368" alt="屏幕截图 2025-10-11 135047" src="https://github.com/user-attachments/assets/e04e42a7-161f-4e02-acf6-05b24a847c4e" />


Initially, I wanted to modify an existing box from online, but found that their models couldn't be easily altered. Therefore, I decided to create a box from scratch in Rhino, because I thought Rhino would allow for more precise operations. After a series of steps, the first model I built had a wall thickness of 0.8mm and holes with a diameter of 2.8mm. 


Later, I went to the FabLab, where Saverio seriously pointed out (a popular Chinese internet phrase meaning 'emphatically noted') that the horizontal structures in 3D printing are very fragile. These posts that pass through and secure the Arduino can only be used once; if disassembled, they would break. Saverio suggested that I remove the posts and just have holes, using specific types of screws for fixation. Alternatively, if I wanted to prevent the Arduino from vibrating up and down inside the box, I could turn the posts into supports, so the Arduino would be pressed against the box and unable to move. I first modified it to have holes because my box was inherently very flat. Thus, the first print was done. I set it up in Bambu Studio, sliced it, and Saverio helped me print it. The first time failed because the printed filament didn't adhere well to the build plate, but the second time was normal. However, this print had very thin walls. Saverio demonstrated how fragile it was and reminded me to be careful not to put pressure on these fragile pieces. Unfortunately, even though I placed them in the front of my backpack, they still broke under the pressure of other items inside the bag.
<img width="50%" src="https://github.com/user-attachments/assets/6bae6400-6df6-4277-9ff7-1de33f3e6a6e">
<img width="50%" src="https://github.com/user-attachments/assets/136fcb3c-0ce7-411e-8d21-c7f787c69142">

Therefore, I increased the wall thickness to 3mm. Since the lid and base of the previous box couldn't align properly, I designed a step-and-groove system with raised and recessed edges to ensure precise fitting. Regrettably, as I don’t have the habit of saving incremental versions while working, I realized these modifications almost required rebuilding the model from scratch—so that’s what I did. Additionally, I slightly reduced the size of the openings reserved for the Arduino ports, so that the screw holes and these port openings would be clearly separated.

Meanwhile, considering the use of the laser cutter, I initially planned to cut an acrylic sheet to snap directly into place, but it would have easily fallen out. Saverio suggested that I make the acrylic piece larger, leave mounting holes, and secure all components together using screws.

Right before the second print, my model ran into another issue. For example, the fillets had somehow turned into sharp corners. The solution was to reconstruct that edge from scratch. Previously, I had used the "Blend Surface" tool, but this time I used "Create Surface from Curves." Thankfully, that fixed the problem.

<img width="50%" alt="屏幕截图 2025-10-13 125311" src="https://github.com/user-attachments/assets/93f15abb-a4df-42e7-93d2-8ff25146c137" />



After printing and assembling everything, I noticed that only the front interface holes were a bit too small—everything else fit well. Perhaps while modifying the interface holes, I should also account for the increased wall thickness and adjust the height accordingly to reserve proper space for the Arduino ports. Finally, I manually sanded away the excess material.
<img width="50%" src="https://github.com/user-attachments/assets/bb5f245f-9614-4c09-a2fe-7888634856d3" />
<img width="50%" src="https://github.com/user-attachments/assets/a9f9ea5c-24d0-4423-be93-75a7bc83ad22" />

3dprint consideration: do i need support? will it be stronger in this way? never print column.


here is my files.\


