# TaikoController3Dprint
3D printed taiko controller Arduino based for PC. 

I started on this project as taiko drum controllers are expensive (~$100+) and this project costed me less than 10$ (I already have some tools).

If possible I would recommend to make this using wood as it can be scaled bigger.
### 3D Model

<img src="https://github.com/leCloudy/TaikoController3Dprint/assets/50788385/0d0bc900-a29c-46b2-836d-6ee7e5822be4" height="300">

<img src="https://github.com/leCloudy/TaikoController3Dprint/assets/50788385/b5a6011c-7d6f-41c3-adfd-aa41abcbe998" height="300">

Modelled in Fusion360. I provided the f3d files and the STL files if you want to edit them.

### Controller
<img src="https://github.com/leCloudy/TaikoController3Dprint/assets/50788385/9831c36f-6629-447b-86c7-6e679e99b356" width="500">

#### Circuit
<img src="https://github.com/leCloudy/TaikoController3Dprint/assets/50788385/183959c8-d305-400a-ae4f-0dec97b76d8e" height="500">

<img src="https://github.com/leCloudy/TaikoController3Dprint/assets/50788385/da023cb1-8163-4347-96fa-f277b97f3095" height="500">

I ended up attaching the piezo using blutack to the centre of the back of the don and ka plates

### Printing instructions
https://github.com/leCloudy/TaikoController3Dprint/assets/50788385/0afff80c-5fd6-49ac-9b99-cfe1d718ff6b

As the piezo are used to detect vibration, using a 100% infill should help but it worked for me using 40%.
This was printed using an ender3v2. The dimensions are maxed for the print bed, but if you have a bigger printer you can scale it up.

### Items
1) Arduino Micro
2) M5x25 with M5 nuts (x12)
3) 10mm Piezo Ceramic Wafer (x4)

### Code
Referenced from: https://github.com/LuiCat/ArduinoTaikoController/tree/master
Calibration needs to be accurate as the other piezos might false trigger.

