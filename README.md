# Smart_Draw

## What?
The aim of Smart Draw is to provide the experience of a Smart Board without the need of having one. 

## Why?
Smart Draw can be used to draw on the projector screen/normal screen by making some hand gestures. SmartDraw save the cost having an actual smart board.

## Who?
Although it can be used by anyone it is mainly developed for free educational institutes(NGOs). It would help them in saving cost associated with a smart board. They ony need a projector and a camera.

## How?
Smart Draw makes use of YoloV4 to detect Hand Gestures and DeepSORT to track user's hand. 

First the YoloV4 model will detect Hand Gestures in the video frame and then pass it to the DeepSORT algorithm to track the hand and draw on the screen.

## Available Gestures:
### To Draw:
![draw](https://github.com/Pratham-Pandey/Smart_Draw/blob/main/resource/draw.jpg)


### To Erase:
![erase](https://github.com/Pratham-Pandey/Smart_Draw/blob/main/resource/erase.jpg)

## Demo:

![demo](https://github.com/Pratham-Pandey/Smart_Draw/blob/main/resource/bg8.jpg)


## Installation:
* Clone this Repository using ``` https://github.com/Pratham-Pandey/Smart_Draw.git ``` .
* Install "requirements.txt" using: ``` pip install -r requirements.txt ``` .
* Run "draw_custom_object_tracker.py".
