### Homework 5 (due Sunday, October 16, 2016)

This week's assignment is a review of what we did in class, plus an extra lab assignment to learn about `analogWrite`, an approximately analog version of `digitalWrite`.

In order to complete this week’s homework assignment you will need to go to the Hybrid Lab and check out an Arduino and associated components. Please allow sufficient time for this!

  1. Modifying what we did in class
    1. Rebuild the circuit that we built in class, consisting of a potentiometer and a servo motor. Test first the potentiometer using the `analogReadSerial` example (file->examples->basics) and then test the servo using the `knob` example (file->examples->servo->knob).
    2. If your servo motor seems unhappy near the ends of the range, modify the parameters to the `map()` function to limit its range.
    3. Add a red LED and a green LED to any two digital pins. Don’t forget the resistors (any value between 300 and 1000 ohms). Test each of those LEDs using the blink example.
    4. Modify the knob example so that the the red LED lights when the servo is between angles 0 and 20, and light the green LED when the servo is between angles 160 and 180. If you modified the range use your numbers instead. Hint: the `if()` statement in Arduino works just like the `if()` statement in P5.js.
    5. **Upload your code to your Github repository**
    6. **Hand-draw a schematic of your completed circuit, take a picture, and upload the picture to your Github repository**
  
  2. Learn about `analogWrite()`
    1. Read the `analogWrite()` [reference page](https://www.arduino.cc/en/Reference/AnalogWrite).
    2. Optional: If you are curious about PWM read (this explanation)[https://www.arduino.cc/en/Tutorial/PWM].
    3. Follow [this tutorial](https://www.arduino.cc/en/Tutorial/AnalogInOutSerial) to use a potentiometer to control the brightness of an LED.
    4. Answer these questions, and upload them to your Github repository:
      1. Why can you only use certain pins for `analogWrite()`?
      2. What is the range the map() function maps the value to? Why this range?
      
   3. Email us a link to your Github by Sunday night.

