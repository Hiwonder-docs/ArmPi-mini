# 2.Quick User Experience

<p id="anchor_1"></p>

## [1. APP Installation and Connection ]()

## 2. App Control

User can use app “WonderPi” to control ArmPi mini. This lesson will introduce the specific operation methods of each game.

### 2.1 Getting Ready

(1) Firstly, calibrate the picking position of ArmPi mini.

Please refer to the content in “[Getting Ready/7.Position Calibration]()” to learn about the specific operation steps.

(2) Install app “WonderPi” and connect the robotic arm.

Please refer to the content in “[Quick User Experience/2. APP Control ]()” to learn about the specific operation steps.

### 2.2 Start Game

There are five games in app including remote control, color recognition, color tracking, target tracking and intelligent stacking.

<img src="../_static/media/chapter_2/section_2/image1.jpeg"  alt="loading" />

The following list briefly introduces each game mode.

| Icon | Game mode | Instruction |
|:--:|:--:|:--:|
| <img src="../_static/media/chapter_2/section_2/image2.png" style="width:0.59055in;height:0.59233in" /> |    Robot Control     | Control the movement of robot arm |
| <img src="../_static/media/chapter_2/section_2/image3.png" style="width:0.59055in;height:0.59055in" /> | Color Recognition | It can recognize red, green and blue. When the target color is recognized, ArmPi mini will execute the corresponding action. |
| <img src="../_static/media/chapter_2/section_2/image4.png" style="width:0.59055in;height:0.59227in" /> | Color Sorting | It can recognize red, green and blue. When the target color is recognized and place the block in the middle of the gripper, ArmPi mini will pick the object and place it to the corresponding position. |
| <img src="../_static/media/chapter_2/section_2/image5.png" style="width:0.59028in;height:0.63125in" /> | Target Tracking | It can recognize red, green and blue. When the target color is recognized, ArmPi mini will pick the object and place it to the corresponding position. |
| <img src="../_static/media/chapter_2/section_2/image6.png" style="width:0.59028in;height:0.58542in" /> | Intelligent Stacking | When the target block is recognized, robot arm will pick and stack the blocks in the stacking area. |

The following list introduces the functions of the navigation bar in game selection interface. 

| Icon | Instruction |
|:--:|:--:|
| <img src="../_static/media/chapter_2/section_2/image7.png" style="width:0.39306in;height:0.39306in" /> | Back to the connection interface. |
| <img src="../_static/media/chapter_2/section_2/image8.png" style="width:0.39306in;height:0.39306in" /> | Adjust color threshold. If want to learn about the specific adjustment method, please refer to the content in “Quick User Experience->3.Color Threshold Adjustment”. |
| <img src="../_static/media/chapter_2/section_2/image9.png" style="width:0.3937in;height:0.3937in" /> | Display the window of Hiwonder information |

**2.2.1 Robot Control** 

:::{Note}
After entering the game “Remote control”, ArmPi mini will stand straight up. Therefore, please make sure there is no obstacle in front of the robot before entering game.
:::

Select “Robot Control” to enter this game. The interface is divided into two parts:

(1) The left side is servo control area.

(2) The right side displays the image returned by camera.

<img src="../_static/media/chapter_2/section_2/image10.jpeg"  />

**① Navigation Bar Icon Function**

The button function of navigation bar is explained in following list which is also applicable to other games.

<table  class="docutils-nobg" style="margin:0 auto" border="1">
<colgroup>
<col style="width: 21%" />
<col style="width: 78%" />
</colgroup>
<tbody>
<tr>
<td style="text-align: center;"><strong>Icon</strong></td>
<td style="text-align: center;"><strong>Function Instruction</strong></td>
</tr>
<tr>
<td style="text-align: center;"><img src="../_static/media/chapter_2/section_2/image7.png" style="width:0.39306in;height:0.39306in" /></td>
<td style="text-align: left;">Back to the previous interface.</td>
</tr>
<tr>
<td style="text-align: center;"><img src="../_static/media/chapter_2/section_2/image11.png" style="width:0.3937in;height:0.3937in" /></td>
<td style="text-align: left;"><p>Capture and save the returned image to photo.</p>
<p>Click on <img src="../_static/media/chapter_2/section_2/image12.png" style="width:0.47222in;height:0.47431in" />to check the image.</p></td>
</tr>
<tr>
<td style="text-align: center;"><img src="../_static/media/chapter_2/section_2/image13.png" style="width:0.3937in;height:0.39685in" /></td>
<td style="text-align: left;">Hide the navigation bar.</td>
</tr>
<tr>
<td style="text-align: center;"><img src="../_static/media/chapter_2/section_2/image9.png" style="width:0.3937in;height:0.3937in" /></td>
<td style="text-align: left;">Display the window of Hiwonder information.</td>
</tr>
</tbody>
</table>



**② Game Interface Icon Function**

