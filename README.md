# The Great Voice Driven Turtle Race
## A voice-driven game in JavaScript using audio input as control via the Google+ Hangout API

[![ScreenShot](http://img.youtube.com/vi/AK4hgwO5zm0/0.jpg)](http://youtu.be/AK4hgwO5zm0)

### Overview
This is a JavaScript-based demo using v.0.2 of the [Google+ Hangout API](https://developers.google.com/+/hangouts/reference). I implemented an idea I saw of a racing game where the players controlled on-screen cars with their voices; I wrote mine, a turtle race, in [an XML gadget](http://dl.dropbox.com/u/12019700/hangouts-api/gadget.xml).

The secret sauce is hooking into and handling the _onVolumesChanged_ event and manipulating the user's audio, which I did to control the turtle's rate of acceleration. I also emulated [Jonathan Beri's demo](https://plus.google.com/+JonathanBeri/posts) that he did in a tech talk for visually monitoring a user's input audio level.

Have fun with it! :)

_Disclaimer: I snagged the graphics in a Google Image search, but I'm not publishing this software commercially. Besides, the turtle is too cute NOT to use._

---

Check out my book, [Designing and Developing for Google Glass](http://www.amazon.com/Designing-Developing-Google-Glass-Differently/dp/1491946458), by O'Reilly & Associates. **Thanks for your support! :)**