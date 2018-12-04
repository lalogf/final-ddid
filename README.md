# Slides clicker

Arduino passes slides and turn on and off lights based on video being played.

## Idea

After being in some classes where teachers need to walk from one extreme to the
other in a classroom just to turn on or turn off the lights when playing a video
during a class, this idea started: `having slides clicker that can save the
teachers for these walks and rather turn on and turn off the ligths.`

## Prototype

For the prototype I used a classroom toy set and a foldable studio with a 
micro-USB light.

![clicker](https://lh4.googleusercontent.com/-VLY3fDEgj0Tv3Z4GwnSGyKXrH1cpsKyomYmP8ld8AhbuDzs-lFWlGocNQTAZ06whDe04CTk2HApazTdA_DTm9wYrrZqzbO8QdiYJYjCY8XwPjqjq4KbZkXrOYZB4Bkg5_Bs9jP7_7U) 

The micro-usb light is connected to the system through the Arduino.

![Classroom](https://lh5.googleusercontent.com/kTOCAK0HWca0IuQfXd9zbg-kFaHq3uwh577_c_qVHtah_Rd8lBFT4A6nuEBUKqxRzCK1-lD7RVqRtSqHfYrV_OVfQmIYn0X7zvPSswuDMrYogB4boVo2MC5n3d02W4nc9QRx3ukfv94)

For the interaction between the arduino and the slides I used:

- For the Slides: [Reveal js](https://github.com/hakimel/reveal.js/)
- For the Video: [Wistia and its well documented API](https://wistia.com/support/developers/player-api#events)
- For real time communication between the arduino and the interface: [socket.io](https://socket.io/)

## Video of prototype working

You can see the video in this [link](https://lalogf.wistia.com/medias/wrha75uv4z).

## Code

The rest of the code for the project can be found in this repository.