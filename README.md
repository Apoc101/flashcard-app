# Flashcard app

Available at https://apoc101.github.io/flashcard-app.

This was made to exercise trivia and general knowledge, as well as to test my capabilities with React and APIs.

The way that it works is that it deserializes JSONs taken from the [open trivia API](https://opentdb.com/) into objects that are then displayed on divs, aka cards; 
then you can click on the div to change it's bool "flipped" value from false to true and viceversa, hiding content and displaying it depending on its state.

> **Warning**: IT DOES NOT WORK ON FIREFOX; for some reason when you flip the card it just refuses to hide the content on the other side so it layers it all on the div and is unreadable.

I will try to fix this, but I'm really not sure what causes it since I'm using simple CSS rules of hiding and displaying content based off elements' states.

I did follow a tutorial for a small part of this, mainly because my React bigbrainism is not that big as of the writing of this app, so I needed some assistance on a few things like deserialization.
