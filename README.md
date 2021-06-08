# HowsMySalute

This is a simple computer vision program to try to determine is someone's "salute" pose meets USMC standards.  Marine Corps Order (MCO) [5060.20](https://www.marines.mil/News/Publications/MCPEL/Electronic-Library-Display/Article/1867417/mco-506020-cancels-mco-p506020/) covers the requirements for a proper salute.

>When "SALUTE" is given, raise your right hand smartly in the
>most direct manner until the tip of your forefinger touches the lower part
>of the headdress above and slightly right of your right eye. Your fingers
>should be extended straight and joined with the thumb along the forefinger.
>You should be able to see your entire palm when looking straight ahead.
>Your upper arm should be parallel with the deck with the elbow in line with
>the body and your forearm at a 45-degree angle. Your wrist and hand should
>be straight, a continuation of the line made by your forearm. At the same
>time, if not in ranks, turn your head and eyes toward the person or colors
>you are saluting.

This script will track to following parts of the requirement:
* Upper Arm is parallel to the deck
* Forearm is at a 45 degree angle
* Wrist and hand is a in-line with the forearm
* Palm is visible

To prepare your system for the script, make sure python 3 is installed along with mediapipe, OpenCV, numpy and matplotlib.  The pip program can be used for the installation.
