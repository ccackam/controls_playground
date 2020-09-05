# Controls Playground

This is a MATLAB app that can be used to simulate a spring mass damper system under open loop, PID, and Full State Feedback Control. A simple user interface allow for adjusting the inputs to the system on the fly. Several plots can be used to see the response of the system. An animation of the response can allow be played.

## Useful Links

This application was made as part of a video series to teach Linear Controls theory. This was made to augment AERO 625 at Texas A&M university for those who have not had undergraduate controls courses. The videos can be found here:

https://www.youtube.com/playlist?list=PL-t7_t3CzJkMvHt0An0ZTc5OAfXc8Wwkz

The specific video introducing this application can be found here:

https://youtu.be/6I-UxwgsnPU

Much of this course and the comments in the code used to create this app are drawn from the textbook The Control Book, by Randy Beard, Tim McLain, and Cammy Peterson. A fee copy can be found here:

https://controlbook.byu.edu

The Github repository for this application is here:

https://github.com/ccackam/controls_playground

The latest release of this application can be found here:

https://github.com/ccackam/controls_playground/releases

## Instalation

Almost no installation is required. As long as you have the MATLAB, just download the .mlappinstall file from the latest release and double click to install the file.

### Requirments

MATALB - https://www.mathworks.com/products/matlab.html

If you are a student, check with your school to see if they offer MATLAB to their students for free.

### Download

Download the latest .mlappinstall file from here: https://github.com/ccackam/controls_playground/releases

### Install

Double click the installation file.

## Usage

Using this application is relatively intuitive.

### Opening

To open the application open MATLAB and open the App menu at the top.

From the drop down select the Controls Playground application.

### Operation

To change the simulation simply move the sliders. Pressing a 0 button will move that slider back to 0. Pressing the R button will reset the slider to some default value. There are several different categories of sliders. Including:

- Intial Conditions
- System Parameters
 - Mass
 - Spring Constant
 - Damping Constant
- Saturation Limits
- Control Gains/Tuning Parameters
- Integrator Anti-windup Limits

The plots in the center of the page plot various system variables. The diagram at the top of the page can be used to animate the system.