<table class="docutils-nobg" border="1">
<colgroup>
<col style="width: 35%" />
<col style="width: 64%" />
</colgroup>
<tbody>
<tr>
<td style="text-align: center;"><strong>Icon</strong></td>
<td style="text-align: center;"><strong>Function instruction</strong></td>
</tr>
<tr>
<td style="text-align: center;"><img src="../_static/media/chapter_2/section_2/image14.png" style="width:1.5748in;height:0.36557in" alt="loading" /></td>
<td style="text-align: left;"><p>Drag<img src="../_static/media/chapter_2/section_2/image15.jpeg" style="width:0.29375in;height:0.31181in" alt="loading" />icon to “close” or “Release” side to control the gripper to open or close.</p>
<p>Click <img src="../_static/media/chapter_2/section_2/image16.jpeg" style="width:0.33056in;height:0.32708in" alt="loading" />and<img src="../_static/media/chapter_2/section_2/image17.jpeg" style="width:0.33681in;height:0.34028in" alt="loading" />to slightly adjust the servo rotation.</p></td>
</tr>
<tr>
<td style="text-align: center;"><p><img src="../_static/media/chapter_2/section_2/image18.png" style="width:in;height:in" alt="loading" /></p>
<td style="text-align: left;"><p>Drag<img src="../_static/media/chapter_2/section_2/image15.jpeg" style="width:0.29375in;height:0.31181in" alt="loading" />icon to “Forward” or “Backward” side to control the corresponding servo to rotate forward or backward.</p>
<p>Click<img src="../_static/media/chapter_2/section_2/image16.jpeg" style="width:0.33056in;height:0.32708in" alt="loading" />and<img src="../_static/media/chapter_2/section_2/image17.jpeg" style="width:0.33681in;height:0.34028in" alt="loading" />to slightly adjust the servo rotation.</p></td>
</tr>
<tr>
<td style="text-align: center;"><img src="../_static/media/chapter_2/section_2/image21.jpeg" style="width:1.5748in;height:0.38574in" alt="loading" /></td>
<td style="text-align: left;"><p>Drag<img src="../_static/media/chapter_2/section_2/image15.jpeg" style="width:0.29375in;height:0.31181in" alt="loading" />icon to “Left” or “Right” side to control ID6 servo to rotate to left or right.</p>
<p>Click<img src="../_static/media/chapter_2/section_2/image16.jpeg" style="width:0.33056in;height:0.32708in" alt="loading" />and<img src="../_static/media/chapter_2/section_2/image17.jpeg" style="width:0.33681in;height:0.34028in" alt="loading" />to slightly adjust the servo rotation.</p></td>
</tr>
<tr>
<td style="text-align: center;"><img src="../_static/media/chapter_2/section_2/image22.jpeg" style="width:1.57431in;height:0.99236in" /></td>
<td style="text-align: left;">Display the real-time returned image.</td>
</tr>
</tbody>
</table>



**2.2.2 Color Recognition**

:::{Note}

* Please start this game under a moderate environment light, too bright or too dark light will influence the normal recognition affect.

* After starting game, please ensure there is no other object containing the recognition color except the target object within the camera frame, otherwise the recognition result will be affected.

  :::

Firstly, click “Color Recognition” to enter game interface. The interface consists of two parts.

(1) At the left side, you can start or stop game, and set color threshold.

(2) The right side of interface displays the real-time returned image.

<img src="../_static/media/chapter_2/section_2/image23.jpeg"  alt="loading" />

**① Icon Function**

| Icon | Function |
|:--:|:--:|
| <img src="../_static/media/chapter_2/section_2/image24.jpeg" style="width:1.1811in;height:0.33292in" alt="loading" /> | Start or stop game |
| <img src="../_static/media/chapter_2/section_2/image25.png" style="width:1.1811in;height:0.48474in" /> | Adjust color threshold. <br/>You can refer to “4.Start ArmPi mini/ 3.Color Threshold Adjustment” to learn about the specific adjustment method. |
| <img src="../_static/media/chapter_2/section_2/image23.jpeg" style="width:1.5748in;height:0.99512in" alt="loading" /> | Display the real-time image returned by camera. The current recognized color is displayed in the lower left corner. |

**② Operation Instruction and Realization Outcome**

(1) Click “Start Recognition” and position red, blue or green object in camera frame.

(2) When the red object is recognized, robot arm will nod. When the blue or green object is recognized, robot arm will shake its head.

**2.2.3 Color Sorting**

:::{Note}

* Before starting game, you need to firstly calibrate the gripping position of the robot to avoid influencing the game effect. 

* Please start this game under a moderate environment light, too bright or too dark light will influence the normal recognition affect.

* After starting game, please ensure there is no other object containing the recognition color except the target object within the camera frame, otherwise the recognition result will be affected.

  :::

Firstly, click “Color Sorting” to enter game interface. The interface consists of two parts.

(1) At the left side, you can start or stop game.

(2) The right side of interface displays the real-time returned image.

