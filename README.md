# Project-H

Instructions:
1. Make sure you have the required equipment
          1.1 Breadboard (optional but useful)
          1.2 Jumper cables (a mix of male-male, male-female, female-female)
                    1.2.1 Try to keep black to ground, red to voltage, and blue/green for data.
          1.3 Particle Argon
          1.4 Two resistors
          1.5 LED
          1.6 Particle Wifi module
          1.7 Usb cable for the particle argon
2. Make sure you are signed onto and understand
          2.1 Webhooks
          2.2 ThingSpeak (website where it will upload data)
          2.3 Particle (web ide and concepts in the site)
          2.4 email
          2.5 mobile phone
3. Creation: See report or the following link to have an idea of how it works: https://youtu.be/u_6qosnmbfM 
4. How to run
          4.1 Copy the code from this github to particle ide
          4.2 change the overall time variation to your chossing example 20 -> 300 (whihc is 5 minutes)          
          4.3 follow this link for an idea of webhooks https://docs.particle.io/tutorials/device-cloud/webhooks/#your-first-webhook 
          4.4 When flashing there will be some blinking from the LED, after the first 2 blinks put your phones light in front of the sensor
          4.5 when it flashes twice again move th flash away from the photo sensor
          4.6 after that move the flash back in place and simulate the work place.
          4.7 Check particle entries to make sure it is all running correctly adn there is an output. 
5. See the output
          5.1 If the led goes red after you leave the camera in front of the sensor for the selected period of time than it is working
          5.2 if the entry is being updated with 1 as a value with presense as a event than the webhook is working.
          5.3 if you recive an email after setting up the IFTTT, which should be if presense occurs send email to (your email) than that works.
