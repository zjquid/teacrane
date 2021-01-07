# the tea crane
it's a crane that makes you tea

# construction materials
* micro servo 9g SG90 (x2) (https://www.amazon.com/Tower-Pro-SG90-Analog-Servo/dp/B07B8SJQJD/ref=sr_1_25?keywords=servo+sg90&qid=1557756883&s=toys-and-games&sr=1-25)
* Arduino Genuino Uno
* A decent amount of 0.25inch thick plywood/acrylic (any material works)
* breadboard
* 2000ohm resistor
* button
* wires

# presentation materials
* toothpicks
* teabags
* cups
* hot water
* drip plate/saucer
* coaster (mug position)

# how to make it
* download the model schematics
* lasercut or use hands
* construct the thing
* flash program to arduino
* if /dev/ttyACM0 isn't recognized or whatever (sometimes happens with linux), try
``
sudo chmod a+rw /dev/ttyACM0
``
* for the breadboard, follow the picture bread.jpg and make sure the button connects to A0 on the arduino

