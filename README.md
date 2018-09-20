# GameCircles

Description: This is a Game app that when a key is pressed a random color cirlce pop up in the browser along with an effect sound.

We can create a new sound by adding a new object as show below:  
    <Key>: {
    color: "<Color>",
    sound: new Howl({
    	src: ['<sound file directory>']
    	})
	}
  
The libraries used in this projects are :
Paper.js is an open source vector graphics scripting framework that runs on top of the HTML5 Canvas.

http://paperjs.org/reference/size/	
  
Howler.js is an audio library for the modern web. It defaults to Web Audio API and falls back to HTML5 Audio. This makes working with audio in JavaScript easy and reliable across all platforms.
  https://cdnjs.cloudflare.com/ajax/libs/howler/2.0.14/howler.core.min.js
