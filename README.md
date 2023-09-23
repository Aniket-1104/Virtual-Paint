# Virtual-Paint
Detects the colour you are holding  and sketch your ideas on screen with that colour. Have fun !!

STEPS TO RUN:
- Copy the code in any python editor.
- You will have to install opencv-python and numpy packages.
  <br>
  `pip3 install opencv-python`
  <br>
  `pip3 install numpy`
  <br>
- By default the application will detect blue color to use.
- If you want to add any new colours you can do that by running colorPicker.py file and obtaining the HSV value for that specific colour.
- Add the min max HSV value in the the myColors array and the color in myColorValues array in the VirtualPaint.py file

---
EXAPMLE:

to add green colour:

>min max HSV value = 57, 76, 0, 100, 255, 255
>
>green colour = 0, 255, 0

therefore new array values:
>myColors = [[90,48,0,118,255,255], [57,76,0,100,255,255]]
>
>myColorValues = [[255,0,0], [0,255,0]]

