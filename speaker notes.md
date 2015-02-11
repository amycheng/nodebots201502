# Nodebots 2/2015 

- I am web developer at the Brooklyn Museum, and in my free time I liked to tinker with hardware to make art

- using the FadeCandy to make LED art
- the FadeCandy is great because it makes it easier to be more expressive (i.e. productive) with LEDS

- essentially plug and play (as long as your physical wiring is correct!)
	- i had issues where my connection power was a bit loose
	- wasn’t sure which power supply I needed (just realized I was bad at reading comprehension)

## Arduino vs FadeCandy 

### Arduino
- define pin
- turn pin on and off

### FadeCandy
- start the Fade Candy server
- initialize open pixel control 
- map LEDS to pixels
- “draw” the pixels

## How the FadeCandy works
- runs the FadeCandy server, which listens to your code
- What is this LED suppose to do?
- uses open pixel control (kinda like the machine code that controls the LEDS) 
- seems more complicated, but starting the servers is just one line of code and it’s much quicker to do something cool than it is with Arduino code 
- since Fade Candy is compatible with a lot of languages, chances are you’re able to use a language you’re already familiar with. 

## Pros of Fade Candy
- use all kinds of different programming languages to use the FadeCandy
	- which means you can bring in other libraries to do something cool (i.e. math libraries)
- a single FadeCandy can drive ALOT of LEDS
- hardware magic creates smoother color transitions and gives you easier control over LEDS

## Disadvantage
- can’t run the code on the FadeCandy itself 
	- needs a computer to run the FadeCandy server (more on this later)

## Getting Started
1. get a FadeCandy, some WS2812 LEDs (i.e. Adafruit NeoPixels), smart LEDS
2. Download the FadeCandy library
3. Run the server
4. Write some code!


## Using Node.js
- Note: the examples are pretty great

### Visual Model of mapping pixels
- [run this code] 
- [walk through code]
- code is similar to Arduino code, in that 
### Abstract Model of mapping pixels
- [run this code]
- [walk through code]
- there’s a convenience method for generating a model, which is just a JSON object of what looks like to be coordinates of LEDs in geometrical space
