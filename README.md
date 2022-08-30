A class that draws a fully animated rotatable wheel with sections containing strings. The wheel once spun, rotates for a certain period and stops at a random point, which gives the selected string. An example of animation in Java.
The idea behind this project was to create a Java class that designs a simple „wheel-of-fortune“ type of control, which is basically a wheel divided into n sections of the same sizes, and has a tick in the middle of the right side (3 o'clock position) which shows the current selection. The idea was that the wheel could be turned by using the mouse, and also spun with an initial speed and deceleration if the mouse button was released during the movement. Once the wheel would stop spinning, the selected string could be read based on what the tick is pointing at.

The wheel could be used for random selections from limited numbers of strings. The limit is due to the fact that the wheel is divided up to as many sections as the size of the string array, so visually it is only possible to fit in so many.

Since I am quite new to Java programming, this project was in a way intended for me to practice a little bit with Java animation