<img src="../_static/media/chapter_2/section_2/image1.png"  alt="loading" />

**① Icon Function**

| Icon | Function |
|:--:|:--:|
| <img src="../_static/media/chapter_2/section_2/image26.png" style="width:in;height:in" alt="loading" /> | Start or stop game |
| <img src="../_static/media/chapter_2/section_2/image25.png" style="width:1.1811in;height:0.48474in" /> | Adjust color threshold. <br/>You can refer to “Quick User Experience/3.Color Threshold Adjustment” to learn about the specific adjustment method. |
| <img src="../_static/media/chapter_2/section_2/image26.jpeg" style="width:1.5748in;height:0.98604in" alt="loading" /> | Display the real-time image returned by camera. The current recognized color is displayed in the lower left corner. |

**② Operation Instruction and Realization Outcome**

(1) Click “Start sorting”, and put the colored block in camera frame.

(2) When the block is recognized, the gripper will open automatically.

(3) Position the block in the middle of the gripper, and then the gripper will pick the block and place it in the corresponding position.



**2.2.4 Target Tracking**

:::{Note}

* Please start this game under a moderate environment light, too bright or too dark light will influence the normal recognition affect.

* After starting game, please ensure there is no other object containing the recognition color except the target object within the camera frame, otherwise the recognition result will be affected.

  :::

Firstly, click “Target Tracking” to enter game interface. The interface consists of two parts.

(1) At the left side, you can start or stop game.

(2) The right side of interface displays the real-time returned image.

<img src="../_static/media/chapter_2/section_2/image27.jpeg"  alt="loading" />

**① Icon Function**

<table class="docutils-nobg" border="1">
<colgroup>
<col style="width: 35%" />
<col style="width: 64%" />
</colgroup>
<tbody>
<tr>
<td style="text-align: center;"><strong>Icon</strong></td>
<td style="text-align: center;"><strong>Function</strong></td>
</tr>
<tr>
<td style="text-align: center;"><img src="../_static/media/chapter_2/section_2/image28.jpeg" style="width:1.1811in;height:0.27587in" alt="loading" /></td>
<td style="text-align: left;">Start or stop game</td>
</tr>
<tr>
<td style="text-align: center;"><img src="../_static/media/chapter_2/section_2/image29.jpeg" style="width:0.7874in;height:1.10977in" alt="loading" /></td>
<td style="text-align: left;"><p>Select target color.</p>
<p>“R” is red, “G” is green and “B” is blue.</p></td>
</tr>
<tr>
<td style="text-align: center;"><img src="../_static/media/chapter_2/section_2/image30.jpeg" style="width:0.7874in;height:0.71739in" alt="loading" /></td>
<td style="text-align: left;">Display the current tracked color</td>
</tr>
<tr>
<td style="text-align: center;"><img src="../_static/media/chapter_2/section_2/image27.jpeg" style="width: in;height: in" alt="loading" /></td>
<td style="text-align: left;">Display the real-time image returned by camera. </td>
</tr>
</tbody>
</table>



**② Operation Instruction and Realization Outcome**

(1) Firstly, select the color to track in color selection area. Here take red for example, click “R”.

(2) Then click “Start tracking”, and position the red block in camera frame.

(3) When the block is recognized, robot arm will move with the block.



**2.2.5 Intelligent Stacking**

:::{Note}

* Please start this game under a moderate environment light, too bright or too dark light will influence the normal recognition affect.

* After starting game, please ensure there is no other object containing the recognition color except the target object within the camera frame, otherwise the recognition result will be affected.

  :::

Firstly, click “Intelligent Stacking” to enter game interface. The interface consists of two parts.

(1) At the left side, you can start or stop game, and adjust color threshold.

(2) The right side of interface displays the real-time returned image.



<img src="../_static/media/chapter_2/section_2/image31.jpeg"  alt="loading" />

**① Icon Function**

| Icon | Function |
|:--:|:--:|
| <img src="../_static/media/chapter_2/section_2/image44.png" style="width:1.1811in;height:0.30725in" alt="loading" /> | Start or stop game |
| <img src="../_static/media/chapter_2/section_2/image25.png" style="width:1.1811in;height:0.48474in" /> | Adjust color threshold. <br/>You can refer to “Quick User Experience/ 3.Color Threshold Adjustment” to learn about the specific adjustment method. |
| <img src="../_static/media/chapter_2/section_2/image31.jpeg" style="width:in;height:in" alt="loading" /> | Display the real-time image returned by camera. The current recognized color is displayed in the lower left corner. |

**② Operation Instruction and Realization Outcome**

(3) Click “Start stacking”, and place the colored block within detection area.

(4) When the block is recognized, robot arm will pick the block and place it in stacking area.

(5) The stacking area can stack up to three blocks. When the upper limit is reached, please remove the blocks in the stacking area before the next black is stacked.

## [3. Adjust Color Threshold]()

