[comment]: <> (Title: title)
[comment]: <> (Description: description)
[comment]: <> (Cover image path: image name)


# Gretchen

## Idea

After growing tired of Alexa, I decided to make my own home assistant. Meet Gretchen. Gretchen will have a screen that rotates to face the user and access to various home utilities such as lights, thermostat, speakers, and ect. . . I will also add features such as a network attached storage system and add blocking.

I will be using a Raspberry PI5 as Gretchen's primary computer.  

## Rotating Screen

I currently have my PI5 attached to a screen so I will have to rotate the entire pi. 

### Parts

I'm going to use parts that I have from various other projects:

I have the PI5 and screen, a WYZE cam, and a Servo attached to a Node MCU which gives me basic control of the Servo through HTTP requests. I recognize that this project could be simplified by having a screen which is not attached to the PI, or the PI boating from an SD card rather than an SSD, or attaching the Servo directly to the PI5 rather than Node MCU. 


### Rotation 
My first concern is that the PI5 will be too heavy for my Servo.