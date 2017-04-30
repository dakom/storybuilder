# Storybuilder

Currently a placeholder, concept is an interactive editor which follows story structure advice to enable building a story organically

On a technical level it would be built around a series of Protobufs that describe the structure at different level

For example - there could be a Beat protobuf which contains the following criteria:

* Character Objective
* Initial Value at stake
* Expected Reaction
* Actual Reaction
* New Value

Each of those could be combined and augmented within a Scene protobuf, and those into a Sequence protobuf, those into an Act protobuf, and ultimately the entire Story itself.

Technically - the frontend would be web-based and could use some js graphing tool or maybe three.js to allow simultaneous and interweaving lines

References: 
*  Robert McKee's Story
*  Pixar in a Box Storytelling
