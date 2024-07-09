# Hexapod

My project is the Hexapod. A hexapod robot is a robot with 6 legs and it moves using servos. My hexapod can perform various movements and uses ultrasonic sensors to sense its location and look for obstacles. It uses Arduino to operate. It can either move autonomously(by itself) or by remote-control, and uses ultrasonic sensors to sense for obstacles while moving autonomously.


| **Engineer** | **School** | **Area of Interest** | **Grade** |
|:--:|:--:|:--:|:--:|
| Winston Z | Quarry Lane | Computer Science | Incoming Junior


![Headstone Image](Headshot.png)
  
<!--- # Final Milestone

**Don't forget to replace the text below with the embedding for your milestone video. Go to Youtube, click Share -> Embed, and copy and paste the code to replace what's below.**

<iframe width="560" height="315" src="https://www.youtube.com/embed/F7M7imOVGug" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe>

For your final milestone, explain the outcome of your project. Key details to include are:
- What you've accomplished since your previous milestone
- What your biggest challenges and triumphs were at BSE
- A summary of key topics you learned about
- What you hope to learn in the future after everything you've learned at BSE

-->

# Second Milestone


<iframe width="560" height="315" src="https://www.youtube.com/embed/1lfTrHyL7ps?si=SPMoC00xOcoACDT6" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>

Since my first milestone, I have implemented remote-controlled movement to my Hexapod. I can either use an IDE called "Processing" on my computer to control the robot, or I can use an app on my phone called Freenove. The IDE and app have built-in code that controls the robot, so I didn't have to program anything yet, as that will be part of my third milestone, which is autonomous movement with obstacle detection. 

My heavy battery was a problem at first. When I just velcroed it to the bottom of the frame, or the top, the weight distribution around the robot was off, causing it to be off-balance. To solve this, I used CAD and 3D printed a board to mount the battery on, and I fastened the board on top of the frame using standoffs. Another problem I had was wire management. When I was testing the remote-controlled movement before, the servos were rotating in the wrong direction, which was hindering the movement. I spent a long time trouble-shooting and thinking it was a software problem, or that I set the servos to the wrong default positions, but it turns out that I plugged the servos into the wrong pins on my control board, causing them to rotate in the wrong directions. This was due to there being so many wires in such a small space, so I have to be more careful next time.

As stated before, for my final milestone, I plan to implement an autonomous program that uses an ultrasonic sensor to detect obstacles and avoid them. Also, if I have time, I will add a robotic claw to the robot for another feature.

<img src="processingapp.png" width="425" height="425"><img src="mobileapp.jpg" width="283" height="425">
<img src="BatteryMountPrinted.jpg" width="425" height="425"><img src="hexapod.jpg" width="425" height="425">

# First Milestone


<iframe width="560" height="315" src="https://www.youtube.com/embed/yqBxWRG2DWo?si=klUiK1sxId_AdxoZ" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>

My project is the hexapod robot. For my first milestone, I have assembled the robot, which includes 18 servos, the battery, an Arduino control board, and an ESP8266 Wifi module. The Hexapod consists of 6 legs, each of which is controlled by 3 servos. The Arduino control board controls the robot. So far, the robot can't move, but I set the default positions for all the servos, so when I press the power button the servos go to their default position, allowing the robot to stand up. Initially, the default positions were out of place, and it took a lot of time to take out each servo and reset the default position to the correct place.

For the software part of this project, which will be implemented in my 2nd and 3rd milestones, I plan to code an autonomous portion, where the robot moves by itself, and also a remote-controlled portion. I will use the ESP8266 module to connect to my joystick for the remote-controlled portion in my second milestone, which is programmed through an IDE called "Processing." The autonomous portion will be implemented in my third milestone. I will install ultrasonic sensors so it can sense for obstacles, and it will run through the Arduino control board.

<img src="Battery.jpg" width="425" height="283"><img src="Controlboard.jpg" width="425" height="283">

![Headstone Image](fullhexapod.jpg)



# Starter Project

<iframe width="560" height="315" src="https://www.youtube.com/embed/q1qfZzEQkaI?si=5SK6mRZD0XwLfbRt" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>


My starter project was an RGB board that displays a color. How it works is that there are three sliders that control the color of the light on the board. Every color can be represented by 3 number values that are red blue and green. The sliders determines the value of those 3 colors and the light then displays the color.



# Schematics 

## Starter Project Diagram
![StarterProjectImage](FERTS91H8CVL1Z6.webp)

## CAD for battery mount
![CAD](batterymountcad.png)

<!---
# Code
Here's where you'll put your code. The syntax below places it into a block of code. Follow the guide [here]([url](https://www.markdownguide.org/extended-syntax/)) to learn how to customize it to your project needs. 

```c++
void setup() {
  // put your setup code here, to run once:
  Serial.begin(9600);
  Serial.println("Hello World!");
}

void loop() {
  // put your main code here, to run repeatedly:

}
```
-->

# Bill of Materials

| **Part** | **Note** | **Price** | **Link** |
|:--:|:--:|:--:|:--:|
| RGB Color Slider | Starter Project | $7.99 | <a href="https://www.amazon.com/Arduino-A000066-ARDUINO-UNO-R3/dp/B008GRTSV6(https://www.amazon.com/Soldering-Practice-Learning-Electronics-Training/dp/B0BKM3D927/ref=sxts_b2b_sx_reorder_acb_customer?content-id=amzn1.sym.f63a3b0b-3a29-4a8e-8430-073528fe007f%3Aamzn1.sym.f63a3b0b-3a29-4a8e-8430-073528fe007f&crid=31BMGGPIVNQ9Y&cv_ct_cx=tingbowie+diy+soldering+practice+kit+rgb&dib=eyJ2IjoiMSJ9.Rp97Q3zBJhWEH42AutKwzg.L_RdOYbQTJNYwxc0fgvKasLS9FnuTzz6CJIW5DKLDzg&dib_tag=se&keywords=tingbowie+diy+soldering+practice+kit+rgb&pd_rd_i=B0BKM3D927&pd_rd_r=5d377ea4-3171-4534-86a9-e77dc275c03b&pd_rd_w=dufIe&pd_rd_wg=T9sS9&pf_rd_p=f63a3b0b-3a29-4a8e-8430-073528fe007f&pf_rd_r=DZ1WERVCKDZMWWZM21J7&qid=1719859681&sbo=RZvfv%2F%2FHxDF%2BO5021pAnSA%3D%3D&sprefix=tingbowie+diy+soldering+practice+kit+rgb%2Caps%2C117&sr=1-1-9f062ed5-8905-4cb9-ad7c-6ce62808241a)/"> Link </a> |
| Freenove Hexapod Robot Kit With Controller | Main Project | $126.95 | <a href="https://www.amazon.com/Freenove-Raspberry-Crawling-Detailed-Tutorial/dp/B07FLVZ2DN/ref=asc_df_B07FLVZ2DN/?tag=hyprod-20&linkCode=df0&hvadid=692875362841&hvpos=&hvnetw=g&hvrand=18317927699298684350&hvpone=&hvptwo=&hvqmt=&hvdev=c&hvdvcmdl=&hvlocint=&hvlocphy=9032183&hvtargid=pla-2281435177618&mcid=cd179c3d961631ab9022bc5774d9b3fe&hvocijid=18317927699298684350-B07FLVZ2DN-&hvexpln=73&gad_source=1&th=1)/"> Link </a> |

